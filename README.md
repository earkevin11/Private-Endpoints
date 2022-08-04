# Private-Endpoints

# What are Azure Private Endpoints? Diff between Service Endpoints and Private Endpoints?
- Private Endpoints are powered by Azure Private Link.
- You can connect to your PaaS services over a private endpoint in your virtual network.
- When you enable Private Endpoint, it also creates a private DNS zone so you can map the DNS name for private IP address onto the Azure Storage Account 

# Service Endpoint
- Service Endpoint goes over the Microsoft backbone network while Private endpoint goes a step further and creates an addtional private connection. 
- Service endpoint accesses the public IP address of the Storage Account whereas in Private endpoint it is all private communication.
