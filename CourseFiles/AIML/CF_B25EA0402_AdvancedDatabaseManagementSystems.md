# Course File - Dual-Level (Awareness + Advanced) Design

## 0\. Course identification 🟢

| Field                       | Entry                                |
| --------------------------- | ------------------------------------ |
| Faculty name                | Dr. J. Ragaventhiran                 |
| REVA ID                     | REVA03025                            |
| Email                       | <j.ragaventhiran@reva.edu.in>        |
| Programme                   | B.Tech - AIML                        |
| Course code                 | B25EA0402 (0-0-2-2)                  |
| Course title                | Advanced Database Management Systems |
| Semester & section          | 4 & AIML                             |
| Academic year               | Even 2026-27                         |
| Course duration (sessions)  | 30 sessions                          |
| Office / consultation hours | 8:30 am to 4:30 pm                   |

**School vision:** To produce excellent quality technologists and researchers of global standards in computing and Information technology who have potential to contribute to the development of the nation and the society with their expertise, skills, innovative problem-solving abilities, strong moral and ethical values.

**School mission:** - To create state-of-the-art computing labs infrastructure and research facilities in information technology. - To provide student-centric learning environment in Computing and Information technology through innovative pedagogy and education reforms. - To encourage research, innovation and entrepreneurship in computing and information technology through industry/academia collaborations and extension activities. - Organize programs through club activities for knowledge enhancement in thrust areas of information technology. - To enhance leadership qualities among the youth and enrich personality traits, promote patriotism, moral and ethical values.

## 1\. Course description 🟢

This course provides practical exposure to advanced database concepts including transaction management, concurrency control, distributed databases, NoSQL systems, MongoDB, and collaborative database development using Git and GitHub. The course emphasizes hands-on learning through workshops, case studies, and mini-projects involving modern database technologies used in industry.

## 2\. Course content (units & weightage) 🟢

| Unit | Syllabus                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Weightage |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------- |
| 1    | **Transaction Processing and Concurrency Control:** Introduction to Transaction Processing, Transaction States, ACID Properties, Transaction Support in SQL, Schedules and Serializability, Lock-Based Concurrency Control, Two-Phase Locking (2PL), Deadlocks and Recovery, Timestamp-Based Concurrency Control, Optimistic Concurrency Control, Case Studies on Banking and E-Commerce Systems.<br><br>**Hands-on Activities:** Simulating concurrent transactions in MySQL; Implementing locks and transaction isolation levels; Deadlock detection and resolution exercises; Comparative analysis of concurrency control methods | 25 Marks  |
| 2    | **Distributed Databases and NoSQL Systems:** Introduction to Distributed Databases, Distributed Database Architectures, CAP Theorem, Data Replication and Partitioning, Emergence of NoSQL Systems, Characteristics of NoSQL Databases, Key-Value Stores, Document Databases, Column-Family Databases, Graph Databases, Comparison of SQL and NoSQL Systems, Use Cases and Industry Applications.<br><br>**Hands-on Activities:** Exploring distributed database architectures; Working with sample datasets in different NoSQL models; CAP theorem demonstrations; SQL vs NoSQL performance comparison                              | 25 Marks  |
| 3    | **MongoDB for Modern Applications:** MongoDB Architecture and Data Model, BSON Documents, Collections and Databases, CRUD Operations, Query Operators, Indexing, Aggregation Framework, Data Validation, MongoDB Replication, Sharding Concepts, Transactions in MongoDB, Introduction to MongoDB Atlas.<br><br>**Hands-on Activities:** Installation and configuration of MongoDB; CRUD operations using Mongo Shell and MongoDB Compass; Aggregation pipeline development; Index optimization exercises; Deploying a cloud database using MongoDB Atlas                                                                            | 25 Marks  |
| 4    | **Database DevOps using Git and GitHub:** Introduction to Version Control Systems, Git Fundamentals, GitHub Workflow, Database Schema Versioning, SQL Script Management, Collaborative Database Development, Branching and Merging Strategies, Managing Database Migration Scripts, CI/CD Concepts for Databases, Documentation and Project Management using GitHub.<br><br>**Hands-on Activities:** Git and GitHub setup; Repository creation and collaboration; Version controlling SQL scripts; Database migration tracking; Team-based database project using GitHub                                                             | 25 Marks  |

