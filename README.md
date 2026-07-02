# SoCSE-Curriculum

Curriculum-design system for **REVA University, School of Computer Science & Engineering (SoCSE)** — the **2026 B.Tech scheme** (CSE, ISE, IT, AIML, AIDS, IoT, Cyber Security).

This repository is not software — it is a **knowledge base + AI workflow** that helps faculty design and review **dual-level Course Files** with the help of an AI coding assistant (Claude Code, VS Code, or Antigravity IDE).

> **The one idea this repo serves — dual-level design.** Every core course is delivered at **two levels in one course**: an **awareness floor** every student must clear (protecting placement readiness) and an **advanced ceiling** needed to exceed 8 CGPA — separated by **assessment, not by streaming students into sections**. Read [`REVA_BTech_Curriculum_Strategy.md`](REVA_BTech_Curriculum_Strategy.md) for the *why*.

---

## What's in here

| Document | What it is |
|---|---|
| [`REVA_BTech_Curriculum_Strategy.md`](REVA_BTech_Curriculum_Strategy.md) | The strategy — the *why* behind dual-level design |
| [`Course_Designer_Guidelines_2026.md`](Course_Designer_Guidelines_2026.md) | Design rules by course category and L-T-P pattern |
| [`Course_File_Template.md`](Course_File_Template.md) | The Course File template faculty fill (§0–§22) |
| [`Curriculum_Visual_Map.md`](Curriculum_Visual_Map.md) | Semester map: each course's category, L-T-P-C, level, prerequisites |
| [`Course_Design_Workflow.md`](Course_Design_Workflow.md) | The two-path faculty workflow (start from Outcomes **or** Activities) |
| [`Course_Design_Checklist.md`](Course_Design_Checklist.md) | The ~45-item gate every finished course must pass |
| [`Course_Design_Verification_DAA.md`](Course_Design_Verification_DAA.md) | A worked example: the DAA course file verified against the checklist |
| `.claude/skills/` | Two AI skills: **reva-course-designer** and **reva-course-reviewer** |
| [`AGENTS.md`](AGENTS.md) | Orientation for AI agents working in this repo |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to contribute (setup, GitHub, architecture) |

---

## Before you start

1. A **GitHub account** (a GitHub-for-Education account is ideal).
2. **Git** installed — <https://git-scm.com/downloads>.
3. **One AI assistant** of your choice (set up below): **Claude Code**, **VS Code** + an AI extension, or **Antigravity IDE**.
4. *(Optional)* **Python 3** — only needed if a tool must read existing `.docx` course files.

Clone the repository:

```bash
git clone https://github.com/kavyareva24/SoCSE-Curriculum.git
cd SoCSE-Curriculum
```

---

## How to design a course (pick your tool)

All three tools do the same job — open this folder so the AI can read the strategy, template, guidelines, and map, then drive the [two-path workflow](Course_Design_Workflow.md). The difference is only *how the AI is invoked*.

### Option A — Claude Code (recommended; skills work natively)

[Claude Code](https://claude.com/claude-code) auto-discovers the skills in `.claude/skills/`.

```bash
cd SoCSE-Curriculum
claude
```

Then just describe your task in plain English — the right skill triggers automatically:

- **To design:** *"Design the course file for Operating Systems (Sem 5). I'll give you the course outcomes."* → triggers **reva-course-designer**.
- **Activities-first:** *"Here are the weekly activities for my course — reverse-engineer the COs and the full course file."*
- **To review:** *"Verify my DAA course file against the checklist."* → triggers **reva-course-reviewer**.

You can also type `/` to see available skills. Claude reads [`AGENTS.md`](AGENTS.md) for repo context.

### Option B — VS Code

1. Install [VS Code](https://code.visualstudio.com/), then add an AI assistant extension — the **Claude Code extension** (skills work the same as Option A) or **GitHub Copilot Chat**.
2. `File → Open Folder…` → select the cloned `SoCSE-Curriculum` folder.
3. Open the AI chat panel. With the folder open the assistant can read the template, guidelines, strategy, and `AGENTS.md`.
4. Drive the workflow by pasting a prompt from [`Course_Design_Workflow.md`](Course_Design_Workflow.md) §2 (Outcomes-first) or §3 (Activities-first) — e.g.:
   > "Using `Course_File_Template.md`, `Course_Designer_Guidelines_2026.md`, and the curriculum strategy, generate a complete Course File for *‹code – title›* (category ‹…›, L-T-P ‹…›, level ‹…›). My COs and Bloom levels are below…"
5. Attach your existing/old course document if you have one, and ask the AI to modernise it onto the template.

> With the **Claude Code extension**, the `reva-course-designer` / `reva-course-reviewer` skills trigger just like in Option A. With **Copilot**, paste the workflow prompts manually instead.

### Option C — Antigravity IDE

[Antigravity](https://antigravity.google/) is an agent-first IDE.

1. Open Antigravity and **open the cloned `SoCSE-Curriculum` folder** as your workspace.
2. Open the **Agent panel**. Antigravity reads [`AGENTS.md`](AGENTS.md) for repo context automatically.
3. The `.claude/skills/` files don't auto-trigger here (they're a Claude Code convention), so **drive the process with the prompts in [`Course_Design_Workflow.md`](Course_Design_Workflow.md)** — point the agent at the template, guidelines, strategy, and map, and follow Path A or Path B.
4. Let the agent fill [`Course_File_Template.md`](Course_File_Template.md) interactively, then review.

---

## The workflow in one picture

```
Locate your course in the map (category, L-T-P, level, prerequisites)
                              │
              ┌───────────────┴───────────────┐
        PATH A: write Course Outcomes    PATH B: list Activities in the
        (conventional OBE)               session plan (one per session)
              └───────────────┬───────────────┘
                              ▼
        AI fills the dual-level Course File (interactive or one-shot)
                              ▼
        FACULTY review (human first)  →  AI review (best practice +
                              ▼           strategy + curriculum structure)
        Verify against Course_Design_Checklist.md  →  submit to BoS
```

Full detail: [`Course_Design_Workflow.md`](Course_Design_Workflow.md).

---

## Reviewing / verifying a finished course

Ask your AI assistant to run the course through [`Course_Design_Checklist.md`](Course_Design_Checklist.md) (the **reva-course-reviewer** skill does this in Claude Code). It produces a per-item **Pass / Fail** verdict with fixes and an overall **READY / NOT READY** result. See [`Course_Design_Verification_DAA.md`](Course_Design_Verification_DAA.md) for the format and rigour expected.

---

## Contributing & ownership

The curriculum is owned by REVA SoCSE. To propose changes — a new course file, a template/guideline update, or a new skill — read [`CONTRIBUTING.md`](CONTRIBUTING.md) for setup, the GitHub pull-request process, and the repository architecture.
