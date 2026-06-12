# Course File - Dual-Level Design

## Database Management Systems · B25CS0302 · AIML Semester 3

**Template version:** Course_File_Template_DualLevel.md (REVA SoCSE 2026 B.Tech Scheme) Sections marked 🟢 contain content ported from the existing CBCS course file. Sections marked 🔵 are new dual-level additions - placeholders remain where the source file was silent.

## 0\. Course identification 🟢

| Field                       | Entry                                                             |
| --------------------------- | ----------------------------------------------------------------- |
| Faculty name                | Dr. J. Ragaventhiran                                              |
| REVA ID                     | REVA03025                                                         |
| Email                       | [j.ragaventhiran@reva.edu.in](mailto:j.ragaventhiran@reva.edu.in) |
| Programme                   | B.Tech - AIML                                                     |
| Course code                 | B25CS0302                                                         |
| Course title                | Database Management Systems                                       |
| L-T-P-C                     | 1-1-1-3                                                           |
| Semester & section          | 3rd Semester - AIML                                               |
| Academic year               | Even 2026-27                                                      |
| Course duration (sessions)  | 65 sessions                                                       |
| Office / consultation hours | 8:30 am to 4:30 pm                                                |

**School vision:** To produce excellent quality technologists and researchers of global standards in computing and information technology who have the potential to contribute to the development of the nation and society with their expertise, skills, innovative problem-solving abilities, and strong moral and ethical values.

**School mission:**

- To create state-of-the-art computing labs infrastructure and research facilities in information technology.
- To provide a student-centric learning environment through innovative pedagogy and education reforms.
- To encourage research, innovation, and entrepreneurship through industry/academia collaborations and extension activities.
- To organise programmes through club activities for knowledge enhancement in thrust areas of information technology.
- To enhance leadership qualities, enrich personality traits, promote patriotism, and nurture moral and ethical values.

## 1\. Course description 🟢

This course provides a solid technical foundation in the theory and practice of database management systems, covering data modelling, relational database design, SQL programming, and normalization. Using current database products as a case study, students learn to design, develop, and maintain database-driven applications, with emphasis on data independence, integrity, security, recovery, and performance. The course develops the practical skill to move from a conceptual ER model through to a deployed, normalized relational database with working SQL code.

## 2\. Course content (units & weightage) 🟢

| Unit | Syllabus                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Weightage |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| 1    | **Introduction to Databases and Conceptual Modelling:** Introduction to databases, characteristics of the database approach, data models, schemas, instances, database languages and interfaces, high-level conceptual data models for database design. **ER Model:** entity types, attributes, keys, relationship types, weak entity types, ER diagrams. **Practical:** installation and configuration of MySQL; creating databases and tables; working with data types and constraints; defining primary keys and foreign keys; designing and implementing a simple database schema. | 25 Marks  |
| 2    | **Entity-Relationship Modelling and SQL Programming:** ER Model concepts, ER diagrams, mapping cardinalities, weak entity sets, Enhanced ER (EER) Model, specialization and generalization, relational database design from ER Models. **Introduction to SQL:** data types, DDL, DML. **Practical:** CREATE, ALTER, DROP; INSERT, UPDATE, DELETE; constraints; data loading and validation; basic SELECT queries; mini database from ER design.                                                                                                                                        | 25 Marks  |
| 3    | **Advanced SQL:** Retrieving data with SELECT, restricting and sorting, single-row functions, joins, nested subqueries, views, PL/SQL basics, functions and stored procedures. **Practical:** SELECT with filtering and sorting; aggregate functions and GROUP BY; inner/outer/self/cross joins; nested and correlated subqueries; views; PL/SQL blocks, functions, and stored procedures.                                                                                                                                                                                             | 25 Marks  |
| 4    | **Database Design Theory and Normalization:** Informal design guidelines for relation schemas, functional dependencies, normal forms (1NF, 2NF, 3NF, BCNF). **Practical:** identification of functional dependencies; candidate key computation; conversion to 1NF, 2NF, 3NF; BCNF decomposition; comprehensive database design case study.                                                                                                                                                                                                                                            | 25 Marks  |

## 3\. 🔵 Dual-level scope of each unit (KEYSTONE)

This table declares - for each unit - what the **awareness floor** and the **advanced ceiling** mean. Every assessment, rubric, and CGPA calibration derives from it.

| Unit | Awareness level - every student must reach (the floor)                                                                                                                                                                                  | Advanced level - required to exceed 8 CGPA (the ceiling)                                                                                                                                                                                    |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Define database vs. file system; explain ANSI three-schema architecture; identify entity types, attributes, keys, and relationships; draw a correct ER diagram for a given, familiar scenario. Install MySQL and create a basic schema. | Justify design choices in an ER diagram for a novel, multi-constraint scenario; compare alternative modelling decisions (e.g., attribute vs. entity type) with reasoned trade-offs; identify modelling ambiguities and propose refinements. |
| 2    | Map a given ER diagram to relational tables following standard rules; write correct DDL (CREATE, ALTER, DROP) and DML (INSERT, UPDATE, DELETE) for a described schema; identify mapping cardinalities.                                  | Design a complete relational schema from an ambiguous or complex real-world description; evaluate alternative schema choices against constraints; predict and resolve constraint violations before execution.                               |
| 3    | Write SELECT queries with WHERE, ORDER BY, GROUP BY, aggregate functions, and standard joins; create a simple view; write a basic PL/SQL block.                                                                                         | Write correlated subqueries and multi-level nested queries; optimize a query execution plan; design and implement reusable stored procedures and functions for a real-world application requirement.                                        |
| 4    | Identify functional dependencies in a given relation; apply the steps to decompose a relation into 2NF and 3NF; recognize a BCNF violation.                                                                                             | Derive the minimal cover of a dependency set; prove or disprove lossless-join and dependency-preservation properties of a decomposition; redesign a poorly normalized schema for a realistic case study justifying each step.               |