## 3\. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level - every student must reach (the floor)                                                                                                                                  | Advanced level - required to exceed 8 CGPA (the ceiling)                                                                                                                                                            |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Define ACID properties, transaction states, and schedules; apply 2PL and basic lock-based concurrency control to a standard banking/e-commerce transaction scenario in MySQL            | Analyze schedules for serializability/conflict serializability, compare 2PL, timestamp-based, and optimistic concurrency control for an unfamiliar workload, and detect/resolve deadlocks in a non-trivial scenario |
| 2    | Explain distributed database architectures, the CAP theorem, and replication/partitioning; identify and describe the four NoSQL data models (key-value, document, column-family, graph) | Evaluate which NoSQL model and partitioning/replication strategy best fits a novel real-world application, justifying trade-offs using the CAP theorem against an equivalent SQL design                             |
| 3    | Perform standard CRUD operations, basic queries, and indexing in MongoDB using Mongo Shell/Compass on a familiar dataset                                                                | Design and optimize an aggregation pipeline and index strategy for an unfamiliar/large dataset, and configure replication/sharding concepts and deploy a cloud database on MongoDB Atlas                            |
| 4    | Use Git fundamentals (init, commit, branch, push/pull) and the GitHub workflow to version-control a given SQL script                                                                    | Design a branching/merging strategy and migration-tracking workflow for a team-based database project, applying CI/CD concepts to manage schema changes across environments                                         |

**Bloom anchor (use to keep "awareness" vs "advanced" consistent across courses):**

| Level                  | Bloom verbs                 | Typical question stem                                                            |
| ---------------------- | --------------------------- | -------------------------------------------------------------------------------- |
| **Awareness (floor)**  | Remember, Understand, Apply | "Define…", "Explain…", "Apply X to this standard case…"                          |
| **Advanced (ceiling)** | Analyze, Evaluate, Create   | "Compare and justify…", "Optimize…", "Design a solution for this novel problem…" |

## 4\. Course objectives 🟢

The objectives of this course are to: - Understand transaction processing and concurrency control mechanisms in database systems. - Explore distributed database architectures and NoSQL database technologies. - Develop applications using MongoDB for handling semi-structured data. - Apply version control and collaborative development practices for database projects using Git and GitHub. - Design and implement scalable database solutions for modern applications.

## 5\. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome                                                                                                                      | Level (Awareness / Advanced / Both) 🔵 | POs                           | PSOs             |
| --- | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ----------------------------- | ---------------- |
| CO1 | Explain the concepts of transaction processing, ACID properties, schedules, and concurrency control mechanisms in database systems. | Awareness                              | PO1, PO2, PO3, PO4, PO5, PO10 | PSO1, PSO2       |
| CO2 | Apply transaction management and concurrency control techniques using SQL-based database systems.                                   | Both                                   | PO1, PO2, PO3, PO4, PO5       | PSO1, PSO2       |
| CO3 | Analyze distributed database architectures and evaluate the characteristics and applications of NoSQL databases.                    | Advanced                               | PO1, PO2, PO3, PO4, PO5       | PSO1, PSO2, PSO3 |
| CO4 | Design and implement document-oriented databases using MongoDB and perform CRUD operations, indexing, and aggregation.              | Both                                   | PO1, PO2, PO3, PO4, PO5       | PSO1, PSO2       |
| CO5 | Develop scalable database solutions utilizing MongoDB distributed features such as replication and sharding.                        | Advanced                               | -                             | PSO1             |
| CO6 | Employ Git and GitHub for collaborative database development, schema version control, documentation, and project management.        | Advanced                               | PO5, PO9, PO10                | PSO1, PSO2       |

🔵 **CO level rationale:** CO1 covers foundational definitions/explanations (floor only). CO2 and CO4 span both - students apply standard procedures (floor) and can extend them to optimization/aggregation design (ceiling). CO3, CO5, CO6 are advanced - analysis, scalable design, and collaborative workflow design represent the ceiling, ensuring the course has genuine advanced content beyond the floor.

## 6\. Pedagogy 🟢

- Direct method
- ICT and Digital support
- Collaborative and Cooperative learning
- Differentiated Instruction
- Flipped Classroom

## 7\. Textbooks, references, e-resources 🟢

**Textbook(s):** - Silberschatz, A., Korth, H. F., & Sudarshan, S. (2019). _Database System Concepts_ (7th ed.). McGraw-Hill Education, New York, NY.

