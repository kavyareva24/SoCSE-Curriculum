# Course File --- Dual-Level (Awareness + Advanced) Design

### B24EA501 · Machine Learning · Semester 5 · AIML · AY 2026--27 (Odd)

## 0. Course identification 🟢

  -----------------------------------------------------------------------
  Field                               Entry
  ----------------------------------- -----------------------------------
  Faculty name                        Sindhu P. Menon

  REVA ID                             REVA02778

  Email                               <sindhu.menon@reva.edu.in>

  Programme                           B.Tech --- AIML

  Category                            HC

  Course code                         B24EA501 (1-1-1)

  Course title                        Machine Learning

  Semester & section                  5-A,B,C

  Academic year                       2026--2027 Odd

  Course duration (sessions)          65 sessions (excluding IA and SEE
                                      exams)

  Office / consultation hours         8:30 am -- 4:30 pm
  -----------------------------------------------------------------------

**School vision:** To emerge as a globally recognised department of
computer science in education, research, and innovation that advances
technology for sustainable development, serves humanity, and nurtures
ethically responsible leaders for the digital future.

**School mission:** To provide learner-centric education in computer
science and engineering, leveraging cutting-edge technologies to empower
students with strong theoretical foundations, practical skills, and
interdisciplinary knowledge; to foster innovation, research, and
entrepreneurship in emerging areas of computer science while promoting
sustainability, inclusivity, and universal values; to prepare graduates
for lifelong learning and impactful careers; to build a culture of
collaboration through industry--academia partnerships; and to serve
society through technology solutions that enhance human well-being.

## 1. Course description 🟢

This integrated course provides students with a strong foundation in
Machine Learning by combining conceptual understanding, analytical
problem-solving, and hands-on implementation across the complete ML
lifecycle --- from data preparation and feature engineering through
regression, classification, model evaluation, clustering, dimensionality
reduction, and responsible AI practices. The course follows an
activity-based learning approach in which theoretical concepts are
reinforced through tutorial exercises and laboratory sessions using
Python and Scikit-Learn on real-world datasets. Organized progressively
from foundational concepts to advanced model development and
optimisation, the course culminates in mini-projects and case studies
that require students to apply machine learning techniques to solve
genuine engineering problems.

## 2. Course content (units & weightage) 🟢

  ------------------------------------------------------------------------------
  Unit                    Syllabus                       Weightage
  ----------------------- ------------------------------ -----------------------
  1                       **Introduction to Machine      25 Marks
                          Learning and Data              
                          Preprocessing** ---            
                          Introduction to ML, Types of   
                          Learning (Supervised,          
                          Unsupervised), ML Pipeline,    
                          Training/Validation/Testing,   
                          Feature Types, Data Cleaning,  
                          Missing Value Handling,        
                          Feature Scaling, Encoding      
                          Categorical Variables, Feature 
                          Selection, Overfitting and     
                          Underfitting, Bias--Variance   
                          Tradeoff. *(TB1: Ch 1          
                          §1.1--1.2.5, Ch 2 §2.1--2.8,   
                          Ch 4 §4.3/4.7--4.8; TB2: Ch 1  
                          §1.1--1.5, Ch 3 §3.1--3.3)*    

  2                       **Regression Models** ---      25 Marks
                          Simple Linear Regression,      
                          Multiple Linear Regression,    
                          Polynomial Regression, Model   
                          Assumptions, Cost Function,    
                          Performance Measures (MAE,     
                          MSE, RMSE, R² Score). *(TB1:   
                          Ch 2 §2.6, Ch 4 §4.6, Ch 5     
                          §5.8; TB2: Ch 1 §1.5, Ch 3     
                          §3.1)*                         

  3                       **Classification Models** ---  25 Marks
                          K-Nearest Neighbour, Naïve     
                          Bayes Classifier, Decision     
                          Trees, Support Vector          
                          Machines, Confusion Matrix,    
                          Accuracy, Precision, Recall,   
                          F1 Score, ROC Curve and AUC.   
                          *(TB1: Ch 3 §3.2--3.4, Ch 5    
                          §5.5, Ch 8 §8.4--8.5, Ch 9     
                          §9.2.1, Ch 10 §10.7--10.9;     
                          TB2: Ch 2 §2.1--2.5, Ch 4      
                          §4.1--4.5, Ch 6 §6.1--6.4, Ch  
                          7 §7.1--7.2)*                  

  4                       **Model Evaluation, Clustering 25 Marks
                          and Dimensionality Reduction** 
                          --- Cross Validation, K-Fold   
                          Validation, Hyperparameter     
                          Tuning, Ensemble Learning      
                          (Bagging, Random Forest,       
                          Boosting), K-Means Clustering, 
                          Hierarchical Clustering,       
                          Cluster Validation, Curse of   
                          Dimensionality, PCA,           
                          Introduction to Responsible AI 
                          and Explainability. *(TB1: Ch  
                          6 §6.2--6.6, Ch 7 §7.2--7.8,   
                          Ch 14 §14.2--14.8, Ch 15       
                          §15.1--15.5; TB2: Ch 9         
                          §9.1--9.3, Ch 12 §12.1--12.2)* 
  ------------------------------------------------------------------------------

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

  -----------------------------------------------------------------------
  Unit                    Awareness level ---     Advanced level ---
                          every student must      required to exceed 8
                          reach (the floor)       CGPA (the ceiling)
  ----------------------- ----------------------- -----------------------
  1                       Define ML paradigms and Analyse trade-offs in
                          the ML pipeline;        feature selection
                          explain data cleaning,  strategies for a novel
                          missing-value handling, dataset; justify
                          feature scaling and     preprocessing choices
                          encoding; identify      (scaling method,
                          overfitting vs          encoding scheme) with
                          underfitting and        reasoning; derive and
                          describe the            interpret the
                          bias--variance tradeoff bias--variance
                          in standard cases       decomposition and
                                                  propose remediation for
                                                  a given learning curve

  2                       Apply simple, multiple  Compare regression
                          and polynomial          models for a new
                          regression to           real-world problem and
                          instructor-given        justify model
                          datasets; compute MAE,  selection; analyse
                          MSE, RMSE, R²; explain  residuals to diagnose
                          cost function           assumption violations;
                          minimisation            optimise a regression
                                                  pipeline through
                                                  feature transformation
                                                  choices

  3                       Apply KNN, Naïve Bayes, Evaluate and compare
                          Decision Tree and SVM   classifiers on an
                          to standard             unseen domain problem
                          classification tasks;   using ROC analysis;
                          compute                 design a decision-tree
                          confusion-matrix        pruning strategy;
                          metrics (accuracy,      analyse the effect of
                          precision, recall, F1,  hyperparameter choices
                          AUC); explain           (k, kernel, depth) with
                          algorithmic decisions   justification

  4                       Explain                 Design a full
                          cross-validation and    model-evaluation
                          K-fold; apply K-Means   pipeline (K-fold +
                          clustering; implement   hyperparameter tuning)
                          PCA; describe ensemble  for a novel prediction
                          concepts (bagging,      task; justify
                          boosting, Random        cluster-count selection
                          Forest); explain the    using silhouette
                          curse of dimensionality analysis; evaluate an
                                                  ML model for bias and
                                                  propose explainability
                                                  measures aligned with
                                                  responsible AI
                                                  principles
  -----------------------------------------------------------------------

