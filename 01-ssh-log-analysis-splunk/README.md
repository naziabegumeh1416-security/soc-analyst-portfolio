# SSH Log Analysis using Splunk
 
## Overview
This project focuses on monitoring and identifying suspicious SSH login activity on a Linux server using Splunk. It simulates a real-world SOC (Security Operations Center) task: detecting brute-force login attempts and unauthorized access through log analysis.
 
## Objective
- Collect and centralize Linux SSH authentication logs in Splunk
- Detect failed login attempts, unusual login times, and repeated access attempts
- Build dashboards and alerts to speed up threat detection
 
## Tools & Technologies
Splunk, Linux, SSH, SPL (Search Processing Language)
 
## Step-by-Step Process
1. Configured a Linux server to generate SSH authentication logs (/var/log/auth.log)
2. Forwarded logs into Splunk using a universal forwarder / file monitoring input
3. Wrote SPL queries to filter failed vs successful login events
4. Built a dashboard showing login trends, top source IPs, and failed login counts over time
5. Created an alert that triggers when failed login attempts from a single IP exceed a threshold in a short time window (brute-force pattern)
6. Validated the alert by simulating repeated failed logins
 
## Key Skills Demonstrated
- Log source onboarding and field extraction in Splunk
- SPL query writing for security use cases
- Dashboard and alert creation for SOC monitoring
- Recognizing brute-force / credential-stuffing attack patterns
 
## Outcome
Reduced the manual effort needed to detect suspicious SSH activity by replacing manual log review with automated, real-time Splunk alerting.
 
