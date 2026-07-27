# Course File: Introduction to C Programming

## 0. Course identification 🟢

| Field | Entry |
|---|---|
| Faculty name | TBD |
| REVA ID | TBD |
| Email | TBD |
| Programme | B.Tech — CSE / ISE / IT / AIML |
| Course code | B25CI0101 / B25CI0102 (shared delivery) |
| Course title | Introduction to C Programming |
| Semester & section | Semester I — Core |
| Academic year | 2026–27 |
| L-T-P | 1-1-1 |
| Course duration (sessions) | 42 (14 weeks × L=1, T=1, P=1) |
| Office / consultation hours | TBD |

**School vision / mission:** ‹standard text — unchanged›

**Program-scheme verification:** Course code and `L-T-P` verified against program schemes: [Docs/CSE-v1.md](Docs/CSE-v1.md), [Docs/ISE-v1.md](Docs/ISE-v1.md), [Docs/CSIT-v1.md](Docs/CSIT-v1.md) — official pattern is `L-T-P = 1-1-0` for B25CI0101. Update faculty/contact fields and session plan if the delivery model requires per-program variations.

**HoD / Program decision (lab integration):** The program scheme lists `L-T-P = 1-1-0`. This course is authored for an integrated delivery model (`1-1-1`) to keep lecture/tutorial/practical aligned in a single course. This is subject to formal approval by the HoD/program governance. HoD waiver/approval (paste line below when obtained):

> HoD approval (lab integrated as `1-1-1`): ‹Name› — Signature: ‹…› — Date: ‹YYYY-MM-DD›

If approval is not granted, change `L-T-P` to `1-1-0` and move lab sessions to the paired course code `B25CI0102` as per program scheme.

---

## 1. Course description 🟢

This course introduces the fundamentals of the C programming language: basic syntax, data types, control structures, functions, arrays, structures and modular program design. It builds practical programming skills for implementing algorithms and solving computational problems.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | Basics: C lexical structure, data types, operators, expressions, input/output, simple programs | 25 |
| 2 | Control flow: decision statements, loops, functions, recursion, scope, storage classes | 25 |
| 3 | Data structures: arrays, strings, structures, arrays of structures | 25 |
| 4 | Composite types: structures, unions, typedef, debugging; mini-project | 25 |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (the floor) | Advanced level — required to exceed 8 CGPA (the ceiling) |
|---|---|---|
| 1 | Understand syntax; write, compile and run simple programs; use variables, operators, simple I/O | Read and refactor code for style/efficiency; explain undefined behaviour and compiler diagnostics; micro-optimise hot inner loops |
| 2 | Correctly use `if/switch`, loops; decompose problems into functions; write simple recursive solutions | Design robust modular APIs; reason about tail recursion, stack usage, and write higher-order abstractions |
| 3 | Use arrays/strings and basic `struct` usage safely | Design and implement algorithms using arrays and `struct`s; detect and fix common errors |
| 4 | Define and use `struct`s and build small programs combining units 1–3 | Design and implement a modular mini-project (with error handling); employ `make` and debugging tools; justify design choices and trade-offs |

**Bloom anchor:** Awareness = Remember/Understand/Apply. Advanced = Analyze/Evaluate/Create.

---

## 4. Course objectives 🟢

- Enable students to read, write, compile and debug C programs for standard problems.
- Teach principled use of arrays and structures to model and manipulate data.
- Develop modular program design and basic software engineering practices (simple build scripts, testing).
- Split programs into source files; build with `gcc` or simple build scripts; link multiple modules.
---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Level (Awareness / Advanced / Both) 🔵 | POs | PSOs |
|---|---|---|---|---|
| CO1 | Write, compile and test C programs for basic problems | Awareness | PO1, PO2 | PSO1 |
| CO2 | Use control constructs and functions to decompose and solve problems | Both | PO1, PO3 | PSO1 |
| CO3 | Manipulate arrays, strings and structures to implement algorithms | Both | PO2, PO3 | PSO1 |
| CO4 | Use structure, array of structures and functions to implement modular programs | Advanced | PO2, PO5 | PSO1 |
| CO5 | Use basic Unix and Windows commands to create, compile, debug and run C programs | Awareness | PO3, PO6 | PSO2 |
| CO6 | Design and implement a modular mini-project demonstrating integration of concepts | Advanced | PO3, PO4 | PSO2 |

---

## 6. Pedagogy 🟢

Lectures with demonstrations (Activation + Demonstration), hands-on lab Application sessions, weekly guided exercises, and a mini-project (Integration). Flipped elements: students read short pre-lab notes and attempt starter problems before lab.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
- Brian W. Kernighan and Dennis M. Ritchie — The C Programming Language (2nd ed.)

