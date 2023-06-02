[![Edit in Eraser](https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&token=968381c8-a7e7-472a-8ed6-4a6626da5501)](https://app.eraser.io/workspace/oCB5kT2ODayur5W94upo)


# AWS Architecture 
This repository contains the diagram as code for the AWS architecture of our project. The code describes the architecture components and the connections between them.

## Architecture Components
The architecture consists of the following components:

- `Auto Scaling` : The Auto Scaling Group (ASG) that manages the EC2 instances.
- `EC2 Instances` : The EC2 instances hosted in the ASG.
- `Route53` : Amazon Route 53 for domain name system (DNS) service.
- `ALB` : Application Load Balancer (ALB) that handles incoming HTTP and HTTPS traffic.
- `DocumentDB for MongoDB` : MongoDB-compatible database service.
- `S3` : Amazon S3 for storage.
- `CloudWatch` : Amazon CloudWatch for monitoring.
- `CloudFront` : Amazon CloudFront for content delivery network (CDN) service.
- `WAF` : AWS WAF for web application firewall.
- `Shield` : AWS Shield for DDoS protection.
- `SonarQube` : SonarQube for continuous inspection of code quality.
- `Terraform` : Terraform for infrastructure as code (IaC).
- `GitHub` : GitHub for source code management.
- `Secrets Manager` : AWS Secrets Manager for managing secrets.


// Define connections Application > Auto Scaling Route53 > ALB > Auto Scaling Auto Scaling > EC2 Instances > DocumentDB for MongoDB EC2 Instances > CloudWatch EC2 Instances > Shield EC2 Instances > CloudFront > WAF EC2 Instances > S3 EC2 Instances > GitHub > SonarQube EC2 Instances > GitHub > Terraform EC2 Instances > Secrets Manager


<!--- Eraser file: https://app.eraser.io/workspace/oCB5kT2ODayur5W94upo --->