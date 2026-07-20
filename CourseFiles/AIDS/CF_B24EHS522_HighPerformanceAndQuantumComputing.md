---
course_code: "B24EHS522"
title: "High Performance and Quantum Computing"
programs: [CSE, ISE, IT, AIML, AIDS, IoT, Cyber Security]
semester: "VII / VIII (Elective)"
category: "PE / Departmental Elective"
ltpc: "3-0-0-3"
contact_hours_per_week: 3
cie: 50
see: 50
total_marks: 100
aicte_category: "Professional Elective"
level: "A + Adv"
 
---

# Course File — High Performance and Quantum Computing

> **Course code:** B24EHS522  
> **Status:** Revised and aligned to the REVA dual-level course-file template and the 2026 curriculum strategy.  
> **Design intent:** This course is offered as a 3-0-0 theory elective with embedded practical activities and self-learning components, using a dual-level structure with an awareness floor and an advanced ceiling.

---

## 0. Course identification 🟢

| Field | Entry |
|---|---|
| Faculty name | ‹…› |
| REVA ID | ‹…› |
| Email | ‹…› |
| Programme | B.Tech — CSE / ISE / IT / AIML / AIDS / IoT / Cyber Security |
| Course code | B24EHS522 |
| Course title | High Performance and Quantum Computing |
| Category | PE / Departmental Elective |
| L-T-P-C | 3-0-0-3 |
| Contact hours / week | 3 |
| Semester | VII / VIII (Elective) |
| Section | ‹…› |
| Academic year | ‹…› |
| Course duration (sessions) | 14 teaching weeks × 3 contact hours/week |
| Office / consultation hours | ‹…› |

**School vision / mission:** To nurture technically competent, ethically grounded, and innovation-oriented engineering professionals through strong conceptual understanding, problem-solving ability, and industry-relevant practice.

---

## 1. Course description 🟢

This course introduces the principles, architectures, and programming paradigms that enable high-performance computation beyond conventional sequential processing. Students develop foundational knowledge of parallel and distributed computing, performance analysis, GPU acceleration, and quantum computing, while also building advanced competence in optimization, profiling, and hybrid classical-quantum solution design.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | Foundations of high performance computing: motivation, Flynn’s taxonomy, memory hierarchy, cache coherence, speedup, efficiency, scalability, Amdahl’s Law, Gustafson’s Law, TOP500/Green500, cluster basics | 25 Marks |
| 2 | Parallel programming models: OpenMP, MPI, process/thread concepts, synchronization, race conditions, deadlocks, load balancing, data decomposition, Python multiprocessing | 25 Marks |
| 3 | GPU computing and performance optimization: GPU architecture, CUDA/OpenCL basics, memory coalescing, occupancy, profiling, cloud HPC, Docker/Kubernetes, AI accelerators | 25 Marks |
| 4 | Quantum computing: qubits, superposition, entanglement, measurement, gates, circuit model, Deutsch-Jozsa, Grover, Shor (conceptual), VQE, QAOA, hybrid classical-quantum systems | 25 Marks |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (floor) | Advanced level — required to exceed 8 CGPA (ceiling) |
|---|---|---|
| 1 | Explain HPC motivation, Flynn’s taxonomy, memory hierarchy, and basic performance metrics; compute speedup for simple cases | Derive and compare scalability models, analyze NUMA/latency trade-offs, and critique exascale design choices |
| 2 | Write basic OpenMP and MPI programs and identify synchronization issues such as race conditions and deadlocks | Design load-balanced, fault-aware, and communication-optimized parallel solutions for non-trivial workloads |
| 3 | Run a basic CUDA kernel and interpret profiler outputs to identify bottlenecks | Optimize kernel occupancy, memory coalescing, and deployment choices for containerized cloud/HPC environments |
| 4 | Explain qubits, gates, superposition, entanglement, and run a basic circuit on a simulator | Analyze quantum algorithms, compare classical versus quantum approaches, and design a hybrid classical-quantum prototype |

---

## 4. Course objectives 🟢

