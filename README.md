<h1 align="center">Bikash Raya</h1>

<h3 align="center">IT Desktop Support Engineer → Cybersecurity | CompTIA Security+ Certified</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Current%20Role-IT%20Desktop%20Support-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Career%20Focus-Cybersecurity-orange?style=for-the-badge"/>
</p>

---

## 👋 Who I Am

IT professional with 2+ years in desktop support making a deliberate move into cybersecurity. I hold a **CompTIA Security+** and have built everything in this portfolio through **hands-on labs** not just coursework.

My hands-on labs cover the full security operations lifecycle: **SIEM deployment, threat detection, vulnerability management, incident response, threat hunting, web application security, cloud IAM, and GRC policy development** all built in Azure cloud and on-premises environments.

---

## 🧪 Cybersecurity Hands-on Labs 

## 🔵 Security Operations and IR Labs

| Project | What I Did | Tools / Skills | Hands-on Report Link |
|---------|-----------|----------------|------|
| **SOC Incident Response Lab** | • Deployed Windows Server (victim) and Ubuntu (attacker) VMs; ran Hydra RDP brute force and detected login events via KQL (Event IDs 4624/4625)<br>• Built a custom analytics rule mapped to MITRE T1110; performed full SOC incident response in Defender XDR | Microsoft Sentinel · Defender XDR · Hydra · KQL · Sysmon · Azure NSG · AMA · DCR · MITRE ATT&CK | [🔗 View Full Report](https://github.com/Bikash-Raya/Sentinel-Defender-XDR-SOC-Incident-Response-lab) |
| **GeoIP Watchlist & Global Attack Map Lab** | • Exposed Web01 for ~2 days to collect 4,270+ real-world RDP attacks from global threat actors<br>• Built a KQL workbook using ipv4_lookup() to enrich attacker IPs and render a global heat map | Microsoft Sentinel · KQL · ipv4_lookup() · Watchlist · Workbook · Defender XDR | [🔗 View Full Report](https://github.com/Bikash-Raya/microsoft-sentinel-geoip-watchlist-attack-map) |
| **Threat Hunting Lab** | • Followed CISA Advisory AA25-141b; simulated LummaC2 execution and ingested Sysmon logs via custom DCR<br>• Ran 5 KQL hunting queries mapped to MITRE ATT&CK; confirmed IOC detection against IP 94.158.244.69 | Microsoft Sentinel · Sysmon · KQL · CISA AA25-141b · MITRE ATT&CK · PS2EXE · IOC Investigation | [🔗 View Full Report](https://github.com/Bikash-Raya/Threat-Hunting-Lab-Sentinel-Sysmon--lummac2-) |
| **Hybrid Endpoint Monitoring Lab** | • Onboarded Windows, Linux, and Azure endpoints into a hybrid SIEM lab via Azure Arc<br>• Built KQL detection rules and triggered and resolved a real incident in Sentinel | Microsoft Sentinel · Azure Arc · AMA · Log Analytics · KQL · DCR · RBAC | [🔗 View Full Report](https://github.com/Bikash-Raya/Microsoft-Sentinel-SIEM-SOC-Lab--Hybrid-Endpoint-Monitoring-Threat-Detection-and-Incident-Response) |
| **Azure Honeynet, SQL Server & Live Attack Detection Lab** | • Deployed Windows and Linux VMs as honeypots with open NSGs; setup SQL Seerver, ingested logs via Log Analytics, DCR, and NSG Flow Logs<br>• Enriched alerts with GeoIP watchlist and confirmed live real-world attack detection using KQL | Microsoft Sentinel · Azure NSG · SQL Server · Log Analytics · KQL · Defender for Cloud | [🔗 View Full Report](https://github.com/Bikash-Raya/Azure-Honeynet-Live-Attack-Detection-NSG-SQL-Microsoft-Sentinel) |

---

## 🔴 Vulnerability Management Labs

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **Nessus Vulnerability Management Lab** | • Built an Active Directory lab; deployed Nessus Essentials on Kali Linux and ran credentialed scans with GPO-based access<br>• Remediated SMB Signing (Plugin 57608) via GPO, 7-Zip Critical CVEs, and conducted a web app scan with 18 findings | Tenable Nessus · Kali Linux · Active Directory · GPO · CVSS · SMB Hardening · Windows Server | [🔗 View Full Report](https://github.com/Bikash-Raya/Nessus-Vulnerability-Management-Lab) |
| **OWASP ZAP — Web App Security Assessment Lab** | • Performed a full DAST assessment against testasp.vulnweb.com using OWASP ZAP 2.17.0<br>• Confirmed SQL Injection, DOM/Reflected XSS, Path Traversal, and Open Redirect across 21 alerts mapped to OWASP Top 10 | OWASP ZAP · DAST · SQL Injection · XSS · Path Traversal · OWASP Top 10 · Kali Linux | [🔗 View Full Report](https://github.com/Bikash-Raya/Web-Application-Security-OWASP-ZAP) |

---

## ☁️ Cloud & Identity Labs

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **Azure IAM Security Lab** | • Provisioned a test user and Security Group in Entra ID; assigned Reader RBAC role and validated least-privilege access<br>• Configured MFA via Microsoft Authenticator and reviewed sign-in logs | Microsoft Entra ID · Azure RBAC · MFA · Sign-in Logs · Least Privilege | [🔗 View Full Report](https://github.com/Bikash-Raya/azure-iam-security-lab) |
| **Azure Cloud — Identity & RBAC Lab** | • Provisioned Windows Server via Azure CLI and configured dynamic group membership<br>• Implemented custom RBAC roles for delegated access control | Azure CLI · Entra ID · Dynamic Groups · RBAC | [🔗 View Full Report](https://github.com/Bikash-Raya/Azure_Cloud_Environment_Setup_Identity_-_RBAC_Implementation-) |
| **Azure Windows VM Administration Lab** | • Provisioned a Windows 11 VM in Azure; configured RDP access, user accounts, and RBAC<br>• Performed troubleshooting and decommissioned the environment | Azure · Windows 11 · RDP · Entra ID · RBAC | [🔗 View Full Report](https://github.com/Bikash-Raya/Azure-Cloud-Windows-11-Virtual-Machine-Deployment-RDP-Administration-User-Lifecycle-Management-RBAC-) |

---

## 📋 GRC & Risk Management

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **Policy and Playbook Development** | • Developed a Phishing Incident Response Playbook with severity classification, containment tracks, and HIPAA breach notification procedures<br>• Wrote a Password & Authentication Policy aligned to NIST SP 800-63B, ISO 27001:2022, and NIST CSF | NIST CSF · ISO 27001:2022 · NIST SP 800-63B · HIPAA · Policy Writing · Incident Playbook · GRC | [🔗 View Full Report](https://github.com/Bikash-Raya/healthcare-cybersecurity-grc-portfolio) |
| **Cyber Risk Assessment** | • Conducted a full information security risk assessment for a fictional LMS; produced Asset Register, Threat Catalogue, and Risk Scoring Matrix<br>• Delivered a Controls Register (NIST CSF), Risk Treatment Plan, and Risk Register | NIST CSF · Risk Assessment · Risk Register · Asset Classification · Control Mapping | [🔗 View Full Report](https://github.com/Bikash-Raya/Cyber-Risk-Assessment) |

---

## 🏗️ Infrastructure Labs

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **On-Prem AD, DC, Windows 11 & Linux** | • Built a virtualised on-prem network with Windows Server 2022 as Domain Controller<br>• Joined Windows 11 and Kali Linux clients; configured AD DS, DNS, and resolved cross-platform connectivity issues | VMware · Windows Server 2022 · Active Directory · DNS · Kali Linux · PowerShell | [🔗 View Full Report](https://github.com/Bikash-Raya/Home-Lab--OnPrem-Windows-Server-Active-Directory-Domain-Controller-Windows-11-Linux) |
| **Enterprise IT Infrastructure Design & Deployment** | • Designed and deployed a full enterprise network for a simulated college with AD OU structure, RBAC, and Microsoft 365 integration<br>• Configured a Fortinet firewall and performed end-to-end validation testing | Active Directory · Microsoft 365 · Fortinet Firewall · RBAC · VLAN | [🔗 View Full Report](https://github.com/Bikash-Raya/IT-Infrastructure-Design-Deployment-Homelab-Project) |

---



## 🛠️ Skills

| | |
|--|--|
| 🔵 **SOC and IR** | Microsoft Sentinel · Defender XDR · KQL · Log Analytics · Alert Triage · Incident Response  |
| 🎯 **Threat Hunting** | MITRE ATT&CK · Hypothesis-Driven Hunting · IOC Investigation · CISA Advisory Analysis · Threat Intel |
| ⚔️ **Offensive Security** | Hydra · Metasploit Concepts · Brute Force · Attack Simulation · Kali Linux |
| 🔴 **Vulnerability Mgmt** | Tenable Nessus · Credentialed Scanning · CVSS Scoring · Remediation Planning · GPO-Based Hardening |
| 🌐 **Web App Security** | OWASP ZAP · DAST · OWASP Top 10 · Burp Suite Concepts |
| ☁️ **Cloud & Identity** | Microsoft Azure · Entra ID · RBAC · Azure IAM · Intune · Microsoft 365 · Active Directory |
| 📋 **GRC & Compliance** | NIST CSF · ISO 27001:2022 · NIST SP 800-63B · HIPAA · Policy Development · Risk Assessment · Playbooks |
| 🖥️ **Systems & Networking** | Windows Server · Linux · VMware · DNS · DHCP · Firewalls · VLANs · NSG |
| 🛠️ **Scripting & Automation** | PowerShell · Python Basics |

---

## 🎓 Certifications & Professional Training

| Qualification | Provider | Credential |
|--------------|----------|------------|
| **CompTIA Security+** | CompTIA | [🔗 Verify](https://www.credly.com/badges/f489e367-4616-4da9-b3d1-fa2217abc36e) |
| **Google Cybersecurity Professional Certificate** | Coursera | [🔗 Verify](https://www.credly.com/badges/43176bd9-b0f9-4f68-8dfb-d91f18e5b55e/linked_in_profile) |
| **SC-200: Microsoft Security Operations Analyst** | Udemy | [🔗 Certificate](https://www.udemy.com/certificate/UC-fab0f971-1d91-44f7-83e9-56952a75d336/) |
| **Tata Cybersecurity Simulation** | Forage | [🔗 Certificate](https://www.theforage.com/completion-certificates/ifobHAoMjQs9s6bKS/gmf3ypEXBj2wvfQWC_ifobHAoMjQs9s6bKS_HG5z6cFBsTiHgMNhb_1776147302554_completion_certificate.pdf) |
| **AIG Cybersecurity Simulation** | Forage | [🔗 Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/AIG/2ZFnEGEDKTQMtEv9C_AIG_HG5z6cFBsTiHgMNhb_1702523682604_completion_certificate.pdf) |
| **ANZ Cyber Security Management Simulation** | Forage | [🔗 Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/ANZ/Hf4QMESoFeQwXPsiH_ANZ%20Australia_HG5z6cFBsTiHgMNhb_1702344768941_completion_certificate.pdf) |
| **Mastercard Cybersecurity Simulation** | Forage | [🔗 Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/mastercard/vcKAB5yYAgvemepGQ_Mastercard_HG5z6cFBsTiHgMNhb_1702348419111_completion_certificate.pdf) |
| **Telstra Cybersecurity Simulation** | Forage | [🔗 Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Telstra%20AU/RNhbu8QnDzthwynEf_Telstra_HG5z6cFBsTiHgMNhb_1701832539937_completion_certificate.pdf) |
| **Datacom Cybersecurity Simulation** | Forage | [🔗 Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Datacom/yTszJTvkHFBH6zAn3_Datacom_HG5z6cFBsTiHgMNhb_1702609391245_completion_certificate.pdf) |

---

## 📫 Get in Touch

<p align="center">
  <a href="https://www.linkedin.com/in/bikash-raya/">
    <img src="https://img.shields.io/badge/LinkedIn-Bikash%20Raya-0072b1?style=flat-square&logo=linkedin"/>
  </a>
  &nbsp;
  <a href="https://github.com/Bikash-Raya">
    <img src="https://img.shields.io/badge/GitHub-Bikash--Raya-181717?style=flat-square&logo=github"/>
  </a>
</p>
