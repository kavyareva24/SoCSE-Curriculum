---
course_code: "B25CS0701"
title: "Principles of Federated Learning"
programs: [CSE, AIDS, AIML, IoT]
semester: VII
category: SC
ltpc: "3-0-0-3"
contact_hours_per_week: 3
cie: 50
see: 50
total_marks: 100
aicte_category: PEC
level: "Adv"
status: designed
---

# Course File - Dual-Level (Awareness + Advanced) Design

## 0. Course identification

| Field | Entry |
|---|---|
| Faculty name | To be assigned by HoD |
| REVA ID | To be updated |
| Email | To be updated |
| Programme | B.Tech - CSE |
| Course code | B25CS0701 |
| Course title | Principles of Federated Learning |
| Category | SC |
| L-T-P-C | 3-0-0-3 |
| Contact hours / week | 3 |
| Semester | VII |
| Section | A / B (as allotted) |
| Academic year | 2026-27 |
| Course duration (sessions) | 40 contact sessions (planned as 16 instructional blocks in Section 11) |
| Office / consultation hours | 2 hours/week (to be notified) |

School vision / mission: As per standard SoCSE statement in the approved institutional course file format.

Scheme alignment note: Category/level are set to SC/Adv in alignment with the Sem VII PE-3 track slot shown in Curriculum_Visual_Map.md. If the current CSE scheme file shows a different administrative label, treat this as an explicit waiver item for BoS reconciliation and update immediately after official codification.

---

## 1. Course description

This course introduces the principles, architectures, algorithms, communication mechanisms, privacy-preserving techniques, optimization strategies, and deployment considerations of Federated Learning (FL). The course focuses on decentralized collaborative intelligence, enabling multiple devices or organizations to train machine learning models without sharing raw data. Students study federated optimization, communication-efficient learning, personalization techniques, trust frameworks, and emerging applications in edge intelligence, healthcare, smart cities, Industry 5.0, and next-generation networks.

This course file follows an activities-first design: the Section 11 activity plan is treated as the definition of course delivery, and CO levels, unit dual-level scope, and assessment split are reverse-engineered from that implementation plan.

---

## 2. Course content (units & weightage)

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | Foundations and Architectures of Federated Learning: Evolution of distributed intelligence; centralized vs distributed learning; FL fundamentals; FL workflow and training lifecycle; cross-device FL; cross-silo FL; horizontal, vertical, hybrid and hierarchical FL; clients, servers and edge nodes; communication frameworks; client participation models; non-IID data challenges; statistical and system heterogeneity; scalability issues; resource constraints; deployment scenarios. | 25 Marks |
| 2 | Federated Optimization and Communication Efficiency: Federated optimization principles; global and local objectives; convergence challenges; FedAvg; weighted aggregation; adaptive aggregation; FedProx; FedNova; FedOpt; SCAFFOLD; clustered FL; communication bottlenecks; model compression; gradient sparsification; quantization; client selection; computation-aware scheduling; energy-efficient and latency-aware FL. | 25 Marks |
| 3 | Privacy, Security and Trust in Federated Learning: Privacy threats in FL; information leakage; membership inference; model inversion; differential privacy; secure aggregation; homomorphic encryption concepts; secure multi-party computation concepts; data poisoning; model poisoning; backdoor attacks; Byzantine adversaries; trust management frameworks; reputation-based systems; blockchain-assisted FL; robust aggregation and anomaly detection. | 25 Marks |
| 4 | Personalized Federated Learning and Emerging Applications: Personalized FL; multi-task learning; meta-learning for FL; context-aware personalization; edge intelligence and FL; edge-cloud collaboration; FL in healthcare, smart cities, industrial IoT, financial analytics and cybersecurity; FL for 5G/6G; intelligent resource management; network slicing optimization; federated foundation models; federated LLMs; split FL; green FL; quantum FL. | 25 Marks |

---

