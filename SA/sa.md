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
ISO 25010 define QA as : functional Suitability, Reliability, Performance Efficiency, Usability, Maintainability, Security, Compatibility, Portability.
     Function Attributes : 
        - Requirements specified by the stakeholders

    Non Functional Attributes :
        - Other qualities like Maintainability, stability, adaptability etc which makes the system acceptable.

Formula for calculating downtime. 
    Availability = 99.9% => 0.1% unavailable => (0.1/100)*365 = 0.365 days down in a year

Hot and Warm Standby :
    Hot Standby : the Standby system is constantly updated and Standby system quickly takes over on failing
    Warm Standby : The standby system is not constantly updated but takes over once the system stop processing events.

Throughput and Latency :
    Throughput : how many packets per time.
    Latency : time between request and response 

## Slides

Quality Attributes : 44
Quality Design Decisions : 51
Usability : 55
User Initiative and system response (cancel, undo, pause, font) : 58 
Task, system, user model : 59
Design Checklist : 61

Availability : 64
Availability tactics : 71
Reliability Metrics : 94

Modifiability : 103
tactics ; 105

Performance : 113
Tactics : 117
