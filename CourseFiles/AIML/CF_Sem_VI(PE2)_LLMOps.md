# Course File — Dual-Level (Awareness + Advanced) Design

### PE2 — LLMOps | AIML | Semester VI | AY 2026–27

## 0. Course identification 🟢

| Field | Entry |
|---|---|
| Faculty name | Kartikey Sachan |
| REVA ID | REVA03483 |
| Email | kartikey.sachan@reva.edu.in |
| Programme | B.Tech — AIML |
| Course code | PE2-LLMOps / B24EA06XX |
| Course title | LLMOps |
| Semester & section | VI — A/B |
| Academic year | 2026–27 |
| Course duration (sessions) | 48 sessions (Theory + Tutorial + Practical integration) |
| Office / consultation hours | Monday–Friday, 2:30 PM–4:30 PM |
| Dual-Level Designation | A + Adv |
| Category | PE2 / Elective |

**School vision:** To emerge as a globally recognized department of computer science in education, research, and innovation that advances technology for sustainable development, serves humanity, and nurtures ethically responsible leaders for the digital future.

**School mission:** To provide learner-centric education in computer science and engineering, leveraging cutting-edge technologies to empower students with strong theoretical foundations, practical skills, and interdisciplinary knowledge; to foster innovation, research, and entrepreneurship in emerging areas of computer science while promoting sustainability, inclusivity, and universal values; to prepare graduates for lifelong learning and impactful careers; to build a culture of collaboration through industry–academia partnerships; and to serve society through technology solutions that enhance human well-being.

---

## 1. Course description 🟢

This course bridges the gap between LLM theory and real-world practice by introducing students to the lifecycle of production-ready generative AI systems. Students learn how to design prompts, build retrieval-augmented generation pipelines, evaluate model behaviour, deploy and monitor LLM applications, and manage safety, cost, and governance concerns. The course is designed to develop practical expertise for AI engineering roles, startups, and product teams where LLM systems must be reliable, scalable, and responsible.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | Foundations of LLMs and LLMOps — LLM lifecycle, transformer basics, prompt design, tokens, context window, APIs, model selection, environment setup, versioning, and workflow orchestration. | 25 Marks |
| 2 | Prompt engineering and retrieval-augmented generation — prompt templates, tool calling, function calling, embeddings, chunking, vector stores, document ingestion, retrieval strategies, and RAG evaluation. | 25 Marks |
| 3 | Evaluation, deployment, and observability — testing strategies, hallucination checks, latency/cost monitoring, CI/CD for LLM apps, model registry, deployment patterns, logging, tracing, and dashboards. | 25 Marks |
| 4 | Safety, governance, and capstone operations — guardrails, responsible AI, privacy, human-in-the-loop review, cost optimization, prompt/model versioning, and end-to-end LLMOps mini-project. | 25 Marks |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (the floor) | Advanced level — required to exceed 8 CGPA (the ceiling) |
|---|---|---|
| 1 | Explain the LLM lifecycle, transformer basics, prompt design, and API-based application workflow; configure a basic local or cloud-based LLM environment and compare model choices for a simple task. | Analyse trade-offs among models, context-window limits, latency, cost, and deployment constraints for a novel use case; justify a model-selection strategy for a production scenario. |
| 2 | Apply prompt templates and basic retrieval techniques to a standard document-query task; explain chunking, embeddings, and vector search at a conceptual level. | Design and evaluate an end-to-end RAG pipeline for an unfamiliar domain, compare retrieval strategies, and justify chunking, indexing, and re-ranking choices. |
| 3 | Run a basic LLM evaluation workflow using accuracy, relevance, and latency checks; describe monitoring, logging, and deployment patterns for LLM systems. | Design a robust deployment and observability pipeline with versioning, regression testing, dashboards, and failure analysis for real-world traffic. |
| 4 | Identify guardrails, privacy concerns, and responsible-AI principles relevant to LLM applications; describe human-in-the-loop review and cost-control practices. | Build and defend a full LLMOps solution that includes guardrails, safety review, cost optimisation, governance, and continuous improvement for a live product context. |

**Bloom anchor:**

| Level | Bloom verbs | Typical question stem |
|---|---|---|
| Awareness (floor) | Remember, Understand, Apply | “Define…”, “Explain…”, “Apply X to this standard case…”, “Use the given prompt template to…”. |
| Advanced (ceiling) | Analyse, Evaluate, Create | “Compare and justify…”, “Design a solution for…”, “Evaluate the trade-off between…”, “Propose and defend…”. |