**Bloom anchor:**

  -----------------------------------------------------------------------
  Level                   Bloom verbs             Typical question stem
  ----------------------- ----------------------- -----------------------
  **Awareness (floor)**   Remember, Understand,   \"Define...\",
                          Apply                   \"Explain...\", \"Apply
                                                  X to this standard
                                                  case...\", \"Calculate
                                                  the metric for...\"

  **Advanced (ceiling)**  Analyse, Evaluate,      \"Compare and
                          Create                  justify...\",
                                                  \"Optimise the pipeline
                                                  for...\", \"Design a
                                                  solution for this novel
                                                  problem...\",
                                                  \"Critique the model\'s
                                                  fairness and
                                                  propose...\"
  -----------------------------------------------------------------------

## 4. Course objectives 🟢

-   Understand Machine Learning fundamentals --- paradigms, pipeline,
    and mathematical underpinnings

-   Prepare and engineer data for learning --- cleaning, scaling,
    encoding, and feature selection

-   Develop predictive models using regression and classification
    algorithms

-   Evaluate and improve model performance through validation techniques
    and ensemble methods

-   Apply unsupervised learning techniques --- clustering and
    dimensionality reduction

-   Implement ML solutions using Python/Scikit-Learn on real-world
    datasets

-   Practice responsible and ethical AI --- explainability, fairness,
    and professional integrity

-   Achieve progressive mastery through integrated theory--tutorial--lab
    learning

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

  ----------------------------------------------------------------------------
  CO#            Course outcome   Level 🔵       POs            PSOs
  -------------- ---------------- -------------- -------------- --------------
  CO1            Explain machine  Awareness      PO1 (3), PO2   PSO1 (3)
                 learning                        (2), PO5 (2),  
                 paradigms,                      PO9 (--)       
                 workflow, data                                 
                 types, and                                     
                 preprocessing                                  
                 techniques                                     
                 required for                                   
                 building                                       
                 intelligent                                    
                 systems                                        

  CO2            Apply data       Both           PO1 (3), PO2   PSO1 (3), PSO2
                 cleaning,                       (3), PO5 (3),  (2)
                 feature                         PO9 (3), PO10  
                 engineering,                    (2)            
                 feature scaling,                               
                 and encoding                                   
                 techniques to                                  
                 prepare datasets                               
                 for machine                                    
                 learning                                       
                 applications                                   

  CO3            Develop and      Both           PO1 (3), PO2   PSO1 (3), PSO2
                 evaluate                        (3), PO3 (2),  (3)
                 regression                      PO5 (3), PO9   
                 models for                      (3), PO10 (3)  
                 predictive                                     
                 analytics using                                
                 appropriate                                    
                 performance                                    
                 measures                                       

  CO4            Build and        Both           PO1 (3), PO2   PSO1 (3), PSO2
                 analyse                         (3), PO3 (2),  (3)
                 classification                  PO4 (2), PO5   
                 models using                    (3), PO9 (3),  
                 KNN, Naïve                      PO10 (3)       
                 Bayes, Decision                                
                 Trees, and                                     
                 Support Vector                                 
                 Machines                                       

  CO5            Evaluate and     Advanced       PO1 (3), PO2   PSO2 (3), PSO3
                 improve machine                 (3), PO3 (3),  (2)
                 learning models                 PO4 (3), PO5   
                 using validation                (3), PO7 (2),  
                 techniques,                     PO10 (2), PO11 
                 performance                     (3)            
                 metrics, and                                   
                 ensemble                                       
                 learning methods                               
                 for enhanced                                   
                 predictive                                     
                 performance                                    

  CO6            Apply clustering Advanced       PO1 (2), PO2   PSO1 (2), PSO2
                 techniques and                  (2), PO3 (2),  (3), PSO3 (3)
                 implement                       PO4 (2), PO5   
                 machine learning                (3), PO7 (2),  
                 solutions using                 PO8 (3), PO9   
                 Python and                      (2), PSO1 (2), 
                 Scikit-Learn to                 PSO2 (3), PSO3 
                 solve real-world                (3)            
                 data-driven                                    
                 problems while                                 
                 adhering to                                    
                 ethical and                                    
                 responsible AI                                 
                 practices                                      
  ----------------------------------------------------------------------------

> 🔵 CO1 is Awareness (floor, placement-readiness anchor). CO2--CO4 are
> Both (bridging floor to ceiling). CO5--CO6 are Advanced (ceiling ---
> required for \> 8 CGPA).

## 6. Pedagogy 🟢

-   **Direct method** --- conceptual explanation and algorithm analysis
    for all units

-   **ICT and Digital support** --- NPTEL video lectures, YouTube
    demonstrations (links in §12)

-   **Activity-based / collaborative learning** --- in-class tutorial
    problem-solving and peer discussion

-   **Differentiated instruction** --- tiered assignments separating
    awareness and advanced tasks (see §8)

-   **Flipped classroom** --- selected NPTEL segments assigned for
    pre-reading; class time used for exercises and discussion

The direct instruction and ICT-supported methods are primarily used
during the Activation and Demonstration phases of the Merrill framework,
while activity-based, collaborative, and flipped learning approaches are
employed during the Application and Integration phases. The
implementation of these phases is detailed in the session plan (Section
11) and audited in Section 22.

## 7. Textbooks, references, e-resources 🟢

**Textbooks:**

1.  Ethem Alpaydin, *Introduction to Machine Learning*, 4th Edition, MIT
    Press (TB1)

2.  Christopher M. Bishop, *Pattern Recognition and Machine Learning*,
    Springer (TB2)

**References:**

1.  Aurélien Géron, *Hands-On Machine Learning with Scikit-Learn, Keras
    and TensorFlow*, 3rd Edition

2.  Tom Mitchell, *Machine Learning*, McGraw-Hill

3.  Andreas C. Müller and Sarah Guido, *Introduction to Machine Learning
    with Python*

**Journals / Magazines:**

-   Journal of Machine Learning Research (JMLR): <https://www.jmlr.org/>

-   Machine Learning (Springer):
    <https://link.springer.com/journal/10994>

**SWAYAM / NPTEL / MOOCs:**

1.  NPTEL: Machine Learning by Prof. Balaraman Ravindran, IIT Madras ---
    <https://onlinecourses.nptel.ac.in/>

2.  Coursera: *AI for Everyone* by Andrew Ng ---
    <https://www.coursera.org/learn/ai-for-everyone>