## 3. Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level - every student must reach (floor) | Advanced level - required to exceed 8 CGPA (ceiling) |
|---|---|---|
| 1 | Explain FL fundamentals, architectures, participation models, and workflow; differentiate centralized vs distributed learning; identify heterogeneity and deployment constraints. | Evaluate trade-offs among cross-device/cross-silo/hybrid FL setups under non-IID, scalability, and resource constraints; justify architecture selection for a given domain. |
| 2 | Describe federated optimization goals, standard aggregation (FedAvg), and core communication bottlenecks. | Analyze and compare advanced optimization and communication-efficient methods (FedProx, FedNova, FedOpt, SCAFFOLD, clustering, compression, scheduling) for heterogeneous and latency-constrained environments. |
| 3 | Explain key privacy/security threats and baseline protections in FL (privacy leakage, poisoning, secure aggregation, differential privacy concepts). | Assess robustness and trust design by selecting and defending advanced mechanisms (reputation, blockchain-assisted trust, robust aggregation, anomaly detection) against adversarial settings. |
| 4 | Explain personalization and edge-enabled FL use cases across healthcare, smart cities, industrial systems, and networks. | Design and critique application-oriented FL frameworks using advanced techniques (meta-learning, federated foundation models, federated LLMs, split/green/quantum FL) with domain-specific constraints. |

---

## 4. Course objectives

- Explain principles, architecture, operational workflow, and deployment models of federated learning systems for decentralized collaborative intelligence.
- Analyze federated optimization techniques, aggregation mechanisms, and communication-efficient learning strategies for distributed model training.
- Evaluate the impact of statistical heterogeneity, system constraints, scalability challenges, and resource management on FL performance.
- Assess privacy-preserving, security-enhancing, trust management, and robustness mechanisms in FL.
- Design personalized and edge-enabled federated learning frameworks for real-world applications.
- Critically examine emerging trends and future research directions in federated learning.

---

## 5. Course outcomes (COs) and PO/PSO mapping

| CO# | Course outcome | Bloom level (R/U/Ap/An/E/C) | Level (Awareness / Advanced / Both) | POs | PSOs |
|---|---|---|---|---|---|
| CO1 | Explain the principles, architecture, operational workflow, and deployment models of federated learning systems for decentralized collaborative intelligence. | U | Awareness | PO1, PO2 | PSO1 |
| CO2 | Analyze federated optimization techniques, aggregation mechanisms, and communication-efficient learning strategies for distributed model training under heterogeneous environments. | An | Both | PO1, PO2, PO4 | PSO1, PSO2 |
| CO3 | Evaluate the impact of statistical heterogeneity, system constraints, scalability challenges, and resource management issues on federated learning performance. | E | Advanced | PO2, PO3, PO4 | PSO1, PSO2 |
| CO4 | Assess privacy-preserving, security-enhancing, trust management, and robustness mechanisms used to protect federated learning systems against adversarial threats and information leakage. | E | Both | PO2, PO3, PO5 | PSO2, PSO3 |
| CO5 | Design personalized and edge-enabled federated learning frameworks for real-world applications in healthcare, smart cities, industrial systems, cybersecurity, and next-generation communication networks. | C | Both | PO3, PO4, PO5 | PSO2, PSO3 |
| CO6 | Critically examine emerging trends, advanced architectures, and future research directions in federated learning, including federated foundation models, federated large language models, green federated learning, and intelligent distributed AI ecosystems. | E/C | Advanced | PO1, PO2, PO12 | PSO3 |

Activity-to-CO derivation basis (Section 11):
- CO1: Sessions 01-03 (Awareness)
- CO2: Sessions 05-07 (Awareness + Both)
- CO3: Sessions 04 and 08 (Advanced)
- CO4: Sessions 09-12 (Awareness + Both + Advanced)
- CO5: Sessions 13-15 (Awareness + Both + Advanced)
- CO6: Session 16 (Advanced)

---

## 6. Pedagogy

