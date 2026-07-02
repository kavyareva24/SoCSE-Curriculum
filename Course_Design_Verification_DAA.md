# Course Design Verification — DAA (B24EF0401)

> **Subject:** `CF_DAA_B24EF0401_2025-2026_new.docx` — *Design and Analysis of Algorithms*, B.Tech Sem IV-B, EVEN AY2025-2026, Faculty: Thirumagal Mohan (REVA00769).
> **Checked against:** [Course_Design_Checklist.md](Course_Design_Checklist.md), using [Course File Template](Course_File_Template.md), [Guidelines](Course_Designer_Guidelines_2026.md), [Strategy](REVA_BTech_Curriculum_Strategy.md), and the [Visual Curriculum Map](Curriculum_Visual_Map.md).
> **Date:** 2026-06-08.

---

## Headline finding

This file is a **complete and competent *standard* CBCS Course File** — but it is **not the 2026 Dual-Level Course File**. It predates the curriculum strategy and contains **none of the dual-level (awareness/advanced) machinery** that the strategy makes load-bearing. As a legacy document it is fine; as a 2026-scheme course design it **fails most Blockers** and is **NOT READY** until upgraded.

There is also one **structural mismatch with the curriculum map**: the map lists DAA as `1-1-1-3 | HC | A+Adv` (an **integrated theory + lab** course with an advanced ceiling), but this file delivers it as **theory-only, "Direct method", 48 lecture sessions** with no practical/lab component, no rubric, and no level tagging.

---

## Scoring summary

| Band | Count | IDs failing / partial |
|---|---|---|
| 🔴 Blocker — **Fail** | 11 | A2, A3, A6, B2, B3, B4, C1, D2, E1, E2, E3 |
| 🔴 Blocker — Partial | 3 | D1, F1, F2 |
| 🟠 Major — Fail/Partial | 10 | B1, B6, C2, C3, D3, D5, D7, E4, F3, G3 |
| 🟡 Minor — Fail/Partial | 4 | A1, G1, I4, J3 |
| ✅ Pass / N-A | 14 | A4, A5, B5, C4, D4, D6*, E5, E6*, E7, G2, H1, H2, H3, H4, I1, I2, I3, I5, J1 |

**Verdict: 🔴 NOT READY** for the 2026 dual-level scheme. 11 Blockers fail outright and 3 more are only partially met. (* = passes as a standard course file but is incomplete for dual-level.)

---

## Item-by-item verification

### A. Identity & structural alignment

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| A1 | 🟡 Partial | All identity fields present, but **duration says "42 sessions" while the §11 plan lists 48**. | Reconcile the session count. |
| A2 | 🔴 **Fail** | **No L-T-P, no category, no level stated.** Map says `1-1-1-3 / HC / A+Adv`; the file reflects none of this. | State category, L-T-P-C, and dual-level level; align to the map. |
| A3 | 🔴 **Fail** | DAA is **integrated `1-1-1`** (theory + tutorial + lab). File delivers **theory-only**, no lab/practical sessions, no rubric — the practical credit where the ceiling is demonstrated is missing. | Add the tutorial and lab/practical strands; design the ceiling into the lab (Guidelines §4.3). |
| A4 | ✅ Pass | Prerequisite "Data Structures" recorded — consistent with the map's DSA → DAA arrow. | Optionally note the mentoring/track link explicitly. |
| A5 | ✅ Pass | Vision/mission and front-matter present. | — |
| A6 | 🔴 **Fail** | No reference to the **course-level awareness/advanced split** or the **reference exemplar**. | Document the split in §14 and record the calibration (Guidelines §0). |

