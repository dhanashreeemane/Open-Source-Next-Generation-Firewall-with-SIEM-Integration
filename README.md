# Open-Source-Next-Generation-Firewall-with-SIEM-Integration

## Overview
The **Open-Source-Next-Generation-Firewall-with-SIEM-Integration** is a robust security monitoring framework integrating **Intrusion Detection and Prevention Systems (IDS/IPS)** with advanced **log analysis, vulnerability assessment, and automated threat response** mechanisms. It combines **Wazuh, Suricata, OPNsense, and VirusTotal API** to provide comprehensive security monitoring across both network and endpoint layers.

## 🔍 Key Features
- **[File Integrity Monitoring (FIM)](UseCases/File_Integrity_Monitoring.md)** – Tracks unauthorized modifications to critical system files.
- **[Network Intrusion Detection (NIDS)](UseCases/Network_IDS_Suricata.md)** – Uses **Suricata IDS** to detect suspicious network activity.
- **[Vulnerability Assessment](UseCases/Vulnerability_Assessment.md)** – Scans systems for **known CVEs** and security weaknesses.
- **[Malicious Command Execution Detection](UseCases/Malicious_Command_Detection.md)** – Monitors commands for unauthorized system modifications.
- **[SSH Brute-Force Prevention](UseCases/SSH_Brute_Force_Prevention.md)** – Identifies and blocks repeated failed login attempts.
- **[VirusTotal API Integration](UseCases/Malicious_File_Detection.md)** – Detects and classifies malware-infected files.
- **[Security Awareness Module](UseCases/Security_Awareness_Module.md)** – Provides 300+ best practices to improve personal security.

## 🏗️ System Architecture
This SIEM stack follows a **multi-layered defense model**, incorporating:
1. **[Firewall & IDS/IPS (OPNsense & Suricata)](Architecture.md#firewall-and-idsips-opnsense-suricata)** – Network-based monitoring and threat prevention.
2. **[Log Collection & Correlation (Wazuh SIEM)](Architecture.md#log-collection-and-correlation)** – Centralized event analysis and real-time alerting.
3. **[Security Awareness Module](Architecture.md#security-awareness-module)** – Ensuring cybersecurity hygiene through best practices.
4. **[Automated Incident Response](Architecture.md#automated-incident-response)** – Dynamic rules for blocking malicious IPs and files.

## 📂 Project Structure
```
📂 Next-Gen-SIEM-Stack
├── 📄 README.md            # Project overview
├── 📄 Architecture.md       # System design and security policies
├── 📄 Installation.md       # Setup guide for all components
├── 📂 UseCases             # Security monitoring use cases
│   ├── 📄 [File_Integrity_Monitoring.md]
│   ├── 📄 [Network_IDS_Suricata.md]
│   ├── 📄 [Vulnerability_Assessment.md]
│   ├── 📄 [Malicious_Command_Detection.md]
│   ├── 📄 [SSH_Brute_Force_Prevention.md]
│   ├── 📄 [Malicious_File_Detection.md]
├── 📄 Experimental_Results.md  # Performance evaluation and analysis
├── 📄 Contributing.md         # Contribution guidelines
├── 📄 License.md            # Licensing details
```

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/dhanashreeemane/Open-Source-Next-Generation-Firewall-with-SIEM-Integration.git
   ```
2. Follow the [Installation Guide](Installation.md) to set up the SIEM system.
3. Explore different security monitoring use cases in the **[UseCases](UseCases/)** directory.

## 🛡️ Contribution & Community
We welcome security enthusiasts to contribute! Read the [Contributing Guide](Contributing.md) for details.

## 📜 License
This project is licensed under the [MIT License](License.md).

---
This project ensures **proactive cybersecurity monitoring**, **real-time intrusion detection**, and **automated threat mitigation** for enhanced organizational security. 🚀