- Direct teaching with concept lectures
- Guided analysis of research papers and case studies
- Demonstration-based discussion of FL workflows and algorithms
- Problem-based sessions on optimization, privacy, and trust design
- Application-oriented mini design tasks

---

## 7. Textbooks, references, e-resources

Textbook(s):
- Yang, Q., Liu, Y., Cheng, Y., Kang, Y., Chen, T., and Yu, H. (2019). Federated Learning. Morgan and Claypool Publishers.
- Thai, M. T., Phan, H. N., and Thuraisingham, B. (Eds.). (2025). Handbook of Trustworthy Federated Learning. Springer.
- Jin, Y., Zhu, H., Xu, J., and Chen, Y. (2023). Federated Learning. Springer Nature Singapore.

References:
- Nguyen, L. M., Hoang, T. N., and Chen, P. Y. (Eds.). (2024). Federated Learning: Theory and Practice. Elsevier.
- Foley, P., Sheller, M. J., Edwards, B., Pati, S., Riviera, W., Sharma, M., et al. (2022). OpenFL: The Open Federated Learning Library. Physics in Medicine and Biology, 67(21), 214001.
- Krishnan, S., Anand, A. J., Srinivasan, R., Kavitha, R., and Suresh, S. (2024). Federated Learning. CRC Press.
- Ludwig, H., and Baracaldo, N. (Eds.). (2022). Federated Learning: A Comprehensive Overview of Methods and Applications. Springer.
- Yadav, S. P., Bhati, B. S., Mahato, D. P., and Kumar, S. (Eds.). (2022). Federated Learning for IoT Applications. Springer.
- Hong, C. S., Khan, L. U., Chen, M., Chen, D., Saad, W., and Han, Z. (2021). Federated Learning for Wireless Networks. Springer.

Web / e-books / NPTEL:
- NPTEL: Deep Learning / Distributed Systems electives relevant to FL
- Papers With Code: Federated Learning benchmarks and implementations
- Flower / FedML / OpenFL official documentation for framework exposure
- Selected recent NeurIPS, ICLR, ICML, IEEE TMC, and IEEE IoT-J FL papers

---

## 8. Differentiated instruction (mapped to the two levels)

Reaching the floor (awareness level) - for students at risk:
- Remedial sessions on FL fundamentals, workflow, and baseline algorithms
- Scaffolded worksheets for heterogeneity, convergence, and privacy basics
- Structured peer-support and concept recap quizzes

Reaching the ceiling (advanced level) - for students aiming above 8 CGPA:
- Paper critique tasks on optimization, secure aggregation, and robust FL
- Stretch design tasks for domain-specific FL architecture decisions
- Advanced reading and seminar presentations on federated foundation models, FLLMs, and green FL

Intake-aware bridge plan (Weeks 0-1):
- Diagnostic prerequisite check on probability, optimization, ML training loop, and model evaluation
- Bridge capsule A: probability/statistics refresh (2 contact sessions + worksheet)
- Bridge capsule B: gradient-based optimization and convergence intuition (2 contact sessions + quiz)
- Bridge capsule C: secure/distributed ML basics primer for non-prior-exposure learners (2 contact sessions)
- Students below threshold in diagnostic are auto-enrolled into bridge support with mentor follow-up

---

## 9. Assignments

| Assignment | Units covered | Marks | Window | Level (Awareness / Advanced) |
|---|---|---|---|---|
| Assignment 1 | Unit 1 and Unit 2 | 5 | Before IA-2 | Awareness |
| Assignment 2 | Unit 3 and Unit 4 | 5 | Before SEE | Advanced |

---

## 10. Prerequisites / pre-reading

Machine Learning, Artificial Intelligence, Deep Learning, Probability and Statistics, Data Analytics.

---

## 11. Lesson plan - tentative transaction dates + session implementation

