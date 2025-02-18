# Teaching course work
```mermaid
graph TD;
    %% First Year - No Prerequisites
    MOD(0212CTR-2 Moderation) -->|None| 
    MATH1(0381MATH-3 Calculus 1) -->|None| 
    ENG1(0522ENG-5 Intensive English Program) -->|None|
    PS(1311CCS-3 Problem Solving & Programming) -->|None| 

    %% Second Year
    ENG1 -->|S| ENG2(0292ENG-2 Specialized English Language)
    MATH1 -->|S| MATH2(0382MATH-3 Calculus 2)
    PROB(0384MATH-3 Probability & Statistics) -->|None|
    PHYS(1308PHYS-3 Principles of Physics) -->|None|
    CHEM(1309CHEM-3 Chemistry) -->|None|
    PS -->|S| IP(1312CCS-3 Introduction to Programming)
    ETH(4256CIS-2 Computing Ethics) -->|None|

    %% Third Year
    VOL(0291VOLN-2 Volunteering Skills) -->|None|
    LA(0383MATH-3 Linear Algebra) -->|None|
    DM(2222CCS-2 Discrete Mathematics) -->|S| PROB
    SC(2261CIS-2 Science Communication) -->|None|
    COA(2321CCS-3 Computer Organization & Architecture) -->|S| PS
    DBMS(2321CIS-3 Database Management Systems) -->|None|
    OOP(2413CCS-4 Object-Oriented Programming) -->|S| IP

    %% Fourth Year
    ARAB(0221ARAB-2 Arabic Language Skills) -->|None|
    OR(2224CCS-2 Operations Research) -->|None|
    AP(2314CCS-3 Advanced Programming) -->|S| OOP
    OS(2323CCS-3 Operating Systems) -->|S| COA
    SE(2341CCS-3 Software Engineering) -->|S| OOP
    DS(2431CCS-4 Data Structure & Algorithms) -->|S| OOP
    CN(2461CCS-4 Computer Networks) -->|S| OOP

    %% Fifth Year
    TI(3226CCS-2 Technological Innovation) -->|None|
    AI(3251CCS-2 Artificial Intelligence) -->|S| DS
    WD(3342CCS-3 Web Engineering) -->|S| AP
    ML(3352CCS-3 Machine Learning) -->|S| PROB
    SEC(3362CCS-3 Computer & Network Security) -->|S| CN
    GD(3371CCS-3 Game Design & Development) -->|S| OOP
    Free(Free Course) -->|None|

    %% Sixth Year
    PD(3325CCS-3 Parallel & Distributed Computing) -->|S| OS
    ALG(3332CCS-3 Design & Analysis of Algorithms) -->|S| DS
    SPM(3343CCS-3 Software Project Management) -->|S| SE
    CON1(Concentration Course 1) -->|None|
    CON2(Concentration Course 2) -->|None|
    CON3(Concentration Course 3) -->|None|

    %% Seventh Year
    CP(0401MHR-4 Career Preparation Skills) -->|None|
    COMP(4327CCS-3 Compilers) -->|S| AP
    IOT(4342CE-3 Internet of Things) -->|S| SEC
    PROJ(4381CCS-3 Project) -->|S| SPM
    CON4(Concentration Course 4) -->|None|
    CON5(Concentration Course 5) -->|None|
    CON6(Concentration Course 6) -->|None|

    %% Eighth Year
    CT(4882CCS-8 Cooperative Training) -->|S| CP
