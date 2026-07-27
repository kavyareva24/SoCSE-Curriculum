# Studio Course Guidelines (0-0-2)

Purpose: Practical guidance for teachers designing activities and assessments for a studio-style course (0-0-2). These courses prioritise doing, iteration, collaboration, and demonstrable artifacts over lectures.

Principles
- Active creation: students learn by building, testing, documenting, and iterating.
- Alignment: every activity must map to at least one Course Outcome (CO) and be tagged as Awareness/Advanced in the course file (§3/§14 mapping).
- Continuous feedback: provide frequent, rapid, low-stakes feedback loops (daily/weekly checkpoints).
- Portfolio-first: every assessed deliverable must be portfolio-ready (README, tests, demo notes).
- Equity by design: structure activities so students with weaker preparation can follow scaffolded paths to the same deliverable.

Course structure (recommended rhythm)
- Weekly 2-hour studio session (0-0-2): combination of short facilitation (15–30 min), paired/group work, and drop-in mentoring.
- Sprint cadence: 2–3 week micro-sprints culminating in a deliverable or demo.
- Checkpoints: at least one checkpoint each studio meeting where teams show progress (code, tests, docs).

Activity types
- Micro-challenges (30–90 minutes): focused tasks that teach one technique (unit testing, profiling).
- Sprint projects (2–3 weeks): small system features or integrations tied to COs.
- Collaborative builds: pair or triad work with defined roles (owner, reviewer, tester).
- Bug-bounties / debugging clinics: push students to read, interpret, and fix failing systems.
- Exploratory demos: short student-led demos of experiments; emphasis on iteration and reflection.

Design checklist for each activity
- Learning objective: explicit CO mapping and Bloom level.
- Artefact spec: minimum viable deliverable (code + README + tests + demo script).
- Success criteria: pass/fail acceptance tests + rubric points for quality.
- Timebox & milestones: clear checkpoint schedule inside the sprint.
- Accessibility & equity notes: suggested scaffolds, starter code, and extension tasks.

Assessment strategy
- Overall balance (recommended): Continuous/portfolio: 70–80%, Demonstration + viva: 10–20%, Participation/checkpoints: 10%.
- Instruments
  - Sprint project (major; 40–60%): evaluated by rubric and automated tests.
  - Portfolio snapshot (minor; 10–20%): curated work with reflection.
  - Live demo + viva (10–20%): short demo and Q&A to assess understanding and rationale.
  - Weekly checkpoints & peer review (10%): attendance, checkpoint artefacts, peer feedback.

Rubrics (templates)
- Sprint project (100 pts)
  - Functionality / correctness: 40 pts (automated tests pass)
  - Design & architecture: 20 pts (modularity, patterns, trade-offs)
  - Tests & robustness: 10 pts (unit tests, edge cases)
  - Documentation & reproducibility: 10 pts (README, run instructions, demo script)
  - Iteration & issue tracking: 10 pts (evidence of fixes, issues closed)
  - Reflection & learning notes: 10 pts (what changed, why)

- Demo + viva (20 pts)
  - Demo clarity & reproducibility: 8 pts
  - Conceptual reasoning (why this design): 6 pts
  - Answering edge-case/complexity questions: 6 pts

- Checkpoints / participation (10 pts weekly aggregated)
  - On-time submission of checkpoint: 4 pts
  - Peer feedback quality: 3 pts
  - Engagement during studio: 3 pts

Portfolio & badge integration
- Every studio course requires a course folder in the shared portfolio repo (GitHub/GitLab).
- Students must maintain a single `portfolio/<course_code>/<student>` folder with:
  - README.md (project summary)
  - runnable artifact or link to GitHub Pages / demo video
  - tests and instructions
  - reflection.md (300–500 words)
- Badge criteria (example "Studio-Depth" badge): pass the course exam/threshold, complete two sprint projects with rubric ≥ 70%, maintain portfolio, pass viva.

Facilitation guidance
- Facilitator role: unblock, question, and extend — do not lecture for extended periods.
- Drop-in mentoring: reserve 30–45 minutes each studio for one-on-one help.
- Pairing policy: rotate roles every sprint to distribute experience and reduce gatekeeping.
- Office hours: weekly slots for deeper technical or conceptual help.

Academic integrity & reproducibility
- All code must include a `AUTHORS.md` and a commit history; plagiarism flagged by mismatched commit graphs.
- Use autograders/CI to check basic correctness; require logs showing local testing and iterations.
- For group projects, require a short contributions log describing each student’s inputs.

Inclusion & scaffolding strategies
- Provide a starter scaffold that produces partial credit when extended.
- Offer documented guided steps for the first sprint (walkthrough notebook or video) then progressively remove scaffolds.
- Use mixed-ability pairing: pair a stronger student with a learner, and track role rotation to avoid one-person dominance.

Operational notes
- Lab environment: ensure reproducible containers (Docker) or cloud sandboxes with documented images.
- Autograder: simple unit-test harness to gate core functionality; human rubric grades assess architecture and reflection.
- Timekeeping: require checkpoint artefacts to be timestamped and pushed before the session to count for that meeting.

Mapping to Course File template
- In `Course_File_Template.md` §11: list studio sprints as session blocks, tag each sprint with Merrill phase.
- In §14: include portfolio and sprint projects as instruments; explicitly mark which deliverables contribute to Advanced marks and how they map to CGPA calibration (§14.1).

Examples (quick)
- DSA sprint: implement a memory-efficient graph library with adjacency compression; acceptance tests + performance benchmark.
- DBMS sprint: small write-ahead-log and recovery simulator with crash tests.
- OOP sprint: design a plugin-based architecture with dependency inversion and unit tests.

Quick templates to drop into repos
- `README_TEMPLATE.md` (project summary, run steps, tests)
- `CHECKPOINT_TEMPLATE.md` (what to show at each meeting)
- `REFLECTION_TEMPLATE.md` (prompts for 300–500 words)

Closing notes
- Studios demand continuous instructor attention; keep cohorts small (15–25) and use peer mentors/TA support.
- Measure impact: track portfolio quality, demo outcomes, and placement uptake; iterate the rubric each offering.

---

If you want, I can: (a) add `README_TEMPLATE.md`, `CHECKPOINT_TEMPLATE.md`, and `REFLECTION_TEMPLATE.md` files to the repo now; or (b) create an autograder scaffold for one of the example sprints.