**References:**
- K. N. King — C Programming: A Modern Approach
- B. W. Kernighan — C FAQ and online resources

**Web / e-books / NPTEL:**
- NPTEL lectures on Programming in C; GNU `gdb` manuals; selected tutorials on arrays, structures and modular programming.

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

Reaching the floor (awareness level):
- Short remedial workshops after IA-1 for students scoring < 40% in IA-1.
- Curated worked examples, step-by-step lab sheets, peer programming groups.

Reaching the ceiling (advanced level):
- Optional advanced lab tasks and stretch problems (time/space optimizations, advanced algorithm design).
- Mini-research tasks: inspect open-source C code, write a brief critique and improvement plan.

**Remediation triggers:** Students with IA-1 score < 40% will be enrolled in remedial workshops; persistent gaps after IA-2 trigger one-to-one mentoring and re-assessment opportunities.

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window |
|---|---|---|---|
| Assignment 1 (lab + report) | Unit 1 & 2 | 5 | Week 3–5 |
| Assignment 2 (lab + report) | Unit 3 & 4 | 5 | Week 9–11 |

---

## 10. Prerequisites / pre-reading 🟢

**Prerequisite course(s):** None (recommended: basic high-school mathematics). Record any prior exposure gaps in mentoring notes.

Recommended pre-reading: program flowcharts and simple pseudocode.

**Week-0 bridge (optional, recommended for mixed intake):** 2-day bootcamp covering basic command-line skills, GCC toolchain (compile/run), basic Git usage, simple pseudocode → starter problems. Triggered for cohorts where intake gaps are identified.

---

## 11. Lesson plan — tentative transaction dates + session implementation 🟢🔵

