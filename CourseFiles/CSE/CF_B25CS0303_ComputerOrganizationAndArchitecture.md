---
course_code: "B25CS0303"
title: "Computer Organization and Architecture"
programs: [CSE]
semester: III
category: HC
ltpc: "3-0-0-3"
contact_hours_per_week: 3
cie: 50
see: 50
total_marks: 100
aicte_category: PEC
level: "TBD — verify in Curriculum_Visual_Map.md"
status: draft-design
---

# Course File — Computer Organization and Architecture

> **Status: DRAFT DESIGN** — aligned to the 2026 dual-level course-design template and the 3-0-0 theory-course guidelines.
> The awareness floor protects placement readiness, while the advanced ceiling is assessed through higher-order analysis and design tasks.

---

## 0. Course identification 🟢

| Field | Entry |
|---|---|
| Faculty name | ‹…› |
| REVA ID | ‹…› |
| Email | ‹…› |
| Programme | B.Tech — CSE |
| Course code | B25CS0303 |
| Course title | Computer Organization and Architecture |
| Category | HC |
| L-T-P-C | 3-0-0-3 |
| Contact hours / week | 3 |
| Semester | III |
| Section | ‹…› |
| Academic year | ‹…› |
| Course duration (sessions) | 15 teaching weeks × 3 contact hours/week |
| Office / consultation hours | ‹…› |

**School vision / mission:** ‹standard text — unchanged›

---

## 1. Course description 🟢

This course introduces the internal organization of computers from basic logic building blocks to processor execution, memory hierarchy, and input/output systems. Students learn how instructions are fetched, decoded, and executed, how data moves through the system, and how design choices affect speed, efficiency, and reliability.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | Basic computer organization: functional units, instruction cycle, registers, bus structure, von Neumann architecture, instruction execution flow. | 25 Marks |
| 2 | Data representation and arithmetic; instruction formats; addressing modes; CPU control and datapath basics. | 25 Marks |
| 3 | Memory hierarchy; cache organization; virtual memory; I/O organization; interrupts and bus interfacing. | 25 Marks |
| 4 | Pipelining; performance metrics; hazards; parallelism basics; case studies in modern processor design. | 25 Marks |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (floor) | Advanced level — required to exceed 8 CGPA (ceiling) |
|---|---|---|
| 1 | Describe CPU components, explain the fetch-decode-execute cycle, and distinguish between memory, registers, and I/O units. | Compare von Neumann and Harvard organization, analyze timing of instruction execution, and explain performance bottlenecks in a simple datapath. |
| 2 | Recognize instruction formats, addressing modes, and the role of the ALU and control unit in executing simple instructions. | Trace a program through a basic datapath, compare instruction-set design choices, and justify the effect of addressing mode selection on efficiency. |
| 3 | Explain memory hierarchy, cache basics, virtual memory, and the role of interrupts and buses in I/O operations. | Evaluate cache mapping and replacement policies, analyze miss penalties, and justify memory- and I/O-design choices for a target workload. |
| 4 | Understand pipelining concepts, hazards, and basic performance measures such as throughput and latency. | Analyze pipeline hazards and design a performance-improvement strategy for a processor pipeline in an unfamiliar context. |

---

## 4. Course objectives 🟢

- Understand the functional organization of a computer system and explain the interaction among CPU, memory, and I/O units.
- Apply basic computer-architecture concepts to decode, trace, and evaluate instruction execution.
- Analyze memory and I/O design choices with respect to speed, capacity, and cost trade-offs.
- Evaluate processor performance trade-offs using pipelining and parallelism concepts.

---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Level (Awareness / Advanced / Both) 🔵 | POs | PSOs |
|---|---|---|---|---|
| CO1 | Explain the functional units of a computer and the fetch-decode-execute cycle using standard architecture terminology. | Awareness | PO1(3), PO2(2) | PSO1(2) |
| CO2 | Interpret instruction formats, addressing modes, and simple datapath operations to solve basic machine-level problems. | Both | PO1(3), PO2(2), PO3(2) | PSO1(2), PSO2(2) |
| CO3 | Compare memory hierarchy, cache behavior, and I/O organization to evaluate performance trade-offs. | Both | PO1(3), PO2(2), PO3(2), PO4(1) | PSO1(2), PSO2(2) |
| CO4 | Design and explain a simple control/data path for a given instruction sequence. | Both | PO1(3), PO2(3), PO3(2), PO4(2) | PSO1(2), PSO2(3) |
| CO5 | Analyze pipeline and memory-system bottlenecks to recommend suitable performance improvements. | Advanced | PO1(3), PO2(3), PO3(2), PO4(2) | PSO1(2), PSO2(3) |
| CO6 | Evaluate a processor or memory-design choice for a novel application and justify the trade-off. | Advanced | PO1(3), PO2(3), PO3(3), PO4(2), PO5(2) | PSO1(2), PSO2(3) |