- Introduce the fundamentals of HPC systems, performance metrics, and parallel architecture.
- Develop competence in shared-memory, distributed-memory, and GPU-based programming models.
- Enable analysis and optimization of performance using profiling and benchmarking tools.
- Introduce quantum computing concepts, algorithms, and hybrid classical-quantum applications for industry and research readiness.

---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Level (Remember / Understand / Apply / Analyse / Evaluate / Create) 🔵 | POs | PSOs |
|---|---|---|---|---|
| CO1 | Describe the fundamental concepts of HPC, including Flynn’s taxonomy, memory hierarchy, performance metrics, and scalability laws. | Remember / Understand | PO1, PO2 | PSO1 |
| CO2 | Explain parallel programming models such as OpenMP, MPI, and the theoretical basis of quantum bits, superposition, and entanglement. | Understand | PO1, PO5 | PSO1 |
| CO3 | Implement basic shared-memory, distributed-memory, and GPU-based solutions for computationally intensive problems. | Apply | PO3, PO5 | PSO1 |
| CO4 | Analyze performance bottlenecks, synchronization issues, and scalability limitations using profiling and benchmarking tools. | Analyse | PO2, PO4, PO5 | PSO1, PSO2 |
| CO5 | Evaluate the suitability of classical HPC and quantum approaches for realistic engineering and scientific problems. | Evaluate | PO2, PO4, PO6, PO8 | PSO2 |
| CO6 | Design and develop a hybrid classical-quantum or optimized HPC prototype for a real-world scenario. | Create | PO3, PO4, PO9, PO10, PO11 | PSO2 |

---

## 6. Pedagogy 🟢

The course will be delivered through direct instruction, problem-based learning, flipped learning, collaborative learning, case analysis, experiential lab work, and guided mini-project work.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
- Grama, Gupta, Karypis, Kumar — Introduction to Parallel Computing, Pearson.
- Nielsen & Chuang — Quantum Computation and Quantum Information, Cambridge University Press.
- Kirk & Hwu — Programming Massively Parallel Processors, Morgan Kaufmann.

**References:**
- Pacheco & Malensek — An Introduction to Parallel Programming, Morgan Kaufmann.
- Rieffel & Polak — Quantum Computing: A Gentle Introduction, MIT Press.
- Hennessy & Patterson — Computer Architecture: A Quantitative Approach, Morgan Kaufmann.
- NVIDIA developer documentation on CUDA and Nsight.
- Intel VTune documentation and HPC best practices.

**Web / e-books / NPTEL:**
- NPTEL courses on HPC and quantum computing.
- IBM Quantum Learning Platform.
- Google Colab GPU/TPU runtimes.
- MIT OpenCourseWare resources on parallel computing and quantum information.

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk of not clearing it:**
- Scaffolded worked examples and simplified analogies for parallelism and quantum concepts.
- Guided worksheets, paired mentoring, and focused remedial practice before internal assessments.
- Template-based lab exercises with stepwise instructions.

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**
- Advanced reading, paper critique, and design-oriented stretch assignments.
- Optimization and benchmarking tasks using profilers and modern HPC tooling.
- Hybrid classical-quantum prototype work with presentation and critical reflection.

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window | Level (Awareness / Advanced) |
|---|---|---|---|---|
| Assignment 1 | Unit 1 & 2 | 5 | Before IA-2 | Awareness |
| Assignment 2 | Unit 3 & 4 | 5 | Before IA-3 | Advanced |

---

## 10. Prerequisites / pre-reading 🟢

- Data Structures and Algorithms
- Computer Organization and Architecture
- Operating Systems
- Basic Linear Algebra and Probability
- Programming proficiency in C/C++ or Python

> 🔵 Prerequisite performance is used to guide mentoring and track choice, as the course has a clear placement-readiness floor and research-readiness ceiling.

---

## 11. Lesson plan — tentative transaction dates + session implementation 🟢🔵

