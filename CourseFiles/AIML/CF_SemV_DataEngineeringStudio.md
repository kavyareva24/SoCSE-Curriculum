# Course File — Dual-Level (Awareness + Advanced) Design

### Data Engineering Studio | AI/ML & Data Engineering SIG | Semester V | AY 2026–27

Generated from the REVA Course File Template — Dual-Level. Sections marked with placeholders (‹…›) are complete.

## 0. Course identification 🟢

| Field | Entry |
| --- | --- |
| Faculty name | ‹…› |
| REVA ID | ‹…› |
| Email | ‹…› |
| Programme | B.Tech — AIML / CSE / IT (AI/ML & Data Engineering SIG) |
| Course code | ‹No official code assigned yet› |
| Course title | Data Engineering Studio |
| Semester & section | V — A |
| Academic year | 2026–27 |
| Course duration (sessions) | 12 studio sessions · 24 lab hours |
| Office / consultation hours | Weekly sprint clinic hours; SIG Slack office hours |
| Dual-Level Designation | A+Adv (Awareness + Advanced) |
| Category | W4 / Workshop (HC / 0-0-2) |

**L-T-P-C:** 0-0-2 → 2 contact hours/week · **2 Credits**  
**Assessment:** CIE 50% · SEE 50%

**School vision:** To develop graduates who can bridge data, AI, and enterprise needs by designing robust data platforms, operationalising analytics, and delivering trustworthy data solutions that support sustainable, inclusive technology outcomes.

---

## 1. Course description 🟢

Data Engineering Studio is a hands-on workshop where student teams design, build, and deploy a working data pipeline and analytics solution using modern data tooling. The course emphasizes real-world data ingestion, transformation, storage, observability, and operational analytics. Students learn the discipline of making data usable for downstream AI and BI consumers while balancing scale, quality, cost, and governance.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
| --- | --- | --- |
| 1 | Data acquisition and storage — data sources, ingestion patterns, batch vs streaming, metadata, raw landing zones, schema-on-read, cloud file systems, data lake concepts, DuckDB/Parquet/Delta Lake. | 25 Marks |
| 2 | Pipeline design and orchestration — ETL/ELT, data transformation, orchestration tools (Apache Airflow / Prefect / Dagster), incremental loads, checkpoints, retries, idempotence. | 25 Marks |
| 3 | Data modelling and quality — dimensional modelling, star schemas, data vault basics, data contracts, validation rules, data quality checks, observability, anomaly detection. | 25 Marks |
| 4 | Operational analytics and governance — BI dashboards, SQL-based analytics, access control, lineage, cost optimisation, data privacy, documentation, handoff to consumers. | 25 Marks |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (the floor) | Advanced level — required to exceed 8 CGPA (the ceiling) |
| --- | --- | --- |
| 1 | Ingest data from at least one batch source and one API or file source into a raw landing zone; document schema assumptions; load data into a queryable storage format. | Design and justify a hybrid storage architecture for batch + streaming sources; optimise ingestion for throughput and cost; implement schema evolution handling and metadata capture. |
| 2 | Build a working ETL/ELT pipeline that transforms raw data into cleaned, analytics-ready tables; schedule and monitor pipeline runs; handle retries and simple failures. | Create an idempotent, parameterized pipeline with orchestration; explain choice of tooling and trade-offs; implement checkpointing, partition pruning, and lineage tracking. |
| 3 | Model data for analytics using a star schema or dimensional approach; implement data quality checks; profile and validate key metrics; document data contracts. | Evaluate and optimise the model for query performance; design a data contract that supports evolving downstream requirements; add anomaly detection and automated quality alerts. |
| 4 | Build a working dashboard / analytics query set; demonstrate how consumers access the data; apply basic access controls and documentation. | Deliver a polished analytics story with dashboard/cube-level insights; propose governance and cost-control controls for a production dataset; argue why the solution is reliable, maintainable, and ethically sound. |

---

## 4. Course objectives 🟢

- Deliver a production-style data ingestion and transformation workflow using modern tooling.
- Apply data modelling principles to make raw data analytics-ready for business and AI consumers.
- Operate data pipelines with resilience, observability, and quality checks.
- Communicate data architecture decisions, trade-offs, and governance considerations clearly.
- Reflect on how data engineering supports downstream AI, analytics, and product goals.

