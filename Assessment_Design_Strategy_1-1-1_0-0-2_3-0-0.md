# Assessment Design Strategy: 1-1-1, 0-0-2, and 3-0-0 Courses
**School of Computer Science & Engineering, REVA University**
**Reference Scheme:** 2026 | Last Updated: June 2026

---

## Purpose

This document defines a consistent assessment-design strategy for three common course patterns in the 2026 scheme:
- **1-1-1** — Integrated theory + tutorial + lab
- **0-0-2** — Workshop-style practical course
- **3-0-0** — Theory course with lecture-only delivery

It frames the assessment architecture, activity count, and evaluation pattern so course designers can apply the same core rules across programs.

---

## 1. Core Assessment Principles

1. **Assessment must match the L-T-P shape.** 1-1-1 courses need both CIA and SEE; 0-0-2 courses need continuous practice assessment plus a final project/hackathon; 3-0-0 courses need two internal assessments and one final SEE.
2. **Activity count equals lecture sessions.** Every lecture session should anchor one designed activity. This keeps teaching, learning, and assessment tightly coupled.
3. **Frequent, low-stakes evaluation is mandatory.** Frequent auto-graded checks maintain engagement, provide fast feedback, and make learning visible for mixed-ability cohorts.
4. **Every evaluation must sample three sources:** the current week, previous weeks, and an unknown but related context. This ensures retrieval practice, cumulative learning, and transfer.

---

## 2. 1-1-1 Course Assessment Strategy

### 2.1 Assessment Architecture

- **CIA + SEE** is the required model.
- CIA should be built from classroom activities, tutorial work, and lab submissions.
- SEE should integrate both conceptual understanding and practical implementation.

### 2.2 Activity Count and Format

- **Number of activities:** Minimum 15 activities, one per lecture session in a standard 15-week semester.
- **Activity design:** each activity is a classroom/tutor/lab task that is directly linked to course COs.


### 2.3 Evaluation Pattern

For every evaluation event, include:
- **One current-week activity** — tests the just-taught concept.
- **One previous-weeks activity** — reinforces spaced retrieval and retention.
- **One unknown-related activity** — presents a related problem in a new context to test transfer.

This 3-part pattern should be explicit in the weekly assessment rubric and in the question/item blueprint.

### 2.4 CIA Design

- **15 activities in class** should each produce observable evidence of student work.
- A subset of these activities may be completed during lab or tutorial, but each must be anchored to one lecture session.
- Use **auto-graded elements** where possible: MCQs, short code tests, structured rubric checks, and simple programming correctness assertions.

### 2.5 SEE Design

- SEE must be a coherent summative event that assesses both the course floor and the ability to apply skills in a related unknown context.
- Include both:
  - **Theory / conceptual questions**
  - **Practical programming or design problems**
- Maintain the same sampling principle where possible: current concept, prior concept, and applied/related transfer question.

---

## 3. 0-0-2 Course Assessment Strategy

### 3.1 Assessment Architecture

- **CIA + one project / hackathon** is the required model.
- Daily practice is the assessment backbone; the final evaluative event is a project-based hackathon or presentation.

### 3.2 Activity Count and Format

- **Number of activities = number of workshop sessions.**
- Each session must have a clearly defined activity with an artifact submission.
- Example: a 16-session workshop should have 16 activities.

### 3.3 Session Evaluation Pattern

- **Evaluation every session**.
- Each session consists of:
  - **Code submission** — the practical artifact or working deliverable for the day.
  - **Quiz** — a short formative quiz covering the session’s concepts.

### 3.4 CIA Design

- Use auto-grading for the code submission whenever possible, through test cases, CI checks, or structured rubric scoring.
- The quiz should be short, focused, and preferably auto-graded (MCQs, structured short answers).
- Keep the session completion criteria explicit: working submission + quiz score.

### 3.5 Final Project / Hackathon

- The SEE event is a **project, hackathon, or live demonstration** that integrates the workshop activities.
- It should reward synthesis, design thinking, and working artifact quality, not merely completion of individual sessions.

---

## 4. 3-0-0 Course Assessment Strategy

### 4.1 Assessment Architecture

- **2 IA + 1 SEE** is the required model.
- The 3-0-0 course is lecture-heavy; assessment must create regular interaction with the content through auto-graded activities.

### 4.2 Activity Count and Format

- **Number of activities = number of lecture sessions.**
- For a typical 45-lecture semester, design **45 auto-graded activities**.
- Activities should be short concept checks, MCQ quizzes, structured analysis problems, or small applied questions directly tied to lecture content.

### 4.3 CIA Design

- Organize the 45 activities into two internal assessment packages.
- Each IA should sample activities from the lecture sequence and include a mix of current-week and cumulative content.
- Auto-grading is critical: use digital quizzes, LMS assessments, or question banks that can be scored automatically.

### 4.4 Evaluation Pattern

- Each IA should include:
  - **One current-session activity** — immediate recall/understanding of the current lecture.
  - **One earlier-session activity** — spaced retrieval from prior lectures.
  - **One unknown-related activity** — a novel application or context-linked question.
- This pattern ensures that IA is not only a memory test but also a transfer check.

### 4.5 SEE Design

- The final SEE should remain a traditional summative exam, but it must also reflect the course’s active learning through the 45 activities.
- Preserve a clear split between:
  - **Conceptual mastery**
  - **Analytic / applied reasoning**
- Include at least one question or item that draws on a related but unseen context.

---

## 5. Cross-Cutting Rules for All 1-1-1 Course Types

- **Design with explicit traceability.** Every activity must map to one or more COs and at least one assessment event.
- **Use the “current/previous/unknown” sampling rule in every evaluation.** This is the core pattern for robust formative and summative assessment.
- **Prefer auto-graded components.** The more auto-graded items included, the more scalable the course becomes.

---

## 6. Example Assessment Blueprint

| Course Type | Assessment Model | Activity Count | Session Evaluation | Final SEE |
|---|---|---|---|---|
| 1-1-1 | CIA + SEE | 15 | current + previous + unknown | Theory + practical lab exam |
| 0-0-2 | CIA + project / hackathon | sessions count | Every session: code submission + quiz | Project/hackathon/presentation |
| 3-0-0 | 2 IA + 1 SEE | 45 auto-graded activities | IA1/IA2 each sample current + prior + unknown | Traditional SEE with transfer question |

---

## 7. Implementation Notes

- 1-1-1 design should preserve the integrated nature of lecture, tutorial, and lab; the evaluation pattern makes the course cumulative without adding extra sessions.
- 0-0-2 design should preserve workshop momentum; daily assessment should be lightweight but reliable.
- 3-0-0 design should turn lecture time into active learning through frequent auto-graded checks rather than passive note-taking.

This file may serve as the assessment anchor for course files built on these L-T-P patterns.