**Bloom anchor:**

| Level                  | Bloom verbs                 | Typical question stem                                                                     |
| ---------------------- | --------------------------- | ----------------------------------------------------------------------------------------- |
| **Awareness (floor)**  | Remember, Understand, Apply | "Define…", "Explain…", "Draw the ER diagram for…", "Write a query that…"                  |
| **Advanced (ceiling)** | Analyze, Evaluate, Create   | "Compare and justify…", "Prove that…", "Design and optimize…", "Evaluate the trade-offs…" |

## 4\. Course objectives 🟢

- Understand database concepts, architectures, and conceptual data modelling.
- Design databases using ER and EER models.
- Develop SQL queries for data definition, manipulation, and retrieval.
- Apply database design principles and normalization techniques.
- Implement database applications using SQL and procedural extensions (PL/SQL).

## 5\. Course outcomes (COs) and PO/PSO mapping 🟢🔵

| CO# | Course outcome                                                                                                          | Level (Awareness / Advanced / Both) 🔵 | POs                                              | PSOs                      |
| --- | ----------------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ------------------------------------------------ | ------------------------- |
| CO1 | Explain database concepts, architectures, and data models.                                                              | Awareness                              | PO1(3), PO2(3), PO3(2), PO4(2), PO5(2), PO10(1)  | PSO1(3), PSO2(3)          |
| CO2 | Design conceptual and logical database schemas using ER/EER models.                                                     | Both                                   | PO1(3), PO2(3), PO3(2), PO4(3), PO5(1)           | PSO1(3), PSO2(3)          |
| CO3 | Construct SQL queries for database creation, manipulation, and retrieval.                                               | Both                                   | PO1(3), PO2(3), PO3(2), PO4(3), PO5(3)           | PSO1(3), PSO2(3), PSO3(3) |
| CO4 | Develop database applications using advanced SQL and PL/SQL constructs.                                                 | Advanced                               | PO1(3), PO2(3), PO3(2), PO4(3), PO5(1)           | PSO1(3), PSO2(3)          |
| CO5 | Apply normalization techniques to design efficient relational databases.                                                | Advanced                               | PO1(3), PO2(3), PO3(2), PO4(3), PO5(1)           | PSO1(2)                   |
| CO6 | Develop and evaluate database solutions individually or in a team, and report results with analysis and interpretation. | Advanced                               | PO3(2), PO5(2), PO8(1), PO9(3), PO10(2), PO11(1) | PSO1(3), PSO2(3)          |

🔵 **Level rationale.** CO1 is Awareness (Bloom: recall/explain). CO2-CO3 span Both levels (standard design/query = Awareness; novel design/optimisation = Advanced). CO4-CO6 are Advanced: they demand creating and evaluating solutions beyond a standard recipe. The Awareness COs (CO1, plus awareness portions of CO2-CO3) cover placement-readiness; the Advanced COs (CO4-CO6) gate the 8+ CGPA band.

## 6\. Pedagogy 🟢

- **Direct instruction** - used throughout for foundational definitions and procedure walkthroughs.
- **ICT and digital support** - YouTube videos, PPTs, and MySQL Workbench demonstrations.
- **Collaborative and cooperative learning** - group-based mini-projects and lab tasks.
- **Differentiated instruction** - separate advanced tasks for high achievers; scaffolded notes and remedial classes for learners below the floor.
- **Flipped classroom** - selected topics pre-assigned via video links; class time used for problem-solving.

## 7\. Textbooks, references, e-resources 🟢

**Textbooks:**

- Abraham Silberschatz, Henry F. Korth, S. Sudarshan - _Database System Concepts_, 6th ed., McGraw Hill, 2010.
- Elmasri & Navathe - _Fundamentals of Database Systems_, 5th ed., Pearson Education, 2007.

**References:**

- C. J. Date - _Database Design and Relational Theory: Normal Forms and All that Jazz_, O'Reilly, 2012.
- Raghu Ramakrishnan & Johannes Gehrke - _Database Management Systems_, 3rd ed., McGraw-Hill, 2003.

**Web / e-resources:** (see §12 for unit-wise links)

## 8\. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) - for students at risk:**

- Remedial sessions triggered when IA-1 score < 40%; identified from §15 result-analysis table.
- Detailed printed/digital notes and worked SQL examples for each unit's core topics.
- Scaffolded lab tasks: students complete partially written queries before writing from scratch.
- Peer mentoring: advanced-level students paired with below-floor learners for lab sessions.