| S.No | Planned date | Exec. date | Unit / topic | Merrill phase | Activity (what the faculty runs) | % compl. | Level (A/Adv) | CO | Remarks |
|---|---|---|---|---|---|---|---|---|---|
| 01 | Week 1 (S1) | To be entered after delivery | Unit 1 - FL motivation and distributed intelligence | Problem-centred + Activation | Present healthcare/smart-city FL scenario, followed by lecture and prior-knowledge activation quiz. | 5% | A | CO1 | Block spans 2 sessions |
| 02 | Week 1 (S2) | To be entered after delivery | Unit 1 - FL workflow and lifecycle | Demonstration | Instructor walkthrough of end-to-end federated training lifecycle with client-server cycle. | 10% | A | CO1 | Block spans 2 sessions |
| 03 | Week 2 (S3) | To be entered after delivery | Unit 1 - FL architectures (cross-device/cross-silo/hybrid) | Application | Guided classification exercise: choose architecture for given deployment contexts. | 15% | A | CO1 | Block spans 2 sessions |
| 04 | Week 2 (S4) | To be entered after delivery | Unit 1 - non-IID and system heterogeneity | Application + Integration | Case analysis on heterogeneity impact and architecture trade-off justification. | 25% | Adv | CO3 | Block spans 4 sessions |
| 05 | Week 3 (S5) | To be entered after delivery | Unit 2 - federated optimization basics and FedAvg | Problem-centred + Activation + Demonstration | Problem-first lecture + worked derivation of global/local objectives and FedAvg update cycle. | 30% | A | CO2 | Block spans 3 sessions |
| 06 | Week 4 (S6) | To be entered after delivery | Unit 2 - advanced optimization methods | Demonstration | Comparative walkthrough of FedProx, FedNova, FedOpt, and SCAFFOLD behavior. | 40% | Both | CO2 | Block spans 3 sessions |
| 07 | Week 4 (S7) | To be entered after delivery | Unit 2 - communication efficiency methods | Application | Practice activity on compression, sparsification, quantization decisions by scenario. | 50% | A | CO2 | Block spans 2 sessions |
| 08 | Week 5 (S8) | To be entered after delivery | Unit 2 - scheduling and client selection | Integration | Design mini-task: optimize client selection under energy and latency constraints. | 50% | Adv | CO3 | Block spans 2 sessions |
| 09 | Week 6 (S9) | To be entered after delivery | Unit 3 - privacy threats and leakage | Problem-centred + Activation | Recap quiz and threat-model mapping activity for membership/model inversion attacks. | 58% | A | CO4 | Block spans 2 sessions |
| 10 | Week 6 (S10) | To be entered after delivery | Unit 3 - secure aggregation and differential privacy | Demonstration | Guided demonstration of privacy-preserving pipeline choices and limitations. | 65% | A | CO4 | Block spans 3 sessions |
| 11 | Week 7 (S11) | To be entered after delivery | Unit 3 - poisoning and Byzantine threats | Application | Group exercise to identify attack vectors and propose mitigation controls. | 72% | Both | CO4 | Block spans 3 sessions |
| 12 | Week 8 (S12) | To be entered after delivery | Unit 3 - trust frameworks and robust aggregation | Integration | Advanced critique of trust/reputation/blockchain-assisted FL and robust aggregation. | 75% | Adv | CO4 | Block spans 2 sessions |
| 13 | Week 9 (S13) | To be entered after delivery | Unit 4 - personalization and edge FL | Problem-centred + Activation + Demonstration | Problem-framed lecture and scenario demo for personalization in mobile/edge settings. | 82% | A | CO5 | Block spans 2 sessions |
| 14 | Week 10 (S14) | To be entered after delivery | Unit 4 - domain applications (healthcare, smart cities, cybersecurity) | Application | Team activity mapping FL design patterns to selected real-world domain constraints. | 90% | Both | CO5 | Block spans 2 sessions |
| 15 | Week 11 (S15) | To be entered after delivery | Unit 4 - FL for 5G/6G and resource management | Application + Integration | Advanced design challenge for network-aware federated orchestration. | 95% | Adv | CO5 | Block spans 2 sessions |
| 16 | Week 12 (S16) | To be entered after delivery | Unit 4 - emerging trends (FLLMs, split FL, green FL, quantum FL) | Integration | Seminar and synthesis reflection on future FL research directions. | 100% | Adv | CO6 | Block spans 4 sessions |

