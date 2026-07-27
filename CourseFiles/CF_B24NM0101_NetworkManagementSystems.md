# CF_B25CSS711 — Network Management Systems

## 0. Course identification

| Field | Entry |
|---|---|
| Faculty name | Dr. Syed Muzamil Basha |
| REVA ID | REVA02214 |
| Email | muzamilbasha.s@reva.edu.in |
| Programme | B.Tech — CSE / CSIT / ISE / IT / AIML |
| Course code | B25CSS711 |
| Course title | Network Management Systems |
| Semester & section | 7th Sem, All sections |
| Academic year | 2026–27 |
| Course duration (sessions) | 48 L (3-0-0) |
| Total period load (TPL) | 300 |
| Office / consultation hours | 42 |

## 1. Course description

This course prepares students to design, implement and troubleshoot network management solutions for modern dynamic networks. Topics include management frameworks, model-driven protocols (SNMP, NETCONF, RESTCONF, YANG), alarm and fault management, SDN/NFV management, network observability and automation using REST APIs and tooling. Emphasis is on hands-on use of NETCONF4J/RESTCONF, SNMP tools, SDN controllers and observability stacks.

## 2. Prerequisites / pre-reading

- Basic knowledge of computer networks (OSI/TCP–IP models)
- Understanding of routers, switches, hubs
- Basic hands-on experience with network simulators (Packet Tracer, GNS3, Mininet)

## 3. Course objectives

1. Understand network management concepts, frameworks and standards (TMN, FCAPS, eTOM).
2. Explain and apply SNMP, NETCONF, RESTCONF and YANG model-driven management.
3. Configure and monitor networks using NETCONF/REST APIs and client libraries (NETCONF4J, Postman).
4. Apply fault management techniques: alarm lifecycle, correlation, root-cause analysis.
5. Explore SDN, NFV and network observability with AI/ML analytics for operational insights.
6. Design scalable automated management solutions aligned with orchestration frameworks.

## 4. Course outcomes (COs) and PO/PSO mapping

| CO No | Course Outcome Description | Related Unit | POs Mapped | PSOs Mapped |
|---:|---|---:|---|---|
| CO1 | Describe, illustrate, and differentiate fundamentals of Network Management, protocols, standards, and their evolution. | Unit I | PO1, PO2, PO5, PO10, PO11 | PSO1 |
| CO2 | Explain, analyze, and summarize models/frameworks (OSI, TCP/IP, TMN, MIB) used in Network Management. | Unit II | PO1, PO2, PO3, PO4, PO5, PO10, PO11 | PSO1, PSO2 |
| CO3 | Compare, demonstrate, and implement SNMP operations and architecture including security features and RMON. | Unit III | PO1, PO2, PO3, PO4, PO5, PO9, PO10, PO11 | PSO1, PSO2 |
| CO4 | Select, evaluate, and use commercial and open-source Network Management tools and applications. | Unit IV | PO2, PO3, PO5, PO6, PO7, PO8, PO9, PO10, PO11 | PSO2 |
| CO5 | Apply, organize, and integrate FCAPS functionalities in managing real-time networks. | Unit IV | PO1, PO2, PO3, PO5, PO6, PO7, PO8, PO9, PO10, PO11 | PSO2, PSO3 |
| CO6 | Investigate, interpret, and adapt future trends in Cloud and SDN Management. | Unit IV | PO1, PO2, PO4, PO5, PO6, PO7, PO8, PO10, PO11 | PSO2, PSO3 |

### CO–PO / PSO matrix (Strength values)

| CO\\PO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PSO1 | PSO2 | PSO3 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| CO1 | 3 | 2 | 1 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 2 | 1 | 1 | 1 |
| CO2 | 2 | 3 | 2 | 1 | 1 | 0 | 0 | 0 | 0 | 1 | 3 | 1 | 1 | 1 |
| CO3 | 2 | 2 | 2 | 1 | 3 | 0 | 0 | 0 | 1 | 1 | 2 | 1 | 1 | 1 |
| CO4 | 1 | 2 | 3 | 1 | 3 | 1 | 1 | 1 | 1 | 1 | 3 | 1 | 1 | 1 |
| CO5 | 2 | 2 | 3 | 1 | 3 | 2 | 1 | 1 | 2 | 2 | 3 | 1 | 1 | 1 |
| CO6 | 1 | 2 | 1 | 3 | 2 | 1 | 2 | 1 | 1 | 1 | 2 | 1 | 1 | 1 |