**Reaching the ceiling (advanced level) - for students aiming above 8 CGPA:**

- A separate group assignment (3-4 members) on a database design problem not covered in class (e.g., designing a multi-tenant SaaS schema, query optimisation analysis).
- Optional stretch problems appended to every lab: one advanced-level query optimisation or schema redesign task per unit.
- Reading a relevant research paper or case study (e.g., Google Spanner architecture overview) with a one-page written reflection.
- Extension challenge: students design and document the full schema, ER model, and normalized relations for one of the lab mini-project domains from scratch.

## 9\. Assignments 🟢

| Assignment   | Units covered | Marks | Window      | Nature                                                                 |
| ------------ | ------------- | ----- | ----------- | ---------------------------------------------------------------------- |
| Assignment 1 | Units 1 & 2   | 5     | Before IA-2 | Practical-based; group of 3-4; ER design + schema implementation       |
| Assignment 2 | Units 3 & 4   | 5     | Before SEE  | Practical-based; group of 3-4; advanced SQL + normalization case study |

**Lab mini-project (integrated across all units):** Students design and implement one database-driven application - Library Management System, Hospital Management System, Inventory Management System, Student Information System, or Smart Home Data Management System. Project marks awarded against the Assignment 2 component.

## 10\. Prerequisites / pre-reading 🟢

- Knowledge of any programming language (loops, conditionals, functions).
- Basic understanding of data representation (tables, records, fields) is helpful.

🔵 **Mentoring note:** Prerequisite-course performance (Programming Fundamentals / any Sem-1/2 coding course) is the input academic mentors use to advise track choice. Record SRNs of students who struggled with programming logic - they are at higher risk of falling below the awareness floor in Units 3-4 (SQL procedural extensions).

## 11\. Lesson plan - tentative transaction dates + session implementation 🟢🔵

Each row is one session. The **Merrill phase** and **Activity** columns carry the implementation plan; **Level** shows where the advanced ceiling is _taught_. Planned dates are to be filled before the semester begins; Exec. date and % completion filled as the course runs. The session-count below maps 65 sessions across 4 units (~16 sessions each for Units 1-3, ~17 for Unit 4).