Section 11 budgeting note: each row is an instructional block (2-4 contact sessions). Total planned contact sessions across blocks = 40.

---

## 12. ICT & digital support

- FL simulation/notebook demonstrations for training rounds and aggregation behavior
- Visualization tools for convergence, communication cost, and heterogeneity impact
- Open-source FL frameworks for guided demonstrations (for example OpenFL/FedML-like workflows)
- NPTEL/MOOC and recent conference paper resources

---

## 13. Academic integrity policy

Standard policy applies. Plagiarism, fabricated results, unauthorized collaboration, or misrepresentation in any evaluation component will attract disciplinary action and can result in zero marks.

---

## 14. Evaluation scheme - dual-level

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
|---|---|---|---|---|---|---|---|
| 1 | Test 1 (IA-1) | 20 | 20 | 14 | 6 | Week 5 | CO1-CO3 |
|  | Test 2 (IA-2) | 20 | 20 | 14 | 6 | Week 10 | CO4-CO6 |
|  | Assignment 1 | 5 | 5 | 3 | 2 | Week 6 submission | CO1-CO3 |
|  | Assignment 2 | 5 | 5 | 3 | 2 | Week 11 submission | CO4-CO6 |
| 2 | SEE | 50 | 50 | 36 | 14 | End of semester | CO1-CO6 |
| CIE Total |  | 50 | 50 | 34 | 16 |  |  |
| Grand Total |  | 100 | 100 | 70 | 30 |  |  |

### 14.1 CGPA calibration check

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | REVA 10-point scale reference used in existing course files: 80+ marks corresponds to 8 CGPA band; 70-79 marks corresponds to 7 CGPA band. |
| Max % achievable from awareness marks alone | 70% |
| Grade band that % falls into | 7 CGPA band (below 8 CGPA) |
| Advanced marks needed to cross 8 CGPA | At least 10 marks out of the 30 advanced marks (70 + 10 = 80). |
| Calibration confirmed (awareness-only < 8 CGPA) | Yes |

### 14.2 Question-paper blueprint

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| IA-1 / IA-2 | Fundamentals, workflow, baseline optimization, standard-case privacy/security questions | Trade-off analysis, robust method selection, architecture/design justification in unfamiliar scenarios |
| SEE | Balanced unit-wise standard-case coverage | At least one high-cognitive advanced question per unit (analysis/evaluation/design) |

---

## 15. Result analysis

| Exam | < 40% (below floor - remediate) | 40-75% (floor cleared) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 |  |  |  |
| IA-2 |  |  |  |
| Assignment 1 |  |  |  |
| Assignment 2 |  |  |  |
| SEE |  |  |  |

---

## 16. Learner support tracking

### 16.1 Remediation (students below floor)

| Sl | SRN | Name | IA | Gap identified | Remedial class dates | Re-assessment result |
|---|---|---|---|---|---|---|
| 1 | To be entered | To be entered | IA-1/IA-2 | FL fundamentals / optimization / privacy basics | Week 6 and Week 11 support slots | To be entered |

### 16.2 Enrichment (students reaching for ceiling)

| Sl | SRN | Name | Advanced task assigned | Outcome |
|---|---|---|---|---|
| 1 | To be entered | To be entered | Research critique + design note on advanced FL method | To be entered |

| Group | No. of students | Action taken |
|---|---|---|
| Below floor (slow learners) |  |  |
| At ceiling (fast learners) |  |  |

---

## 17. Track-advice signal