**References:** - Elmasri, R., & Navathe, S. B. (2016). _Fundamentals of Database Systems_ (7th ed.). Pearson Education, Boston, MA. - Chodorow, K. (2019). _MongoDB: The Definitive Guide: Powerful and Scalable Data Storage_ (3rd ed.). O'Reilly Media, Sebastopol, CA. - Sadalage, P. J., & Fowler, M. (2012). _NoSQL Distilled: A Brief Guide to the Emerging World of Polyglot Persistence_. Addison-Wesley Professional, Boston, MA. - Chacon, S., & Straub, B. (2014). _Pro Git_ (2nd ed.). Apress, New York, NY.

**Web / e-books / NPTEL:** ‹…›

## 8\. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) - for students at risk of not clearing it:** - Detailed notes given to make slow learners understand subject concepts clearly. - Remedial sessions/notes/assignments triggered by IA performance, focused on standard transaction, NoSQL, MongoDB CRUD, and Git workflow procedures. - ‹curated e-learning material, worked examples, peer mentoring›

**Reaching the ceiling (advanced level) - for students aiming above 8 CGPA:** - A separate group assignment (3-4 members) for fast learners covering optimization/design problems across units. - ‹journal/paper review with written report on a distributed database or NoSQL topic› - ‹design algorithms/pipelines for real-world or novel problems; advanced-topic reading beyond the prescribed text; optional stretch problems›

## 9\. Assignments 🟢

| Assignment   | Units covered                  | Marks | Window                                                                                                 |
| ------------ | ------------------------------ | ----- | ------------------------------------------------------------------------------------------------------ |
| Assignment 1 | Unit 1 & first half of Unit 2  | 5     | Before IA-2 _(practical-based, group of 3-4 students; carries 10 marks per original scheme - confirm)_ |
| Assignment 2 | Second half of Unit 2 & Unit 3 | 5     | Before SEE _(practical-based, group of 3-4 students; carries 10 marks per original scheme - confirm)_  |

## 10\. Prerequisites / pre-reading 🟢

Knowledge of any programming language.

🔵 **Note:** prerequisite-course performance is the input academic mentors use to advise track choice (see §17). Record the prerequisite explicitly so the mentoring link is traceable.

## 11\. Lesson plan - tentative transaction dates + session implementation 🟢🔵