## 5. Pedagogy & teaching methods

- Lectures with demonstrations (Activation = lecture + demo)
- Case studies, in-class simulations and guided exercises
- Problem-based and group-based tasks linked to real network management scenarios
- Mini-project / capstone design for automated orchestration and observability
- Guest session / industry demo (ONAP / ONF / NFV tooling)

## 6. Unit-wise syllabus and hours (48 L)

- Unit I — Introduction to Network Management and Frameworks (12 L)
  - Mobile Network management overview; eTOM and TMN frameworks
  - EMS and NMS architectures; NMS SBI (southbound) and NBI (northbound)
  - FCAPS process and responsibilities
  - SNMP introduction: concepts, evolution, architecture, PDUs (GET/SET/GETNEXT), TRAPs
  - SNMP security overview and limitations
  - YANG: evolution, motivation, basic data model concepts

- Unit II — Model-Driven Management & Protocols (12 L)
  - Model-driven management: rationale and operational benefits
  - YANG data model structure: modules, containers, lists, leaf/leaf-list, typedef, grouping
  - NETCONF protocol: concepts, operations (get, get-config, edit-config, copy-config, delete-config, lock/unlock)
  - RESTCONF: architecture, mapping NETCONF/YANG to REST, JSON/XML encodings
  - Hands-on RESTCONF via Postman examples
  - Alarm management concepts and introduction to network virtualization

- Unit III — Fault & Alarm Lifecycle, NMS Interfaces, NFV (12 L)
  - Alarm lifecycle: generation, propagation, correlation, suppression, clearance
  - Fault correlation techniques and root-cause analysis approaches
  - NMS discovery processes and FM NBI flows
  - REST API fundamentals, design patterns, authentication (OAuth, basic, tokens)
  - ONF TAPI overview (service abstraction for transport)
  - NFV concepts: VIM, VNFM, NFVO; management challenges

- Unit IV — SDN, Observability & Advanced Management (12 L)
  - SDN architecture, controller northbound/southbound functions, controller-engine responsibilities (route, switch, rollback)
  - Network observability vs monitoring: telemetry, flow traces, distributed tracing
  - Observability data collection, storage (Prometheus, InfluxDB, Kafka), and visualization (Grafana)
  - Applying analytics/AI-ML on observability data: anomaly detection, prediction methods
  - Service orchestration, ordering and assurance overview; network slicing via ONAP
  - Emerging directions and research challenges

## 7. In-class activities & experiential learning (3-0-0)

Because this is a 3-0-0 course, practical skills are developed through lecture-based activities, demonstrations, case studies and guided assignments rather than separate lab hours.

Suggested in-class activities and exercises:

1. SNMP activity: instructor-led walkthrough of SNMP GET/SET/GETNEXT with a simulated MIB browser and discussion of TRAP flows.
2. YANG modelling workshop: students review a YANG module in groups, extract the data tree, and suggest mapping to network elements.
3. NETCONF simulation: use a shared emulator or recorded demo to trace get-config/edit-config operations and discuss error-handling.
4. RESTCONF role-play: students write REST request payloads and map them to YANG model resources in small teams.
5. Fault management scenario: present an alarm flood event, then guide students through root-cause analysis and suppression design.
6. SDN case study: analyze controller-controller interaction, flow rollback, and network reconfiguration with example topology.
7. Observability design exercise: map a network service to required telemetry sources, metrics, and dashboard panels.
8. Orchestration debate: compare ONAP service ordering, assurance, and network slicing use cases in class discussions.

## 8. Assignments, activities and mini-projects

- Assignment 1 (Unit I–II): SNMP command design, YANG mapping exercise, and a short report on one management framework — 10 marks (Awareness 6 / Advanced 4).
- Assignment 2 (Unit III–IV): RESTCONF/NETCONF automation design and observability dashboard proposal — 10 marks (Awareness 6 / Advanced 4).
- Class quiz series: three short in-class quizzes on core terminology, frameworks, and protocols — 6 marks.
- Case-study reflection: one written analysis of a fault management scenario and SDN observability architecture — 4 marks.
- Mini-project design presentation: group deliverable describing an automated management architecture, alarm workflow, and observability pipeline — 10 marks.

