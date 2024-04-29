# 1st-AWS-project

(VPC with servers in private subnets and NAT)

I have created a VPC that is used for servers in a production environment. To improve resiliency, the servers are deployed in two availability zones, using the auto-scaling groups and application load balancer. For more security, I deployed the servers in private subnets. The servers receive request through the Load balancer. The server can connect to the internet via NAT gateway. To improve resiliency , you can deploy the NAT gateway in the both Availability zone.

NOTE- I have completed the 1st AWS project with the help of AWS Documentation ,with this project, I can confidently create VPCs,Public subnets,Private subnets Application load balancer,s3 gateway,NAT gateway,Auto-scaling groups,Availability zones and Region.
