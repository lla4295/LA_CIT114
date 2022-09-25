# Notes 05: Networking & Content Delivery
## 1. Summarize a few key points made in the readings or videos.
- A computer network is made up of two or more client machines that are connected together and use a network device to share resources.
- Network Devices Include: Routers, Hubs, Bridges, Wireless Routers, Switches, and Wireless Bridges.
- Network Topology is the layout pattern using which devices are interconnected. (Ex: Bus, Star, Mesh, Ring, Daisy Chain.)
### OSI Layers (Open Systems Interconnection)
- OSI is a reference model that specifies standards for communication and functionalites for each layer.
- Layers Include:
- Layer 7 - Application - OSI layer that is closest to end user; user interacts directly with software application.
- Layer 6 - Presentation - Establishes context between application-layer entities.
- Layer 5 - Session - Controls the connection/dialouges between computers, it also establishes, manages and terminates connections between local&remote application.
- Layer 4 - Transport - Provides the functional/procedual means of transportation of variable-length data sequences, from source to destination host.
- Layer 3 - Network - Provides the functional/procedual means of transportation of variable-length data sequences (packets from one node to another in different network.
- Layer 2 - Data Link - Link between two directly connected codes; node-to-node data transfer.
- Layer 1 - Physical - Responsible for transmission of unstructured, raw data between device and physical transmission medium.
### Network Definitions
- Protocol - The set of rules or algorithms which define the way how two entities can communicate across the network. (Ex: TCP, IP, UDP, DHCP, etc.)
- Host Name - Each device in a network has a unique identifier, or "hostname". - Hostname in command prompt to find yours.
- IP address - Network address of a system across a network; ipconfig in command prompt to find yours.
- Classless Inter-Domain Routing (CIDR) - Method to describe networks w/ slashes; this is a way to express groups of IP address that are consecutive.
- MAC Address (Media Access Control address) - A physical identifier of each host associated with the NIC. (Assigned when manufactured)
- Port - Logical channel through which data can be transferred.
- Socket - Unique combination of IP addresses.
### Amazon VPC (Amazon Virtual Private Cloud)
- A virtual network that is dedicated to your AWS account.
- Lets you provision a logically isolated section of AWS cloud; This area will let you launch AWS resources in a virual network you define.
- With this, you have complete control over your virtual networking environment.
- Allows for easy network configuration customization.
### VPN (Virtual Private Networks)
- Allows a user to connect to one or more remote private network to another one through a secure virtual tunnel over the public internet.
- Many companies use this to allow employees to access resources from anywhere in the world. (Work from home, etc.)
- AWS also allows for VPN use through AWS Client VPN, Site-To-Site VPN, Cloudhub VPN, or a third-party software.
### Network Security
- Security groups act as a virtual firewall for instances to control inbound & outbound traffic.
- When you launch an AWS instance, you can assign up to 5 security groups.
- With security groups, you can add rules to control the inbound and outbound traffic to/from instances.
- Network Access Control Lists (ACL's) are an optional layer of security for your VPC; these are additional rules you can make to control network traffic.
### Amazon Route 53
- DNS (Domain Name System) - Translates human-readable domains such as www.amazon.com to IP addresses that are readable for machines, like 192.0.2.44
- DNS services manage the mapping between domain names and numbers, they also translate and furfill queries for end-users.
- An example of a DNS service is Amazon Route 53, this is a highly available and scalable web service.
- Amazon Route 53 is a realiable and cost effective way to route end users to internet applications by translating domain names to IP addresses that users use to connect to each other.
- Amazon Route 53 can be used to route users to infrastructure outside of AWS, monitor application, endpoint health, and control network traffic.
- Amazon Route 53 also allows you to purchase domain names and automatically their DNS settings configured.
### Amazon Cloudfront
- AWS service that securely delivers data, videos, applications, and APIS to customers globally with low latency, high transfer speeds, and within a developer-friendly environment.
- Using Cloudfront can speed up the distribution of static and dynamic web content.
## 2. Identify and provide two quotes that were made in the readings or videos, that you found interesting. Describe why you found each quote of them interesting.
> "If you're a developer or a system admin, the bulk of your time is spent up here in layers 5 through 7. It creates a divide." - Don (ITPROTV Video)
- I found this quote interesting because I am more interested in becoming a developer or sysadmin, this let me know which layers I should focus on learning/apply to me while learning.
> "Let me just turn that on real quick. And I can browse the network, and it's going to start looking across the network." - Don (ITPROVTV Video)
- I found this quote interesting because I followed along with him in the video and turned on Network Discovery and saw a bunch of different devices on my home network, I didn't know this setting existed before.
## 3. Outline the new facts that you learned from this section?
- Learned about the 7 OSI layers & what each layer does.
- Learned networking definitions so I could understand AWS networking services better.
- Learned about AWS network security options.
- Learned about AWS route 53 services.
- Learned about AWS cloudfront service.
## 4. What questions remain in your mind after reading this section?
- Will the OSI layers stay relevant for a long time, or be replaced with another networking model in the future?