| S.No  | Planned date | Exec. date | Unit / topic                                                                         | Merrill phase 🔵             | Activity (what the faculty runs) 🔵                                                                                                                         | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
| ----- | ------------ | ---------- | ------------------------------------------------------------------------------------ | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ---------------- | ----- | ------- |
| 01    | ‹…›          |            | Unit 1 - Introduction to Transaction Processing, Transaction States, ACID Properties | Problem-centred + Activation | Present a banking/e-commerce transaction-failure scenario; **lecture followed by a demonstration** of transaction states and ACID properties                |          | A                | CO1   |         |
| 02    | ‹…›          |            | Unit 1 - Transaction Support in SQL, Schedules and Serializability                   | Demonstration                | Worked example: writing transactions in SQL; walkthrough of serial vs. concurrent schedules                                                                 |          | A                | CO1   |         |
| 03    | ‹…›          |            | Unit 1 - Lock-Based Concurrency Control, Two-Phase Locking (2PL)                     | Demonstration                | Live demonstration of locking and 2PL on a sample schedule                                                                                                  |          | A                | CO1   |         |
| 04    | ‹…›          |            | Unit 1 - Concurrency control hands-on                                                | Application                  | Lab: Simulating concurrent transactions and isolation levels in MySQL (familiar problem)                                                                    | 25%      | A                | CO2   |         |
| 05    | ‹…›          |            | Unit 1 - Deadlocks and Recovery, Timestamp-Based & Optimistic Concurrency Control    | Application + Integration    | Stretch lab: deadlock detection/resolution exercise and comparative analysis of concurrency control methods on an unfamiliar workload (ceiling)             |          | Adv              | CO2   |         |
| 06    | ‹…›          |            | Unit 1 - Case studies (Banking, E-Commerce)                                          | Integration                  | Case-study discussion: apply concurrency control concepts to real-world banking/e-commerce systems                                                          |          | Adv              | CO2   |         |
| 07    | ‹…›          |            | Unit 2 - Introduction to Distributed Databases, Architectures, CAP Theorem           | Activation                   | Recap quiz on Unit 1; **lecture followed by a demonstration** introducing distributed architectures and CAP theorem                                         |          | A                | CO3   |         |
| 08    | ‹…›          |            | Unit 2 - Data Replication and Partitioning                                           | Demonstration                | Worked example/demo of replication and partitioning strategies                                                                                              |          | A                | CO3   |         |
| 09    | ‹…›          |            | Unit 2 - Emergence of NoSQL, Key-Value & Document Databases                          | Demonstration                | Demonstration of key-value and document database models with sample datasets                                                                                |          | A                | CO3   |         |
| 10    | ‹…›          |            | Unit 2 - Column-Family & Graph Databases                                             | Application                  | Guided exercise: working with sample datasets in different NoSQL models                                                                                     |          | A                | CO3   |         |
| 11    | ‹…›          |            | Unit 2 - Comparison of SQL and NoSQL Systems                                         | Application                  | CAP theorem demonstration and SQL vs NoSQL performance comparison lab                                                                                       |          | A                | CO3   |         |
| 12    | ‹…›          |            | Unit 2 - Use cases and industry applications                                         | Integration                  | Stretch task: evaluate and justify NoSQL model choice for a novel real-world application (ceiling)                                                          | 50%      | Adv              | CO3   |         |
| 13    | ‹…›          |            | Unit 3 - MongoDB Architecture and Data Model, BSON Documents                         | Activation                   | Recap quiz on Unit 2; **lecture followed by a demonstration** of MongoDB architecture and BSON document model                                               |          | A                | CO4   |         |
| 14    | ‹…›          |            | Unit 3 - Installation and Configuration of MongoDB                                   | Demonstration                | Live installation/configuration walkthrough of MongoDB                                                                                                      |          | A                | CO4   |         |
| 15    | ‹…›          |            | Unit 3 - CRUD Operations, Query Operators                                            | Demonstration                | Worked example of CRUD operations and query operators using Mongo Shell and Compass                                                                         |          | A                | CO4   |         |
| 16    | ‹…›          |            | Unit 3 - CRUD hands-on                                                               | Application                  | Lab: CRUD operations on a familiar dataset using Mongo Shell and Compass                                                                                    |          | A                | CO4   |         |
| 17    | ‹…›          |            | Unit 3 - Indexing                                                                    | Application                  | Guided lab: index creation on a familiar dataset                                                                                                            |          | A                | CO4   |         |
| 18    | ‹…›          |            | Unit 3 - Aggregation Framework, Data Validation                                      | Application + Integration    | Stretch lab: aggregation pipeline development and index optimization on an unfamiliar/large dataset (ceiling)                                               |          | Adv              | CO5   |         |
| 19    | ‹…›          |            | Unit 3 - MongoDB Replication, Sharding Concepts, Transactions in MongoDB             | Demonstration                | Lecture/demo of replication, sharding, and transactions in MongoDB                                                                                          |          | A                | CO5   |         |
| 20    | ‹…›          |            | Unit 3 - Introduction to MongoDB Atlas                                               | Integration                  | Mini-task: deploying a cloud database using MongoDB Atlas (transfer to own context)                                                                         | 75%      | Adv              | CO5   |         |
| 21    | ‹…›          |            | Unit 4 - Introduction to Version Control Systems, Git Fundamentals                   | Activation                   | Recap quiz on Unit 3; **lecture followed by a demonstration** of Git fundamentals (init, commit, branch)                                                    |          | A                | CO6   |         |
| 22    | ‹…›          |            | Unit 4 - GitHub Workflow                                                             | Demonstration                | Live demo of GitHub workflow: repository creation, push/pull, collaboration                                                                                 |          | A                | CO6   |         |
| 23    | ‹…›          |            | Unit 4 - Database Schema Versioning, SQL Script Management                           | Demonstration                | Worked example: version-controlling SQL scripts                                                                                                             |          | A                | CO6   |         |
| 24    | ‹…›          |            | Unit 4 - Git/GitHub setup and repository collaboration                               | Application                  | Lab: Git and GitHub setup, repository creation and collaboration on a given SQL script (familiar task)                                                      |          | A                | CO6   |         |
| 25    | ‹…›          |            | Unit 4 - Branching and Merging Strategies                                            | Application                  | Guided exercise on branching/merging strategies                                                                                                             |          | A                | CO6   |         |
| 26    | ‹…›          |            | Unit 4 - Managing Database Migration Scripts, CI/CD Concepts                         | Application + Integration    | Stretch task: design a migration-tracking workflow and outline CI/CD concepts for an unfamiliar database project (ceiling)                                  |          | Adv              | CO6   |         |
| 27    | ‹…›          |            | Unit 4 - Documentation and Project Management using GitHub                           | Demonstration                | Demonstration of documentation practices and project management using GitHub                                                                                |          | A                | CO6   |         |
| 28-30 | ‹…›          |            | Unit 4 - Capstone                                                                    | Integration                  | Team-based database project using GitHub: mini-project transferring version-control, schema-management, and CI/CD skills to the team's own database project | 100%     | Adv              | CO6   |         |