---

## 4. Course objectives 🟢

- Understand the LLM lifecycle and the principles of LLMOps in real production environments.
- Design and refine prompt-based solutions for common business and academic tasks.
- Build retrieval-augmented generation systems using embeddings, chunking, and vector stores.
- Evaluate LLM applications for quality, reliability, latency, hallucination, and cost.
- Deploy and monitor LLM systems using modern tools and operational practices.
- Apply responsible AI, safety, and governance practices in production-grade AI workflows.

---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Level (Remember / Understand / Apply / Analyse / Evaluate / Create) 🔵 | POs | PSOs |
|---|---|---|---|---|
| CO1 | Explain the LLM lifecycle, transformer-based foundations, and the role of LLMOps in delivering reliable AI products. | Understand | PO1(3), PO2(2), PO5(2) | PSO1(3) |
| CO2 | Design and compare prompt-based workflows, tool use, and orchestration patterns for task-oriented LLM applications. | Apply | PO1(3), PO2(3), PO3(2), PO5(2) | PSO1(3), PSO2(2) |
| CO3 | Build and evaluate retrieval-augmented generation pipelines using embeddings, chunking, vector stores, and retrieval strategies. | Analyse | PO1(3), PO2(3), PO3(3), PO4(2), PO5(3) | PSO1(3), PSO2(3) |
| CO4 | Deploy and manage LLM applications using APIs, versioning, CI/CD, logging, and monitoring practices. | Create | PO1(3), PO2(3), PO3(3), PO4(3), PO5(3), PO10(2) | PSO1(3), PSO2(3) |
| CO5 | Evaluate LLM systems for quality, latency, cost, hallucination, safety, and resilience using practical testing methods. | Evaluate | PO1(3), PO2(3), PO4(3), PO7(2), PO8(3) | PSO1(3), PSO3(2) |
| CO6 | Develop and present an end-to-end LLMOps mini-project that integrates prompting, RAG, deployment, monitoring, and responsible AI controls. | Create | PO1(3), PO2(3), PO3(3), PO4(3), PO5(3), PO8(3), PO10(2) | PSO1(3), PSO2(3), PSO3(3) |

🔵 Rationale for the level tags: CO1 establishes the placement-readiness floor by covering the vocabulary and workflow of modern LLM systems. CO2–CO3 build applied skills that are directly relevant to internships and industry projects. CO4–CO6 represent the advanced ceiling because they require design, deployment, evaluation, and product-style thinking beyond textbook recall.

---

## 6. Pedagogy 🟢

- Direct instruction for core concepts such as transformers, prompt design, RAG, and deployment basics.
- Demonstration-led learning using live coding sessions with LLM APIs and open-source tooling.
- Problem-based learning using case studies from customer support, document Q&A, and enterprise assistants.
- Project-based learning through a semester-long mini-project that simulates a real product workflow.
- Peer review and reflection to strengthen design reasoning and deployment discipline.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
1. Instructor-developed notes and curated industry handouts for LLMOps and generative AI deployment.
2. Selected chapters from NLP and Generative AI texts used for foundation concepts.

**References:**
1. Lewis Tunstall, Leandro von Werra, Thomas Wolf — Natural Language Processing with Transformers.
2. Chip Huyen — Designing Machine Learning Systems.
3. O’Reilly materials on prompt engineering, RAG, and MLOps.

**Web / e-books / NPTEL / MOOCs:**
1. OpenAI API documentation and prompt engineering guides.
2. Hugging Face transformers and inference documentation.
3. LangChain / LlamaIndex documentation for orchestration and RAG.
4. MLflow, Weights & Biases, Docker, GitHub Actions, and vector-database documentation.

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk of not clearing it:**
- Remedial support after IA-1 for students struggling with prompt basics, retrieval concepts, or API usage.
- Curated worked examples and short videos on prompt templates, embeddings, and basic deployment steps.
- Peer mentoring for lab activities and guided notebook walkthroughs.
- Scaffolded assignments that begin with explanation and basic application before open-ended design tasks.

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**
- Advanced mini-project extensions such as multi-agent orchestration, evaluation dashboards, or cost-aware optimisation.
- Journal/paper review on RAG, eval frameworks, guardrails, or observability.
- Stretch tasks requiring model selection justification, safety design, and deployment trade-off analysis.
- Optional participation in open-source LLM challenge or hackathon-style project.

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window | Level (Awareness / Advanced) |
|---|---|---|---|---|
| Assignment 1 | Unit 1 | 5 | Week 3 | Awareness |
| Assignment 2 | Unit 2 | 5 | Week 6 | Awareness |
| Assignment 3 | Unit 3 | 5 | Week 9 | Advanced |
| Assignment 4 | Unit 4 | 5 | Week 12 | Advanced |
| Final Project | All Units | 10 | Week 15–16 | Advanced |

