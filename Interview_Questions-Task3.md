# Interview Questions - Task 3

### 1. What is vulnerability scanning?
Vulnerability scanning is an automated process used to identify security weaknesses, misconfigurations, and outdated software in systems or networks.  
It helps security professionals detect potential entry points before attackers exploit them.

---

### 2. What is OpenVAS (GVM)?
OpenVAS (Open Vulnerability Assessment System), now known as GVM (Greenbone Vulnerability Management), is an open-source vulnerability scanner.  
It performs comprehensive scans of hosts and services to detect known vulnerabilities using regularly updated vulnerability feeds.

---

### 3. Why are vulnerability feeds important?
Feeds contain up-to-date information about new vulnerabilities (CVEs) and security checks.  
Without updated feeds, a scanner cannot detect the latest threats, leading to incomplete or outdated results.

---

### 4. What are CVEs?
CVE stands for *Common Vulnerabilities and Exposures*.  
Each CVE is a unique identifier assigned to a publicly disclosed cybersecurity vulnerability so that organizations can track and patch it consistently.

---

### 5. What is CVSS?
CVSS (Common Vulnerability Scoring System) provides a numerical score (0 – 10) that reflects the severity of a vulnerability.  
Scores are typically classified as:  
- **Low (0.1–3.9)**  
- **Medium (4.0–6.9)**  
- **High (7.0–8.9)**  
- **Critical (9.0–10)**  

---

### 6. How does OpenVAS perform a vulnerability scan?
OpenVAS connects to the target host, enumerates its open ports and services, and runs various tests (NVTs – Network Vulnerability Tests) against each service.  
It compares the findings to its vulnerability feed to identify issues, then reports severity scores and remediation steps.

---

### 7. What are the differences between vulnerability scanning and penetration testing?
- **Vulnerability scanning**: Automated, detects known issues and configuration flaws.  
- **Penetration testing**: Manual and goal-oriented, attempts to exploit vulnerabilities to confirm real-world impact.  
Both complement each other in a security program.

---

### 8. What steps should be taken after finding vulnerabilities?
1. **Verify** and prioritize findings based on CVSS scores.  
2. **Apply patches or updates** to affected software.  
3. **Re-scan** the system to ensure issues are fixed.  
4. **Document** the remediation steps and maintain updated configurations.

---

### 9. Why should scans be run regularly?
Because new vulnerabilities emerge every day and systems frequently change.  
Regular scanning ensures continuous monitoring and helps maintain a strong security posture.

---

### 10. What challenges can occur during vulnerability scanning?
- False positives (reported issues that aren’t real).  
- Network interruptions or performance impact.  
- Unauthenticated scans missing deeper issues.  
- Outdated feeds or incomplete configurations causing missed detections.
