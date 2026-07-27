# Course Design Strategy: 1-1-1 and 0-0-2 Courses
**School of Computer Science & Engineering, REVA University**
**Reference Scheme:** 2026 | Last Updated: June 2026

---

## Purpose

This document specifies the pedagogical design strategy, activity design principles, and assessment architecture for two course types in the 2026 scheme:

- **1-1-1 courses** — one lecture, one tutorial, one lab per week (integrated theory-practice courses)
- **0-0-2 courses** — pure workshop courses (W1–W8 in the scheme), no lecture/tutorial, only practice sessions

Both strategies are grounded in the student reality described in the Curriculum Strategy: a mixed cohort with ~30% Explorers/Achievers, ~40% Passengers, and ~30% Resistors. The design must make the higher-skill path the path of least resistance, not an optional extra.

---

## Part 1: 1-1-1 Course Design Strategy

### 1.1 What a 1-1-1 Course Is

One lecture hour + one tutorial hour + one lab hour per week, over a 15-week semester. Total contact: ~45 hours. The lecture, tutorial, and lab are a **weekly triplet** — not three isolated slots.

| Slot | Purpose | Ownership |
|---|---|---|
| Lecture (1 hr) | Concept introduction, mental model, worked example | Faculty-led |
| Tutorial (1 hr) | Guided practice, problem-solving, misconception correction | Faculty-led; every student seen at least once per 2 weeks |
| Lab (1 hr) | Hands-on implementation, tool use, debugging | Student-driven with faculty support |

### 1.2 Course Outcome Design

Write **4–6 COs** per course. COs must be anchored to two sources simultaneously:

**Student demographics anchor:**
- Account for the biology/rural intake (~40%): COs must not assume prior CS exposure beyond what the scheme has already delivered.
- Account for the persona split: COs must be achievable at an awareness floor (Passengers/Resistors) and extensible to an advanced ceiling (Explorers/Achievers).
- Each CO should be achievable by a Passenger-level student who completes all structured activities — not just by self-driven students.

**Industry requirements anchor:**
- Map each CO to a job-task that will exist when students graduate (3–4 years out), not to a 2019-era job description.
- At least 2 of the 6 COs should require AI-augmented working (using tools, interpreting AI output, validating AI-generated code) rather than purely manual execution.
- At least 1 CO should involve communication/explanation of work (not just doing it), since human-in-the-loop roles require articulation.

**CO Bloom's level guidance:**

| CO Number | Minimum Level | Ceiling Level |
|---|---|---|
| CO1 | Remember / Understand | Apply |
| CO2 | Understand | Apply |
| CO3 | Apply | Analyze |
| CO4 | Apply | Analyze |
| CO5 (optional) | Analyze | Evaluate |
| CO6 (optional) | Evaluate | Create |

COs 1–4 define the **awareness floor**; COs 5–6 (or the advanced extension of COs 3–4) define the **advanced ceiling**.

### 1.3 Activity Design

Design **15 ± 5 activities** (10 minimum, 20 maximum) distributed across the weekly triplet. Activities are the atomic unit of the course — each activity maps to one or more COs and has a defined slot, duration, and output.

**Activity types and slot mapping:**

| Activity Type | Slot | Typical Duration | Example |
|---|---|---|---|
| Concept + worked example | Lecture | 60 min | Explain recursion with 2 traced examples |
| Problem set (guided) | Tutorial | 60 min | Solve 3 problems of graduated difficulty |
| Coding task (implementation) | Lab | 60 min | Implement a function, run tests, submit via GitHub |
| Debugging exercise | Lab | 60 min | Given broken code, diagnose and fix with explanation |
| Design / diagram task | Tutorial | 60 min | Draw ER diagram or algorithm flowchart |
| Mini-project checkpoint | Lab | 60 min | Incremental deliverable toward a 3-week project |
| Peer review | Tutorial | 30–45 min | Structured critique of a classmate's submission |
| Reflection quiz | Tutorial | 15–20 min | 5–10 MCQs + 2 written justifications |

**Activity design rules:**
1. Every activity must map to at least one CO. Record this mapping explicitly.
2. At least one-third of all activities must be **auto-gradable** (code tests, MCQs, structured forms) to reduce grading load and enable fast feedback.
3. Every activity must have a **floor version** (minimum correct output demonstrating awareness) and, for COs 5–6, an **advanced extension** (optional deeper deliverable).
4. Sequence activities so each builds on the previous: no activity should require knowledge from a future week's lecture.
5. At least 2 activities per module should explicitly involve **reading or correcting AI-generated output** (prompt, review, validate), not just writing code from scratch.

