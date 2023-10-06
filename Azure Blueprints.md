- Blueprint of configurations that can be assigned to multiple [Subscriptions](Subscriptions.md)
- Types of assignment (Lock Assignment); Applied at the ARM level
	- Don't lock
	- Do not delete
	- Read only
- Blueprints are version controlled, and updated in subscriptions when published
- They use Deny assignments to avoid conflicts when assigning
- Probably most useful when there are multiple [Subscriptions](Subscriptions.md) or [Management Groups](Management%20Groups.md)

![](Pasted%20image%2020231004125546.png)
## Artifacts in a Blueprint
- [Resource Groups](Resource%20Groups.md)
- [ARM Templates](ARM%20Templates)
- [Azure RBAC](Azure%20RBAC.md)
- [Azure Policy](Azure%20Policy)
## Reference
[(2) Functionality and Usage of Azure Blueprints - AZ-900 Certification Course - YouTube](https://www.youtube.com/watch?v=SJbDcvkySCY&list=PLlVtbbG169nED0_vMEniWBQjSoxTsBYS3&index=52&ab_channel=JohnSavill%27sTechnicalTraining)