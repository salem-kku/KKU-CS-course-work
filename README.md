# Teaching course work
```mermaid
graph TD;
    %% First Year
    MOD(Moderation) -->|None| ENG1(Intensive English Program)
    MATH1(Calculus 1) -->|None| MATH2(Calculus 2)
    ENG1 -->|None| ENG2(Specialized English Language)
    PS(Problem Solving & Programming) -->|None| IP(Introduction to Programming)

    %% Second Year
    MATH2 -->|S| PROB(Probability & Statistics)
    PS -->|S| IP
    IP -->|S| OOP(Object-Oriented Programming)
    COA(Computer Organization & Architecture) -->|S| PS
    DBMS(Database Management Systems) -->|None| OOP
    OOP -->|S| DS(Data Structures & Algorithms)
    OOP -->|S| SE(Software Engineering)
    OS(Operating Systems) -->|S| COA
    CN(Computer Networks) -->|S| OOP

    %% Third Year
    AI(Artificial Intelligence) -->|S| DS
    ML(Machine Learning) -->|S| PROB
    WD(Web Engineering) -->|S| AP(Advanced Programming)
    SEC(Computer & Network Security) -->|S| CN
    PD(Parallel & Distributed Computing) -->|S| OS
    ALG(Design & Analysis of Algorithms) -->|S| DS
    SPM(Software Project Management) -->|S| SE

    %% Fourth Year
    CP(Career Preparation Skills) -->|None| CT(Cooperative Training)
    COMP(Compilers) -->|S| AP
    IOT(Internet of Things) -->|S| SEC
    PROJ(Project) -->|S| SPM

    %% Relations
    MATH1 -->|S| MATH2
    ENG1 -->|S| ENG2
    PS -->|S| IP
    IP -->|S| OOP
    OOP -->|S| DS
    OOP -->|S| SE
    DS -->|S| AI
    PROB -->|S| ML
    COA -->|S| OS
    OOP -->|S| CN
    OS -->|S| PD
    DS -->|S| ALG
    SE -->|S| SPM
    CN -->|S| SEC
    AP -->|S| WD
    AP -->|S| COMP
    SEC -->|S| IOT
    SPM -->|S| PROJ
    CP -->|S| CT