---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Level (Remember / Understand / Apply / Analyse / Evaluate / Create) 🔵 | POs | PSOs |
| --- | --- | --- | --- | --- |
| CO1 | Explain modern data engineering patterns, storage formats, and ingestion workflows. | Understand / Apply | PO2 | PSO1.2 |
| CO2 | Build and automate a data pipeline that ingests, transforms, and delivers analytics-ready data. | Apply | PO3 | PSO1.3 |
| CO3 | Model data for analytics and validate data quality through checks and documentation. | Analyse / Evaluate | PO4 | PSO4.1 |
| CO4 | Design and implement pipeline observability, lineage, and error recovery mechanisms. | Evaluate | PO5 | PSO5.1 |
| CO5 | Communicate data solution architecture, trade-offs, and governance to stakeholders. | Create | PO6 | PSO6.1 |
| CO6 | Reflect on the data engineering workflow and propose improvements for scale, reliability, and ethical compliance. | Evaluate / Create | PO7 | PSO7.1 |

> 🔵 **New column — CO level.** CO1–CO3 cover the awareness floor clearly; CO4–CO6 carry the advanced ceiling and ensure the course has a genuine upper tier.

---

## 6. Pedagogy 🟢

- **Project-based studio** — student teams work on a single data product across the workshop, with repeated build-review-refine cycles.
- **Just-in-time tooling** — teams use current data engineering stacks such as Apache Airflow, dbt, DuckDB, Apache Spark, or cloud alternatives, refreshed each cycle.
- **Live data problems** — faculty present real-world dataset scenarios and evolving stakeholder requests to simulate production conditions.
- **Mentored pair programming** — faculty and advanced peers support less experienced students during pipeline implementation.
- **Demonstration and critique** — weekly demos and sprint reviews surface both technical correctness and business relevance.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
- *Fundamentals of Data Engineering* — Joe Reis and Matt Housley
- *Designing Data-Intensive Applications* — Martin Kleppmann

**References:**
- *Data Engineering with Python* — Paul Crickard
- *Building the Data Lakehouse* — Bill Inmon, Mary Levins
- dbt Labs documentation, Airflow documentation, DuckDB guides, Snowflake/Databricks architecture notes.

**Web / e-books / NPTEL:**
- dbt Learn courses and developer docs
- AWS Glue/Google Cloud Dataflow introductory labs (if cloud access available)
- YouTube videos on data modelling and pipeline observability
- Industry blog posts on data mesh, data contracts, and analytics engineering.

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk of not clearing it:**
- Guided starter kits with scaffolded pipelines and template data models.
- Weekly mentorship labs focused on one core concept: ingestion, transformation, quality, and analytics.
- Pair programming with a stronger peer or faculty buddy for the first two sprints.
- Checklists for production readiness, documentation, and "definition of done."  
- Recorded walkthroughs of the sample pipeline, from raw data to dashboard.

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**
- Optional optimization tasks: partitioning, incremental transformation, query performance tuning.
- Leadership roles in architecture review, data contract design, and governance policy definition.
- Design a reusable data engineering pattern for future datasets beyond the course brief.
- Prepare a technical handoff packet for downstream analysts/AI teams, including lineage and cost impact.

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window | Level (Awareness / Advanced) |
| --- | --- | --- | --- | --- |
| Assignment 1: Ingestion proof-of-concept + schema notes | 1 | 5 | Sprint 2 | Awareness |
| Assignment 2: Pipeline automation and monitoring report | 2 | 5 | Sprint 4 | Awareness |
| Assignment 3: Data model + quality test suite | 3 | 5 | Sprint 6 | Awareness |
| Assignment 4: Analytics dashboard + consumer access plan | 4 | 5 | Sprint 8 | Awareness + Advanced |
| Assignment 5: Governance & cost optimisation proposal | 4 | 5 | Sprint 10 | Advanced |
| Assignment 6: Reflective improvement plan + stakeholder narrative | 1–4 | 10 | Sprint 12 | Advanced |

---

## 10. Prerequisites / pre-reading 🟢

Prerequisite course(s):
- Data Base Management Systems (B25CS0302) or equivalent DBMS foundation.
- Python for Data Science (B25CS0101) or equivalent scripting skills.
- Advanced Database Management Systems is helpful for advanced students but not mandatory.

