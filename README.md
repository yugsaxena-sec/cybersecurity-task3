# Task 3 – Basic Vulnerability Scan on Local Machine

## Objective
Perform a vulnerability scan on my local system using Nessus Essentials and identify common security weaknesses.

## Tools Used
- Nessus Essentials (Version 10.10.0)
- Kali Linux (Kernel 6.16.8)
- Target: Localhost (192.168.29.186)

## Steps I Followed
1. Installed Nessus Essentials and set it up on my machine.
2. Added localhost as the target and started a full system scan.
3. Enabled credentialed checks for better coverage.
4. Waited for the scan to complete and exported the Nessus file and converted into HTML report.
5. Reviewed the results and noted down all key vulnerabilities.

## Key Findings
- **High Severity:** Ruby REXML 3.3.3 < 3.4.2 DoS vulnerability (CVE-2025-58767)
- **Info Level:** Apache, PHP, Node.js, Nginx, PostgreSQL, OpenSSL, etc.
- Most findings were informational with no major exploitable threats.

## Fixes and Mitigations
- Update `rexml` Ruby Gem to version 3.4.2 or later.
- Keep all system packages and libraries up to date.
- Disable unused services (like Apache or Nginx if not required).
- Review IPv6 configuration and disable unused interfaces.

## Learning Outcome
This task helped me understand:
- How vulnerability scanners detect system weaknesses.
- The difference between high, medium, and informational findings.
- The importance of regular updates and patch management.