### 9.1 Unit-wise mini-project assignments

| Unit | Mini-project assignment | Expected output |
|---|---|---|
| Unit 1 | Build a prompt-based assistant for a simple domain such as student query handling or FAQ support. | Prompt design, sample responses, and a short evaluation note |
| Unit 2 | Create a document Q&A system using a basic RAG workflow with a small knowledge base. | Working prototype, chunking strategy, and retrieval example |
| Unit 3 | Develop an LLM evaluation notebook that compares response quality, latency, and cost for two prompt versions. | Evaluation report and metrics table |
| Unit 4 | Design a safe and monitored LLM application with guardrails, logging, and basic observability. | Guardrail design, monitoring plan, and demo |
| Final Project | Build an end-to-end LLMOps solution that integrates prompting, RAG, evaluation, deployment, monitoring, and responsible AI controls for one use case. | Full project demo, code repository, and report |

### 9.2 Suggested weekly learning activities (16 activities)

| Week | Activity | Type | Deliverable |
|---|---|---|---|
| 1 | Module Quiz 1 — LLM lifecycle and prompt basics | Quiz | 10-question quiz, 10 marks, 1 mark each |
| 2 | Virtual experiment on prompt temperature, top-p and token limits | Virtual experiment | Recorded observation sheet |
| 3 | Prompt-template comparison task | Activity | Compare 3 prompt strategies |
| 4 | Module Quiz 2 — transformers, context window, and hallucination basics | Quiz | 10-question quiz, 10 marks, 1 mark each |
| 5 | Virtual experiment on context-window and response quality trade-offs | Virtual experiment | Comparative report |
| 6 | Assignment 1: design a prompt-based assistant for a simple use case | Assignment | Report + code notebook |
| 7 | Module Quiz 3 — embeddings, chunking, and retrieval concepts | Quiz | 10-question quiz, 10 marks, 1 mark each |
| 8 | Virtual experiment on chunking and vector retrieval quality | Virtual experiment | Retrieval analysis report |
| 9 | Assignment 2: build a basic RAG pipeline for document Q&A | Assignment | Working RAG prototype |
| 10 | Module Quiz 4 — evaluation metrics: relevance, faithfulness, latency, and cost | Quiz | 10-question quiz, 10 marks, 1 mark each |
| 11 | Virtual experiment on LLM evaluation using automated checks | Virtual experiment | Evaluation notebook and metrics table |
| 12 | Assignment 3: create a monitoring and observability dashboard for an LLM app | Assignment | Dashboard + short write-up |
| 13 | Module Quiz 5 — guardrails, privacy, and responsible AI practices | Quiz | 10-question quiz, 10 marks, 1 mark each |
| 14 | Virtual experiment on safety/guardrail configuration and fail-safe handling | Virtual experiment | Guardrail test log |
| 15 | Final Module Quiz 6 — comprehensive quiz on all covered topics | Quiz | 10-question comprehensive quiz, 10 marks, 1 mark each |
| 16 | Mini-project: end-to-end LLMOps solution with prompt design, RAG, evaluation, and deployment | Mini-project | Final project demo and report |

### 9.2 Quiz structure (module-wise)

Each quiz will contain 10 questions, each carrying 1 mark.

- 5 easy questions
- 3 moderate questions
- 2 hard questions

The final quiz will be a comprehensive assessment covering all topics studied in the course.

### 9.3 Module-wise quiz question bank

The questions below are aligned to the weekly sessions and are formatted as MSQ-style multiple-choice questions for each module quiz.

#### Module Quiz 1 — Session 1 to Session 2: LLM lifecycle and prompt basics
1. What is the role of a tokenizer in an LLM pipeline?
   - A. To convert text into tokens for model processing
   - B. To store model weights
   - C. To generate images
   - D. To deploy the application
