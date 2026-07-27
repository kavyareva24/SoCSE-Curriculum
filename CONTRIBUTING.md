# Contributing to SoCSE-Curriculum

Thank you for helping build REVA SoCSE's curriculum-design system. This guide is for **human contributors** — faculty, SIG/pod leads, and the curriculum committee — and covers the repository architecture, setup, and the GitHub process for proposing changes.

> New here? Read [`README.md`](README.md) first (what the repo is and how to *use* it), then come back here to learn how to *change* it.

---

## 1. Who contributes, and what

| Contributor | Typical contributions |
|---|---|
| **Faculty / course designers** | New or revised **Course Files** for their courses |
| **SIG / pod leads** | Workshop, elective, project, and internship designs for their track; currency updates |
| **Curriculum committee** | Changes to the **strategy**, **guidelines**, **template**, **checklist**, and **curriculum map** |
| **Tooling maintainers** | The AI **skills** under `.claude/skills/` and the agent guide `AGENTS.md` |
| **Directors** | **Approval** — strategy-level and template-level changes are approved by Directors |

Most contributions are **additive** (a new course file) or **small edits**. Changes to the shared, load-bearing documents (strategy, guidelines, template, checklist) are higher-impact and need committee/Director review.

---

## 2. Repository architecture

The repo is layered: **strategy** sets direction, **guidelines + template** turn it into design rules and a fillable document, the **workflow + checklist** drive and gate the work, and **course files** are the outputs. The **map** is the structural index; the **skills** automate the workflow.

```
                ┌─────────────────────────────────────────────┐
   WHY  ──────► │ REVA_BTech_Curriculum_Strategy.md           │  direction, dual-level rationale
                └───────────────────────┬─────────────────────┘
                                        │ derived into
                ┌───────────────────────▼─────────────────────┐
   RULES ─────► │ Course_Designer_Guidelines_2026.md          │  design rules by category / L-T-P
                │ Course_File_Template.md                     │  the document faculty fill (§0–§22)
                └───────────────────────┬─────────────────────┘
                                        │ operated by
                ┌───────────────────────▼─────────────────────┐
   PROCESS ───► │ Course_Design_Workflow.md  (two entry paths)│  how faculty produce a course
                │ Course_Design_Checklist.md (~45-item gate)  │  the submission bar
                └───────────────────────┬─────────────────────┘
                                        │ produces / verifies
                ┌───────────────────────▼─────────────────────┐
   OUTPUTS ───► │ CF_<COURSE>.docx   (individual Course Files) │
                │ Course_Design_Verification_<COURSE>.md       │  worked verifications
                └─────────────────────────────────────────────┘

   INDEX   ───► Curriculum_Visual_Map.md     (category, L-T-P-C, level, prerequisites per course)
   AUTOMATION ► .claude/skills/reva-course-designer , reva-course-reviewer
   AGENT GUIDE► AGENTS.md      HUMAN GUIDES► README.md , CONTRIBUTING.md
```

**Dependency direction matters:** a course file depends on the template, which depends on the guidelines, which depend on the strategy. When you change an upper layer, check what it invalidates below it (e.g. editing the template may require updating the checklist and the skills).

---

## 3. Setup & installation

### 3.1 Prerequisites

1. **GitHub account** (GitHub-for-Education recommended).
2. **Git** — <https://git-scm.com/downloads>. Configure your identity:
   ```bash
   git config --global user.name  "Your Name"
   git config --global user.email "you@reva.edu.in"
   ```
3. **The GitHub CLI** (`gh`) — <https://cli.github.com/> — convenient for forks and pull requests. Authenticate once with `gh auth login`.
4. **An AI assistant** for course work — Claude Code, VS Code + extension, or Antigravity (see [`README.md`](README.md)). Not required just to edit Markdown.
5. *(Optional)* **Python 3** — only to read existing `.docx` course files (see §7).

### 3.2 Get the code

Because of how write-access is configured (see §4), most contributors **fork first**:

```bash
# Fork to your account and clone your fork
gh repo fork kavyareva24/SoCSE-Curriculum --clone=true
cd SoCSE-Curriculum
```

This sets `origin` = your fork and `upstream` = `kavyareva24/SoCSE-Curriculum`. Keep your fork current with:

```bash
git fetch upstream && git checkout main && git merge upstream/main
```

---

## 4. Write access & the fork-based workflow

> **Important.** Direct pushes to `kavyareva24/SoCSE-Curriculum` require write access that not all contributors have. In the current setup, the shared `adminedarc` credential returns **HTTP 403** on push to the upstream. The supported path for everyone is therefore **fork → branch → pull request**.

If you *do* have upstream write access, you may push branches directly to `origin` and skip the fork. Otherwise:

```
your fork (origin)            upstream (kavyareva24)
  feature branch  ── push ─►   ── pull request ─►  main  ── review/approve ─►  merged
```

---

## 5. Making a contribution (step by step)

1. **Sync** your `main` with upstream (§3.2).
2. **Branch** with a descriptive name:
   ```bash
   git checkout -b course-os-sem5          # new course file
   git checkout -b guidelines-currency-fix # edit to a shared doc
   ```
3. **Make the change.** For a new course, use the [workflow](Course_Design_Workflow.md) and fill [`Course_File_Template.md`](Course_File_Template.md). Follow the conventions in §6.
4. **Self-check.** For a course file, run it through the [checklist](Course_Design_Checklist.md) (the `reva-course-reviewer` skill automates this) — aim for **READY** before opening the PR.
5. **Commit.** Use a clear imperative subject; pass multi-line messages from a file, **not** a shell here-string:
   ```bash
   git commit -F message.txt
   ```
   End AI-assisted commit messages with a co-author trailer if you used an assistant.
6. **Push** to your fork:
   ```bash
   git push -u origin course-os-sem5
   ```
7. **Open a pull request** into `kavyareva24:main`:
   ```bash
   gh pr create --repo kavyareva24/SoCSE-Curriculum --base main \
     --head <your-username>:course-os-sem5 \
     --title "Add Operating Systems (Sem 5) course file" --body-file pr.md
   ```
   In the PR description say **what** changed, **which course/document**, and **whether it passes the checklist**.
8. **Review & approval.** A curriculum-committee reviewer (and a **Director** for strategy/template/checklist changes) reviews and merges. Address comments by pushing more commits to the same branch.

---

## 6. Conventions & house style

- **Markdown** is the working format. Match the existing voice: tables, blockquote callouts for rules, severity markers `🔴 Blocker / 🟠 Major / 🟡 Minor`, and template-section markers `🟢 standard / 🔵 strategy-bearing`.
- **Preserve `‹…›` placeholders** in templates; fill them in course files.
- **Cross-link** related documents by relative path so the set stays navigable.
- **Never stream students** into ability sections — differentiation is by assessment only (Strategy §5.4).
- **Do not invent an unrecorded awareness/advanced split.** Define and document the course-level split in §14 and record the §14.1 calibration; seek HoD/program approval if required.
- **Honour the keystone sections** when editing a Course File: §3 dual-level scope, §11 session plan (Merrill phase + activity + level), §14/§14.1 assessment + CGPA calibration, §22 Merrill strategy.
- **Do not delete or "polish" `CourseDesignWorkflow.md`** (raw planning notes) without asking the owner.
- **Keep perishable tooling out of frozen theory syllabi** — it belongs in activities/labs/workshops (Strategy §6.1).
- If you change the **template** or **strategy**, update the **checklist** and the **skills** to match in the same PR.

---

## 7. Working with `.docx` course files

`python-docx` is **not** assumed to be installed. To **read** a Word course file, extract `word/document.xml` from the `.docx` (it's a zip) and pull the text runs:

```bash
python -c "
import zipfile, io
from xml.etree import ElementTree as ET
ns='{http://schemas.openxmlformats.org/wordprocessingml/2006/main}'
z=zipfile.ZipFile('CF_COURSE.docx')
root=ET.fromstring(z.read('word/document.xml').decode('utf-8'))
out=[''.join(t.text for t in p.iter(ns+'t') if t.text).strip() for p in root.iter(ns+'p')]
io.open('_extract.txt','w',encoding='utf-8').write(chr(10).join(x for x in out if x))
"
```

Write output as **UTF-8** (the default Windows codepage fails on characters like `‑`). Remove temporary `_extract.txt` files before committing. To **author/edit** a `.docx`, prefer your AI assistant's document tooling, or edit the underlying XML carefully.

---

## 8. Review checklist for maintainers

Before merging a PR, confirm:

- [ ] Scope matches the PR description; no unrelated files changed.
- [ ] A new/changed **course file** passes [`Course_Design_Checklist.md`](Course_Design_Checklist.md) (zero unresolved Blockers/Majors), with the dual-level keystones present.
- [ ] Category / L-T-P / level are **consistent with [`Curriculum_Visual_Map.md`](Curriculum_Visual_Map.md)**.
- [ ] Changes to a shared doc (strategy/guidelines/template/checklist) have matching updates downstream and **Director approval** where required.
- [ ] House-style conventions (§6) followed; links resolve; no stray temp files.

---

## Questions

Open a GitHub Issue, or contact the curriculum committee (course-design strategy owners) listed in the planning notes. For how to *use* the repo to design a course, see [`README.md`](README.md).