### 1.4 Time Allocation and Teaching Model

Weekly rhythm per 3-hour block:

```
1 hr  — Lecture: introduce concept, one worked example, one common misconception addressed
1 hr  — Tutorial: guided practice; faculty move through room; every student must be spoken to
        at least once every 2 weeks (tracked in tutorial register)
1 hr  — Lab: hands-on task; student submits output before leaving
```

**Faculty–student contact requirement:**
Tutorial is the primary vehicle for individual contact. Faculty must assess each student's understanding through direct conversation at least **once per 2-week cycle**. This is not optional — it is the mechanism that separates 1-1-1 from a lecture-only course.

In cohorts larger than 30, split tutorials into two batches (15–18 per group) to make individual contact feasible.

**Weekly test cadence:**
- A short test (15–20 minutes) runs **every week** at the start of tutorial or lab.
- Each weekly test evaluates **previously covered COs** (not the current week), reinforcing spaced retrieval.
- Tests cover both theory (MCQs + justification) and practical (one small coding or analysis task).
- Marks: small percentage contribution (1–2% per week) to CIA to create accountability without high stakes per test.
- Students who miss or fail a weekly test may sit a **repeat (makeup) test** the following week. Makeup tests are scheduled, not ad hoc. They cover the same COs as the missed test, with different questions.

### 1.5 Assessment Architecture

#### Continuous Internal Assessment (CIA) — 50 marks

| Component | Marks | Frequency | Notes |
|---|---|---|---|
| Weekly tests (theory + practical) | 15 | Every week (~14 tests; best 10 counted) | ~1.5 marks/test; MCQ + justification + 1 coding task |
| Lab submissions | 15 | Every lab session (14 labs) | Auto-graded via test cases + manual rubric for code quality |
| Tutorial problem sets | 10 | Every tutorial (14 tutorials) | Graded for correctness + explanation |
| Mini-project / checkpoint | 10 | 1–2 per semester | CO-mapped deliverable; floor/advanced tagged |

Makeup tests replace missed weekly tests at the same marks ceiling — not bonus marks. A student cannot earn more than the original weekly test cap by taking a makeup.

#### Semester End Examination (SEE) — 50 marks

SEE follows the **ACP model** (Assess → Consolidate → Produce):

**Theory component (MCQ + Justification exam):**
- Format: MCQ questions paired with mandatory written justification for each answer.
- Rationale: MCQs enable autograding of factual recall; justification questions prevent guessing and test understanding.
- Both the MCQ answer and the justification must be correct to earn full marks for a question.
- MCQ answer correct, justification incorrect or missing → partial credit only.
- Platform: auto-graded for MCQ component; justifications reviewed by faculty (or AI-assisted rubric).

**Lab exam (practical component):**
- Student receives a set of **X known programs** drawn from the semester's lab activities (announced in advance).
- Student also receives **1 unknown program** — a novel problem that requires applying the same skills in a new context.
- The unknown program is the primary differentiator between awareness-floor and advanced-ceiling performance.
- Lab exam is conducted in a live environment; no internet access; AI tool access policy defined per course.
- Rubric: functional correctness (auto-tested) + code quality (manual) + brief written explanation of approach.

**SEE Marks Split (example for a programming-heavy 1-1-1 course):**

| Component | Marks |
|---|---|
| Theory MCQ + Justification | 20 |
| Lab exam — known programs | 20 |
| Lab exam — unknown program | 10 |
| **Total SEE** | **50** |

Adjust split based on CO balance (theory-heavy vs. implementation-heavy courses).

---

## Part 2: 0-0-2 Course Design Strategy

### 2.1 What a 0-0-2 Course Is

A pure workshop course — no lecture, no tutorial. Two lab/practice hours per session, typically run as a **half-day or full-day workshop block** over a condensed period. In the 2026 scheme, these are the W1–W8 workshops.

**Default planning assumption: 16 workshop days** (sessions). Total contact: 32 hours of active workshop time.

### 2.2 Course Outcome Design

Write **4–6 COs** using the same demographic and industry anchors as 1-1-1, but calibrated for a **doing-first** course:

- Every CO must be demonstrable through a **built artifact or deployed output**, not through an exam answer alone.
- COs should describe what a student can **create, deploy, or present** by the end of the workshop — not what they know.
- At least 1 CO must involve **collaboration or communication** (pair work, team demo, peer teaching).
- At least 1 CO must involve **using a real tool or platform** that appears in industry job descriptions (GitHub, cloud provider, API, framework — not a toy environment).
- COs should be achievable in 16 sessions of 2 hours each (32 hours total). Scope accordingly.

**CO framing example (not course-specific):**
- "Build and deploy a working [artifact] using [tool/platform] that satisfies [real-world constraint]."
- "Diagnose and fix [class of problems] in a given [codebase/system] and document the changes."
- "Present [deliverable] to a peer audience and respond to questions about design decisions."

### 2.3 Activity Design

**Number of activities = number of workshop days = 16.**

One activity per session. Each activity is a complete, self-contained unit of work that a student finishes within the session and submits before leaving.

**Every session follows the same 100-minute structure:**

| Phase | Duration | What Happens |
|---|---|---|
| **Activation** | 10 min | Surface prior knowledge; connect today's task to yesterday's work; quick warm-up question or demo |
| **Demonstration** | 20 min | Faculty or guest demonstrates the day's tool/technique on a live problem; students watch, ask, predict |
| **Application** | 60 min | Students build/implement independently or in pairs; faculty circulate and intervene; output submitted to GitHub before session ends |
| **Integration** | 10 min | Class debrief: what did you build, what broke, what pattern did you notice; connects to next session |
| **Quiz** | 10 min | 5–8 MCQs on today's concepts + 1–2 justification questions; auto-graded; score visible immediately |

**Activity design rules for 0-0-2:**
1. Every activity's **Application output must be submittable to GitHub** (code, notebook, config file, deployment manifest, or documentation file). No paper-only deliverables.
2. Each activity must have a **definition of done**: a set of auto-graded checks (unit tests, linter pass, CI badge, deployment URL) that confirm the output is complete. Students do not self-declare completion.
3. Activities are sequenced so that each session's output **builds on or extends** the previous session's output. By day 16, students have a portfolio of 16 connected artifacts, not 16 isolated exercises.
4. The day-16 activity is always a **synthesis task**: the student integrates outputs from multiple earlier sessions into a complete demonstration piece for the SEE hackathon/presentation.
5. For cohorts with wide ability range: define a **floor deliverable** (minimum passing output) and a **stretch deliverable** (additional feature, optimization, or extension) for each activity. The stretch is optional but encouraged.

### 2.4 Daily Accomplishment and Auto-Grading

Daily accomplishment tracking is **predominantly automated via GitHub**:

- Each student maintains a **workshop repository** (one repo per course, structured with a folder per session day).
- Faculty define a GitHub Actions workflow that runs on each push: tests, linters, deployment checks, or output validation as appropriate to the day's task.
- Auto-grading checks for:
  - Commit made within the session window (timestamp evidence of in-class work)
  - Tests passing (functional correctness)
  - Defined file structure present (process compliance)
  - Optional: code complexity or coverage thresholds

**Grading model:**
- Session score = auto-grader output (0/1 per check, weighted) + quiz score.
- Faculty override is possible for edge cases but should not be the primary grading mechanism.
- Students see their score within 30 minutes of session end (auto-grader runs on push).

**MCQ + Justification component (CIA):**
- In addition to session quizzes, one standalone MCQ + Justification assessment is administered mid-workshop (after session 8).
- Same format as 1-1-1: MCQ answer + written justification; partial credit for MCQ-only correct answers.
- Covers the conceptual foundations behind the tools and techniques used in sessions 1–8.
- Auto-graded for MCQ; faculty-reviewed for justifications.

### 2.5 Assessment Architecture

#### Continuous Internal Assessment (CIA) — 50 marks

| Component | Marks | Frequency | Notes |
|---|---|---|---|
| Daily session submissions (GitHub) | 25 | 16 sessions | Auto-graded; ~1.5 marks/session; floor deliverable = full marks |
| Daily session quizzes | 10 | 16 sessions (best 12 counted) | ~0.8 marks/quiz; MCQ + justification; auto-graded |
| Mid-workshop MCQ + Justification | 15 | Once (after session 8) | Theory component; covers sessions 1–8 |

#### Semester End Examination (SEE) — 50 marks

SEE for 0-0-2 is a **hackathon or structured presentation**, not a written exam.

