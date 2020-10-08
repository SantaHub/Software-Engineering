# SQM

Books 

## CS 1

Quality : Quality is how well a system functions, it varies with perspective.
    Functional view :
        - how well the functions works
        - developers or users view - Role based perspective
        - Quality at each requirement
    Non Functional view
        - Business view
        - How good the product attract revenue.
        - Align with Quality Attributes :
            - reliability
            - availability
            - Affordability
            - usability
            - maintainability
            - Portability
            - Testability

David Garwin's 5 views of Quality :
    - Transcendental View : Immediately recognizable but cannot explicitly define.
    - Users view : product fulfills user's view
    - Manufacturer's view : conforms or exceeds specification
    - Product view : compared with general product standard
    - value-based view : how much valuable it is for the customer.

## CS 2

Software Quality : An effective software process applied in a manner that creates a useful product that provides measurable value for those who producr it and those who use it.

McCall's SQ factors :
    Catagories :
        - Product operation factors : 
            correctness, operatability, reliability, efficiency, integrity and usability.
        - Product revision factor : 
            Its ability to undergo change : maintainability, flexibility, Testability
        - Product transition factors:
            Adaptability to new environments : Portability, Reusability and interoperability.

Achieving Software Quality :
    - Software engineering methods : SDLC practices, Deployment, documentation 
    - Project management techniques : Agile, estimation, planning, risk analysis
    - Quality Control: makes sure work product meets its goal. docs, ASR models, reviews, test suits.
    - Quality Assurance: establish infrastructure and make data available for analysis

    Software engineering Methods :
        - Sound practices used through all phases of SDLC
        - Completed understanding of the problem.
        - Comprehensive design
        - constructive code : applying best practices.
        - comprehensive testing.
        - Deployment strategies.
        - Effective documentation

    Project management techniques : ( not much focused)
        - time estimation
        - risk analysis
        - Human centric : keeping developers efficient.

    Quality Control :
        - Have quality goals
        - Intermediate products developed to contribute to final product :
            SRS documentation
            Use case diagram
            Quality specification
            code test review

    Quality Assurance :
        - Solid engineering methods
        - Rational project management
        - Quality control actions
        - Enable data availability to quantify quality.

## CS 3

Measuring Quality Attributes
    - identify main Attributes
    - identify sub Attributes

Software Engineering Process :
    - framework of tasks that are required to build high-quality software.
    - The process is adopted and changed based on requirement though the basic steps are same. 

Generic Process framework Activities :
    There generated activities arranged in different orders and executed with different rigor models different development processes.
    - Communication :
        - Inception : establish Basic understanding. Use IEEE SRS template
        - Elicitation : identify objective of system
        - Elaboration : refining requirements
        - Negotiation : resolving conflicting Requirements
        - specification : Writing down documents, creating models based on templates.
        - Validation : assessing quality of the work products created.
    - Planning :
    - Modeling
    - Construction
    - Deployment

Umbrella Activities : 
    Activities to be executed on all generic framework activities.
    - Software project tracking and control : allows manage any delay
    - Risk management : Assess the risk that could affect the project quality
    - Software quality assurance : Defines and conducts activities required to ensure software quality
    - Technical reviews : Review to reduce bugs
    - Measurement : process, project and product measurement needs to assist software fulfillment.
    - Software configuration management : Manages effect of change through software process.
    - Reusability Management : maximizing software reuse.
    - Work product preparation : Work products like models, documents, logs.

Software Process Models :
    Perspective process model :
        - Detailed execution of 5 generic Activities
        - intended to make projects more manageable
        - better cost estimates
        - achieve required project schedule and quality
        - Carry out process more systematically.
    Agile Process Model :
        - Informal approach to software process model
        - Emphasis on Adaptability
        - Minimal software engineering work products

Perspective Software Process Model :
    - Waterfall : linear sequential model
    - Incremental Process Model
    - Evolutionary Process Model
    - Unified Process for Object Oriented system

