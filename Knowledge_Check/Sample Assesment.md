AWS Final
Power User Access allows ____.
Access to all AWS services except the management of groups and users within IAM.
When can you attach/replace an IAM role on an EC2 instance?
IAM Roles can be attached to instances in the stopped or running state, or replaced for instances in the running state. Prior to early 2017, you would only be able to attach an IAM role at launch, and if you wanted to attach a role, you would have to terminate and re-launch the instance.
Standard Reserved Instances can be moved between regions
No, standard Reserved Instances cannot be moved between regions. You can choose if a Reserved Instance applies to either a specific Availability Zone, or an Entire Region, but you cannot change the region
In order to enable encryption at rest using EC2 and Elastic Block Store, you must ____.
The use of encryption at rest is default requirement for many industry compliance certifications. Using AWS managed keys to provide EBS encryption at rest is a relatively painless and reliable way to protect assets and demonstrate your professionalism in any commercial situation.
Can Spread Placement Groups be deployed across multiple Availability Zones?
Yes, spread Placement Groups can be deployed across availability zones since they spread the instances further apart. Cluster Placement Groups can only exist in one Availability Zone since they are focused on keeping instances together, which you cannot do across Availability Zones
Where in the AWS Global Infrastructure are EC2 instance provisioned?
Availability Zones, when you're setting up an EC2 instance, you select which subnet you'd like to place your EC2 instance in. Each subnet is tied to a specific availability zone. You cannot move an instance between Availability Zones, without setting up a copied version of the instance. Whilst they exist in Regions, they are not portable across the whole region, nor across the whole globe
DB security groups are used with DB instances that are not in a VPC and on the EC2-Classic platform. When you create a DB security group, you need to specify a destination port number.
No, you don't need to specify a destination port number when you create DB security group rules. The port number defined for the DB instance is used as the destination port number for all rules defined for the DB security group.
What happens to the I/O operations of a single-AZ RDS instance during a database snapshot or backup?
I/O may be briefly suspended while the backup process initializes (typically under a few seconds), and you may experience a brief period of elevated latency.
In RDS, when are changes to the backup window implemented?
When applying changes to the backup window, you can choose either to have the changes done during the next scheduled maintenance window or immediately. The schedule itself is modified right away.
If I wanted to run a database on an EC2 instance, which of the following storage options would Amazon recommend?
Elastic Block Storage (EBS) is recommended block level storage for EC2 instances if you were running a database on an EC2 instance. If the question didn't focus on the solution being on the instance, RDS would be the preferred choice.
What data transfer charge is incurred when replicating data from your primary Amazon RDS MySQL instance to your read replica?
Data transferred between Availability Zones for replication of Multi-AZ deployments is free.
With new RDS DB instances, automated backups are enabled by default?
True
Which AWS DB platform is most suitable for OLTP workloads?
Amazon RDS with provisioned IOPS delivers fast, predictable, and consistent I/O performance that is great for OLTP database workloads.
Which of the following is not a feature of DynamoDB?
DynamoDB is the AWS managed NoSQL database service. It has many features that are being added to constantly, making it a great service to use for many different requirements. The feature which was incorrect is DynamoDB only being single availability zone by default making this the correct answer. DynamoDB is distributed across three geographically distinct datacentres by default, all of the other options listed are valid features of DynamoDB.
DB security groups are used with DB instances that are not in a VPC and on the EC2-Classic platform. When you create a DB security group, you need to specify a destination port number.
You don't need to specify a destination port number when you create DB security group rules. The port number defined for the DB instance is used as the destination port number for all rules defined for the DB security group.
True or False - EC2 Key Pairs, Security Groups, and ELBs are region-specific
True
When using EC2 instances with Dedicated Hosting, which of the following modes are you able to transition between by stopping the instance and starting it again?
The tenancy of an instance can only be change between variants of 'dedicated' tenancy hosting. It cannot be changed from or to default tenancy hosting.
Is Memory a custom CloudWatch metric?
Yes - Remember under the shared security model that AWS can see the instance, but not inside the instance to what it is doing. AWS can see that you have Memory, but how much of the memory is being used cannot be seen by AWS. In the case of CPU AWS can see how much of CPU you are using, but cannot see what you are using if for.
What is the maximum Attribute Name & Value in DynamoDB
There is a limit of 400 KB
By definition, a public subnet within a VPC is one that ____.
Has at least one route in its routing table that uses an Internet Gateway (IGW).
In SQS, how can you reduce cost without compromising service?
SQS long polling doesn't return a response until a message arrives in the queue, reducing your overall cost over time. Short polling WILL return empty responses.
How long can a message be retained in an SQS Queue?
14 days
What data formats are used to create CloudFormation templates?
Only JSON and YAML can be used to create CloudFormation templates
How many minutes would elapse between metrics being sent to CloudWatch?
Using the default settings metrics are sent every 5 minutes to CloudWatch. Using the detailed settings, metrics are then sent every 1 minute.