2. Which of the following best describes prompt engineering?
   - A. Writing code for database access
   - B. Designing instructions to guide LLM responses
   - C. Training a neural network from scratch
   - D. Managing cloud servers
3. Which of the following is commonly used while calling an LLM API?
   - A. Temperature
   - B. Compiler version
   - C. RAM capacity
   - D. Network topology
4. What does the context window represent?
   - A. The number of tokens the model can consider at once
   - B. The size of the screen display
   - C. The storage memory of the server
   - D. The number of users connected
5. Which statement best differentiates a prompt from a system instruction?
   - A. A prompt is the user request, while a system instruction defines model behavior
   - B. A prompt is always longer than the instruction
   - C. A system instruction is only used in databases
   - D. A prompt is hidden from the user
6. Why does increasing the temperature affect output variability?
   - A. It makes the model more deterministic
   - B. It increases randomness in the generated output
   - C. It reduces the number of tokens
   - D. It shortens the context window
7. How does prompt clarity influence model response quality?
   - A. It has no impact
   - B. Clear prompts generally improve relevance and accuracy
   - C. It only affects speed
   - D. It always increases cost
8. Which of the following is true about zero-shot and few-shot prompting?
   - A. Zero-shot uses examples; few-shot does not
   - B. Few-shot provides examples; zero-shot does not
   - C. Both require fine-tuning
   - D. Both use only system instructions
9. Which prompt is most suitable for a customer-support chatbot to reduce hallucinations?
   - A. Answer freely without constraints
   - B. Use only verified policy information and say when unsure
   - C. Generate as many ideas as possible
   - D. Ignore the user question
10. Which factor most directly affects cost, accuracy, and latency when choosing a model for the same task?
   - A. The color of the interface
   - B. The model size and deployment setup
   - C. The keyboard layout
   - D. The file extension

#### Module Quiz 2 — Session 3 to Session 4: transformers, context window, and hallucination basics
1. What is the main purpose of attention in a transformer?
   - A. To focus on relevant parts of the input sequence
   - B. To compress the database
   - C. To replace the CPU
   - D. To store logs
2. What is a token in the context of LLMs?
   - A. A unit of text processed by the model
   - B. A password entry
   - C. A hardware component
   - D. A storage format
3. What is hallucination in LLM outputs?
   - A. A safe and verified response
   - B. A confident but incorrect or fabricated response
   - C. A repeated prompt
   - D. A model crash
4. What is the effect of a larger context window?
   - A. It allows the model to consider more previous context
   - B. It always improves accuracy by 100%
   - C. It removes the need for prompts
   - D. It decreases the number of tokens
5. Which is a limitation of a long context window?
   - A. It always lowers cost
   - B. It may increase latency and memory use
   - C. It removes all errors
   - D. It avoids tokenization
6. Why can longer prompts increase latency and cost?
   - A. They require more tokens to process
   - B. They reduce model size
   - C. They avoid attention layers
   - D. They disable API calls
7. How does transformer architecture differ from traditional RNNs?
   - A. Transformers process input in parallel using attention
   - B. RNNs are always more accurate
   - C. Transformers cannot handle text
   - D. RNNs use fewer parameters
8. Which is a practical method to reduce hallucinations in a prompt-based application?
   - A. Ask the model to answer without checking facts
   - B. Provide clear instructions and relevant context
   - C. Increase temperature to maximum
   - D. Remove all examples from the prompt
9. Which statement best compares a shorter and longer prompt for the same task?
   - A. Shorter prompts are always better
   - B. Longer prompts may provide more context but increase cost and latency
   - C. Longer prompts never affect quality
   - D. Shorter prompts require more memory
10. Which prompting strategy improves factuality in a domain-specific assistant?
   - A. Random guessing
   - B. Giving domain-specific context and verification instructions
   - C. Using the longest possible prompt only
   - D. Ignoring the user’s question

#### Module Quiz 3 — Session 5 to Session 6: embeddings, chunking, and retrieval concepts
1. What is an embedding?
   - A. A vector representation of meaning
   - B. A type of hardware token
   - C. A database backup file
   - D. A cloud storage bucket
2. What is chunking in document retrieval?
   - A. Splitting documents into smaller pieces for indexing
   - B. Compressing images
   - C. Encrypting the database
   - D. Deleting irrelevant text
3. What is the purpose of a vector store?
   - A. To store and retrieve embeddings efficiently
   - B. To replace the CPU
   - C. To run operating systems
   - D. To generate user interfaces