> 🔵 **Note:** Prerequisite performance is the academic mentors' input signal for the AI/ML & Data Engineering SIG. Students with DBMS grades below the awareness floor are recommended for a focused bridging module in week 0.

---

## 11. Lesson plan — tentative transaction dates + session implementation 🟢🔵

| S.No | Planned date | Exec. date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 01 | Week 1 | | Unit 1 — Data ingestion fundamentals | Problem-centred + Activation | Present the product problem and dataset; live walkthrough of a simple ingestion pipeline; define raw vs curated zones | 10% | A | CO1 | Start team backlog, assign roles |
| 02 | Week 2 | | Unit 1 — Storage and metadata | Demonstration | Faculty demos Parquet/Delta Lake ingestion; teams build their landing zone and capture schema metadata | 20% | A | CO1 | Peer review of schema assumptions |
| 03 | Week 3 | | Unit 2 — Pipeline orchestration | Application | Guided lab on Airflow / Prefect; teams author a DAG/pipeline and run first job | 30% | A | CO2 | Faculty checks idempotence pattern |
| 04 | Week 4 | | Unit 2 — Incremental loads and retries | Application + Integration | Teams extend pipeline to incremental load; implement retry handling and logging; mid-sprint demo | 40% | A | CO2 CO4 | Advanced students review retry design |
| 05 | Week 5 | | Unit 3 — Analytics modelling | Activation | Faculty explains star schema / dimensional modelling; teams propose a model for their dataset | 50% | A | CO3 | Model critique session with faculty |
| 06 | Week 6 | | Unit 3 — Data quality and contracts | Demonstration | Live walkthrough of data tests and contracts; teams implement checks and document expectations | 60% | A | CO3 | Advanced: design an automated anomaly alert |
| 07 | Week 7 | | Unit 4 — BI and consumer handoff | Application | Teams build dashboards and query sets; faculty demonstrates dashboard storytelling | 70% | A/Adv | CO4 CO5 | Advanced: incorporate business metrics |
| 08 | Week 8 | | Unit 4 — Governance and access | Application + Integration | Teams define access controls, lineage, and documentation; review governance checklist | 80% | Adv | CO4 CO5 | Peer review of governance docs |
| 09 | Week 9 | | Unit 2–4 — Production readiness | Integration | Sprint review and stakeholder feedback session; teams refine pipeline based on review | 85% | Adv | CO2 CO4 | Advanced: cost/scale trade-off memo |
| 10 | Week 10 | | Unit 4 — Analytics storytelling | Reflection | Teams present dashboard narrative to faculty; faculty coaches demo pacing and context | 90% | Adv | CO5 CO6 | Prepare for final demo and viva |
| 11 | Week 11 | | Capstone — Live data product demo | Integration | Showcase working pipeline and analytics; capture user feedback; conduct peer evaluation | 95% | Adv | CO5 CO6 | Final review of documentation |
| 12 | Week 12 | | Capstone — Retrospective & improvement plan | Reflection | Teams present retrospective, improvements, and next steps; submit reflective artifact | 100% | Adv | CO6 | Final corrective action notes |

> 🔵 The Level column makes it explicit where advanced-level learning is taught. This workshop intentionally moves into advanced practice in Weeks 7–12, so the ceiling is visible in the calendar.

---

## 12. ICT & digital support 🟢

- **Apache Airflow / Prefect / Dagster** — pipeline orchestration and workflow monitoring.
- **dbt / SQL** — transformation and analytics modelling.
- **DuckDB / Delta Lake / Parquet** — storage formats and query tools.
- **GitHub** — version control, CI, deployment automation.
- **Metabase / Superset / Power BI** — dashboards and analytics storytelling.
- **Slack / Teams** — async communication and mentor office hours.
- **Notion / Jira** — sprint planning, decision logs, issue tracking.
- **YouTube / vendor docs** — short videos on data contracts, data mesh, and data observability.

---

## 13. Academic integrity policy 🟢

Plagiarism or uncredited copying of pipeline configurations, dashboards, or reports is prohibited and results in a zero for that assignment. AI-generated code or SQL is permitted only if the student documents the prompt used and validates the output manually. Peer review must remain honest and specific: feedback should focus on the work and proposed improvements, not on individuals.