| S.No | Planned date | Exec. date | Unit / topic                                                                | Merrill phase 🔵             | Activity 🔵                                                                                                               | % compl. | Level (A/Adv) 🔵 | CO 🔵         | Remarks |
| ---- | ------------ | ---------- | --------------------------------------------------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------- | -------- | ---------------- | ------------- | ------- |
| 01   | ‹…›          |            | U1 - Intro to databases; file system vs. DBMS                               | Problem-centred + Activation | Present real-world problem: "Why do large hospitals not store records in Excel?" Lecture followed by live comparison demo | 6%       | A                | CO1           |         |
| 02   | ‹…›          |            | U1 - Characteristics of DB approach; three-schema architecture              | Demonstration                | Worked walkthrough of ANSI three-schema layers using MySQL Workbench                                                      | 12%      | A                | CO1           |         |
| 03   | ‹…›          |            | U1 - Data models; schemas; instances                                        | Demonstration                | Lecture + diagram: conceptual → logical → physical, with worked example                                                   | 18%      | A                | CO1           |         |
| 04   | ‹…›          |            | U1 - DB languages and interfaces                                            | Activation + Application     | Recap quiz on §01-03; hands-on: students classify DDL vs DML commands                                                     | 24%      | A                | CO1           |         |
| 05   | ‹…›          |            | U1 - ER Model: entity types, attributes, keys                               | Demonstration                | Lecture followed by step-by-step ER diagram build (Library scenario)                                                      | 29%      | A                | CO2           |         |
| 06   | ‹…›          |            | U1 - ER Model: relationship types, cardinalities                            | Application                  | Guided lab: students draw ER diagram for a given Hospital scenario                                                        | 35%      | A                | CO2           |         |
| 07   | ‹…›          |            | U1 - Weak entity types; ER diagram conventions                              | Application                  | Pair exercise: identify weak entities in an e-commerce scenario; class critique                                           | 40%      | A                | CO2           |         |
| 08   | ‹…›          |            | U1 - **Adv:** Multi-constraint ER design; modelling alternatives            | Application + Integration    | Stretch problem: students compare two ER designs for the same ambiguous domain and justify choice                         | 46%      | Adv              | CO2           |         |
| 09   | ‹…›          |            | U1 Lab - MySQL install; creating databases and tables                       | Application                  | Hands-on: install MySQL Workbench, create schema, define tables with correct data types                                   | 50%      | A                | CO3           |         |
| 10   | ‹…›          |            | U1 Lab - Primary keys, foreign keys, constraints                            | Application                  | Lab task: add PK/FK constraints to the U1 Library schema; test integrity violations                                       | 56%      | A                | CO3           |         |
| 11   | ‹…›          |            | U1 Lab - Simple schema implementation                                       | Integration                  | Mini-task: design and implement a complete schema from a new domain description (Student Information System)              | 62%      | A                | CO3           |         |
| 12   | ‹…›          |            | U1 Lab - **Adv:** Schema refinement and redesign                            | Integration                  | Advanced lab: students identify weaknesses in a given poorly-designed schema and rebuild it                               | 68%      | Adv              | CO6           |         |
| 13   | ‹…›          |            | U1 - Unit summary + Q-paper walkthrough                                     | Activation                   | Recap lecture: awareness-level vs. advanced-level question examples; self-assessment quiz                                 | 75%      | A                | CO1, CO2      |         |
| 14   | ‹…›          |            | U1 - Revision / flipped-classroom debrief                                   | Integration                  | Students present their ER diagrams; peer feedback session                                                                 | 80%      | Both             | CO2, CO6      |         |
| 15   | ‹…›          |            | U1 - Buffer / catch-up / extended activity                                  | ‹…›                          | ‹Faculty to record activity used›                                                                                         | 88%      | A                | ‹…›           |         |
| 16   | ‹…›          |            | U1 - Buffer / advanced stretch                                              | ‹…›                          | ‹Advanced: journal case-study read + 1-page reflection›                                                                   | 100%     | Adv              | CO6           |         |
| 17   | ‹…›          |            | U2 - EER Model: specialization & generalization                             | Problem-centred + Activation | Anchoring problem: "Model a university with students, grad-students, and faculty in one ER." Lecture + demo               | 6%       | A                | CO2           |         |
| 18   | ‹…›          |            | U2 - EER: disjoint vs. overlapping; completeness constraints                | Demonstration                | Worked walkthrough: EER diagram with multiple inheritance levels                                                          | 12%      | A                | CO2           |         |
| 19   | ‹…›          |            | U2 - Relational DB design from ER: mapping rules                            | Demonstration                | Lecture followed by step-by-step ER-to-table mapping (7 rules) using Library schema                                       | 18%      | A                | CO2           |         |
| 20   | ‹…›          |            | U2 - Mapping cardinalities; weak entity sets                                | Application                  | Guided lab: map the Hospital ER from U1 to relational tables                                                              | 24%      | A                | CO2           |         |
| 21   | ‹…›          |            | U2 - **Adv:** Complex ER-to-relational mapping; trade-off analysis          | Application                  | Stretch problem: given two alternative ER designs for the same domain, map both to relations and compare                  | 30%      | Adv              | CO2, CO6      |         |
| 22   | ‹…›          |            | U2 - SQL: data types; DDL (CREATE, ALTER, DROP)                             | Demonstration                | Live coding: CREATE TABLE with constraints; ALTER to add columns; DROP with cascade                                       | 37%      | A                | CO3           |         |
| 23   | ‹…›          |            | U2 - SQL: DML (INSERT, UPDATE, DELETE)                                      | Application                  | Lab task: populate the Library schema; update and delete with WHERE                                                       | 43%      | A                | CO3           |         |
| 24   | ‹…›          |            | U2 - Constraints implementation; data loading                               | Application                  | Lab task: test NOT NULL, UNIQUE, CHECK, FK constraints; load a CSV dataset                                                | 50%      | A                | CO3           |         |
| 25   | ‹…›          |            | U2 - Basic SELECT queries                                                   | Application                  | Guided lab: SELECT with WHERE, ORDER BY; filtering patterns                                                               | 56%      | A                | CO3           |         |
| 26   | ‹…›          |            | U2 Lab - Mini DB from ER design                                             | Integration                  | Integrative lab: students implement their own Inventory System schema end-to-end                                          | 62%      | A                | CO3, CO6      |         |
| 27   | ‹…›          |            | U2 - **Adv:** Predicting and resolving constraint violations                | Integration                  | Advanced lab: given a flawed INSERT script, students identify all violations and fix the schema                           | 68%      | Adv              | CO4, CO6      |         |
| 28   | ‹…›          |            | U2 - Unit summary; IA-1 preparation                                         | Activation                   | Awareness vs. advanced Q examples; practice IA questions; class debrief                                                   | 75%      | Both             | CO1-CO3       |         |
| 29   | ‹…›          |            | U2 - Revision / flipped debrief                                             | Integration                  | Students teach back one mapping rule to the class                                                                         | 88%      | A                | CO2           |         |
| 30   | ‹…›          |            | U2 - Buffer / catch-up                                                      | ‹…›                          | ‹Faculty to record›                                                                                                       | 94%      | A                | ‹…›           |         |
| 31   | ‹…›          |            | U2 - Buffer / advanced stretch                                              | ‹…›                          | ‹Advanced: design a multi-entity EER and map to relations for a novel domain›                                             | 100%     | Adv              | CO6           |         |
| 32   | ‹…›          |            | U2 - **IA-1 Assessment**                                                    | -                            | IA-1 (Units 1 & 2, 40 marks → scaled to 20)                                                                               | -        | Both             | CO1-CO3       |         |
| 33   | ‹…›          |            | U3 - Advanced SQL: SELECT revisited; restricting & sorting                  | Problem-centred + Activation | Anchoring problem: "What are the top-5 most borrowed books last month?" Lecture + live SQL demo                           | 6%       | A                | CO3           |         |
| 34   | ‹…›          |            | U3 - Single-row functions (string, numeric, date)                           | Demonstration                | Live coding walkthrough: UPPER, ROUND, DATE_FORMAT, IFNULL on real data                                                   | 12%      | A                | CO3           |         |
| 35   | ‹…›          |            | U3 - Aggregate functions; GROUP BY; HAVING                                  | Application                  | Guided lab: sales totals by region; filter groups with HAVING                                                             | 18%      | A                | CO3           |         |
| 36   | ‹…›          |            | U3 - Joins: INNER, OUTER (LEFT/RIGHT/FULL)                                  | Demonstration                | Worked examples: compare join types on the Library schema; visualise result sets                                          | 24%      | A                | CO3           |         |
| 37   | ‹…›          |            | U3 - Self-join; cross join                                                  | Application                  | Lab task: employee-manager self-join; generate all seat pairs (cross join)                                                | 30%      | A                | CO3           |         |
| 38   | ‹…›          |            | U3 - Nested subqueries                                                      | Demonstration                | Lecture followed by demonstration: scalar, row, table subqueries in WHERE and FROM                                        | 37%      | A                | CO4           |         |
| 39   | ‹…›          |            | U3 - **Adv:** Correlated subqueries; EXISTS                                 | Application                  | Stretch lab: rewrite a nested query as correlated; compare execution plans in Workbench                                   | 43%      | Adv              | CO4           |         |
| 40   | ‹…›          |            | U3 - Views: creation, usage, updatable views                                | Application                  | Lab task: create role-specific views (e.g., student-facing view hiding salary data)                                       | 50%      | A                | CO4           |         |
| 41   | ‹…›          |            | U3 - PL/SQL basics: blocks, variables, control flow                         | Demonstration                | Live coding: anonymous block with IF-ELSE and loop; output via DBMS_OUTPUT                                                | 56%      | A                | CO4           |         |
| 42   | ‹…›          |            | U3 - Functions and stored procedures                                        | Application                  | Guided lab: write a stored procedure to register a new library member                                                     | 62%      | A                | CO4           |         |
| 43   | ‹…›          |            | U3 - **Adv:** Optimising queries; designing reusable procedures             | Integration                  | Advanced lab: profile a slow multi-join query; add indexes; redesign as a stored procedure                                | 68%      | Adv              | CO4, CO6      |         |
| 44   | ‹…›          |            | U3 Lab - Capstone SQL lab                                                   | Integration                  | Students implement full SQL back-end for their mini-project (queries, views, procedures)                                  | 75%      | Both             | CO3, CO4, CO6 |         |
| 45   | ‹…›          |            | U3 - Unit summary; IA-2 preparation                                         | Activation                   | Awareness vs. advanced Q examples for Unit 3; peer quiz                                                                   | 88%      | Both             | CO3, CO4      |         |
| 46   | ‹…›          |            | U3 - Buffer / revision                                                      | ‹…›                          | ‹Faculty to record›                                                                                                       | 94%      | A                | ‹…›           |         |
| 47   | ‹…›          |            | U3 - Buffer / advanced stretch                                              | ‹…›                          | ‹Advanced: write a trigger-based audit log for the mini-project DB›                                                       | 100%     | Adv              | CO4, CO6      |         |
| 48   | ‹…›          |            | U4 - Informal design guidelines; update anomalies                           | Problem-centred + Activation | Anchoring problem: "Why does this EMPLOYEE table have 1000 redundant rows?" Lecture + demo                                | 6%       | A                | CO5           |         |
| 49   | ‹…›          |            | U4 - Functional dependencies: definitions, inference rules                  | Demonstration                | Worked examples: derive all FDs from a given relation; Armstrong's axioms                                                 | 12%      | A                | CO5           |         |
| 50   | ‹…›          |            | U4 - Candidate keys; prime/non-prime attributes                             | Application                  | Lab task: compute candidate keys for given FD sets                                                                        | 18%      | A                | CO5           |         |
| 51   | ‹…›          |            | U4 - 1NF: definition and conversion                                         | Application                  | Guided exercise: identify and eliminate multi-valued attributes in a messy relation                                       | 24%      | A                | CO5           |         |
| 52   | ‹…›          |            | U4 - 2NF: partial dependencies and decomposition                            | Demonstration                | Lecture followed by step-by-step 2NF decomposition; work through two examples                                             | 30%      | A                | CO5           |         |
| 53   | ‹…›          |            | U4 - 3NF: transitive dependencies and decomposition                         | Application                  | Guided lab: decompose a 2NF relation to 3NF; verify no anomalies remain                                                   | 37%      | A                | CO5           |         |
| 54   | ‹…›          |            | U4 - BCNF: definition and decomposition algorithm                           | Application                  | Pair exercise: apply BCNF to a relation with overlapping candidate keys                                                   | 43%      | A                | CO5           |         |
| 55   | ‹…›          |            | U4 - **Adv:** Minimal cover; lossless-join & dependency preservation proofs | Application                  | Stretch lab: compute minimal cover; prove lossless decomposition using the tableau algorithm                              | 50%      | Adv              | CO5, CO6      |         |
| 56   | ‹…›          |            | U4 - **Adv:** Redesigning a poorly-normalized real schema                   | Integration                  | Advanced case study: students receive a denormalized e-commerce schema and redesign it to BCNF, justifying each step      | 57%      | Adv              | CO5, CO6      |         |
| 57   | ‹…›          |            | U4 Lab - Functional dependency identification                               | Application                  | Lab: given a populated table, discover FDs empirically; compare with given set                                            | 62%      | A                | CO5           |         |
| 58   | ‹…›          |            | U4 Lab - Comprehensive DB design case study (Awareness)                     | Application                  | Lab: full pipeline - ER → relational → normalize to 3NF for the Student Information System                                | 68%      | A                | CO5, CO3, CO2 |         |
| 59   | ‹…›          |            | U4 Lab - **Adv:** Comprehensive DB design case study (Ceiling)              | Integration                  | Advanced lab: extend the case study - normalize to BCNF, prove properties, document trade-offs                            | 75%      | Adv              | CO5, CO6      |         |
| 60   | ‹…›          |            | U4 - Unit summary; IA-2 prep                                                | Activation                   | Awareness vs. advanced Q examples for Unit 4; self-assessment quiz                                                        | 82%      | Both             | CO4, CO5      |         |
| 61   | ‹…›          |            | U4 - **IA-2 Assessment**                                                    | -                            | IA-2 (Units 3 & 4, 40 marks → scaled to 20)                                                                               | -        | Both             | CO3-CO6       |         |
| 62   | ‹…›          |            | All units - Mini-project presentations (Group A)                            | Integration                  | Groups present and demo their database application; Q&A                                                                   | 88%      | Both             | CO6           |         |
| 63   | ‹…›          |            | All units - Mini-project presentations (Group B)                            | Integration                  | Groups present and demo their database application; Q&A                                                                   | 94%      | Both             | CO6           |         |
| 64   | ‹…›          |            | All units - SEE revision: awareness tier                                    | Activation                   | Comprehensive recall/apply questions across all units; worked solutions                                                   | 97%      | A                | CO1-CO5       |         |
| 65   | ‹…›          |            | All units - SEE revision: advanced tier                                     | Activation                   | Advanced question walkthrough: novel-problem items, optimisation and design justification                                 | 100%     | Adv              | CO4-CO6       |         |

