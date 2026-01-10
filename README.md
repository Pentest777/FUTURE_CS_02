#Task 2
🔐 Security Alert Monitoring & Incident Response (SOC Project)

This project demonstrates Security Operations Center (SOC) fundamentals by simulating real-world security alert monitoring and incident response activities using SIEM tools. The objective is to analyze logs, detect suspicious behavior, classify incidents, and prepare a structured Incident Response Report.

🎯 Project Objectives
Monitor security alerts generated from log data
Identify suspicious activities and potential attacks
Perform alert triage and incident classification
Draft a professional incident response report
Understand SOC analyst workflows

🛠 Tools & Technologies Used
Elastic Stack (ELK)
Elasticsearch
Logstash
Kibana
Splunk (Free Trial)
Sample log files (Web server, authentication, system logs)

🔍 Methodology
1️⃣ Log Ingestion
Imported sample logs into ELK Stack and Splunk
Parsed logs to extract fields such as:
IP address
Username
Timestamp
HTTP status codes
Failed login attempts

2️⃣ Alert Monitoring & Detection
Monitored SIEM dashboards for:
Multiple failed login attempts (Brute Force)
Login attempts from unusual IP locations
Excessive HTTP 404 / 500 errors
Suspicious request patterns
Example:
🔴 5+ failed logins from a single IP within 2 minutes
🔴 Admin login attempt outside business hours

3️⃣ Alert Triage
Each alert was analyzed and categorized as:
True Positive – Confirmed malicious activity
False Positive – Legitimate user behavior
Benign Event – No security impact

4️⃣ Incident Classification
Incidents were classified using standard SOC severity levels:
Severity
Incident Type
Low
Policy violation
Medium
Suspicious login
High
Brute-force attack
Critical
Account compromise

5️⃣ Incident Response Report
A detailed report was created including:
Incident summary
Timeline of events
Indicators of Compromise (IoCs)
Impact analysis
Containment & mitigation steps
Recommendations
