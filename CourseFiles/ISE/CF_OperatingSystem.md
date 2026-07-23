---
course_code: "B25IS0404"
title: "Operating Systems (Linux based)"
programs: [ISE]
semester: IV
category: HC
ltpc: "2-0-1-3"
contact_hours_per_week: 4
cie: 50
see: 50
total_marks: 100
aicte_category: PCC
level: "Dual-level (A+Adv)"
status: designed
---

# Course File — Operating Systems (Linux based)

> **Status: DESIGNED** — This file is a complete course design for the ISE offering. Review with the curriculum committee before final verification.

---

## 0. Course identification 🟢

| Field | Entry |
|---|---|
| Faculty name | TBD |
| REVA ID | TBD |
| Email | TBD |
| Programme | B.Tech — ISE |
| Course code | B25IS0404 |
| Course title | Operating Systems (Linux based) |
| Category | HC |
| L-T-P-C | 2-0-1-3 |
| Contact hours / week | 4 |
| Semester | IV |
| Section | TBD |
| Academic year | 2026-27 |
| Course duration (sessions) | 30 Lectures + 15 Lab Sessions |
| Office / consultation hours | TBD |

**School vision / mission:**
- **Vision:** To be an international center of excellence in computer science and engineering education and research, fostering innovation and leadership for societal development.
- **Mission:** To impart quality education through industry-aligned curriculum, state-of-the-art infrastructure, active research, and ethical values, preparing students for global opportunities.

---

## 1. Course description 🟢

This course explores the fundamental principles, design, and implementation of modern operating systems, with a strong focus on Linux systems. Students will learn process management, CPU scheduling, inter-process communication, concurrency, deadlocks, memory virtualization, storage structures, and file systems. Through integrated laboratory sessions, students will acquire practical skills in Linux shell programming, Unix system call programming (using C), process manipulation, synchronization primitives (mutexes/semaphores), and memory diagnostics.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | **Introduction & Process Management:** Operating System structure, system calls, OS operations, processes: state transition, PCB, context switching, process creation/termination. CPU Scheduling: scheduling criteria, non-preemptive vs preemptive algorithms (FCFS, SJF, Priority, Round Robin). Practical: installation & navigation of Linux, basic Shell scripting (control structures, variables), process control calls (`fork`, `exec`, `wait`, `exit`). | 25 Marks |
| 2 | **Process Synchronization & Deadlocks:** Concurrency, Race Condition, Critical Section Problem, Peterson's Solution. Synchronization hardware, Mutexes, Semaphores, Classic Problems (Bounded Buffer, Readers-Writers). Deadlocks: System model, characterization, Prevention, Avoidance (Banker's Algorithm), Detection, and Recovery. Practical: IPC using pipes and FIFOs, multithreaded programming using Pthreads, synchronization using mutexes and semaphores, deadlock simulation. | 25 Marks |
| 3 | **Memory Management:** Background, Address Binding, Logical vs Physical Address Space, Dynamic Loading/Linking. Contiguous Allocation, Paging (hardware support, protection, shared pages), Segmentation. Virtual Memory: Demand Paging, Copy-on-Write, Page Replacement Algorithms (FIFO, Optimal, LRU). Practical: Linux memory diagnostics tools (`vmstat`, `free`, `/proc/meminfo`), memory allocation simulators, implementation of Page Replacement Algorithms in C. | 25 Marks |
| 4 | **Storage & File Systems:** File concept, Access methods, Directory structure, File system mounting, protection. File system implementation: Directory implementation, Allocation methods (Contiguous, Linked, Indexed), Free space management. Disk structure, Disk scheduling (FCFS, SSTF, SCAN, LOOK). Linux Systems: Kernel structure, Virtual File System (VFS), process representation (`task_struct`). Practical: Unix file system calls (`open`, `read`, `write`, `close`, `stat`), implementation of Disk Scheduling Algorithms, Linux process tracing (`strace`), Linux kernel compilation exploration. | 25 Marks |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (floor) | Advanced level — required to exceed 8 CGPA (ceiling) |
|---|---|---|
| 1 | Explain OS structures and process lifecycles. Calculate waiting and turnaround times for standard scheduling algorithms. Write basic Shell scripts and execute process spawning with `fork` and `exec`. | Optimize CPU scheduling parameters. Analyze context-switching overheads in multi-core systems. Develop shell programs with signal handling (`SIGINT`, `SIGCHLD`) and dynamic process monitoring. |
| 2 | Identify critical section risks. Implement thread creation using standard Pthreads. Resolve basic synchronization tasks using mutex locks. Simulate Banker's deadlock avoidance. | Implement lock-free synchronization primitives using atomic operations. Analyze and debug complex synchronization anomalies (Priority Inversion, Deadlock Livelock). Solve multi-resource Banker's algorithm with dynamic resource Allocation under concurrency. |
| 3 | Explain physical and virtual address mapping. Calculate paging offsets. Implement page replacement policies (FIFO, LRU) programmatically under test conditions. | Analyze Translation Lookaside Buffer (TLB) miss penalties. Design custom memory pools and dynamic paging simulators. Interpret Linux page faults and analyze memory fragmentation metrics. |
| 4 | Explain file directories and storage structures. Apply disk scheduling heuristics (FCFS, SSTF, SCAN). Perform file input/output operations using standard system calls. | Analyze directory search complexities and design indexing schemes. Evaluate Linux Ext4 filesystem structure and write kernel module explorations (e.g., file descriptors and inode metadata analysis). Optimize disk I/O scheduling in virtualized environments. |