Final Assesment
An organization performs a risk management exercise as it relates to server security. Experts examine a workflow that involves the replication of files from one server to another. The replication is found to not use any form of encryption for data. The experts document this finding during which phase of the exercise?
Identification of known vulnerabilities
Identification of mission-critical functions
Identification of potential threats
Identification of risk responses
Identification of known vulnerabilities

Identification of any vulnerabilities for each function or workflow is useful in determining what risk exists and how to harden systems. Unencrypted data and communications is susceptible to an attack.
When managing risk, experts refer to the four common phases of Identify, Assess, Control, and Review as which concept?
Framework
Lifecycle
Categories
Capabilities
Lifecycle

Risk management tasks are defined by a life cycle. The four major phases common to all risk management life cycles include Identify, Assess, Control, and Review.
____ form the basis of a risk management program and also serve as an authoritative reference. The NIST Cybersecurity Framework is a popular framework that helps organizations define five core functions within a cybersecurity program.
Risk frameworks
People, Processes, and Technologies are types of ___. When designing and implementing controls identified via the risk management program, careful analysis determines which controls are used.
control categories
The _______ deconstructs the capabilities of a successful and comprehensive cybersecurity program into five capabilities including Identify, Protect, Detect, Respond, and Recover.
NIST cybersecurity framework
An organization plans to sign an agreement with a new technology services vendor. Currently, the services that the organization receives are detrimental such that a lock-in scenario exists. Evaluate the statements and determine which best describes the organization's current situation.

A vendor's product is developed in a way that makes it inoperable with other products.

Determining if a vendor will be in business on an ongoing basis.

Being completely dependent on a vendor for products or services because switching is impossible.

Verifying the type and level of support to be provided by the vendor in support.
Being completely dependent on a vendor for products or services because switching is impossible.


A vendor lock-in describes when a customer is completely dependent on a vendor for products or services because switching is either impossible or would result in substantial complexity and costs.
A _______ describes when a vendor's product is developed in a way that makes it inoperable with other products. Integration with other products is usually not feasible or it does not exist.
vendor lockout
Engineers that support the software systems within an organization implement the use of the Capability Maturity Model Integration (CMMI) to measure functionality and capability. Currently, a score of Level 2: Managed is assigned to the systems. Which statement describes the current state of the software applications?

A. Many work activities are defined via processes but work is still frequently reactive in nature.
B. The majority of work is well-defined via processes and proactive measures are in place.
C. Processes do not exist and work is reactive in nature.
D. Work is well-defined via processes, work is proactive, and is measured.
A. Many work activities are defined via processes but work is still frequently reactive in nature.

Capability Maturity Model Integration (CMMI) describes five levels of maturity within the operational or software capabilities of an organization. Level 2 Managed refers to many work activities being defined via processes, but work is still frequently reactive in nature.
CMMI Level _ Defined means that the majority of work is well-defined via processes and proactive measures are in place.
3
CMMI Level _ Initial is a state where the processes do not exist and are not defined. Work is reactive in nature within the organization's systems.
1
CMMI Level _ Optimizing is the highest level. At this level, work is well-defined via processes, work is proactive, measured, analyzed, and continuously improved.
5
Security consultants suggest a tabletop exercise be performed to evaluate incident response procedures. In doing so, what do the consultants suggest as part of the exercise? (Select all that apply.)
Evaluate plans for feedback
Assign a representative to analyze plan effectiveness
Identify and act upon a specific objective
Respond to an imaginary event
Identify and act upon a specific objective
Respond to an imaginary event