*These activities are integrated into lecture sessions and assessed through reports, quizzes, presentations and written submissions.*

## 9. Evaluation scheme — dual-level

| Sl | Component | Marks | Weight % | Awareness marks | Advanced marks | Schedule | COs |
|---|---|---|---|---|---|---|---|
| 1 | IA-1 (Mid-test 1) | 20 | 20 | 14 | 6 | Week 8 | CO1, CO2, CO3 |
| 2 | Assignment 1 | 10 | 10 | 6 | 4 | Week 6 | CO1, CO2 |
| 3 | Assignment 2 | 10 | 10 | 6 | 4 | Week 14 | CO3, CO4, CO5 |
| 4 | Mini-project design presentation | 10 | 10 | 6 | 4 | Week 16 | CO4, CO5, CO6 |
| 5 | Class quizzes / in-class exercises | 10 | 10 | 10 | 0 | Throughout | CO1–CO4 |
| 6 | Case-study reflection | 10 | 10 | 6 | 4 | Week 12 | CO4, CO5, CO6 |
| 7 | SEE | 60 | 60 | 36 | 24 | SEE | CO1–CO6 |
|   | **Total** | **100** | **100** | **84** | **16** | | |

> **Awareness/advanced calibration:** awareness-only achievement is capped at 84%, which should be aligned with the institute's grade-point conversion to ensure that scoring above 8 CGPA requires the advanced component.

## 10. Session plan — summary (Merrill phases + level mapping)

This is a high-level session distribution (48 lecture sessions). Each lecture is 60–75 minutes depending on schedule.

- Unit I (12 sessions)
  - S1–S2: Introduction, TMN/eTOM, problem anchor (Problem-centred) — Level: Awareness — CO1
  - S3–S4: EMS/NMS architectures, SBI/NBI (Activation + Demonstration) — Level: Awareness — CO1
  - S5–S6: FCAPS deep-dive (Demonstration) — Level: Awareness — CO5
  - S7–S8: SNMP basics: PDUs, GET/SET/GETNEXT (Demonstration + Application) — Level: Awareness — CO3
  - S9: SNMP TRAPs and security (Application) — Level: Adv — CO3
  - S10–S12: YANG overview and use-cases (Demonstration + Integration) — Level: Adv — CO2

- Unit II (12 sessions)
  - S13–S14: YANG details: containers, lists, typedef (Activation + Demonstration) — CO2
  - S15–S17: NETCONF operations: get/edit-config, locking, error handling (Demonstration + Application) — CO2, CO3
  - S18–S19: RESTCONF mapping, Postman examples (Application) — Level: Awareness — CO2
  - S20–S24: Alarm management introduction and virtualization basics (Problem-centred + Application) — CO5

- Unit III (12 sessions)
  - S25–S27: Alarm lifecycle, correlation, RCA techniques (Demonstration + Application) — CO5
  - S28–S30: NMS discovery and FM NBI flows (Demonstration) — CO4
  - S31–S33: REST API patterns, auth; ONF TAPI high-level (Application) — CO4
  - S34: NFV roles (VIM/VNFM/NFVO) (Activation) — CO6

- Unit IV (12 sessions)
  - S35–S37: SDN architecture, controllers, rollbacks (Demonstration + Application) — CO6
  - S38–S40: Observability vs monitoring, telemetry collection (Application) — CO4, CO6
  - S41–S44: Analytics on observability data (basic ML pipelines for anomaly detection) (Application + Integration) — CO6
  - S45–S48: Service orchestration & ONAP overview; course wrap-up and project integration (Integration) — CO4, CO5, CO6

## 11. Assessment blueprint (question paper guidance)

- SEE paper: Part A (short answer, Bloom: Remember/Understand/Apply) — 20 marks (awareness-heavy)
- Part B (long answer, Application/Analysis) — 20 marks
- Part C (advanced/novel problem, Analysis/Evaluate/Create) — 20 marks (ceiling)

Internal tests should mirror this split at reduced scale; include at least one advanced task in each IA.

