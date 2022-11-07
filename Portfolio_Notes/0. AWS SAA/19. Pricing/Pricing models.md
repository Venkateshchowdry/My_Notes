# Pricing

### 4 models
1. Pay as you go :
2. Save when you reserve:
	applicable for EC2, Dynamo DB, Elastic cache, RDS, Redshift
3. Pay less by using more:
4. Pay less as aws grows:

### Free Tire
IAM
VPC
Consolidated billing
{ Elastic Bean Stalk, Cloud Formation, Auto Scaling Group}-we pay for the resources created.
Free Tier: EC2 t2.micro. S3 EBS, ELB. AWS data transfer,

### Compute Pricing
1. On demand Instance: Pay/sec(linux/win) other-pay/hr
2. Reserved Instance: 75% discount but we have to take 1/ 3 years 
3. Spot instance: 90% discount 
4. dedicated hosts: reserved for 1/ 3 years commitment
5. savings plan: alternative to save on sustained usage

#for lambda:   pay/ call/ duration
#for ECS: EC2 launch type model:aws resouces created and stored in your application
#for Fargate: Fargate launch type model: pay for vCPU and memory resouces allocated to your applications in containers.
#for Storage S3: based on data volume transfer out of the S3
#for EBS: gb/month-provisioned
#for RDS: per hour billing
backup storage- no additional cost if is it in same region.

#for Networking:![[Pasted image 20220920011920.png]]


### Savings plan: 
commit certain $ amount / 1 or 3 years- long term commitments
#EC2 Savings plan: commit to usage of individual instance families in a region- up to 72% disc
#Compute Savings plan: up to 66% disc-regardless of everything

### AWS compute optimizer
Recommends optimal resources for your workloads- to reduce cost and maximise performance

### Billing and costing tools
1. Estimating Costs: Pricing calculator
2. Tracking costs: 
	1. billing dashboards
	2. cost allocation tags: to track costs in detailed level
		1. tags are used for organizing resources
	3. cost and usage reports: dive deep in to cost and usage reports
	4. cost explorer: we can forecast usage up to 12 months based on previous usage with the help of visualization tools
3. Monitoring against costs plans
	1. billing alarms: billing data metrics are stored in cloudwatch us-east-1
	2. budget: allot a budget and send alarm when cost exceeds budget
		1. 2 budgets free then 0.02$/day/budget
		2. 5 sns notification/ budget

## Trusted Advisor
no need to install anything- just high level assessment on 5 categories and give recommendation 
	1. cost optimization
	2. performance
	3. security
	4. fault tolerance
	5. service limits

![[Pasted image 20220920043919.png]]

### for Business Support Plan - 24x7 phone email and chat access
if production system impaired- aws will respond in < 4 hours
	if production system down < 1 hour we will get support
	
### for Enterprise on-ramp Support Plan
- access to a pool of Technical account managers(TAM)
- concierge support team- for billing and acc best practices
- Infrastructure Event Management, Well-Architected & Operations overview
	{
	if production system impaired- aws will respond in < 4 hours
	if production system down < 1 hour we will get support
	} -- same as above
	if Business-critical system down< 30 minutes

### for Enterprise Support Plan
- {
all same as Enterprise on-ramp Support Plan
} + if Business-critical system down< 15 minutes

## Best Practices
![[Pasted image 20220920045553.png]]