A tabletop exercise will identify a specific objective and then use it to determine whether all parties involved in the response know what to do and how to work together to complete the exercise.
Developers at an organization look to place security concerns at the forefront of application development. If the developers choose to utilize dynamic application testing, which element do they put in place?
SecDevOps
Infrastructure as Code
Security as Code
Spiral Method
Security as Code (SaC)

Security as Code (SaC) is an element of SecDevOps that uses automated methods to introduce static code analysis testing and dynamic application testing (DAST) as applications are developed.
___ places security at the forefront of development efforts. Two essential elements to ______ are Security as Code (SaC) and Infrastructure as Code (IaC).
SecDevOps
____ leverages configuration management tools to control infrastructure changes.
Infrastructure as Code (IaC)
An organization considers a federation approach when it comes to credential management. For what reason might the organization consider this solution?
Peer trust models can avoid a single point of failure.
The use of a digital signature allows the relying party to trust the identity provider.
To retain a single account for all participating networks.
A network needs to be accessible to more than just a well-defined group of employees.
A network needs to be accessible to more than just a well-defined group of employees.

Federation is the notion that a network needs to be accessible to more than just a well-defined group of employees. In business, a company might need to make parts of its network open to partners, suppliers, and customers.
Management at a large financial firm maps out a data life cycle plan. During the process, regulatory restrictions are considered when defining which phase? (Select all that apply.)

Archive
Create
Use
Destroy
Archive
Destroy

When data is no longer used on a regular basis, it can be archived to help reduce costs and complexity. Important considerations include the legal and regulatory requirements governing retention periods.
When data is no longer needed and authorized for destruction, defining the legally compliant methods for its destruction is critically important.
Systems Administrators at a manufacturing company deploy a virtualized infrastructure while utilizing a virtual desktop (VDI) approach. By doing so, the administrators deploy which solutions? (Select all that apply.)
Containers
Thin client
Minimal OS
Thick client
Thin client
Minimal OS

Virtual desktop infrastructure (VDI) refers to using a virtual machine (VM) as a means of provisioning corporate desktops. In a typical VDI, desktop computers are replaced by low-spec, low-power thin client computers.
A virtual desktop infrastructure (VDI) uses a virtual machine (VM) as a means of deploying corporate desktops. When the thin client starts, it boots a minimal OS.
Wireless engineers at a large communications provider rollout Wi-Fi Protected Access 3 (WPA3) at a client site. Which security features influence the decision to utilize WPA3 over WPA2? (Select all that apply.)
Simultaneous Authentication of Equals (SAE)
AES Galois Counter Mode Protocol (GCMP)
4-way handshake authentication
AES CCMP
Simultaneous Authentication of Equals (SAE)
AES Galois Counter Mode Protocol (GCMP)

With WPA3, the Simultaneous Authentication of Equals (SAE) protocol replaces the 4-way handshake, which has been found to be vulnerable to various attacks. SAE uses the Dragonfly handshake.
AES Galois Counter Mode Protocol (GCMP) replaces the AES CCMP mode of operation. Enterprise authentication methods must use 192-bit AES, while personal authentication can use either 128-bit or 192-bit.
A systems security engineer deploys several new workstations in an organization. While doing so, a hardware security module (HSM) is also deployed for security services. What solution has the engineer provided by utilizing the HSM?
Unchangeable asymmetric private key
The use of digital certificates
An archive and escrow for keys
Record the presence of unsigned kernel-level code
An archive and escrow for keys

A hardware security module (HSM) is a network appliance designed to perform centralized PKI management for a network of devices. It can act as an archive or escrow for keys in case of loss or damage.
A security engineer utilizes the Extensible Authentication Protocol (EAP) between client workstations and server systems. If the solution uses public key certificates on both clients and servers, which EAP implementation does the engineer deploy?
Protected Extensible Authentication Protocol (PEAP)
EAP Tunneled Transport Layer Security (EAP-TTLS)
EAP Transport Layer Security (EAP-TLS)
EAP with Flexible Authentication via Secure Tunneling (EAP-FAST)
EAP Transport Layer Security (EAP-TLS)