---

## 6. Pedagogy 🟢

- Direct instruction for foundational concepts and terminology.
- Demonstration-based teaching using worked examples and simple datapath traces.
- Problem-based learning through short numerical and conceptual exercises.
- Flipped-classroom support through pre-read material and short quizzes.
- Collaborative discussion for comparing design alternatives.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
- M. Morris Mano and Michael D. Ciletti, Computer System Architecture.
- David A. Patterson and John L. Hennessy, Computer Organization and Design.

**References:**
- William Stallings, Computer Organization and Architecture.
- Carl Hamacher, Zvonko Vranesic, and Safwat Zaky, Computer Organization.

**Web / e-books / NPTEL:**
- NPTEL course materials on Computer Organization and Architecture.
- Logisim and CPU simulator demonstrations.
- University-supported lecture notes and open-access videos on pipelining and cache design.

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk:**
- Weekly remedial support triggered by IA performance and short topic-wise quizzes.
- Curated worked examples, summary notes, and peer mentoring for core concepts such as instruction cycle and memory hierarchy.
- Scaffolded practice sheets with step-by-step tracing of simple instructions.

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**
- Stretch problems involving pipeline hazard analysis and cache design trade-offs.
- Short comparative case studies requiring students to justify a processor or memory choice for a novel application.
- Optional reading of current processor design reports or architecture notes beyond the prescribed text.

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window |
|---|---|---|---|
| Assignment 1 | Unit 1 & 2 | 5 | Before IA-2 |
| Assignment 2 | Unit 3 & 4 | 5 | Before IA-3 |

**Assignment brief:**
- Assignment 1: Trace a sample instruction sequence and explain instruction formats, addressing modes, and basic datapath behavior.
- Assignment 2: Evaluate a cache or pipelining scenario and justify performance improvements for a given workload.

---

## 10. Prerequisites / pre-reading 🟢

Prerequisite courses: Digital Logic Design / Basic Electronics and Data Structures and Algorithms.

---

## 10.1 🔵 Formative activity design (based on the reference activity bank)

The course uses a sequence of short, low-stakes activities so that CIE is continuous rather than concentrated in a single exam. The activity set below is adapted from the reference file and is intended to be completed in class or as a short post-class submission.

| Activity | Timing | Format | Duration | Marks | Level | COs |
|---|---|---|---|---|---|---|
| Quiz 1 — Computer components and functional units | Week 1 | 10 MCQ/short-answer questions | 10 minutes | 10 × 1 mark | Awareness | CO1 |
| Quiz 2 — Fetch-decode-execute cycle | Week 2 | 10 concept-based questions | 10 minutes | 10 × 1 mark | Awareness | CO1 |
| Quiz 3 — Memory organization and storage hierarchy | Week 5 | 10 short questions | 10 minutes | 10 × 1 mark | Awareness | CO3 |
| Quiz 4 — Instruction formats and addressing modes | Week 7 | 10 application-based questions | 10 minutes | 10 × 1 mark | Both | CO2, CO4 |
| Quiz 5 — Pipelining and hazards | Week 13 | 10 short analytical questions | 10 minutes | 10 × 1 mark | Advanced | CO5 |
| Mini-project 1 — Datapath and instruction tracing | Week 8 | Short design note + diagram | 1 week | 5 marks | Both | CO2, CO4 |
| Mini-project 2 — Cache / pipeline design justification | Weeks 14–15 | Report + viva | 2 weeks | 5 marks | Advanced | CO3, CO5, CO6 |

---

## 10.2 🔵 Quiz design (10 questions × 1 mark; 10 minutes each)

Each quiz is a fast, low-stakes formative check and is mapped to one or more COs. The questions are designed to test recall, basic understanding, or simple application, while the later quizzes also include transfer-based reasoning.

