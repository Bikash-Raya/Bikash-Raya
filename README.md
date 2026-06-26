<h1 align="center">Bikash Raya</h1>

<h3 align="center">IT Desktop Support Engineer → Cybersecurity | CompTIA Security+ Certified</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/bikash-raya/">
    <img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Current%20Role-IT%20Desktop%20Support-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Career%20Focus-Cybersecurity-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Open%20to%20Work-Cybersecurity%20Roles-brightgreen?style=for-the-badge"/>
</p>

---

## 👋 About Me

IT professional with **2+ years in desktop support** making a deliberate move into cybersecurity. I hold a **CompTIA Security+** and have built everything in this portfolio through **hands-on labs** — not just coursework.

My labs cover the full security operations lifecycle: **SIEM deployment, threat detection, vulnerability management, incident response, threat hunting, web application security, cloud IAM, and GRC policy development** — all built in real Azure environments using real tools.

Currently targeting **SOC Analyst, Security Analyst, and GRC Analyst** roles where I can contribute from day one.

---

## 🛠️ Skills

| | |
|--------|----------------------|
| **Security Operations (SIEM & Detection)** | Microsoft Sentinel · Microsoft Defender XDR · KQL · Log Analytics · Alert Triage · Incident Response · Sysmon · DCR |
| **Threat Hunting & Analysis** | MITRE ATT&CK · Hypothesis-Driven Hunting · IOC Investigation · CISA Advisory Analysis · Threat Intelligence |
| **Vulnerability Management** | Tenable Nessus · Credentialed Scanning · CVSS Scoring · Remediation Planning · GPO-Based Hardening |
| **Web Application Security** | OWASP ZAP · DAST · Burp Suite Concepts · OWASP Top 10 · KQL Web Scanning |
| **Cloud & Identity** | Microsoft Azure · Entra ID · RBAC · Azure IAM · Intune · Microsoft 365 · Active Directory |
| **GRC & Compliance** | NIST CSF · ISO 27001:2022 · NIST SP 800-63B · HIPAA · Policy Development · Risk Assessment · Incident Playbooks |
| **Systems & Networking** | Windows Server · Linux · VMware · DNS · DHCP · Firewalls · NSG |
| **Scripting & Automation** | PowerShell · Python Basics · Hydra · PS2EXE |

---

## 🔵 Security Operations & Blue Team Labs

