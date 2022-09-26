# Notes 07: Storage
## 1. Summarize a few key points made in the readings or videos.
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
## 2. Identify and provide two quotes that were made in the readings or videos, that you found interesting. Describe why you found each quote of them interesting.
> "One of the things IT professionals must think about is how can we protect data from being compromised both at rest and in transit. Encryption is a method securing data by taking data and making it unreadable without the right decryption information." (9.05 Encrypting Storage)
- I found this quote interesting because I have an interest in cybersecurity and learning about storage data encryption is fun.
> "The Caesar Cipher (Links to an external site.) is one of the most historically well-known ciphers this is known as a substitution cipher where one letter is substituted for another." (9.05 Encrypting Storage)
- I found this quote interesting because I've heard about the Caesra Cipher before but I didn't do extensive research into it. From this, I was able to learn what it was and how it relates to data encryption.
## 3. Outline the new facts that you learned from this section?
- Learned about storage mediums and the two types, volatile and non-volatile.
- Learned about Disaster Recovery methods and practices for IT infrastructure.
- Learned about RAID, the 5 levels of it, and what each level doesw.
- Learned about how storage functions in the cloud.
- Learned about AWS Cloud Storage Services and their uses.
## 4. What questions remain in your mind after reading this section?
- Is AWS/Amazon responsible for the encryption of data in cloud storage?
- Who would be responsible for a AWS cloud storage data breach?
