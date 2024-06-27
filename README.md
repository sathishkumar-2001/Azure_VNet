This repo shows what?why?how? use of Azure VNet(virtual network)

azure firewall restrict the access to enter into the vnet
each subnet has a nsg like a security guard
each route tables has a system routes(path) , it is responsible for routing the request
devops engineers will create a app gateway for each subnet and place a load balancers
load balancers are responsible for maintain traffic
azure DNS
App gateway is used layer7 traffic
Load balancers is used layer4 traffic
vnet peering - when you want to connect two vnet , we can modify the routing table , you should have the admin access for both vnet
vnet gateway 
vpn gateway - connect between onprimises to azure vnet

we will be using the bashton host to connect to the vm in the private subnet


![image](https://github.com/sathishkumar-2001/Azure_VNet/assets/126504329/8f63cc84-ca5f-4d38-80ad-e16f9773e9d6)


![image](https://github.com/sathishkumar-2001/Azure_VNet/assets/126504329/4732b77a-36d6-4f46-b095-90acbacdcdc5)
