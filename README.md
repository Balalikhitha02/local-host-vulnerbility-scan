#  Basic Vulnerability Scan (Nessus Essentials)

##  Objective
Perform a vulnerability scan on my local machine to identify security risks, analyze them, and suggest mitigations.

---

##  Tool Used
- **Nessus Essentials (by Tenable)**  

---

## Steps I Followed
1. Installed Nessus Essentials on Windows 10.  
2. Set target as **127.0.0.1** (my own PC).  
3. Created and launched a **Basic Network Scan**.  
4. Waited for scan completion (~45 minutes).  
5. Exported the results in **PDF format**.  
6. Took screenshots of dashboard and results.  
7. Documented top security concerns and mitigations.  

---

## Security Concerns Found
- **Critical Issues**  
  - Outdated software with known vulnerabilities.  
  - Open ports exposing services like SMB.  

- **High Issues**  
  - Weak service configurations.  
  - Information disclosure via banners.  

- **Medium Issues**  
  - Missing security updates.  

---

## Mitigation Suggestions
- Apply latest OS and application patches regularly.  
- Disable or firewall unused services/ports.  
- Use secure configurations and hardening guides (CIS Benchmarks).  
- Perform scans monthly to ensure continuous protection.  

---

## Repository Contents
- `Nessus_Report.pdf` → Exported vulnerability report.  
- `Screenshots/` → Proof of scan (dashboard, results, critical issue).  
- `README.md` → Documentation of the task.  

---

## Learning Outcome
- Understood the difference between **critical, high, medium, low** vulnerabilities.  
- Learned to use Nessus Essentials for practical vulnerability management.  
- Improved skills in documentation and reporting of cybersecurity findings.  

---