### Quiz 1 — Computer components and functional units (CO1)
- Q1. The CPU is responsible for _________.
- Q2. The ALU performs _________ and _________ operations.
- Q3. The control unit generates _________ signals.
- Q4. The Program Counter stores the address of the next _________.
- Q5. Registers are used to store _________ results temporarily.
- Q6. Cache memory is placed between the CPU and _________.
- Q7. The main memory is also called _________.
- Q8. The input/output unit is used to connect the computer to _________.
- Q9. In a von Neumann architecture, instructions and data are stored in the same _________.
- Q10. A computer system is made of processing, memory, and _________ units.

### Quiz 2 — Fetch-decode-execute cycle (CO1)
- Q1. The first step of the instruction cycle is _________.
- Q2. During fetch, the CPU retrieves an instruction from _________.
- Q3. The instruction is placed in the _________ register.
- Q4. Decode means interpreting the instruction’s _________ and operands.
- Q5. Execute means performing the required arithmetic or _________ operation.
- Q6. The Program Counter is updated after each _________.
- Q7. The sequence fetch-decode-execute repeats until the CPU reaches a _________ condition.
- Q8. The CPU uses control signals to direct the _________ path.
- Q9. The instruction register holds the current _________ being executed.
- Q10. The fetch-decode-execute cycle is also called the instruction _________.

### Quiz 3 — Memory organization and storage hierarchy (CO3)
- Q1. Cache is faster than _________ memory.
- Q2. The memory hierarchy is arranged from fastest to _________ capacity.
- Q3. Registers are the _________ and fastest storage in the CPU vicinity.
- Q4. Main memory is typically _________ than cache and slower than registers.
- Q5. Virtual memory extends the apparent size of _________.
- Q6. A cache hit means the required data is found in the _________.
- Q7. A cache miss means data must be fetched from a lower _________.
- Q8. The purpose of cache is to reduce average memory _________ time.
- Q9. ROM is mainly used for storing _________ instructions.
- Q10. The memory hierarchy supports the principle of _________ locality.

### Quiz 4 — Instruction formats and addressing modes (CO2, CO4)
- Q1. An instruction format describes the arrangement of opcode and _________.
- Q2. Immediate addressing uses the operand value embedded in the _________.
- Q3. Direct addressing uses the address stored in the instruction to access _________.
- Q4. Indirect addressing uses a memory location that contains another _________.
- Q5. Register addressing uses data already present in a _________.
- Q6. The ALU receives operands from registers or _________.
- Q7. A datapath is the path used for data movement between functional _________.
- Q8. A control signal enables a specific operation in the _________ unit.
- Q9. The choice of addressing mode affects the speed and _________ of the instruction.
- Q10. A simple datapath can be traced by following the flow of data through the _________ and ALU.

### Quiz 5 — Pipelining and hazards (CO5)
- Q1. Pipelining improves processor performance by overlapping instruction _________.
- Q2. A hazard occurs when instructions compete for the same _________.
- Q3. A data hazard occurs when one instruction needs data from a previous _________.
- Q4. A control hazard is caused by a branch or _________ instruction.
- Q5. Structural hazard occurs when hardware resources are not available for two _________.
- Q6. Throughput measures how many instructions are completed per unit of _________.
- Q7. Latency is the time taken to complete one instruction from start to _________.
- Q8. Forwarding is used to reduce _________ hazards.
- Q9. Pipeline stages are usually arranged as fetch, decode, execute, and _________.
- Q10. A well-designed pipeline reduces idle time and improves overall _________.

---

## 10.3 🔵 Mini-project design brief

### Mini-project 1 — Datapath and instruction tracing (CO2, CO4)
- Task: Students trace a simple instruction sequence and draw a basic datapath diagram showing how operands move through registers, ALU, and control signals.
- Deliverables: one-page note, hand-drawn or digital block diagram, and a 2-minute explanation.
- Assessment focus: correctness of trace, clarity of datapath flow, and ability to explain control decisions.

### Mini-project 2 — Cache / pipeline design justification (CO3, CO5, CO6)
- Task: Students analyze a small cache or pipeline scenario and justify a design choice such as cache size, mapping policy, or hazard-mitigation strategy.
- Deliverables: short report, worked example, and short viva presentation.
- Assessment focus: reasoning quality, trade-off analysis, and ability to justify design decisions for a novel application.

