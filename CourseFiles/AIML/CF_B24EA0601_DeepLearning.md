# Course File — Dual-Level (Awareness + Advanced) Design

### B24EA0601 — Deep Learning | AIML | Semester 6 | AY 2026–27

Generated from Deep\_Learning.pdf using Course\_File\_Template\_DualLevel.md.  
Sections where the source document provided data are filled. Placeholders (‹…›) mark fields faculty must complete before submission.

## 0\. Course identification 🟢

| Field | Entry |
| --- | --- |
| Faculty name | Dr. Sindhu P Menon |
| REVA ID | REVA02778 |
| Email | Sindhu.menon@reva.edu.in |
| Programme | B.Tech — AIML |
| Course code | B24EA0601 |
| Course title | Deep Learning |
| Semester & section | VI — A |
| Academic year | 2026–27 |
| Course duration (sessions) | Theory: 13 sessions · Tutorial: 26 sessions · Practical: 26 sessions |
| Office / consultation hours | Thursday 2.20PM to 4.30 PM and Working Saturdays |
| Dual-Level Designation | A+Adv (Awareness + Advanced) |
| Category | HC(Hard Core) |

**L-T-P-C:** 1-1-1 → 5 contact hours/week · **5 Credits**  
**Assessment:** CIE 50% · SEE 50%

The course follows the approved Scheme of Instruction. Theory, tutorial and practical sessions are scheduled through integrated activity-based delivery across the semester. Session counts represent instructional transactions and not separate weekly credit allocations.

**School vision:** To emerge as a globally isualizat department of computer science in education, research, and innovation that advances technology for sustainable development, serves humanity, and nurtures ethically responsible leaders for the digital future.

**School mission:** To provide learner-centric education in computer science and engineering, leveraging cutting-edge technologies to empower students with strong theoretical foundations, practical skills, and  
interdisciplinary knowledge; to foster innovation, research, and entrepreneurship in emerging areas of computer science while promoting sustainability, inclusivity, and universal values; to prepare graduates  
for lifelong learning and impactful careers; to build a culture of collaboration through industry—academia partnerships; and to serve society through technology solutions that enhance human well-being.

## Course description 🟢

This course provides students with a structured foundation in Deep Learning, progressing from neural network fundamentals through convolutional, recurrent, and transformer-based architectures to generative models and explainable AI. It adopts an activity-based, integrated theory-tutorial-lab approach in which students implement models using TensorFlow/Keras and PyTorch on real-world image, text, and tabular datasets. By course end, students can independently design, train, evaluate, and interpret end-to-end deep learning solutions while applying responsible AI practices.

## 2\. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
| --- | --- | --- |
| 1 | Neural Network Fundamentals and Deep Feedforward Networks — Artificial Neurons, Perceptron, MLP, Activation Functions (Sigmoid, Tanh, ReLU, Leaky ReLU), Loss Functions, Forward Propagation, Backpropagation, Gradient Descent, Optimisation Algorithms (SGD, Momentum, Adam), Weight Initialisation, Batch Normalisation, Overfitting and Regularisation, Dropout. | 25 Marks |
| 2 | Convolutional Neural Networks and Computer Vision — Convolution Operation, Feature Maps, Padding, Stride, Pooling Layers, CNN Architecture, LeNet, AlexNet, VGGNet, ResNet, DenseNet, Transfer Learning, Fine-Tuning, Image Augmentation. | 25 Marks |
| 3 | Sequence Models and Transformers — RNN, Vanishing Gradient Problem, LSTM, GRU, Bidirectional RNN, Sequence-to-Sequence Learning, Attention Mechanism, Transformer Architecture, Encoder-Decoder Models, BERT Fundamentals, NLP Applications. | 25 Marks |
| 4 | Generative Deep Learning and Explainable AI — Autoencoders (Sparse, Denoising, Variational), GANs, DCGAN, Model Explainability, Grad-CAM, XAI, Ethical AI, Bias and Fairness. | 25 Marks |

## 3\. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (the floor) | Advanced level — required to exceed 8 CGPA (the ceiling) |
| --- | --- | --- |
| 1 | Define and explain artificial neurons, MLP architecture, activation functions, and the roles of forward propagation and backpropagation; apply standard gradient descent to a given network by hand; identify overfitting from training curves and state remedies (dropout, isualization). | Analyse the effect of different optimisers (SGD vs Momentum vs Adam) on convergence for a novel dataset; derive backpropagation weight-update equations; design and justify a isualization strategy for an unseen classification problem; evaluate batch isualization trade-offs. |
| 2 | Explain convolution, pooling, stride, and padding; compute feature-map dimensions and parameter counts for standard CNN layers; describe the architecture differences among LeNet, AlexNet, VGGNet, and ResNet; apply a pretrained model for transfer learning on a given task. | Design and justify a CNN architecture or fine-tuning strategy for a novel computer-vision problem (e.g., medical image diagnosis); analyse residual learning and its effect on gradient flow; evaluate augmentation strategies and their impact on isualization; compare architectures against each other and against the task requirements. |
| 3 | Explain RNN, LSTM, and GRU architectures and their gate mechanisms; describe the vanishing-gradient problem and why LSTM/GRU address it; apply a sequence model to a standard NLP task; outline the Transformer encoder-decoder and the role of attention. | Implement and compare LSTM, GRU, and Transformer models for a novel sequence task; analyse attention scores and interpret their meaning; design an end-to-end chatbot or classification architecture, justifying model and hyperparameter choices; evaluate BERT fine-tuning trade-offs. |
| 4 | Describe autoencoder variants (standard, sparse, denoising, VAE) and their latent-space representations; explain GAN generator-discriminator dynamics and DCGAN improvements; state what Grad-CAM isualizat and why XAI matters; identify examples of bias and fairness issues in deep learning. | Design and implement a VAE or DCGAN for a novel generation task; evaluate Grad-CAM outputs to diagnose model behaviour and justify predictions; critically analyse fairness and bias in a real system; propose and defend a responsible AI framework for a given application scenario. |