| S.No | Week | Type (L/T/P) | Exec. date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
|---:|---:|---|---|---|---|---:|---:|---|---|
| 01 | 1 | L | | Unit 1 — C overview; compilation toolchain; first program | Activation + Demonstration | 2% | A | CO1 | Lecture |
| 02 | 1 | T | | Unit 1 — Short exercises: variables, expressions | Application | 4% | A | CO1 | Tutorial |
| 03 | 1 | P | | Unit 1 — Lab: compile/run first programs; environment setup. Advanced stretch: optional refactor/undefined-behaviour analysis task for fast learners (code-golf, micro-optimisation) | Application + Integration | 6% | Adv | CO1 | Practical (includes advanced challenge) |
| 04 | 2 | L | | Data types, operators, precedence | Demonstration | 8% | A | CO1 | Lecture |
| 05 | 2 | T | | Exercises on expressions and I/O | Application | 10% | A | CO1 | Tutorial |
| 06 | 2 | P | | Lab: small I/O programs | Application | 12% | A | CO1 | Practical |
| 07 | 3 | L | | Control flow: `if`, `switch` | Demonstration | 14% | A | CO2 | Lecture |
| 08 | 3 | T | | Problem-solving with conditionals | Application | 16% | A | CO2 | Tutorial |
| 09 | 3 | P | | Lab: conditional-based programs | Application | 18% | A | CO2 | Practical |
| 10 | 4 | L | | Loops: `for`, `while`, `do-while` | Demonstration | 20% | A | CO2 | Lecture |
| 11 | 4 | T | | Loop-based algorithm exercises | Application | 22% | A | CO2 | Tutorial |
| 12 | 4 | P | | Lab: loop programming tasks. Advanced stretch: write robust, efficient loop solutions (invariants, off-by-one proofs, micro-optimisations) and analyse complexity | Application + Integration | 24% | Adv | CO2 | Practical (includes advanced challenge) |
| 13 | 5 | L | | Functions, parameter passing, scope | Activation + Demonstration | 26% | A | CO2 | Lecture |
| 14 | 5 | T | | Function decomposition exercises | Application | 28% | A | CO2 | Tutorial |
| 15 | 5 | P | | Lab: write and test functions; recursion starter | Application | 30% | A | CO2 | Practical |
| 16 | 6 | L | | Arrays and strings — basics | Demonstration | 32% | A | CO3 | Lecture |
| 17 | 6 | T | | Array/string exercises | Application | 34% | A | CO3 | Tutorial |
| 18 | 6 | P | | Lab: string handling tasks | Application | 36% | A | CO3 | Practical |
| 19 | 7 | L | | Arrays, strings and `struct` introduction | Demonstration | 38% | A | CO3 | Lecture |
| 20 | 7 | T | | Array/string and `struct` exercises | Application | 40% | A | CO3 | Tutorial |
| 21 | 7 | P | | Lab: string handling and programs using array of structures | Application | 42% | A | CO3 | Practical |
| 22 | 8 | L | | Structures, typedefs and modular use | Demonstration + Application | 44% | Both | CO3 | Lecture |
| 23 | 8 | T | | Exercises on struct design and modularization | Application | 46% | Both | CO3 | Tutorial |
| 24 | 8 | P | | Lab: implement struct-based records and tests | Application | 48% | Both | CO3 | Practical |
| 25 | 9 | L | | Debugging common errors and testing strategies | Demonstration + Integration | 50% | A | CO5 | Lecture |
| 26 | 9 | T | | Debugging and fix exercises (gdb traces) | Application | 52% | A | CO5 | Tutorial |
| 27 | 9 | P | | Lab: guided debugging labs; fix logic errors | Application | 54% | A | CO5 | Practical |
| 28 | 10 | L | | Structure, array of structures, typedefs and unions | Demonstration | 56% | A | CO4 | Lecture |
| 29 | 10 | T | | Design exercises using structure and array of structures | Application | 58% | A | CO4 | Tutorial |
| 30 | 10 | P | | Lab: implement structure-based records and programs using array of structures | Application | 60% | A | CO4 | Practical |
| 31 | 11 | L | | Modularization; modular programs | Demonstration + Application | 62% | A | CO4 | Lecture |
| 32 | 11 | T | | Exercises: implement modular programs | Application | 64% | A | CO4 | Tutorial |
| 33 | 11 | P | | Lab: implement modular programs and test cases | Application | 66% | A | CO4 | Practical |
| 34 | 12 | L | | Build practices, modularization | Activation + Demonstration | 68% | Adv | CO4, CO6 | Lecture |
| 35 | 12 | T | | Exercises splitting code across files; use simple build scripts | Application | 70% | Adv | CO6 | Tutorial |
| 36 | 12 | P | | Lab: build with `gcc`/link multiple modules. | Application | 72% | Adv | CO6 | Practical |
| 37 | 13 | L | | Debugging tools (`gdb`) | Demonstration + Application | 74% | A | CO5 | Lecture |
| 38 | 13 | T | | Debugging case studies and test design | Application | 76% | A | CO5 | Tutorial |
| 39 | 13 | P | | Lab: guided debugging labs; memory leak fixes | Application | 78% | A | CO5 | Practical |
| 40 | 14 | L | | Mini-project planning and integration | Problem-centred + Activation | 84% | Adv | CO6 | Lecture |
| 41 | 14 | T | | Project tutorial: test cases, division of work | Integration | 92% | Adv | CO6 | Tutorial |
| 42 | 14 | P | | Mini-project implementation, submission and demo | Integration | 100% | Adv | CO6 | Practical / Demo |

---

## 11.2 Suggested lab activities (mapped to units)

Below are concrete lab/programming activities and experiments faculty can assign or use as in‑lab exercises. They are organised by topic and mapped to the units in §2.

- Basics & Algorithms (Unit 1)
	- Addition of two numbers; compare three numbers; odd/even test; prime test — algorithm + flowchart (hand/diagram) and C implementation.
	- Sum of N numbers; compute GCD — algorithm and C implementation.
	- Small calculator: addition, subtraction, multiplication, division, modulus (variables & expressions).
	- Geometry helpers: area of rectangle, area of circle, distance between two points.

- Decision statements & functions (Unit 2)
	- Compare two numbers; compare three numbers; roots of a quadratic equation (if/else variants).
	- Implement basic calculator using `switch` and functions.
	- Write modular functions: area of rectangle, distance between two points, roots of quadratic.

- Loops & numerical methods (Units 2–3)
	- Sum up to N; evaluate Taylor series using `for` loop.
	- Prime test using `while`; generate prime numbers; compute nCr; generate Fibonacci sequence.

- Arrays & algorithms (Unit 3)
	- Sum of N numbers, find largest/smallest/second largest; compute mean and standard deviation.
	- Horner’s method for polynomial evaluation; Sieve of Eratosthenes for primes.

- Strings & 2D arrays (Unit 3 / Unit 4)
	- String processing: count vowels/consonants; compute string length; concatenate two strings — all without using string library helpers.
	- Two‑dimensional arrays: matrix addition/subtraction; matrix transpose.

- Structures & records (Units 3–4)
	- Structure examples: distance between two points; area calculations (triangle/rectangle/circle); sum of two fractions.
	- Array of structures: CRUD on student records; CRUD on employee/library/product/exam records (basic fileless in‑memory exercises).