EAP Transport Layer Security (EAP-TLS) is one of the strongest types of authentication. An encrypted Transport Layer Security (TLS) tunnel is established between a client and a server using public-key certificates on the server and client.
____ uses an encrypted tunnel established between the supplicant and authentication server, but ____ only requires a server-side public key certificate.
Protected Extensible Authentication Protocol (PEAP)
_____ uses a server-side certificate to establish a protected tunnel through which the user's authentication credentials can be transmitted to the authentication server.
EAP Tunneled Transport Layer Security (EAP-TTLS)
_____ uses a Protected Access Credential (PAC), which is generated for each user from the authentication server's master key.
EAP with Flexible Authentication via Secure Tunneling (EAP-FAST)
Systems administrators hope to learn details about recent attacks on a portion of a company's network. In doing so, which deceptive tool do the administrators utilize when tight control and monitoring is the goal?
Honeynet
Honeypot
Decoy files
Simulator
Honeynet

A honeynet contains several honeypots attached to a tightly controlled and heavily monitored network.
Developers that are working on a web application use coding practices to prevent insecure references. Several months after deployment of the application, testers discover that at times the application is running in a controlled state. What vulnerability have testers uncovered?
Security misconfiguration
Poor exception handling
Weak cryptography implementations
Information disclosure
Poor exception handling

Poor exception handling describes when an application is not written to anticipate problems or safely manage them to leave the application in a controlled state.
A security administrator establishes several certification authority servers on a private network. Part of the configuration utilizes cross-certification. How does this approach benefit from issuing a certificate?
Multiple departments are combining resources.
Trusted providers can be expanded or reduced.
A single authority issues certificates to several intermediate authorities.
A single authority issues certificates to users.
Multiple departments are combining resources.

Cross certification describes when a certificate is used to establish a trust relationship between two different certification authorities (CA). This can be useful when different organizations are combining resources.
____ describe the set of root CAs that are trusted to validate an identity. Certificates signed by a _____ will in turn be trusted. ________ can be expanded or reduced as appropriate.
Trusted providers
Experts perform risk management activities at an organization. During which phase are quantitative and qualitative methods useful?
Identification of risk responses
Identification of known vulnerabilities
Identification of potential threats
Analysis of business impacts
Analysis of business impacts

The analysis of business impacts uses quantitative and qualitative methods to analyze impacts and likelihood of a risk.
A network system that recently moved from on-premises to the cloud experiences a security breach. Investigators research and determine the cause. Of the findings, what is the Cloud Service Provider (CSP) responsible for? (Select all that apply.)
Tenant resource identity and access control
Physical security of the infrastructure
User identity management
Data and application security configuration
Tenant resource identity and access control
Physical security of the infrastructure

A cloud tenant is the account holder for the cloud service. This account is required to access cloud services. Tenant resource identity and access control are the responsibility of the cloud service provider (CSP).
Network administrators look to harden a corporate network. Initial testing results in discovering that wireless signals from the private network extended further into a public area than expected. How have the administrators discovered this vulnerability?
Software Composition Analysis
Vulnerability scans
Fuzz testing
Persistence
Vulnerability scans

Vulnerability scans, such as a wireless scan, can identify the configuration and signal coverage of an organization's wireless network, for example, to determine if the hardware is vulnerable to known attacks.
An application specialist suggests using a particular application in a virtualized environment to avoid configuring additional workstations for the sake of using one piece of software. What does the specialist suggest using?
Containers
Thin client
Minimal OS
Thick client
Containers

Application cell/container virtualization dispenses with the idea of a hypervisor and instead enforces resource separation at the operating system level. The OS defines isolated "cells" for each user instance to run in.
A company requests that a newly implemented cloud presence be strengthened with a resilient architecture. Engineers suggest heterogeneity. If management at the company agrees, which solution will be implemented?
Distributed allocation of resources
Using solutions from different vendors
Copy data to where it can be utilized most effectively
Allow multiple redundant processing nodes
Using solutions from different vendors

