
In the GUI

Creating the resource group
- Container for all virtual objects in the lab

Creating the VM
- After registering a Microsoft.Compute resource provider
- Select Windows Server 2022 Datacenter - x64 Gen2 for the OS
- For this lab, the only region I could choose with available VM sizes in a reasonable budget (Standard_DSS1_v2) was South Africa North
- This important to note, because the virtual network and public IP need to be in the same region. So the first VM is where I created the VNet and PIP
- Used a standard HDD, default size

Creating the virtual network
- Acts as a virtual switch / subnet for the VMs

Creating the public IP address
- Public facing WAN for the server
- This is a bit insane if you're used to traditional ISP > bridged modem > firewall configurations
- Azure can route traffic using a specific WAN directly to the NIC of the virtual server using their Software Defined Network (SDN) 
- The traffic is secured using Azure's Network Security Group (NSG) technology.
- The NSG acts as a firewall/filter for each public IP, or each subnet. Applying an NSG to the vnet subnet is the next best thing to a virtualized firewall.


