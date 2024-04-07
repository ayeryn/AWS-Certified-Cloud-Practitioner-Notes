# Practice Exam 1

1. You have noticed that several critical Amazon EC2 instances have been terminated. Which of the following AWS services would help you determine who took this action?
    - A. Amazon Inspector.
    - B. AWS CloudTrail.
    - C. AWS Trusted Advisor.
    - D. EC2 Instance Usage Report.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

4. Which of the below options are related to the reliability of AWS? (Choose TWO)
    - A. Applying the principle of least privilege to all AWS resources.
    - B. Automatically provisioning new resources to meet demand.
    - C. All AWS services are considered Global Services, and this design helps customers serve their international users.
    - D. Providing compensation to customers if issues occur.
    - E. Ability to recover quickly from failures.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E
    </details>

5. Which statement is true regarding the AWS Shared Responsibility Model?
    - A. Responsibilities vary depending on the services used.
    - B. Security of the IaaS services is the responsibility of AWS.
    - C. Patching the guest OS is always the responsibility of AWS.
    - D. Security of the managed services is the responsibility of the customer.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

7. A company has developed an eCommerce web application in AWS. What should they do to ensure that the application has the highest level of availability?
    - A. Deploy the application across multiple Availability Zones and Edge locations.
    - B. Deploy the application across multiple Availability Zones and subnets.
    - C. Deploy the application across multiple Regions and Availability Zones.
    - D. Deploy the application across multiple VPC’s and subnets.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

8. What does AWS Snowball provide? (Choose TWO)
    - A. Built-in computing capabilities that allow customers to process data locally.
    - B. A catalog of third-party software solutions that customers need to build solutions and run their businesses.
    - C. A hybrid cloud storage between on-premises environments and the AWS Cloud.
    - D. An Exabyte-scale data transfer service that allows you to move extremely large amounts of data to AWS.
    - E. Secure transfer of large amounts of data into and out of the AWS.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
    </details>


19. One of the most important AWS best-practices to follow is the cloud architecture principle of elasticity. How does this principle improve your architecture’s design?
    - A. By automatically scaling your on-premises resources based on changes in demand.
    - B. By automatically scaling your AWS resources using an Elastic Load Balancer.
    - C. By reducing interdependencies between application components wherever possible.
    - D. By automatically provisioning the required AWS resources based on changes in demand.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>


31. Which of the following services allows customers to manage their agreements with AWS?
    - A. AWS Artifact.
    - B. AWS Certificate Manager.
    - C. AWS Systems Manager.
    - D. AWS Organizations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

32. Which of the following are examples of AWS-Managed Services, where AWS is responsible for the operational and maintenance burdens of running the service? (Choose TWO)
    - A. Amazon VPC.
    - B. Amazon DynamoDB.
    - C. Amazon Elastic MapReduce.
    - D. AWS IAM.
    - E. Amazon Elastic Compute Cloud.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
    </details>



36. Which of the following must an IAM user provide to interact with AWS services using the AWS Command Line Interface (AWS CLI)?
    - A. Access keys.
    - B. Secret token.
    - C. UserID.
    - D. User name and password.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>


38. Select TWO examples of the AWS shared controls.
    - A. Patch Management.
    - B. IAM Management.
    - C. VPC Management.
    - D. Configuration Management.
    - E. Data Center operations.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D

      __Shared Controls__ – Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services. Examples include:

      - Patch Management – AWS is responsible for patching and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.
      - Configuration Management – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.
      - Awareness & Training - AWS trains AWS employees, but a customer must train their own employees.
    </details>

39. In order to implement best practices when dealing with a “Single Point of Failure,” you should attempt to build as much automation as possible in both detecting and reacting to failure. Which of the following AWS services would help? (Choose TWO)
    - A. ELB.
    - B. Auto Scaling.
    - C. Amazon Athen.
    - D. ECR.
    - E. Amazon EC2.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

43. Under the shared responsibility model, which of the following is the responsibility of AWS?
    - A. Client-side encryption.
    - B. Configuring infrastructure devices.
    - C. Server-side encryption.
    - D. Filtering traffic with Security Groups.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

44. What does the AWS Health Dashboard provide? (Choose TWO)
    - A. Detailed troubleshooting guidance to address AWS events impacting your resources.
    - B. Health checks for Auto Scaling instances.
    - C. Recommendations for Cost Optimization.
    - D. A dashboard detailing vulnerabilities in your applications.
    - E. Personalized view of AWS service health.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
    </details>



47. Which of the following is not a benefit of Amazon S3? (Choose TWO)
    - A. Amazon S3 provides unlimited storage for any type of data.
    - B. Amazon S3 can run any type of application or backend system.
    - C. Amazon S3 stores any number of objects, but with object size limits.
    - D. Amazon S3 can be scaled manually to store and retrieve any amount of data from anywhere.
    - E. Amazon S3 provides 99.999999999% (11 9’s) of data durability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
    </details>


49. What does AWS provide to deploy popular technologies such as IBM MQ on AWS with the least amount of effort and time?
    - A. Amazon Aurora.
    - B. Amazon CloudWatch.
    - C. AWS Quick Start reference deployments.
    - D. AWS OpsWorks.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>
