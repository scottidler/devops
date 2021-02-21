# Logging And Monitoring
![logging-and-monitoring](../../images/logging-and-monitoring.jpg)
## Description
An engineering organization will capture logging for all applications, web servers, and machines as well as setup monitoring to check for health and performance.
## Rationale
During failures and outages it is common that looking through logs is the only way to figure out what is causing the failure. Application monitoring can also give hints to failures and record data points as the failure is taking place. Without these two systems in place some failures and events will be impossible to prevent, diagnose and fix quickly.
## Implication
An engineering organization will invest in setting up comprehensive logging across all production systems as well as monitoring to record events and performance. Doing so will provide the tools necessary to respond quickly to events and even prevent some as well.
## Principles
* [Readable](../design-principles/readable.md) because the logging and monitoring need to be clear and communicate the current state of an application or process.
* [Automated](../design-principles/automated.md) because the sheer volume of data and the frequency it is harvested at requires automation.
* [Self-service](../design-principles/self-service.md) because a lot of these product allow the user to create and save queries to get at their data even quicker.
## References
* http://devopsflowmetrics.org/
* https://en.wikipedia.org/wiki/Server_log
* https://en.wikipedia.org/wiki/Application_performance_management
## Examples
* journalctl, Kibana, Prometheus are some examples of the logging and monitoring possible in this space.
