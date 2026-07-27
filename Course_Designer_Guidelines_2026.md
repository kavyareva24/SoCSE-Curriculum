# Course Designer Guidelines — 2026 Scheme

> **Who this is for.** Faculty and SIG teams designing or revising any course in the 2026 B.Tech scheme (CSE, ISE, IT, AIML, AIDS, IoT and Cyber Security with Block chain).
>
> **What it does.** It translates the curriculum strategy into concrete design rules, organized by the **course category** and **L-T-P pattern** the course carries — because a 3-0-0 theory foundation course and a 0-0-2 workshop need very different designs. Use the decision table in §2 to find your course type, then follow the rules for that type plus the universal rules in §1.
>
> **Companion document.** Every course produces a Course File using the *Course File Template*. These guidelines tell you how to **design** the course; the template tells you how to **document** it.

---

## 1. Universal rules (every course, every category)

1. **Outcome-first.** Write Course Outcomes (COs) before content. Each CO maps to PO/PSO and is tagged with a **Bloom taxonomy level** (Remember / Understand / Apply / Analyse / Evaluate / Create) as per standard OBE practices. 
2. **Outcome Rules.** 
A well-drafted Course Outcome should not just be a vague statement. It should be structured using a maximum of four distinct **components**:

**2.1.1 Action (Mandatory):**
A measurable action verb representing the cognitive process. This must be drawn directly from Bloom's Taxonomy.

**2.1.2 Knowledge (Mandatory):**
The specific knowledge element the student is acting upon. Rao categorizes knowledge into four types: Factual, Conceptual, Procedural, and Metacognitive.

**2.1.3 Condition (Optional):**
The context, tools, or environment under which the cognitive activity needs to be performed (e.g., "using MATLAB," "given a set of user constraints").

**2.1.4 Criterion (Optional):**
The standard or performance level that the activity needs to meet (e.g., "with 90% accuracy," "to meet IEEE standards").

Example

Every course outcome should pass the **SMART test**:

**2.2.1 S - Specific:**
It should target a specific area of knowledge or skill. Avoid vague generalizations.

**2.2.2 M - Measurable:**
You must be able to assess it through an exam, project, presentation, or assignment.

**2.2.3 A - Achievable:**
It must be realistic for the students to accomplish within the timeframe and level of the course.

**2.2.4 R - Relevant:**
It must align with the broader Program Outcomes (POs) and the overall goals of the degree or curriculum.

**2.2.5 T - Time-bound:**
It is implied that this will be achieved by the end of the course.

The outcomes must be prerequisite to another outcome or final outcome which maps to a job/skill.

2. **Assessment.** Favor frequent low-stakes assessment over a single high-stakes exam. Assign a percentage of grades for meaningful engagement based on no of attempts, no of commits, prompts, no of activities completed, no of days worked.

3. **Honest contact-hour budgeting.** Design to the real contact hours implied by L-T-P (see §3), not to an idealized self-study assumption — most of the cohort will not self-study. 1 credit is 30 hours of total student load per semester.
4. **Differentiated support.** Courses should be designed such that they can be offerred in only online, blended and classroom instruction. If a student is not able to complete the no of activities in class or they miss a class, they can complete the activities in the beyond classroom hours in blended mode or online mode.
5. **Academic integrity.** Design evalution methods
a. Asking why questiosn for MCQs.
b. Submission of prompts for coding assignments.

---

## Activities

### 1. Activity and assessment alignment

- **Design activities first, then assessments.** Every activity must map to one or more COs and contribute observable evidence for CIE.
- **Activity count equals lecture sessions.** For 1-1-1 and 3-0-0 courses, design one activity per lecture session. For 0-0-2 courses, design one activity per workshop session.
- **Keep it low-stakes and frequent.** Prefer frequent, auto-graded checks over a single high-stakes evaluation event.
- **Use the current / previous / unknown sampling rule.** Every evaluation should include one item from the current week/session, one item from prior weeks/sessions, and one related but unfamiliar transfer item.
- **Auto-grade where possible.** MCQs, structured short answers, code tests, and rubric checklists reduce faculty load and provide fast feedback.

### 2. 1-1-1 course design

- **Assessment model:** CIA + SEE.
- **Activity count:** Minimum 15 activities, one per lecture session in a standard 15-week semester.
- **CIA design:** Build the CIA from classroom activities, tutorial work, and lab submissions. Each activity should have a concrete output and a short assessment or verification step.
- **Weekly evaluation:** Each weekly assessment should include current-week, prior-week, and unknown-related elements.
- **SEE design:** Use a mixed exam that combines conceptual questions with practical/programming or design problems. At least one SEE item should ask students to apply list-based skills to a new, unseen context.

### 3. 0-0-2 course design

- **Assessment model:** CIA + one project / hackathon.
- **Activity count:** One activity per workshop session.
- **Session evaluation:** Every session must include a code submission and a short formative quiz.
- **CIA design:** Use auto-grading for code submissions whenever possible. The quiz should be short, focused, and preferably auto-graded.
- **SEE design:** Final evaluation must be a project, hackathon, or live demonstration that integrates the workshop activities and rewards synthesis, design thinking, and a working artifact.

### 4. 3-0-0 course design

- **Assessment model:** 2 IA + 1 SEE.
- **Activity count:** One activity per lecture session; for a 45-lecture semester, plan 45 auto-graded activities.
- **CIA design:** Organize the activities into two internal assessments. Each IA should include current-session, earlier-session, and unknown-related items.
- **Evaluation design:** Use frequent concept checks, MCQ quizzes, structured analysis problems, or small applied questions tied to lecture content.
- **SEE design:** The final exam should preserve a clear split between conceptual mastery and analytic/applied reasoning, with at least one question drawing on a related unseen context.

### 5. Cross-cutting assessment rules

- **Match assessment to the L-T-P shape.** A 1-1-1 course must have both CIA and SEE; a 0-0-2 course must have continuous practical assessment and a final project-based SEE; a 3-0-0 course must have two IAs plus SEE.
- **Design with explicit traceability.** Maintain a CO–activity–assessment map in the course file.
- **Prefer scalable evaluation.** Auto-graded components make the course more manageable and more reliable for mixed-ability cohorts.

### 6. Example blueprint

| Course Type | Assessment Model | Activity Count | Session Evaluation | Final SEE |
|---|---|---|---|---|
| 1-1-1 | CIA + SEE | at least 15 | current + previous + unknown | Theory + practical lab exam |
| 0-0-2 | CIA + project/hackathon | One per session | Every session: code submission + quiz | Project/hackathon/presentation |
| 3-0-0 | 2 IA + 1 SEE | 45 auto-graded activities | IA1/IA2 each sample current + prior + unknown | Traditional SEE with transfer question |
