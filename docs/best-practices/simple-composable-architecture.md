# Simple Composable Architecture
![simple-composable-architecture](../../images/simple-composable-architecture.jpg)

## Description
An engineering organization will use and create simple, composable tools, containers, micro-architectures, etc.

## Rationale
Simple architectures, with standardized interfaces can be composed together which reduces cost of development and maintenance.  Design and architecture made this way is much more simple to understand.

## Implication
Most engineering organizations already have lots of technologies which are not built with this principle in mind.  Engineers should look for opportunities to either migrate existing technologies or decommission older technologies and replace with newer ones following this principle.

## Principles
* [Readable](../design-principles/readable.md) because the individual pieces are simple and easier to understand.
* [Automated](../design-principles/automated.md) because all of these architectures are automated processes that work together to deliver a desired result.
* [Collaborative](../design-priciples/collaborative.md) because many teams will be working on each of these parts and collaborating to get them to work together.

## References
* https://en.wikipedia.org/wiki/Composability

## Examples
* If we had a single service to get LDAP information, then multiple applications could be made by composing services like this.  The advantage would be to have one code base and deployment location for all related
* AWS has a federation of services that are inter-operable and are a good example of this.

<[prev](avoid-vendor-lock-in.md)|[next](logging-and-monitoring.md)>
