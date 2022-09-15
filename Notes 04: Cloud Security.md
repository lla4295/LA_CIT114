# Notes 04: Cloud Security
### 1. Summarize a few key points made in the readings or videos.
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
### 2. Identify and provide two quotes that were made in the readings or videos, that you found interesting. Describe why you found each quote of them interesting.
> “Security is now in the job of informing the teams about the risks of their actions.” - (6.16 Putting the Security into DevOps - The Rise of DevSecOps)
- I found this quote interesting because it shows that enforcing company policy and education of employees is a huge part of security. It really isn't just hacking, and securing systems.

> “Let’s move from patching broken code, to protecting ourselves as the code is built, tested and delivered.” - (6.16 Putting the Security into DevOps - The Rise of DevSecOps)
- I found this quote interesting because it puts an emphasis on securing code as it is built rather than fixing it after it is made, I think this development mindset
,DevSecOps is very smart.

### 3. Outline the new facts that you learned from this section?
- Learned what cybersecurity was.
- Learned ways to improve cybersecurity.
- Learned about AWS and customer security responsibilites. (Security and Compliance Model)
- Learned about IAM management, essentials, and ways to use it.
- Learned about applications for securing accounts, data, and compliance.

### 4. What questions remain in your mind after reading this section?
- N/A

