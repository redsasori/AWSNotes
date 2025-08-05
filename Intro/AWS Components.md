# Concept:
![[Pasted image 20250804111931.png]]

## VPC -> Virtual Private Cloud

## 2 Blocks -> Buildings/Apps 

## Subnets
Chunks/Pieces of IP address

![[Pasted image 20250804113132.png]]

**CIDR Range**(10.0.0.0/16) -> **Org 1** -> Building 1 -> 10.0.1.0/24(VPC 1) 10.0.2.0/24(VPC 2) 
**CIDR Range** (172.16.0.0/16) -> **Org 2** -> Building 2 ->172.16.1.0/24(VPC 3) 172.16.2.0/24(VPC 4)

CIDR -> https://www.ipaddressguide.com/cidr
# Routes -> To go outside the internal network
Routes decide how the the traffic goes outside of the network.
**Route Tables** -> Used to control the flow of traffic between subnets, gateways or other network devices.
## Security -> IGW( Internet Gateway)
It will allow on traffic/people which are authorized.

# Regions and AZ

![[Pasted image 20250804115904.png]]

