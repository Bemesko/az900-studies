- [Azure](Azure.md) boils down to capacity served as resources that are controlled by a control plane ([Azure Resource Manager](Azure%20Resource%20Manager)), this capacity can be managed with things such as [Azure Policy](Azure%20Policy), [Azure RBAC](Azure%20RBAC.md), [Azure Tags](Azure%20Tags) and [Microsoft Defender for Cloud](Microsoft%20Defender%20for%20Cloud)
	- The purpose of Azure Arc is to extend the Azure control plane to service outside of Azure
- Closely related to [Hybrid Cloud](Hybrid%20Cloud.md)
- Set of technologies to manage a [Cloud Computing](Cloud%20Computing.md) environment
- Cloud type can be [Public Cloud](Public%20Cloud.md), [Private Cloud](Private%20Cloud.md), [Hybrid Cloud](Hybrid%20Cloud.md) or even [MultiCloud](MultiCloud.md)

## Arc-enabled servers
- Either [VM](Virtual%20Machine.md) or Bare Metal servers
- An agent runs in the server, and the control plane now knows about that server instance, so the management and governance features of Azure are now applied to that server
- Server gains an Identity

## Arc-enabled [[Kubernetes]]
- Azure services that can be installed in the cluster (regardless of cloud or on premises)
- This enables [[GitOps]]
- Once this is set up, there are a bunch of Arc-enabled services that can be instantiated
	- Data services
	- ML Services
	- App services
![](Pasted%20image%2020231004125135.png)

## Reference
[(2) Describe the Purpose of Azure Arc - AZ-900 Certification Course - May 2022 New - YouTube](https://www.youtube.com/watch?v=cW6_rvDYSHg&list=PLlVtbbG169nED0_vMEniWBQjSoxTsBYS3&index=14&ab_channel=JohnSavill%27sTechnicalTraining)