---

## 14. 🔵 Evaluation scheme — dual-level (CORE OF THE TEMPLATE)

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Submitted / Due | COs |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Team ingestion & storage deliverable | 15 | 15 | 12 | 3 | Sprint 2 | CO1 |
| 2 | Pipeline automation + monitoring | 15 | 15 | 10 | 5 | Sprint 4 | CO2, CO4 |
| 3 | Data model + quality test suite | 15 | 15 | 10 | 5 | Sprint 6 | CO3 |
| 4 | Analytics demo + dashboard story | 15 | 15 | 9 | 6 | Sprint 11 | CO4, CO5 |
| 5 | Governance & optimisation report | 10 | 10 | 4 | 6 | Sprint 10 | CO4, CO6 |
| 6 | Reflective improvement plan | 10 | 10 | 3 | 7 | Sprint 12 | CO6 |
| 7 | Peer evaluation | 10 | 10 | 6 | 4 | Sprint 12 | CO4, CO5 |
| **Total CIE** | 80 | 80% | **54** | **26** | | |
| 8 | SEE: Live demo + viva voce | 20 | 20% | 16 | 4 | End of semester | CO1–CO6 |
| **Total** | 100 | 100% | **70** | **30** | | |

### 14.1 🔵 The calibration that enforces the CGPA rule

| Check | Entry |
| --- | --- |
| Marks-to-CGPA conversion used | REVA 10-point scale (80+ = 8 CGPA; 70–79 = 7 CGPA) |
| Max % achievable from awareness marks alone | 70% |
| Grade band that % falls into | 7 CGPA band — below 8 CGPA |
| Advanced marks needed to cross 8 CGPA | ≈10 marks from the advanced pool (40% of advanced) |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | Yes |

> The awareness floor is deliberately set at 70 marks. Students must earn advanced marks in the final demo/viva and reflective assessment to cross the 8-CGPA threshold.

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
| --- | --- | --- |
| CIE deliverables | "Show a working ingestion pipeline"; "Provide a schema and quality checklist" | "Explain why this architecture scales"; "Justify governance choices and optimisation trade-offs" |
| Peer evaluation | "Did the team member complete assigned tasks?" | "Did the team member unblocked others, propose improvements, or mentor peers?" |
| SEE demo + viva | "Run the pipeline and dashboard; explain how it works" | "If data volume doubled, what changes would you make?"; "How would you detect and recover from silent data corruption?" |

---

## 15. 🔵 Result analysis — banded to detect the two levels

| Grade band | Mark range | CGPA equiv. | Interpretation |
| --- | --- | --- | --- |
| O (Outstanding) | 90–100 | 10 | Advanced ceiling fully demonstrated; product-quality data platform delivered |
| A+ (Advanced) | 80–89 | 8–9 | Advanced ceiling reached; strong data engineering judgement |
| A (Proficient) | 70–79 | 7–8 | Awareness floor cleared; reliable contributor |
| B+ (Competent) | 60–69 | 6–7 | Approaching floor; needs guided practice in next course |
| B (Developing) | 50–59 | 5–6 | Below floor; needs remediation |
| C (Incomplete) | 40–49 | 4–5 | Did not complete workable deliverable |
| F (Fail) | <40 | <4 | Did not meet minimum course requirements |

---

## 16. Curriculum mapping — CO to PO/PSO/CSCore

| CO | Bloom level | PO mapped | PSO mapped | CSCore competency | Remark |
| --- | --- | --- | --- | --- | --- |
| CO1 | Understand / Apply | PO2 | PSO1.2 | Data systems fundamentals | |
| CO2 | Apply | PO3 | PSO1.3 | Engineering practice | |
| CO3 | Analyse / Evaluate | PO4 | PSO4.1 | Investigation & validation | |
| CO4 | Evaluate | PO5 | PSO5.1 | Team and process | |
| CO5 | Create | PO6 | PSO6.1 | Communication | |
| CO6 | Evaluate / Create | PO7 | PSO7.1 | Lifelong learning | |

---

## 17. 🔵 Track-advice signal — prerequisites & post-course feedback

**Input signal to academic mentors:**
- DBMS performance and Python scripting scores from prerequisite courses help place students into the AI/ML & Data Engineering SIG or suggest a floor-track support plan.
- Students with low scores in Data Base Management Systems are recommended for a week-0 bootcamp before the studio begins.

