---
course_code: "TBD"
title: "Operating Systems"
programs: [AIDS, AIML, CSE, CSIT, ISE, IoT]
semester: V
category: HC
ltpc: "3-0-0-3"
contact_hours_per_week: 3
cie: 50
see: 50
total_marks: 100
aicte_category: PCC
level: "TBD — verify in Curriculum_Visual_Map.md"
status: draft
---

# Course File — Operating Systems

> **Status: DRAFT** — This version provides a complete first-pass course-file structure for delivery and review.
> The dual-level design is embedded in the unit scope, lesson plan, and assessment split so the awareness floor and advanced ceiling are explicit.

---

## 0. Course identification 🟢

| Field | Entry |
|---|---|
| Faculty name | To be assigned by the department |
| REVA ID | To be assigned |
| Email | faculty@reva.edu.in |
| Programme | B.Tech — AIDS / AIML / CSE / CSIT / ISE / IoT |
| Course code | TBD |
| Course title | Operating Systems |
| Category | HC |
| L-T-P-C | 3-0-0-3 |
| Contact hours / week | 3 |
| Semester | V |
| Section | To be assigned |
| Academic year | 2026–27 |
| Course duration (sessions) | 16 teaching weeks × 3 contact hours/week |
| Office / consultation hours | Monday–Friday, 3:30–4:30 PM |

**School vision / mission:** To nurture technically competent, ethically grounded, and innovation-oriented engineering professionals through strong conceptual understanding, problem-solving ability, and industry-relevant practice.

---

## 1. Course description 🟢

This course introduces the principles of modern operating systems, including how they organize computer hardware, manage processes and memory, and provide services to users and applications. Students develop both foundational understanding and analytical skills to evaluate scheduling, synchronization, deadlock handling, virtual memory, and file system design.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | Operating System Principles: what Operating Systems do, computer system organization, computer system architecture, Operating System structure, computing environments, Operating System services, user–Operating System interface, system calls and system programs, Operating System structure | 25 Marks |
| 2 | Process Management: process concept, process scheduling, operations on processes, inter-process communication; Threads: overview, multicores programming, multithreading models, thread libraries, threading issues; Process Synchronization: background, the critical section problem, Peterson’s solution, synchronization hardware, semaphores, classical problems of synchronization including the bounded-buffer problem, readers–writers problem, and dining-philosophers problem | 25 Marks |
| 3 | CPU Scheduling: basic concepts, scheduling criteria, scheduling algorithms, multiple processor scheduling, thread scheduling; Deadlock: definition, characteristics, methods of handling deadlocks, deadlock prevention, deadlock avoidance using the banker’s algorithm, deadlock detection and recovery | 25 Marks |
| 4 | Memory Management: background, swapping, contiguous memory allocation, paging, structure of page table, segmentation; Virtual Memory Management: background, demand paging, copy-on-write, page replacement, allocation of frames, thrashing; File System Interface: file concept, access methods, directory and disk structure, file system mounting, file sharing, protection | 25 Marks |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (floor) | Advanced level — required to exceed 8 CGPA (ceiling) |
|---|---|---|
| 1 | Describe what an operating system does, explain the basic system architecture and services, and identify common system calls and OS structures | Analyze the interaction among hardware, OS components, and user interfaces, and compare alternative OS structures for different computing environments |
| 2 | Explain process and thread concepts, identify synchronization primitives, and solve routine examples involving semaphores and scheduling | Evaluate concurrency designs, compare multithreading models, and reason about correctness for classical synchronization problems under realistic conditions |
| 3 | Apply standard CPU scheduling algorithms and explain deadlock concepts and prevention strategies | Compare scheduling policies under different workloads and design or justify deadlock-avoidance and recovery approaches for complex systems |
| 4 | Explain memory allocation, paging, segmentation, demand paging, and basic file-system concepts | Evaluate memory-management trade-offs, justify page-replacement strategies, and analyze file-system design choices for sharing, protection, and performance |

---

## 4. Course objectives 🟢

- Introduce the core principles and architecture of operating systems.
- Develop understanding of process management, synchronization, scheduling, and deadlock handling.
- Build analytical ability to compare memory-management and virtual-memory strategies.
- Strengthen the ability to connect OS concepts with real-world computing environments and file-system design.

