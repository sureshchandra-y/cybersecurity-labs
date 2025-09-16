# SOC Log Analysis Lab

**Objective:** Ingest logs and detect suspicious activity (e.g., brute-force login attempts).

**Tools Used:** Splunk (or ELK)

**Steps Performed:** 
1. Ingest sample auth/firewall logs.
2. Run queries to find repeated failed logins.
3. Create alert for >10 failed attempts in 10 minutes.
4. Investigate top IPs and timeline.

**Suggested Response:** Block IPs, reset targeted accounts, follow IR playbook.
