# Azure-Virtual-Network with 4 Subnets
This template allows you to create a Virtual Network with four subnets.

Adress Space:The address space for a virtual network is composed of one or more non-overlapping address ranges that are specified in CIDR notation. The address range you define can be public or private (RFC 1918). Whether you define the address range as public or private, the address range is reachable only from within the virtual network, from interconnected virtual networks, and from any on-premises networks that you have connected to the virtual network. You cannot add the following address ranges:
224.0.0.0/4 (Multicast)
255.255.255.255/32 (Broadcast)
127.0.0.0/8 (Loopback)
169.254.0.0/16 (Link-local)
168.63.129.16/32 (Internal DNS)

Subnet address range: The range must be within the address space you entered for the virtual network. The smallest range you can specify is /29, which provides eight IP addresses for the subnet. Azure reserves the first and last address in each subnet for protocol conformance. Three additional addresses are reserved for Azure service usage. As a result, a virtual network with a subnet address range of /29 has only three usable IP addresses. 
