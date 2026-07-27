# Course Design Workflow — Two Entry Paths

> **Who this is for.** Faculty and SIG teams authoring a Course File for any course in the 2026 B.Tech scheme (CSE, ISE, IT, AIML, AIDS, IoT, Cyber Security).
>
> **What it does.** It defines *how a faculty member produces a completed Course File* using Generative AI (Claude), starting from whichever artefact they find most natural to write — **Course Outcomes** (the conventional OBE order) or **Activities** (the things students actually do). Both paths converge on the same deliverable: a fully filled **Course File — Dual-Level** document, reviewed by the faculty and then by Claude.
>
> **Companion documents.**
> - [Course File Template](Course_File_Template.md) — the deliverable to be filled.
> - [Course Designer Guidelines — 2026](Course_Designer_Guidelines_2026.md) — the design rules, by course category and L-T-P.
> - [B.Tech Curriculum Strategy](REVA_BTech_Curriculum_Strategy.md) — the *why* behind the dual-level design.
> - [Course Design Checklist](Course_Design_Checklist.md) — the gate every finished course must pass.
> - [Visual Curriculum Map](Curriculum_Visual_Map.md) — where this course sits, its category, L-T-P, level, and prerequisites.

---

## 0. Before you start (one-time setup)

1. **Clone the repository** containing the templates (this folder).
2. Have a **Generative-AI account** — GitHub-for-Education Copilot, a Claude/Pro account, or equivalent — and an IDE/editor (VS Code, Antigravity, or any editor that can talk to the model).
3. **Locate your course in the [Visual Curriculum Map](Curriculum_Visual_Map.md)** and write down four facts before doing anything else:
   - **Category** (FC / HC / SC / OE / ETC / MC / W / AEC / Proj / Intern)
   - **L-T-P-C** (e.g. DAA = `1-1-1-3`, HC integrated)
   - **Level on the dual-level scale** (A / Adv / A+Adv / —)
   - **Prerequisite courses** (the arrows feeding into your node)
4. **Confirm the necessary decisions are recorded** (Guidelines §0): the course-level awareness/advanced split documented in the Course File, and a filled reference exemplar. If either is missing, document and justify the split in the file — do not leave it unspecified.

> These four facts decide *everything* downstream. A `3-0-0` theory course and a `1-1-1` integrated course are designed differently (Guidelines §3–§4). The map tells you which rules apply.

---

## 1. Choose your entry path

You may begin from **either** artefact. Pick the one that matches how you think about the course.

| | **Path A — Outcomes-first** | **Path B — Activities-first** |
|---|---|---|
| You start by writing… | **Course Outcomes (COs)** | **Activities** (one per session block) |
| Best when… | You think in terms of *what the student will be able to do* and are comfortable with the OBE/Bloom framing. | You think in terms of *what the student will actually do* — the quiz, program, mini-project, or assignment they submit. |
| Claude then generates… | Units → dual-level scope → activities → session plan → assessment → mappings. | COs → units → dual-level scope → session plan → assessment → mappings, **reverse-engineered from your activities**. |
| OBE order | Conventional (outcomes drive design). | Inverted (activities reveal the intended outcomes; Claude makes the OBE structure explicit and you confirm it). |

Both paths produce the **same** Course File and both pass through the **same** review and checklist in §4–§5. Choosing a path is only about where you *start writing*.

---

## 2. Path A — Outcomes-first (conventional OBE)

**Step A1 — Write the Course Outcomes.**
In the chat, write 5–6 COs in the form *"By the end of the course the student will be able to ‹verb› ‹object› ‹condition›."* Use action verbs, not "understand/know". If you already have an existing/older course document, attach it — Claude will lift and modernise the COs from it.

