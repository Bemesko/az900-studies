See: [Shared responsibility in the cloud - Microsoft Azure | Microsoft Learn](https://learn.microsoft.com/en-us/azure/security/fundamentals/shared-responsibility)

- When a cloud provider offers a service to a customer, both are responsible for distinct parts of the service
- Different [[Cloud Service Types]] are classified based on how much responsibility each side has to ensure business value is delivered
- More responsibility for the customer means (generally) less pricing and higher flexibility and control over their resources
- The [Cloud Provider](Cloud%20Provider.md) is always responsible for physical security, power, cooling and network connectivity
- The customer is always responsible for their data, devices and accounts/identities

![](Pasted%20image%2020230824210711.png)

## Stuff needed to deliver value
In a general sense we need the following (from higher to lower level) to deliver value:

1. Data
1. Application
1. Runtime
1. Operational System
1. Hypervisor/[Virtual Machine](Virtual%20Machine.md)
1. Compute
1. Network
1. Storage

- From the runtime downwards things aren't really delivering value on their own, they just support what's above them
- Each [Cloud Service Types](Cloud%20Service%20Types) divides responsibility by drawing a line somewhere along these resources