- Modularization, build & debug (Unit 4 + CO5)
	- Split programs into source files; build with `gcc` or simple build scripts; link multiple modules.
	- Explore basic Unix/Windows commands: `mkdir`, `cd`, `rm`, `gcc`/`cc`, `gdb`, `vi`/`vim`/`gedit`; find files containing a string (e.g., `grep`/`findstr`); set and export environment variables.
	- Guided debugging labs using `gdb` and basic testcases; simple memory‑safety observations (no `valgrind` required unless available).

- Integration / Mini‑project
	 - Modular mini‑project integrating parsing, arrays/structures, functions with basic tests and README.

### 11.1 Activity rubrics (brief)

Lab rubric (recommended, per lab / out of 10):
- **Functionality (6)** — program produces correct output for specified test cases (Awareness).
- **Robustness & style (2)** — handles edge cases, uses clear variable names, comments (Awareness).
- **Advanced insight (2)** — optional optimisation, principled refactor, memory-safety justification (Advanced).

Tutorial rubric (recommended, per tutorial / out of 4):
- **Correctness (2)** — correct solution to the posed problem (Awareness).
- **Explanation & reasoning (1)** — ability to explain choices and complexity (Awareness/Advanced).
- **Advanced extension (1)** — propose an improvement or alternate design (Advanced).

Use these rubrics to make the floor/ceiling distinction concrete in in-class grading: work that meets only the Awareness criteria maps to the floor; the Advanced columns capture stretch performance required to earn ceiling marks.

## 12. ICT & digital support 🟢

- Lab machines with GCC toolchain and `gdb` installed. Shared Git repository for student projects. Link to course lab materials and sample problems on LMS.

---

## 13. Academic integrity policy 🟢

Standard policy: plagiarism or copying in assignments or project reports results in zero marks for the component and a disciplinary review.

Anti-AI & assessment-hardening measures:

- Use scaffolded, multi-stage submissions for lab assignments (starter code → intermediate checkpoint → final submission) to force incremental work and provenance.
- Require short code walkthrough video or live mini-viva for major assignments/mini-projects to verify authorship.
- Use randomized input cases and personalisation (small data/parameter differences) for automated test harnesses so simple copy-paste solutions fail.
- Apply code-plagiarism detection (similarity tools) and manual inspection for suspicious cases; document findings in the remediation log.
- For high-stakes advanced tasks, include an oral/verbal component (short viva or defence) and design questions that probe design reasoning, not only outputs.

---

## 14. 🔵 Evaluation scheme — dual-level (CORE OF THE TEMPLATE)

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
|---|---|---:|---:|---:|---:|---|---|
| 1 | Test 1 (IA-1) | 20 | 20 | 14 | 6 | Week 6 | CO1–CO3 |
| 2 | Test 2 (IA-2) | 20 | 20 | 14 | 6 | Week 10 | CO3–CO5 |
| 3 | Assignment 1 | 5 | 5 | 3 | 2 | Week 5 | CO1–CO3 |
| 4 | Assignment 2 | 5 | 5 | 3 | 2 | Week 11 | CO4–CO6 |
| 5 | Mini-project (Integration) | 10 | 10 | 4 | 6 | Week 14 | CO6, CO4 |
| 6 | SEE (End Semester Exam) | 40 | 40 | 28 | 12 | Exam | CO1–CO6 |
| **Total** | | **100** | **100%** | **66** | **34** | | |

### 14.1 🔵 The calibration that enforces the CGPA rule

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | 10-point scale; 80% ≈ CGPA 8.0 |
| Max % achievable from awareness marks alone | 66% |
| Grade band that % falls into | Below CGPA 8 (≈ 66% → ~6.6–7 band depending on mapping) |
| Advanced marks needed to cross 8 CGPA | Student must earn significant portion of the 34 advanced marks to reach ≥80% |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | Yes |
| Course-level awareness/advanced split | Course-level decision — faculty must record and justify the split in §14. This Course File uses a 66/34 split only as a working calibration in §14; finalise assessment after internal approval (HoD/program governance) as required. |

HoD confirmation of course-level awareness/advanced split: ‹Name / HoD› — Date: ‹YYYY-MM-DD› (pending)

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| IA-1 | Short-answer, code-writing for standard cases (parts A/B) | One medium novel-problem (trace or extend) |
| IA-2 | Mixed code-writing and short debugging tasks | One advanced design/analysis question and one optimization task |
| SEE | Full-length paper: majority are standard-case problems across units | At least one or two high-mark advanced questions (novel problem/design) |