4. Which is a common similarity metric used in retrieval?
   - A. Cosine similarity
   - B. File size
   - C. Screen resolution
   - D. CPU frequency
5. What is a retrieval-augmented generation system?
   - A. A system that retrieves relevant information before generating a response
   - B. A system that only uses training data
   - C. A system that disables all prompts
   - D. A system that stores only images
6. Why is chunk size important in RAG pipelines?
   - A. It affects retrieval quality and context usefulness
   - B. It changes the user’s browser
   - C. It removes the need for embeddings
   - D. It eliminates all errors
7. How does retrieval quality affect the final answer of an LLM?
   - A. Better retrieval usually leads to more relevant answers
   - B. It has no effect
   - C. It only affects speed
   - D. It always reduces costs
8. Which statement best compares keyword search and semantic search?
   - A. Keyword search matches exact terms; semantic search matches meaning
   - B. Keyword search is always better than semantic search
   - C. Semantic search does not use embeddings
   - D. Keyword search uses vector stores only
9. Which chunking strategy is best for a large PDF document repository?
   - A. One huge chunk for the entire document
   - B. Chunk by section and preserve metadata
   - C. Randomly split without structure
   - D. Ignore page boundaries
10. How can metadata improve retrieval quality in a RAG system?
   - A. By helping retrieve the correct context more precisely
   - B. By reducing the number of tokens
   - C. By replacing the language model
   - D. By removing the need for indexing

#### Module Quiz 4 — Session 7 to Session 8: evaluation metrics, relevance, faithfulness, latency, and cost
1. What is relevance in LLM evaluation?
   - A. Whether the answer addresses the question properly
   - B. Whether the output is colorful
   - C. Whether the response is long
   - D. Whether the model uses a specific API
2. What is faithfulness in the context of generated answers?
   - A. Whether the response is consistent with the provided source information
   - B. Whether the response is visually appealing
   - C. Whether the response uses many examples
   - D. Whether the response is always short
3. What does latency measure in an LLM application?
   - A. The time taken to generate a response
   - B. The size of the prompt
   - C. The number of users logged in
   - D. The temperature value
4. Which is a cost factor in running LLM APIs?
   - A. Number of tokens processed
   - B. Number of keyboards in the room
   - C. Mouse movement speed
   - D. Screen brightness
5. What is the purpose of automated evaluation?
   - A. To measure outputs consistently and efficiently
   - B. To replace all human review
   - C. To avoid all prompts
   - D. To increase model size
6. Why might a highly fluent answer still be unfaithful?
   - A. It may sound good but not match the source facts
   - B. It always uses fewer tokens
   - C. It never contains errors
   - D. It has lower latency
7. How can latency and cost be balanced in a production LLM system?
   - A. By choosing efficient prompts and model settings
   - B. By ignoring evaluation metrics
   - C. By using the largest possible model always
   - D. By increasing the context window unnecessarily
8. What is the difference between human evaluation and automated evaluation?
   - A. Human evaluation uses people; automated evaluation uses measurable criteria or tools
   - B. Human evaluation is always cheaper
   - C. Automated evaluation never needs prompts
   - D. Human evaluation is always more objective
9. Which is the best evaluation rubric for a customer-service assistant?
   - A. Accuracy, clarity, helpfulness, and safety
   - B. Font size and color scheme
   - C. Number of emojis used
   - D. Length of the response only
10. Which method is suitable to compare two prompt versions using quantitative metrics?
   - A. Use the same test cases and record accuracy, latency, and cost
   - B. Ask only one user to judge both prompts
   - C. Compare the models by color only
   - D. Use random guesses

#### Module Quiz 5 — Session 9 to Session 10: guardrails, privacy, and responsible AI practices
1. What is a guardrail in an LLM application?
   - A. A control that limits unsafe or undesired outputs
   - B. A hardware cable
   - C. A file format
   - D. A deployment script
2. Why is data privacy important in LLM systems?
   - A. To prevent exposure of sensitive information
   - B. To reduce model size
   - C. To increase prompt length
   - D. To remove evaluation metrics
3. What is human-in-the-loop review?
   - A. Human review of outputs before final use
   - B. A method for removing all prompts
   - C. A type of tokenizer
   - D. A cloud database feature