**Bloom anchor:**

| Level | Bloom verbs | Typical question stem |
| --- | --- | --- |
| Awareness (floor) | Remember, Understand, Apply | “Define…”, “Explain…”, “Apply X to this standard case…”, “Calculate the feature-map size given…” |
| Advanced (ceiling) | Analyse, Evaluate, Create | “Compare and justify the choice of…”, “Design a solution for…”, “Evaluate the trade-off between…”, “Propose and defend…” |

## 4\. Course objectives 🟢

*   Understand Deep Learning Fundamentals: develop a strong foundation in neural networks, representation learning, activation functions, isualizatio methods, and the deep learning workflow.
*   Develop Neural Network Models: acquire the ability to design, train, and evaluate feedforward neural networks using appropriate loss functions, isualizatio algorithms, and isualization techniques.
*   Apply Deep Learning to Computer Vision: gain proficiency in CNNs and transfer learning for image classification and visual recognition tasks.
*   Apply Sequence Learning Techniques: learn RNNs, LSTM, GRU, attention mechanisms, and transformer architectures for sequence and language-based applications.
*   Explore Generative and Foundation Models: understand autoencoders, GANs, LLMs, and modern generative AI concepts.
*   Implement Deep Learning Solutions: build hands-on expertise implementing deep learning models using TensorFlow/Keras and PyTorch.
*   Evaluate and Interpret Deep Models: learn model evaluation, explainability techniques, isualization methods, and performance improvement strategies.
*   Practice Responsible and Ethical AI: understand fairness, transparency, explainability, and ethical considerations in deep learning systems.

## 5\. Course outcomes (Cos) and PO/PSO mapping 🟢🔵

| CO# | Course outcome | Level (Awareness / Advanced / Both) 🔵 | Pos | PSOs |
| --- | --- | --- | --- | --- |
| CO1 | Explain neural network architectures, representation learning concepts, activation functions, isualizatio methods, and isualization techniques used in deep learning systems. | Awareness | PO1(3), PO2(2) | PSO1 |
| CO2 | Develop and train feedforward neural networks using suitable architectures, loss functions, isualizatio algorithms, and isualization strategies. | Both | PO1(3), PO2(3), PO3(2), PO4(2), PO5(3) | PSO1, PSO2 |
| CO3 | Design and evaluate convolutional neural network models and transfer learning solutions for computer vision applications. | Advanced | PO1(3), PO2(3), PO3(3), PO4(2), PO5(3) | PSO1, PSO2 |
| CO4 | Build and analyse recurrent neural network, LSTM, GRU, attention-based, and transformer models for sequence learning tasks. | Advanced | PO1(3), PO2(3), PO3(3), PO4(3), PO5(3) | PSO1, PSO2 |
| CO5 | Apply generative deep learning techniques, explainable AI methods, and foundation model concepts to solve advanced AI problems. | Advanced | PO1(3), PO2(3), PO3(2), PO4(2), PO5(3), PO9(3) | PSO1, PSO3 |
| CO6 | Implement end-to-end deep learning solutions using modern frameworks and evaluate their effectiveness for real-world applications while adhering to ethical and responsible AI practices. | Advanced | PO1(3), PO2(3), PO3(3), PO4(3), PO5(3), PO7(2), PO8(3), PO9(2), PO10(2), PO11(3) | PSO1, PSO3 |

🔵 **Rationale for level tags:** CO1 covers foundational recall/explanation — it is the placement-readiness floor. CO2 spans standard application (awareness) through isualiza-selection and training strategy (advanced). CO3–CO6 all require design, evaluation, or novel-problem transfer — they constitute the ceiling that a student must reach to exceed 8 CGPA.

🔵 Placement and Competitive Examination Alignment (Awareness Floor)

The awareness-level outcomes (CO1 and CO2) establish the minimum competency expected from all learners and directly support placement readiness and higher-study preparation.

| Awareness CO | Competency Domain | Relevance |
| --- | --- | --- |
| CO1 | Neural Network Fundamentals | Frequently assessed in AI/ML interviews, technical discussions, coding assessments, and postgraduate entrance examinations involving Machine Learning and Artificial Intelligence. |
| CO1 | Activation Functions, Loss Functions, Backpropagation | Supports conceptual questions in placement interviews, GATE AI/DS preparation, and AI certification examinations. |
| CO2 | Model Training and Optimisation | Develops practical understanding of gradient descent, optimisers, and performance improvement techniques expected in AI/ML internships and entry-level roles. |
| CO2 | Neural Network Implementation | Builds competency in implementing and evaluating basic deep learning models using industry-standard frameworks such as TensorFlow and PyTorch. |

Awareness-floor attainment indicates that a learner possesses the foundational knowledge and implementation skills required for entry-level AI/ML technical interviews, internships, certification examinations, and advanced coursework in Deep Learning.

## 6\. Pedagogy 🟢

