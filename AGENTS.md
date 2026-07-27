# AGENTS.md — working in the SoCSE-Curriculum repository

Guidance for AI coding agents (and humans) working in this repo. Read this first.

## What this repository is

The curriculum-design and course-design system for **REVA University, School of Computer Science & Engineering (SoCSE)** — the **2026 B.Tech scheme** (CSE, ISE, IT, AIML, AIDS, IoT and Cyber Security with Blockchain). It is a **documentation/knowledge repository**, not a software project: there is no build, no test suite, no application code. The "source" is Markdown and Word documents that define curriculum strategy, course-design rules, templates, and individual course files.

## Repository map

| File | Role | Edit freely? |
|---|---|---|
| `README.md` | Usage guide — designing a course with Claude Code / VS Code / Antigravity | Yes |
| `CONTRIBUTING.md` | Contributor guide: architecture, setup, fork-based PR workflow | Yes |
| `REVA_BTech_Curriculum_Strategy.md` | The strategy (the *why*). Source of truth. | Rarely — strategy decisions are institutional |
| `Course_Designer_Guidelines_2026.md` | Design rules by course category and L-T-P | Rarely |
| `Course_File_Template.md` | The Course File template faculty fill (§0–§22) | Carefully — it's a shared template |
| `Docs/<PROGRAM>-v1.md` | **Official per-program schemes of instruction** (AIDS, AIML, CSE, CSIT, ISE, IoT) — authoritative course code, category, L-T-P-C, contact hours, CIE/SEE. Look up a course in the **student's program** doc. | When the scheme changes |
| `CourseFiles/` | **All completed course design documents** — one `.md` per course. Sub-folders: `Foundation/` (all-6 shared), `AI-Programs/` (AIDS+AIML±CSE), `CS-Programs/` (CSE+CSIT+ISE+IoT), and per-program folders. See `CourseFiles/README.md` for the placement rule and naming convention. | Add files here as courses are designed |
| `Course_Design_Workflow.md` | The two-path faculty workflow (Outcomes-first / Activities-first) | Yes |
| `Course_Design_Checklist.md` | ~45-item submission gate with stable IDs + severities | Yes |
| `Course_Design_Verification_DAA.md` | Worked verification of the DAA course file | Yes (it's an artifact) |
| `CourseDesignWorkflow.md` | Faculty's raw planning notes — **do not polish or delete without asking** | No |
| `CF_DAA_*.docx`, `*.docx` | Actual course files / reports (Word) | Read mostly; edit only on request |
| `.claude/skills/` | Project skills (see below) | Yes |

## Skills in this repo

Two project skills under `.claude/skills/` package the core workflows. Prefer them over ad-hoc work:

- **`reva-course-designer`** — author a complete dual-level Course File via either entry path (start from Course Outcomes, or from Activities in the session plan).
- **`reva-course-reviewer`** — verify a completed Course File against `Course_Design_Checklist.md` + strategy + curriculum structure, producing a READY / NOT READY verdict.

## Conventions

- **Markdown** is the working format. Keep the existing voice: tables, blockquote callouts for rules, `🔴/🟠/🟡` severities, `🟢/🔵` template-section markers. Preserve the `‹…›` placeholder convention in templates.
- **Cross-link** related docs by relative path so the set stays navigable.
- **Do not stream students** into ability sections in any design — differentiation is by assessment (Strategy §5.4). Do not invent an unrecorded awareness/advanced split; instead define and document the course-level split in §14 and record the §14.1 calibration.
- **Honour the keystone sections** when touching a Course File: §3 dual-level scope, §11 session plan (Merrill phase + activity + level per session), §14/§14.1 assessment + CGPA calibration, §22 Merrill strategy.

## Working with `.docx` files

`python-docx` is **not installed**. To read a Word file, extract `word/document.xml` from the docx (a zip) and pull the `<w:t>` runs — see the snippet in `.claude/skills/reva-course-reviewer/SKILL.md`. Write output with UTF-8 encoding (the default Windows codepage chokes on characters like `‑`). To *edit* a `.docx`, use the `docx` skill if available, or operate on the underlying XML carefully.

## Environment

- OS: Windows. A `bash` tool and PowerShell are both available; the repo path is `C:\Users\DELL\Desktop\SoCSE-Curriculum`.
- Git normalises LF→CRLF on checkout; the `LF will be replaced by CRLF` warnings on `git add` are harmless.

## Contributing / Git workflow

- Default branch: **`main`**. Branch before committing non-trivial work.
- Commit message style: imperative subject; end with `Co-Authored-By: Claude Opus 4.8 <noreply@anthropic.com>`. **Pass multi-line messages via `-F <file>`, not a PowerShell here-string** (the here-string leaked a stray `@` into a subject line once).
- **Push access caveat:** the stored credential authenticates as **`adminedarc`**, which has **no write access** to the upstream `kavyareva24/SoCSE-Curriculum`. Direct `git push origin main` returns **403**.
  - Workaround in use: a fork **`adminedarc/SoCSE-Curriculum`** exists, wired as the git remote **`fork`**. Push feature branches to `fork` and open PRs into `kavyareva24:main` (`gh pr create --repo kavyareva24/SoCSE-Curriculum --base main --head adminedarc:<branch>`).
  - The clean long-term fix is to give the working account write access to the upstream repo (or repoint `origin`). Confirm with the user before changing remotes or auth.
- Only commit/push when the user asks.