🔵 **Level audit:** Sessions 08, 12, 21, 27, 31, 39, 43, 47, 55, 56, 59, 65 are explicitly tagged **Adv** - at least two per unit. Sessions 62-63 (mini-project integration) cover Both. The ceiling is taught, not only assessed.

## 12\. ICT & digital support 🟢

**Unit 1 - Introduction to Databases and Conceptual Modelling**

- Introduction to databases: <https://www.youtube.com/watch?v=T7AxM7Vqvaw>
- Characteristics of the database approach: <https://www.youtube.com/watch?v=wClEbCyWryI>
- Three-schema architecture: <https://www.youtube.com/watch?v=vuXnRRG-m5M>
- ER diagrams: <https://www.youtube.com/watch?v=wOD02sezmX8>
- Concepts of relationships: <https://www.youtube.com/watch?v=n3mHfQft5P8>

**Unit 2 - ER Modelling and SQL Programming**

- Relational model concepts: <https://www.youtube.com/watch?v=Q45sr5p_NmQ>
- Relational model constraints: <https://www.youtube.com/watch?v=uPOGPL2C0_8>
- Transactions, dealing with constraint violations: <https://www.youtube.com/watch?v=lMthy1iwR3s>
- Unary relational operations (SELECT, PROJECT): <https://www.youtube.com/watch?v=8PJGw123zeE>
- Relational algebra set operations: <https://www.youtube.com/watch?v=r6OsT9Zi4Cg>

