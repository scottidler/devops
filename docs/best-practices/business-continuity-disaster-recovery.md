# Business Continuity Disaster Recovery
![business-continuity-disaster-recovery](../../images/business-continuity-disaster-recovery.jpg)
## Description
An engineering organization will have robust Business Continuity and Disaster Recovery practices as well as exercise recovery procedures on a regular basis.

## Rationale
Unexpected disasters can cripple an organization or business. Therefore, it is important to be able to continue business in the event of a disaster. It is also import to be able to recover from a disaster at any momment. Doing so allows the orgranization to be able to survive any event, especially those that are unplanned.

## Implication
Important data and processes should be run in more than one location, preferably separated by hundreds of miles, so that in the event of a disaster, the impact is not more than one location. Backups should be taken of sensitive data and code at regular intervals. The ability to recover any of these should be audited regularly so that high confidence in the ability to recover at any moment is achieved.

## Principles
* [Continuous](../design-principles/continuous.md) because we should routinely test recovery and iteratively improve the process.
* [Culture](../design-principles/culture.md) because the impact can be mitigated by good cultural values towards mitigation.
* [Automated](../design-principles/automated.md) because these process should rely heavily on automation.

## References
* http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html#concepts-available-regions
* https://en.wikipedia.org/wiki/Business_continuity
* https://en.wikipedia.org/wiki/Disaster_recovery_plan
* https://en.wikipedia.org/wiki/Disaster_recovery_and_business_continuity_auditing

## Examples
* Use bacula for automated backups and recovery

<[prev](security-by-design.md)|[next](automate-it.md)>