| Field | Entry |
|---|---|
| Is this a prerequisite for a SIG track? | Yes - AI/ML Systems, Edge Intelligence, and Intelligent Cyber Systems tracks |
| % of students at advanced level (> 75% / 8+ CGPA) | To be computed after SEE |
| Domains where advanced performance clustered | To be identified from CO5 and CO6 performance evidence |
| Recommended note to academic mentors | Students consistently strong in advanced design and evaluation tasks may be advised toward AI/ML and Edge AI-heavy pathways. |

---

## 18. CO attainment

Target: 60%

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level |
|---|---|---|---|---|---|---|---|
| CO1 | To be entered | To be entered | To be entered | NA | To be entered | To be computed | Awareness |
| CO2 | To be entered | To be entered | To be entered | NA | To be entered | To be computed | Both |
| CO3 | To be entered | To be entered | To be entered | NA | To be entered | To be computed | Advanced |
| CO4 | NA | To be entered | NA | To be entered | To be entered | To be computed | Both |
| CO5 | NA | To be entered | NA | To be entered | To be entered | To be computed | Both |
| CO6 | NA | To be entered | NA | To be entered | To be entered | To be computed | Advanced |

---

## 19. CO-PO/PSO mapping & overall attainment

Strength: 1 = Low, 2 = Medium, 3 = High

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 | PSO3 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | - | - | - | - | - | - | - | - | - | - | 3 | - | - |
| CO2 | 3 | 3 | - | 2 | - | - | - | - | - | - | - | - | 3 | 2 | - |
| CO3 | 2 | 3 | 2 | 2 | - | - | - | - | - | - | - | - | 3 | 2 | - |
| CO4 | - | 3 | 2 | - | 3 | - | - | - | - | - | - | - | - | 3 | 2 |
| CO5 | - | 2 | 3 | 2 | 2 | - | - | - | - | - | - | - | - | 3 | 3 |
| CO6 | 2 | 2 | - | - | - | - | - | - | - | - | - | 3 | - | - | 3 |

Overall attainment (Direct 80% + Indirect/Feedback 20%):

| Metric | Internal | External | Grand total (80%+20%) |
|---|---|---|---|
| CO attainment |  |  |  |
| PO attainment |  |  |  |
| PSO attainment |  |  |  |

Minimum level for PO attainment: 50%-60%

---

## 20. Course completion summary

| Unit | Planned date | Completion date | Remarks |
|---|---|---|---|
| 1 | Week 1-2 | To be entered after delivery |  |
| 2 | Week 3-5 | To be entered after delivery |  |
| 3 | Week 6-8 | To be entered after delivery |  |
| 4 | Week 9-12 | To be entered after delivery |  |

---

## 21. Faculty reflection - dual-level health check

- Did the awareness floor protect baseline readiness for students with weaker prerequisite coverage? To be completed after final attainment analysis.
- Was the advanced ceiling reached by the expected share, and was it taught and assessed coherently? To be completed after final attainment analysis.
- One change to improve awareness/advanced split in the next offering: To be recorded in course-close review meeting.

Review status log:
- Faculty review completed (activities-first design confirmation): 2026-07-10
- Checklist/strategy review completed: 2026-07-10

---

## 22. Implementation strategy - Merrill's First Principles

Learning activities in Section 11 are aligned to Merrill's five phases: problem-centred, activation, demonstration, application, and integration. Each unit includes both awareness-level and advanced-level activity touchpoints, with advanced sessions concentrated in design, trade-off, and transfer-oriented tasks.

### 22.1 Phase-coverage check

| Check | Entry |
|---|---|
| All five Merrill phases used at least once per unit | Yes |
| Section 11 sessions using Activation = lecture + demonstration | 01, 05, 09, 13 |
| Section 11 sessions delivering Advanced-level activities | 04, 08, 12, 15, 16 |
| Ceiling taught (>=1 Adv activity per unit, not only assessed) | Yes |

---

Signatures:

Course Faculty (digital signature): Dr. Nimrita Koul, Dr. Anooja Ali; digital approval record to be attached in submission packet

HoD / Director (digital signature): Pending final administrative approval
