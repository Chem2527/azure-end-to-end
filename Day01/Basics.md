agility - quickly adapting to changing needs
Fault tolerance - ability of a system of service to remain operational even incase of hardware or software errors or unexpected disruptions
Standard_D2s_v3 ---> Hosting websites, lightweight applications, or development and testing environments.

Compute Optimized VMs

Standard_F2s_v2 ----> high CPU-to-memory ratio ---> Batch processing, gaming applications, and other CPU-intensive workloads

Memory Optimized VMs

Standard_E16s_v3 ----> Running large databases, in-memory caching, and analytics applications

Storage Optimized VMs

Standard_L8s_v2 ---> Big data applications, data warehousing, and large-scale databases.

VNET

Vnet: logical isolation of network within the physical network of microsoft azure. usecase(requesting for vms in same az without vnet leds to hackinf of systems within tht physical server.)


size can be measured in terms of ip addresses. these can be defined in terms of CIDR.

Its good to apply NSG to subnets as same is applied to resources present inside the subnet.
NSG ---> use case: all the resources in pub subnet able to access DB.
ASG ----> we can group resources in pub subnet and only that particular resources able to access DB.
Route table : How should traffic flow within a particular subnet.


DevOps engineers create  additional subnet called app gateway subnet where they deploy LB and the responsibility is to load the balance and LB is configured with dns name of our application and it will be mapped to ip address of LB.


if users want to perform actions on azure they need identities either users,groups,roles
if one resource wants to access another they need identities like service principal or managed identity.



