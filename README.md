Log-Based Threat Detection on RHEL 9


**SSH Watchdog** is a lightweight, production-ready Bash script that scans a RHEL 9 system’s `/var/log/secure` for failed SSH login attempts. It helps identify brute-force attacks by logging any IP address with repeated failed logins to a dedicated alert file (`/var/log/ssh_alerts.log`).
## 🎯 Objectives
- Parse and monitor SSH login activity
- Detect brute-force attempts (5+ failed logins)
- Log alerts to a centralized file for auditing
- Schedule routine scans via cron
- Demonstrate automation and log forensics skill
