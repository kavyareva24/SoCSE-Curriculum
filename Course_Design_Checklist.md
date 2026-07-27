# Course Design Checklist

> **Purpose.** The single gate every completed Course File must pass before submission to the Board of Studies / HoD. It merges three sources into one verifiable list: **template completeness** ([Course File Template](Course_File_Template.md)), **design rules** ([Course Designer Guidelines — 2026](Course_Designer_Guidelines_2026.md)), and **strategy alignment** ([B.Tech Curriculum Strategy](REVA_BTech_Curriculum_Strategy.md) + [Visual Curriculum Map](Curriculum_Visual_Map.md)).
>
> **How to use.** After the faculty review and the Claude review (see [Course Design Workflow §4–§5](Course_Design_Workflow.md)), check every item. Each has a stable **ID** so reviews and verification reports can reference it. Mark each **Pass / Fail / N-A / Waiver**. A course is submission-ready only when every item is **Pass**, **N-A**, or carries an explicit, justified **Waiver**.
>
> **Severity.** Items marked **🔴 Blocker** must pass — they are load-bearing for the strategy or for OBE validity. **🟠 Major** gaps must be fixed before the course runs. **🟡 Minor** items are quality polish.

---

## A. Identity & structural alignment

| ID | Check | Severity | Source |
|---|---|---|---|
| A1 | Course identification block complete (faculty, REVA ID, email, programme, code, title, semester/section, AY, duration in sessions, consultation hours). | 🟡 Minor | Template §0 |
| A2 | **Course code, category, and L-T-P-C match the program's scheme of instruction** (`Docs/<PROGRAM>-v1.md` for the student's program), and the **dual-level level (A / Adv / A+Adv / —)** matches the [Visual Curriculum Map](Curriculum_Visual_Map.md). | 🔴 Blocker | Docs/ scheme; Map; Guidelines §2 |
| A3 | The **design treatment matches the L-T-P shape** — e.g. an integrated `1-1-1` course has a real practical/lab component, not theory-only delivery; a `0-0-x` course is rubric-graded. | 🔴 Blocker | Guidelines §3–§4, §6 |
| A4 | **Prerequisite course(s) recorded** (§10) and consistent with the map's incoming arrows; the mentoring/track link is traceable. | 🟠 Major | Template §10; Map |
| A5 | School vision/mission and standard front-matter present and current. | 🟡 Minor | Template §0 |
| A6 | The two **decisions are confirmed to exist or are documented**: the course-level awareness/advanced split recorded in §14 + filled reference exemplar (flagged if missing). | 🔴 Blocker | Guidelines §0 |

## B. Course outcomes (COs)

| ID | Check | Severity | Source |
|---|---|---|---|
| B1 | **COs written first** and stated as measurable, action-verb statements (not "understand/know"); 5–6 COs typical. | 🔴 Blocker | Guidelines §1.1 |
| B2 | **Every CO tagged with a Bloom taxonomy level** (Remember / Understand / Apply / Analyse / Evaluate / Create) in the §5 level column. | 🔴 Blocker | Template §5; Strategy §5.4 |
| B3 | **At least the highest CO(s) are at Analyse / Evaluate / Create level** — the course has a genuine ceiling. | 🔴 Blocker | Template §5 |
| B4 | Course outcomes map to CSCore / entrance-test / placement competencies (where applicable) to protect student employability. | 🔴 Blocker | Guidelines §1.3, §4.2 |
| B5 | Each CO mapped to **PO/PSO** with correlation strength (1/2/3). | 🟠 Major | Template §5, §19 |
| B6 | COs are **constructively aligned** — every CO is taught (§11) and assessed (§14); no orphan CO, no assessment without a CO. | 🟠 Major | OBE best practice |

## C. Dual-level scope per unit (KEYSTONE)

| ID | Check | Severity | Source |
|---|---|---|---|
| C1 | **§3 dual-level scope table filled for every unit** — awareness floor and advanced ceiling each stated explicitly. | 🔴 Blocker | Template §3 |
| C2 | Floor vs ceiling wording is **anchored to Bloom verbs** (floor = Remember/Understand/Apply; ceiling = Analyze/Evaluate/Create). | 🟠 Major | Template §3; Guidelines §1.2 |
| C3 | The split is **consistent with the reference exemplar** so "advanced" means the same thing across courses. | 🟠 Major | Guidelines §0.2, §4.2 |
| C4 | Course content/units (§2) and their weightage are present and sum correctly. | 🟡 Minor | Template §2 |

## D. Activities & session plan (Merrill)

| ID | Check | Severity | Source |
|---|---|---|---|
| D1 | **§11 merged session plan filled** — every session has unit/topic, planned date, % completion, and CO tag. | 🔴 Blocker | Template §11 |
| D2 | **Each session carries an activity** with enough description to communicate intent (what the student does/submits); for Activities-first courses, the activity set is the spine. | 🔴 Blocker | Template §11; Workflow §3 |
| D3 | **Every session tagged with a Merrill phase**; across each unit all five phases (Problem-centred, Activation, Demonstration, Application, Integration) appear at least once. | 🟠 Major | Template §22, §22.1 |
| D4 | [Removed — Level handling simplified to assessment only] | 🔴 Blocker | — |
| D5 | Activity **session counts are realistic** against true contact hours implied by L-T-P (honest budgeting, no idealized self-study assumption). | 🟠 Major | Guidelines §1.6 |
| D6 | **Continuous, frequent, low-stakes** assessment favoured over a single high-stakes exam. | 🟠 Major | Guidelines §1.5 |
| D7 | For high-P courses, the **level distinction lives in an activity rubric** (works = floor; efficient/scalable/well-reasoned = ceiling), not a question paper. | 🟠 Major | Guidelines §6, §4.3–§4.4 |