---

## 11. Lesson plan 🟢🔵

| S.No | Planned date | Exec. date | Unit / topic | Merrill phase 🔵 | Activity 🔵 | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
|---|---|---|---|---|---|---|---|---|---|
| 01 | Week 1 | | Unit 1 — Basic computer organization and functional units | Activation | Quiz 1: CPU, ALU, control unit, registers, and memory-type identification. | 7% | A | CO1 | |
| 02 | Week 2 | | Unit 1 — Registers, bus structure, and instruction execution | Demonstration | Quiz 2: fetch-decode-execute cycle with short PC/IR tracing questions. | 13% | A | CO1 | |
| 03 | Week 3 | | Unit 1 — Control unit and datapath basics | Application | Trace a simple instruction through the control and data path in a worksheet. | 20% | A | CO2 | |
| 04 | Week 4 | | Unit 1 — von Neumann vs Harvard organization | Integration | Compare both models in a short note and discuss a suitable application context. | 27% | Adv | CO1, CO2 | |
| 05 | Week 5 | | Unit 2 — Data representation and arithmetic | Activation | Quiz 3: memory organization and storage-hierarchy concepts with basic cache questions. | 33% | A | CO3 | |
| 06 | Week 6 | | Unit 2 — Instruction formats and addressing modes | Demonstration | Complete an addressing-mode worksheet showing operand access steps. | 40% | A | CO2 | |
| 07 | Week 7 | | Unit 2 — ALU, control signals, and micro-operations | Application | Quiz 4: instruction formats and addressing modes with one transfer-based application problem. | 47% | A | CO4 | |
| 08 | Week 8 | | Unit 2 — Instruction set design and datapath trade-offs | Integration | Write a short design memo justifying a datapath choice for a novel processor scenario. | 53% | Adv | CO4, CO6 | |
| 09 | Week 9 | | Unit 3 — Memory hierarchy and cache basics | Activation | Analyze a simple cache scenario using hit/miss calculations. | 60% | A | CO3 | |
| 10 | Week 10 | | Unit 3 — Cache mapping and replacement policies | Demonstration | Solve a cache-mapping worksheet and explain replacement-policy trade-offs. | 67% | A | CO3 | |
| 11 | Week 11 | | Unit 3 — Virtual memory and I/O organization | Application | Complete an interrupt/bus-trace exercise and explain the role of I/O control. | 73% | A | CO3 | |
| 12 | Week 12 | | Unit 3 — I/O and memory design trade-offs | Integration | Mini-project milestone 1: justify a memory and I/O design for a performance-sensitive application. | 80% | Adv | CO3, CO6 | |
| 13 | Week 13 | | Unit 4 — Pipelining and performance metrics | Activation | Quiz 5: pipelining, hazards, and basic performance terminology. | 87% | A | CO5 | |
| 14 | Week 14 | | Unit 4 — Hazards and performance optimization | Application | Analyze a pipeline-hazard case and suggest a mitigation strategy. | 93% | A | CO5 | |
| 15 | Week 15 | | Unit 4 — Case study in modern processor design | Integration | Mini-project presentation and viva: datapath, cache, or pipeline design justification. | 100% | Adv | CO5, CO6 | |

---

## 12. ICT & digital support 🟢

- Logisim for digital logic and datapath visualization.
- CPU simulator tools for tracing instruction execution.
- Interactive memory hierarchy animations and cache simulation demos.
- NPTEL and YouTube lecture modules on pipelining, cache design, and instruction execution.
- Short teacher-prepared slides and worked examples for each unit.

---

## 13. Academic integrity policy 🟢

All evaluation components must be the student’s own work. Plagiarism, unauthorized collaboration, or copying of solution steps in assignments, quizzes, or internal assessments will result in zero marks for the relevant component and may trigger disciplinary action as per institutional policy.

---

