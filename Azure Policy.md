- This concept shows up a lot in the [Az 900](Az%20900.md) test
- When deploying things [On Premises](On%20Premises.md), we often rely on an Operations technician that knows the business and regulatory requirements, and they can check whether the thing we want to deploy is valid or not
- When deploying on the [Cloud](Cloud%20Computing.md), there's no Operations person because things are self-service.
	- That said, organizations still have requirements they need to meet. That is where Azure Policy enters
- An Azure Policy is basically a condition and an effect if that condition is met
	- A condition can be pretty much anything that can be derived from an [ARM Templates](ARM%20Templates). e.g. Check if a resource's SKU is in the list of allowed SKUs
	- Effects can be:
		- Audit: Just show if things are or aren't compliant
		- Deny: Make users unable to deploy something that's not compliant with the policy
		- Append/Modify: Change the [ARM Templates](ARM%20Templates) with default values if they aren't specified
- Policies can be applied at all levels of the [Resource Hierarchy](Hierarchy%20of%20resource%20groups,%20subscriptions,%20and%20management%20groups.md): [Management Groups](Management%20Groups.md), [Subscriptions](Subscriptions.md), [Resource Groups](Resource%20Groups.md) or [Azure resources](Azure%20resources.md)
	- Policies are inherited to lower objects of the hierarchy, so they should go from more general to more specific
- A group of policies is called an **Initiative**
	- There are various default Initiatives in [Azure](Azure.md) that correspond to some regulatory certifications

## Reference
[Functionality and Usage of Azure Policy - AZ-900 Certification Course - YouTube](https://www.youtube.com/watch?v=z7WMqHE3R8g&list=PLlVtbbG169nED0_vMEniWBQjSoxTsBYS3&index=49&ab_channel=JohnSavill%27sTechnicalTraining)