### B. Course outcomes

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| B1 | 🟠 Partial | 6 COs present, but **CO1 "Understand of fundamental algorithmic concepts" is grammatically broken and uses a weak, non-measurable verb**; CO3 "Develop the skills to analyze" is fuzzy. CO2/CO4/CO5/CO6 use good verbs. | Rewrite CO1/CO3 as measurable action statements. |
| B2 | 🔴 **Fail** | **No Bloom Taxonomy level column** on any CO. | Tag every CO with its Bloom level in the §5 level column. |
| B3 | 🔴 **Fail** | Bloom level not identified for COs (cannot confirm cognitive ceiling). | Tag the COs with their Bloom levels. |
| B4 | 🔴 **Fail** | Course outcomes **not mapped to CSCore / entrance-test / placement** competencies — critical, as DAA is a placement-critical HC course. | Map the floor COs to entrance-test topics. |
| B5 | ✅ Pass | COs mapped to POs/PSOs in §5 and the §19 matrix is filled. | — |
| B6 | 🟠 Partial | COs are mapped to assessments, but the **session plan does not tag any CO per session** (CO column effectively empty) — teaching-to-CO traceability is broken. | Add a CO tag to each §11 session row. |

### C. Dual-level scope per unit (keystone)

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| C1 | 🔴 **Fail** | **§3 dual-level scope table is entirely absent.** This is the single most important table in the dual-level template. | Author awareness-floor vs advanced-ceiling per unit. |
| C2 | 🟠 Fail | No Bloom-anchored floor/ceiling distinction anywhere. | Add per the Bloom anchor (Template §3). |
| C3 | 🟠 Fail | No exemplar calibration. | Calibrate against the reference exemplar. |
| C4 | ✅ Pass | 4 units with 25-mark weightage each; content well-specified. | — |

### D. Activities & session plan (Merrill)

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| D1 | 🔴 Partial | §11 plan has dates, topics, % completion — **but no CO column**. | Add CO column to every row. |
| D2 | 🔴 **Fail** | The plan has an **"Extended Activities" column that is empty for all 48 rows** — there are **no activities**. The course is defined purely by topics, not by what students do/submit. | Design one activity per session block (the heart of both workflow paths). |
| D3 | 🟠 Fail | No Merrill phase tagging; pedagogy is "Direct" only — Activation/Demonstration/Application/Integration absent. | Tag each session's Merrill phase; cover all five per unit. |
| D4 | ✅ N-A | [Removed — Level handling simplified to assessment only] | — |
| D5 | 🟠 Partial | 48 lecture sessions are plausible for the lecture strand, but **ignore the tutorial + lab hours** implied by `1-1-1`. | Re-budget against true contact hours. |
| D6 | ✅ Pass* | 2 IAs + 2 assignments + SEE — acceptable minimum, but not especially continuous/low-stakes. | Consider more frequent low-stakes checks. |
| D7 | 🟠 Fail | DAA has a practical credit, yet **no rubric exists** to carry the floor/ceiling distinction on practical work. | Build an activity rubric (works = floor; efficient/optimal = ceiling). |

### E. Assessment & CGPA calibration

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| E1 | 🔴 **Fail** | §14 is standard CBCS — **no awareness/advanced mark split** on any instrument. | Split every instrument's marks into floor/ceiling. |
| E2 | 🔴 **Fail** | The official mark ratio is not applied. | Apply the institutional ratio (Guidelines §0.1). |
| E3 | 🔴 **Fail** | **§14.1 CGPA calibration check absent** — there is no guarantee that awareness-only mastery lands below 8 CGPA. This is the strategy's keystone constraint. | Complete and confirm the calibration table. |
| E4 | 🟠 Fail | SEE blueprint is "two questions per unit, answer one" — **no awareness vs advanced item identification**. | Add the §14.2 blueprint. |
| E5 | ✅ Pass | Components total 100 (20+20+5+5+50). | — |
| E6 | ✅ Pass* | Integrity policy present (§13); but **AI-completion resistance not designed in**. | Add integrity-by-design for own-competence COs. |
| E7 | ✅ Pass | Result-analysis bands `<40 / 40–75 / >75` present. | Re-read the >75 band as the "advanced attained" count. |

### F. Differentiated support

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| F1 | 🔴 Partial | A "Slow Learners" remediation block exists (remedial classes on IA performance) — **but it is generic and not tied to a defined awareness floor** (none exists). | Tie remediation to the §3 floor. |
| F2 | 🔴 Partial | A "High Achievers" enrichment block exists (journal review, design for real-world problems) — **but not tied to defined Advanced COs**. | Tie enrichment to Advanced COs/ceiling. |
| F3 | 🟠 Fail | **No bridge/week-0 ramp** and an unstated assumption of prior exposure (Data Structures) — risky for the rural/biology intake. | Add a bridge ramp where the gap is real. |