**Hackathon/Presentation format:**
- Students receive a **problem statement** 24–48 hours before the SEE day (or at the start of a half-day SEE session for a condensed version).
- Problem statement requires integrating skills from multiple workshop sessions.
- Students build and submit a working solution to GitHub (or equivalent platform) within the allotted time.
- Final 15 minutes: live demonstration + 5-minute Q&A with evaluators.
- Evaluation is CO-mapped via a rubric applied by two evaluators (internal + external or peer-pair).

**SEE Marks Split:**

| Component | Marks |
|---|---|
| Working solution (auto-grader + functionality) | 20 |
| Design quality, approach, code structure | 15 |
| Live demo + Q&A | 10 |
| Documentation / README in GitHub repo | 5 |
| **Total SEE** | **50** |

---

## Part 3: Cross-Cutting Principles

### 3.1 CO–Activity–Assessment Traceability

For both course types, maintain an explicit **traceability table** in the course file:

| Activity / Assessment | CO1 | CO2 | CO3 | CO4 | CO5 | CO6 |
|---|---|---|---|---|---|---|
| Activity 1 | ✓ | | | | | |
| Activity 2 | ✓ | ✓ | | | | |
| Weekly test 1 | ✓ | ✓ | | | | |
| ... | | | | | | |
| SEE theory | ✓ | ✓ | ✓ | ✓ | | |
| SEE lab/hackathon | | | ✓ | ✓ | ✓ | ✓ |

Every CO must be assessed by at least 2 activities and appear in both CIA and SEE.

### 3.2 Dual-Level Tagging

Every activity and every assessment item must be tagged:
- **[A] Awareness** — required of all students; demonstrates basic competence.
- **[Adv] Advanced** — expected of top-tier students; demonstrates higher-order application.

The course is designed so that a student who completes all [A]-tagged work earns a passing grade. [Adv]-tagged work unlocks higher grade bands and badge eligibility.

### 3.3 Feedback Loop Timing

| Course Type | Feedback Mechanism | Target Turnaround |
|---|---|---|
| 1-1-1 | Weekly test auto-grade | Same day |
| 1-1-1 | Lab submission auto-grade | Within 24 hours |
| 1-1-1 | Tutorial problem set | Within 1 week |
| 0-0-2 | Session GitHub auto-grade | Within 30 minutes |
| 0-0-2 | Daily quiz | Immediate (in-session) |
| Both | SEE results | Within 2 weeks of exam |

Fast feedback is a design requirement, not a nice-to-have. Activities that cannot be graded within the target window must be redesigned or replaced with auto-gradable equivalents.

### 3.4 AI Tool Policy

Both course types must explicitly state in the course file:
- Which AI tools are permitted during CIA activities and to what extent.
- What is and is not permitted during SEE (lab exam / hackathon).
- At least one activity per course that explicitly teaches **responsible and effective AI tool use** — not avoidance, not unchecked reliance.

---

## Summary Comparison

| Dimension | 1-1-1 | 0-0-2 |
|---|---|---|
| Contact pattern | 1 hr lecture + 1 hr tutorial + 1 hr lab / week | 2 hr workshop session / day × 16 days |
| COs | 4–6; awareness floor + advanced ceiling | 4–6; all demonstrable via built artifacts |
| Activities | 15 ± 5; distributed across lecture/tutorial/lab | 16; one per session day; sequenced build |
| Session structure | Weekly triplet | 10-20-60-10-10 min phases (fixed) |
| Student–faculty contact | Every student seen in tutorial ≥ once / 2 weeks | Faculty circulates during 60-min application block |
| Formative assessment | Weekly test (theory + practical) every week | Daily quiz + GitHub auto-grade every session |
| Makeup / repeat | Weekly repeat test for missed/failed weekly tests | Re-submission window per session (same week) |
| CIA instruments | Weekly tests + lab submissions + tutorial sets + mini-project | Session GitHub submissions + daily quizzes + mid-workshop MCQ |
| SEE theory | MCQ + mandatory written justification (autograded MCQ) | MCQ + mandatory written justification (mid-workshop, not SEE day) |
| SEE practical | Lab exam: X known programs + 1 unknown program | Hackathon/presentation: novel problem, GitHub submission + live demo |
| Auto-grading emphasis | Weekly tests, lab submissions, SEE MCQ | Daily GitHub submissions (CI), daily quizzes, SEE solution |
| Primary differentiator tool | Unknown program in SEE lab exam | Live Q&A + novel problem in SEE hackathon |