*   **Direct instruction** for foundational concepts (neural network mechanics, architecture definitions).
*   **Demonstration-led learning** — live coding sessions in TensorFlow/Keras and PyTorch for every practical unit.
*   **Problem-based / case-study learning** — every unit has at least one industry case study (student placement prediction, medical image diagnosis, e-commerce sentiment, manufacturing defect detection).
*   **Activity-based tutorials** — structured numerical exercises reinforce theory before lab implementation.
*   **Mini-project / capstone** — Level 2 lab experiments (Programs 9–16) simulate real client briefs and require end-to-end solution design.
*   **Self-directed learning** —a published self-learning component (Vision Transformers, LLMs, Prompt Engineering, Federated Learning, Edge AI, etc.) is assessed through seminars or written reports and evaluated as part of Assignment-2.

## 7\. Textbooks, references, e-resources 🟢

**Textbooks:**

1.  Simon Haykin, _Neural Networks and Learning Machines_, 3rd Edition, Pearson, 2016.
2.  Adam Gibson and Josh Patterson, _Deep Learning: A Practitioner’s Approach_, O’Reilly, 1st Edition, 2017.
3.  Ian Goodfellow, Yoshua Bengio, and Aaron Courville, _Deep Learning_, MIT Press.

**Reference books:**

1.  François Chollet, _Deep Learning with Python_, Manning Publications.
2.  Charu Aggarwal, _Neural Networks and Deep Learning_, Springer.
3.  Aurélien Géron, _Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow_, 3rd Edition, O’Reilly.

**Journals / Magazines:**

