# Windows Threat Hunting & SIEM Ingestion Lab

A hands-on cybersecurity portfolio project demonstrating endpoint telemetry monitoring, threat hunting, and centralized log management.

---

## 🛠️ Tools & Environment
* **Endpoint:** Windows Virtual Machine (`DESKTOP-KBEEQLF`)
* **Telemetry & Logging:** Sysmon (System Monitor)
* **SIEM & Analytics:** Wazuh SIEM

---

## 🔍 Lab Evidence & Screenshots

### 1. PowerShell Execution Monitoring
![PowerShell Execution](images/01_powershell_execution.jpg)
*Capturing PowerShell script execution through Sysmon telemetry.*

### 2. Command Line Abuse Detection
![Command Line Abuse](images/02_cmd_abuse.jpg)
*Tracking command-line execution anomalies.*

### 3. Parent-Child Process Relationship
![Parent Child Process](images/03_parent_child_process.jpg)
*Analyzing process lineage to identify suspicious execution chains.*

### 4. Encoded Command Analysis
![Encoded Command](images/04_encoded_command.jpg)
*Identifying obfuscated command lines and payloads.*

### 5. Wazuh SIEM Ingestion & Dashboard
![Wazuh Sysmon Ingestion](images/05_wazuh_sysmon_ingestion.png)
*Real-time log ingestion and event timelines on the Wazuh SIEM dashboard.*

---

## 📌 Conclusion
This project highlights practical threat hunting capabilities, endpoint visibility configuration, and incident analysis workflows essential for Security Operations Center (SOC) operations.