| S.No | Planned date | Exec. date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
|---|---|---|---|---|---|---|---|---|---|
| 01 | Week 0 | | Bridge — architecture and math refresher | Activation | Diagnostic quiz and concept recap | 100% | A | CO1 | Bridge course |
| 02 | Week 1 | | Unit 1 — HPC motivation and Flynn’s taxonomy | Problem-centred + Activation | Case study on modern HPC systems | 25% | A | CO1 | |
| 03 | Week 2 | | Unit 1 — memory hierarchy and cache coherence | Demonstration | Diagram-based explanation and worked examples | 50% | A | CO1 | |
| 04 | Week 3 | | Unit 1 — performance metrics, Amdahl’s/Gustafson’s laws | Application | Short problem-solving session on speedup and efficiency | 75% | A | CO1, CO2 | |
| 05 | Week 4 | | Unit 1 — TOP500/Green500 and cluster basics | Integration | Poster on energy-aware HPC | 100% | Adv | CO1, CO5 | |
| 06 | Week 5 | | Unit 2 — OpenMP and loop parallelization | Demonstration | Hands-on OpenMP lab | 25% | A | CO2, CO3 | |
| 07 | Week 6 | | Unit 2 — MPI and collective communication | Application | Distributed sum / matrix multiplication exercise | 50% | A | CO2, CO3 | |
| 08 | Week 7 | | Unit 2 — synchronization, races, deadlocks | Problem-centred | Debugging and reasoning on synchronization failures | 75% | A | CO4 | |
| 09 | Week 8 | | Unit 2 — load balancing and multiprocessing | Integration | Mini-hackathon on parallel sorting | 100% | Adv | CO3, CO4 | |
| 10 | Week 9 | | Unit 3 — GPU architecture and CUDA basics | Demonstration | GPU execution demonstration | 25% | A | CO2, CO3 | |
| 11 | Week 10 | | Unit 3 — memory coalescing and occupancy | Application | CUDA kernel optimization task | 50% | A | CO3, CO4 | |
| 12 | Week 11 | | Unit 3 — profiling, cloud HPC, Docker/Kubernetes | Integration | Profiler-based bottleneck analysis | 100% | Adv | CO4, CO5 | |
| 13 | Week 12 | | Unit 4 — qubits, superposition, entanglement, gates | Demonstration | Quantum circuit construction using Qiskit | 25% | A | CO2 | |
| 14 | Week 13 | | Unit 4 — Grover, Deutsch-Jozsa, VQE/QAOA | Application | Simulation-based analysis and report | 75% | Adv | CO4, CO5 | |
| 15 | Week 14 | | Unit 4 — hybrid quantum-classical prototype showcase | Integration | Mini-project presentation and viva | 100% | Adv | CO6 | Capstone |

---

## 12. ICT & digital support 🟢

- OpenMP and GCC toolchain
- MPI implementation (OpenMPI/MPICH)
- NVIDIA CUDA Toolkit and Nsight
- Intel VTune profiler
- IBM Quantum Experience / Qiskit / Qiskit Aer
- Google Colab GPU/TPU environments
- NPTEL and MIT OpenCourseWare resources
- Online visualizations for architecture and quantum circuits

---

## 13. Academic integrity policy 🟢

All submitted work must be original. Plagiarism in any evaluation component will attract zero marks. Use of AI-based coding assistance must be disclosed; conceptual understanding and viva will be used to verify independent competence. Proper citation of references and external code is mandatory.

---

## 14. 🔵 Evaluation scheme — dual-level

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
|---|---|---|---|---|---|---|---|
| 1 | Test 1 (IA-1) | 20 | 20 | 14 | 6 | ‹…› | CO1–CO3 |
| | Test 2 (IA-2) | 20 | 20 | 14 | 6 | ‹…› | CO4–CO6 |
| | Assignment 1 | 5 | 5 | 3 | 2 | ‹…› | CO1–CO3 |
| | Assignment 2 | 5 | 5 | 3 | 2 | ‹…› | CO4–CO6 |
| 2 | SEE | 50 | 50 | 35 | 15 | End of semester | CO1–CO6 |
| **Total** | | **100** | **100%** | **70** | **30** | | |