| Project | What I Did | Tools / Skills | Detailed Report Link |
|---------|-----------|----------------|------|
| **Microsoft Sentinel & Defender XDR — SOC Incident Response Lab** | Deployed Windows Server (victim) and Ubuntu (attacker) VMs; disabled firewall and opened NSG; ran Hydra RDP brute force attack; detected 7 failed + 1 successful login via KQL (Event IDs 4624/4625); built a custom analytics rule mapped to MITRE T1110; triggered Incident ID 18 in Defender XDR; performed full SOC incident response including task creation, investigation, and closure | Microsoft Sentinel · Defender XDR · Hydra · KQL · Sysmon · Azure NSG · AMA · DCR · MITRE ATT&CK | [🔗 View Full Report](https://github.com/Bikash-Raya/Sentinel-Defender-XDR-SOC-Incident-Response-lab) |
| **Microsoft Sentinel — GeoIP Watchlist & Global Attack Map** | Left Web01 exposed for ~2 days to collect 4,270+ real-world RDP attacks from global threat actors; uploaded GeoIP CSV watchlist; built a KQL workbook using ipv4_lookup() to enrich attacker IPs with geographic coordinates; rendered a global heat map showing attack origins including Hanoi (808), Southampton (795), London (681) | Microsoft Sentinel · KQL · ipv4_lookup() · Watchlist · Workbook · Defender XDR | [🔗 View Full Report](https://github.com/Bikash-Raya/microsoft-sentinel-geoip-watchlist-attack-map) |
| **LummaC2 Threat Hunting Lab — Sentinel & Sysmon** | Followed CISA Advisory AA25-141b; built a hypothesis that LummaC2 executed in the environment; created a safe simulation executable (LummaC2.exe); installed Sysmon v15.21; created a custom DCR to ingest Sysmon logs; ran 5 KQL hunting queries mapped to MITRE ATT&CK — Hunt 1 returned 3 confirmed results; simulated nslookup against IOC IP 94.158.244.69 and confirmed detection | Microsoft Sentinel · Sysmon · KQL · CISA AA25-141b · MITRE ATT&CK · PS2EXE · IOC Investigation | [🔗 View Full Report](https://github.com/Bikash-Raya/Threat-Hunting-Lab-Sentinel-Sysmon--lummac2-) |
| **Microsoft Sentinel SIEM — Hybrid Endpoint Monitoring** | Deployed a hybrid SIEM lab onboarding Windows, Linux, and Azure endpoints via Azure Arc; built KQL detection rules and triggered/resolved a real incident in Sentinel | Microsoft Sentinel · Azure Arc · AMA · Log Analytics · KQL · DCR · RBAC | [🔗 View Full Report](https://github.com/Bikash-Raya/Microsoft-Sentinel-SIEM-SOC-Lab--Hybrid-Endpoint-Monitoring-Threat-Detection-and-Incident-Response) |
| **Azure Honeynet — Live Attack Detection** | Deployed Windows and Linux VMs as honeypots with deliberately open NSGs; ingested logs into Sentinel via Log Analytics, DCR, and NSG Flow Logs; enriched alerts with GeoIP watchlist; confirmed live real-world attack detection using KQL | Microsoft Sentinel · Azure NSG · SQL Server · Log Analytics · KQL · Defender for Cloud | [🔗 View Full Report](https://github.com/Bikash-Raya/Azure-Honeynet-Live-Attack-Detection-NSG-SQL-Microsoft-Sentinel) |

---

## 🔴 Offensive Security & Vulnerability Management

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **Nessus Vulnerability Management Lab** | Built an Active Directory lab (biksec.com); created a Nessus service account (SVC_Nessus); deployed Nessus Essentials 10.12.0 on Kali Linux; created credentialed scan policies; deployed GPOs for WMI/Remote Registry/Firewall; ran authenticated scans; identified and remediated SMB Signing (Plugin 57608) via GPO and 7-Zip Critical CVEs; conducted a web app scan of testasp.vulnweb.com (18 findings) | Tenable Nessus · Kali Linux · Active Directory · GPO · CVSS · SMB Hardening · Windows Server | [🔗 View Full Report](https://github.com/Bikash-Raya/Nessus-Vulnerability-Management-Lab) |
| **OWASP ZAP — Web Application Security Assessment** | Performed a full DAST assessment against testasp.vulnweb.com using OWASP ZAP 2.17.0; confirmed SQL Injection (including 15-second WAITFOR time-based blind injection), DOM XSS, Reflected XSS, Path Traversal (Windows/system.ini retrieved), and Open Redirect; identified 21 alerts across OWASP Top 10 | OWASP ZAP · DAST · SQL Injection · XSS · Path Traversal · OWASP Top 10 · Kali Linux | [🔗 View Full Report](https://github.com/Bikash-Raya/Web-Application-Security-OWASP-ZAP) |

---

## ☁️ Cloud & Identity Labs

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **Azure IAM Security Lab — User, Group, RBAC & Sign-in Logs** | Created a Resource Group (RG-IAM-Security-Lab); provisioned a test user (IAM Test User) in Entra ID; created a Security Group (IAM-Lab-Readers); assigned Reader RBAC role; validated read access worked and delete/create were blocked; configured MFA via Microsoft Authenticator; reView Full Reported sign-in logs | Microsoft Entra ID · Azure RBAC · MFA · Sign-in Logs · Least Privilege | [🔗 View Full Report](https://github.com/Bikash-Raya/azure-iam-security-lab) |
| **Azure Cloud Environment — Identity & RBAC** | Provisioned Windows Server via Azure CLI; configured dynamic group membership; implemented custom RBAC roles for delegated access control | Azure CLI · Entra ID · Dynamic Groups · RBAC | [🔗 View Full Report](https://github.com/Bikash-Raya/Azure_Cloud_Environment_Setup_Identity_-_RBAC_Implementation-) |
| **Azure Windows 11 VM — Full Lifecycle Administration** | Provisioned a Windows 11 VM in Azure; configured RDP access; managed user accounts and RBAC; performed troubleshooting and decommissioned the environment | Azure · Windows 11 · RDP · Entra ID · RBAC | [🔗 View Full Report](https://github.com/Bikash-Raya/Azure-Cloud-Windows-11-Virtual-Machine-Deployment-RDP-Administration-User-Lifecycle-Management-RBAC-) |

---

## 📋 GRC & Risk Management

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **Healthcare Cybersecurity GRC Portfolio — BrightCare Health Clinic** | Developed two professional GRC documents for a fictional healthcare clinic: (1) Phishing Incident Response Playbook with severity classification, containment tracks, HIPAA breach notification procedures, and evidence chain-of-custody; (2) Password & Authentication Policy aligned to NIST SP 800-63B — both mapped to NIST CSF, ISO 27001:2022 Annex A, and HIPAA Security Rule | NIST CSF · ISO 27001:2022 · NIST SP 800-63B · HIPAA · Policy Writing · Incident Playbook · GRC | [🔗 View Full Report](https://github.com/Bikash-Raya/healthcare-cybersecurity-grc-portfolio) |
| **LMS Cyber Risk Assessment** | Conducted a full information security risk assessment for a fictional Learning Management System; produced Asset Register, Threat Catalogue, Vulnerability Register, Risk Scoring Matrix (Impact × Likelihood), Controls Register (NIST CSF), Risk Treatment Plan, and Risk Register | NIST CSF · Risk Assessment · Risk Register · Asset Classification · Control Mapping | [🔗 View Full Report](https://github.com/Bikash-Raya/Cyber-Risk-Assessment) |

---

## 🏗️ Infrastructure Labs

| Project | What I Did | Tools / Skills | Repo |
|---------|-----------|----------------|------|
| **On-Prem Home Lab — AD, Domain Controller, Windows 11 & Linux** | Built a virtualised on-prem network with Windows Server 2022 as Domain Controller; joined Windows 11 and Kali Linux clients; configured AD DS, DNS, and resolved cross-platform connectivity issues | VMware · Windows Server 2022 · Active Directory · DNS · Kali Linux · PowerShell | [🔗 View Full Report](https://github.com/Bikash-Raya/Home-Lab--OnPrem-Windows-Server-Active-Directory-Domain-Controller-Windows-11-Linux) |
| **Enterprise IT Infrastructure Design & Deployment** | Designed and deployed a full enterprise network for a simulated college — AD with OU structure, RBAC, Microsoft 365 integration, Fortinet firewall, and end-to-end validation testing | Active Directory · Microsoft 365 · Fortinet Firewall · RBAC · VLAN | [🔗 View Full Report](https://github.com/Bikash-Raya/IT-Infrastructure-Design-Deployment-Homelab-Project) |

---

## 🏢 Forage Cybersecurity Virtual Internships

| Simulation | Company | What I Did | Tools / Skills | Repo | Certificate |
|------------|---------|-----------|----------------|------|-------------|
| Cybersecurity Analyst | Tata | Assessed an organisation's cybersecurity posture and provided strategic security advisory recommendations | Threat Analysis · Risk Reporting · Security Frameworks | — | [🔗 View Full Report](https://www.theforage.com/completion-certificates/ifobHAoMjQs9s6bKS/gmf3ypEXBj2wvfQWC_ifobHAoMjQs9s6bKS_HG5z6cFBsTiHgMNhb_1776147302554_completion_certificate.pdf) |
| Shields Up Cybersecurity | AIG | Responded to a ransomware threat scenario, assessed vulnerabilities, and drafted an incident response communication | Incident Response · Vulnerability Assessment · Ransomware Analysis | — | [🔗 View Full Report](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/AIG/2ZFnEGEDKTQMtEv9C_AIG_HG5z6cFBsTiHgMNhb_1702523682604_completion_certificate.pdf) |
| Cyber Security Management | ANZ Australia | Investigated phishing emails and analysed PCAP network traffic to extract hidden files and recover encoded data | Wireshark · HxD · PCAP Analysis · Base64 Decoding | [🔗 Repo](https://github.com/Bikash-Raya/ANZ-Cyber-Security-Job-Simulation) | [🔗 View Full Report](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/ANZ/Hf4QMESoFeQwXPsiH_ANZ%20Australia_HG5z6cFBsTiHgMNhb_1702344768941_completion_certificate.pdf) |
| Cybersecurity Job Simulation | Mastercard | Designed a phishing simulation, analysed results to identify vulnerable teams, and created targeted security awareness training | Phishing Simulation · Security Awareness · Presentation | [🔗 Repo](https://github.com/Bikash-Raya/Mastercard-Cybersecurity-Job-Simulation-Forage-) | [🔗 View Full Report Full Report](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/mastercard/vcKAB5yYAgvemepGQ_Mastercard_HG5z6cFBsTiHgMNhb_1702348419111_completion_certificate.pdf) |
| Cybersecurity Job Simulation | Telstra | Triaged a network malware incident, identified affected systems, and drafted a technical mitigation response | Incident Triage · Network Security · Malware Analysis | — | [🔗 View Full Report](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Telstra%20AU/RNhbu8QnDzthwynEf_Telstra_HG5z6cFBsTiHgMNhb_1701832539937_completion_certificate.pdf) |
| Cybersecurity Job Simulation | Datacom | Investigated APT34 (OILRIG) breach using OSINT and MITRE ATT&CK; delivered a risk assessment with inherent, current, and target risk ratings | MITRE ATT&CK · OSINT · NIST · Risk Matrix | [🔗 Repo](https://github.com/Bikash-Raya/Datacom-Cybersecurity-Job-Simulation) | [🔗 View Full Report](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Datacom/yTszJTvkHFBH6zAn3_Datacom_HG5z6cFBsTiHgMNhb_1702609391245_completion_certificate.pdf) |

---

## 🎓 Certifications

| Certification | Issuer | Credential |
|---------------|--------|------------|
| **CompTIA Security+** | CompTIA | [🔗 Verify](https://www.credly.com/badges/f489e367-4616-4da9-b3d1-fa2217abc36e) |
| **Google Cybersecurity Professional Certificate** | Google | [🔗 Verify](https://www.credly.com/badges/43176bd9-b0f9-4f68-8dfb-d91f18e5b55e/linked_in_profile) |
| **SC-200: Microsoft Security Operations Analyst** | Microsoft (via Udemy) | [🔗 Verify](https://www.udemy.com/certificate/UC-fab0f971-1d91-44f7-83e9-56952a75d336/) |

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