---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Level (Awareness / Advanced / Both) 🔵 | POs | PSOs |
|---|---|---|---|---|
| CO1 | Explain the basic purpose, services, architecture, and structure of an operating system | Awareness | PO1, PO2 | PSO1 |
| CO2 | Describe process, thread, and inter-process communication concepts and apply synchronization mechanisms to standard problems | Both | PO1, PO3 | PSO1 |
| CO3 | Analyze CPU scheduling algorithms and deadlock prevention, avoidance, detection, and recovery strategies | Both | PO2, PO3 | PSO1 |
| CO4 | Apply memory management and virtual memory techniques to routine problems | Both | PO1, PO3 | PSO1 |
| CO5 | Evaluate file-system interface, protection, and sharing mechanisms for practical use cases | Advanced | PO2, PO4 | PSO2 |
| CO6 | Compare operating-system design choices for performance, reliability, and modern computing environments | Advanced | PO2, PO4, PO12 | PSO2 |

---

## 6. Pedagogy 🟢

The course will be delivered through direct instruction, concept mapping, worked examples, problem-based learning, short case discussions, and guided analysis of real operating-system behavior.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
- Abraham Silberschatz, Peter Baer Galvin, and Greg Gagne, Operating System Concepts.
- Andrew S. Tanenbaum and Herbert Bos, Modern Operating Systems.

**References:**
- William Stallings, Operating Systems: Internals and Design Principles.
- Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau, Operating Systems: Three Easy Pieces.
- Maurice J. Bach, Design of the Unix Operating System.

**Web / e-books / NPTEL:**
- NPTEL course on Operating Systems
- Linux documentation and tutorials
- OS simulation and visualization resources for process scheduling and memory management

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk of not clearing it:**
- Remedial sessions on core terminology, process concepts, and standard algorithms
- Guided worked examples and stepwise practice for scheduling and memory-management problems
- Peer mentoring and scaffolded revision sheets for key topics

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**
- Comparative analysis tasks on scheduling and memory-management policies
- Short reading assignments on modern OS features such as virtualization and containerization
- Stretch problems requiring design justification, performance reasoning, and case-based evaluation

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window | Level |
|---|---|---|---|---|
| Assignment 1 | Unit 1 & 2 | 5 | Before IA-2 | Awareness |
| Assignment 2 | Unit 3 & 4 | 5 | Before IA-3 | Advanced |

---

## 10. Prerequisites / pre-reading 🟢

Students should have prior familiarity with basic programming constructs, data structures, computer organization, and elementary problem solving.

---

## 11. Lesson plan — tentative transaction dates + session implementation 🟢🔵

| S.No | Planned date | Exec. date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
|---|---|---|---|---|---|---|---|---|---|
| 01 | Week 1 |  | Unit 1 — OS principles and what operating systems do | Activation | Begin with a real-world example of how a laptop or mobile device handles multiple tasks | 6% | A | CO1 |  |
| 02 | Week 1 |  | Unit 1 — Computer system organization, architecture, and OS structure | Demonstration | Explain layered OS design and system organization using a block diagram | 12% | A | CO1 |  |
| 03 | Week 2 |  | Unit 1 — Computing environments, services, and system calls | Application | Demonstrate common system calls and compare OS services across environments | 18% | A | CO1 |  |
| 04 | Week 2 |  | Unit 1 — User–OS interface and system programs | Application + Integration | Compare command-line and graphical interfaces with a practical activity | 25% | Adv | CO1 |  |
| 05 | Week 3 |  | Unit 2 — Process concept, process scheduling, and operations on processes | Activation | Use a simple process-state diagram and classroom example | 31% | A | CO2 |  |
| 06 | Week 3 |  | Unit 2 — Inter-process communication and threads | Demonstration | Demonstrate thread creation and IPC through a small example | 37% | A | CO2 |  |
| 07 | Week 4 |  | Unit 2 — Multithreading models and threading issues | Application | Compare user-thread and kernel-thread models through case discussion | 43% | A | CO2 |  |
| 08 | Week 4 |  | Unit 2 — Process synchronization and classical problems | Integration | Analyze bounded-buffer, readers–writers, and dining-philosophers problems | 50% | Adv | CO2 |  |
| 09 | Week 5 |  | Unit 3 — CPU scheduling concepts and scheduling algorithms | Activation | Work through FCFS, SJF, Round Robin, and priority scheduling examples | 56% | A | CO3 |  |
| 10 | Week 6 |  | Unit 3 — Multiple processor scheduling and thread scheduling | Demonstration | Compare scheduling decisions in multi-core and multi-processor contexts | 62% | A | CO3 |  |
| 11 | Week 7 |  | Unit 3 — Deadlock characteristics, prevention, and avoidance | Application | Apply banker’s algorithm to a classroom scenario | 68% | A | CO3 |  |
| 12 | Week 7 |  | Unit 3 — Deadlock detection and recovery | Integration | Evaluate recovery strategies for a realistic deadlock case | 75% | Adv | CO3 |  |
| 13 | Week 8 |  | Unit 4 — Memory management, swapping, and contiguous allocation | Activation | Use diagrams to explain swapping and contiguous allocation | 81% | A | CO4 |  |
| 14 | Week 9 |  | Unit 4 — Paging, page tables, segmentation, and virtual memory | Demonstration | Compare paging and segmentation with worked examples | 87% | A | CO4 |  |
| 15 | Week 10 |  | Unit 4 — Demand paging, page replacement, thrashing, and file-system interface | Application | Analyze page-replacement decisions and file access methods | 93% | A | CO5 |  |
| 16 | Week 11 |  | Unit 4 — File sharing, protection, and capstone review | Integration | Discuss file-system design trade-offs and complete a mini-case review | 100% | Adv | CO5 |  |

