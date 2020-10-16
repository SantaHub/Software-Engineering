# Cloud computing
Course ID : SE ZG527

T1 : Moving To The Cloud : <https://learning.oreilly.com/library/view/moving-to-the/9781597497251/>

T2 : Cloud Computing: Principles and Paradigms: <https://learning.oreilly.com/library/view/cloud-computing-principles/9780470887998/>

## Module 1

### RL 1 Introduction

Cloud computing :
    - availability
    - scalability
    - pay per use

3-4-5 Cloud computing :
    - 3 cloud service models or types :
        - SaaS : Software as a service
        - PaaS : Platform as a service
        - IaaS : infrastructure as a service
    - 4 deployment models :
        - public cloud : for small scale users
        - private cloud (usually on-premise): cloud infrastructure maintained by specific requirement of an organization
        - hybrid cloud : part of the system resides on public cloud and restricted resources reside on the private cloud
        - community cloud : infrastructure maintained for a group of organizations with common requirements.
    - 5 essential characteristics of cloud computing :
        - on demand self service
        - ubiquitous network access
        - location transparent resource pooling
        - Rapid elasticity
        - pay per use

## Module 2

### RL 2 Virtualization Techniques and Types

Virtualization : Allows multiple operating systems to run on a single computer.
    - guest OSs are managed by Virtual Machine Monitor known hypervisor

Hypervisor Design Goals:
    - Isolation :
        - security Isolation
        - fault Isolation
        - resource Isolation
    - Reliability :
        - Minimal code base
        - layered Design
        - not extensible
    - scalability :
        - scale to large number of cores
        - Large memory systems

 Monolithic hypervisor Vs Microkernelized
    Monolithic hypervisor :
        - common driver for all OSs.
        - complex kernel
    Microkernelized : 
        - smallest TCB (Trusted computing Base)
        - independent drivers

Types of Virtualization 
    Fullvirtualization :
        - fully emulated host system
        - architecture independent
        - performance drain on fully emulating the system
        - VMWare
    Paravirtualization : 
        - hardware assisted virtualization allows direct access for OSs managed by VMM (hypervisor) and improve performance
        - a low overhead full virtualization
    SKI Virtualization:
        - Single Kernel Image. Allows multiple copies of itself.
        - Not flexibility. Sacrifices security and Reliability of other methods.

Known Issues : 
    - Software licensing : Large spawning of expensive licensed Software installed servers could lead to large bills, as each server would need seperate licensing
    - IT Training : VM Training
    - hardware Investment : Benefits of virtualization is realized only on huge virtualization and requirement high spec machines.
    - performance bottleneck by in-band applicaitons
    - Interoperability amoind products still evolving
    - Device failure leads to loss of mapping table.

Docker 
    Each applicaiton with its dependencies are packed into a single container.
    Dockers allow elimination of redudant OS dependency by using a docker engine making the virtualization lighter.

# M3

## RL3.1 IaaS

Key concepts : 
    Cloudbursting : Process of off-loading tasks to the cloud during when the most compute resource are needed
    Multi - tenant computing : Virtualization allows multiple customers on single system.
    Resource Pooling : Rather than individual resource allocation, the resources are pooled to reduce risk and increase advantages for the user.

Iaas Primary Facets :
    Elasticity : The degree to which the system autonomously adapts its capacity to workload over time
    Or The ability of a system to expand and contract its dedicated resources to meet the demand.
    Virtualization : Ability to share the resource for a system as individual multiple system.

Considerations while moving to cloud :
    - Applications needs to be developed for generic IaaS
    - Development of resource allocation Software
    - What type of data has to be moved to cloud
    - Cloud migration would affect day-to-day operation of the business.

OpenStack terminology
    NOVA : compute instances
    Glance : Image (OS) Service
    Swift : Object store (S3)
    Neutron : Networking
    Cinder : Volume Service (EBS)
    Heat : Orchestration
    Cellometer : AWS cloud watch
    Keystone : Identity service
    Horizon : Dashboard

VM provisioning : 
    - request a server from pool and select the image it should run on.
    - Customize and configure the machine to associate to network and storage
    Scripted : VagrantFile / Heat

VM migration for maintance :
    Cold/regular migration : VMs are turned off. Data is migrated to new host and new host is started.
    Live migration : VMs are configured in data/network sharing. RL 3.5 9:00-15:00
        Challenges : lots of state in memory


## Slides 

CS1 :
    - What is cloud computing : 6
    - 3-4-5 Rule : 11
    - Cloud providers characteristics : 25

CS2 :
    - Datacenter : 30
    - Difference between cloud deployment models, public private hybrid community : 39
    - Virtualization & Types of virtualization : 42
    - Hypervisor & design goals : 52
    - advantages, issues and applications of virtualization : 74
    
    - Docker : 84

    - Iaas : 103
    - S3 : 115
    - SimpleDB : 124
    - EC2 : 130
    - EBS : 139
    - Features of IaaS : 145
    - VM provisioning : 154
    - Migration : 159
    - OpenStack : 170

    - Docker : 195
    - LXC and LXD : 198
    - Diff virtualization and cloud computing : 199
    - Cloud Orchestration Techniques : 202
    - Orchestration and automation : 205
    - Orch Tools : 210

    Module 5 Slides
    - PaaS : 3
    - Fabric controller : 19
    - SQL Azure : 21
    - AppFabric : 22
    - Azure programming model : 24
    - storage servce : 27
    - SaaS ApplicationArchitecture : 55
    - 