## 12. Result analysis and dual-level health checks

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared, awareness-solid) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 | | | |
| Assignment 1 | | | |
| Assignment 2 | | | |
| Case-study reflection | | | |
| Mini-project presentation | | | |
| SEE | | | |

## 13. Learner support tracking

### 13.1 Students below the floor (per IA) — remediation

| Sl | SRN | Name | IA | Gap identified | Remedial action | Re-assessment result |
|---|---|---|---|---|---|---|

### 13.2 Students reaching for the ceiling — enrichment

| Sl | SRN | Name | Advanced task assigned | Outcome |
|---|---|---|---|---|

| | No. of students | Action taken |
|---|---|---|
| Below floor (slow learners) | | |
| At ceiling (fast learners) | | |

## 14. Track-advice signal

| Field | Entry |
|---|---|
| Is this a prerequisite for a SIG track? | No — but strong students can be guided toward Network/Cloud SIGs |
| % of students at advanced level (> 75% / 8+ CGPA) | ‹…› |
| Domains where advanced performance clustered | SDN management, observability, automation |
| Recommended note to academic mentors | Students strong in CO4–CO6 are good candidates for Network/Cloud/Security SIGs. |

## 15. CO attainment

**Set target:** 60

| CO | IA1 | Assignment 1 | Assignment 2 | Case study | Mini-project | SEE | Direct attainment | Level (A/Adv) |
|---|---|---|---|---|---|---|---|---|
| CO1 | | | | | | | | A |
| CO2 | | | | | | | | A |
| CO3 | | | | | | | | Both |
| CO4 | | | | | | | | Adv |
| CO5 | | | | | | | | Adv |
| CO6 | | | | | | | | Adv |

## 16. CO–PO/PSO mapping & overall attainment

Use the repository template tables to report overall attainment. Ensure direct CO assessment covers both awareness and advanced levels separately.

## 17. Course completion summary

| Unit | Planned date | Completion date | Remarks |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |

## 18. Faculty reflection — dual-level health check

- Did the awareness floor genuinely protect placement-readiness for the weakest students? ‹…›
- Was the advanced ceiling reached by roughly the expected share, or did it collapse / go unassessed? ‹…›
- One change to the awareness/advanced split for next offering: ‹…›

## 19. Implementation strategy — Merrill's First Principles

The course uses Merrill's five phases in lecture-based activities: Problem-centred anchoring, Activation through lecture + demonstration, Demonstration of protocol operations, Application through exercises and case studies, and Integration via the mini-project design.

### 19.1 Phase-coverage check

| Check | Entry |
|---|---|
| All five Merrill phases used at least once per unit | Yes |
| Sessions using Activation = lecture + demonstration | S3–S4, S15–S17, S25–S27, S35–S37 |
| Sessions delivering Advanced-level activities | S9, S10–S12, S20–S24, S41–S48 |
| ✅ Ceiling taught (≥1 Adv activity per unit, not only assessed) | Yes |

## 20. Learning resources

### Textbooks
- Mani Subramanian, Network Management, 2010
- Raouf Boutaba, Network Management: Basics, Standards and Evolution
- William Stallings, SNMP, SNMPv2, SNMPv3, and RMON 1 and 2

### References & RFCs
- NETCONF Specification — RFC 6241
- RESTCONF — RFC 8040
- YANG — RFCs (RFC 6020 / RFC 7950 and tutorials)
- ONF TAPI documentation; ETSI NFV Framework Documentation
- NETCONF4J API and Java client docs; ncclient Python client docs

### Online resources
- [NMS Course](https://nmswipro.vercel.app/)
- Vendor documentation (Cisco IOS-XE RESTCONF/NETCONF guides)
- Prometheus, Grafana, Kafka documentation; Mininet & Ryu/ONOS tutorials

## 13. Suggested reading & demos

- Practical guides and GitHub repositories for NETCONF4J and RESTCONF examples
- Case studies on SDN-based traffic engineering and NFV orchestration

## 14. CO attainment & result analysis (templates)

Use the template tables in the repository Course_File_Template.md to record IA and SEE attainment, remediation logs, and the dual-level health-check at course close.

## 15. Academic integrity, learner support & reflections

- Plagiarism policy: zero marks for plagiarised deliverables.
- Track remedial sessions and enrichment tasks per §16 of the template.

---

Faculty signature: ‹…›
