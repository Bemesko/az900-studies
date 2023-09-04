---
alias: IaaS
---
- Generally adopted by companies migrating their existing [On Premises](On%20Premises.md) infrastructure to the cloud
- Most flexible of the [Cloud Service Types](Cloud%20Service%20Types.md) and gives customers the most control
- Basically renting the hardware in a data center

## Use Cases
- [Virtual Machines](Virtual%20Machine.md)
- [[Lift and Shift]] migrations
- Replicating configurations for testing and development enviroments
## [Shared Responsibility](Shared%20Responsibility.md)
- The cloud provider is responsible only up to the Hypervisor
	- Basically the hardware and connectivity to the internet

**Customer Responsibility**
1. Data
1. Application
1. Runtime
1. Operational System

**Cloud Responsibility**
1. Hypervisor/[Virtual Machine](Virtual%20Machine.md)
1. Compute
1. Network
1. Storage