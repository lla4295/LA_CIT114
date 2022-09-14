# Notes 03: Cloud Global Infrastructure
### 1. Summarize a few key points made in the readings or videos.
- AWS has infrastructure all over the world; this allows you to go global in minutes.
- AWS regions are seperate geographic area that AWS uses to house its infrastructure. (Distributed around the world so customers can choose closest location.)
- AWS availability zones are building blocks that make up AWS regions. (AZ's are isolated data center locations within a region.)
- It is recommended to distribute instances over multiple availability zones so if one fails, you have a backup.
- AWS infrastructure is elastic, scalable, fault-tolerant, and highly available.
- AWS serves 245 countries/territories in total, it has 27 launched regions, 87 Availability Zones (AZ's), and 410 points of presence. 
- AWS regions include: North America, South America, Europe, Middle East, Africa, Asia Pacific, and Australia.
- Points of presence consists of data centers close to Edge Locations and Regional Edge Cache servers.
- AWS Local Zone places data centers close to large population, industry, and IT centers.
## Factors to consider when choosing AWS region (Best for workload)
- Supported AWS services - Some AWS services are not available in all regions.
- Cost - Differs based on region.
- Latency - Should be blazing fast, should be picked based on target audience location.
- Security & Compliance - Abide by each countries Data Security and Compliance rules.
- Service Level Agreements - Not all AWS services warrant the same SLA.
- AWS foundational services include compute, storage, databases, and networking.
- *# of Edge Locations > # of Availability Zones > # of Regions*
#### 2. Identify and provide two quotes that were made in the readings or videos, that you found interesting. Describe why you found each quote of them interesting.
> "Amazon Web Services is powered by Data Centers like the one I showed here.  Each Availability Zone is the result of a massive Data Center.  Aren't we glad we didn't have to worry about any of these details..." (5.08 Data Center Concepts)
- I found this quote in the reading interesting because it showed, explained the scale of data centers and stated that it is an advantage of cloud computing. This made me think about how revolutionary/efficient cloud computing really is for organizations.
> "Of all the employees at Google, a very, very small percentage of those employees are authorised to even enter a data centre campus." 
> Joe Kava (VP of Data Centers @ Google) - 5.09 "Inside a Google data center"
- I found this quote in the video interesting because it shows the level of security data centers have. The amount of security measures and restrictions Google implements for their employees and regular people is just insane.

#### 3. Outline the new facts that you learned from this section?
- Learned about AWS global infrastructure.
- Learned about AWS regions, AZ's, and Points of Presence.
- Learned about the difference between Points of Presence & AWS local zones.
- Learned about factors to consider when choosing AWS regions.
#### 4. What questions remain in your mind after reading this section?
- What AWS regions are most popular, do their data centers ever get overloaded w/ customers?