**Unit 3 - Advanced SQL**

- SQL comprehensive tutorial: <https://www.youtube.com/watch?v=HXV3zeQKqGY>
- Advanced SQL Free online Course: <https://shorturl.at/DgbHM>

**Unit 4 - Database Design Theory and Normalization**

- Informal design guidelines: <https://www.youtube.com/watch?v=mr3fmcMQgdw&t=215s>
- Normalization overview: <https://www.youtube.com/watch?v=xoTyrdT9SZI>
- All normal forms: <https://www.youtube.com/watch?v=EGEwkad_llA>

**Tool:** MySQL Workbench (free) - used for all lab sessions.

## 13\. Academic integrity policy 🟢

Students are expected to follow the Rules of Conduct and Academic Behaviour standards detailed in the Student Regulation Handbook. Failure to comply may result in disciplinary action as stipulated in the Student Regulations.

**Note:** Copying and plagiarism in any form for any evaluation component (including lab work, assignments, and mini-project) will result in zero marks for that component.

## 14\. 🔵 Evaluation scheme - dual-level (CORE OF THE TEMPLATE)

| Sl        | Component                                   | Marks   | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date          | COs     |
| --------- | ------------------------------------------- | ------- | -------- | ----------------------- | ------------------------ | ------------- | ------- |
| 1         | Test 1 (IA-1) - Units 1 & 2, scaled from 40 | 20      | 20       | ≈14                     | ≈6                       | ‹…›           | CO1-CO3 |
|           | Test 2 (IA-2) - Units 3 & 4, scaled from 40 | 20      | 20       | ≈14                     | ≈6                       | ‹…›           | CO3-CO6 |
|           | Assignment 1 - Units 1 & 2, group practical | 5       | 5        | 3                       | 2                        | ‹before IA-2› | CO1-CO3 |
|           | Assignment 2 - Units 3 & 4, group practical | 5       | 5        | 3                       | 2                        | ‹before SEE›  | CO4-CO6 |
| 2         | SEE - all units, 100 marks scaled to 50     | 50      | 50       | ≈35                     | ≈15                      | ‹…›           | CO1-CO6 |
| **Total** |                                             | **100** | **100%** | **≈69**                 | **≈31**                  |               |         |

