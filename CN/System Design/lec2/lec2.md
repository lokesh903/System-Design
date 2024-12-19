### Monolithic Architecture

helps us to initiate the developemnt of project as its easy and at this stage we don't know what will be the final architecture of the project. 

it consists of three parts

1. frontend
2. backend
3. storage 

all  three part's code should be combine together and deployed also in same environment.

##### when to use monolithic architecture

same codebase, 
same repo, 
same deployement, 
not clear understanding of the project, 
small team, small project, 
fast development, easy to start, 
easy to deploy, security is easy, 
integration is easy, testing is easy
less confused devlopers


### Microservices

Instead of one big monolith we should have multiple small services. Each service is responsible for one thing. Each service is independent and can be developed

1. Loose coupling 
2. indepent Service (should have there own database)

#### advantages

1. selective scaling
2. fault tolerance
3. Loose coupling
4. deployment time as each service can be deployed independently
5. multiple tech stacks
6. proper ownership and better collaborations

#### challenges

1. costilier infrastructure
2. its complex in terms of communication between services
3. Integration testing is tricky
4. Security
5. Monitoring and logging is harder
6. higher latency because of additional network calls