## 14. 🔵 Evaluation scheme — dual-level

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
|---|---|---|---|---|---|---|---|
| 1 | Test 1 (IA-1) | 20 | 20 | 14 | 6 | Week 5–6 | CO1–CO3 |
| | Test 2 (IA-2) | 20 | 20 | 14 | 6 | Week 10–11 | CO4–CO6 |
| | Assignment 1 | 5 | 5 | 3 | 2 | Before IA-2 | CO1–CO3 |
| | Assignment 2 | 5 | 5 | 3 | 2 | Before IA-3 | CO4–CO6 |
| 2 | SEE | 50 | 50 | 35 | 15 | End of semester | CO1–CO6 |
| **CIE Total** | | **50** | | | | | |
| **Grand Total** | | **100** | | | | | |

### 14.1 🔵 CGPA calibration check

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | REVA 10-point grade conversion applied to course marks |
| Max % achievable from awareness marks alone | 70% |
| Grade band that % falls into | Below the 8-CGPA band for this course, subject to the institution’s grade table |
| Advanced marks needed to cross 8 CGPA | Approximately 10–12 marks from the advanced component |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | Yes |

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| IA-1 / IA-2 | Short definitions, basic tracing, simple numerical problems, and standard comparison questions | Higher-mark analysis questions requiring transfer to an unfamiliar processor or memory scenario |
| SEE | Standard-case questions across all units with direct application of taught principles | At least one advanced item per unit involving design justification, comparative analysis, or performance evaluation |

---

## 15. 🔵 Result analysis

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 | | | |
| IA-2 | | | |
| SEE | | | |

---

## 16. Learner support tracking 🟢🔵

### 16.1 Remediation (students below floor)

| Sl | SRN | Name | IA | Gap identified | Remedial class dates | Re-assessment result |
|---|---|---|---|---|---|---|

### 16.2 Enrichment (students reaching for ceiling)

| Sl | SRN | Name | Advanced task assigned | Outcome |
|---|---|---|---|---|

---

## 17. 🔵 Track-advice signal

| Field | Entry |
|---|---|
| Prerequisite for a SIG track? | Yes — foundation for Systems, Embedded, Cloud, and AI-accelerator related tracks |
| % students at advanced level (> 75% / 8+ CGPA) | ‹…› |
| Domains where advanced performance clustered | Processor design, memory systems, performance analysis, and architecture trade-offs |
| Note to academic mentors | Students who perform strongly in Units 3–4 are suitable candidates for deeper work in systems and performance-oriented domains. |

---

## 18. CO attainment 🟢

**Target:** 60%

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level 🔵 |
|---|---|---|---|---|---|---|---|
| CO1 | | | | | | | A |
| CO2 | | | | | | | Both |
| CO3 | | | | | | | Both |
| CO4 | | | | | | | Both |
| CO5 | | | | | | | Adv |
| CO6 | | | | | | | Adv |

---

## 19. CO–PO/PSO mapping & overall attainment 🟢

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 | PSO3 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | | | | | | | | | | | 2 | | |
| CO2 | 3 | 2 | 2 | | | | | | | | | | 2 | 2 | |
| CO3 | 3 | 2 | 2 | 1 | | | | | | | | | 2 | 2 | |
| CO4 | 3 | 3 | 2 | 2 | | | | | | | | | 2 | 3 | |
| CO5 | 3 | 3 | 2 | 2 | | | | | | | | | 2 | 3 | |
| CO6 | 3 | 3 | 3 | 2 | 2 | | | | | | | | 2 | 3 | |

**Overall attainment** (Direct 80% + Indirect/Feedback 20%):

| | Internal | External | Grand total (80%+20%) |
|---|---|---|---|
| Target attainment | 60% | 60% | 60% |

---

## 20. Course completion summary 🟢

| Unit | Planned date | Completion date | Remarks |
|---|---|---|---|
| 1 | Week 1–4 | | |
| 2 | Week 5–8 | | |
| 3 | Week 9–12 | | |
| 4 | Week 13–15 | | |

---

## 21. 🔵 Faculty reflection — dual-level health check

- Did the awareness floor genuinely protect placement-readiness? Yes, because the floor covers terminology, basic tracing, and standard application tasks.
- Was the advanced ceiling reached by the expected share of students? To be reviewed after the first offering using IA and SEE performance bands.
- One change to the awareness/advanced split for next offering: Increase the advanced share slightly if many students routinely master the floor but underperform in transfer-based analysis.

---

**Signatures**

Course Faculty: ‹digital signature — name, date› &nbsp;&nbsp;&nbsp; HoD / Director: ‹digital signature — name, date›

