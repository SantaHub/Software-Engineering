# SA
Course ID : SS ZG653

who needs an architect ; Martin Fowler

T1 : https://learning.oreilly.com/library/view/software-architecture-in/9780132942799/ch01.html


## RL 1.2

Stakeholders : beneficiaries of the application.

Software Architecture : 
    Structure  comprising of software elements and relationship among them. Interacting with patterns with their components and subsystems.

## RL 2.1

Kruchten 4+1 view :
    End user
    infrastructure team
    Architect/Integrator
    Development team
    + 1 => Use case
## CS2 

Quality Attributes 
ISO 25010 define QA as : 
    System Quality : Availability, Modifiability, Performance, Security, Testability, Usability
    Business Quality : Time to market, cost and benefit, project lifetime, targeted market, rollout schedule, Legacy integration.
    Quality of architecture : conceptual integrity, correctness, completeness, buildability.

Function Attributes : 
- Requirements specified by the stakeholders

Non Functional Attributes :
- Other qualities like Maintainability, stability, adaptability etc which makes the system acceptable.

Formula for calculating downtime. 
    Availability = 99.9% => 0.1% unavailable => (0.1/100)*365 = 0.365 days down in a year

Hot and Warm Standby :
    Hot Standby : the Standby system is constantly updated and Standby system quickly takes over on failing
    Warm Standby : The standby system is not constantly send heart beats. Warm system checks periodically and takes over if active server is down.

Throughput and Latency :
    Throughput : how many packets per time.
    Latency : time between request and response 

## Slides SA.pdf

Quality Attributes : 44
Quality Design Decisions : 51

Usability : 55
Usability tactics : 57
User Initiative and system response (cancel, undo, pause, font) : 58 
Task, system, user model : 59
Design Checklist : 61

Availability : 64
Availability tactics : 71
Reliability Metrics : 94

RL 5 :
    Modifiability : 103
    tactics ; 105
    Performance : 113
    Tactics : 117

RL6:
    - Security : 2
    - Security Tactics : 6
    - Detect attacks : 7
    - Testability : 19
    - Testability Tactics ; 23
    - Interoperatability : 35
RL7:
    - OODesign : 1
    - UML : 19
RL8 :
    - UML : 1
    - Agile : 13
    - CRC : 17
    - Unified Process : 24
    - Unified 5 steps : Architecture Activities, Feature driven design, Feature to architecture, Use case model, 
RL9 :
    - Introduction to patterns : 1
    - OO design principles : 6
    - Layering Pattern : 22
RL10 :
    - Pipe and filter pattern : 1
    - Blackboard architecture : 20
RL11:
    - Distributed systems : 1
RL12:
    - interactive systems
RL13 :
    - Adaptable systems
RL14:
    - Design patterns
RL15 :
    - Design Patterns, structural patterns, composite patterns
RL16:
    - Behaviour Pattern
RL17 :
    - Cloud computing paradigm
RL18:
    - Cloud computing architectural pattern
RL19:
    - Architecture and Requirements
    - Requirement document, business goal, stakeholders : 8
RL20 :
    - Sequence diagram
    - CC
    - documenting Behaviour : 46


## slides CS 

CDN : 103
Protect system from variation : 112
Rule engine : 114

QA : 127
ADD : 283
Judiciary system : 286

Layered Arch : 408
Techniques in layered arch : 414
Aspected oriented cross cutting : 429
Techniques Datalayer : 433
SSL : 449
Logging : 450

ATAM : 463

## SA All Ordered. pdf

Software Architecture : 11
Context Diagram : 13
CC view : 14
Deployment diagram : 15
Architecture & Design : 20
Decomposition diagram : 25
CC Diagram : 27
Deployemnt diagram : 32

Architecture Pattern
    Layered Pattern : 35
    pub-sub : 36
    Pipeline : 37

Quality Attributes : 67, 76
    sub char : 70
Availability tactics : 85
Performance tactics : 100
Modifiability tactics : 109
Security tactics : 183

Digital Signature and Certificate : 184
Interoperatability : 191
SOAP vs ReST : 194
Dimensions of Usability : 197
Testability tactics : 203

ASR : 267
Utility Tree : 268
interprocess communication mechanism : 335
Deployment view : 340

C4 Model : 373
Typical Layered Architecture : 408
    Presentation layer Techniques : 414
    Client side caching vs server side caching : 415
    Memcached : 416
    Business Layer : 422
    stateless and stateful sessions : 427
    Aspect oriented design for cross cutting concerns : 429
    Data layer : 433
    Services layer : 437
    SSL : 449
    IPsec : 452
    session management : 453


ATAM : trade off analysis :
ATAM Participants : 505

Architecture and Testing : 522
Phases of architecture reconstruction : 545

List of architecture patterns : 557
Layered pattern : for separating areas of concern : 558
Pub-sub model : to notify dynamic subscribers : 565
Pipe and filter : to apply multiple transformations in Sequence : 578
Model View Controller : 589
SOA service oriented architecture : 595
Micro service architecture : 606
SOA vs Micro service : 618
Client-server pattern : 625
Map Reduce pattern : 637
multi-tier pattern : 642

OSI Layers : 657
Load Balancer : 658

Integration stratergies : 681
    File transfer : 683
    shared database : 685
    Remote method invocation : 686
    serialization : 687
    Remote method invocation : 
    Messaging : 689
    TCP/IP sockets : 691
    EBS : enterprise service bus : 699

Serverless : 707
Container : 724
Caching : 732
Business Process Management : 740
SSL : 741
Logging : 742

Architecturing for cloud : 750
multi-tenant architecture : 753
Mobile application : 791
Mobile application architecture : 807
NoSQL DB : 839
Graph db : 860
Stream processing : 871

Failure Management : 882
Network partitioning : 886
Best practice to manage failure : 903

Blockchain : 914
Big data : 932
Use of big data : 945
Hadoop : 949
Map Reduce Pattern : 953
Apache Spark : 964
Real time analytics : 967
IOT : 973

Security : 975
    TLS : 980
    OpenID : 984
    OAuth : 988
    LDAP : 991
    IAM : 993
    Firewall : 995
    De-militarized zones : 996
    Business process management : 1001
    SSL : 1002
    Logging : 1003
    Async operation : 1004

Cost benefit analysis : 1011
    Utility value : 1017
    CBAM : 1034

Machine Learning : 1053
