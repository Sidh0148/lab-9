# lab-9
Report: Cloud Migration Cost Analysis for ShopPro International

Provide a high-level summary of the project objectives, including the goals of migrating ShopPro International’s infrastructure to the cloud. Briefly outline the expected benefits, such as cost savings, improved scalability, and enhanced reliability across ShopPro’s global operations.

Cloud migration cost:
Services	Monthly Cost
AWS Data Transfer	$1443.60
AWS Database Migration Service	$2253.2
EC2	$17,687.90

Data transfer cost is helping to migrate the data from the on-premises to cloud services for that first need to put estimation for data after that deploy the storage on cloud platform 25tb of data.

Database migration services are helping for SQL and NOSQL databases in which need a type of database instance types that match the memory and CPU requirements, then select the appropriate storage for the data and location for the redundancy and transferring 5124gb of data using t3.medium instance.
10-EC2 is used for the time estimated needed for migration estimate storage needs for staging data. While migrating the data from on-premises to clous platform need some virtual machines to transfer data and handle the load

Operational cost
Services 	Monthly cost
Amazon EC2	$4842.56
Amazon RDS for MySQL	$ 8,305.83
Amazon DynamoDB for NOSQL	$10,964 upfront and $4,756.03 monthly cost
Amazon Redshift (for data warehouse)	$ 4,548.40
Amazon Simple Storage Service	$ 48.18
	
	

For operational cost amazon EC2 is used for virtual machines, for this 20 virtual machines are deployed and extra 10 are used for monthly spikes.
Amazon RDS for MYSQL is set for 5tb and backup retention
DynamoDB for NoSQL, setting storage (10 TB) and read/write throughput based on usage.
S3 and specify 15 TB storage and query processing costs.
S3 for backup storage and select geo-redundant (cross-region replication) options for each region.

Management Cost:
Services	Monthly cost
Amazon CloudWatch	$96.01
AWS IAM Access Analyzer	$30.00

CloudWatch for logging, custom metrics, and security alerts, Estimate metrics retention, especially for logs and analytics.
IAM for security management, and resource tagging to enable cost allocation.

Cost Optimization Choices
Choosing pay as you go model other than reserved instance will reflect a good cost optimization for EC2
For fixed instances it costs $6719.8 for 30 vm’s for pay as you go model the vm’s in actual used is 20 and 10 additional for peak usage it costs $4842.56
DynamoDB Upfront Cost: You have a $10,964 upfront cost for DynamoDB. In a pay-as-you-go model, you would only pay for what you use monthly, allowing you to retain cash flow and avoid a high upfront expenditure.
RDS, and Redshift services, pay-as-you-go lets you scale resources up or down based on actual demand. This flexibility prevents you from over-provisioning and paying for unused capacity. If demand decreases, you can instantly scale down and reduce costs.
Future Growth and Budget Plan
Over the next three years the anticipated growth in users and data volume requires a budget increase of 10-15% annually
The annual cost associated with the 
Year	Projected Monthly cost	Estimated annual Increase
Year 1	$401,556	10%
Year 2	$441711	10%
Year 3	4485882	10%
