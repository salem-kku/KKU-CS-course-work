```mermaid
flowchart TB

  %% === First Semester ===
  PS(Problem Solving & Programming) --> IP(Introduction to Programming)
  MATH1(Calculus 1)
  ENG1(Intensive English)

  subgraph STANDALONE1[Standalone Courses]
    MOD(Moderation)
  end

  %% === Second Semester ===
  IP --> OOP(Object-Oriented Programming)
  PROB(Probability & Statistics)
  MATH2(Calculus 2)
  ENG2(Specialized English)
  PHYS(Principles of Physics)
  CHEM(Chemistry)
  ETH(Computing Ethics)

  %% === Third Semester ===
  OOP --> DS(Data Structures & Algorithms)
  DBMS(Database Systems)
  COA(Computer Organization & Architecture)
  DM(Discrete Mathematics)
  SC(Science Communication)
  LA(Linear Algebra)

  subgraph STANDALONE2[Standalone Courses]
    VOL(Volunteering Skills)
  end

  %% === Fourth Semester ===
  DS --> ALG(Design & Analysis of Algorithms)
  OS(Operating Systems)
  SE(Software Engineering)
  AP(Advanced Programming)
  OR(Operations Research)

  subgraph STANDALONE3[Standalone Courses]
    ARAB(Arabic Language Skills)
  end

  %% === Fifth Semester ===
  CN(Computer Networks)
  TI(Technological Innovation)
  AI(Artificial Intelligence) --> ML(Machine Learning)
  SEC(Computer Security)
  GD(Game Development)
  WD(Web Development)

  %% === Sixth Semester ===
  PD(Parallel & Distributed Computing)
  SPM(Software Project Management)
  CON1(Concentration Course 1)
  CON2(Concentration Course 2)
  CON3(Concentration Course 3)

  %% === Seventh Semester ===
  COMP(Compilers)
  IOT(Internet of Things)
  PROJ(Graduation Project) --> SPM
  CON4(Concentration Course 4)
  CON5(Concentration Course 5)
  CON6(Concentration Course 6)

  subgraph STANDALONE4[Standalone Courses]
    CP(Career Preparation)
  end

  %% === Eighth Semester ===
  subgraph STANDALONE5[Final Training]
    CT(Cooperative Training) --> CP
  end

  %% === Prerequisite Dependencies ===
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

  %% === Styling for Readability ===
  style STANDALONE1 fill:#f9f9f9,stroke:#333,stroke-width:2px,font-size:18px
  style STANDALONE2 fill:#f9f9f9,stroke:#333,stroke-width:2px,font-size:18px
  style STANDALONE3 fill:#f9f9f9,stroke:#333,stroke-width:2px,font-size:18px
  style STANDALONE4 fill:#f9f9f9,stroke:#333,stroke-width:2px,font-size:18px
  style STANDALONE5 fill:#ffdd57,stroke:#333,stroke-width:2px,font-size:18px
