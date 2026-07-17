---
Course: Data Structures (C)
Course Code: B24CS0501
Credits: 3
L-T-P: 3-1-0
Prerequisite: Basic C programming (Introduction to C Programming or equivalent)
Semester: Odd / 2026 Scheme
Duration: 15 weeks
---

# Course File: Data Structures (C)

## 0. Course Overview
This course covers dynamic memory management, pointers, structures, and core data structures: linked lists, stacks, queues, trees, and an introduction to graphs. It is designed as a 1-1-1 style course (lecture, tutorial, lab rhythm) following the REVA 2026 design strategy.

## 1. Course Outcomes (COs)
Define 4–6 COs anchored to student demographics and industry needs.

- CO1 (Remember→Apply): Explain and apply dynamic memory, pointers, and structures in C to implement basic data types.
- CO2 (Understand→Apply): Implement and analyze linear data structures (linked lists, stacks, queues) for common operations and applications.
- CO3 (Apply→Analyze): Design and implement tree-based structures (BST) and basic graph representations, and use them for searching and traversal.
- CO4 (Analyze→Evaluate): Debug, test, and evaluate data structure implementations for correctness, complexity, and code quality; document design choices.
- CO5 (optional — Advanced): Extend basic structures with advanced features (circular lists, headers, priority queues) and reason about trade-offs.

Each CO maps to activities and assessments in the traceability section below.

## 2. Mapping of Units to COs

- Unit 1 (Pointers, Dynamic Memory, Structures) → CO1, CO4
- Unit 2 (Linked Lists) → CO2, CO4
- Unit 3 (Stacks, Queues; applications) → CO2, CO4
- Unit 4 (Trees, BST, Graph intro) → CO3, CO4, CO5

## 3. Detailed Syllabus (Unit-wise)

### Unit 1: Dynamic Memory & Structures (approx. Weeks 1–4)
- Declaring pointer variables, pointer arithmetic, null and generic pointers, pointer-to-pointer.
- Dynamic memory allocation: malloc/calloc/realloc/free; dangling pointers and safe patterns.
- Dynamic arrays and passing arrays to functions.
- Structures in C: nested structures, arrays of structures, passing structures to functions, self-referential structures.
- Intro to Abstract Data Types (ADTs) and classification of data structures.

Learning activities: pointer tracing exercises, small allocator-style labs, structure design tasks.

### Unit 2: Linked Lists (approx. Weeks 5–7)
- Singly linked lists (with and without header node), circular linked lists, doubly linked lists (with and without header).
- Operations: insertion, deletion, traversal, search, concatenation, reversal.
- Applications: implementing queues and stacks via lists; Round Robin scheduling algorithm (conceptual application).

Learning activities: implement list ADT, debugging broken-list exercises, small project to model a task queue.

### Unit 3: Stacks & Queues (approx. Weeks 8–10)
- Stack ADT: array (dynamic) and linked representations; push/pop, overflow/underflow handling.
- Applications: infix→postfix conversion, postfix evaluation.
- Queue ADT: array (circular) and linked implementations; priority queue basics; scheduling examples.
- Lab activities: implement stack-based expression evaluator, queue-based scheduler simulator.

### Unit 4: Trees & Graphs (approx. Weeks 11–15)
- Trees: terminology, binary trees, Binary Search Tree (BST) — array and linked representations, insert/search/delete, traversals (inorder, preorder, postorder).
- Applications of BST for searching; complexity analysis.
- Introduction to graphs: terminology, types, adjacency matrix/list representations; basic traversal concepts (BFS/DFS overview) — implementation optional / conceptual.

Learning activities: implement BST operations, traverse and test, small comparison of BST vs. sorted array search.

## 4. Activity Design (15 activities; distributed across lecture/tutorial/lab)
Each activity maps to one or more COs and has a floor version + optional advanced extension.

Activity list (one per week, mapped to weekly triplet):

1. Pointer basics & tracing (CO1) — tutorial exercise + short written justification [A]
2. Dynamic memory lab: simple allocator and free (CO1, CO4) — lab submission + tests [A]
3. Structures & nested records design (CO1) — lab: build employee record ADT [A]
4. Dynamic arrays & passing arrays to functions (CO1) — tutorial + auto-graded tests [A]
5. Singly linked list implementation (CO2) — lab: create/insert/delete [A]
6. Linked list debugging challenge (CO2, CO4) — fix broken code + explanation [A]
7. Circular & doubly linked lists (CO2) — advanced extension: header node patterns [Adv]
8. Stack ADT and array implementation (CO2) — lab + infix/postfix demo [A]
9. Postfix evaluation and expression conversion (CO2, CO4) — tutorial + coding [A]
10. Queue ADT: circular array & linked queue (CO2) — lab [A]
11. Priority queues & scheduling application (CO2, CO5) — advanced extension [Adv]
12. Binary trees & traversals (CO3) — lab: implement traversals [A]
13. BST implementation: insert/search/delete (CO3) — lab + tests [A]
14. BST applications: searching and simple performance comparison (CO3, CO4) — mini-project checkpoint [A/Adv]
15. Introduction to graphs, BFS/DFS conceptual lab, revision and synthesis (CO3, CO4) — capstone integration [A]