Heterogeneous, or diverse, components are components that are not the same as or similar to each other. In an enterprise, these translate to the use of multiple vendor products in a security solution
An engineer discovers that an attack occurred on a system via a backdoor through a connected application. What enabled this form of attack?
Middleware
Library
Container
API
API

APIs provide the core mechanisms that enable the integration and orchestration of application integration. APIs can be exploited to gain access to protected features of the underlying platform or used to extract sensitive data.
A development team integrates incremental and waterfall methods while managing a software development project. What approach does the team use to manage the project lifecycle?
SecDevOps
Infrastructure as Code
Spiral method
Security as code
Spiral method

With a spiral development model, teams combine several approaches to software development, such as incremental and waterfall, into a single hybrid method. Development is modified repeatedly in response to stakeholder feedback.
During a data life cycle plan, regulatory restrictions aren't usually a concern during which phases? (Select all that apply.)
Create
Use
Archive
Destroy
Create
Use

Data creation pertains to office productivity files, manual data entry, data interfaces, external feeds, automated capture, databases, files systems, and more.

How data is used to support operational needs and objectives pertains to how it is viewed, manipulated/processed, and saved/overwritten or deleted.
An internal cloud application at an organization requires additional storage space. Engineers configure a storage area network to satisfy the need. What cloud deployment and service models did the engineers use? (Select all that apply.)
Private cloud
Platform as a Service (PaaS)
Public cloud
Infrastructure as a Service (IaaS)
Private cloud
Infrastructure as a Service (IaaS)

A private cloud is an infrastructure that is completely private and owned by the organization. In this case, the storage is for internal use only.

Infrastructure as a Service (IaaS) is a means of provisioning IT resources such as servers, load balancers, and storage area network (SAN) components quickly.
An application uses encrypted transactional data to record incoming and changing data sets. Which technology does the application use?
Big data
Blockchain
Artificial intelligence
Deep learning
Blockchain

Blockchain describes an expanding list of transactional records which are secured using cryptography. Records are connected in a chain, and each record is referred to as a block.
_____ refers to data collections that are so large and complex that they are difficult for traditional database tools to manage.
Big data
___ is the science of creating machine systems that can simulate or demonstrate a similar general intelligence capability to humans.
Artificial intelligence (AI)
______ is a type of machine learning that de-constructs knowledge into a series of smaller, simpler parts. Complex concepts are broken down into simpler elements of knowledge so they can be used to interpret data.
Deep learning
When using a virtual private network (VPN) on a mobile device, which would provide always-on functionality?
Application
Web-based
Operating system
Location
Operating system

An operating system level VPN offers comprehensive protection of device traffic since they operate at a low level of the operating system and capture all device traffic as a result. OS level VPN can be configured to operate as "always-on."
A security engineer looks to change the Extensible Authentication Protocol (EAP) authentication method between client workstations and server systems. If the current solution uses the Protected Access credential, which EAP implementation does the engineer look to replace?
Protected Extensible Authentication Protocol (PEAP)
EAP Tunneled Transport Layer Security (EAP-TTLS)
EAP Transport Layer Security (EAP-TLS)
EAP with Flexible Authentication via Secure Tunneling (EAP-FAST)
EAP with Flexible Authentication via Secure Tunneling (EAP-FAST)

EAP with Flexible Authentication via Secure Tunneling (EAP-FAST) uses a Protected Access Credential (PAC), which is generated for each user from the authentication server's master key.
Which web traffic protection method is configured on an SSL/TLS web server to periodically obtain a time-stamped Online Certificate Status Protocol (OCSP) response from the certificate authority?
Certificate Pinning
Certificate Stapling
Strict Transport Security
Digital Signature
Certificate Stapling

Certificate stapling resolves certificate pinning issues by having a SSL/TLS web server periodically obtain a time-stamped OCSP response from the CA.
Security engineers perform threat intelligence training. Which approach uses threat intelligence in a practical and actionable way?
Tactical
Operational
Strategic
Emulation
Emulation

Emulation exercises help teams test and improve their skills and capabilities and also force the interpretation and use of threat intelligence in a practical and actionable way.
______ is focused on the big picture leadership-focused information typically associated with reports. The information is used to help identify the motivations, capabilities, and intentions of various threat actors.
Strategic threat intelligence
Systems administrators use a deceptive tool to lure an adversary into a trap that contains false information. What tool have the administrators utilized?
Honeynet
Honeypot
Decoy files
Simulator
Decoy files

