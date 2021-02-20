# Cattle Not Pets
![cattle-not-pets](../../images/cattle-not-pets.jpg)
## Description
An engineering organization will aim to have all compute resources be cattle not pets including: physical machines, virtual machines and containers.
## Rationale
Treating a compute resource as pet takes special care, is hard to reproduce, and can be difficult to maintain.  There will always be question about what changes or software were installed to a system to cause a failure.  In contrast, treating these resources as cattle, something that created programmatically, multiple times allows the engineer to reason about the resources, not care about any one compute resource and apply good coding practices to the build process.
## Implication
An engineering organization will have to evolve the way that they think about compute resources.  Building technology that uses the cattle has implications such as naming schemes, keeping track of which systems are active, which are failing, tracking logging, and debugging in an environment with ephemeral nodes, to name a few.
## Principles
* [Continuous](../design-principles/continuous.md) because these technologies enable iteration and continuous rapid change.
* [Self-service](../design-principles/self-service.md) because self-service is enabled when asking for a new VM or grabbing a container off of Docker Hub.
* [Automated](../design-principles.md) because these systems are built with automation in mind and in fact that is the point of their use.
* [Holistic](../design-principles/holistic.md) because these systems touch the entire stack and are involved in a variety of concern through out the product.
## References
* http://cloudscaling.com/blog/cloud-computing/the-history-of-pets-vs-cattle/
* http://www.engineyard.com/blog/pets-vs-cattle
* https://www.hostworks.com.au/pets-versus-cattle-thinking-infrastructure-isnt-enough/
## Examples
* Containers (Docker, Open Container Initiative, rkt, etc)
* Virtual Machine orchestration via vagrant or otto
* autocert uses two Docker containers (nginx, and api) to deliver the application.  Both are recycled on every deploy.