Notes:
- At least 5 activities must be auto-gradable (unit tests, MCQs). Marked activities include lab submissions with test harnesses.
- Each activity file/folder should be submitted to the course GitHub repo in the lab session; CI runs unit tests where possible.

## 5. Weekly Session Plan (15-week outline)

Week 1: Lecture — pointers; Tutorial — pointer tracing; Lab — pointer exercises (Activity 1)
Week 2: Lecture — dynamic memory; Tutorial — memory patterns; Lab — allocator exercises (Activity 2)
Week 3: Lecture — structures; Tutorial — structure design; Lab — employee ADT (Activity 3)
Week 4: Lecture — dynamic arrays & passing arrays; Tutorial — examples; Lab — auto-graded tests (Activity 4)
Week 5: Lecture — linked list theory; Tutorial — list problems; Lab — implement singly linked list (Activity 5)
Week 6: Lecture — list operations; Tutorial — edge cases; Lab — debugging list (Activity 6)
Week 7: Lecture — circular/doubly lists; Tutorial — compare patterns; Lab — advanced list (Activity 7)
Week 8: Lecture — stacks; Tutorial — stack algorithms; Lab — stack ADT (Activity 8)
Week 9: Lecture — infix/postfix; Tutorial — conversions; Lab — postfix evaluator (Activity 9)
Week 10: Lecture — queues; Tutorial — circular queue; Lab — queue ADT (Activity 10)
Week 11: Lecture — priority queues & scheduling; Tutorial — applications; Lab — priority example (Activity 11)
Week 12: Lecture — trees fundamentals; Tutorial — tree properties; Lab — traversals (Activity 12)
Week 13: Lecture — BST operations; Tutorial — proofs and complexity; Lab — implement BST (Activity 13)
Week 14: Lecture — BST applications and performance; Tutorial — compare search strategies; Lab — checkpoint project (Activity 14)
Week 15: Lecture — graphs intro & revision; Tutorial — final MCQ + justification; Lab — synthesis capstone (Activity 15) + SEE prep

## 6. Assessment Architecture (Following the 2026 strategy)

Total: CIA 50 marks + SEE 50 marks

CIA (50 marks):
- Weekly tests (theory + practical): 15 marks — short quizzes across weeks (best 10 counted). Auto-graded MCQs + one short coding snippet justification. (~1.5 marks/test)
- Lab submissions (auto-graded + manual quality): 15 marks — graded across labs (auto tests + rubric)
- Tutorial problem sets and assignments: 10 marks — correctness + explanation
- Mini-project / checkpoint(s): 10 marks — CO-mapped deliverable (floor + optional advanced feature)

SEE (50 marks):
- Theory: MCQ + justifications — 20 marks (auto-graded MCQ + faculty/AI-assisted rubric for justifications)
- Lab exam — known programs: 20 marks (student implements programs based on semester labs)
- Lab exam — unknown program: 10 marks (novel problem testing transfer of knowledge)

Assessment rules and policies:
- Makeup tests: scheduled repeats for missed weekly tests; same marks cap.
- Auto-grading: Provide unit tests and CI workflows for lab submissions where feasible.
- AI tool policy: During CIA, limited AI assistance allowed for code templates and debugging discussion; for SEE lab exams, AI tool policy is course-specific — typically no external AI/code-generation allowed unless explicitly permitted and monitored.

## 7. Traceability Table (sample excerpt)

| Activity / Assessment | CO1 | CO2 | CO3 | CO4 | CO5 |
|---|---:|---:|---:|---:|---:|
| Activity 1 (pointers) | ✓ | | | ✓ | |
| Activity 5 (singly list) | | ✓ | | ✓ | |
| Weekly test midterm | ✓ | ✓ | | ✓ | |
| Lab exam (known) | | ✓ | ✓ | ✓ | |
| Lab exam (unknown) | | ✓ | ✓ | ✓ | ✓ |

## 8. Rubrics & Grading Notes
- Lab submissions: automated tests (functional correctness) = 70%; code quality & documentation = 30%.
- Tutorial problem sets: correctness = 80%; explanation/justification = 20%.
- Mini-project: functionality = 60%; design & explainability = 30%; optional advanced features = 10%.

## 9. Feedback & Turnaround Targets
- Weekly test auto-grades: same day.
- Lab auto-grades: within 24 hours.
- Tutorial problem set feedback: within one week.

## 10. Resources & Suggested Reading
- Kernighan & Ritchie, The C Programming Language (for pointer & C idioms)
- Weiss / Goodrich, Data Structures & Algorithm texts (student-friendly editions)
- Online: Coursera/edX modules for visualizing data structures; GitHub Classroom for labs.

## 11. AI Use and Responsible Tooling
- Include at least one activity introducing responsible AI-assisted coding: students must critique AI-generated code, propose fixes, and document tests (mapped to CO4).
- Explicit AI policy for SEE will be stated in the course-specific exam instructions.

---
Generated using REVA 2026 course-design strategy templates; tailored to DS-1 syllabus.