Waterfall Model :
    - Strict linear Model. Only forward arrows.
    - Problem requirement is fully understood.
    - Complex structures have well-defined systems.
    - Reflects good engineering practices

Incremental Process Model :
    - Requirements are reasonably understood.
    - provide limited Functionality to users quickly
    - Refine and expand in later releases
    - Deliver increments of software.
    Adv :
        - Customer Value due to easily releases
        - Early increments : helps elicit requirements for later increments
        - Low project failure risk
        - highest priority system services
        - Smaller teams could execute the model.

Evolutionary Process Model :
    - Requirements evolve as product progress
    - Iterative model
    Prototyping Model :
        - Poorly understood requirements
        - Quick and dirty system

Spiral Model :
    - Each phases of activity is done in iterationn.
    - At end of each iteration the phases added or elimated.
    - At end of iteration a small version of product is released.

## CS 4

Managing Quality in SDLC :
    in SDLC : 
        - Manage quality of the process used to create the work product :
            - identify stakeholders
            - create process workflow guidelines with associated checklist
            - create process review guideline with associated checklist
            - use available tools / techniques
        - Manage quality of the work product during every phase :
            - identify work product to be created : Usage scenario, Function and feature lists, requirement models, specification documents.
            - define template for each work product : IEEE SRS template
            - create checklist to review the work product
            - review work product created - create review process guideline
            - use available tools/techniques.

Review process guideline :
    - review the product not the producer
    - set agenda
    - limit debate and rebuttal
    - Enunciate problem areas, dont attempt to solve every problem
    - take written notes
    - limit participants and insist upon preparation
    - develop checklist for each product to be reviewed.
    - Allocate resource and schedule time for review
    - training for all reviewers
    - review earlier reviews

# M4

Quality Function Deployment :
    Goals :
        - Prioritize spoken and unspoken customer wants and needs
        - Translate needs into technical characteristics and design specification
        - Build and deliver quality product or serivce by focusing towards customer satisfaction.

    Helps to :
        - understand new product requirements
        - Design product Requirements
        - Determine the process characteristics
        - Control the manufacturing process
        - To document the existing product specifications

    House of Quality Provides :
        - A requirement planning capability
        - A tool for graphic and integrated thinking
        - A means to capture and preserve engineering thought process
        - means to Communicate the thought process to new members of QFD team
        - inform management regarding any risks, needs of the customer or requirements.
    Building house of quality :
        1 identify the stakeholders (who) :
            - consumer
            - regulatory agencies
            - manufacturing
            - marketing/sales
        2 Determine the customer requirements (what) :
            - Safety
            - Comfort
            - light weight
            - Looks attractive/stylish
            - cost effective
            - has bluetooth and speaker
        3 Who vs What :
            - Relative importance of the requirements.
            - Priority Rating of a requirement = (priority/sum off priority of all requirements)* 100
        4 How :
            - set of engineering specification
    House of quality :
        body : customer requirement vs technical requirement.
            weight of the relationship is mapped using target, circle, triangle or blank
            target : 9; strong relationship
            circle : 3; Medium relationship
            triangle : 1; weak relationship
            blank : no relationship
        Roof : For technical understand relation between requirements.
            - ve relationship : requirement are inversely related.
            + ve relationship : direct related
            blank             : no relations
        Comparative assessment : how each requirement relate with competitors 
            1 - 5 scale.
        importance : sum of all (priority percentage * relationship weight) for each technical requirement.
        relative importance : importance / sum(importance) 
        Technical spec : units, our spec, competitors spec

## mid sem exam important questions

CS 7
White box and black box testing : 1:20:00
    Black Box : 
        Boundary Value analysis :
            Nominal 4n+1 test cases, n #of input parameters.
            Robust  6n+1 test cases

CS 4 
Determining development process model question : 00:43:00
House of quality : 1:37:00 
    10 marks numerical sure!