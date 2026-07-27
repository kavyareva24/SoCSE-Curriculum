# Pilot Proposal: Parallel Advanced Stream for DSA, DBMS, and OOP

## Problem statement

- The current strategy emphasises dual-level assessment within one course, which protects the awareness floor and preserves CGPA coherence.
- Yet for placement-critical programming courses such as **DSA, DBMS, and OOP**, some students need more depth than the course’s advanced ceiling can practically deliver within a single classroom and fixed syllabus.
- The specific problem is: **how to provide a deeper, inquiry-based learning path for motivated students without breaking assessment fairness, CGPA coherence, or the awareness floor.**

## Proposed solution

Run a **limited, optional parallel advanced stream** for DSA, DBMS, and OOP where:

- both streams take the **same core assessment** (same exam and same grade scale), so CGPA remains comparable;
- the advanced stream is an **optional, facilitator-led inquiry cohort** that uses project-based, peer-led learning and a flexible topical agenda;
- the awareness stream remains a **structured core delivery** focused on the floor and the shared exam outcomes;
- the advanced stream is explicitly designed to produce **portfolio artifacts and a badge**, giving placement value even without a grade premium.

## Why this proposal would work

1. **Preserves the floor**
   - Same assessment means the awareness level remains the measurable core requirement.
   - The advanced stream still needs to master the same exam topics, so the course’s baseline is not weakened.

2. **Keeps CGPA coherent**
   - If both streams are graded by the same exam, there is no dual-track grade inflation or incomparability.
   - The advanced stream’s extra work is captured in non-grade signals: portfolio, badge, internship selection.

3. **Makes advanced learning meaningful**
   - The advanced path is not just extra homework; it is a structured cohort with a facilitator, real projects, and peer learning.
   - It is limited to placement-critical programming subjects, where the additional depth directly improves employability.

4. **Limits operational risk**
   - Only three courses are involved, so scheduling and staffing remain feasible.
   - The model is a pilot, not an immediate systemwide change.

## Caveats and risks

- **Motivation risk**: If the advanced cohort gets no grade advantage, students may not choose it unless the portfolio/badge value is persuasive.
- **Self-selection bias**: Without active outreach, the advanced stream will attract already confident students, worsening diversity unless faculty actively invite underrepresented learners.
- **Facilitator dependency**: Success depends on an expert facilitator who can keep the cohort exploring while still covering the exam-aligned core.
- **Resource load**: Even three courses require additional scheduling, a second section or time slot, and extra coordination.
- **Implicit signaling**: The advanced stream can still be interpreted as a “better” track; communication must stress that the stream is optional growth, not a remedial label.
- **Assessment alignment**: The advanced stream must still practice the exam format; otherwise, advanced students can become excellent builders but underperform on the shared exam.

## Experiment design

### Objectives

- Validate that the advanced stream attracts motivated students.
- Confirm that the presence of the advanced stream does not reduce awareness-floor performance.
- Test whether portfolio + badge signals increase placement value.
- Evaluate whether the same-exam model is operationally manageable for 3 courses.

### Scope

- Courses: **DSA (Semester 2), DBMS (Semester 3), OOP (Semester 2 or 3)**.
- Cohort: advanced stream is optional and limited to 15–25 students per course.
- Duration: one academic year, with DSA as the first pilot in Semester 2, then DBMS and OOP in the following semester if DSA is stable.

### Structure

- **Awareness stream**
  - Structured delivery of core syllabus.
  - Exam-focused practice, guided problem sets, standard lab exercises.
  - Assessment: same midterm/final exam as the advanced stream.

- **Advanced stream**
  - Project-driven inquiry path with facilitator guidance.
  - Weekly deliverables, peer debugging, exploration of deeper system design.
  - Topics are flexible, but each must map back to exam-aligned core concepts.
  - Students still take the same midterm/final exam as the awareness stream.

### Course-specific design notes

