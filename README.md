# Arch on AWS - Kuba's notes

[TOC]

## Networking p1.
### How to "slice" a VPC into multiple subnets using CIDR notation?
- You can also use [cidr.xyz](cidr.xyz) to figure out your IP ranges

![](https://i.imgur.com/TI9eDWS.png)

### A sample VPC that we've build during the Demo:

![](https://i.imgur.com/io5vY4g.png)


## Containers
- [ECS vs. EKS](https://aws.amazon.com/blogs/containers/amazon-ecs-vs-amazon-eks-making-sense-of-aws-container-services/)
- [ECS Workshop](https://ecsworkshop.com)
- [EKS Workshop](https://www.eksworkshop.com)

## AWS Certified Solutions Architect – Associate  
- focus on core services: Regions, AZs, EC2, S3, VPC, IAM, ELB, RDS, Aurora, ElastiCache, Route53, CloudFront, ECS, Fargate, Serverless, CloudWatch, KMS, SSM Parameter Store, Disaster Recovery - more in Exam Readiness below
- Breath over depth with a few exceptions
- Need high level understanding of AWS Services

### Official materials
- Prepare for Your AWS Certification Exam, everything under [AWS Certified Solutions Architect – Associate][aws-prep] tabs (click "+" to see the list of resources):

- Recommended: Under "Take Exam Readiness training" you will be able to access free Exam Readiness either pre-recorded or live webinar

- Practice Exam - short, paid practice exam from AWS to give you some idea where you're at (alsow available in resources)

- Solid material, questions very similar in complexity comparing to real exam, but pricey: [AWS Certified Solutions Architect Study Guide: Associate SAA-CO2 Exam][study-guide]

### Free practice exams + 50% of the exam
https://www.linkedin.com/posts/semaan_awscertification-free-training-activity-6851356228971479040-RpNC

### Non-offical materials
#### Breakdown 
https://www.linkedin.com/posts/semaan_aws-cloud-developers-activity-6840279276223287296-N1rV/

Good to map domains from offical materials to specific services, but focused mainly on passing an exam (again breath over depth).

- Solution Architect course: https://www.udemy.com/share/101WgCBEYfc1dVRH4=/
- Soultion Architect practice exams (pretty close to the original ones): https://www.udemy.com/share/101WLyBEYfc1dVRH4=/

# Questions and Answers

[Questions and Answers - Architecting on AWS 18.10.2021-21.10.2021](https://hackmd.io/@kubakonczyk/BJwrfDpSF)

[aws-prep]: https://aws.amazon.com/certification/certified-solutions-architect-associate/

[study-guide]: https://www.amazon.com/Certified-Solutions-Architect-Study-Guide/dp/1119713080/ref=sr_1_1?dchild=1&keywords=aws+solution+architect&qid=1625248049&sr=8-1

[udemy-1]: https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c02/
[udemy-2]: https://www.udemy.com/course/aws-certified-solutions-architect-associate-amazon-practice-exams-saa-c02/l