🔵 The **Level** column shows where in the calendar the advanced-level content is actually taught - not just assessed. The **Merrill phase** + **Activity** columns carry the implementation plan; the phase-coverage audit lives in §22.1.

## 12\. ICT & digital support 🟢

Links to YouTube videos and PPTs are used as below:

- **Unit-1: Transaction Processing and Concurrency Control** - ‹link›
- **Unit-2: Distributed Databases and NoSQL Systems** - ‹link›
- **Unit-3: MongoDB for Modern Applications** - ‹link›
- **Unit-4: Database DevOps using Git and GitHub** - ‹link›

## 13\. Academic integrity policy 🟢

Students are expected to follow the Rules of Conduct and Academic Behavior standards as detailed in the Student Regulation handbook. Failure to comply with these rules may result in disciplinary actions as stipulated in the Students Regulations.

**Note:** Copying and plagiarism in any form for any of the evaluation components will result in zero marks.

## 14\. 🔵 Evaluation scheme - dual-level (CORE OF THE TEMPLATE)

| Sl        | Component     | Marks   | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs                |
| --------- | ------------- | ------- | -------- | ----------------------- | ------------------------ | ---- | ------------------ |
| 1         | Test 1 (IA-1) | 20      | 20       | ‹≈14›                   | ‹≈6›                     | ‹…›  | CO1, CO2           |
|           | Test 2 (IA-2) | 20      | 20       | ‹≈14›                   | ‹≈6›                     | ‹…›  | CO3, CO4, CO5, CO6 |
|           | Assignment 1  | 5       | 5        | ‹3›                     | ‹2›                      | ‹…›  | CO1, CO2, CO3      |
|           | Assignment 2  | 5       | 5        | ‹3›                     | ‹2›                      | ‹…›  | CO4, CO5, CO6      |
| 2         | SEE           | 50      | 50       | ‹≈35›                   | ‹≈15›                    | ‹…›  | CO1-CO6            |
| **Total** |               | **100** | **100%** | **≈70**                 | **≈30**                  |      |                    |

**Original IA structure (carried over from source document - reconcile with table above):** - IA1 - Questions from Unit-1 and Unit-2. Test conducted for 40 marks. - IA2 - Questions from Unit-3 and Unit-4 (complete). Test conducted for 40 marks. - Assignment 1 - Practical-based assignment to groups of 3-4 students; questions from Unit-1 and first half of Unit-2; carries 10 marks. - Assignment 2 - Practical-based assignment to groups of 3-4 students; questions from second half of Unit-2 and Unit-3 (complete); carries 10 marks. - Semester End Exam - 100 marks scaled down to 50; questions drawn from all 4 units, two per unit, student answers one per unit.

### 14.1 🔵 The calibration that enforces the CGPA rule

| Check                                              | Entry                                                                                                                                                    |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Marks-to-CGPA conversion used                      | ‹…›                                                                                                                                                      |
| Max % achievable from awareness marks alone        | ≈70%                                                                                                                                                     |
| Grade band that % falls into                       | < 8 CGPA band - confirm                                                                                                                                  |
| Advanced marks needed to cross 8 CGPA              | ‹Approx. ≥15 of the 30 advanced marks (≈50% of advanced component), based on the ≈70/30 split above - confirm against REVA's marks-to-grade-point table› |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | ‹Yes / No›                                                                                                                                               |

If the last row is **No**, the split is mis-calibrated - rebalance the awareness/advanced marks before the course runs.

### 14.2 Question-paper blueprint 🔵

| Instrument  | Awareness questions (Bloom: R/U/Ap)                                                                | Advanced questions (Bloom: An/E/C)                                                                                                                |
| ----------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| IA-1 / IA-2 | ‹e.g. Part A + first half of Part B - definitions, standard procedures (ACID, CRUD, Git commands)› | ‹e.g. final high-mark question - schedule analysis, NoSQL model justification, aggregation pipeline design›                                       |
| SEE         | ‹standard-case questions across all units›                                                         | ‹at least one advanced item per unit - e.g. deadlock analysis, distributed design trade-off, sharding/replication design, CI/CD migration design› |