---

## 4. Course objectives 🟢

- To understand the structural components, architectures, and design principles of operating systems.
- To analyze process scheduling, synchronization, and deadlock management strategies in concurrent environments.
- To study physical and virtual memory systems, pagination, and page performance optimizations.
- To evaluate logical and physical architectures of file systems, storage allocations, and disk I/O protocols.
- To implement Linux-based system programming skills using shell scripts, system calls, and synchronization APIs.

---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Level (Awareness / Advanced / Both) 🔵 | POs | PSOs |
|---|---|---|---|---|
| CO1 | Describe operating system architectures, system call structures, and process state transitions using Linux constructs. | Awareness | PO1, PO2, PO5, PO10 | PSO1 |
| CO2 | Implement and optimize concurrent execution, scheduling algorithms, and process control mechanisms using Unix APIs. | Both | PO1, PO2, PO3, PO4, PO5 | PSO1, PSO2 |
| CO3 | Construct multithreaded programs and solve process synchronization and deadlock problems using mutexes, semaphores, and Banker's algorithm. | Both | PO1, PO2, PO3, PO4, PO5 | PSO1, PSO2, PSO3 |
| CO4 | Model physical and virtual memory spaces and optimize page replacement strategies under varying reference workloads. | Both | PO1, PO2, PO3, PO4 | PSO1, PSO2 |
| CO5 | Design secure storage layouts and apply disk scheduling heuristics to maximize I/O utilization and storage efficiency. | Both | PO1, PO2, PO3, PO4, PO5 | PSO1, PSO2 |
| CO6 | Investigate Linux internal subsystems (such as process structures or file decriptors) individually or in teams, and formulate reports with analytical evaluations. | Advanced | PO2, PO4, PO5, PO9, PO10, PO12 | PSO1, PSO3 |

---

## 6. Pedagogy 🟢

This course follows a combined lecture-theory and practical lab model (aligned with the 2-0-1 credit pattern):
1. **Direct Instruction (Theory):** 2 hours per week focused on conceptual foundations, mathematical calculations (scheduling, memory mapping, disk movement), and logical algorithms.
2. **Integrated Labs:** 2 hours per week. A 110-minute cycle including concepts activation (10m), code walkthrough/implementation demo (20m), hands-on practice & programming application (60m), group integration/debugging (10m), and formative quiz/checkpoint (10m).
3. **Spaced Retrieval:** Weekly assessments testing current-week, previous-week, and unseen transfer application items to build retention.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
- Abraham Silberschatz, Peter Baer Galvin, and Greg Gagne. *Operating System Concepts*, 10th ed., Wiley, 2018.
- Robert Love. *Linux Kernel Development*, 3rd ed., Addison-Wesley Professional, 2010.