---

## 15. 🔵 Result analysis — banded to detect the two levels

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared, awareness-solid) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 | | | |
| IA-2 | | | |
| Assignment 1 | | | |
| Assignment 2 | | | |
| Mini-project | | | |
| SEE | | | |

---

## 16. Learner support tracking 🟢🔵

### 16.1 Students below the floor (per IA) — remediation

| Sl | SRN | Name | IA | Gap identified | Remedial class dates | Re-assessment result |
|---|---|---|---|---|---|---|

### 16.2 Students reaching for the ceiling — enrichment

| Sl | SRN | Name | Advanced task assigned | Outcome |
|---|---|---|---|---|

| | No. of students | Action taken |
|---|---|---|
| Below floor (slow learners) | | Remedial sessions, peer tutoring |
| At ceiling (fast learners) | | Advanced tasks, project extension |

---

## 17. 🔵 Track-advice signal (links course → SIG track choice)

| Field | Entry |
|---|---|
| Is this a prerequisite for a SIG track? | Yes — foundational for Systems, Embedded, and low-level tracks |
| % of students at advanced level (> 75% / 8+ CGPA) | ‹to be filled after results› |
| Domains where advanced performance clustered | Algorithmic and systems-style tasks |
| Recommended note to academic mentors | Students strong on CO4–CO6 recommended for Systems / Embedded SIGs. |

---

## 18. CO attainment 🟢

**Set target:** 60

| CO | IA1 | IA2 | A1 | A2 | Mini-project | SEE | Direct attainment | Level (A/Adv) 🔵 |
|---|---|---|---|---|---|---|---|---|
| CO1 | | | | | | | Awareness |
| CO2 | | | | | | | Both |
| CO3 | | | | | | | Both |
| CO4 | | | | | | | Advanced |
| CO5 | | | | | | | Awareness |
| CO6 | | | | | | | Advanced |

---

## 19. CO–PO/PSO mapping & overall attainment 🟢

**Strength: 1 = Low, 2 = Medium, 3 = High.**

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PSO1 | PSO2 |
|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | 1 | 1 | 1 | 1 | 3 | 1 |
| CO2 | 3 | 2 | 2 | 1 | 1 | 1 | 3 | 1 |
| CO3 | 2 | 3 | 2 | 1 | 1 | 1 | 3 | 1 |
| CO4 | 1 | 3 | 2 | 2 | 1 | 1 | 2 | 2 |
| CO5 | 1 | 2 | 3 | 1 | 2 | 2 | 1 | 3 |
| CO6 | 1 | 1 | 3 | 3 | 1 | 2 | 1 | 3 |

---

## 20. Course completion summary 🟢

| Unit | Planned date (week) | Completion date | Remarks |
|---|---|---|---|
| 1 | Week 1–3 | | |
| 2 | Week 4–6 | | |
| 3 | Week 7–9 | | |
| 4 | Week 10–14 | | Mini-project |

---

## 21. 🔵 Faculty reflection — dual-level health check

- Did the awareness floor genuinely protect placement-readiness for the weakest students? ‹Faculty to answer at close›
- Was the advanced ceiling reached by roughly the expected share, or did it collapse / go unassessed? ‹Faculty to answer at close›
- One change to the awareness/advanced split for next offering: ‹Faculty suggestion›

---

**Signatures**

No streaming policy: Students will NOT be streamed into separate sections based on ability; differentiation is achieved through assessment design (awareness vs advanced). Faculty/HOD must confirm this policy for the program offering.

Course Faculty — ‹Name, Signature›   Date: ‹YYYY-MM-DD›

HoD / Director — ‹Name, Signature›   Date: ‹YYYY-MM-DD›

Review log: Reviewer — `reva-course-reviewer` run on 2026-06-09; verification produced a NOT READY verdict pending HoD confirmation and signatures. Paste external review notes or HoD responses here.

---

## 22. 🔵 Implementation strategy — Merrill's First Principles

See template §22 for phase definitions. This course's §11 plan covers Activation, Demonstration, Application and Integration; ensure at least one Advanced-level Application/Integration session per unit (weeks 6, 9, 11 and mini-project weeks).

### 22.1 Phase-coverage check 🔵

| Check | Entry |
|---|---|
| All five Merrill phases used at least once per unit | Yes |
| §11 sessions using Activation = lecture + demonstration | 01, 05, 12 |
| §11 sessions delivering Advanced-level activities | 09, 12, 13, 14 |
| ✅ Ceiling taught (≥1 Adv activity per unit, not only assessed) | Yes |
