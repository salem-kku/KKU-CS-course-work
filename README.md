```mermaid
flowchart TB

  %% === First Semester ===
  PS(Problem Solving & Programming) --> IP(Introduction to Programming)
  MATH1(Calculus 1) --- ENG1(Intensive English)
  MOD(Moderation)

  %% === Second Semester ===
  IP --> OOP(Object-Oriented Programming)
  PROB(Probability & Statistics) --- MATH2(Calculus 2)
  ENG2(Specialized English) --- PHYS(Principles of Physics)
  CHEM(Chemistry) --- ETH(Computing Ethics)

  %% === Third Semester ===
  OOP --> DS(Data Structures & Algorithms)
  DBMS(Database Systems) --- COA(Computer Organization & Architecture)
  DM(Discrete Mathematics) --- SC(Science Communication)
  LA(Linear Algebra) --- VOL(Volunteering Skills)

  %% === Fourth Semester ===
  DS --> ALG(Design & Analysis of Algorithms)
  OS(Operating Systems) --- SE(Software Engineering)
  AP(Advanced Programming) --- OR(Operations Research)
  ARAB(Arabic Language Skills)

  %% === Fifth Semester ===
  CN(Computer Networks) --- TI(Technological Innovation)
  AI(Artificial Intelligence) --> ML(Machine Learning)
  SEC(Computer Security) --- GD(Game Development)
  WD(Web Development)

  %% === Sixth Semester ===
  PD(Parallel & Distributed Computing) --- SPM(Software Project Management)
  CON1(Concentration Course 1) --- CON2(Concentration Course 2)
  CON3(Concentration Course 3)

  %% === Seventh Semester ===
  CP(Career Preparation)
  COMP(Compilers) --- IOT(Internet of Things)
  PROJ(Graduation Project) --> SPM
  CON4(Concentration Course 4) --- CON5(Concentration Course 5)
  CON6(Concentration Course 6)

  %% === Eighth Semester ===
  CT(Cooperative Training) --> CP

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
  style PS fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:16px
  style IP fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:16px
  style OOP fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:16px
  style DS fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:16px
  style AI fill:#f4f4f4,stroke:#333,stroke-width:2px,font-size:16px
  style CT fill:#ffdd57,stroke:#333,stroke-width:2px,font-size:16px