**References:**
- William Stallings. *Operating Systems: Internals and Design Principles*, 9th ed., Pearson, 2017.
- W. Richard Stevens and Stephen A. Rago. *Advanced Programming in the UNIX Environment*, 3rd ed., Addison-Wesley Professional, 2013.
- Michael Kerrisk. *The Linux Programming Interface: A Linux and UNIX System Programming Handbook*, No Starch Press, 2010.

**Web / e-books / NPTEL:**
- NPTEL Course on Operating Systems (IIT Kharagpur / IIT Madras)
- OSTEP (Operating Systems: Three Easy Pieces) online book: `https://pages.cs.wisc.edu/~remzi/OSTEP/`
- Linux Documentation Project (LDP): `https://tldp.org/`

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk:**
- **Scaffolded Code Templates:** Pre-written boilerplates for process control and Pthreads files where students only implement core logic (e.g. fill in the critical section or scheduling logic).
- **Spaced Remedial Clinics:** Dedicated laboratory debugging slots triggered by IA results, focusing on C structural pointers, system-call errors (`errno`), and shell syntax.
- **Visual Simulators:** Interactive animations of paging, scheduling algorithms, and deadlock loops to bridge abstract concepts.

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**
- **Signal-Interrupt Custom Shell:** Create a command shell implementing process piping (`|`), file redirection (`>`, `<`), background processes (`&`), and interrupt trap routines.
- **Lock-Free Queue Implementation:** Develop and profile a lock-free queue using atomic operations (compare-and-swap) and benchmark performance against mutex-locked synchronization.
- **Linux Kernel Modding:** Compile a basic kernel module to retrieve process structures directly from the kernel’s `/proc` descriptor tree and document memory allocations.

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window |
|---|---|---|---|
| Assignment 1 | Unit 1 & 2 | 5 Marks (3 Floor + 2 Ceiling) | Week 7 (prior to IA-2) |
| Assignment 2 | Unit 3 & 4 | 5 Marks (3 Floor + 2 Ceiling) | Week 13 (prior to SEE) |

---

## 10. Prerequisites / pre-reading 🟢

- **Prerequisites:** `B24CI0109` (Introduction to C Programming), `B25CS0303` (Computer Organization and Architecture).
- **Pre-reading:** C pointer manipulation, structures, command-line terminal basics, binary/hex converter math, and logic gates.

---

## 10.1 🔵 1-1-1 Weekly activities & assessment (tabular)

