---
name: reva-course-reviewer
description: >-
  Review and verify a completed REVA SoCSE Course File against the Course Design
  Checklist, the curriculum strategy, the curriculum structure/map, and
  university OBE best practices — producing a per-item pass/fail verdict with
  severities and concrete fixes, plus an overall READY / NOT READY verdict. Use
  whenever a faculty member or reviewer wants to review, verify, audit,
  critique, or quality-check a drafted course design / course file / syllabus,
  or asks "is my course ready", "check my course file against the checklist",
  "verify my course design", "what's missing in my course", "review my course
  before BoS", or wants reviewer-style feedback. Works on .md or .docx course
  files. Do NOT use to author a course from scratch — use reva-course-designer
  for that.
---

# REVA Course Reviewer (checklist verification)

Independently verify a completed Course File and produce an actionable, evidence-based verdict. The bar is the **2026 dual-level scheme**: a file that is a competent *standard* CBCS course file but lacks the awareness/advanced machinery is **NOT READY** and must say so.

## Canonical references (read from the repository root)

- `Course_Design_Checklist.md` — the ~45-item gate with stable IDs and severities (🔴 Blocker / 🟠 Major / 🟡 Minor). **This is the spine of the review.**
- `Course_File_Template.md` — what a complete file should contain.
- `Course_Designer_Guidelines_2026.md` — the design rules each item enforces.
- `REVA_BTech_Curriculum_Strategy.md` — strategy alignment (dual-level, sort-late, currency, one-mainline).
- `Docs/<PROGRAM>-v1.md` — the course's **official program scheme of instruction**. Verify code, category, L-T-P-C, contact hours, and CIE/SEE against the **student's program** (AIDS→`Docs/AIDS-v1.md`, AIML→`Docs/AIML-v1.md`, CSE→`Docs/CSE-v1.md`, CS-IT/Cyber→`Docs/CSIT-v1.md`, ISE→`Docs/ISE-v1.md`, IoT→`Docs/IoT-v1.md`) — **not AIDS by default.**
- `Curriculum_Visual_Map.md` — verify dual-level level (A/Adv/A+Adv), prerequisite continuity, and SIG-track alignment (AIDS-anchored, generalisable).
- `Course_Design_Verification_DAA.md` — **the worked example; match its format and rigour.**

## Step 1 — Get the course content

The subject may be Markdown or a Word file. For `.docx`, extract the text first (python-docx is **not** installed in this environment — read the zip's `word/document.xml` instead):

```bash
python -c "
import zipfile, io
from xml.etree import ElementTree as ET
ns='{http://schemas.openxmlformats.org/wordprocessingml/2006/main}'
z=zipfile.ZipFile('COURSE_FILE.docx')
root=ET.fromstring(z.read('word/document.xml').decode('utf-8'))
out=[''.join(t.text for t in p.iter(ns+'t') if t.text).strip() for p in root.iter(ns+'p')]
io.open('_extract.txt','w',encoding='utf-8').write(chr(10).join(x for x in out if x))
"
```

Clean up the temporary extract file when done.

## Step 2 — Independent review (three lenses)

Before the checklist, assess against:
1. **University OBE best practice** — measurable action-verb COs, constructive alignment (CO ↔ activity ↔ assessment), Bloom consistency, integrity, accessibility.
2. **Curriculum strategy** — dual-level design present and load-bearing; no streaming; sort-late-with-data; currency-underneath.
3. **Curriculum structure** — the course's **code, category, and L-T-P-C match the student's program scheme in `Docs/<PROGRAM>-v1.md`** (checklist item A2); level (A/Adv/A+Adv) consistent and prerequisites continuous per `Curriculum_Visual_Map.md`; SIG-track linkage for SC/W/Proj/Intern.

## Step 3 — Run the checklist line by line

For **every** ID in `Course_Design_Checklist.md`, record: **Verdict** (Pass / Partial / Fail / N-A), **Severity**, **Finding** (cite specific evidence from the file — section, wording, what's present or missing), and a concrete **Fix**. Be honest and specific; do not pass an item on benefit of the doubt.

## Step 4 — Score and conclude

Produce, in the format of `Course_Design_Verification_DAA.md`:
- A **headline finding** (one paragraph: what the file is, and the single biggest gap or structural mismatch).
- A **scoring summary** table (counts of Blocker/Major/Minor fails + passes, with the failing IDs).
- The **item-by-item table(s)** grouped by checklist section (A–J).
- A **prioritised remediation plan** — Blockers first, then Majors — ending with a ready-to-paste prompt the faculty can use (often via `reva-course-designer`) to fix the gaps.

**Verdict rule:** a course is **READY** only with zero unresolved Blockers and zero unresolved Majors. Otherwise **NOT READY**.

## Output

Write the verdict to a file named `Course_Design_Verification_<COURSE>.md` in the repository root (mirroring the DAA example), and summarise the headline + counts + top fixes in chat.
