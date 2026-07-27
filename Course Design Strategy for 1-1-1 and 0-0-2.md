# Course Design Strategy for 1-1-1 and 0-0-2

## Course Design Strategy for 1-1-1 course

### 1. Course Outcomes (COs) Strategy
The floor-level 1-1-1 course must establish a strong, accessible foundation for mixed-ability cohorts while staying aligned with employer expectations for entry-level programming and problem-solving.
* **Target Range:** Define 4 to 6 Course Outcomes (COs).
* **Alignment:** COs must be explicitly aligned with student demographics, including prior exposure to coding, logical reasoning, and applied mathematics, and with industry requirements such as readable code, debugging, modular design, and basic algorithmic thinking.
* **Floor Orientation:** Keep the COs focused on the course floor. Advanced ceiling outcomes are not part of this course; those are served separately by the Intense Programming Lab (IPL).
* **Example COs:**
  * CO1: Describe and apply fundamental programming constructs, control flow, and data structures to solve routine problems.
  * CO2: Develop, test, and debug simple programs with clear code structure, comments, and basic input/output handling.
  * CO3: Analyze small problem statements and decompose them into modular program components using functions or procedures.
  * CO4: Interpret program behavior and justify algorithmic choices through short text-based explanations.
  * CO5: Execute practical coding tasks under guided lab conditions and validate outcomes against expected results.

### 2. Weekly Contact & Engagement Model
The weekly design preserves the integrated 1-1-1 rhythm while making tutorial/lab time the primary practice and assessment window.

| Component | Duration | Operational Guidelines |
| :--- | :--- | :--- |
| **Teaching (Lecture/Theory)** | 1 Hour | Introduce concepts, explain the theory behind constructs, and demonstrate small examples. Keep the lecture tightly linked to the next practical activity. |
| **Practice (Tutorial)** | 2 Hours | Students work on guided exercises, coding tasks, or code reading. Teachers must meet every student at least once in each two-week cycle to assess understanding, remove misconceptions, and provide tailored support. |
| **Evaluation (Lab)** | 2 Hours | Use this time for weekly tests, lab checkpoints, formative quizzes, and small practice exams that include both theory and practical components. |

### 3. Activity Design Framework
A 1-1-1 course should be driven by discrete classroom and lab activities that map directly to the COs and the weekly assessment rhythm.
* **Target Count:** Design around 15 ± 2 activities for the semester.
* **Alignment:** Each activity must clearly link to one or more COs and should be tagged with the primary CO it supports.
* **Activity Types:** Include scaffolded coding tasks, code tracing exercises, debugging challenges, program-writing labs, and short reflective write-ups that ask students to justify their design decisions.
* **Practical Focus:** Every activity should have a real practical output, whether a runnable program, a debugging fix, or a test-driven check. Theory is introduced in the lecture and reinforced through practice.

### 4. Continuous Internal Assessment (CIA)
Weekly assessment is the central formative engine for a 1-1-1 floor course.
* **Weekly Tests:** Conduct weekly tests that include a balanced mix of theory questions and practical coding problems.
* **Prior-CO Coverage:** Reserve a small percentage of each test (typically 10–15%) for previously covered COs, ensuring spaced repetition and retention.
* **Theory + Practical Balance:** Design each weekly test to assess both conceptual understanding (e.g. MCQs, short justification prompts) and applied skills (e.g. code writing, debugging tasks).
* **Make-up / Repeat Tests:** Offer weekly repeat tests as make-up opportunities for CIA. These allow students to recover marks and demonstrate improved understanding before the end of the semester.

### 5. Semester End Examination (SEE)
The SEE must follow the ACP model with separate but coherent theory and practical components.

| SEE Component | Format & Details |
| :--- | :--- |
| **Theory Component** | **Format:** MCQs with paired text-based "Why/Justification" prompts. This combination is autograded where possible, but it must still require students to explain reasoning in brief text form. |
| **Practical / Lab Component** | **Format:** Lab exam consisting of an assigned set of 'X' programs that students must implement and execute. |
| **Unknown Program Requirement** | Include at least one unknown or unseen program in the lab exam to test independent problem-solving within the floor-level scope. |

### 6. Floor Course Clarification
* This strategy is explicitly for the floor-level 1-1-1 course. The advanced ceiling is handled by the Intense Programming Lab (IPL) track.
* The 1-1-1 course should therefore prioritize confidence, correctness, and consistent practice over ambitious completion of advanced topics.

---

## Course Design Strategy for 0-0-2 course

### 1. Course Outcomes (COS) Strategy
For a purely practical, workshop-driven course, the learning objectives must reflect hands-on competencies and real-world application.
* **Target Range:** Define 4 to 6 Course Outcomes (COs).
* **Alignment:** COs must directly address industry requirements (e.g., version control, deployment, applied problem solving) while remaining accessible to the specific student demographics and their prior technical exposure.
* **Action-Oriented:** Utilize higher-order cognitive levels (Apply, Analyze, Create) to ensure students are building rather than just recalling.

### 2. Activity Structure
This course abandons traditional semester pacing in favor of an intensive, day-by-day workshop model.
* **Activity Count:** The number of activities should be equal to the number of sessions available for the workshop.
* **Progression:** Activities should ideally build cumulatively, allowing the daily accomplishments to form the foundation of the final Semester End Examination (SEE) project.

### 3. Workshop Session Structure (The 110-Minute Cycle)
Every single workshop session follows a strict, time-boxed pedagogical cycle designed to maximize active learning and immediate application.

| Duration | Phase | Operational Guidelines |
| :--- | :--- | :--- |
| **10 mins** | Activation | Hook the students. Recall prior knowledge, state the daily objective, or present the real-world problem being solved today. |
| **20 mins** | Demonstration | Live coding, system walkthrough, or architectural breakdown. Show how to approach the day's specific problem. |
| **60 mins** | Application | Core hands-on practice. Students work independently or in pairs to execute the day's activity. |
| **10 mins** | Integration | Bring the cohort back together. Summarize the key takeaways, debug common errors found during the application phase, and connect the day's work to the broader course goals. |
| **10 mins** | Quiz | Formative assessment to lock in the day's concepts before dismissal. |

### 4. Continuous Internal Assessment & Daily Auto-Grading
Evaluation in this model is high-frequency and tightly integrated with standard developer workflows.
* **GitHub-Driven Evaluation:** Daily application accomplishments are submitted and evaluated predominantly using GitHub. Leveraging platforms like GitHub Classroom allows for immediate, automated feedback through continuous integration (CI) tests, ensuring students meet the daily baseline without creating an unmanageable grading bottleneck.
* **Daily Quizzes:** The 10-minute closing quiz contributes to the continuous tracking of theoretical understanding alongside the practical GitHub commits.

### 5. Semester End Examination (SEE) Framework
The final evaluation steps away from traditional written exams, dividing assessment into a high-stakes practical application and a distinct theory verification.
* **Practical SEE (Hackathon / Presentation):** * Replaces the standard lab exam. Students participate in a time-bound hackathon or deliver a project presentation.
    * This evaluates their ability to synthesize the 16 daily activities into a cohesive, functional product.