| Week | Topic | Theory & Lab Session Focus | Assessment Components (Current / Previous / Unknown) | Graded Artifact / Evidence | COs | Bloom Level |
|---|---|---|---|---|---|---|
| 1 | OS Architectures & Linux | **Theory:** Kernel-User spaces, Monolithic vs Microkernel.<br/>**Lab:** Navigating Linux, path operations, file permissions. | **Current:** Setup environment, execute basic directory permissions.<br/>**Previous:** None.<br/>**Unknown:** Find files using grep and execute actions via pipelines. | Shell execution logs and screenshot. | CO1 | Understand |
| 2 | Shell Programming | **Theory:** Shell variables, loops, command line arguments.<br/>**Lab:** Shell scripts for system checks. | **Current:** Conditional script parsing text logs.<br/>**Previous:** Search operations inside user folders (Week 1).<br/>**Unknown:** Monitor CPU usage script utilizing system stats. | Executable shell scripts (`.sh`). | CO1 | Apply |
| 3 | Process Control API | **Theory:** Process states, PCB, creation lifecycle.<br/>**Lab:** Unix system calls `fork`, `exec`, `wait`, `exit`. | **Current:** C program executing child execution cycles.<br/>**Previous:** Automate C execution using bash (Week 2).<br/>**Unknown:** Handle orphan and zombie process termination. | Process trace outputs and C source code. | CO2 | Apply |
| 4 | CPU Scheduling algorithms | **Theory:** Scheduling metrics, FIFO/SJF scheduling.<br/>**Lab:** Programmatic implementation of FCFS & SJF. | **Current:** Simulate FCFS/SJF and calculate average waiting time.<br/>**Previous:** Spawning process threads (Week 3).<br/>**Unknown:** Apply SJF on dynamically arriving tasks. | Python/C simulator outputs + manual matrix. | CO2 | Analyze |
| 5 | Priority & RR Scheduling | **Theory:** Preemptive algorithms, Round Robin quantum impact.<br/>**Lab:** Simulator for Priority and RR. | **Current:** Simulate RR and Priority schedules.<br/>**Previous:** Compare RR against FCFS/SJF (Week 4).<br/>**Unknown:** Resolve scheduling with aging constraints. | Algorithm comparison code and wait plots. | CO2 | Analyze |
| 6 | Critical Section & Mutex | **Theory:** Race conditions, hardware test-and-set, Mutex.<br/>**Lab:** Multithreaded C programs using Linux Pthreads. | **Current:** Thread creation sharing memory, protected by Mutex.<br/>**Previous:** Scheduling thread priorities (Week 5).<br/>**Unknown:** Trace race outcomes on global counter without locks. | Thread synchronization C source files. | CO3 | Create |
| 7 | Semaphores & Synchronization | **Theory:** Binary/counting semaphores, classic problems.<br/>**Lab:** Producer-Consumer problem solving using POSIX semaphores. | **Current:** C code for Producer-Consumer with bounded buffer.<br/>**Previous:** Pthread locks (Week 6).<br/>**Unknown:** Solve Reader-Writer starvation variant. | Graded synchronization C code. | CO3 | Create |
| 8 | Checkpoint & Debugging | **Theory:** Deadlock scenarios, conditions.<br/>**Lab:** Diagnosing synchronization bugs using Valgrind/GDB. | **Current:** Debug a concurrent program with a deadlock bug.<br/>**Previous:** Thread tracing (Week 7).<br/>**Unknown:** Debug thread-safety issue in a custom library. | Bug trace report and corrected C files. | CO3 | Apply |
| 9 | Deadlock Avoidance | **Theory:** Resource Allocation Graph, Banker’s Algorithm.<br/>**Lab:** Code implementation of Banker's Algorithm. | **Current:** Banker's program checking safe states.<br/>**Previous:** Simulate resource graph loops (Week 8).<br/>**Unknown:** Banker's algorithm with dynamic resource request. | Banker's source logic + matrices. | CO3 | Analyze |
| 10 | Memory Paging | **Theory:** Base-limit registers, logical-physical translation.<br/>**Lab:** Address translator simulation. | **Current:** Simulate paging address map calculations.<br/>**Previous:** Memory allocation in processes (Week 3).<br/>**Unknown:** Translate multi-level page table offsets. | Address simulation code and verification logs. | CO4 | Apply |
| 11 | Page Replacement-1 | **Theory:** Demand paging, page faults, FIFO, Optimal.<br/>**Lab:** Simulation of FIFO Page Replacement. | **Current:** Count page faults for FIFO on string references.<br/>**Previous:** Memory paging maps (Week 10).<br/>**Unknown:** Predict optimal replacement faults under varying frame buffers. | Page tracing script + results. | CO4 | Analyze |
| 12 | Page Replacement-2 | **Theory:** LRU, thrashing, working-set model.<br/>**Lab:** Simulation of LRU Page Replacement in C. | **Current:** Implement LRU replacement algorithm.<br/>**Previous:** Compare LRU faults with FIFO (Week 11).<br/>**Unknown:** Implement Least-Frequently-Used (LFU) variant. | C code with page hit ratios. | CO4 | Analyze |
| 13 | File System Operations | **Theory:** Inodes, File system structures, Directory allocation.<br/>**Lab:** Access file metadata using `stat` system calls. | **Current:** C program querying inode permissions and file tags.<br/>**Previous:** Paging memory sizes (Week 12).<br/>**Unknown:** Write a custom recursive directory lister. | Unix directory parsing code. | CO5 | Apply |
| 14 | Disk Scheduling | **Theory:** Disk seek geometry, FCFS, SSTF, SCAN.<br/>**Lab:** Disk scheduling seek time simulator. | **Current:** Compute seek movements for SSTF/SCAN.<br/>**Previous:** File manipulation (Week 13).<br/>**Unknown:** Simulate C-LOOK algorithm on boundary sector requests. | Disk simulation script + seek calculations. | CO5 | Analyze |
| 15 | Integrated Project (Linux Internals) | **Theory:** Linux kernel subsystems review.<br/>**Lab:** Read proc tree (`/proc/modules`, `/proc/devices`). | **Current:** Write program reporting memory page usage from `/proc`.<br/>**Previous:** Kernel process control calls (Week 3).<br/>**Unknown:** Profile dynamic kernel context context swaps. | Kernel analytics script and report file. | CO6 | Evaluate |

