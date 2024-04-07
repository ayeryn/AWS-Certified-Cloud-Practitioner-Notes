# Notes
- Amazon CodeGuru
    - code review

- Amazon CodeWhisperer
    - AI-powered code generator

- AWS CodeCommit: source code version control service. CodeCommit helps users store and manage developers' source code in AWS.

- AWS CodePipeline
    -  Automate continuous delivery pipelines for fast and reliable updates
    - manages the __movement__ of code between the individual services. 
    - not source code storage

- Amazon Inspector: automated and continual __vulnerability__ management at scale
    - Audits a single EC2 instance
    - generates a report from a long list of security checks, i.e. 699 checks

- Trusted Advisors
    - doesn't generate out a PDF
    - Gives you a holistic view of recommendations
    - Not just for security

- Amazon CloudTrail
    <details markdown=1><summary markdown='span'>Answer</summary>
    API calls, who did what, who to blame
    </details>

- AWS Artifact
    <details markdown=1><summary markdown='span'>Answer</summary>
    No cost, self-service portal for on-demand access to __compliance reports__ and for entering into select online __agreements__.
    </details>
 
 - AWS EMR 
    <details markdown=1><summary markdown='span'>Answer</summary>
    
    - Big data

    - serverless
    </details>

- Shared Controls – Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services. Examples include:    

    - __Patch Management__ – AWS is responsible for patching and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.
    - __Configuration Management__ – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.
    - __Awareness & Training__ - AWS trains AWS employees, but a customer must train their own employees.
    - Responsibilities vary depending on the services used

- Security Groups v NACL
    - Security Group: firewall at the **instance** level
        - ALLOW only
    - NACL: firewall at the **subnect** level
        - ALLOW or DENY

- AWS Health Dashboard
    - Detailed __troubleshooting__ guidance to address AWS events impacting your resources.
    - Personalized view of AWS __service health__.

- AWS Quick Starts
    - By using best practices and automating hundreds of manual procedures, Quick Starts can help you __deploy popular technologies__ to AWS in minutes.

- What are the characteristics of Amazon S3?    
	- S3 allows you to store unlimited amounts of data    
	- Objects are directly accessible via a URL
    - A durable storage system
    - static website
    - media data store for the CloudFront service  

- S3 Tiers
    - S3 Standard - General purpose storage for any type of data, typically used for __frequently accessed__ data
    - S3 Intelligent - Tiering - Automatic cost savings for data with __unknown or changing access patterns__
    - S3 Standard - Infrequent Access - For long lived but __infrequently accessed data__ that needs _millisecond access_
    - S3 Express One Zone - _High-performance_ storage for your __most frequently__ accessed data
    - S3 Glacier - long-term backups and archives

- ELB: Distribute network traffic to improve application __scalability__
    - ensures that only _healthy targets_ receive traffic.
    - Application Load Balancers
        - L7 - application - HTTP/s
        - routing rules
        - can attach WAF
    - Network Load Balancers
        - L3 and 4 - TCP and UDP
        - performance required for TCP and TLS traffic
        - ultra-low latencies
        - sudden and volatile traffic
    - Gateway Load Balancers
        - GENEVE
    - Classic Load Balancers (retired)
        - L3, 4, 7
        - for apps built within EC2-Classic

- EBS - Elastic Block Storage
    - easy-to-use, scalable, high-performance block-storage service designed for _Amazon EC2_
    - database with high read/write activity
    - Amazon EBS volumes
        - These are storage volumes that you attach to Amazon EC2 instances. After you attach a volume to an instance, you can use it in the same way you would use a local hard drive attached to a computer, for example to store files or to install applications.
        - Amazon EBS snapshots — These are point-in-time backups of Amazon EBS volumes that persist independently from the volume itself. You can create snapshots to back up the data on your Amazon EBS volumes. You can then restore new volumes from those snapshots at any time.
    
- AWS RDS
	- Automated patches and backups
	- You can resize the capacity accordingly

- reliability of AWS
	- Automatically provisioning new resources to meet demand
	- Ability to recover quickly from failures

- SNS
    - Pub/Sub
    - Emails, webhook applications
    - doesn't guarantee delivery

- SQS
    - Queueing
    - _Retain_ messages for up to 14 days
    - Good for delayed tasks

- Sending Emails
    - SNS: practical and internal emails
        - triggered by other AWS resources
        - plaintext emails, like billing alarms
    - SES: transactional emails
        - triggered by in-app functions: signup, password reset, etc.
        - HTML emails
    - PinPoint: promotional emails
        - emails for marketing campaigns
    - WorkMail: Email web client like Gmail