1.  IEEE Transactions on Neural Networks and Learning Systems (TNNLS) — [https://cis](https://cis).ieee.org/publications/t-neural-networks-and-learning-systems
2.  IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI) — [https://www](https://www).computer.org/csdl/journal/tp
3.  International Journal of Computer Vision (IJCV) — [https://www](https://www).springer.com/journal/11263

**NPTEL / MOOCs:**

1.  NPTEL: Deep Learning (Prof. Sudarshan Iyengar, IIT Ropar) — [https://nptel](https://nptel).ac.in/courses/106106184
2.  Coursera: Neural Networks and Deep Learning (Andrew Ng) — [https://www](https://www).coursera.org/learn/neural-networks-deep-learning
3.  Coursera: Deep Learning Specialisation (Andrew Ng) — [https://www](https://www).coursera.org/specializations/deep-learning

## 8\. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk of not clearing it:**

*   Remedial classes triggered after IA-1 for students below 40% — focused on forward/backpropagation numerics and standard CNN/RNN application.
*   Curated worked examples: solved tutorials (perceptron outputs, LSTM gate calculations, feature-map dimensions) shared on the LMS.
*   Peer mentoring pairs (advanced-level student buddies) for labs Programs 1–8.
*   Scaffolded assignments: Part A questions (define, explain, calculate) before open-ended design tasks.

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**

*   Research paper review: one paper from TNNLS/TPAMI per unit; students submit a one-page critical summary.
*   Advanced lab experiments (Programs 9–16): Level 2 experiments require full design justification, architecture comparison, and explainability reporting — not just running code.
*   Self-learning component seminars: students present one topic from the self-learning list (ViT, LLMs, Federated Learning, etc.) to the class.
*   Stretch tutorial problems: open-ended isualiza-analysis and architecture-design problems beyond the textbook scope.
*   Optional Kaggle competition participation linked to CV or NLP units.

## 9\. Assignments 🟢

| Assignment | Units covered | Marks | Window |
| --- | --- | --- | --- |
| Assignment 1 | Units 1 & 2 | 5 | Before IA-2 |
| Assignment 2 | Units 3 & 4 | 5 | Before SEE |

🔵 Each assignment includes both awareness questions (Part A: define, explain, calculate) and at least one advanced question (Part B: design, compare, justify) so the split aligns with §14.

## 10\. Prerequisites / pre-reading 🟢

**Prerequisite course:** B24EA0501 – Artificial Intelligence and Machine Learning (Semester 5) — Students must have working knowledge of supervised/unsupervised learning, gradient descent, and Python (NumPy, Pandas, Scikit-learn).

🔵 Week 0 / Bridge Activity:  
  
Before commencement of Unit 1, students shall complete a self-assessment quiz covering Python programming, NumPy, Pandas, Scikit-learn, matrix operations, and gradient descent fundamentals.  
  
Students scoring below 50% in the diagnostic quiz shall be advised to complete LMS-based remedial modules and guided practice notebooks before Week 2.

🔵 Semester 5 Machine Learning grade is the primary mentor signal for track-readiness. Students with ML grade < B should receive floor-targeted support from Week 1. Students with ML grade A/S are candidates for the AI/ML-Data Engineering SIG ceiling track.

## 11\. Lesson plan — tentative transaction dates + session implementation 🟢🔵

Legend: **A** = Awareness level · **Adv** = Advanced level · Merrill phases: PC = Problem-centred, Act = Activation, Demo = Demonstration, App = Application, Int = Integration.

### Unit 1 — Neural Network Fundamentals and Deep Feedforward Networks (Theory: ~4 sessions · Tutorial: 8 sessions)

| S.No | Planned date | Exec. Date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level 🔵 | CO | Remarks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T01 | <…> | <…> | Artificial Neurons, Perceptron | PC + Act | Present student placement T02prediction problem; explain perceptron model and decision boundary |  | Present student placement T02prediction problem; explain perceptron model and decision boundary |  | Present student placement T02prediction problem; explain perceptron model and decision boundary | 8 | A | CO1 |  |
|  |
| Present student placement T02prediction problem; explain perceptron model and decision boundary |  | Present student placement T02prediction problem; explain perceptron model and decision boundary |
|  |
| Present student placement T02prediction problem; explain perceptron model and decision boundary |
| T02 | <…> | <…> | MLP Architecture, Activation Functions | Demo | Demonstrate MLP architecture and compare Sigmoid, Tanh and ReLU. | 16 | A | CO1 |  |
| T03 | <…> | <…> | Loss Functions, Forward Propagation | Demo | Work through forward-pass calculations and loss computation. | 23 | A | CO1 |  |
| T04 | <…> | <…> | Backpropagation, Optimizers, Regularization | App + Int | Students perform weight updates and compare SGD, Momentum and Adam | 31 | Adv | CO2 |  |
| TU1.1 | <…> | <…> | Perceptron Output Calculation | App | Compute perceptron outputs. | — | A | CO1 |  |
| TU1.2 | <…> | <…> | Activation Function Analysis |  | Activation Function Analysis | App | Compare activation functions numerically. | — | A | CO1 |  |
|  |
| Activation Function Analysis |
| TU1.3 | <…> | <…> | Forward Propagation | App | Solve forward-pass examples. | — | A | CO1 |  |
| TU1.4 | <…> | <…> | Backpropagation | App | Weight-update calculations. | — | A | CO1 |  |
| TU1.5 | <…> | <…> | Gradient Descent | App | Numerical optimization exercises. | — | A | CO2 |  |
| TU1.6 | <…> | <…> | Optimizer Comparison | App | Compare SGD, Momentum, Adam. | — | A | CO2 |  |
| TU1.7 | <…> | <…> | Batch Normalization & Dropout | App | Regularization exercises | — | A | CO2 |  |
| TU1.8 | <…> | <…> | Overfitting Case Study | Int | Diagnose overfitting and justify remedies. | — | Adv | CO2 |  |
| P1.1 | <…> | <…> | Python & NumPy Refresher | Demo + App | Environment setup and matrix operations. | — | A | CO1 |  |
| P1.2 | <…> | <…> | Perceptron Classification | App | Implement perceptron classifier | — | A | CO1 |  |
| P1.3 | <…> | <…> | Activation Function Analysis | App | Visualize activation functions. | — | A | CO1 |  |
| P1.4 | <…> | <…> | MLP Classification | App | Train MLP model. | — | A | CO2 |  |
| P1.5 | <…> | <…> | Optimizer Comparison | App | Compare SGD, Momentum and Adam | — | A | CO2 |  |
| P1.6 | <…> | <…> | Regularization and Dropout | App | Reduce overfitting. | — | A | CO2 |  |
| P1.7 | <…> | <…> | Performance Analysis | Int | Analyse and improve model performance. | — | Adv | CO2 |  |

### Unit 2 — Convolutional Neural Networks and Computer Vision (Theory: ~3 sessions · Tutorial: 8 sessions)

| S.No | Planned date | Exec. Date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level 🔵 | CO | Remarks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T05 | <…> | <…> | Convolution Operation, Feature Maps, Padding, Stride, Pooling Layers | PC + Act | Present real-world problem of plant disease detection using images. Demonstrate convolution operation manually and explain feature extraction through kernels, padding, stride and pooling. | 38 | A | CO1 |  |
| T06 | <…> | <…> | CNN Architectures: LeNet, AlexNet, VGGNet | Demo | Compare evolution of CNN architectures. Demonstrate implementation of LeNet using TensorFlow/Keras and analyse parameter growth across architectures. | 46 | A | CO1 |  |
| T07 | <…> | <…> | ResNet, DenseNet, Transfer Learning, Fine-Tuning, Image Augmentation | App + Int | Students analyse residual learning, compare CNN architectures, perform transfer learning and justify model selection for a novel computer vision application. | 54 | A | CO1 |  |
| TU2.1 | <…> | <…> | Convolution Operations | App | Manual convolution calculations using different kernel sizes and strides. | — | A | CO3 |  |
| TU2.2 | <…> | <…> | Feature Map Dimensions | App | Compute output dimensions for various CNN configuration | — | A | CO3 |  |
| TU2.3 | <…> | <…> | Pooling Layer Operations | App | Perform max-pooling and average-pooling calculations. | — | A | CO3 |  |
| TU2.4 | <…> | <…> | CNN Parameter Calculations | App | Calculate trainable parameters and computational complexity of CNN architectures. | — | A | CO3 |  |
| TU2.5 | <…> | <…> | Architecture Comparison | App | Compare LeNet, AlexNet, VGGNet, ResNet and DenseNet for different applications. | — | A | CO3 |  |
| TU2.6 | <…> | <…> | Transfer Learning Case Study | Int | Select a suitable CNN architecture for medical image diagnosis and justify transfer-learning strategy. | — | Adv | CO3 |  |
| P2.1 | <…> | <…> | CNN for Image Classification | Demo + App | Implement a CNN model for handwritten digit recognition using the MNIST dataset. | — | A | CO3 |  |
| P2.2 | <…> | <…> | CNN Performance Tuning | App | Experiment with filters, kernel sizes and learning rates to improve accuracy. | — | A | CO3 |  |
| P2.3 | <…> | <…> | Image Augmentation using Keras |  | Image Augmentation using Keras | App | Apply augmentation techniques and analyse their impact on model generalization. | — | A | CO3 |  |
|  |
| Image Augmentation using Keras |
| P2.4 | <…> | <…> | Transfer Learning with MobileNet/ResNet | App | Fine-tune a pretrained CNN model for custom image classification. | — | A | CO3 |  |
| P2.5 | <…> | <…> | CNN-Based Medical Image Diagnosis | App | Develop a CNN solution for chest X-ray classification and evaluate performance metrics. | — | A | CO3, CO5 |  |
| P2.6 | <…> | <…> | Smart Manufacturing Defect Detection | App | Design and evaluate a CNN-based defect detection system and justify architecture selection. | — | A | CO3,CO5 |  |

### Unit 3 — Unit 3 — Sequence Models and Transformers

### (Theory: 3 Sessions · Tutorial: 6 Sessions · Practical: 6 Sessions)

| S.No | Planned date | Exec. Date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level 🔵 | CO | Remarks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T08 | <…> | <…> | RNN, Vanishing Gradient Problem, LSTM, GRU, Bidirectional RNN | PC + Act | Present e-commerce sentiment analysis problem. Explain sequence modelling using RNNs, demonstrate vanishing gradient issues, and discuss how LSTM and GRU architectures address long-term dependency challenges. | 62 | A | CO1 |  |
| T09 | <…> | <…> | Sequence-to-Sequence Learning, Attention Mechanism, Transformer Architecture | Demo | Demonstrate encoder-decoder architecture and attention mechanism. Illustrate attention score computation and explain Transformer components including multi-head attention and positional encoding. | 69 | A | CO1 |  |
| T010 | <…> | <…> | BERT Fundamentals and NLP Applications | App + Int | Students analyse Transformer-based models, evaluate BERT fine-tuning strategies, and justify architecture selection for novel NLP and sequence-learning applications. | 77 | A | CO1 |  |
| TU3.1 | <…> | <…> | RNN State Computation | App | Compute hidden states and outputs for simple recurrent neural networks. | — | A | CO3 |  |
| TU3.2 | <…> | <…> | LSTM Gate Calculations |  | LSTM Gate Calculations | App | Calculate forget, input and output gate values for given sequences. | — | A | CO3 |  |
|  |
| LSTM Gate Calculations |
| TU3.3 | <…> | <…> | GRU Computations | App | Perform numerical exercises involving GRU update and reset gates. | — | A | CO3 |  |
| TU3.4 | <…> | <…> | Sequence-to-Sequence Modelling | App | Analyse encoder-decoder workflows for translation and text generation tasks. | — | A | CO3 |  |
| TU3.5 | <…> | <…> | Attention Score Computation | App | Calculate attention weights and context vectors for sample sequences. | — | A | CO3 |  |
| TU3.6 | <…> | <…> | Transformer-Based Chatbot Design Case Study | Int | Compare LSTM and Transformer architectures and justify model selection for a conversational AI application. | — | Adv | CO3 |  |
| P3.1 | <…> | <…> | LSTM Sentiment Analysis | Demo + App | Implement an LSTM model for e-commerce review sentiment classification. | — | A | CO4 |  |
| P3.2 | <…> | <…> | Time-Series Forecasting using LSTM | App | Develop and evaluate an LSTM-based forecasting model on sequential data. | — | A | CO4 |  |
| P3.3 | <…> | <…> | GRU-Based Sequence Modelling | App | Implement and compare GRU performance with LSTM on a sequence-learning task. |  | Implement and compare GRU performance with LSTM on a sequence-learning task. | — | A | CO4 |  |
|  |
| Implement and compare GRU performance with LSTM on a sequence-learning task. |
| P3.4 | <…> | <…> | Sequence-to-Sequence Learning with Attention | App | Build an encoder-decoder model with attention mechanism for text processing applications. | — | A | CO4 |  |
| P3.5 | <…> | <…> | Transformer Text Classification | App | Implement a Transformer-based classifier and evaluate model performance on text datasets. |  | Implement a Transformer-based classifier and evaluate model performance on text datasets. | — | Adv | CO4, CO5 |  |
|  |
| Implement a Transformer-based classifier and evaluate model performance on text datasets. |
| P3.6 | <…> | <…> | Resume Screening using BERT | App | Fine-tune a BERT model for intelligent recruitment classification and analyse prediction bias and fairness considerations. |  | Fine-tune a BERT model for intelligent recruitment classification and analyse prediction bias and fairness considerations. | — | Adv | CO4, CO6 |  |
|  |
| Fine-tune a BERT model for intelligent recruitment classification and analyse prediction bias and fairness considerations. |

### Unit 4 — Generative Deep Learning and Explainable AI (Theory: ~3 sessions · Tutorial: 8 sessions)

| S.No | Planned date | Exec. Date | Unit / topic | Merrill phase 🔵 | Activity (what the faculty runs) 🔵 | % compl. | Level 🔵 | CO | Remarks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T011 | <…> | <…> | Autoencoders (Sparse, Denoising, Variational Autoencoders) |  | Autoencoders (Sparse, Denoising, Variational Autoencoders) | PC + Act | Present AI-assisted manufacturing defect detection problem. Explain encoder-decoder architecture, latent space representation, sparse and denoising autoencoders, and introduce Variational Autoencoders (VAE). | 85 | A | CO5 |  |
|  |
| Autoencoders (Sparse, Denoising, Variational Autoencoders) |
| T012 | <…> | <…> | GANs, DCGANs and Generative Deep Learning | Demo | Demonstrate generator-discriminator training process, explain GAN loss functions, DCGAN architecture, mode collapse issues, and applications of generative models. | 92 | A | CO5 |  |
| T013 | <…> | <…> | Explainable AI, Grad-CAM, Ethical AI, Bias and Fairness | App + Int | Students analyse Grad-CAM visualizations, evaluate explainability techniques, identify bias and fairness issues in AI systems, and justify responsible AI practices for real-world applications. | 100 | A | CO5, CO6 |  |
| TU4.1 | <…> | <…> | Autoencoder Architecture Analysis |  | Autoencoder Architecture Analysis | App | Analyse encoder-decoder structures and reconstruction workflows. | — | A | CO5 |  |
|  |
| Autoencoder Architecture Analysis |
| TU4.2 | <…> | <…> | Latent Space Interpretation | App | Interpret latent representations generated by autoencoders and VAEs. | — | A | CO5 |  |
| TU4.3 | <…> | <…> | GAN Loss Functions and Training Dynamics | App | Analyse generator-discriminator loss behaviour and convergence challenges. | — | A | CO5 |  |
| TU4.4 | <…> | <…> | DCGAN Architecture Analysis | App | Compare GAN and DCGAN architectures for image generation tasks. | — | A | CO5 |  |
| TU4.5 | <…> | <…> | Grad-CAM and Explainability Exercises | App | Interpret saliency maps and Grad-CAM visualizations for model explanations. | — | A | CO5, CO6 |  |
| TU4.6 | <…> | <…> | Responsible AI Case Study | Int | Analyse bias, fairness and transparency issues in AI applications and propose mitigation strategies. | — | Adv | CO5, CO6 |  | CO5, CO6 |  |
|  |
| CO5, CO6 |
| P4.1 | <…> | <…> | Autoencoders (Sparse, Denoising, Variational Autoencoders) | Demo + App | Implement and evaluate an autoencoder for dimensionality reduction and reconstruction. | — | A | CO5 |  |
| P4.2 | <…> | <…> | GANs, DCGANs and Generative Deep Learning | App | Train a denoising autoencoder to reconstruct noisy images. | — | A | CO5 |  |
| P4.3 | <…> | <…> | Explainable AI, Grad-CAM, Ethical AI, Bias and Fairness | App | Implement VAE and visualise latent-space representations. | — | A | CO5 |  |
| P4.4 | <…> | <…> |  | App | Develop and train a GAN for synthetic image generation. | — | A | CO5 |  |
| P4.5 | <…> | <…> |  | App | Generate realistic image samples using a DCGAN architecture. | — | Adv | CO4, CO5 |  |
| P4.6 | <…> | <…> | Explainable AI using Grad-CAM | App | Generate and analyse Grad-CAM heatmaps for CNN predictions. | Generate and analyse Grad-CAM heatmaps for CNN predictions. |  | — | Adv | CO5, CO6 |  |
| Generate and analyse Grad-CAM heatmaps for CNN predictions. |
|  |
| P4.6 | <…> | <…> | Deep Learning Capstone Project | Int | Design, implement and evaluate a complete deep learning solution incorporating explainability and responsible AI considerations. | Design, implement and evaluate a complete deep learning solution incorporating explainability and responsible AI considerations. |  | — | Adv | CO5, CO6 |  |
| Design, implement and evaluate a complete deep learning solution incorporating explainability and responsible AI considerations. |
|  |

## 12\. ICT & digital support 🟢

| Unit | Resources |
| --- | --- |
| 1 | 3Blue1Brown “Neural Networks” YouTube series; TensorFlow Playground (https://playground.tensorflow.org); Andrew Ng Coursera Week 1–4 videos |
| 2 | CS231n (Stanford) CNN lecture slides and notes; Keras Applications documentation; fast.ai Practical Deep Learning Part 1 |
| 3 | Illustrated Transformer (Jay Alammar blog); HuggingFace tutorials; Andrew Ng Coursera Sequence Models course |
| 4 | GAN Lab (https://poloclub.github.io/ganlab/); Distill.pub articles on feature isualization and Grad-CAM; AI Fairness 360 toolkit (IBM) |
| All | NPTEL Deep Learning (Prof. Sudarshan Iyengar, IIT Ropar); Google Colab for all lab sessions |

All ICT resources, URLs, and digital learning materials shall be verified before commencement of each course offering to ensure accessibility and currency.

**Review-cycle note:** Framework versions, software tools, datasets, and ICT resources used in this course shall be reviewed and verified before each offering to ensure technical currency and compatibility.

## 13\. Academic integrity policy 🟢

All submitted work — assignments, lab reports, tutorial sheets, and projects — must be the student's own. Copying, plagiarism, or unauthorised collaboration in any evaluation component will result in zero marks for that component, and repeated violations will be escalated per REVA University's academic integrity policy. Use of AI-assisted code generation tools must be declared; undeclared use is treated as plagiarism.

## 14\. 🔵 Evaluation scheme — dual-level (CORE OF THE TEMPLATE)

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Test 1 (IA-1) | 20 | 20 | ≈14 | ≈6 | ‹…› | CO1–CO2 |
|  | Test 2 (IA-2) | 20 | 20 | ≈14 | ≈6 | ‹…› | CO3–CO4 |
|  | Assignment 1 | 5 | 5 | 3 | 2 | ‹before IA-2› | CO1–CO2 |
|  | Assignment 2 | 5 | 5 | 3 | 2 | ‹before SEE› | CO3–CO6 |
| 2 | SEE | 50 | 50 | ≈35 | ≈15 | ‹…› | CO1–CO6 |
| Total |  | 100 | 100% | ≈69 | ≈31 |  |  |

**Split rationale:** ~70% awareness / ~30% advanced. A student scoring all awareness marks and none of the advanced marks scores ≈69/100, which maps to below 8 CGPA — satisfying the calibration rule.

Awareness–Advanced ratio adopted as per B.Tech AIML Dual-Level Curriculum Guidelines. Assignment-2 includes evaluation of the self-learning component through seminar presentation and/or written report.

### 14.1 CGPA calibration check 🔵

| Check | Entry |
| --- | --- |
| Max marks scoring awareness only | ≈69 / 100 |
| Grade band that % falls into | B+ / 7.x CGPA band — below 8 CGPA ✅ |
| Advanced marks needed to cross 8 CGPA | ≈1–11 of the 31 advanced marks, depending on exact CGPA boundary |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | Yes |

The calibration holds with the 69/31 split. If grading boundaries shift, re-verify before the course runs.

### Reference Exemplar for Advanced-Level Calibration:

### Advanced-level expectations in this course have been aligned with the AIML programme's outcome-based curriculum framework, prerequisite knowledge requirements, and programme outcome expectations. The assessment structure has been calibrated to provide approximately 69% awareness-level opportunities and 31% advanced-level opportunities in alignment with the dual-level course design philosophy adopted for this course.

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) | Marks Split |
| --- | --- | --- | --- |
| IA-1 (CO1–CO2) | Part A: define activation functions, explain backpropagation, calculate forward-pass output for a given network, apply dropout to reduce overfitting | Part B final question: design and justify a network + optimiser for a novel regression problem; analyse convergence behaviour | ≈14 Awareness + ≈6 Advanced |
| IA-2 (CO3–CO4) | Part A: compute feature-map dimensions, explain residual learning, describe LSTM gate equations, apply transfer learning workflow | Part B final question: design a CNN solution for medical imaging or a Transformer pipeline for a novel NLP task; justify architecture and evaluation strategy | ≈14 Awareness + ≈6 Advanced |
| SEE (CO1–CO6) | Standard-case questions across all four units: definitions, standard calculations, known architecture descriptions, standard application scenarios | At least one advanced item per unit: novel-problem design, comparative analysis, XAI interpretation, generative model justification | ≈35 Awareness + ≈15 Advanced |

## 15\. 🔵 Result analysis — banded to detect the two levels

_(To be filled after each assessment)_

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared, awareness-solid) | > 75% (advanced attained) |
| --- | --- | --- | --- |
| IA-1 |  |  |  |
| IA-2 |  |  |  |
| Assignment 1 |  |  |  |
| Assignment 2 |  |  |  |
| SEE |  |  |  |

## 16\. Learner support tracking 🟢🔵

### 16.1 Students below the floor (per IA) — remediation

| Sl | SRN | Name | IA | Gap identified | Remedial class dates | Re-assessment result |
| --- | --- | --- | --- | --- | --- | --- |

### 16.2 Students reaching for the ceiling — enrichment

| Sl | SRN | Name | Advanced task assigned | Outcome |
| --- | --- | --- | --- | --- |
|  | No. of students | Action taken |
| --- | --- | --- |
| Below floor (slow learners) |  |  |
| At ceiling (fast learners) |  |  |

## 17\. 🔵 Track-advice signal (links course → SIG track choice)

| Field | Entry |
| --- | --- |
| Is this a prerequisite for a SIG track? | Yes — AI/ML-Data Engineering SIG and AI Research/NLP SIG |
| % of students at advanced level (> 75% / 8+ CGPA) | ‹fill after SEE› |
| Domains where advanced performance clustered | ‹e.g. "strong in CNN/Vision (Units 1–2), weaker in Transformers (Unit 3)"› |
| Recommended note to academic mentors | Students consistently above the ceiling in Units 2–4 (CNN, sequence models, generative AI) are strong candidates for the AI/ML-Data Engineering and NLP SIG tracks. Students who excelled specifically in Grad-CAM and XAI (Unit 4) may consider Responsible AI / Explainable AI electives in Sem 7–8. |

## 18\. CO attainment 🟢🔵

**Set target:** 60%

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level (A/Adv) 🔵 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CO1 |  |  |  |  |  |  | Awareness |
| CO2 |  |  |  |  |  |  | Both |
| CO3 |  |  |  |  |  |  | Advanced |
| CO4 |  |  |  |  |  |  | Advanced |
| CO5 |  |  |  |  |  |  | Advanced |
| CO6 |  |  |  |  |  |  | Advanced |

_(Values to be filled post-assessment)_

## 19\. CO–PO/PSO mapping & overall attainment 🟢

**Strength: 1 = Low, 2 = Medium, 3 = High.**

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PSO1 | PSO2 | PSO3 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CO1 | 3 | 2 |  |  |  |  |  |  |  |  |  | 3 |  |  |
| CO2 | 3 | 3 | 2 | 2 | 3 |  |  |  |  |  |  | 3 | 2 |  |
| CO3 | 3 | 3 | 3 | 2 | 3 |  |  |  |  |  |  | 3 | 3 |  |
| CO4 | 3 | 3 | 3 | 3 | 3 |  |  |  |  |  |  | 3 | 3 |  |
| CO5 | 3 | 3 | 2 | 2 | 3 |  |  |  | 3 |  |  | 3 |  | 2 |
| CO6 | 3 | 3 | 3 | 3 | 3 |  | 2 | 3 | 3 | 2 | 2 | 3 |  | 3 |

**Overall attainment** _(fill post-SEE)_:

|  | Internal | External | Grand total (80% + 20%) |
| --- | --- | --- | --- |
| CO attainment |  |  |  |
| PO attainment |  |  |  |
| PSO attainment |  |  |  |

**Minimum level for PO attainment:** 50%–60%

## 20\. Course completion summary 🟢

| Unit | Planned date | Completion date | Remarks |
| --- | --- | --- | --- |
| 1 — Neural Network Fundamentals | ‹…› |  |  |
| 2 — CNNs and Computer Vision | ‹…› |  |  |
| 3 — Sequence Models and Transformers | ‹…› |  |  |
| 4 — Generative DL and XAI | ‹…› |  |  |

## 21\. 🔵 Faculty reflection — dual-level health check

_(To be completed at course close)_

*   Did the awareness floor genuinely protect placement-readiness for the weakest students? ‹…›
*   Was the advanced ceiling reached by roughly the expected share, or did it collapse / go unassessed? ‹…›
*   One change to the awareness/advanced split for next offering: ‹…›

**Signatures**

Course Faculty (digital signature) — ‹…›     HoD / Director (digital signature) — ‹…›

## 22\. 🔵 Implementation strategy — Merrill's First Principles

Learning activities in §11 are structured around **Merrill's First Principles of Instruction**.

| Phase | What it means | Typical activity in this course |
| --- | --- | --- |
| Problem / Task-centred | Anchor learning in a real-world problem | Student placement, medical imaging, sentiment classification, defect detection |
| Activation | Activate relevant prior knowledge | Lecture followed by a demonstration; recap quiz linking prior ML concepts |
| Demonstration | Show, don't just tell | Live coding in TF/Keras; whiteboard derivations; architecture walkthroughs |
| Application | Learner practises with feedback | Guided numerical tutorials; lab programs (Level 1: Programs 1–8) |
| Integration | Learner transfers to own context | Level 2 lab experiments (Programs 9–16); capstone project; self-learning seminars |

**Design rule:** across each unit the §11 sessions cover all five phases. Advanced-level activities appear explicitly in Application and Integration sessions — without them the course has no ceiling.

### 22.1 Phase-coverage check 🔵

| Check | Entry |
| --- | --- |
| All five Merrill phases used at least once per unit | Yes — each unit opens with a PC+Act session, progresses through Demo and App sessions, and closes with an Int/case-study session. |
| §11 sessions using Activation = lecture + demonstration | T01, T09, T16, T23 (unit-opening sessions for each unit) |
| §11 sessions delivering Advanced-level activities | T08 (U1), T15 (U2), T22 (U3), T28 (U4); TU1.8, TU2.8, TU3.8, TU4.8 (advanced case-study tutorials); Lab Programs 9–16 |
| ✅ Ceiling taught (≥1 Adv activity per unit, not only assessed) | Yes |

### Lab programme summary (for reference)

| Program | Topic | Scenario | Level | CO |
| --- | --- | --- | --- | --- |
| 1 | Perceptron Classification | Classify students as Pass/Fail based on internal marks | Level 1 | CO1 |
| 2 | Activation Function Analysis | Compare Sigmoid, Tanh, ReLU using a dataset | Level 1 | CO1 |
| 3 | MLP for Binary Classification | Predict employee attrition using HR data | Level 1 | CO2 |
| 4 | Optimisation Algorithms | Compare SGD, Momentum, Adam for customer churn prediction | Level 1 | CO2 |
| 5 | Regularisation and Dropout | Reduce overfitting in student placement prediction model | Level 1 | CO2 |
| 6 | CNN for Image Classification | Handwritten digit recognition | Level 1 | CO3 |
| 7 | Image Augmentation & CNN | Plant disease classification accuracy improvement | Level 1 | CO3 |
| 8 | Transfer Learning (MobileNet/ResNet) | Animal/object classification with limited training data | Level 1 | CO3 |
| 9 | CNN-Based Medical Image Diagnosis | Chest X-ray classification: Normal vs Pneumonia | Level 2 | CO3, CO5 |
| 10 | Smart Manufacturing Defect Detection | CNN visual inspection system for assembly-line images | Level 2 | CO3, CO5 |
| 11 | LSTM Sentiment Analysis | E-commerce review classification (Positive/Neutral/Negative) | Level 2 | CO4 |
| 12 | Time-Series Forecasting (LSTM/GRU) | Retail monthly sales prediction and model comparison | Level 2 | CO4 |
| 13 | Transformer Text Classification | News article multi-domain categorisation | Level 2 | CO4, CO5 |
| 14 | Resume Screening using BERT | Intelligent recruitment classification + bias analysis | Level 2 | CO4, CO6 |
| 15 | Explainable AI using Grad-CAM | Manufacturing defect prediction visual justification | Level 2 | CO5, CO6 |
| 16 | Deep Learning Capstone Project | Real-world dataset: compare ≥2 architectures, justify best model with metrics + explainability | Level 2 | CO5, CO6 |

**Appendix A – Specimen Rubric for Level-2 Lab Programmes**

| Criterion | Description | Marks |
| --- | --- | --- |
| Problem Understanding | Correct interpretation of the problem statement and dataset | 4 |
| Architecture Selection & Justification | Appropriate model selection with technical justification | 4 |
| Implementation & Performance | Model implementation, training and evaluation metrics | 4 |
| Comparative Analysis | Comparison with at least one alternative architecture | 4 |
| Explainability & Responsible AI | Use of Grad-CAM/XAI and discussion of ethical considerations | 4 |
| Total |  | 20 |

This rubric is indicative and may be adapted for Programs 9–16 depending on the nature of the task while retaining the awareness–advanced assessment philosophy**.**

**Self-Learning Component topics:** Vision Transformers (ViT), Large Language Models (LLMs), Prompt Engineering, Multimodal AI, Self-Supervised Learning, Explainable Deep Learning, Federated Learning, Edge AI for Deep Learning, Deep Learning Applications in Healthcare and Smart Cities.