---

## 11. Lesson plan 🟢🔵

| S.No | Unit / Topic | Merrill Phase 🔵 | Activity 🔵 | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
|---|---|---|---|---|---|---|
| L01 | Unit 1: Operating System Introduction | Activation | Discuss history of OS, relate utility functions to abstract processes. | A | CO1 | Planned week 1 |
| L02 | Unit 1: OS Structures & System Calls | Demonstration | Walkthrough of system calls (file read/write) vs API library calls. | A | CO1 | Planned week 1 |
| P01 | Lab 1: Linux shell navigation | Application | Practice directory commands, execute pipeline scripts and filters. | A | CO1 | Planned week 1 |
| L03 | Unit 1: Process Concept & PCB | Activation | Define Process Control Block fields using real OS representations. | A | CO1 | Planned week 2 |
| L04 | Unit 1: Context Switching & Lifecycle | Demonstration | Illustrate process scheduling queues, context execution swap overheads. | A+Adv | CO1 | Planned week 2 |
| P02 | Lab 2: Shell Programming basics | Application | Write scripts with variables, loops, conditional error checks. | A | CO1 | Planned week 2 |
| L05 | Unit 1: Process Spawning & Control | Demonstration | Walkthrough C program implementing `fork()` tree processes. | A | CO2 | Planned week 3 |
| L06 | Unit 1: Advanced Process Control | Application | Trace memory execution space replacement via `execve()`. | Adv | CO2 | Planned week 3 |
| P03 | Lab 3: Unix Process Spawning | Application | Spawning hierarchies, parent-child signaling, and zombie monitoring. | A+Adv | CO2 | Planned week 3 |
| L07 | Unit 1: CPU Scheduling Criteria | Activation | Establish Gantt chart calculations, trace FCFS and SJF execution. | A | CO2 | Planned week 4 |
| L08 | Unit 1: SJF and Priority Scheduling | Demonstration | Analyze SJF preemptive variants, priority starvation problems. | A | CO2 | Planned week 4 |
| P04 | Lab 4: CPU FCFS/SJF Simulator | Application | Programmatically model CPU scheduling queue and compute parameters. | A | CO2 | Planned week 4 |
| L09 | Unit 1: Round Robin Scheduling | Demonstration | Analyze time slice sizing effect on system behavior. | A+Adv | CO2 | Planned week 5 |
| L10 | Unit 1: Multilevel Queue & Feedback | Integration | Detail scheduling algorithms with feedback priority adjustment. | Adv | CO2 | Planned week 5 |
| P05 | Lab 5: Priority/RR Simulator | Application | Implement preemptive priority scheduler with aging mechanisms. | A+Adv | CO2 | Planned week 5 |
| L11 | Unit 2: Critical Sections & Race | Activation | Explain concurrency risks in global counter updates. | A | CO3 | Planned week 6 |
| L12 | Unit 2: Mutual Exclusion & Hardware | Demonstration | Show hardware solutions (Test-and-Set) and Pthreads Mutex implementation. | A+Adv | CO3 | Planned week 6 |
| P06 | Lab 6: Multithreading in C | Application | Program Pthreads updating arrays, using mutex locks to check race results. | A+Adv | CO3 | Planned week 6 |
| L13 | Unit 2: Semaphores | Demonstration | Detail counting and binary semaphores, identify lock execution order. | A | CO3 | Planned week 7 |
| L14 | Unit 2: Bounded-Buffer & Readers-Writers | Integration | Model Producer-Consumer database access rules. | A+Adv | CO3 | Planned week 7 |
| P07 | Lab 7: Semaphore Synchronization | Application | Implement Producer-Consumer concurrent execution using POSIX Semaphores. | A+Adv | CO3 | Planned week 7 |
| L15 | Unit 2: Deadlock Characterization | Activation | Map necessary conditions for deadlocks, draw resource graphs. | A | CO3 | Planned week 8 |
| L16 | Unit 2: Deadlock Prevention & Safety | Demonstration | Discuss lock order guidelines to prevent deadlock states. | A | CO3 | Planned week 8 |
| P08 | Lab 8: Thread Debugging | Application | Induce deadlocks and isolate bugs using GDB and Valgrind logs. | A+Adv | CO3 | Planned week 8 |
| L17 | Unit 2: Deadlock Avoidance | Demonstration | Step-by-step trace of Banker's safety and request vectors. | A | CO3 | Planned week 9 |
| L18 | Unit 2: Multi-resource Banker | Integration | Analyze performance issues of Banker's safety checks. | Adv | CO3 | Planned week 9 |
| P09 | Lab 9: Banker's Algorithm Program | Application | Build a Banker's safety analyzer in C. | A+Adv | CO3 | Planned week 9 |
| L19 | Unit 3: Address Space & Paging | Activation | Detail base/limit registers and logical to physical page offsets. | A | CO4 | Planned week 10 |
| L20 | Unit 3: Multiple Level Paging | Demonstration | Analyze multi-level memory maps and page-table sizes. | Adv | CO4 | Planned week 10 |
| P10 | Lab 10: Address Paging Simulator | Application | Implement virtual address structure translation mapping. | A+Adv | CO4 | Planned week 10 |
| L21 | Unit 3: Demand Paging & Page Faults | Activation | Describe page fault sequence, copy-on-write optimizations. | A | CO4 | Planned week 11 |
| L22 | Unit 3: FIFO & Optimal Replacement | Demonstration | Calculate page fault lists; describe execution performance. | A | CO4 | Planned week 11 |
| P11 | Lab 11: FIFO Page Replacement | Application | Write code processing reference sequences using FIFO replacement. | A | CO4 | Planned week 11 |
| L23 | Unit 3: LRU & Thrashing | Demonstration | Analyze LRU hardware support, thrashing dynamics. | A+Adv | CO4 | Planned week 12 |
| L24 | Unit 3: Working Set Model | Integration | Contrast page replacement heuristics under local scheduling. | Adv | CO4 | Planned week 12 |
| P12 | Lab 12: LRU & LFU Simulator | Application | Build and execute LRU simulator to measure fault hit ratios. | A+Adv | CO4 | Planned week 12 |
| L25 | Unit 4: File Systems & Mounts | Activation | Identify directories, file attributes, logical permissions. | A | CO5 | Planned week 13 |
| L26 | Unit 4: Allocation Structures | Demonstration | Compare contiguous, linked, and indexed descriptor blocks. | A+Adv | CO5 | Planned week 13 |
| P13 | Lab 13: Unix System IO calls | Application | Read, write, copy files using raw system descriptors. | A+Adv | CO5 | Planned week 13 |
| L27 | Unit 4: Disk Geometry & SSTF | Activation | Detail cylinder seek times; trace FCFS and SSTF disk passes. | A | CO5 | Planned week 14 |
| L28 | Unit 4: SCAN & LOOK Schedulers | Demonstration | Map head turnaround patterns on LOOK and SCAN algorithms. | A | CO5 | Planned week 14 |
| P14 | Lab 14: Disk Seek Simulator | Application | Model disk request queues in C and verify seek outputs. | A+Adv | CO5 | Planned week 14 |
| L29 | Unit 4: Linux Systems Architecture | Activation | Detail kernel file structure (`task_struct`, virtual file descriptor table). | A | CO6 | Planned week 15 |
| L30 | Unit 4: Linux VFS & IPC Internals | Integration | Analyze virtual inode mapping and Linux socket descriptors. | Adv | CO6 | Planned week 15 |
| P15 | Lab 15: Systems Kernel Tracing | Application | Trace program execution context swaps using `strace` and `/proc`. | Adv | CO6 | Planned week 15 |