- **DSA**
  - Advanced stream projects: production-style implementations of priority queues, memory-efficient graphs, search heuristics, or small database indexing engines.
  - Core exam alignment: all projects must explicitly surface heap/graph/search concepts and be paired with exam-style problem-solving sessions.

- **DBMS**
  - Advanced stream projects: query engine components, transaction logging simulators, normalization design for real datasets, or a mini-RDBMS feature.
  - Core exam alignment: relational algebra, ER modelling, normalization, indexing strategies.

- **OOP**
  - Advanced stream projects: architected domain models, design-pattern-driven systems, component packaging, and testable APIs.
  - Core exam alignment: class design, inheritance, polymorphism, encapsulation, and UML representation.

### Data collection and metrics

- **Enrollment**: advanced stream opt-in rate, demographic breakdown.
- **Performance**: midterm/final exam pass rates in both streams, grade distribution comparison.
- **Persistence**: retention in the advanced stream through the semester.
- **Portfolio output**: number of project artifacts completed, quality rubric score, recruiter feedback.
- **Perception**: student survey on whether the advanced stream was worth the effort.
- **Placement signal uptake**: number of companies/interviewers that value the badge or portfolio artifact.

### Governance

- Joint oversight by the course team, placement office, and program lead.
- Weekly sync between the awareness and advanced instructors to ensure alignment and avoid content drift.
- Mid-semester review after the first assessment to decide whether to continue, adjust, or stop the pilot.

## Portfolio + badge infrastructure

### Portfolio infrastructure

- Use a shared **GitHub Classroom / GitLab group / internal repo** for advanced stream work.
- Each student maintains a **mini-portfolio** with:
  - project README,
  - problem statement,
  - architecture notes,
  - testing evidence,
  - reflection on what they learned and why the implementation matters.
- Link each project to the course competence it supports (e.g. “This B-tree project maps to DBMS indexing and query optimisation”).
- Faculty reviews portfolios with a simple rubric:
  - technical correctness,
  - system thinking,
  - documentation quality,
  - evidence of iteration and debugging.

### Badge infrastructure

- Issue a **“Depth Certified” badge** for each course on successful completion of the advanced stream.
- Badge criteria:
  1. successful completion of the core course exam,
  2. completion of the advanced portfolio project(s),
  3. evidence of reflection/learning notes,
  4. facilitator confirmation that the student engaged in inquiry-based learning.
- Badge placement:
  - recruiter-facing sheet or transcript supplement,
  - placement portal filter/tag,
  - LinkedIn-style credential if the institute uses digital badge services.
- The badge is not a grade; it is a **placement signal** that the student did more than the baseline.

### Linking portfolio + badge to placement

- The placement office should treat badge earners as a **priority shortlist** for internships and domain-aligned roles.
- During placement drives, students may present their portfolio artifacts in a short demo or one-page summary.
- Recruiters should be told: “This student passed the core course and also completed an advanced project in the same domain.”

## Success criteria

A successful pilot should demonstrate:

- **No reduction in awareness exam performance**.
- **Positive demand** for the advanced stream among students who can benefit from it.
- **High-quality portfolio artifacts** that are usable in placement conversations.
- **Badge recognition** by at least one employer or internship coordinator as a meaningful signal.
- **Operational feasibility** for the faculty and admin team to run the parallel stream.

## Next steps

1. approve the pilot design and nominate faculty pairs for DSA, DBMS, and OOP.
2. configure the portfolio platform and badge rubric before the first semester begins.
3. run the DSA pilot in Semester 2, with a fixed review point after the midterm.
4. if DSA is stable, roll the same model into DBMS and OOP in the next semester.
5. if any core risk appears, pause the advanced stream and reconvene on a more integrated hybrid model.

## Summary

This proposal is a **limited experiment** for three placement-critical programming courses, designed to preserve the shared assessment and the awareness floor while creating a distinct, portfolio-backed advanced learning path. The key success factor is making the advanced cohort valuable beyond grades — through tangible work products, a credible badge, and placement alignment.
