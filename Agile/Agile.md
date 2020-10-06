# Agile
Course ID : SE ZG544

T1 : Agile and Iterative Development: A Manager's Guide
: <https://learning.oreilly.com/library/view/agile-and-iterative/0131111558/>

T2 : Agile Project Management For Dummies, 2nd Edition : <https://learning.oreilly.com/library/view/agile-project-management/9781119405696/>

## Module 1

Ref : T2. Chapter 1

### LS 1.1 : Traditional Software Development Practices

Waterfall Phases:
    - Requirement analysis
    - Design
    - Development
    - Integration
    - Testing
    - Deployment
    Has a linear flow, though Royce, in his paper had suggested the development and testing phases to be iterative.

### LS 1.2 : Need for Agile Methods

Standish Group Research :  

- Project Success  
  - 11% projects succeeded
  - 29% projects failed outright
  - 60% projects challenged constrains
- Feature Usage : Pie Chart
  - 7% Always
  - 13% Often
  - 16% Sometime
  - 19% Rarely
  - 45% Never

### LS 1.3 : Benefits of Agile Methods

Agile                          : Traditional  

- Individuals and interactions : processes and tools
- Working software             : comprehensive documentation
- Customer collaboration       : contract negotiation
- Responding to change         : following a plan

Empirical Control Method based on iterative adoption, making decision based on requirements :

- Unfettered Transparency
- Frequent inspection
- immediate adaption

Project management benefits :

- Project success rate : Problems are identified early.
- Scope creep : developed only when needed
- Continuous change : Kaizen

## Module 2

### LS 2.1 Iterative and incremental approach

T1 : Key motivation for iterative development

- Early risk mitigation and discovery
- Early change adoption
- Decomposes complexity
- Builds customer and team confidence early
- Early market capture
- predictability
- Time boxing (IMP)

### LS 2.2 Popular Agile Methods

T2 : The big three

Lean Values:

- Eliminate waste : Doing only whats barely sufficient
- Amplify learning : Failures are approached with learning mindset
- Deliver as late as possible : Keep your open for adaption till last moment
- Deliver as fast as possible : Manage workflows than schedules.
- Empower the team : invest in team and their tools
- Build quality in : setup quality control to the workflows
- See the whole : Identify bottlenecks and think long term

Lean Kanban :

- Visualize : visualize workflow on white board and identify the bottlenecks
- Limit work in progress (WIP) : the lesser items you work on, the faster you finish them.
- Manage flow : Manage the tasks in progress to developer ratio

Scrum :

- Daily scrum : organize the day by reviewing what had been done yesterday and work planned for the day
- Sprint : constant inspection on progress towards release goal
- sprint end : assess performance and plan adaptation

Scrum roles :

Product owner : Represent and speaks for the business needs of the project
Development team : multi-skilled team capable of doing multiple jobs on the project
Scrum master : Protects the team from org distractions, blockers and ensure scrum played properly.

Extreme Programming principles:

- Coding is the core activity
- XP teams do lots of testing
- communication between customer and programmer is direct
- Overall design considered for refactoring to improve reusability, simplicity and maintainability

## Module 3

### LS 3.1 Vision, principle and manifesto

Agile Values :

- individual and interaction
- Customer collaboration
- Responding to change
- usable software 

Refer T1 3. It has the differentiate box.

12 Agile principles :

- Satisfy customer
- embrace change
- frequent Delivery
- Customer collaboration
- Support and trust
- Face-to-Face communication
- Working Software
- Sustainable Phases
- Technical Excellence
- keep it simple
- self Organization
- inspect and adapt


# CS 3

Motivated and Talented Individuals :
  5th agile principle states Build project around motivated individuals.

  Maslow's hierarchy of needs : Once basic needs are met out behavior will be driven by meeting higher-level needs.

# CS 4 M4 

CS 4 is waste of time. Checking T1 chap 7,8

### Scrum

- self - directed and self-organizing team
- no external addition of work to an iteration, once chosen
- daily stand-up meeting
- usually 30 calender days iteration
- demo to external stakeholders at end of each iteration
- each iteration, client-driven adaptive planning

Life cycle :

- planning : vision, expectations and funding
- Staging : more requirements, prioritize enough for 1st iteration
- Development : implement system for the 1st release
- Release : operational Deployment

Workproducts, roles and Practices :
  - Requirement : Product and release backlog
  - Project Management : Backlog graph, sprint backlog, product & release backlog.

Roles :
  Customer : Product owner :
    - create and prioritize product backlog
  Development : Scrum Team :
    - work on sprint backlog
  Management : Scrum Master :
    - 50% developer, not just management
    - knows and reinforces the project and iteration vision and goals
    - conducts sprint review (demos)
  
Practices : 
  Requirements :
    - pre-game planning, sprint planning, sprint review.
  Design :
    - high level design phase
  Test and verification :
    - sprint review
  Project Management :
    - daily scrum
    - sprint, sprint planning
  Configuration and change management environment:
    - Daily Build

Values :
  Commitment : defined goal for an iteration is set by the scrum team
  Focus : Team focus on stated goals and master removes blocks and resources, also review and brief result of iteration
  Openness : Product backlog graph, velocity and priorities are open to the team.
  Respect : Each member is respected and adopts the attitude of solving individual problems through group exploration.
  Courage : Team has the courage to take responsibility for self-direction and self-management

# CS 4

### Extreme Programming 

Emphasize collaboration, quick and early software creation, and skillful development practices.
Founded on 4 values :
  - communication
  - simplicity
  - feedback
  - courage
Has low ceremony scale, with feature summarized story cards.

Practices :
The planning game :
  - User -stories
  - exploration phase
  - commitment phase
  - Steering phase
  Refactoring, pair programming, collective ownership. CI, CD, 40 hr week, on site customer, coding standards, informative workspace.

### Test driven development

Tests are defined before coding.
unit test code -> code -> test -> refactor.

# CS 5

Lean : eliminate waste and maximize flow. It employs Value stream mapping, which map what activities provide the value.
Lean Time : time from work requested to delivered.
Cycle/Process/Throughput time : time spend working on the solution.

7 principles :
  Eliminate waste :
    - Unnecessary code
    - Starting more than can be completed.
  Build Quality :
    - Pair programming
    - TDD
    - Reduce context switches
    - Automation
  Create knowledge :
    - Pair programming
    - training
  Defer commitment :
    - dont make decision/commit until last minute to keep options open
  Deliver Fast :
    - build iteratively
    - dont over engineer
  Respect People :
    - communicate proactively and encourage healthy conflict
  Optimize code :
    - value steam mapping
    - system thinking
  
Agile Requirements :

  Requirement Gathering :
    - User stories are the main way to track information, is fundamental unit of product development in agile and enable rapid iteration.
      - Scenario
      - Acceptance criteria
      - INVEST : independent , negotiable, valuable, estimatable, small and testable.
      3C's : card conversation and Confirmation.