---

## 12. ICT & digital support 🟢

- **Linux Command Line Environments:** Custom Docker container / VM configurations for students to execute Linux system programming environment without risk to host systems.
- **Valgrind Concurrent Profiling:** Command line tools to identify synchronization pointer memory leaks and concurrency warnings in C program executions.
- **Visual OS Scheduling animators:** Web animators showing process state execution, page table translations, and disk scheduling traces.

---

## 13. Academic integrity policy 🟢

All practical programs, shell scripts, and system call executions must represent individual, original work. Submission of prompts, source codes, and compilation trace logs is required for programming exercises. Any plagiarized code sequences in CIA or SEE practical verification will receive a zero mark.

---

## 14. 🔵 Evaluation scheme — dual-level

This course specifies a structured marks distribution separating basic awareness floor competencies (60% weightage) from advanced ceiling tasks (40% weightage):

| Sl | Component | Marks | Weight % | Awareness Marks (Floor) | Advanced Marks (Ceiling) | Date | COs |
|---|---|---|---|---|---|---|---|
| 1 | Test 1 (IA-1) | 20 Marks | 20% | 12 Marks | 8 Marks | Week 6 | CO1–CO3 |
| 2 | Test 2 (IA-2) | 20 Marks | 20% | 12 Marks | 8 Marks | Week 12 | CO4–CO6 |
| 3 | Assignment 1 | 5 Marks | 5% | 3 Marks | 2 Marks | Week 7 | CO1–CO3 |
| 4 | Assignment 2 | 5 Marks | 5% | 3 Marks | 2 Marks | Week 13 | CO4–CO6 |
| 5 | SEE (Theory) | 25 Marks | 25% | 15 Marks | 10 Marks | End of Sem | CO1–CO6 |
| 6 | SEE (Practical) | 25 Marks | 25% | 15 Marks | 10 Marks | End of Sem | CO1–CO6 |
| | **Grand Total** | **100 Marks** | **100%** | **60 Marks** | **40% Marks** | | |

