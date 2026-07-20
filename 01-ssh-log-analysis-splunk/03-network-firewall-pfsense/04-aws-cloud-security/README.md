# AWS Cloud Security & Threat Detection
 
## Overview
This project secures an AWS cloud environment using identity and access best practices, centralized logging, and automated threat detection — core skills for cloud/SOC security roles.
 
## Objective
- Apply least-privilege access control in AWS IAM
- Enable centralized audit logging
- Set up continuous, automated threat detection in the cloud
 
## Tools & Technologies
AWS (Free Tier), IAM, CloudTrail, GuardDuty
 
## Step-by-Step Process
1. Reviewed the AWS account and identified overly permissive IAM users/policies
2. Created IAM users, groups, and custom policies following the principle of least privilege
3. Enabled AWS CloudTrail for centralized logging of all account activity (API calls, console logins)
4. Enabled AWS GuardDuty for continuous, automated threat detection across the account
5. Reviewed GuardDuty findings and CloudTrail logs to identify misconfigurations and risky activity
6. Documented remediation steps for each identified issue (e.g., removing unused access keys, restricting overly broad policies)
 
## Key Skills Demonstrated
- IAM least-privilege configuration
- Cloud audit logging (CloudTrail)
- Cloud-native threat detection (GuardDuty)
- Cloud security misconfiguration remediation
 
## Outcome
Hardened a cloud environment against common misconfigurations and stood up continuous monitoring so future threats are detected automatically rather than manually.
 
