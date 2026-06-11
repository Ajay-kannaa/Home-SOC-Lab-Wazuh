# Home SOC Lab — Wazuh SIEM Detection & Incident Response

##  Overview
This project is a home-built Security Operations Center (SOC) lab using Wazuh SIEM to simulate real-world attack detection, monitoring, and incident response.

It focuses on brute-force detection, log correlation, threat mapping, and incident investigation aligned with MITRE ATT&CK framework.

---

## 🏗️ Architecture

- Windows endpoint + Sysmon
- Linux endpoint
- Wazuh Manager (SIEM)
- Log collection and correlation engine

(Add architecture diagram in /architecture folder)

---

## 🚨 Detections Built

- Brute Force Attack Detection
- Privilege Escalation Monitoring
- Suspicious Process Execution
- Authentication Failure Spikes

---

##  Example Detection Logic

Detected brute-force attack using:

- Spike in failed login attempts
- Same user targeted repeatedly
- Time-based correlation window

Mapped to MITRE ATT&CK:
- T1110 — Brute Force

---

##  Incident Response Example

Included:
- Full incident timeline
- Attack behavior analysis
- Containment steps
- Root cause analysis
- Lessons learned

File: `/incident_reports/brute_force_incident_report.md`

---

## 🛠️ Tools Used

- Wazuh SIEM
- Sysmon
- Windows Event Logs
- Linux audit logs
- MITRE ATT&CK
- Splunk for reference
- Python for log analysis

---

## 📌 Key Skills Demonstrated

- SIEM tuning
- Detection engineering
- Threat hunting
- Log analysis
- Incident response
- MITRE ATT&CK mapping

---