---

### 14.1 🔵 CGPA calibration check

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | standard percentage conversion: 90%+ = 10, 80%+ = 9, 70%+ = 8, 60%+ = 7, 50%+ = 6, 40%+ = 5 |
| Max % achievable from awareness marks alone | **60%** (corresponds to 60 marks total) |
| Grade band that % falls into | **Grade D / C (Grade Point: 7.0)** |
| Advanced marks needed to cross 8 CGPA | **10 Marks** (required to reach 70% for Grade B / GP: 8.0) |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | **Yes** (60% falls strictly in the 7.0 GP band, preventing students from obtaining 8 CGPA without completing advanced components) |

---

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| **IA-1 (20 Marks)** | 12 Marks: Basic FCFS/SJF Gantt calculations, shell script loops, OS monolithic architectures. | 8 Marks: Multi-threaded Pthreads scheduling, critical section Peterson solutions logic validation. |
| **IA-2 (20 Marks)** | 12 Marks: Pagination offset layouts, FIFO page replacements, scanning disk queues, stat structure parameters. | 8 Marks: Multi-level translation misses, Banker's algorithms with dynamic resource inputs, thrashing diagnostics. |
| **SEE Theory (25 Marks)** | 15 Marks: CPU scheduling calculations, semaphore operations, address paging transitions, disk seek seeks. | 10 Marks: Multi-core synchronization race conditions, directory indexing schemes, Virtual File System kernel maps. |
| **SEE Practical (25 Marks)** | 15 Marks: Write a standard C process spawning script or a Pthread synchronization mutex solution, execute standard Shell commands. | 10 Marks: Modify the custom thread locks to pass unseen test constraints, shell script including interrupt handler. |