**Output signal from this course:**
- Studio grade band and peer-evaluation profile feed into internship track recommendations for sem 6–7.
- Students who exceed the advanced ceiling are strong candidates for AI/ML/Data Engineering internships or advanced analytics roles.

---

## 18. Industry partnership & just-in-time calibration

**Recruiter alignment:**
- The SIG updates briefs each cycle using current data engineering job descriptions from target recruiters.
- The workshop uses live datasets or realistic simulated enterprise datasets drawn from logistics, retail, healthcare, or fintech domains.
- Industry mentors review final demos and can nominate teams for internship interviews.

**Currency mechanism:**
- Tooling is refreshed each cycle: this year the workshop may use DuckDB + dbt + Airflow; next year it could use Databricks SQL + Delta Live Tables depending on recruiter demand.
- The course brief is re-authorised annually by the SIG to keep the studio aligned with current data platform trends.

---

## 19. Remediation & enrichment pathways

**For students at risk of not reaching the floor:**
- Structured guided labs in Weeks 1–3 with template code and explicit checklists.
- Peer pairing with an advanced team member for pipeline construction.
- Weekly remediation clinic on data modelling and quality.
- "Contributor role" assignment focused on implementing and testing a defined pipeline component.

**For students aiming to exceed the ceiling:**
- Optional architecture leadership role in Weeks 4–8.
- Extended optimisation tasks: query tuning, incremental load performance, governance automation.
- A mini-design review memo explaining the cost/scale/quality trade-offs of the chosen solution.
- Recommended mentorship for internship or capstone placement in a data platform team.

---

## 20. Support resources & mentorship model

- **Studio lead:** responsible for brief selection, sprint cadence, and final review.
- **Data engineering mentor:** provides code review, architecture critique, and pipeline reliability coaching.
- **Peer mentors:** advanced students who help with dbt modelling, Airflow DAGs, and dashboard storytelling.
- **Templates:** pipeline skeleton repo, data model design sheet, quality checklist, demo script.
- **Accessibility:** all tools are browser-based where possible; recordings and written notes support rural or remote students.

---

## 21. Success metrics (SIG-level dashboard)

- % of teams delivering a working pipeline and dashboard by Week 11 (target: 85%).
- % of graduates placed in analytics/data engineering internships or entry roles (target: 60%+). 
- Recruiter feedback on studio graduates' readiness for data platform roles.
- Correlation between advanced studio grades and internship offers / hiring outcomes.

---

## 22. 🔵 Merrill's Five Moments of Learning (pedagogical strategy)

| Merrill phase | Goal | Studio realization | When |
| --- | --- | --- | --- |
| Problem-centred | Present a real data problem. | Live brief from an enterprise-style dataset; teams define data requirements. | Week 1 |
| Activation | Recall and connect prior DBMS / Python knowledge. | Faculty links DBMS schema design and Python scripting to the current pipeline requirement. | Week 1–2 |
| Demonstration | Show working pipeline and tests. | Faculty demos ingestion, transformation, and analytics workflows using the course stack. | Week 2–3 |
| Application | Teams build their own pipeline. | Teams execute sprint tasks, implement deliverables, and receive mentor support. | Week 3–9 |
| Integration | Teams refine, optimise, and present a polished solution. | Final demo, governance review, and reflection on deployment readiness. | Week 10–12 |

**Phase coverage audit:** All five Merrill phases appear in the session plan, with explicit advanced-level integration in Weeks 8–12. ✅

---

## 23. Closing reflection for faculty

This workshop succeeds when the emphasis stays on reliable data delivery rather than on perfect analytics. The course should reward teams that move from raw data to usable insights with a working pipeline, clear documentation, and a thoughtful governance narrative. For students who need support, the early sprints must be scaffolded tightly; for advanced students, the ceiling lives in optimisation, architecture, and stakeholder communication.

---

## End-of-course faculty checklist

- [ ] Recruiter-aligned brief reviewed for the next cycle.
- [ ] Final demos and internship recommendations shared with SIG / career services.
- [ ] Students below the awareness floor flagged for follow-up support.
- [ ] CGPA calibration check recorded and verified.
- [ ] Tooling and brief changes documented for the next offering.
