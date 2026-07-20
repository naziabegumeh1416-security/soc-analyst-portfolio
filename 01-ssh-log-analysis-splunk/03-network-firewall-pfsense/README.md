# Secure Network & Firewall Configuration (pfSense + IDS/IPS)
 
## Overview
This project simulates designing and securing an enterprise network segment using pfSense as the firewall, with Suricata as an IDS/IPS layer to detect malicious traffic, tested using real attack simulations.
 
## Objective
- Build a segmented, secure network architecture
- Configure firewall rules and NAT to allow only legitimate traffic
- Detect and validate intrusion attempts using IDS/IPS
 
## Tools & Technologies
pfSense, Suricata (IDS/IPS), Kali Linux, NAT & Access Control Policies
 
## Step-by-Step Process
1. Designed a lab network architecture with segmented zones (e.g., LAN, WAN, DMZ)
2. Installed and configured pfSense as the perimeter firewall
3. Created stateful firewall rules and NAT policies to permit legitimate traffic and block unauthorized access
4. Integrated Suricata with pfSense to monitor traffic and detect malicious activity in real time
5. Used Kali Linux to simulate attacks: port scanning (Nmap) and brute-force login attempts
6. Verified that the firewall blocked unauthorized traffic and that Suricata generated alerts for the simulated attacks
 
## Key Skills Demonstrated
- Firewall rule design (stateful inspection, NAT, ACLs)
- IDS/IPS deployment and tuning
- Offensive testing (attack simulation) to validate defensive controls
- Network segmentation principles
 
## Outcome
Validated that the firewall + IDS/IPS combination correctly blocked and/or alerted on simulated real-world attacks, confirming the defensive architecture worked as designed.
 