### G. Content currency & resources

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| G1 | 🟡 Partial | No perishable tooling and **no review-cycle note**. | Note a refresh cycle; place any tooling in lab/activities. |
| G2 | ✅ Pass | Textbook (Levitin), references (CLRS, AHU, Knuth), NPTEL + e-resources, and per-unit YouTube links — solid and current. | — |
| G3 | 🟠 Fail | Pedagogy = **"Direct method" only**, justified by "learners already have foundations" — inadequate for an integrated course needing demonstration/application/integration. | List the real method mix (Merrill phases). |

### H. Mapping, attainment & tracking

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| H1 | ✅ Pass | §19 CO-PO/PSO matrix filled with strengths. *(Minor: §5 cites PO12 but the matrix header stops at PO11 — reconcile.)* | Reconcile PO11/PO12. |
| H2 | ✅ Pass | §18 attainment table with target 60 present. | — |
| H3 | ✅ Pass | Slow/fast-learner tracking tables present. | — |
| H4 | ✅ Pass | 80% direct + 20% indirect model and min PO level stated. | — |

### I. Strategy alignment

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| I1 | ✅ Pass | Single course for all — no streaming. | — |
| I2 | ✅ Pass | No early labels / hard gates present. | — |
| I3 | ✅ N-A | DAA is HC/CSCore, not a SIG-owned SC/W/Proj. | — |
| I4 | 🟡 Fail | **§17 track-advice signal absent** — DAA results feed AI/ML-SIG suitability and should be summarised. | Add the track-advice note. |
| I5 | ✅ N-A | Core theory course; one-mainline framing not applicable directly. | — |

### J. Review & sign-off

| ID | Verdict | Finding | Fix |
|---|---|---|---|
| J1 | ✅ Pass | Authored by the course faculty (assumed faculty-reviewed). | Re-review after the dual-level upgrade. |
| J2 | 🔄 In progress | This document **is** the Claude review. | Resolve the gaps below, then re-run. |
| J3 | 🟡 Partial | Signatures block present; **§21 dual-level health-check reflection absent**. | Add the §21 reflection stub. |

---

## What to do next (prioritised remediation)

The fastest route is to **regenerate this course on the dual-level template** using the [Course Design Workflow](Course_Design_Workflow.md) — the existing file is excellent raw material (units, content, references, dates are all reusable).

**Blocker fixes first (must pass before the course runs):**
1. **Re-cast onto the Dual-Level template** and restore the structural facts — category, `1-1-1-3`, level `A+Adv` — to match the map *(A2, A3)*.
2. **Author the §3 dual-level scope** for all four units — floor vs ceiling *(C1)*.
3. **Identify Bloom level** for every CO; map the floor to placement/entrance-test topics *(B2, B3, B4)*.
4. **Design one activity per session** (the empty "Extended Activities" column) and tag each with Merrill phase *(D2, D1)*.
5. **Split assessment** into awareness/advanced marks, define and apply the course-level split, and complete the **§14.1 CGPA calibration** *(E1, E2, E3)*.
6. **Tie remediation/enrichment to the floor/ceiling** *(F1, F2)*.
7. **Confirm the course-level split is documented + exemplar exist** *(A6)*.

**Then Majors:** rewrite CO1/CO3 (B1), trace COs through §11 (B6, D1), add the §14.2 blueprint (E4), add a bridge ramp (F3), list the real pedagogy mix (G3), and add the lab rubric (D7).

**A practical prompt to start the upgrade (Activities-first is the natural fit here, since the topic plan already exists):**

Take the existing DAA Course File content (units, topics, dates, references — all valid) and upgrade it onto `Course_File_Template.md` for an HC **integrated `1-1-1-3`, level A+Adv** course. For each of the 48 session topics, design **one activity** a student submits (auto-graded quiz, program, or mini-task), tagging Merrill phase. Then author the §3 dual-level scope, identify Bloom levels for the COs, split §14 assessment per the course-level split defined for this course, and complete the §14.1 CGPA calibration. Ask me about tooling and the advanced-task briefs as you go.
