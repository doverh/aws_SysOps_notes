# Acronyms

## C

Chef Automate - Chef Automate is an enterprise server software package that provides automated workflow for continuous deployment, and insights about managed nodes in a web-based management console. Chef Automate delivers infrastructure automation by including Chef Infra, security and compliance information and enforcement by including Chef InSpec, and automated deployment by including Chef Habitat.

## E

EC2 - Amazon Elastic Compute Cloud (Amazon EC2) provides on-demand, scalable computing capacity in the Amazon Web Services (AWS) Cloud. Using Amazon EC2 reduces hardware costs so you can develop and deploy applications faster.

EFS - Elastic File System - When a SysOps administrator launches new EC2 instances in the new subnets, the EC2 instances are unable to mount the file system.

## F

- FIPS - The Federal Information Processing Standard (FIPS) Publication 140-3 is a US and Canadian government standard that specifies the security requirements for cryptographic modules that protect sensitive information.

## I

Inspector -  is a security vulnerability assessment service that helps improve the security and compliance of your AWS resources. Amazon Inspector automatically assesses resources for vulnerabilities or deviations from best practices, and then produces a detailed list of security findings prioritized by level of severity. Amazon Inspector includes a knowledge base of hundreds of rules mapped to common security standards and vulnerability definitions that are regularly updated by AWS security researchers.

## P

Prometheus - open-source monitoring toolkit for collecting and aggregating time series metrics. If you adopt Prometheus as your monitoring protocol, enable Prometheus metrics in the following section. Amazon Managed Service for Prometheus monitors and provides alerts on containerized applications and infrastructure at scale.

## Q

Queues - Amazon SQS(Amazon Simple Queue Service) supports dead-letter queues, which source queues can target for messages that are not processed successfully. Dead-letter queues are useful for debugging your application because you can isolate unconsumed messages to determine why processing did not succeed. Once messages are in a dead-letter queue, you can:

Examine logs for exceptions that might have caused messages to be moved to a dead-letter queue.

Analyze the contents of messages moved to the dead-letter queue to diagnose application issues.

Determine whether you have given your consumer sufficient time to process messages.

Move messages out of the dead-letter queue using dead-letter queue redrive.



## R

- Route 53 - is a scalable and highly available Domain Name System (DNS) service. Released on 5 December 2010 (13 years ago),[1] it is part of Amazon.com's cloud computing platform, Amazon Web Services (AWS). The name is a possible reference to U.S. Routes, and "53" is a reference to the TCP/UDP port 53, where DNS server requests are addressed. Also enables AWS customers to route users to non-AWS infrastructure and to monitor the health of their application and its endpoints. Route 53's servers are distributed throughout the world. Amazon Route 53 supports full, end-to-end DNS resolution over IPv6. Recursive DNS resolvers on IPv6 networks can use either IPv4 or IPv6 transport to send DNS queries to Amazon Route 53.

## S

SSM - AWS Systems Manager Agent is a software that runs on Amazon Elastic Compute Cloud (Amazon EC2) instances, edge devices, on-premises servers, and virtual machines (VMs). SSM Agent makes it possible for Systems Manager to update, manage, and configure these resources. The agent processes requests from the Systems Manager service in the AWS Cloud, and then runs them as specified in the request. SSM Agent then sends status and execution information back to the Systems Manager service by using the Amazon Message Gateway Service (ssmmessages). (In AWS Regions launched before 2024, status and execution information might also be sent back by the Amazon Message Delivery Service (service prefix: ec2messages).  

## T

Terraform - https://spacelift.io/blog/terraform-in-ci-cd    

## V

VPC - Virtual Private Cloud - Lambda owns this VPC, which is not connected to your account's default VPC. When you connect a Lambda function to a VPC in your account to access private resources, the function cannot access the internet unless your VPC provides access. Internet access from a private subnet requires network address translation (NAT). To give your function access to the internet, route outbound traffic to a NAT gateway in a public subnet. 