4. Which is a common safety risk in LLM outputs?
   - A. Harmful or misleading content
   - B. Faster response generation
   - C. Lower token usage
   - D. Better formatting
5. Which is one responsible AI principle?
   - A. Fairness
   - B. Randomness
   - C. Compression
   - D. Overfitting
6. Why should LLM applications log prompts and responses carefully?
   - A. To support auditing, debugging, and compliance
   - B. To increase API cost only
   - C. To avoid all evaluation
   - D. To remove context windows
7. How can prompt injection be mitigated in a deployed system?
   - A. By restricting tool access and validating inputs
   - B. By increasing context window size indefinitely
   - C. By removing all examples from prompts
   - D. By disabling logging
8. Which statement best compares safety filtering and content moderation?
   - A. Both are mechanisms to reduce unsafe outputs
   - B. Safety filtering is only for images
   - C. Content moderation is only for APIs
   - D. Both are unrelated to LLMs
9. Which guardrail strategy is best for an enterprise chatbot handling confidential data?
   - A. Use strict access control and redact sensitive data
   - B. Allow unrestricted access to all documents
   - C. Disable all logging to reduce cost
   - D. Encourage random responses
10. How should bias and fairness be monitored in a real-world LLM product?
   - A. Through regular testing across diverse user groups and scenarios
   - B. By ignoring edge cases
   - C. By using only one prompt style
   - D. By disabling human review

#### Final Module Quiz 6 — Session 11 to Session 12: comprehensive quiz on all covered topics
1. What is the difference between prompting and RAG?
   - A. Prompting uses instructions directly, while RAG retrieves external context before answering
   - B. Prompting is only for images
   - C. RAG never uses prompts
   - D. Prompting always requires a database
2. Which metric is commonly used to evaluate LLM quality?
   - A. Accuracy or relevance
   - B. Screen size
   - C. Mouse speed
   - D. Currency rate
3. What is the purpose of a vector store?
   - A. To store and search embeddings efficiently
   - B. To replace the language model
   - C. To create images
   - D. To compile code
4. Why does observability matter in LLMOps?
   - A. It helps monitor failures, cost, and performance
   - B. It removes the need for evaluation
   - C. It replaces guardrails
   - D. It decreases prompt length
5. What is one benefit of versioning prompts or models?
   - A. It enables reproducibility and comparison across deployments
   - B. It eliminates all errors
   - C. It removes the need for evaluation
   - D. It reduces all costs to zero
6. How would you improve a weak RAG pipeline?
   - A. Improve retrieval quality, chunking, and source relevance
   - B. Remove all documents from the knowledge base
   - C. Reduce the model size to zero
   - D. Disable prompts entirely
7. Why is deployment monitoring essential for a production LLM app?
   - A. It helps detect failures, latency spikes, and quality drops
   - B. It avoids the need for logs
   - C. It eliminates hallucinations completely
   - D. It replaces cloud infrastructure
8. Which statement best compares responsible AI practices with basic prompt engineering?
   - A. Responsible AI includes safety, fairness, privacy, and governance beyond prompt design
   - B. Responsible AI ignores evaluation metrics
   - C. Prompt engineering is the same as responsible AI
   - D. Safe prompts are enough for all governance needs
9. Which workflow is most appropriate for a document assistant from prompt design to monitoring?
   - A. Prompt design, retrieval, evaluation, deployment, and monitoring
   - B. Only image generation
   - C. Only database storage
   - D. Only token counting
10. Which trade-off is most important when deploying an LLM in practice?
   - A. Balancing accuracy, latency, cost, and safety
   - B. Choosing the longest possible prompt only
   - C. Ignoring user needs
   - D. Using the most expensive model always

---

## 10. Prerequisites / pre-reading 🟢

Prerequisite courses: Python programming, basic machine learning, data structures, and exposure to APIs and cloud tools.

> 🔵 Note: Students should complete a short diagnostic exercise on Python, APIs, and basic ML concepts before the course begins. Students with weak prerequisite grounding will be supported through early remedial practice.

---

## 11. Lesson plan — tentative transaction dates + session implementation 🟢🔵

