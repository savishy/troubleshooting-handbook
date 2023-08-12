# The Role of Observability

Modern software troubleshooting is impossible without having eyes and ears into your software's functioning. This is especially true of Distributed, Cloud Native application stacks with thousands of deployed instances. 

Observability is the discipline of gauging the behaviour and performance of your application solely from external signals. 

During an incident, having the right level of observability plays a crucial role in optimizing metrics (_add reference to chapter on MTTx_).

## How much is too much?

How many metrics are too many? Do you need logs, metrics and traces? 

* Logs: what was the system doing at the time of the incident?
* Metrics: how was the system performing at the time of the incident?
* Tracing: what are your system's upstream and downstream dependencies and how were they behaving?


## The Golden Signals 

_add reference from Google SRE_

https://sre.google/sre-book/monitoring-distributed-systems/

* Request Rate 
* Error
* Duration