**Self-learning component topics:** Applications of ML in Healthcare,
Finance and Agriculture; Data Visualisation Techniques; Data Quality
Assessment; Open-Source ML Libraries; Logistic Regression (overview);
Regression Trees; Regularisation (Ridge, Lasso); Feature Interaction;
Multiclass Classification; Cost-Sensitive Learning; Introduction to
Neural Networks; Association Rule Mining; Recommender Systems;
Semi-Supervised Learning; Reinforcement Learning (overview); Explainable
AI; ML Applications in Smart Cities and IoT.

**Content Currency Note:** Laboratory tools, datasets, and software
libraries used in the course will be reviewed and updated annually
before the commencement of the Odd Semester.

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) --- for students at risk of not
clearing it:**

-   Remedial support classes triggered by IA-1 and IA-2 performance (\<
    40%)

-   Detailed notes and worked examples distributed for core concepts
    (scaling, encoding, regression, classifier metrics)

-   Scaffolded Level-1 assignments (Assignments 1--8) covering basic
    preprocessing, regression, and classification tasks

-   Curated NPTEL / YouTube videos assigned as pre-class viewing with
    guided comprehension questions

-   Peer mentoring pairing for students identified after IA-1

**Remediation Trigger**: Students scoring below 40% in IA-1 or IA-2 will
be enrolled in remedial activities. The nature of remediation will be
determined through CO-wise result analysis and targeted to the specific
concepts in which the student demonstrates learning gaps.

**Reaching the ceiling (advanced level) --- for students aiming above 8
CGPA:**

-   Group project (3--4 members) drawing on Level-2 assignments
    (Assignments 9--16) including cross-validation pipelines,
    hyperparameter tuning, ensemble methods, and the Comparative ML
    Mini-Project (Assignment 16)