- SaaS
    - don't have to worry about how the service is maintained.
    - it just works and and remain available
- PaaS
    - don't worry about provisioning, configuring, or understanding the hardware or OS
    - EB
- IaaS
    - don't worry about the IT staff, datacenters or hardware
    - EC2

- EB: deploy and scale web applications, like Heroku

- Compute Saving Plan
    - _EC2_ instance usage regardless of instance family, size, Availability Zone, Region, OS, or tenancy
    - _Fargate_ usage
    - _Lambda_ usage for Duration, Provisioned Concurrency, and Provisioned Duration

- AWS Pricing Calculator
    - AWS Pricing Calculator is a free web-based planning tool that you can use to __create cost estimates__ for using AWS services. 
    - Use cases:
        - Model your solutions before building them
        - Explore AWS service price points
        - Review the calculations behind your estimates
        - Plan your AWS spend
        - Find cost saving opportunities

- CloudFormation: enables you to create and provision AWS __infrastructure deployments__ predictably and repeatedly.
    - __IaC__

- AWS OpsWork: provides a simple and flexible way to __create and manage stacks and applications__. 
    - With AWS OpsWorks, you can provision AWS resources, manage their configuration, deploy applications to those resources, and monitor their health.

- What AWS service has built-in DDoS mitigation?
    - You can use AWS services that operate from _edge locations_   
        - Amazon CloudFront (CDN)
        - AWS Global Accelerator: a network layer service in which you create accelerators to improve the security, availability, and performance of your applications for local and global users.
        - Amazon Route 53 (DNS)


- Aurora: built-in fault tolerance and automated failover capability

- AWS Transit Gateway: a network transit hub that you can use to __interconnect__ your virtual private clouds (VPCs) and on-premises networks

- ACM: AWS Certificate Manager helps you to provision, manage, and renew publicly trusted __TLS__ certificates on AWS based websites.

- Amazon Comprehend uses natural language processing (_NLP_) to extract insights about the __content of documents__ without the need of any special preprocessing. 

- AWS Service Catalog: enables organizations to create and manage catalogs of _IT services that are approved for AWS_. These IT services can include everything from virtual machine images, servers, software, databases, and more to complete multi-tier application architectures.

- AWS CAF (Cloud Adoption Framework)
    - a set of best practices, tools, and guidance that helps organizations get started with cloud technologies. 
    - Governance
    - Business
    - People
    - Platform
    - Security
    - Operations

- DynamoDB
    - Automatically scales to meet required throughput capacity.
    - Offers extremely low (single-digit millisecond) latency.

- Data at-rest
    - Versioning
    - Permissions

### _CONNECT_ services
- Direct Connect: Dedicated Fiber Optics Connection
    - on premise -> AWS
    - fast and **private**

- Amazon Connect: Call Center as a service

- Media Connect: new version of Elastic Transcoder
    - converts videos to different video types
    - overlays images, insert video clips, robust UI

### Migrations
- AWS Application Discovery Service
    - __plan application migration__ projects by automatically identifying applications running in on-premises data centers, their associated dependencies, and their performance profile.

- AWS MGN: Application Migration Service
    - automated lift-and-shift solution. This solution can __migrate physical servers and any databases or applications__ that run on them to EC2 instances in AWS.

- AWS DMS (Database migration service)
    - a web service you can use to __migrate data__ from 
        - on-premise database
        - Amazon RDS DB instance
        - database on EC2 instance 
    - to a database on an AWS service. 

- Amazon Snowball
    - Easily __migrate__ terabytes of data to the cloud without limits in storage capacity or compute power.

    - Accelerate application performance in disconnected, austere edge environments and __run compute workloads__ with little or no connectivity.
    
    - __Protect your data__ in transit with Snowball’s ruggedized chassis, integrated logistics, and tamper-evident box, and get data to the right place quickly.

- AWS Storage Gateway
    - a service that connects an __on-premises software appliance with cloud-based storage__ to provide seamless and secure integration between your on-premises IT environment and the AWS storage infrastructure in the AWS Cloud.

- AWS MAP (Migration Acceleration Program)
    - a comprehensive and proven cloud migration program based upon AWS’s experience migrating thousands of __enterprise customers__ to the cloud. 
    - AWS Partners
    - AWS Professional Services: a global team of experts that can help you realize your desired business outcomes when using the AWS Cloud. 
    - AWS investments