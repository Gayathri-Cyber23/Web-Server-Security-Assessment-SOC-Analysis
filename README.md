# Web Server Security Assessment & SOC Analysis

## Project Overview

This project was completed as part of my Master of Science in Cybersecurity capstone. The project simulated a real-world cybersecurity consulting engagement for a small business operating a WordPress-based e-commerce website hosted on a Linux server environment.

The objective was to evaluate the security posture of the environment, develop a security program, implement server hardening measures, conduct vulnerability analysis, review security logs, and provide remediation recommendations.

## Technical Environment

- Red Hat Enterprise Linux 8.4
- Apache 2.4.37
- MariaDB 10.6.4
- WordPress
- SSH access through VPN
- Kali Linux for vulnerability analysis

## Project Phases

### Phase 1: Security Program and Risk Assessment
- Reviewed the server and business environment
- Developed security policy and access management guidance
- Created a risk assessment covering OS, web server, database, WordPress, and user-role risks
- Proposed security controls including firewall, IDS, logging, monitoring, and hardening

### Phase 2: Security Implementation and Testing Strategy
- Practiced role-based access control concepts
- Reviewed administrative, security, and web administrator role separation
- Practiced SSH hardening using key-based authentication
- Developed a vulnerability analysis strategy using tools such as Nmap, Nikto, curl, dirb, netcat, ssh-audit, and searchsploit

### Phase 3: Vulnerability Assessment and SOC-Style Analysis
- Conducted vulnerability assessment against a peer server environment
- Performed service enumeration, directory scanning, SSL/TLS review, CMS fingerprinting, and WordPress analysis
- Identified outdated software, exposed directories, weak headers, expired SSL certificate, XML-RPC exposure, and weak SSH algorithms
- Reviewed ModSecurity logs to analyze detected scanner activity and determine whether malicious activity was blocked or logged

## Tools Used

- Nmap
- Nikto
- curl
- dirb
- Gobuster
- Netcat
- ssh-audit
- searchsploit
- testssl.sh
- ModSecurity
- OWASP Core Rule Set
- Kali Linux
- PuTTY
- Microsoft Teams
- Microsoft Office

## Key Skills Demonstrated

- Vulnerability assessment
- Web server security review
- Linux server hardening concepts
- Access control and RBAC
- SSH hardening
- Security policy development
- Risk assessment
- Log review and forensic analysis
- SOC-style investigation
- Security documentation and reporting
- Team leadership and project coordination

## Important Note

This repository contains sanitized academic project documentation. Sensitive information such as IP addresses, usernames, passwords, screenshots containing credentials, instructor contact information, team member contact information, and private school system details have been removed or redacted.
