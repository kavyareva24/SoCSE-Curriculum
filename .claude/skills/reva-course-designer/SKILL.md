---
name: reva-course-designer
description: >-
  Design a complete dual-level (awareness + advanced) Course File for a REVA
  University SoCSE 2026 B.Tech course (CSE / ISE / IT / AIML / AIDS / IoT /
  Cyber Security). Use whenever a faculty member wants to create, author, or
  draft a course design document, course file, syllabus, course outcomes (COs),
  learning activities, session/lesson plan, or assessment scheme for the 2026
  scheme — via either entry path: starting from Course Outcomes (conventional
  OBE) or starting from Activities (quizzes, programs, mini-projects,
  assignments) in the session plan. Triggers on "design my course", "create a
  course file", "write course outcomes for X", "design activities / session
  plan", "help me build the syllabus for my course", or attaching an existing
  course document to modernise. Do NOT use to review or verify an
  already-drafted course — use reva-course-reviewer for that.
---

# REVA Course Designer (dual-level)

Guide a faculty member from a blank start to a **completed `Course File — Dual-Level`** for the REVA SoCSE 2026 B.Tech scheme. The keystone the whole design serves: **every core course is delivered at two levels in one course — an awareness floor every student must clear, and an advanced ceiling needed to exceed 8 CGPA — separated by assessment, never by streaming students into sections.**

## Canonical references (read these from the repository root before designing)

- `Course_File_Template.md` — the deliverable to fill (sections §0–§22).
- `Course_Designer_Guidelines_2026.md` — design rules by course category and L-T-P.
- `REVA_BTech_Curriculum_Strategy.md` — the *why* behind the dual-level design.
- `Docs/<PROGRAM>-v1.md` — the **official 2026 scheme of instruction for each program** (authoritative source for course code, category, L-T-P-C, contact hours, CIE/SEE). Open the one matching the student's program:

  | Program | Scheme doc |
  |---|---|
  | AI & Data Science (AIDS) | `Docs/AIDS-v1.md` |
  | AI & Machine Learning (AIML) | `Docs/AIML-v1.md` |
  | Computer Science & Engineering (CSE) | `Docs/CSE-v1.md` |
  | Computer Science & Information Technology / Cyber Security (CS-IT) | `Docs/CSIT-v1.md` |
  | Information Science & Engineering (ISE) | `Docs/ISE-v1.md` |
  | Internet of Things & Cyber Security (IoT) | `Docs/IoT-v1.md` |

- `Curriculum_Visual_Map.md` — the dual-level **level (A/Adv/A+Adv)**, **prerequisites**, and **SIG/track alignment** (AIDS-anchored but generalisable across programs).
- `Course_Design_Workflow.md` — the two-path workflow this skill operationalises.

## Step 1 — Anchor the course (do this first, always)

**Identify the student's program first**, then open its scheme in `Docs/<PROGRAM>-v1.md` (mapping above) — the authoritative source for the course's **official code, title, category, L-T-P + total credits, contact hours/week, and CIE/SEE split**. Cross-reference `Curriculum_Visual_Map.md` for the dual-level level, prerequisites, and SIG/track. Programs differ — verify against the *correct* program's scheme, not AIDS by default. Record four facts; they drive every later choice:

1. **Category** (FC / HC / SC / OE / ETC / MC / W / AEC / Proj / Intern) — from the program scheme
2. **L-T-P-C** (e.g. DAA = `1-1-1-3`, an integrated theory+lab course) — from the program scheme
3. **Dual-level level** (A / Adv / A+Adv / —) — from the Visual Map
4. **Prerequisite course(s)** (the map's incoming arrows) — from the Visual Map

Then confirm the two decisions exist or are documented (Guidelines §0): the course-level awareness/advanced **split recorded in §14** and a **reference exemplar**. If either is missing, document and justify the split; do not leave it unspecified.

> A `3-0-0` theory course and a `1-1-1` integrated course are designed differently (Guidelines §3–§4). Match the L-T-P treatment: integrated courses need a real practical strand; high-P courses carry the level distinction in a **rubric**, not a question paper.

## Step 2 — Choose the entry path (ask the faculty)

Both paths converge on the same Course File and the same review gate. Pick by how the faculty thinks.

### Path A — Outcomes-first (conventional OBE)
1. Faculty writes 5–6 **COs** as measurable action statements (no "understand/know"). If they attach an old course doc, lift and modernise the COs from it.
2. **Tag each CO** with a Bloom taxonomy level (Remember / Understand / Apply / Analyse / Evaluate / Create) — propose from Bloom verbs + the map level; have them confirm. The assessment design will map these levels to the awareness floor (Remember–Apply) and advanced ceiling (Analyse–Create) splits.
3. Derive **units → §3 dual-level scope per unit → one activity per session (§11) → §14 dual-level assessment + §14.1 CGPA calibration → CO–PO/PSO mappings.**

### Path B — Activities-first
The **set of activities defines the course.** An activity is a quiz, program, small project, or assignment the **student submits** — typically **one per session block** (an hour, two hours, or a week, per L-T-P). Each activity needs a **description** (enough to communicate intent) and a **session count**; optionally its unit and floor/ceiling target.
1. Faculty lists activities directly in the **§11 session table** (one row/block per activity).
2. **Reverse-engineer** COs (with standard Bloom levels), units, §3 scope, Merrill phases, §14 assessment + calibration, and all mappings from the activity set.
3. **Surface the inferred COs and unit scope and have the faculty confirm them** — this is Path B's critical checkpoint. Adjust activities/tags until the inferred OBE structure matches intent.

## Step 3 — Generate the Course File (interactive or one-shot)

Fill every section of `Course_File_Template.md`, replacing all `‹…›` placeholders. Run **interactively** (ask about tooling, vertical, project briefs, weightings) for HC-integrated, SC/PEC, workshop, project, and internship courses where domain judgement matters; **one-shot** is acceptable for straightforward theory courses.

Non-negotiables to honour while generating:
- **§3 dual-level scope** filled for every unit, Bloom-anchored.
- **§11**: every session has unit/topic, CO, a **Merrill phase**, and an **activity**; all five Merrill phases appear per unit.
- **§14**: every instrument must split marks into awareness/advanced as defined for this course; complete and **confirm the §14.1 calibration** (awareness-only < 8 CGPA) and document the rationale.
- **§8** differentiation tied explicitly to floor (remediation) and ceiling (enrichment); intake-aware (no unstated prior-exposure; bridge ramp where the gap is real).
- **Currency**: perishable tooling lives in activities/labs, not frozen into theory; note a review cycle.
- **No streaming**; one course for all (Strategy §5.4).

## Step 4 — Hand off to review

After the **faculty reviews first** (human owns the course), tell them to run the **`reva-course-reviewer`** skill to verify against `Course_Design_Checklist.md` plus the strategy and curriculum structure before Board of Studies submission.

## Output

A completed dual-level Course File (Markdown, or applied into the faculty's `.docx`), with all placeholders resolved and every keystone section (§3, §11, §14/§14.1, §22) populated and self-consistent.
