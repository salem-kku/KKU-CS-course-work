# Teaching course work
```mermaid
graph BT;
    %% Eighth Year - Final Training
    CT(4882CCS-8 Cooperative Training) --> CP(0401MHR-4 Career Preparation Skills);

    %% Seventh Year
    CP --> PROJ(4381CCS-3 Project);
    CP --> CON6(Concentration Course 6);
    CP --> CON5(Concentration Course 5);
    CP --> CON4(Concentration Course 4);
    PROJ --> SPM(3343CCS-3 Software Project Management);
    CP --> COMP(4327CCS-3 Compilers);
    CP --> IOT(4342CE-3 Internet of Things);
    
    %% Sixth Year
    SPM --> SE(2341CCS-3 Software Engineering);
    COMP --> AP(2314CCS-3 Advanced Programming);
    IOT --> SEC(3362CCS-3 Computer & Network Security);
    AP --> WD(3342CCS-3 Web Engineering);
    DS --> ALG(3332CCS-3 Design & Analysis of Algorithms);
    OS --> PD(3325CCS-3 Parallel & Distributed Computing);

    %% Fifth Year
    TI(3226CCS-2 Technological Innovation);
    AI(3251CCS-2 Artificial Intelligence) --> DS;
    ML(3352CCS-3 Machine Learning) --> PROB(0384MATH-3 Probability & Statistics);
    SEC --> CN(2461CCS-4 Computer Networks);
    OOP(2413CCS-4 Object-Oriented Programming) --> GD(3371CCS-3 Game Design & Development);
    Free(Free Course);

    %% Fourth Year
    DS(2431CCS-4 Data Structure & Algorithms) --> OOP;
    OS(2323CCS-3 Operating Systems) --> COA(2321CCS-3 Computer Organization & Architecture);
    SE --> OOP;
    AP --> OOP;
    ARAB(0221ARAB-2 Arabic Language Skills);
    OR(2224CCS-2 Operations Research);

    %% Third Year
    VOL(0291VOLN-2 Volunteering Skills);
    LA(0383MATH-3 Linear Algebra);
    DM(2222CCS-2 Discrete Mathematics) --> PROB;
    SC(2261CIS-2 Science Communication);
    COA --> PS(1311CCS-3 Problem Solving & Programming);
    DBMS(2321CIS-3 Database Management Systems);
    OOP --> IP(1312CCS-3 Introduction to Programming);

    %% Second Year
    ENG1(0522ENG-5 Intensive English Program) --> ENG2(0292ENG-2 Specialized English Language);
    MATH1(0381MATH-3 Calculus 1) --> MATH2(0382MATH-3 Calculus 2);
    PROB;
    PHYS(1308PHYS-3 Principles of Physics);
    CHEM(1309CHEM-3 Chemistry);
    PS --> IP;
    ETH(4256CIS-2 Computing Ethics);

    %% First Year - No Prerequisites
    MOD(0212CTR-2 Moderation);
    MATH1;
    ENG1;
    PS;
