- Separate datacenters in a single region that are able to operate independently of one another
- A single zone can have multiple data centers
- All zones in a region are connected through high speed fiber optic networks
- If one zone goes down, the others can carry on
- There are always 3 availability zones in each zone-enabled [[Azure Region]]
- You can implement [High Availability](High%20Availability.md) by putting all necessary resources for an application in a single availability zone and replicating them into other availability zones

## Services that support Availability Zones
- Zonal Services: Each resource needs to be assigned to a specific zone
	- [Azure virtual machines](Azure%20virtual%20machines)
	- [[Azure Managed Disks]]
	- IP Addresses
- Zone-redundant services: The platform itself automatically replicates across zones
	- [[Zone Redundant Storage]]
	- [[Azure SQL Database]]
- Non-regional services: Services are always available from everywhere in Azure and can resist zone-wide and region-wide outages