### 14.1 🔵 CGPA calibration check

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | Institutional marks-to-grade-point conversion |
| Max % achievable from awareness marks alone | 70% |
| Grade band that % falls into | Below the 8-CGPA band |
| Advanced marks needed to cross 8 CGPA | Additional advanced marks are required beyond the awareness-only performance |
|  Calibration confirmed (awareness-only < 8 CGPA) | Yes |

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| IA-1 / IA-2 | Short concept, direct application, and basic problem-solving items | Higher-order analysis, comparative reasoning, and design-oriented prompts |
| SEE | Standard-case conceptual and applied questions across all units | At least one advanced item per unit with evaluation and design emphasis |

---

## 15. 🔵 Result analysis

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 | | | |
| IA-2 | | | |
| Assignment 1 | | | |
| Assignment 2 | | | |
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
| Prerequisite for a SIG track? | Yes — suitable for AI/ML, Data Engineering, Cloud/HPC, and Emerging Systems tracks |
| % students at advanced level (> 75% / 8+ CGPA) | ‹…› |
| Domains where advanced performance clustered | HPC systems, optimization, GPU programming, quantum algorithms |
| Note to academic mentors | Students showing strong advanced performance in Units 3–4 are suitable for research-oriented and high-performance computing pathways |

---

## 18. CO attainment 🟢

**Target:** 60% attainment

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level 🔵 |
|---|---|---|---|---|---|---|---|
| CO1 | | | | | | | A |
| CO2 | | | | | | | A |
| CO3 | | | | | | | A |
| CO4 | | | | | | | Adv |
| CO5 | | | | | | | Adv |
| CO6 | | | | | | | Adv |

---

## 19. CO–PO/PSO mapping & overall attainment 🟢

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PSO1 | PSO2 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 3 | 1 |
| CO2 | 3 | 1 | 1 | 1 | 3 | 1 | 1 | 1 | 1 | 1 | 2 | 3 | 1 |
| CO3 | 2 | 2 | 3 | 2 | 3 | 1 | 1 | 1 | 2 | 1 | 2 | 3 | 2 |
| CO4 | 2 | 3 | 2 | 3 | 3 | 1 | 2 | 1 | 2 | 1 | 2 | 3 | 3 |
| CO5 | 2 | 3 | 2 | 3 | 2 | 2 | 2 | 2 | 2 | 2 | 3 | 2 | 3 |
| CO6 | 2 | 3 | 3 | 3 | 3 | 2 | 2 | 2 | 3 | 3 | 3 | 2 | 3 |

---

## 20. Course completion summary 🟢

| Unit | Planned date | Completion date | Remarks |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |

---

## 21. 🔵 Faculty reflection — dual-level health check

- Did the awareness floor genuinely protect placement-readiness? ‹…›
- Was the advanced ceiling reached by the expected share of students? ‹…›
- One change to the awareness/advanced split for next offering: ‹…›

---

## 22. Question paper blueprint and assessment alignment

| Bloom level | Marks weight | CO coverage | Awareness marks | Advanced marks |
|---|---|---|---|---|
| Remember | 15% | CO1 | 15% | — |
| Understand | 20% | CO1, CO2 | 15% | 5% |
| Apply | 20% | CO3 | 10% | 10% |
| Analyse | 20% | CO4 | 5% | 15% |
| Evaluate | 15% | CO5 | — | 15% |
| Create | 10% | CO6 | — | 10% |
| **Total** | **100%** | CO1–CO6 | **70%** | **30%** |

---

## 23. CO/PO/PSO attainment and continuous improvement

| Attainment type | Method | Target |
|---|---|---|
| Direct assessment | Weighted average of assignments, quizzes, lab/self-learning tasks, mini-project, capstone, and SEE | ≥ 60% students scoring ≥ 60% in CO-mapped assessment |
| Indirect assessment | Course-exit survey and feedback | ≥ 70% students reporting agreement |
| CO attainment | 80% direct + 20% indirect | Target Level 3 |
| PO/PSO attainment | Computed from CO–PO/PSO matrix | Target Level 3 |
| Closing the loop | Review after each offering and update activities, tools, and rubrics as needed | Continuous improvement |

---

**Signatures**

Course Faculty: ‹Khandgonda Nitin, 20th,july,2026› &nbsp;&nbsp;&nbsp; HoD / Director: ‹digital signature — name, date›
