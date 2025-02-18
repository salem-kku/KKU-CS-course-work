# Teaching course work
```mermaid
graph TB;
    %% First Semester - No Prerequisites
    MOD(0212CTR-2 Moderation);
    MATH1(0381MATH-3 Calculus 1);
    ENG1(0522ENG-5	Intensive English Program) -->|None|;
    PS(1311CCS-3 Problem Solving & Programming) -->|None|;
    
    %% Spacing Node to Improve Readability
    SPACE1(( )) --> MOD;

    %% Second Year
    ENG1 --> ENG2(0292ENG-2 Specialized English Language);
    MATH1 --> MATH2(0382MATH-3 Calculus 2);
    PROB(0384MATH-3 Probability & Statistics);
    PHYS(1308PHYS-3 Principles of Physics);
    CHEM(1309CHEM-3 Chemistry);
    PS --> IP(1312CCS-3 Introduction to Programming);
    ETH(4256CIS-2 Computing Ethics);

    %% Spacing Node
    SPACE2(( )) --> PROB;

    %% Third Year
    VOL(0291VOLN-2 Volunteering Skills);
    LA(0383MATH-3 Linear Algebra);
    DM(2222CCS-2 Discrete Mathematics) --> PROB;
    SC(2261CIS-2 Science Communication);
    COA(2321CCS-3 Computer Organization & Architecture) --> PS;
    DBMS(2321CIS-3 Database Management Systems);
    OOP(2413CCS-4 Object-Oriented Programming) --> IP;

    %% Spacing Node
    SPACE3(( )) --> OOP;

    %% Fourth Year
    ARAB(0221ARAB-2 Arabic Language Skills);
    OR(2224CCS-2 Operations Research);
    AP(2314CCS-3 Advanced Programming) --> OOP;
    OS(2323CCS-3 Operating Systems) --> COA;
    SE(2341CCS-3 Software Engineering) --> OOP;
    DS(2431CCS-4 Data Structure & Algorithms) --> OOP;
    CN(2461CCS-4 Computer Networks) --> OOP;

    %% Fifth Year
    TI(3226CCS-2 Technological Innovation);
    AI(3251CCS-2 Artificial Intelligence) --> DS;
    WD(3342CCS-3 Web Engineering) --> AP;
    ML(3352CCS-3 Machine Learning) --> PROB;
    SEC(3362CCS-3 Computer & Network Security) --> CN;
    GD(3371CCS-3 Game Design & Development) --> OOP;
    Free(Free Course);

    %% Spacing Node
    SPACE4(( )) --> ML;

    %% Sixth Year
    PD(3325CCS-3 Parallel & Distributed Computing) --> OS;
    ALG(3332CCS-3 Design & Analysis of Algorithms) --> DS;
    SPM(3343CCS-3 Software Project Management) --> SE;
    CON1(Concentration Course 1);
    CON2(Concentration Course 2);
    CON3(Concentration Course 3);

    %% Spacing Node
    SPACE5(( )) --> SPM;

    %% Seventh Year
    CP(0401MHR-4 Career Preparation Skills);
    COMP(4327CCS-3 Compilers) --> AP;
    IOT(4342CE-3 Internet of Things) --> SEC;
    PROJ(4381CCS-3 Project) --> SPM;
    CON4(Concentration Course 4);
    CON5(Concentration Course 5);
    CON6(Concentration Course 6);

    %% Eighth Year
    CT(4882CCS-8 Cooperative Training) --> CP;
