# Private-Endpoints

# What are Azure Private Endpoints? What are the differences between Service Endpoints and Private Endpoints?
- Private Endpoints are powered by Azure Private Link.
- You can connect to your PaaS services over a private endpoint in your virtual network.
- When you enable Private Endpoint, it also creates a private DNS zone so you can map the DNS name for private IP address onto the Azure Storage Account 

# Service Endpoint
- Service Endpoint goes over the Microsoft backbone network while Private endpoint goes a step further and creates an addtional private connection. 
- Service endpoint accesses the public IP address of the Storage Account whereas in Private endpoint it is all private communication.
- Service Endpoint has no additional charge



# Private Endpoint Lab #275
- Azure Storage Account > Networking > Create Private Endpoint Connections
- Target sub-resource - choose which service you are creating the private endpoint fo
- Select the existing virtual network - where it will create an private DNS zone.
- The private endpoint resource will be created where it has a private IP address.
- Now users would be connecting via its private IP whereas users are connecting to a service endpoint via public IP 
- Private Endpoint has a charge per hour 
