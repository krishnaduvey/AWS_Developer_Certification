### AWS services and the limits for the 

1. VPCs per region: 5
1. 5 VPC per region, more on request
1. Subnets per VPC: 200
1. Route tables per VPC: 200 (including main route table)
1. Network ACLs per VPC: 200
1. Active VPC peering connections per VPC: 50
1. Outstanding VPC peering connection requests: 25
1. Internet Gateway per region: 5
1. Virtual private gateway (VGW) per region: 5
1. Customer Gateway (CGW) per region: 50
1. VPN connections per region: 50
1. Entries per route table: 50
1. Elastic-IP (EIP) per region for each account: 5
1. Security groups per VPC: 100
1. Security groups per network interface: 5
1. Rules per security group: 50 (per network interface max limit: 250)
1. Rules per ACL: 20
1. BGP advertised routes per VPN Connection: 100


### VPC limits
1. 5 internet gateways per account, equal to VPC limit
1. 5 virtual private gateways and 5 customer gateways
1. 1 internet gateway attached to a subnet at a time
1. 1 subnet can only be in 1 availability zone
1. 50 customer gateways per region
1. 50 VPN connections per region
1. 200 route tables per region
1. 200 subnets per amazon vpc
1. 5 elastic IP addresses
1. 100 security groups
1. 50 rules per security group
1. Under AWS you will have 251 IP addresses, opposed to industry standard 254. And these 4 IP's are reserved for AWS. 


### SQS Related Timeout limits.

1. Messages in the Queue can be **retained** for up to 14 days. (How long can I keep my messages in Amazon SQS message queues) --> 1 minute to 14 days. By default it's 4 days.
  1. 1 --> 4 --> 14
1. Visibility timeout by default is 30 Seconds up to 12 hour maximum 
1. Maximum long polling timeout 20 seconds
1. SQS - Message can contain upto 256KB of text, billed at 64KB chunks,
1. Single request can have 1 to 10 messages unto maximum of 256KB payload
1. Even though there is one message of 256Kb its basically 4 request for billing since (4 * 64KB)

### CloudWatch
1. 1 minute data point are available for 15 days.
1. 5 minute data points are available for 63 days.
1. 1 hour data points are available for 455 days.

### RDS
1. How many reserved instances can I purchase? You can purchase up to **40 reserved DB instances**.

### CloudFormation
1. 200 Stacks per account.
1. There is no limit on the number of templates that you can create.
1. Template, Parameter, Output, and Resource description fields are limited to 4096 characters.
1. You can include up to 60 parameters and 60 outputs in a template.

### Cloudwatch
1. 2 weeks : 
1. 15 Months : 

### S3 
1. 100 Buckets per account.

### IAM
1. 
Q) How many policies can be added. 
For inline policies: **You can add as many inline policies as you want to a user, role, or group,** but the total aggregate policy size (the sum size of all inline policies) per entity cannot exceed the following limits:

User policy size cannot exceed **2,048** characters.
Role policy size cannot exceed **10,240** characters.
Group policy size cannot exceed **5,120** characters.

For managed policies: You can add up to 10 managed policies to a user, role, or group. The size of each managed policy cannot exceed **6,144** characters.
1. You are limited to 1,000 IAM roles under your AWS account.





## Other important aspects of the AWS.

IAM policy --> 

