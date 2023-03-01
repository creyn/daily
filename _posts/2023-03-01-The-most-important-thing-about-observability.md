**Observability** is a non-functional requirement (NFR) of an IT system.
The main goals are:
- to know if the system works on production
- to know if the system works properly
- to know if and when the system will break

The idea behind observability is that, if I know that my system will break
tomorrow, I can fix it beforehand. So my users won't notice any
interruptions.

But the most important thing about observability is **automatization** of
monitoring. Nobody will watch those system metrics and gauges 24/7. You
need the ability to automate the analysis and alerting. So you get some
warning emails (or SMSes) when something is going to happen.

Think about it, how you can design metrics and automation for your
monitoring. You can start with analyzing all those metrics before outages
(in your post-mortem analysis) and run some anomaly detection on those. For
example, Azure has a great tool for anomaly detection and [Azure Monitor](
https://azure.microsoft.com/en-us/products/monitor) has a lot of
observability automation features.

Paweł
