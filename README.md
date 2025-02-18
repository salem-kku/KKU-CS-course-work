```mermaid
flowchart TB

  %% === First Semester ===
  subgraph Sem1[**Semester 1**]
    direction TB
    PS(1311CCS-3 Problem Solving & Programming)
    MATH1(0381MATH-3 Calculus 1)
    ENG1(0522ENG-5 Intensive English Program)
    MOD(0212CTR-2 Moderation)
  end

  X_Spacer1(( ))  --> Sem2  %% Creates spacing

  %% === Second Semester ===
  subgraph Sem2[**Semester 2**]
    direction TB
    IP(1312CCS-3 Introduction to Programming)
    PROB(0384MATH-3 Probability & Statistics)
    MATH2(0382MATH-3 Calculus 2)
    ENG2(0292ENG-2 Specialized English Language)
    PHYS(1308PHYS-3 Principles of Physics)
    CHEM(1309CHEM-3 Chemistry)
    ETH(4256CIS-2 Computing Ethics)
  end

  X_Spacer2(( ))  --> Sem3

  %% === Third Semester ===
  subgraph Sem3[**Semester 3**]
    direction TB
    OOP(2413CCS-4 Object-Oriented Programming)
    DBMS(2321CIS-3 Database Management Systems)
    COA(2321CCS-3 Computer Organization & Architecture)
    DM(2222CCS-2 Discrete Mathematics)
    SC(2261CIS-2 Science Communication)
    LA(0383MATH-3 Linear Algebra)
    VOL(0291VOLN-2 Volunteering Skills)
  end

  X_Spacer3(( ))  --> Sem4

  %% === Fourth Semester ===
  subgraph Sem4[**Semester 4**]
    direction TB
    DS(2431CCS-4 Data Structures & Algorithms)
    OS(2323CCS-3 Operating Systems)
    SE(2341CCS-3 Software Engineering)
    AP(2314CCS-3 Advanced Programming)
    OR(2224CCS-2 Operations Research)
    ARAB(0221ARAB-2 Arabic Language Skills)
  end

  X_Spacer4(( ))  --> Sem5

  %% === Fifth Semester ===
  subgraph Sem5[**Semester 5**]
    direction TB
    CN(2461CCS-4 Computer Networks)
    TI(3226CCS-2 Technological Innovation)
    AI(3251CCS-2 Artificial Intelligence)
    ML(3352CCS-3 Machine Learning)
    SEC(3362CCS-3 Computer & Network Security)
    GD(3371CCS-3 Game Design & Development)
    WD(3342CCS-3 Web Engineering)
  end

  X_Spacer5(( ))  --> Sem6

  %% === Sixth Semester ===
  subgraph Sem6[**Semester 6**]
    direction TB
    PD(3325CCS-3 Parallel & Distributed Computing)
    ALG(3332CCS-3 Design & Analysis of Algorithms)
    SPM(3343CCS-3 Software Project Management)
    CON1(Concentration Course 1)
    CON2(Concentration Course 2)
    CON3(Concentration Course 3)
  end

  X_Spacer6(( ))  --> Sem7

  %% === Seventh Semester ===
  subgraph Sem7[**Semester 7**]
    direction TB
    CP(0401MHR-4 Career Preparation Skills)
    COMP(4327CCS-3 Compilers)
    IOT(4342CE-3 Internet of Things)
    PROJ(4381CCS-3 Graduation Project)
    CON4(Concentration Course 4)
    CON5(Concentration Course 5)
    CON6(Concentration Course 6)
  end

  X_Spacer7(( ))  --> Sem8

  %% === Eighth Semester (Final Training) ===
  subgraph Sem8[**Semester 8**]
    direction TB
    CT(4882CCS-8 Cooperative Training)
  end

  %% === Prerequisite Dependencies ===
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
