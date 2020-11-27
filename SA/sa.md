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

## Combined slides

Software Architecture : 11