| S.No | Planned date | Exec. date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
|---|---|---|---|---|---|---|---|---|---|
| 01 | Week 1 | | Unit 1 — LLM lifecycle and LLMOps overview | Problem-centred + Activation | Present a real-world chatbot case; discuss the full pipeline from prompt to deployment. | 8% | A | CO1 | |
| 02 | Week 1 | | Unit 1 — Transformer foundations and model selection | Demonstration | Demonstrate tokenisation, context windows, and API-based model usage. | 16% | A | CO1 | |
| 03 | Week 2 | | Unit 1 — Prompt design basics and tool setup | Application | Students create and compare a few prompt templates for a standard task. | 24% | A | CO2 | |
| 04 | Week 2 | | Unit 1 — Model choice and workflow design | Application + Integration | Students justify model choice based on latency, cost, and quality. | 32% | Adv | CO1/CO2 | |
| 05 | Week 3 | | Unit 2 — Prompt engineering patterns | Activation | Recap prompt basics; introduce structured prompting and tool calling. | 40% | A | CO2 | |
| 06 | Week 3 | | Unit 2 — Embeddings and vector search | Demonstration | Demonstrate embeddings and retrieval from a small corpus. | 48% | A | CO3 | |
| 07 | Week 4 | | Unit 2 — Chunking and RAG workflow | Application | Students build a simple RAG pipeline for document Q&A. | 56% | A | CO3 | |
| 08 | Week 5 | | Unit 2 — Advanced retrieval strategies | Integration | Students compare retrieval methods and improve the RAG pipeline for a new context. | 64% | Adv | CO3 | |
| 09 | Week 6 | | Unit 3 — Evaluation and testing | Activation | Introduce quality metrics, regression tests, and hallucination checks. | 72% | A | CO5 | |
| 10 | Week 7 | | Unit 3 — Monitoring, logging, and dashboards | Demonstration | Demonstrate tracing, logging, and simple observability dashboards. | 80% | A | CO4 | |
| 11 | Week 8 | | Unit 3 — Deployment and CI/CD | Application | Students deploy a prototype app and version it using GitHub or container workflows. | 88% | A | CO4 | |
| 12 | Week 9 | | Unit 3 — Advanced operations and failure analysis | Integration | Students analyse deployment failures and improve reliability. | 96% | Adv | CO4/CO5 | |
| 13 | Week 10 | | Unit 4 — Guardrails and responsible AI | Activation | Discuss privacy, safety, and human review for LLM applications. | 100% | A | CO5 | |
| 14 | Week 11 | | Unit 4 — Cost and governance controls | Demonstration | Demonstrate cost tracking and prompt/model versioning strategies. | 100% | A | CO5 | |
| 15 | Week 12 | | Unit 4 — Mini-project implementation | Application + Integration | Teams build and refine their LLMOps mini-project. | 100% | Adv | CO6 | |
| 16 | Week 13 | | Capstone review and presentation | Integration | Student teams present their solution and justify deployment decisions. | 100% | Adv | CO6 | |

---

## 12. ICT & digital support 🟢

- OpenAI / Azure OpenAI / Hugging Face playgrounds for model access.
- LangChain or LlamaIndex for prompt orchestration and RAG.
- Vector databases such as Chroma, Pinecone, or Weaviate.
- MLflow / Weights & Biases for experiment tracking.
- Docker, GitHub Actions, and Streamlit/Gradio for simple deployment demos.
- Jupyter notebooks and cloud-based notebooks for practical implementation.

---

## 13. Academic integrity policy 🟢

Students must submit original work for all assessments. Plagiarism, copying of code, or unauthorised use of AI-generated content without acknowledgement will be treated as academic misconduct and may lead to zero marks for the relevant component.

---

## 14. 🔵 Evaluation scheme — dual-level (CORE OF THE TEMPLATE)

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
|---|---|---:|---:|---:|---:|---|---|
| 1 | Test 1 (IA-1) | 20 | 20 | 14 | 6 | Week 5 | CO1–CO3 |
| 2 | Test 2 (IA-2) | 20 | 20 | 14 | 6 | Week 9 | CO4–CO6 |
| 3 | Assignment 1 | 5 | 5 | 3 | 2 | Week 4 | CO1–CO3 |
| 4 | Assignment 2 | 5 | 5 | 3 | 2 | Week 12 | CO4–CO6 |
| 5 | SEE | 50 | 50 | 35 | 15 | End of semester | CO1–CO6 |
| **Total** | | **100** | **100%** | **69** | **31** | | |