A decoy file can include honeytokens and/or canary traps. These decoy files contain data that would be appealing to an adversary but contain false information
Security experts perform forensic activities on a compromised server investigation. Which phase of the investigative process presents legal concerns for the experts?
Identification
Collection
Reporting
Analysis
Collection

During evidence collection, it is important to have the authorization to collect the evidence using tools and methods that will withstand legal scrutiny.
A sysadmin thinks a malicious process is preventing a service from starting on a Windows server. Which event does the log reveal information related to a service that won't start?
Security
System
Application
Forwarded
Application

The Windows Application Event log displays events generated by applications and services. This included information such as when a service cannot start properly.
Systems administrators configure access to a network where each object and each subject is granted a clearance level. Which solution do the administrators configure? (Select all that apply.)
Access Control List (ACL)
Mandatory Access Control (MAC)
SELinux
SEAndroid
Mandatory Access Control (MAC)
SELinux
SEAndroid

Mandatory access control (MAC) is based on the idea of security clearance levels. Rather than defining ACLs on resources, each object and each subject is granted a clearance level, referred to as a label.
In Linux, execution control is normally enforced by using a mandatory access control (MAC) kernel module or Linux Security Module (LSM).
SEAndroid uses mandatory access control (MAC) policies to run apps in sandboxes. When the app is installed, access is granted (or not) to specific shared features.
A penetration tester performs a vulnerability assessment and analysis at a manufacturing firm. The tester uses a packet capture utility to collect the state of an application as it operates. What approach does the tester use to collect information, even if it is encrypted?
Reverse engineering
Dynamic analysis
Side-channel analysis
Static analysis
Side-channel analysis

The side-channel analysis describes inspections of a system and/or software as it operates. Even if traffic is encrypted, information can be collected about the state of an application or information about the endpoints and/or users interacting with it.
______ includes using vulnerability scanning software to identify vulnerabilities and, in a more vigorous approach, penetration testing. A ______ approach requires the evaluation of a system or software while it is running.
Dynamic analysis
____ can be performed in a variety of ways. One method involves manual inspection of source code in order to identify vulnerabilities in programming techniques.
Static analysis
A server was hacked at a small company. Investigators feel that a former employee is the culprit. What intelligence collection method do investigators use to monitor the suspect's social network feeds?
Intelligence feeds
Human intelligence
Deep web
Open-source intelligence
Open-source intelligence

Open-source intelligence refers to using publicly available information sources to collect and analyze data to be used from the perspective of cybersecurity operations. An example is the monitoring of social media networks.
An attacker gains access to a sensitive shared folder. What might a security engineer configure to directly mitigate the problem?
Enable Endpoint Protection
Adjust ACL rules
implement IDS rules
Deploy a script
Adjust ACL rules

Modifying access control list (ACL) rules using access rules can block or limit access to resources, such as blocking access to files and folders or blocking write access from specific accounts.
A forensics team investigates a compromised server. The server is powered on and the team looks to do a live collection of real-time system information. Which tool does the team find suited for the task?
hexdump
strings
vmstat
foremost
vmstat

The vmstat command-line utility is designed to display real-time information about system memory, running processes, interrupts, paging, and I/O statistics.
The ______ utility can be used to extract data from binary files and can display the contents in hexadecimal, decimal, octal, or ASCII formats. _____ inspection is often part of data recovery and/or reverse engineering processes.
hexdump
The ____ command is a Linux-based forensic data recovery utility that uses file carving techniques to extract deleted or corrupted data from a disk partition.
foremost
A security expert examines a server system for malicious processes. Which tool will the experts find helpful in determining dependencies for a process?
readelf
objdump
strace
ldd
ldd

The ldd utility can be used to display a program's dependencies. For example, issuing the command sudo ldd /sbin/poweroff displays all of the shared libraries required by the Linux poweroff command.
A systems administrator looks to harden server systems by first identifying any available and unnecessary services. What solution can accomplish this task efficiently?
Traffic analyzer
Port scanner
HTTP interceptor
Protocol analyzer
Port scanner