-   Stretch problems in tutorials: open-ended cases requiring
    justification of design choices (e.g. \"why this kernel for SVM?\",
    \"design a responsible AI audit for this model\")

-   Optional reading beyond the prescribed text --- selected chapters
    from Géron\'s *Hands-On ML* and recent JMLR survey papers

-   Advanced tutorial tracks: novel-dataset challenges using real Kaggle
    or government datasets for feature engineering and model selection

## 9. Assignments 🟢

  -----------------------------------------------------------------------------
  Assignment      Topic / Level    Units covered  Marks          Window
  --------------- ---------------- -------------- -------------- --------------
  Assignment 1    Data             Unit 1         5              Before IA-1
                  Preprocessing                                  
                  and Feature                                    
                  Scaling (L1)                                   

  Assignment 2    Categorical Data Unit 1         --- (part of   Before IA-1
                  Encoding (L1)                   Asgn 1 bundle) 

  Assignment 3    Exploratory Data Unit 1         ---            Before IA-1
                  Analysis (L1)                                  

  Assignment 4    Simple Linear    Unit 2         ---            Before IA-1
                  Regression (L1)                                

  Assignment 5    Multiple Linear  Unit 2         ---            Before IA-1
                  Regression (L1)                                

  Assignment 6    Polynomial       Unit 2         ---            Before IA-1
                  Regression (L1)                                

  Assignment 7    KNN              Unit 3         ---            Before IA-2
                  Classification                                 
                  (L1)                                           

  Assignment 8    Naïve Bayes      Unit 3         ---            Before IA-2
                  Classification                                 
                  (L1)                                           

  **Assignment    **Assignments    **Units 1--2** **5**          **Before
  Batch 1         1--8 bundled**                                 IA-2**
  (submitted)**                                                  

  Assignment 9    Decision Tree    Unit 3         ---            Before IA-2
                  Classification                                 
                  (L2)                                           

  Assignment 10   SVM              Unit 3         ---            Before IA-2
                  Classification                                 
                  (L2)                                           

  Assignment 11   Model Evaluation Unit 4         ---            Before IA-3
                  using Metrics                                  
                  (L2)                                           

  Assignment 12   K-Fold Cross     Unit 4         ---            Before IA-3
                  Validation (L2)                                

  Assignment 13   Hyperparameter   Unit 4         ---            Before IA-3
                  Tuning --- Grid                                
                  Search (L2)                                    

  Assignment 14   Random Forest    Unit 4         ---            Before IA-3
                  Classification                                 
                  (L2)                                           

  Assignment 15   K-Means          Unit 4         ---            Before IA-3
                  Clustering (L2)                                

  Assignment 16   Comparative ML   Units 3--4     ---            Before IA-3
                  Mini-Project                                   
                  (L2)                                           

  **Assignment    **Assignments    **Units 3--4** **5**          **Before
  Batch 2         9--16 bundled**                                IA-3**
  (submitted)**                                                  
  -----------------------------------------------------------------------------

> Batch 1 (scored 5 marks) covers Units 1--2 and is due before IA-2.
> Batch 2 (scored 5 marks) covers Units 3--4 and is due before IA-3 /
> SEE.
>
> 🔵 **Integrity-by-Design for Assignment Evaluation**
>
> To ensure individual competency and discourage unauthorised
> AI-assisted completion, students shall demonstrate ownership of their
> submitted work through the following mechanisms:

-   Viva voce on the submitted assignment/code.

-   In-class demonstration of program execution and results(wherever
    > applicable).

-   A brief written justification explaining model selection,
    > preprocessing choices, evaluation metrics, and interpretation of
    > results in the student\'s own words.

> Assignment marks may be moderated if the student is unable to explain
> or demonstrate the submitted work.

## 10. Prerequisites / pre-reading 🟢

**Prerequisite courses:** Programming in C/C++/Python; Basic Mathematics
(Linear Algebra, Probability and Statistics).

> 🔵 Week-0 Bridge Module:\
> To ensure uniform readiness for the Machine Learning course, a bridge
> module will be conducted before the commencement of regular classes.
> The module includes:\
> • Python programming refresher\
> • NumPy and Pandas fundamentals\
> • Basic statistics concepts\
> • Diagnostic quiz
>
> 🔵 Prerequisite-course performance --- particularly Python proficiency
> and statistical reasoning --- is the primary input academic mentors
> should use when advising AIML/Data-Engineering SIG track selection.
> Record prerequisite outcomes here so the mentoring signal in §17 is
> traceable.

## 11. Lesson plan --- tentative transaction dates + session implementation 🟢🔵

> Each row is one session. **Level**: A = Awareness, Adv = Advanced.
> **Merrill phase** and **Activity** columns carry the full
> implementation plan; §22 audits phase coverage. Planned dates to be
> filled by faculty at course start; Exec. date and Remarks filled
> during delivery.

### Unit 1 --- Introduction to ML and Data Preprocessing (Sessions 1--16)

  ------------------------------------------------------------------------------------------------------------------
  S.No    Planned   Exec.   Unit / Topic     Merrill phase 🔵    Activity (what   \%       Level   CO      Remarks
          date      date                                         the faculty      compl.   🔵              
                                                                 runs) 🔵                                  
  ------- --------- ------- ---------------- ------------------- ---------------- -------- ------- ------- ---------
  01      ‹...›             U1 ---           Problem-centred +   Present anchor   10%      A       CO1     
                            Introduction to  Activation          problem (Titanic                          
                            ML; Types of                         survival                                  
                            Learning                             prediction);                              
                                                                 lecture on ML                             
                                                                 definition and                            
                                                                 supervised vs                             
                                                                 unsupervised                              
                                                                 paradigms                                 
                                                                 followed by a                             
                                                                 live                                      
                                                                 demonstration of                          
                                                                 a pre-trained                             
                                                                 classifier on                             
                                                                 the Titanic                               
                                                                 dataset                                   

  02      ‹...›             U1 --- ML        Demonstration       Walkthrough:              A       CO1     
                            Pipeline;                            end-to-end ML                             
                            Training /                           pipeline with a                           
                            Validation /                         simple dataset;                           
                            Testing                              show train--test                          
                                                                 split                                     
                                                                 numerically                               

  03      ‹...›             U1 --- Feature   Activation +        Lecture on                A       CO1,    
                            Types; Data      Demonstration       feature types                     CO2     
                            Cleaning                             followed by a                             
                                                                 live demo                                 
                                                                 identifying and                           
                                                                 cleaning a messy                          
                                                                 CSV                                       

  04      ‹...›             U1 --- Missing   Application         Tutorial:                 A       CO2     
                            Value Handling                       numerical                                 
                                                                 imputation                                
                                                                 examples;                                 
                                                                 students work                             
                                                                 mean/median                               
                                                                 imputation by                             
                                                                 hand                                      

  05      ‹...›             U1 --- Feature   Demonstration +     Worked examples           A       CO2     
                            Scaling          Application         of Min-Max and                            
                            (Min--Max,                           Z-score scaling;                          
                            Standard)                            tutorial                                  
                                                                 calculations                              

  06      ‹...›             U1 --- Encoding  Application         Tutorial: Label           A       CO2     
                            Categorical                          Encoding and                              
                            Variables                            One-Hot Encoding                          
                                                                 examples on                               
                                                                 instructor                                
                                                                 datasets                                  

  07      ‹...›             U1 --- Feature   Demonstration       Lecture + demo:           A       CO2     
                            Selection                            filter vs                                 
                                                                 wrapper methods;                          
                                                                 correlation                               
                                                                 heatmap                                   
                                                                 walkthrough                               

  08      ‹...›             U1 ---           Activation +        Lecture on                A       CO1     
                            Overfitting and  Demonstration       bias--variance                            
                            Underfitting                         tradeoff;                                 
                                                                 demonstrate                               
                                                                 learning curves                           
                                                                 in Python                                 

  09      ‹...›             U1 ---           Application +       Stretch problem:          Adv     CO2     
                            Bias--Variance   Integration         given a learning                          
                            Tradeoff                             curve, identify                           
                            (analysis)                           regime and                                
                                                                 propose fix ---                           
                                                                 ceiling task                              

  10      ‹...›             U1 --- Tutorial: Application         Tutorial                  A       CO1,    Extra
                            train--test                          session:                          CO2     class if
                            split numerics;                      Numerical                                 needed
                            imputation;                          problems 1--5                             
                            scaling                              (train-test                               
                                                                 split,                                    
                                                                 imputation,                               
                                                                 scaling                                   
                                                                 calculations)                             

  11      ‹...›             U1 --- Tutorial: Application +       Titanic dataset           Adv     CO2     
                            case study       Integration         case                                      
                            Titanic dataset                      walkthrough:                              
                                                                 identify                                  
                                                                 features,                                 
                                                                 target, model                             
                                                                 type; justify                             
                                                                 choices                                   

  12      ‹...›             U1 --- Lab:      Activation +        Lab: Python               A       CO2     
                            Python           Demonstration       setup; data                               
                            environment;                         loading with                              
                            Pandas data                          Pandas; initial                           
                            loading                              exploration                               

  13      ‹...›             U1 --- Lab: Data Application         Lab: handle               A       CO2     
                            preprocessing                        missing values,                           
                            and cleaning                         remove                                    
                                                                 duplicates,                               
                                                                 basic EDA on                              
                                                                 provided dataset                          

  14      ‹...›             U1 --- Lab:      Application         Lab: implement            A       CO2     
                            Feature scaling                      Min-Max and                               
                            with                                 Standard Scaler;                          
                            Scikit-Learn                         compare                                   
                                                                 distributions                             
                                                                 before/after                              

  15      ‹...›             U1 --- Lab:      Application         Lab: full                 A       CO2     
                            Titanic dataset                      preprocessing                             
                            preprocessing                        pipeline on                               
                                                                 Titanic ---                               
                                                                 encode, scale,                            
                                                                 select features                           

  16      ‹...›             U1 ---           Integration         Student-led      25%      Adv     CO2     Extra
                            Integration /                        discussion:                               class if
                            review                               present Titanic                           needed
                                                                 preprocessing                             
                                                                 choices; peer                             
                                                                 critique of                               
                                                                 decisions                                 
  ------------------------------------------------------------------------------------------------------------------

### Unit 2 --- Regression Models (Sessions 17--28)

  -------------------------------------------------------------------------------------------------------------------
  S.No    Planned   Exec.   Unit / Topic     Merrill phase 🔵    Activity 🔵       \%       Level   CO      Remarks
          date      date                                                           compl.   🔵              
  ------- --------- ------- ---------------- ------------------- ----------------- -------- ------- ------- ---------
  17      ‹...›             U2 --- Simple    Problem-centred +   Anchor problem:            A       CO3     
                            Linear           Activation          predict house                              
                            Regression                           price; lecture on                          
                                                                 SLR model and                              
                                                                 cost function                              
                                                                 followed by                                
                                                                 demonstration of                           
                                                                 gradient descent                           
                                                                 convergence                                

  18      ‹...›             U2 --- Multiple  Demonstration       Walkthrough:               A       CO3     
                            Linear                               extend SLR to                              
                            Regression                           multiple                                   
                                                                 features; matrix                           
                                                                 form explanation                           

  19      ‹...›             U2 ---           Demonstration       Live demo: fit             A       CO3     
                            Polynomial                           polynomial curves                          
                            Regression                           of varying                                 
                                                                 degree; show                               
                                                                 overfitting                                
                                                                 effect                                     

  20      ‹...›             U2 --- Model     Application         Tutorial:                  A       CO3     
                            Assumptions and                      numerical SLR                              
                            Cost Function                        examples; compute                          
                                                                 cost function by                           
                                                                 hand                                       

  21      ‹...›             U2 ---           Application         Tutorial: error            A       CO3     
                            Performance                          metric                                     
                            Measures (MAE,                       calculations on                            
                            MSE, RMSE, R²)                       instructor data;                           
                                                                 interpret R²                               

  22      ‹...›             U2 ---           Application +       Stretch: given             Adv     CO3     
                            Regression       Integration         two models\'                               
                            analysis and                         residual plots,                            
                            interpretation                       select and                                 
                                                                 justify the                                
                                                                 better model                               

  23      ‹...›             U2 --- Tutorial: Application         Tutorial                   A       CO3     Extra
                            regression                           consolidation:                             class
                            numerics                             problems 1--5                              
                            complete                             (SLR, Multiple,                            
                                                                 Polynomial,                                
                                                                 errors,                                    
                                                                 interpretation)                            

  24      ‹...›             U2 --- Lab:      Application         Lab: build SLR             A       CO3     
                            Implement Simple                     and MLR models;                            
                            and Multiple                         fit on train,                              
                            Linear                               evaluate on test                           
                            Regression                                                                      

  25      ‹...›             U2 --- Lab:      Application         Lab: implement             A       CO3     Extra
                            Polynomial                           polynomial                                 class
                            Regression                           regression; tune                           
                                                                 degree; plot                               
                                                                 bias--variance                             

  26      ‹...›             U2 --- Lab:      Application         Lab: end-to-end            A       CO3     
                            House Price                          house price                                
                            Prediction case                      prediction using                           
                            study                                multiple                                   
                                                                 regression;                                
                                                                 evaluate with                              
                                                                 MAE/RMSE/R²                                

  27      ‹...›             U2 --- Lab:      Integration         Lab: compare SLR           Adv     CO3     
                            Evaluate and                         vs MLR vs                                  
                            compare                              Polynomial on                              
                            regression                           same dataset;                              
                            models                               justify best                               
                                                                 model in a short                           
                                                                 written summary                            

  28      ‹...›             U2 ---           Integration         Mini-quiz + peer  50%      Adv     CO3     Extra
                            Integration                          discussion on                              class
                            review                               regression model                           
                                                                 selection for                              
                                                                 novel real-world                           
                                                                 scenario                                   
  -------------------------------------------------------------------------------------------------------------------

### Unit 3 --- Classification Models (Sessions 29--44)

  ---------------------------------------------------------------------------------------------------------------------------
  S.No    Planned   Exec.   Unit / Topic     Merrill phase 🔵    Activity 🔵               \%       Level   CO      Remarks
          date      date                                                                   compl.   🔵              
  ------- --------- ------- ---------------- ------------------- ------------------------- -------- ------- ------- ---------
  29      ‹...›             U3 --- KNN       Problem-centred +   Anchor: disease                    A       CO4     
                            Classifier       Activation          prediction; lecture on                             
                                                                 KNN intuition followed by                          
                                                                 demonstration of                                   
                                                                 distance-based                                     
                                                                 classification on a 2D                             
                                                                 plot                                               

  30      ‹...›             U3 --- KNN:      Demonstration       Worked examples of                 A       CO4     Extra
                            distance metrics                     Euclidean vs Manhattan                             class
                            and k selection                      distance; demo of                                  
                                                                 k-effect on boundary                               

  31      ‹...›             U3 --- Naïve     Activation +        Lecture + demo: Bayes              A       CO4     Extra
                            Bayes Classifier Demonstration       theorem refresher; Naïve                           class
                                                                 Bayes for text                                     
                                                                 classification example                             

  32      ‹...›             U3 --- Decision  Demonstration       Walkthrough: entropy,              A       CO4     
                            Trees                                information gain, tree                             
                                                                 construction step-by-step                          

  33      ‹...›             U3 --- Support   Demonstration       Lecture + demo: margin             A       CO4     
                            Vector Machines                      maximisation; kernel                               
                                                                 trick; SVM on 2D dataset                           

  34      ‹...›             U3 --- Confusion Application         Tutorial: confusion                A       CO4,    
                            Matrix and                           matrix problems; compute                   CO5     
                            metrics                              accuracy, precision,                               
                                                                 recall, F1                                         

  35      ‹...›             U3 --- ROC Curve Application         Tutorial: ROC                      A       CO4,    Extra
                            and AUC                              construction; AUC                          CO5     class
                                                                 interpretation; compare                            
                                                                 two classifiers                                    

  36      ‹...›             U3 ---           Application +       Stretch: given an unseen           Adv     CO4,    Extra
                            Classifier       Integration         medical dataset, select                    CO5     class
                            comparison                           and justify classifier                             
                            analysis                             choice; analyse FP vs FN                           
                                                                 cost                                               

  37      ‹...›             U3 --- Tutorial: Application         Tutorial problems: KNN             A       CO4     Extra
                            KNN and Naïve                        distance calculations;                             class
                            Bayes numerics                       Naïve Bayes probability                            
                                                                 computations                                       

  38      ‹...›             U3 --- Tutorial: Application         Tutorial: Decision tree            A       CO4     Extra
                            Decision Tree                        splitting calculations;                            class
                            (entropy/IG) and                     SVM margin problem;                                
                            SVM metrics                          precision/recall/F1/ROC                            

  39      ‹...›             U3 --- Lab:      Application         Lab: KNN implementation            A       CO4     
                            Heart Disease                        on Heart Disease dataset;                          
                            Prediction ---                       tune k; report metrics                             
                            KNN                                                                                     

  40      ‹...›             U3 --- Lab:      Application         Lab: Naïve Bayes                   A       CO4     Extra
                            Heart Disease                        implementation; compare                            class
                            Prediction ---                       with KNN                                           
                            Naïve Bayes                                                                             

  41      ‹...›             U3 --- Lab:      Application         Lab: build and visualise           A       CO4     Extra
                            Decision Tree                        Decision Tree; analyse                             class
                            implementation                       feature importance                                 

  42      ‹...›             U3 --- Lab: SVM  Application         Lab: SVM with multiple             A       CO4     Extra
                            implementation                       kernels (linear, RBF);                             class
                                                                 select and justify best                            
                                                                 kernel                                             

  43      ‹...›             U3 --- Lab:      Integration         Lab: compare all four              Adv     CO4,    Extra
                            Comparative                          classifiers on Heart                       CO5     class
                            performance                          Disease dataset; produce                           
                            analysis                             evaluation report                                  

  44      ‹...›             U3 ---           Integration         Peer presentation: each   75%      Adv     CO4,    Extra
                            Integration                          group presents classifier                  CO5     class
                            review                               selection rationale for a                          
                                                                 novel domain problem                               
  ---------------------------------------------------------------------------------------------------------------------------

### Unit 4 --- Model Evaluation, Clustering and Dimensionality Reduction (Sessions 45--65)

  --------------------------------------------------------------------------------------------------------------------------
  S.No    Planned   Exec.   Unit / Topic     Merrill phase 🔵    Activity 🔵           \%       Level   CO         Remarks
          date      date                                                               compl.   🔵                 
  ------- --------- ------- ---------------- ------------------- --------------------- -------- ------- ---------- ---------
  45      ‹...›             U4 --- Cross     Problem-centred +   Anchor: reliable               A       CO5        
                            Validation and   Activation          model selection for                               
                            K-Fold                               production; lecture                               
                                                                 on generalisation                                 
                                                                 followed by a                                     
                                                                 demonstration of                                  
                                                                 K-fold on a small                                 
                                                                 dataset showing                                   
                                                                 variance of results                               

  46      ‹...›             U4 ---           Demonstration       Live demo: Grid                A       CO5        
                            Hyperparameter                       SearchCV on a                                     
                            Tuning (Grid                         classifier; visualise                             
                            Search)                              search space                                      

  47      ‹...›             U4 --- Ensemble  Demonstration       Walkthrough:                   A       CO5        
                            Learning:                            Bootstrap                                         
                            Bagging and                          aggregating; Random                               
                            Random Forest                        Forest construction;                              
                                                                 feature importance                                

  48      ‹...›             U4 --- Ensemble  Demonstration       Lecture + demo:                A       CO5        
                            Learning:                            AdaBoost/Gradient                                 
                            Boosting                             Boosting concept;                                 
                                                                 compare with Random                               
                                                                 Forest                                            

  49      ‹...›             U4 --- K-Means   Activation +        Lecture: unsupervised          A       CO6        
                            Clustering       Demonstration       learning and cluster                              
                                                                 concept; demo:                                    
                                                                 K-Means convergence                               
                                                                 animation                                         

  50      ‹...›             U4 ---           Demonstration       Demo: dendrogram               A       CO6        
                            Hierarchical                         construction;                                     
                            Clustering and                       silhouette score                                  
                            Cluster                              calculation worked                                
                            Validation                           example                                           

  51      ‹...›             U4 --- Curse of  Demonstration       Lecture + demo:                A       CO6        
                            Dimensionality                       dimensionality                                    
                            and PCA                              effects; PCA                                      
                                                                 projection                                        
                                                                 visualisation in                                  
                                                                 Python                                            

  52      ‹...›             U4 ---           Activation +        Discussion-led                 Adv     CO6        
                            Responsible AI   Integration         session: bias in ML;                              
                            and                                  SHAP/LIME overview;                               
                            Explainability                       real case studies of                              
                                                                 model fairness                                    
                                                                 failure                                           

  53      ‹...›             U4 --- Tutorial: Application         Tutorial: K-Fold               A       CO5        
                            K-Fold and                           cross-validation                                  
                            hyperparameter                       exercises by hand;                                
                            tuning                               Grid Search example                               

  54      ‹...›             U4 --- Tutorial: Application         Tutorial: manual               A       CO6        
                            K-Means                              K-Means iterations (3                             
                            iterations and                       centroids, 2D data);                              
                            Silhouette Score                     silhouette score                                  
                                                                 calculation                                       

  55      ‹...›             U4 --- Tutorial: Application         Tutorial: PCA via              A       CO6        
                            PCA numerical                        covariance matrix                                 
                            examples                             computation; choose                               
                                                                 number of components                              

  56      ‹...›             U4 --- Advanced: Application +       Stretch: design a              Adv     CO5        
                            evaluation       Integration         complete evaluation                               
                            pipeline design                      pipeline (K-fold +                                
                                                                 Grid Search +                                     
                                                                 ensemble) for a novel                             
                                                                 classification                                    
                                                                 problem; written                                  
                                                                 justification                                     
                                                                 required                                          

  57      ‹...›             U4 --- Advanced: Integration         Stretch: analyse a             Adv     CO6        
                            responsible AI                       given model for                                   
                            audit                                disparate impact;                                 
                                                                 propose                                           
                                                                 explainability                                    
                                                                 measures                                          

  58      ‹...›             U4 --- Lab:      Application         Lab: implement K-Fold          A       CO5        
                            Cross Validation                     CV; compare CV score                              
                            with                                 vs simple train-test                              
                            Scikit-Learn                         split                                             

  59      ‹...›             U4 --- Lab:      Application         Lab: train Random              A       CO5        
                            Random Forest                        Forest; tune                                      
                            implementation                       n_estimators,                                     
                                                                 max_depth; evaluate                               

  60      ‹...›             U4 --- Lab:      Application         Lab: K-Means on                A       CO6        
                            Customer                             retail dataset;                                   
                            Segmentation                         choose k with elbow                               
                            using K-Means                        method; visualise                                 
                                                                 clusters                                          

  61      ‹...›             U4 --- Lab: PCA  Application         Lab: apply PCA to              A       CO6        
                            implementation                       reduce                                            
                            and                                  dimensionality;                                   
                            visualisation                        visualise components;                             
                                                                 evaluate                                          
                                                                 reconstruction                                    

  62      ‹...›             U4 --- Lab:      Integration         Lab: compare K-Means           Adv     CO6        
                            Comparative                          vs Hierarchical                                   
                            study of                             clustering; justify                               
                            clustering                           choice using                                      
                            methods                              silhouette scores                                 

  63      ‹...›             U4 --- Capstone: Integration         Assignment 16: groups          Adv     CO5, CO6   
                            Mini-project                         analyse                                           
                            work session                         instructor-provided                               
                                                                 dataset; compare ≥ 3                              
                                                                 ML models; prepare                                
                                                                 evaluation report                                 

  64      ‹...›             U4 ---           Integration         Student group                  Adv     CO5, CO6   
                            Mini-project                         presentations: model                              
                            presentations                        selection                                         
                                                                 justification and                                 
                                                                 evaluation metrics                                

  65      ‹...›             U4 --- Course    Integration         Full-course Q&A;      100%     Adv     CO1--CO6   
                            integration                          responsible AI                                    
                            review                               discussion;                                       
                                                                 CGPA-ceiling guidance                             
                                                                 on advanced topics                                
  --------------------------------------------------------------------------------------------------------------------------

## 12. ICT & digital support 🟢

**Unit 1 --- Introduction to ML and Data Preprocessing**

-   NPTEL: Machine Learning --- Introduction and Learning Paradigms:
    <https://onlinecourses.nptel.ac.in/noc26_cs66/unit?unit=71&lesson=76>

-   YouTube: Machine Learning Introduction --- NPTEL Lecture:
    <https://www.youtube.com/watch?v=ErnWZxJovaM>

**Unit 2 --- Regression Models**

-   NPTEL: Linear Regression --- NPTEL Machine Learning Course:
    <https://onlinecourses.nptel.ac.in/noc26_cs66/preview>

-   YouTube: Linear Regression Explained Clearly:
    <https://www.youtube.com/watch?v=nk2CQITm_eo>

**Unit 3 --- Classification Models**

-   NPTEL: Classification Techniques (KNN, Naïve Bayes, Decision Trees):
    <https://onlinecourses.nptel.ac.in/noc26_cs66/preview>

-   YouTube: Classification in Machine Learning --- Complete Overview:
    <https://www.youtube.com/watch?v=7VeUPuFGJHk>

**Unit 4 --- Model Evaluation, Clustering and Dimensionality Reduction**

-   NPTEL: Clustering and Dimensionality Reduction:
    <https://onlinecourses.nptel.ac.in/noc26_cs66/preview>

-   YouTube: K-Means Clustering and PCA Explained:
    <https://www.youtube.com/watch?v=4b5d3muPQmA>

## 13. Academic integrity policy 🟢

Students are expected to follow the Rules of Conduct and Academic
Behavior standards detailed in the Student Regulation Handbook. Failure
to comply may result in disciplinary actions as stipulated in the
Students Regulations.

**Note:** Copying and plagiarism in any form for any evaluation
component will result in zero marks.

## 14. 🔵 Evaluation scheme --- dual-level (CORE OF THE TEMPLATE)

  ------------------------------------------------------------------------------------------
  Sl          Component    Marks     Weight %   Awareness   Advanced    Date      COs
                                                marks       marks                 
                                                (floor)     (ceiling)             
  ----------- ------------ --------- ---------- ----------- ----------- --------- ----------
  1           Test 1       20        20         ≈14         ≈6          ‹...›     CO1--CO3
              (IA-1)                                                              

              Test 2       20        20         ≈14         ≈6          ‹...›     CO4--CO6
              (IA-2)                                                              

              Assignment 1 5         5          3           2           ‹before   CO1--CO4
              (Batch 1)                                                 IA-2›     

              Assignment 2 5         5          3           2           ‹before   CO4--CO6
              (Batch 2)                                                 IA-3›     

  2           SEE          50        50         ≈35         ≈15         ‹...›     CO1--CO6

  **Total**                **100**   **100%**   **≈69**     **≈31**               
  ------------------------------------------------------------------------------------------

> IA-1: Questions from Units 1--2; conducted for 40 marks, scaled to 20.
> IA-2: Questions from Units 3--4; conducted for 40 marks, scaled to 20.
> SEE: 100 marks scaled to 50; two questions per unit, student answers
> one per unit.
>
> 🔵 Institutional Awareness--Advanced Ratio:
>
> The assessment scheme follows an Awareness--Advanced distribution of
> approximately 70:30, in alignment with the dual-level learning
> framework adopted by the School of Computer Science and Engineering
> (SoCSE). This ratio is subject to confirmation with the applicable
> SoCSE circular and reference exemplar course.

### 14.1 🔵 The calibration that enforces the CGPA rule

  -----------------------------------------------------------------------
  Check                               Entry
  ----------------------------------- -----------------------------------
  Marks-to-CGPA conversion used       REVA CBCS: ≥ 90% → O (10 GP);
                                      80--89% → A+ (9 GP); 70--79% → A (8
                                      GP)

  Max % achievable from awareness     ≈ 69%
  marks alone                         

  Grade band that % falls into        B+ (7 GP) --- **below 8 CGPA** ✅

  Advanced marks needed to cross 8    Student must earn ≥ 1 mark from the
  CGPA (≥ 70%)                        ≈31 advanced marks in addition to
                                      full awareness marks

  ✅ Calibration confirmed            **Yes** --- a student earning full
  (awareness-only \< 8 CGPA)          awareness marks (≈69%) falls in the
                                      B+ band; clearing 70%+ requires
                                      advanced-mark capture
  -----------------------------------------------------------------------

🔵 **Regulatory Note:**

The marks-to-grade and grade-point conversion used for CGPA calibration
shall be verified against the latest REVA University Academic
Regulations and CBCS grading policy applicable to the admitted batch
before final submission of the course file.

### 14.2 Question-paper blueprint 🔵

  -----------------------------------------------------------------------
  Instrument              Awareness questions     Advanced questions
                          (Bloom: R/U/Ap)         (Bloom: An/E/C)
  ----------------------- ----------------------- -----------------------
  IA-1 / IA-2             Part A (short-answer)   Final Part B question:
                          and the standard Part B a novel/unfamiliar
                          problems (define,       scenario requiring
                          explain, apply to a     comparison,
                          given dataset, compute  justification, or
                          metrics) --- approx     optimisation --- approx
                          28/40 raw marks         12/40 raw marks

  SEE                     Standard-case questions At least one advanced
                          from each unit (define, item per unit:
                          apply, calculate) ---   novel-problem,
                          approx 70/100 raw marks justify-and-design, or
                                                  ethical-analysis item
                                                  --- approx 30/100 raw
                                                  marks
  -----------------------------------------------------------------------

**14.3 Laboratory Evaluation Blueprint** 🔵

  ------------------------------------------------------------------------
  **Criterion**    **Awareness Pass (Floor)** **Advanced Pass (Ceiling)**
  ---------------- -------------------------- ----------------------------
  Code             Code executes correctly    Code is efficient,
  Implementation   and produces the expected  well-structured, and
                   output                     appropriately optimised

  Model Selection  Uses the prescribed ML     Justifies model selection
                   model correctly            and compares alternatives

  Performance      Computes required metrics  Interprets metrics and
  Evaluation       correctly                  explains performance
                                              differences

  Analysis         Reports results obtained   Analyses results critically
                                              and proposes improvements

  Documentation    Basic report submission    Report includes reasoning,
                                              justification, and
                                              conclusions
  ------------------------------------------------------------------------

**Assessment Interpretation:** Awareness-level achievement demonstrates
successful implementation of standard machine learning procedures.
Advanced-level achievement requires justification of design decisions,
comparison of alternatives, optimisation, interpretation of results, and
evidence-based recommendations.

## 15. 🔵 Result analysis --- banded to detect the two levels

*(To be filled after each evaluation is conducted)*

  --------------------------------------------------------------------------------------
  Exam         No.        No. absent \< 40% ---  40--75% --- floor \> 75% --- Pass %
               appeared              below       cleared,          advanced   
                                     floor:      awareness-solid   attained   
                                     remediate                                
  ------------ ---------- ---------- ----------- ----------------- ---------- ----------
  IA-1                                                                        

  IA-2                                                                        

  Assignment 1                                                                

  Assignment 2                                                                

  SEE                                                                         
  --------------------------------------------------------------------------------------

> The **\> 75%** column is the proxy count for students operating at
> advanced level --- cross-check it against how many cross the 8-CGPA
> equivalent threshold. A large 40--75% group with an empty \> 75%
> column signals the ceiling is not being reached or not being assessed.

## 16. Learner support tracking 🟢🔵

### 16.1 Students below the floor (per IA) --- remediation

  -----------------------------------------------------------------------------------
  Sl         SRN        Name       IA         Gap          Remedial   Re-assessment
                                              identified   class      result
                                                           dates      
  ---------- ---------- ---------- ---------- ------------ ---------- ---------------
                                                                      

  -----------------------------------------------------------------------------------

### 16.2 Students reaching for the ceiling --- enrichment

  --------------------------------------------------------------------------
  Sl             SRN            Name           Advanced task  Outcome
                                               assigned       
  -------------- -------------- -------------- -------------- --------------
                                                              

  --------------------------------------------------------------------------

  -----------------------------------------------------------------------
                          No. of students         Action taken
  ----------------------- ----------------------- -----------------------
  Below floor (slow                               Remedial classes,
  learners)                                       detailed notes,
                                                  scaffolded assignments

  At ceiling (fast                                Group advanced project,
  learners)                                       stretch problems,
                                                  optional readings
  -----------------------------------------------------------------------

## 17. 🔵 Track-advice signal (links course → SIG track choice)

  -----------------------------------------------------------------------
  Field                               Entry
  ----------------------------------- -----------------------------------
  Is this a prerequisite for a SIG    Yes --- AI/ML and Data Engineering
  track?                              SIG tracks; AIML programme core
                                      course

  \% of students at advanced level    ‹to be filled after SEE›
  (\> 75% / 8+ CGPA)                  

  Domains where advanced performance  ‹e.g. Classification/Evaluation
  clustered                           pipeline, Clustering --- to be
                                      filled after SEE›

  Recommended note to academic        Students achieving \> 75% in Units
  mentors                             3--4 (classification + model
                                      evaluation) with strong
                                      mini-project outcomes are strong
                                      candidates for the AI/ML --- Data
                                      Engineering SIG. Students with
                                      demonstrated capability in
                                      responsible AI tasks (Assignment
                                      16, Session 57) should be flagged
                                      for ethics-focused research
                                      streams.
  -----------------------------------------------------------------------

## 18. CO attainment 🟢

**Set target:** 60% (percentage of students scoring ≥ 60%)

*(To be filled after each evaluation)*

  ------------------------------------------------------------------------------
  CO       IA1      IA2      A1       A2       SEE      Direct       Level 🔵
                                                        attainment   
  -------- -------- -------- -------- -------- -------- ------------ -----------
  CO1                                                                Awareness

  CO2                                                                Both

  CO3                                                                Both

  CO4                                                                Both

  CO5                                                                Advanced

  CO6                                                                Advanced
  ------------------------------------------------------------------------------

> 🔵 Report attainment of CO5 and CO6 (Advanced) separately against
> CO1--CO4 (Awareness/Both). If CO1--CO4 attain well but CO5--CO6
> don\'t, the floor is healthy but the ceiling is failing --- the key
> diagnostic to act on before the next offering.

## 19. CO--PO/PSO mapping & overall attainment 🟢

**Strength: 1 = Low, 2 = Medium, 3 = High.**

  ----------------------------------------------------------------------------------------------
  CO    PO1   PO2   PO3   PO4   PO5   PO6   PO7   PO8   PO9   PO10   PO11   PSO1   PSO2   PSO3
  ----- ----- ----- ----- ----- ----- ----- ----- ----- ----- ------ ------ ------ ------ ------
  CO1   3     2     ---   ---   2     ---   ---   ---   ---   ---    ---    3      ---    ---

  CO2   3     3     ---   ---   3     ---   ---   ---   3     2      ---    3      2      ---

  CO3   3     3     2     ---   3     ---   ---   ---   3     3      ---    3      3      ---

  CO4   3     3     2     2     3     ---   ---   ---   3     3      ---    3      3      ---

  CO5   3     3     3     3     3     ---   2     ---   ---   2      3      2      3      2

  CO6   2     2     2     2     3     ---   2     3     2     ---    ---    2      3      3
  ----------------------------------------------------------------------------------------------

**Overall attainment** *(Direct 80% + Indirect/Feedback 20% --- to be
filled after SEE)*:

  -----------------------------------------------------------------------
                    Internal          External          Grand total
                                                        (80% + 20%)
  ----------------- ----------------- ----------------- -----------------
  CO attainment                                         

  PO attainment                                         

  PSO attainment                                        
  -----------------------------------------------------------------------

**Minimum level for PO attainment:** 50%--60%

## 20. Course completion summary 🟢

*(To be filled during and after delivery)*

  -----------------------------------------------------------------------
  Unit              Planned date      Completion date   Remarks
  ----------------- ----------------- ----------------- -----------------
  1                 ‹...›                               

  2                 ‹...›                               

  3                 ‹...›                               

  4                 ‹...›                               
  -----------------------------------------------------------------------

## 21. 🔵 Faculty reflection --- dual-level health check

*(To be filled at course close)*

-   Did the awareness floor genuinely protect placement-readiness for
    the weakest students? ‹...›

-   Was the advanced ceiling reached by roughly the expected share, or
    did it collapse / go unassessed? ‹...›

-   One change to the awareness/advanced split for next offering: ‹...›

**Signatures**

Course Faculty (digital signature) --- Sindhu P. Menon HoD / Director
(digital signature) --- Dr. Sarvamangala D R

## 22. 🔵 Implementation strategy --- Merrill\'s First Principles

Learning activities in §11 are structured around **Merrill\'s First
Principles of Instruction** --- knowledge is best built when learners
move through a problem-centred cycle of five phases.

**Merrill\'s five phases:**

  -----------------------------------------------------------------------
  Phase                   What it means           Typical activity in
                                                  this course
  ----------------------- ----------------------- -----------------------
  **Problem /             Anchor learning in a    Titanic survival (U1),
  Task-centred**          real-world problem the  House Price prediction
                          student will solve      (U2), Disease
                                                  prediction (U3),
                                                  Customer segmentation
                                                  (U4)

  **Activation**          Activate prior          Lecture + demonstration
                          knowledge before new    linking prior concepts
                          content                 (Python skills,
                                                  probability,
                                                  statistics)

  **Demonstration**       Show, don\'t just tell  Live Python demo,
                          --- worked examples     algorithm walkthrough,
                                                  numerical example on
                                                  board

  **Application**         Learner practises with  Tutorial problems, lab
                          feedback                exercises, Scikit-Learn
                                                  implementations

  **Integration**         Learner transfers skill Mini-project,
                          to own context          comparative analysis
                                                  reports, novel-domain
                                                  stretch problems
  -----------------------------------------------------------------------

**Design rule:** all five phases appear across each unit; Advanced-level
activities appear in Application and Integration sessions, ensuring the
ceiling is taught (Sessions 9, 11, 16, 22, 27, 28, 36, 43, 44, 52, 56,
57, 62--65) not merely assessed.

### 22.1 Phase-coverage check 🔵

  -----------------------------------------------------------------------
  Check                               Entry
  ----------------------------------- -----------------------------------
  All five Merrill phases used at     Yes --- see §11 session table; each
  least once per unit                 unit opens with Problem-centred +
                                      Activation and closes with
                                      Integration

  §11 sessions using Activation =     S.01, S.03, S.08, S.17, S.29, S.31,
  **lecture + demonstration**         S.45, S.49, S.51

  §11 sessions delivering             S.09, S.11, S.16, S.22, S.27, S.28,
  **Advanced-level** activities       S.36, S.43, S.44, S.52, S.56, S.57,
                                      S.62, S.63, S.64, S.65

  ✅ Ceiling taught (≥ 1 Adv activity **Yes** --- Units 1--4 each contain
  per unit, not only assessed)        at least 2 Advanced-level sessions
                                      before any assessment
  -----------------------------------------------------------------------