### 14.1 🔵 Calibration check

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | Institution-approved CBCS conversion |
| Max % achievable from awareness marks alone | ~69% |
| Grade band that % falls into | Below the 8-CGPA-equivalent threshold |
| Advanced marks needed to cross 8 CGPA | Approximately 31% of the course marks |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | Yes |

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| IA-1 / IA-2 | Short-answer and application questions on prompts, RAG basics, and deployment concepts | One higher-order design/evaluation question per paper |
| SEE | Standard-case questions across all units | At least one advanced item per unit involving design, evaluation, or trade-off analysis |

---

## 15. 🔵 Result analysis — banded to detect the two levels

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared, awareness-solid) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 | | | |
| IA-2 | | | |
| Assignment 1 | | | |
| Assignment 2 | | | |
| SEE | | | |

---

## 16. Learner support tracking 🟢🔵

### 16.1 Students below the floor (per IA) — remediation

| Sl | SRN | Name | IA | Gap identified | Remedial class dates | Re-assessment result |
|---|---|---|---|---|---|---|
| 1 | | | | | | |
| 2 | | | | | | |

### 16.2 Students reaching for the ceiling — enrichment

| Sl | SRN | Name | Advanced task assigned | Outcome |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |

| Category | No. of students | Action taken |
|---|---:|---|
| Below floor (slow learners) | | |
| At ceiling (fast learners) | | |

---

## 17. 🔵 Track-advice signal (links course → SIG track choice)

| Field | Entry |
|---|---|
| Is this a prerequisite for a SIG track? | Yes — recommended for AI/ML, Data Engineering, and Product Engineering-oriented SIGs |
| % of students at advanced level (> 75% / 8+ CGPA) | |
| Domains where advanced performance clustered | RAG systems, evaluation pipelines, deployment automation, observability |
| Recommended note to academic mentors | Students who perform strongly in Units 2–4 are suitable candidates for AI product engineering, applied AI, and data-centric innovation tracks. |

---

## 18. CO attainment 🟢

**Set target:** 60

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level (A/Adv) 🔵 |
|---|---|---|---|---|---|---|---|
| CO1 | | | | | | | A |
| CO2 | | | | | | | Both |
| CO3 | | | | | | | Adv |
| CO4 | | | | | | | Adv |
| CO5 | | | | | | | Adv |
| CO6 | | | | | | | Adv |

---

## 19. CO–PO/PSO mapping & overall attainment 🟢

**Strength: 1 = Low, 2 = Medium, 3 = High.**

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PSO1 | PSO2 | PSO3 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | 3 | 2 | | | 2 | | | | | | 3 | | |
| CO2 | 3 | 3 | 2 | | 2 | | | | | | 3 | 2 | |
| CO3 | 3 | 3 | 3 | 2 | 3 | | | | | | 3 | 3 | |
| CO4 | 3 | 3 | 3 | 3 | 3 | | | | | 2 | 3 | 3 | |
| CO5 | 3 | 3 | | 3 | | | 2 | 3 | | | 3 | | 2 |
| CO6 | 3 | 3 | 3 | 3 | 3 | | | 3 | | 2 | 3 | 3 | 3 |

**Overall attainment** (Direct 80% + Indirect/Feedback 20%):

| | Internal | External | Grand total (80%+20%) |
|---|---|---|---|
| CO attainment | | | |
| PO attainment | | | |
| PSO attainment | | | |

**Minimum level for PO attainment:** 50%–60%

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

- Did the awareness floor genuinely protect placement-readiness for the weakest students? To be completed after first offering.
- Was the advanced ceiling reached by roughly the expected share, or did it collapse / go unassessed? To be completed after assessment review.
- One change to the awareness/advanced split for next offering: To be completed after feedback analysis.

---

**Signatures**

Course Faculty (digital signature) — ____________________   HoD / Director (digital signature) — ____________________

---

## 22. 🔵 Implementation strategy — Merrill's First Principles

The lesson plan is structured around Merrill’s First Principles of Instruction so that students move from a real-world problem to guided practice, demonstration, application, and finally integration. In this course, the advanced ceiling is taught through open-ended design and deployment tasks rather than through assessment alone.

### 22.1 Phase-coverage check 🔵

| Check | Entry |
|---|---|
| All five Merrill phases used at least once per unit | Yes |
| §11 sessions using Activation = lecture + demonstration | Sessions 01, 05, 09, 13 |
| §11 sessions delivering Advanced-level activities | Sessions 04, 08, 12, 15, 16 |
| ✅ Ceiling taught (≥1 Adv activity per unit, not only assessed) | Yes |
