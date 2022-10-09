# Final Reading Notes
## Cloud Concepts Overview
### 1. Summarize a few key points made in the readings or videos.
- The cloud refers to a distinct IT environment that is designed for the purpose of remotely provisioning scalable and measured IT resources.
##### Business drivers of cloud computing include... 
1. **Capacity Planning**
- Planning for determination and furfillment of an organization's future IT demands, resources products/services made easier.
2. **Cost Reduction**
- Cost of buying infrastructure & maintaining it is cheaper.
3. **Organizational Agility**
- Businesses/organizations can adapt to change easier.
##### Cloud computing models include...
1. **SAAS (Software as a Service)**
- Allows users to connect & use cloud-based apps over the internet.
- Resources Include: Application Software.
- Used by end users/customers.
- Ex: Gmail, Google Docs, Google Drive, Office 365, HR/Helpdesk Solutions, and Salesforce.
2. **PAAS (Platform as a Service)**
- A development/deployment environment in the cloud.
- Resources Include: Programming Language Execution Environment, An Operating System, A Web Server, and a Database.
- Used by developers.
- Ex: AWS Elastic Beanstalk, Google App Engine, Windows Azure, Heroku, and Force.com.
3. **IAAS (Infrastructure as a Service)**
- An instant computing infrastructure, that can be provisoned and managed over the internet.
- Resources Include: Data Storage, Virtualization, Servers & Networking.
- Used by sysadmins.
- Ex: Amazon EC2, GoGrid, and Rackspace.com.
## Cloud Economics and Billing
- AWS offers on-demand, pay-as-you-go, and reservation-based payment models, enabling you to obtain the best return on your investment for each specific use case.
- AWS is typically cheaper than on-premise data centers because you only pay for the services you consume w/ no large upfront costs. (Variable costs eliminated/lowered)
- You can save on AWS when you invest reserved capacity/instances (up to 75%), there are three types.
- All Upfront Reserved Instance (AURI) - 32% Savings
- Partial Upfront Reserved Instance (PURI)- 42% Savings
- No Upfront Reserved Instance (NURI)- 43% Savings
- You can also save on AWS when you use more resources and services because of volume-based discounts. (The more you use, the less you pay per GB.)
### Three Fundamental Drivers Of Pricing
- Compute
- Storage
- Outbound Data Transfer
### Pricing Models Include...
- On Demand - Paying for compute or database capacity wo/ long term commitments or upfront payments.
- Dedicated Instances - Amazon EC2; Virtual Private Clouds that run on hardware that is dedicated to a single customer.
- Spot Instances - Amazon EC2 Pricing Mechanism that let you purchase discounted spare computing capacity w/o upfront commitment. 
- Reservations - Paying for capacity ahead of time; allows you to save up to 75%.
### Other Notes...
- Rio Hondo is partnered w/ Amazon Educate, so students have benefits in AWS.
- The AWS free tier allows you to test-drive some AWS services free-of-charge.
- IT infrastructure consists of hardware, software, and networking; there are two types which are traditional and cloud.
- TCO stands for total cost of ownership, this is a formula calculates direct and indirect costs and benefits related to the purchase of any IT component. 
- The goal of TCO is to project a final figure that will reflect the true purchase price with everything considered.
- AWS has budgets and cost/usage reporting to help you keep track of your billing.
- AWS has different support plans that provide customer service benefits at different costs.
## Cloud Global Infrastructure
- AWS has infrastructure all over the world; this allows you to go global in minutes.
- AWS regions are seperate geographic area that AWS uses to house its infrastructure. (Distributed around the world so customers can choose closest location.)
- AWS availability zones are building blocks that make up AWS regions. (AZ's are isolated data center locations within a region.)
- It is recommended to distribute instances over multiple availability zones so if one fails, you have a backup.
- AWS infrastructure is elastic, scalable, fault-tolerant, and highly available.
- AWS serves 245 countries/territories in total, it has 27 launched regions, 87 Availability Zones (AZ's), and 410 points of presence. 
- AWS regions include: North America, South America, Europe, Middle East, Africa, Asia Pacific, and Australia.
- Points of presence consists of data centers close to Edge Locations and Regional Edge Cache servers.
- AWS Local Zone places data centers close to large population, industry, and IT centers.
#### Factors to consider when choosing AWS region (Best for workload)
- Supported AWS services - Some AWS services are not available in all regions.
- Cost - Differs based on region.
- Latency - Should be blazing fast, should be picked based on target audience location.
- Security & Compliance - Abide by each countries Data Security and Compliance rules.
- Service Level Agreements - Not all AWS services warrant the same SLA.
- AWS foundational services include compute, storage, databases, and networking.
- *# of Edge Locations > # of Availability Zones > # of Regions*
## Cloud Security
- Cybersecurity is the protection of all networks, devices, and data from unauthorized access/criminal use. (Ensuring info confidentiality, integrity, and availability.)
- Poor cybersecurity results in multiple risks such as data erasure, altering of files, computer attacks, stolen credit card information from malware/hackers.
#### Ways to improve cyber security
- Keep software up to date.
- Run-up-to-date antivirus software.
- Use strong passwords.
- Change default usernames & passwords.
- Use multifactor authentication (MFA).
- Be suspicious of unexpected emails.
- Install a firewall.
#### AWS Security
- AWS uses a security and compliance system; this means ther is shared security responsibility between AWS and the customer.
- AWS's shared security model helps relieve the customer's operational burden as AWS operates, manages, and controls components from the host operating system.
- The customer of AWS services has responsibility and management of the guest operating systems, application software, and configuration of the AWS firewall.
#### AWS is responsible for...
- Physical security of data centers.
- Hardware infrastructure.
- Software infrastructure.
- Network infrastructure.
#### Customer is responsible for...
- Everything they put in the cloud.
- What is implemented using AWS services, or applications related with AWS.
- Selecting and securing instance operating systems.
- Securing applications launched on AWS resources.
- Security group configurations.
- Firewall configurations.
- Network configurations.
- Secure account management.
### Identity and Access Management (IAM)
- IAM is a webservice that helps you securely control AWS resources for your users.
- IAM is used to control who has access your AWS resources and how they can use it.
- Root user identity is created when you first create an AWS account.
- IAM users must be authorized/authenticated to use AWS services. (IAM policy must be created.)
- It is not reccomended to use the Root User for everyday tasks, or admin tasks. (Credentials of Root user should be securely locked away, IAM users should be utilized.)
- Principle of least advantage promotes the granting of minimal user privileges based on the needs of your users.
### IAM Essentials
- IAM User - Person/application defined in an AWS account.
- IAM Group - Collection of IAM users. (Can be used to manage permissions of multiple users.)
- IAM Policy - Document that defines permissions to determine what users can do in the AWS account. 
- IAM Role - Tool for granting temporary access to specific AWS resources in an AWS account.
### 4 Ways To Use IAM
- AWS Management Console
- AWS Command Line Tools
- AWS SDKs
- IAM HTTPS API
### Applications for Securing Accounts 
- AWS Organizations - (Allows for consolidation and easy governing of multiple AWS accounts in a single organization.)
- AWS Key Management Service - (Lets you create and manage cryptographic keys.)
- Amazon Cognito - (Lets you add user sign-up and sign-in.)
- AWS Shield - (DDOS protection service.)
### Applications for Securing Data
- Data At Rest
- Data In Transit
- Securing S3 Buckets & Objects
### Applications for Ensuring Compliance
- AWS Config
- AWS Artifact
## Networking & Content Delivery
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
## Compute
- AWS offers a variety of compute services, the four broad categories consist of Virtual Machines, Containers, Serverless, and Platform as a Service.
### Compute Service Categories
- Virtual Machines - Lets you obtain and configure capacity with ease, control computing resources, run on Amazon's proven computing environment, build IAAS applications for instance-based VM's, and provison machines & manage as you choose. Ex:) Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud.
- Serverless - Allows you to run code w/o provisioning or managing servers; you only pay for compute time consumed, no charge while code isn't running. Ex:) AWS Lambda.
- Containers - Enable you to run workloads on a single operating-system, these spin up more quickly than VM's so they offer more responsiveness. Ex.) Amazon Elastic Container Service, Amazon Elastic Kubernetes Service, AWS Fargate, and Amazon Elastic Container Registry.
- PAAS (Platform As A Service) - Allows a company to focus on building code and applications rather than the management of infrastructure. Ex:) AWS Elastic Beanstalk.
### Practices For Selection Of Compute Resources
- Evaluation of available compute options.
- Understanding of available compute configuration options.
- Collecting compute-related metrics.
- Determination of required configuration by right-sizing.
- Using of available elasticity of resources.
- Re-evaluation of compute needs based on metrics.
### VM's (Virtual Machines)
- A software-based computer that exists within another computer’s operating system.
- VM's run off hypervisors, or pieces of software/hardware.
- Testing - Software Developers want to test their code in different environments; they use VM's to furfill this need.
- Running software designed for other OSes - VM's can run software designed for other OSes.
- Running outdated software - VM's can run old versions of OSes.
- Cloud Computing uses VM's for running SAAS applications, Backing up data, and Hosting services like email and access management.
- Amazon Elastic Compute Cloud (Amazon EC2) provides virtual machines where you can host the same kinds of applications that you might run on a traditional on-premises server.
### Four Pillars of Cost Optimization
- Pillar 1. Right Size - Choose right balance of instance types & provision matches to your need.
- Pillar 2. Increase elasticity - Use automatic scaling to reduce costs by turning off resources when not needed.
- Pillar 3. Leverage the right pricing model - Choose right pricing model to optimize based on workload/usage patterns.
- Pillar 4. Optimize storage - Optimize storage use to reduce storage costs.
### Containers
- Containers are an approach to operating system virtualization
- Users can work with a program and its dependencies using resource procedures that are isolated.
- Used to build blocks, which help in producing operational efficiency, version control, developer productivity and environmental consistency.
- Benefits include: The Consistency in Cloud Storage, Application Version Control, Efficiency in the Operational Activities, and Productivity of the Developers.
- Amazon Elastic Container Service (ECS), Amazon Elastic Kubernetes Service (EKS), Amazon Elastic Container Registry (ECR) are container services.
### Serverless Computing
- Method of providing backend services on a as-used basis.
- Servers are still used but company gets backend services from a serverless vendor and is charged based on usage.
- Allows users to write and deploy code without worrying about existing infrastructure. 
- AWS Lambda is a container service.
### Platform as a Service (PaaS)
- Removes the need for organizations to manage the underlying infrastructure.
- Allows you to focus on the deployment and management of your applications.
- Increases efficiency becuase you don’t need to worry about resource procurement, capacity planning, software maintenance, patching, or any of the other undifferentiated heavy lifting involved in running your application.
- AWS Elastic Beanstalk is a PaaS service.
## Storage
- Storage is one of the key components/technologies of a computer; it allows a user to retain digital data into a medium.
- There are two types of storage, Volatile and Non-Volatile. 
- Volatile memory is a type of storage that is erased when a computer is powered off/interrupted. Ex.) RAM
- Non-Volatile memory is a type of storage that is saved regardless of power to a computer, it is known as permanent storage or persistent storage. Ex.) Hard Drive, Flash Memory, or ROM.
### Disaster Recovery
- A disaster is anything that puts a business at risk from a natural disaster, equipment failure or cyberattack.
- Disaster Recovery is a set of policies, tools, and procedures that enable the recovery/continuation of IT infrastructure after a disaster.
- Fault Tolerance is the idea that a system can continue to run/work after a component fails. 
- Graceful degradation is the ability for a system to tolerate the failure of a critical component and maintain functionalit.y
- Replication means that you have a copy of your IT infrastructure that is fully functional.
- Redundancy means that you have IT infrastructure to keep your business running at reduced capacity for a short period of time just in case a failure/problem needs to be fixed.
### RAID (Redundant Array of Independent Disks)
- RAID is the fastest way to replicate data.
- There are 5 Levels of RAID.
- RAID 0 - Disk Stripping
- RAID 1 - Disk Mirroring
- RAID 5 - Block-level stripping with a distributed parity
- RAID 6 - An extension of RAID 5 with an additional parity block
- RAID 1+0 - A hybrid RAID that involves having two stripped sets of disks then mirroring them.
### Storage In The Cloud
- Cloud Storage is a cloud computing model that stores data on the internet via a cloud computing provider that operates data storage as as service.
- Cloud Storage is on-demand, flexible, durable, and accessible from anywhere.
- Storing data in the cloud lets IT departments transform their total cost of ownership, time to deployment, and information management.
- The three types of cloud storage are object storage, file storage, and block storage.
- You can use cloud storage for backup and recovery, software test & development, cloud data mitigation, compliance, and big data & data lakes.
### Core AWS Storage Services
- Object Storage - Data storage architecture for handling large amounts of unstructured data; cannot be easily organized into databases w/ rows and columns. 
- Amazon Simple Storage Service (S3), Amazon S3 Glacier are AWS Object Storage services.
- File Storage - Organizes and stores data inside a folder.
- Amazon Elastic File System (EFS), Amazon FSx for Windows File Server, Amazon FSx for Lustre are AWS File Storage Services
- Block Storage - Breaks a file into equally-sized chunks of data and stores these data blocks separately under a unique address.
- Amazon Elastic Block Store (EBS) is an AWS Block Storage Service.
## Databases
- Databases are shared collections of relational data that is used to support organizations.
- Databases typically contain many tables with data stored inside of them.
- A DBMS or Database Management System is a group of programs that allow for the easy creation, maintenence, and control of databases.
- Databases consist of relations, tables, columns, domains, records and degrees.
- There are two types of databases relational & non-relational (document oriented, graph based, key-value, etc.)
- SELECT, INSERT, UPDATE, AND DELETE are basic SQL Query Commands.
- The difference between unmanaged and managed services are that scaling, fault tolerance, and availibility are managed by the user in unmananged while in managed it's built into the service.
### Amazon Relational Database Service (RDS)
- Managed relational database service that provides you with six database engines to choose from. 
- (Amazon Aurora, MySQL, MariaDB, Oracle, Microsoft SQL Server, and PostgreSQL are the six DB engines provided by AWS RDS.
- A DB instance is the most basic building block of Amazon RDS, it contains user-created databases.
- You can choose the DB Engine, computation and memory capactity, and storage or DB instances.
- You can run DB Instances with Amazon VPC so that you can have control over it's networking environment.
- On demand instances or reserved instances pricing options.
### Amazon DynamoDB
- Fully managed key-value and document NoSQL DB service.
- Provides fast and predictable performance with flexibility.
- NoSQL database with flexibility when storing and organizing data.
- Pricing based on what you read, write, and store in your DynamoDB; optional features also available but cost more.
- On demand or provisioned capacity options.
### Amazon RedShift
- Fully managed, petabyte style scalable data warehouse.
- Consists of clutters that are made up from nodes.
- Integrated with data lakes to manage data.
- Pay for what you use pricing.
### Amazon Aurora
- Relational database that is MySQL and PostgreSQL compatible.
- Faster for cost, Highly available, easy setup, pay as you go pricing.
## Cloud Architecture
- In an AWS well-architected framework there are 6 basic pillars.
### 6 Pillars 
- Operational Excellence
- Security
- Reliability
- Performance Efficiency
- Cost Optimization
- Sustainibility
### Operational Excellence
- Ability to support development + run workloads efficiently.
- Ability to gain insight into operations & keep improving supporting processes to improve efficiency & deliver business value.
- 4 practice areas for operational excellence in the cloud are organization, prepare, operate, and evolve.
### Security
- Ability to protect your data, systems, and assets.
- Ability to take advantage of cloud assets to improve security.
- 6 practice areas for security in the cloud are Security, Identity and Access Management, Detection, Infrastructure Protection, Data Protection andIncident Response.
### Reliability 
- Ability of a workload to perform it's intended function correctly + consistently when needed.
- Ability to test + operate workload through it's lifecycle.
- 4 practice areas for reliability in the cloud are foundations, workload architecture, change management, and failure management.
### Performance Efficiency
- Ability to use computing resources efficiently & meet system requirements.
- Ability to maintain efficiency as demand changes and technology evolves.
- 4 practice areas for Performance Efficiency in the cloud are selection, review, monitoring, and tradeoffs.
### Cost Optimization 
- Ability to deliver operations at business value at the lowest possible price.
- 5 practice areas for Cost Optimization in the cloud are Practice Cloud Financial Management, Expenditure and usage awareness, Cost-effective resources, Manage demand and supply resources, and Optimize over time.
### Sustainibility
- Ability for architecture to stay environmentally sustainable.
- 6 practice areas for Sustainibility are Region selection, User behavior patterns, Software and architecture patterns, Data patterns, Hardware patterns, Development and deployment process.
### Availability
- Period of time when a service is available + time required by system to respond to a user.
- Availability = "Available for Use Time" / "Total Time"
- Fault Tolerance, Scalability, and Recoverability influence this.
- High Availibility is important for good architecture.
### AWS Well-Architectured Tool + Trusted Advisor
- The AWS WA tool reviews your architecture and compares it to the latest AWS architecture and best practices.
- You can use this to improve your architecture.
- AWS Trusted Advisor gives you real time guidance to follow AWS best practices.
## Automatic Scaling And Monitoring
### Load Balancing
- Practice of distributing computational workloads between two or more computers.
- Typically employed to divide network traffic among several servers.
- Dividing network traffic amongst several servers reduces strain and improves server efficiency.
- Essential for a majority of internet applications to run properly.
- Typically handled by a hardware or software based tool/application called a "load balancer"
### IT monitoring
- The monitoring of IT infrastructure to determine it's performance in real time.
- Real time IT monitoring allows for issues to be found easily and for them to be solved with well-informed decision-making.
### 3 Majors Components of IT Monitoring
- Sensors that generate raw data from network nodes
- Analytics solutions that process this data into information
- UI interfaces that visualize intuitive and insightful reports
### Common Types of IT Monitoring 
- System Monitoring
- Dependency monitoring
- Integration and API monitoring
- Business Activity Monitoring (BAM)
- Web performance monitoring
- Application Performance Monitoring (APM)
- Real User Monitoring (RUM)
- IT monitoring in modern SDLC frameworks
- Security Monitoring
### Autoscaling
- Cloud computing technique that is for dynamically allocating computational resources.
- Enables organizations to scale cloud services such as server capacities or virtual machines up or down automatically, based on defined situations such as traffic ir utilization levels. 
- AWS offers an autoscaling tool Ex: AWS EC2
### AWS Elastic Load Balancing
- Feature that automatically distributes incoming traffic across multiple targets which can be EC2 Instances, Containers, or IP addresses.
### AWS Cloudwatch
- AWS service that monitors your resources and applications in real time.
- Used to track metrics and collect them.