## E. Assessment & CGPA calibration

| ID | Check | Severity | Source |
|---|---|---|---|
| E1 | **§14 evaluation scheme splits every instrument** into awareness (floor) and advanced (ceiling) marks. | 🔴 Blocker | Template §14 |
| E2 | The **course-level awareness/advanced split (§14) is defined, applied and documented** in the Course File — the rationale and calibration should be recorded. | 🔴 Blocker | Guidelines §14, §4.2 |
| E3 | **§14.1 CGPA calibration check completed and confirmed**: awareness-only mastery lands **below the 8-CGPA band**; crossing it requires advanced marks. | 🔴 Blocker | Template §14.1; Strategy §9.1 |
| E4 | **§14.2 question-paper blueprint** present — awareness vs advanced items identified for each IA and the SEE. | 🟠 Major | Template §14.2 |
| E5 | Component split (IA/assignments/SEE) totals 100 and is internally consistent. | 🟡 Minor | Template §14 |
| E6 | **Academic-integrity design**: assessments resistant to trivial AI-completion where the CO is the student's own competence; integrity policy stated (§13). | 🟠 Major | Guidelines §1.8; Template §13 |
| E7 | **Result-analysis bands (§15)** present and read as floor vs ceiling (<40 / 40–75 / >75). | 🟡 Minor | Template §15 |

## F. Differentiated support

| ID | Check | Severity | Source |
|---|---|---|---|
| F1 | **Remediation path to the floor named** and tied to the awareness level (not generic) — triggered by IA performance. | 🔴 Blocker | Guidelines §1.7; Template §8 |
| F2 | **Enrichment path to the ceiling named** and tied to the advanced level. | 🔴 Blocker | Guidelines §1.7; Template §8 |
| F3 | **Intake-aware**: no unstated prior-exposure assumption; a bridge/week-0 ramp provided where the gap is real (rural / biology-background intake). | 🟠 Major | Guidelines §1.8, §4.1; Strategy §3 |

## G. Content currency & resources

| ID | Check | Severity | Source |
|---|---|---|---|
| G1 | **Perishable tooling lives in labs/workshops/activities**, not frozen into theory syllabi; a review cycle is noted. | 🟠 Major | Guidelines §1.4 |
| G2 | Textbooks, references, e-resources, and ICT/digital support (§7, §12) present and current. | 🟡 Minor | Template §7, §12 |
| G3 | Pedagogy (§6) lists the **actual mix of methods** used (not a single "direct method" label when the design requires demonstration/application/integration). | 🟠 Major | Template §6, §22 |

## H. Mapping, attainment & tracking

| ID | Check | Severity | Source |
|---|---|---|---|
| H1 | **CO–PO/PSO matrix (§19)** filled with strength values and consistent with the §5 per-CO mapping. | 🟠 Major | Template §19 |
| H2 | **CO-attainment table (§18) set up with target.** | 🟠 Major | Template §18 |
| H3 | **Learner-support tracking (§16)** split into remediation + enrichment with capture fields. | 🟡 Minor | Template §16 |
| H4 | **Overall attainment** model (Direct 80% + Indirect 20%) and minimum PO-attainment level stated. | 🟡 Minor | Template §19 |

## I. Strategy alignment

| ID | Check | Severity | Source |
|---|---|---|---|
| I1 | **No streaming** — one course for all students; differentiation is by assessment, never by separate sections/briefs. | 🔴 Blocker | Strategy §5.4, §6.2 |
| I2 | **Sort late, with data** — any track/level signal is advisory feedback, never an early label or hard gate. | 🟠 Major | Strategy §5.5, §6.2 |
| I3 | For SC / Workshop / Project / Internship courses: **ownership sits with a SIG/pod** and the course links into that track's sequence. | 🟠 Major | Guidelines §4.5–§4.6, §4.11–§4.12; Strategy §5.2 |
| I4 | **§17 track-advice signal** defined for prerequisite/core courses (advisory note to academic mentors). | 🟡 Minor | Template §17 |
| I5 | **One-mainline framing** — design optimises for employable-contributor outcomes for the ~95%; entrepreneurship treated as a narrow exit, not the default summit. | 🟡 Minor | Strategy §5.5, §6.3 |

## J. Review & sign-off

| ID | Check | Severity | Source |
|---|---|---|---|
| J1 | **Faculty review completed** (human-first) — faculty confirms COs/activities reflect intent. | 🔴 Blocker | Workflow §4 |
| J2 | **Claude review completed** against best practice + strategy + curriculum structure, with gaps resolved. | 🟠 Major | Workflow §5 |
| J3 | **§21 dual-level health-check reflection** stub present; signatures block ready (faculty + HoD/Director). | 🟡 Minor | Template §21 |

---

## Scoring summary (fill at verification time)

| Band | Count | IDs failing |
|---|---|---|
| 🔴 Blocker — Fail | | |
| 🟠 Major — Fail | | |
| 🟡 Minor — Fail | | |
| ✅ Pass / N-A / Waiver | | |

**Verdict:** ‹READY / NOT READY› — *a course is READY only when zero Blockers and zero Majors remain unresolved.*