---

## 15. 🔵 Result analysis

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 | TBD | TBD | TBD |
| IA-2 | TBD | TBD | TBD |
| SEE | TBD | TBD | TBD |

---

## 16. Learner support tracking 🟢🔵

### 16.1 Remediation (students below floor)

| Sl | SRN | Name | IA | Gap identified | Remedial class dates | Re-assessment result |
|---|---|---|---|---|---|---|
| - | - | - | - | - | - | - |

### 16.2 Enrichment (students reaching for ceiling)

| Sl | SRN | Name | Advanced task assigned | Outcome |
|---|---|---|---|---|
| - | - | - | - | - |

---

## 17. 🔵 Track-advice signal

| Field | Entry |
|---|---|
| Prerequisite for a SIG track? | Yes — Cybersecurity, Enterprise Applications, IoT Specialties |
| % students at advanced level (> 75% / 8+ CGPA) | TBD (available after exams) |
| Domains where advanced performance clustered | TBD |
| Note to academic mentors | Encourage students with advanced scores on sync and scheduling to register for Cloud Engineering and advanced Linux Device Driver tracks. |

---

## 18. CO attainment 🟢

**Target:** 60%

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level 🔵 |
|---|---|---|---|---|---|---|---|
| CO1 | | | | | | | Awareness |
| CO2 | | | | | | | Both |
| CO3 | | | | | | | Both |
| CO4 | | | | | | | Both |
| CO5 | | | | | | | Both |
| CO6 | | | | | | | Advanced |

---

## 19. CO–PO/PSO mapping & overall attainment 🟢

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 | PSO3 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | 1 | - | 2 | - | - | - | - | 1 | - | 1 | 3 | - | - |
| CO2 | 3 | 3 | 2 | 2 | 3 | - | - | - | - | - | - | 1 | 3 | 2 | - |
| CO3 | 3 | 3 | 3 | 2 | 3 | - | - | - | 2 | - | - | 1 | 3 | 3 | 1 |
| CO4 | 3 | 3 | 2 | 2 | 2 | - | - | - | - | - | - | 1 | 2 | 2 | - |
| CO5 | 3 | 3 | 2 | 2 | 2 | - | - | - | - | - | - | 1 | 2 | 2 | - |
| CO6 | 2 | 3 | 2 | 3 | 3 | - | - | - | 3 | 2 | - | 2 | 3 | - | 2 |

---

## 20. Course completion summary 🟢

| Unit | Planned date | Completion date | Remarks |
|---|---|---|---|
| 1 | TBD | | |
| 2 | TBD | | |
| 3 | TBD | | |
| 4 | TBD | | |

---

## 21. 🔵 Faculty reflection — dual-level health check

- Did the awareness floor genuinely protect placement-readiness? TBD
- Was the advanced ceiling reached by the expected share of students? TBD
- One change to the awareness/advanced split for next offering: TBD

---

**Signatures**

Course Faculty: **Faculty Name (TBD), Date** &nbsp;&nbsp;&nbsp; HoD / Director: **Director Name (TBD), Date**