**IA-1 note:** Questions drawn from Units 1 & 2; conducted for 40 marks, scaled to 20. **IA-2 note:** Questions drawn from Units 3 & 4; conducted for 40 marks, scaled to 20. **Assignment 1:** Practical-based; group of 3-4; 10 marks scaled to 5. **Assignment 2:** Practical-based; group of 3-4; 10 marks scaled to 5. **SEE:** Student answers for 100 marks (two questions per unit; answer one per unit), scaled to 50.

### 14.1 🔵 The calibration that enforces the CGPA rule

| Check                                              | Entry                                                                                                                                                               |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Marks-to-CGPA conversion used                      | ‹REVA grading scale - to be confirmed with CoE: e.g., 75%+ = O (10 pts), 65-74% = A+ (9 pts), 55-64% = A (8 pts)…›                                                  |
| Max % achievable from awareness marks alone        | ≈69%                                                                                                                                                                |
| Grade band that % falls into                       | ‹Confirm: at REVA, 65-74% → A+ (9 pts) or 55-64% → A (8 pts)? If 69% → A+ (9 pts, CGPA ≥ 8), the split must be tightened to ≈60/40. **Verify before course runs.**› |
| Advanced marks needed to cross 8 CGPA              | ‹If 69% < 8-CGPA threshold: student needs ≈X of the 31 advanced marks - confirm from conversion table›                                                              |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | ‹**To be verified** - fill after confirming grading scale with CoE›                                                                                                 |

**Action required:** Confirm REVA's marks-to-grade-point conversion. If awareness-only (≈69%) maps to a grade band at or above the 8 CGPA cut, reduce awareness marks to ≈60 and raise advanced to ≈40, then re-run this check.

### 14.2 Question-paper blueprint 🔵

| Instrument       | Awareness questions (Bloom: R/U/Ap)                                                           | Advanced questions (Bloom: An/E/Cr)                                                        |
| ---------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| IA-1 (Units 1-2) | Part A (short answers: define, draw, apply standard mapping rules) + first question of Part B | Final high-mark question: novel ER design or schema evaluation with justification          |
| IA-2 (Units 3-4) | Part A (write standard SELECT, GROUP BY, normalization steps) + first Part B question         | Correlated subquery / stored-procedure design or BCNF proof for a novel relation           |
| SEE              | Standard-case questions for each unit (2 per unit, answer 1) - first option each unit         | Second option each unit: optimisation, redesign, or design-and-justify for a novel problem |

## 15\. 🔵 Result analysis - banded to detect the two levels

| Exam         | < 40% (below floor - remediate) | 40-75% (floor cleared, awareness-solid) | \> 75% (advanced attained) |
| ------------ | ------------------------------- | --------------------------------------- | -------------------------- |
| IA-1         |                                 |                                         |                            |
| IA-2         |                                 |                                         |                            |
| Assignment 1 |                                 |                                         |                            |
| Assignment 2 |                                 |                                         |                            |
| SEE          |                                 |                                         |                            |

The **\> 75%** count approximates students operating at the advanced level. Cross-check with how many students cross the 8-CGPA band at semester end (§17).

## 16\. Learner support tracking 🟢🔵

### 16.1 Students below the floor (per IA) - remediation

| Sl  | SRN | Name | IA  | Gap identified | Remedial class dates | Re-assessment result |
| --- | --- | ---- | --- | -------------- | -------------------- | -------------------- |
|     |     |      |     |                |                      |                      |

### 16.2 Students reaching for the ceiling - enrichment

| Sl  | SRN | Name | Advanced task assigned | Outcome |
| --- | --- | ---- | ---------------------- | ------- |
|     |     |      |                        |         |

|                             | No. of students | Action taken |
| --------------------------- | --------------- | ------------ |
| Below floor (slow learners) |                 |              |
| At ceiling (fast learners)  |                 |              |

## 17\. 🔵 Track-advice signal (links course → SIG track choice)

| Field                                             | Entry                                                                                                                                                                                                                                                                          |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Is this a prerequisite for a SIG track?           | ‹Yes - relevant to Data Engineering, AI/ML Data track, and any backend-development SIG. Confirm with SIG coordinator.›                                                                                                                                                         |
| % of students at advanced level (> 75% / 8+ CGPA) | ‹Fill after SEE results›                                                                                                                                                                                                                                                       |
| Domains where advanced performance clustered      | ‹Fill after results - e.g., strong in SQL optimisation (Unit 3 Adv) vs. normalization proofs (Unit 4 Adv)›                                                                                                                                                                     |
| Recommended note to academic mentors              | Students who score > 75% overall and demonstrate advanced attainment in Units 3-4 (complex SQL + normalization design) are strong candidates for the Data Engineering or AIML-Data Analytics SIG track. Share IA-2 advanced-question scores with mentors before SIG selection. |