## 15\. 🔵 Result analysis - banded to detect the two levels

| Exam         | < 40% (below floor - remediate) | 40-75% (floor cleared, awareness-solid) | \> 75% (advanced attained) |
| ------------ | ------------------------------- | --------------------------------------- | -------------------------- |
| IA-1         |                                 |                                         |                            |
| IA-2         |                                 |                                         |                            |
| Assignment 1 |                                 |                                         |                            |
| Assignment 2 |                                 |                                         |                            |
| SEE          |                                 |                                         |                            |

The **\> 75%** column is, in practice, the count of students operating at advanced level - cross-check it against how many cross the 8-CGPA band.

## 16\. Learner support tracking 🟢🔵

### 16.1 Students below the floor (per IA) - remediation

| Sl  | SRN | Name | IA  | Gap identified | Remedial class dates | Re-assessment result |
| --- | --- | ---- | --- | -------------- | -------------------- | -------------------- |

### 16.2 Students reaching for the ceiling - enrichment

| Sl  | SRN | Name | Advanced task assigned | Outcome |
| --- | --- | ---- | ---------------------- | ------- |

|                             | No. of students | Action taken |
| --------------------------- | --------------- | ------------ |
| Below floor (slow learners) |                 |              |
| At ceiling (fast learners)  |                 |              |

## 17\. 🔵 Track-advice signal (links course → SIG track choice)

| Field                                             | Entry                                                  |
| ------------------------------------------------- | ------------------------------------------------------ |
| Is this a prerequisite for a SIG track?           | ‹Yes/No - which track(s), e.g. AI/ML-Data Engineering› |
| % of students at advanced level (> 75% / 8+ CGPA) | ‹…›                                                    |
| Domains where advanced performance clustered      | ‹…›                                                    |
| Recommended note to academic mentors              | ‹…›                                                    |

## 18\. CO attainment 🟢

**Set target:** ‹60›

| CO  | IA1 | IA2 | A1  | A2  | SEE | Direct attainment | Level (A/Adv) 🔵 |
| --- | --- | --- | --- | --- | --- | ----------------- | ---------------- |
| CO1 |     |     |     |     |     |                   | A                |
| CO2 |     |     |     |     |     |                   | Both             |
| CO3 |     |     |     |     |     |                   | Adv              |
| CO4 |     |     |     |     |     |                   | Both             |
| CO5 |     |     |     |     |     |                   | Adv              |
| CO6 |     |     |     |     |     |                   | Adv              |

🔵 Report attainment of **advanced-level COs separately**. If awareness COs attain well but advanced COs don't, the floor is healthy but the ceiling is failing.

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

**Minimum level for PO attainment:** ‹50%-60%›

## 20\. Course completion summary 🟢

| Unit | Planned date | Completion date | Remarks |
| ---- | ------------ | --------------- | ------- |
| 1    |              |                 |         |
| 2    |              |                 |         |
| 3    |              |                 |         |
| 4    |              |                 |         |

## 21\. 🔵 Faculty reflection - dual-level health check

- Did the awareness floor genuinely protect placement-readiness for the weakest students? ‹…›
- Was the advanced ceiling reached by roughly the expected share, or did it collapse / go unassessed? ‹…›
- One change to the awareness/advanced split for next offering: ‹…›

**Signatures**

Course Faculty (digital signature) - ‹…› HoD / Director (digital signature) - ‹…›

## 22\. 🔵 Implementation strategy - Merrill's First Principles

The per-session implementation plan is merged into the lesson-plan table (§11). Merrill's five phases - Problem/Task-centred, Activation, Demonstration, Application, Integration - are listed there per session.

### 22.1 Phase-coverage check 🔵

| Check                                                           | Entry                                                                                                                        |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| All five Merrill phases used at least once per unit             | Yes (each unit's session block in §11 cycles through Problem-centred/Activation → Demonstration → Application → Integration) |
| §11 sessions using Activation = **lecture + demonstration**     | 01, 07, 13, 21                                                                                                               |
| §11 sessions delivering **Advanced-level** activities           | 05, 06, 12, 18, 20, 26, 28-30                                                                                                |
| ✅ Ceiling taught (≥1 Adv activity per unit, not only assessed) | Yes                                                                                                                          |