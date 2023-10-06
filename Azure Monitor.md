- things in [Azure](Azure.md) generate logs
- [Azure Active Directory](Azure%20Active%20Directory) has audit and sign in logs
- [Subscriptions](Subscriptions.md) have activity logs and service health logs
- [Azure resources](Azure%20resources.md) have metrics and logs
Azure monitor serves as a central place to manage all of these logs and metrics

## Metrics
- Monitor has a built in time series database, which receives metrics from resources
## Logs
- Logs don't actually exist anywhere, but they can be forwarded via Diagnostic Settings
- Places you can forward them to
	- [Azure Storage](Azure%20Storage)
	- [[Event Hub]]
	- [Log Analytics](Log%20Analytics) workspace, which is part of Azure Monitor

## Alerts
- You can create alert rules that may trigger action rules (that do something, such as sending emails)
- Each kind of resource has its own signal types that can trigger alerts 

## Reference
[(2) Functionality and Usage of Azure Monitor - AZ-900 Certification Course - YouTube](https://www.youtube.com/watch?v=v68jL-l9Fww&list=PLlVtbbG169nED0_vMEniWBQjSoxTsBYS3&index=31&ab_channel=JohnSavill%27sTechnicalTraining)