---

## 12. ICT & digital support 🟢

- NPTEL and YouTube lectures on operating systems
- Linux terminal demonstrations and process-management visualizers
- Online simulators for scheduling and paging concepts
- Short articles and documentation on Windows, Linux, and virtualization

---

## 13. Academic integrity policy 🟢

Students must submit their own original work for all assignments, tests, and written tasks. Any evidence of plagiarism, copying, or unauthorized collaboration will result in zero marks for the concerned evaluation component and may lead to disciplinary action as per institutional policy.

---

## 14. 🔵 Evaluation scheme — dual-level

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
|---|---|---|---|---|---|---|---|
| 1 | Test 1 (IA-1) | 20 | 20 | 14 | 6 | Mid-semester | CO1–CO3 |
|  | Test 2 (IA-2) | 20 | 20 | 14 | 6 | Late semester | CO4–CO6 |
|  | Assignment 1 | 5 | 5 | 3 | 2 | Before IA-2 | CO1–CO3 |
|  | Assignment 2 | 5 | 5 | 3 | 2 | Before IA-3 | CO4–CO6 |
| 2 | SEE | 50 | 50 | 35 | 15 | End of semester | CO1–CO6 |
| **CIE Total** | | **50** | | | | | |
| **Grand Total** | | **100** | | | | | |

### 14.1 🔵 CGPA calibration check

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | REVA CBCS grade-point conversion as per academic regulations |
| Max % achievable from awareness marks alone | 70% |
| Grade band that % falls into | Below the 8-CGPA band |
| Advanced marks needed to cross 8 CGPA | A substantial share of the advanced component, approximately 15–20 marks beyond the awareness floor |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | Yes |

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| IA-1 / IA-2 | Short-answer and routine problem-solving questions covering core concepts and standard procedures | One higher-order analytical or design-oriented question per test |
| SEE | Standard-case questions spanning all units and major OS mechanisms | At least one advanced application or evaluation question per unit |

---

## 15. 🔵 Result analysis

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 |  |  |  |
| IA-2 |  |  |  |
| SEE |  |  |  |

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
| Prerequisite for a SIG track? | Yes — suitable for Systems, Software Engineering, Cloud, and Embedded/IoT related tracks |
| % students at advanced level (> 75% / 8+ CGPA) | To be recorded after assessment |
| Domains where advanced performance clustered | Scheduling, concurrency, memory management, and systems design |
| Note to academic mentors | Students showing strong advanced performance should be encouraged to explore systems programming, cloud infrastructure, and performance-oriented electives |

---

## 18. CO attainment 🟢

**Target:** 60%

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level 🔵 |
|---|---|---|---|---|---|---|---|
| CO1 |  |  |  |  |  |  | Awareness |
| CO2 |  |  |  |  |  |  | Both |
| CO3 |  |  |  |  |  |  | Both |
| CO4 |  |  |  |  |  |  | Awareness |
| CO5 |  |  |  |  |  |  | Advanced |
| CO6 |  |  |  |  |  |  | Advanced |
