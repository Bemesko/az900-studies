- The main goal of Microsoft Purview is to allow for insights and governance for an organization's data regardless of where it is stored, without having to import it into a centralized data store.
- Answers 2 main questions:
	- **Where** is my data?
	- **What** data do I have?
	- These questions aren't trivial to answer because data can be in a lot of different places
- Built on Azure Purview and Microsoft 365 Compliance Solutions
- Has Free and Enterprise tiers: [What's in the free version of Microsoft Purview? | Microsoft Learn](https://learn.microsoft.com/en-us/purview/free-version)
	- Free only gives **Data Catalog** and **Data Sharing**
- List of places where you can store data for analysis: [Microsoft Purview Data Map supported data sources and file types | Microsoft Learn](https://learn.microsoft.com/en-us/purview/microsoft-purview-connector-overview)

![](Pasted%20image%2020231009193427.png)

## Capabilities
- First you need to scan the data, which creates a **Data Map**
	1. **Classify** data
	2. Apply sensitivity **Labels**
		- These labels can trigger automations, such as deleting them after X number of days
	3. Get **insights** from the data

### Apps in Governance Portal
- **Data Catalog**: Normalized view of all of the data
	- People can search using filters
- **Data Sharing**: Creates a new, read only storage account in another subscription for the invitee to run analysis. Permissions can be revoked at anytime
	- Specific to [[Azure Blob Storage]] or [[Azure Data Lake Storage Gen2]]
- **Data Policy**: Manage access to data sources and datasets
- **Data Estate Insights**: Gives an overview and actionable information of all data in an organization, targeted to C-level executives
- **Analytics**: using native or external analytics tools
## Reference
[Microsoft Purview Overview - AZ-900 Certification Course - August 2023 New - YouTube](https://www.youtube.com/watch?v=nfP7t8jy0aE&list=PLlVtbbG169nED0_vMEniWBQjSoxTsBYS3&index=50&ab_channel=JohnSavill%27sTechnicalTraining)
[Introduction to Microsoft Purview governance solutions | Microsoft Learn](https://learn.microsoft.com/en-us/purview/governance-solutions-overview)