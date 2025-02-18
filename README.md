```mermaid
flowchart TB

  %% === First Semester ===
  subgraph Sem1[Semester 1]
    direction TB
    PS(1311CCS-3 Problem Solving & Programming) --> SP1[" "]
    MATH1(0381MATH-3 Calculus 1) --> SP2[" "]
    ENG1(0522ENG-5 Intensive English Program) --> SP3[" "]
    MOD(0212CTR-2 Moderation)
  end

  Sem1 -->|Next Semester| Sem2

  %% === Second Semester ===
  subgraph Sem2[Semester 2]
    direction TB
    IP(1312CCS-3 Introduction to Programming) --> SP4[" "]
    PROB(0384MATH-3 Probability & Statistics) --> SP5[" "]
    MATH2(0382MATH-3 Calculus 2) --> SP6[" "]
    ENG2(0292ENG-2 Specialized English Language) --> SP7[" "]
    PHYS(1308PHYS-3 Principles of Physics) --> SP8[" "]
    CHEM(1309CHEM-3 Chemistry) --> SP9[" "]
    ETH(4256CIS-2 Computing Ethics)
  end

  Sem2 -->|Next Semester| Sem3

  %% === Third Semester ===
  subgraph Sem3[Semester 3]
    direction TB
    OOP(2413CCS-4 Object-Oriented Programming) --> SP10[" "]
    DBMS(2321CIS-3 Database Management Systems) --> SP11[" "]
    COA(2321CCS-3 Computer Organization & Architecture) --> SP12[" "]
    DM(2222CCS-2 Discrete Mathematics) --> SP13[" "]
    SC(2261CIS-2 Science Communication) --> SP14[" "]
    LA(0383MATH-3 Linear Algebra) --> SP15[" "]
    VOL(0291VOLN-2 Volunteering Skills)
  end

  Sem3 -->|Next Semester| Sem4

  %% === Fourth Semester ===
  subgraph Sem4[Semester 4]
    direction TB
    DS(2431CCS-4 Data Structures & Algorithms) --> SP16[" "]
    OS(2323CCS-3 Operating Systems) --> SP17[" "]
    SE(2341CCS-3 Software Engineering) --> SP18[" "]
    AP(2314CCS-3 Advanced Programming) --> SP19[" "]
    OR(2224CCS-2 Operations Research) --> SP20[" "]
    ARAB(0221ARAB-2 Arabic Language Skills)
  end

  Sem4 -->|Next Semester| Sem5

  %% === Fifth Semester ===
  subgraph Sem5[Semester 5]
    direction TB
    CN(2461CCS-4 Computer Networks) --> SP21[" "]
    TI(3226CCS-2 Technological Innovation) --> SP22[" "]
    AI(3251CCS-2 Artificial Intelligence) --> SP23[" "]
    ML(3352CCS-3 Machine Learning) --> SP24[" "]
    SEC(3362CCS-3 Computer & Network Security) --> SP25[" "]
    GD(3371CCS-3 Game Design & Development) --> SP26[" "]
    WD(3342CCS-3 Web Engineering)
  end

  Sem5 -->|Next Semester| Sem6

  %% === Sixth Semester ===
  subgraph Sem6[Semester 6]
    direction TB
    PD(3325CCS-3 Parallel & Distributed Computing) --> SP27[" "]
    ALG(3332CCS-3 Design & Analysis of Algorithms) --> SP28[" "]
    SPM(3343CCS-3 Software Project Management) --> SP29[" "]
    CON1(Concentration Course 1) --> SP30[" "]
    CON2(Concentration Course 2) --> SP31[" "]
    CON3(Concentration Course 3)
  end

  Sem6 -->|Next Semester| Sem7

  %% === Seventh Semester ===
  subgraph Sem7[Semester 7]
    direction TB
    CP(0401MHR-4 Career Preparation Skills) --> SP32[" "]
    COMP(4327CCS-3 Compilers) --> SP33[" "]
    IOT(4342CE-3 Internet of Things) --> SP34[" "]
    PROJ(4381CCS-3 Graduation Project) --> SP35[" "]
    CON4(Concentration Course 4) --> SP36[" "]
    CON5(Concentration Course 5) --> SP37[" "]
    CON6(Concentration Course 6)
  end

  Sem7 -->|Final Semester| Sem8

  %% === Eighth Semester (Final Training) ===
  subgraph Sem8[Semester 8]
    direction TB
    CT(4882CCS-8 Cooperative Training)
  end

  %% === Prerequisite Dependencies (Thicker Arrows) ===
  linkStyle default stroke:#000,stroke-width:2px
  PS --> IP
  IP --> OOP
  OOP --> DS
  DS --> AI
  OOP --> SE
  OOP --> AP
  COA --> OS
  OS --> PD
  CN --> SEC
  SE --> SPM
  AP --> WD
  AI --> ML
  PROJ --> SPM
  CP --> PROJ
  COMP --> AP
  IOT --> SEC
  CT --> CP

  %% === Styling for Larger Titles ===
  style Sem1 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
  style Sem2 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
  style Sem3 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
  style Sem4 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
  style Sem5 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
  style Sem6 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
  style Sem7 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
  style Sem8 fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:18px
