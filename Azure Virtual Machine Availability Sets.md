- Grouping of [Azure Virtual Machines](Azure%20Virtual%20Machines.md) that ensure that the VMs in it are available
- VMs receive staggered updates and have independent power and network connectivity
- VMs can be grouped in:
	- Update domains group VMs that can be updated at the same time
	- Fault domains group VMs by common power source and network switch
		- By default the VMs are split into 3 fault domains ([Availability Zones](Availability%20Zones.md)?)
- No additional cost of configuration