## 18\. CO attainment 🟢🔵

**Set target:** 60%

| CO  | IA1 | IA2 | A1  | A2  | SEE | Direct attainment | Level (A/Adv) 🔵 |
| --- | --- | --- | --- | --- | --- | ----------------- | ---------------- |
| CO1 |     |     |     |     |     |                   | Awareness        |
| CO2 |     |     |     |     |     |                   | Both             |
| CO3 |     |     |     |     |     |                   | Both             |
| CO4 |     |     |     |     |     |                   | Advanced         |
| CO5 |     |     |     |     |     |                   | Advanced         |
| CO6 |     |     |     |     |     |                   | Advanced         |

🔵 Report attainment of Advanced COs (CO4-CO6) separately. If CO1-CO3 attain well but CO4-CO6 do not, the floor is healthy but the ceiling is failing - the primary diagnostic signal of this template.

## 19\. CO-PO/PSO mapping & overall attainment 🟢

**Strength: 1 = Low, 2 = Medium, 3 = High.**

| CO  | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PSO1 | PSO2 | PSO3 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---- | ---- | ---- | ---- | ---- |
| CO1 | 3   | 3   | 2   | 2   | 2   |     |     |     |     | 1    |      | 3    | 3    |      |
| CO2 | 3   | 3   | 2   | 3   | 1   |     |     |     |     |      |      | 3    | 3    |      |
| CO3 | 3   | 3   | 2   | 3   | 3   |     |     |     |     |      |      | 3    | 3    | 3    |
| CO4 | 3   | 3   | 2   | 3   | 1   |     |     |     |     |      |      | 3    | 3    |      |
| CO5 |     |     |     |     |     |     |     |     |     |      |      | 2    |      |      |
| CO6 |     |     |     |     | 2   |     |     |     | 3   | 2    |      | 3    | 3    |      |

**Overall attainment** (Direct 80% + Indirect/Feedback 20%):

|                | Internal | External | Grand total (80%+20%) |
| -------------- | -------- | -------- | --------------------- |
| CO attainment  |          |          |                       |
| PO attainment  |          |          |                       |
| PSO attainment |          |          |                       |

**Minimum level for PO attainment:** 50-60%

## 20\. Course completion summary 🟢

| Unit | Planned date | Completion date | Remarks |
| ---- | ------------ | --------------- | ------- |
| 1    |              |                 |         |
| 2    |              |                 |         |
| 3    |              |                 |         |
| 4    |              |                 |         |

## 21\. 🔵 Faculty reflection - dual-level health check

_(To be filled at course close.)_

- Did the awareness floor genuinely protect placement-readiness for the weakest students? ‹…›
- Was the advanced ceiling reached by roughly the expected share, or did it collapse / go unassessed? ‹…›
- One change to the awareness/advanced split or the lesson plan for the next offering: ‹…›

**Signatures**

Course Faculty (digital signature) - Dr. J. Ragaventhiran HoD / Director (digital signature) - ‹…›

## 22\. 🔵 Implementation strategy - Merrill's First Principles

The per-session plan is merged into §11. This section records the strategy and phase audit.

**Merrill's five phases (vocabulary for the §11 "Merrill phase" column):**

| Phase                      | What it means                                                                | Typical activity in this course                                            |
| -------------------------- | ---------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Problem / Task-centred** | Anchor learning in a real-world DB problem the student will be able to solve | Present motivating scenario (e.g., "Why does this schema have anomalies?") |
| **Activation**             | Activate relevant prior knowledge before new content                         | **Lecture followed by a demonstration**; recap quiz; prior-concept recall  |
| **Demonstration**          | Show, don't just tell - worked SQL or ER design examples                     | Live MySQL coding; step-by-step ER diagram build                           |
| **Application**            | Student practises with feedback                                              | Guided lab tasks, pair exercises, problem sets                             |
| **Integration**            | Student transfers skill to their own context                                 | Mini-project lab, case-study redesign, peer presentation                   |

**Design rule:** All five phases appear across each unit. Advanced-level activities (Application/Integration at Adv) are explicitly planned in §11 so the ceiling is taught, not only assessed.

### 22.1 Phase-coverage check 🔵

| Check                                                            | Entry                                                  |
| ---------------------------------------------------------------- | ------------------------------------------------------ |
| All five Merrill phases used at least once per unit              | Yes - confirmed in §11 session plan above              |
| §11 sessions using Activation = **lecture + demonstration**      | S.No 01, 05, 13, 17, 22, 33, 38, 48, 49, 52, 64, 65    |
| §11 sessions delivering **Advanced-level** activities            | S.No 08, 12, 21, 27, 31, 39, 43, 47, 55, 56, 59, 65    |
| ✅ Ceiling taught (≥ 1 Adv activity per unit, not only assessed) | Yes - Units 1-4 each have ≥ 2 Advanced-tagged sessions |

_End of Course File - B25CS0302 Database Management Systems (AIML Sem 3, Even 2026-27)_ _Generated from existing CBCS course file (Dr. J. Ragaventhiran) and upgraded to dual-level template._ _Placeholders remain in §14.1 (CGPA calibration) and §17 (post-results fields) - faculty action required._