A port scanner is used to identify available services running on a device by determining its open ports. A port scanner can be used for network discovery tasks and security auditing.
A _______ is crafted to aid in the analysis of data captured by a sensor. A _______ can provide insights regarding the http sessions by extracting files contained within sessions.
network traffic analyzer
______ are designed to capture traffic in a networked environment and are often configured to store captured traffic for further analysis using other software tools.
Protocol analyzers
Servers at a data center are now protected with a data loss prevention (DLP). A remediation policy is configured such that any user is prevented from copying files, but access to read any files remains. What remediation policy is in place?
Tombstone
Quarantine
Block
Alert
Block

A block policy prevents users from copying the original file but they retain access to it. Users may or may not be alerted to the policy violation, but it will be logged as an incident by the management engine.
_____ quarantines the original file and replaces it with one describing the policy violation and how the user can release it again.
Tombstone policy


AWS FINAL
Which Global Infrastructure identity is composed of one or more discrete data centers with redundant power, networking, and connectivity, and are used to deploy infrastructure?
Availability Zones
Which of the following is NOT one of the Five Characteristics of Cloud Computing?
Dedicated Support Agent to help you deploy applications
You ONLY want to manage Applications and Data. Which type of Cloud Computing model should you use?
Platform as a Service (Paas)
Which of the following options is NOT a point of consideration when choosing an AWS Region?
Capacity availability
AWS Regions are composed of?
Two or more Availability Zones
What is the pricing model of Cloud Computing?
Pay-as-you-go pricing
Which of the following is the definition of Cloud Computing?
On-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user
Which of the following is NOT an advantage of Cloud Computing?
Train your employees less
Which are the 3 pricing fundamentals of the AWS Cloud?
Compute, Storage, and Data transfer out of the AWS�Cloud
Which of the following services has a global scope?
Lambda
What is a proper definition of IAM Roles?
An IAM entity that defines a set of permissions for making AWS service requests, that will be used by AWS services
Which of the following is a an IAM Security Tool?
IAM�Credentials Report
Which principle should you apply regarding IAM Permissions?
Grant least privilege
What are IAM Policies
JSON documents to define Users, Groups or Roles' permissions
Which of the following is an IAM best practise?
Don't use the root user account
Under the shared responsibility model, what is the customer responsible for in IAM
Assigning users proper IAM Policies
What should you do to increase your root account security?
Enable Multi-Factor Authentication (MFA)
Which of the following statement is TRUE?
The AWS CLI can interact with AWS using commands in your command-line shell, while the AWS SDK can interact with AWS programmatically.
Under the Shared Responsibility Model, who is responsible for operating-system patches and updates on EC2 Instances?
The customer
Which network security tool can you use to control traffic in and out of EC2 Instances?
Security Groups
Which EC2 Purchasing Option should you use for an application you plan on running on a server continuously for 1 year?
Reserved Instances
How long can you reserve an EC2 Reserved Instance?
1 or 3 years
Which EC2 Purchasing Option can provide the biggest discount, but is not suitable for critical jobs or databases?
Spot Instances
Which of the following is NOT an EC2 Instance Purchasing Option?
Connect Instances
EBS Volumes CANNOT be attached to multiple EC2 instances at a time.
True
Which EC2 Storage would you use to create a shared network file system for your EC2 Instances?
EFS
Which service can be used to automate image management processes?
EC2 Image Builder
Which statement is CORRECT regarding EC2 Instance Store?
It has a better I/O performance, but the data is lost if the EC2 Instance is terminated
Which of the following is a fully managed native Microsoft Windows file system?
FSx
What is an EBS Volume tied to?
An availability zone
What is an EBS Snapshot?
A backup of your EBS Volume at a point in time
What are AMIs NOT used for?
Add your own IP addresses
Which Load Balancer is best suited for HTTP/HTTPS load balancing traffic?
Application Load Balancer
Which AWS offered Load Balancer should you use to handle hundreds of thousands of connections with low latency?
Network Load Balancer
Which of the following statements is NOT a feature of Load Balancers?
Back-end autoscaling