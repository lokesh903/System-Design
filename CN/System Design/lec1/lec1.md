#### Types of system design

##### 1. High-Level Design(HLD):
This kind of architecture takes into consideration the main components that
would be developed for the resulting product. The designer only focuses on a
high-level overview, including
● principal components,
● database
● services
● relationships between each module/component
with a brief description of the system.

###### how to build this 

1. understand the statement 
2. Requirment  Analysis
    a. functional requirements 
    b. non functional requirements
3. Capacity Estimation
4. Define the diffrent components of the whole application and their communication



##### 2. Low-Level Design(LLD):
On the contrary, this kind of architecture considers the in-depth and detailed
design of each component mentioned in the High-Level Design of the system.
It exposes the logical relationship between different elements and a detailed
description of all the modules. Low-Level Design includes more technical
information as compared to High-Level Design. Low-Level Design includes the
description of the following components:
● IP Address
● Class Diagrams, Sequence Diagram, Activity Diagrams
● VLAN and Port Numbering
● Information about all the platforms, services, and processes of the
product would depend on
● Algorithm and pseudocode
● Different Classes, interfaces and the relationship between them
● Relationships between the modules and system features
● External Interface Requirements, Hardware and Software Interfaces
● Design and Implementation Constraints



### Checkout Experience of a coustumer

#### high level design

it can have 2000/sec requests

1. Functional requirements 
    able to add the items 
    able to checkout the items 
2. Non functional requirements
    it should be scalable
    it should be more available
3. Capacity Estimation 
    it should have 2000/sec requests

4. Define the diffrent components of the whole application and their communication

    1. cart service 
    2. checkout service
    3. inventory service
    4. authentication service
    5. payment service
    6. shipment service

#### low level design

the in-depth and detailed design of each component mentioned in the High-Level Design of the system.

such as erd of components 
