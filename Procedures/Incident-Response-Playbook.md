
# Incident Response Playbook

## 1. Objective
This playbook outlines the standardized lifecycle for detecting, containing, eradicating, and recovering from cybersecurity incidents affecting organizational assets.

## 2. Incident Response Lifecycle (NIST SP 800-61 Structure)

### 2.1 Preparation
* Maintain updated asset inventories and network topology diagrams.
* Conduct regular employee security awareness training on phishing and anomaly reporting.
* Ensure logging and monitoring tools (SIEM/EDR) are active across all endpoints.

### 2.2 Identification
* Detect anomalies via automated alerts, user reports, or external notifications.
* Triage the alert to determine scope, severity (Low, Medium, High, Critical), and potential impact.
* Open an incident ticket and notify the Incident Response Team (IRT).

### 2.3 Containment
* **Short-term Containment:** Isolate compromised hosts from the corporate network immediately to prevent lateral movement (e.g., network segmentation or endpoint quarantine).
* **Long-term Containment:** Apply temporary patches or firewall rules while root-cause analysis is underway.
* Preserve forensic evidence (memory dumps, disk images, system logs) for post-incident analysis.

### 2.4 Eradication
* Identify and remove the root cause (e.g., delete malicious payloads, clean compromised registry keys, or terminate unauthorized user sessions).
* Patch vulnerabilities, misconfigurations, or compromised credentials that enabled the breach.

### 2.5 Recovery
* Restore systems from clean, verified backups.
* Validate system integrity and monitor network traffic closely for secondary anomalies.
* Bring systems back into production once security sign-off is granted.

### 2.6 Lessons Learned
* Conduct a post-incident review meeting within 5 business days of incident closure.
* Document root causes, response effectiveness, and areas for improvement.
* Update existing policies and playbooks to prevent recurrence.