**Step A2 — Tag each CO with its level.**
**Step A2 — Tag each CO with its Bloom Taxonomy level.**
For every CO, identify its Bloom level (Remember / Understand / Apply / Analyse / Evaluate / Create) as per standard OBE practices. The assessment design will map these levels to the awareness floor (Remember–Apply) and advanced ceiling (Analyse–Create) splits.

**Step A3 — Ask Claude to generate the course.**
Paste a prompt like:

> "Using `Course_File_Template.md`, `Course_Designer_Guidelines_2026.md`, and the curriculum strategy, generate a complete Course File for **‹course code – title›** (category ‹…›, L-T-P ‹…›, level ‹…›). My COs and their Bloom levels are below. Derive the units and the §3 dual-level scope per unit, then design **one activity per session** for the §11 lesson plan, then the §14 dual-level assessment with the CGPA calibration check. Ask me whenever a choice needs my judgement."

**Step A4 — Work interactively (or accept a one-shot draft).**
Claude can run this **interactively** (asking you about tooling, vertical, project briefs, weightings) or produce a **one-shot** full draft you then refine. Interactive is recommended for HC integrated, SC/PEC, project and workshop courses, where your domain judgement matters most.

→ Continue to **§4 Review**.

---

## 3. Path B — Activities-first

This path treats the **set of activities as the definition of the course**. You design what students *do*; Claude generates every other component from it.

**What an activity is.** A quiz, a program, a small project, or any other assignment that the **student submits**. Typically **one activity per session block** — and a session may be an **hour, two hours, or a whole week** depending on the course's L-T-P. A workshop "session" is a week of doing; a 3-0-0 theory "session" may be a single lecture hour.

**Each activity carries, at minimum:**
- **Description** — enough to communicate the *intent* (what the student produces and what skill it exercises). It need not be a full rubric yet.
- **Number of sessions** required to complete it.
- *(Optional but useful)* the **unit/topic** it belongs to, and whether it targets the **awareness floor** or the **advanced ceiling**.

**Step B1 — List the activities.**
The simplest place to do this is directly in the **§11 main session-plan table** of the template — one row (or block of rows) per activity, with its description and session count. You are filling §11 *first*, by hand, to the extent that it communicates intent. Example rows:

| Sessions | Activity (what the student does/submits) | Unit/topic |
|---|---|---|
| 1 | Quiz: asymptotic-notation drill (auto-graded) | Unit 1 |
| 2 | Program: implement & instrument merge sort, plot growth | Unit 2 |
| 3 | Mini-task: given a novel problem, choose a design technique, justify the trade-off, implement | Unit 3–4 |

**Step B2 — Hand the activity set to Claude.**
Paste a prompt like:

> "Here is the complete set of activities for **‹course code – title›** (category ‹…›, L-T-P ‹…›, level ‹…›), one per session block, each with a description and session count. Treat these activities as the definition of the course. Using the dual-level template, guidelines and strategy, **reverse-engineer** the Course Outcomes (with standard Bloom levels), the units and their §3 dual-level scope, the Merrill phase for each session, the §14 dual-level assessment with the CGPA calibration check, and all CO–PO/PSO mappings. Where an activity is ambiguous, ask me what I intended."

**Step B3 — Confirm the reverse-engineered OBE structure.**
Claude will surface the COs and unit scope it inferred from your activities. **This is the critical confirmation point of Path B** — check that the outcomes it inferred are the ones you actually intended, and that the floor/ceiling split is right. Adjust activities or tags until the inferred structure matches your intent.

**Step B4 — Generate the full course (interactive or one-shot).**
Same as A4. The activities stay fixed as the spine; Claude fills the remaining template sections around them.

→ Continue to **§4 Review**.

---

## 4. Faculty review (first)

Once Claude has produced the full Course File, **the faculty reviews it first** — the human owns the course. Read the draft against your own intent and the checklist:

- Do the COs (whether you wrote them or Claude inferred them) say what you mean?
- Is the **awareness floor** genuinely reachable by the weakest admitted student (no unstated prior-exposure assumption — Strategy §3, Guidelines §1.8)?
- Is the **advanced ceiling** real and reflected in the §3 unit scope and §14 assessment split (Template §14)?
- Are the activities the ones you would actually run, in the time you actually have (honest contact-hour budgeting — Guidelines §1.6)?
- Is the assessment split something you can defend at a Board of Studies?

Edit directly, or ask Claude to revise specific sections. Iterate until *you* are satisfied.

---

## 5. Claude review (second) + checklist verification

After the faculty is satisfied, ask Claude to perform an **independent review** against three references:

1. **University best practices** — OBE rigour, Bloom alignment, constructive alignment of COs ↔ activities ↔ assessment, measurability, integrity, accessibility.
2. **The [Curriculum Strategy](REVA_BTech_Curriculum_Strategy.md)** — dual-level design, sort-late-with-data, currency-underneath, one-mainline.
3. **The [Curriculum structure / map](Curriculum_Visual_Map.md)** — correct category and L-T-P treatment, prerequisite continuity, SIG-track linkage, and level (A/Adv/A+Adv) consistency.

Prompt:

> "Independently review this completed Course File against (a) university OBE best practices, (b) `REVA_BTech_Curriculum_Strategy.md`, and (c) `Curriculum_Visual_Map.md`. Then run it line-by-line through `Course_Design_Checklist.md` and produce a pass/fail verdict per item with specific fixes for every gap."

**Then run the formal gate:** verify the course against every item in [Course_Design_Checklist.md](Course_Design_Checklist.md). A course is **submission-ready only when every checklist item passes** (or carries an explicit, justified waiver). See [Course_Design_Verification_DAA.md](Course_Design_Verification_DAA.md) for a worked example of such a verification.

---

## 6. The workflow at a glance

```
        ┌─────────────────────────────┐
        │ 0. Setup + locate course in │
        │    the map (cat, L-T-P,     │
        │    level, prerequisites)    │
        └──────────────┬──────────────┘
                       │  choose how you think
          ┌────────────┴─────────────┐
          ▼                          ▼
  PATH A — Outcomes-first    PATH B — Activities-first
  write COs + level tags     list activities in §11
  (conventional OBE)         (desc + # sessions)
          │                          │
          ▼                          ▼
   Claude derives units,      Claude reverse-engineers
   scope, activities,         COs, units, scope, plan,
   assessment, mappings       assessment, mappings
          │                          │  (confirm inferred COs)
          └────────────┬─────────────┘
                       ▼
            Full Course File draft
            (interactive OR one-shot)
                       ▼
            4. FACULTY REVIEW (human first)
                       ▼
            5. CLAUDE REVIEW
            (best practice + strategy + structure)
                       ▼
            VERIFY against Course_Design_Checklist.md
                       ▼
            Submit to BoS / HoD  ──►  sign-off
```

---

## 7. Notes, conventions, open questions

- **One activity per session block is the design unit of Path B.** Keep activities small and frequent — the strategy favours continuous low-stakes assessment over one high-stakes exam (Guidelines §1.5), especially for the at-risk majority.
- **Activities carry the ceiling in high-P courses.** The higher the Practical in L-T-P, the more the level distinction lives in a **rubric on the activity**, not a question paper (Guidelines §6, "golden rule").
- **Currency lives in activities, not frozen syllabi.** Perishable tooling belongs in the activity description (refreshed each cycle); the conceptual CO stays stable (Strategy §6.1).
- **COs may be authored to N.J. Rao's format** where the institution adopts it; activities are designed with Generative AI and reviewed by the course-design team (per the planning notes in `CourseDesignWorkflow.md`).
- **Open institutional decisions** (still to be resolved centrally, from Strategy §9): how strongly performance feedback binds vs advises track choice; whether differentiation is by separate advanced COs or by activity weighting; PEO/PSO generation timing. These do not block individual course design but should be tracked.
