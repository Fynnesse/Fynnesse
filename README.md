# Jeremiah Asagba

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeremiahasagba)
[![Security+](https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white)](https://www.credly.com/badges/6e5b060b-26d7-401c-9477-71f0cac0c2e5/public_url)
[![Network+](https://img.shields.io/badge/-Network%2B-007ACC?&style=for-the-badge&logo=CompTIA&logoColor=white)](https://www.credly.com/badges/dbcc35d7-77ca-4db7-942c-28da1f8a026a/public_url)

I'm a security analyst based in Manchester, UK, working toward a Tier 1 SOC role.

Most of what's here is documentation rather than code. I investigate things in live cloud environments and write up how I did it, including the parts that went wrong. I hold an MSc in Cybersecurity Management, Security+ and Network+, and two years of IT support experience before this.

Currently working through a 10-week cloud security track. Five investigations published so far, with storage exposure hunting up next.

---

## Cloud Security Investigations

Documented investigations in a live multi-user Azure tenant. Each one covers method, evidence and severity-ranked remediation.
**[→ security-portfolio](https://github.com/Fynnesse/security-portfolio)**

| # | Investigation | Focus |
|---|---|---|
| 1 | [Tracing a Non-Compliant Azure Deployment to an Audit-Only Policy](https://github.com/Fynnesse/security-portfolio/blob/main/01-operation-dead-deploy.md) | Governance forensics, Azure Policy, deployment audit trail |
| 2 | [Reconstructing an OAuth Consent-Phishing Kill Chain](https://github.com/Fynnesse/security-portfolio/blob/main/02-The-Stolen-Identity.md) | Entra ID, app registrations, OAuth consent abuse |
| 3 | [Auditing Azure RBAC Four Ways: What Each Method Cannot See](https://github.com/Fynnesse/security-portfolio/blob/main/03-Privilege-Audit.md) | Azure RBAC, PIM, Resource Graph with KQL, least privilege |
| 4 | [Reviewing a Friday Deploy Against a Production Baseline](https://github.com/Fynnesse/security-portfolio/blob/main/04-Spin-Up-and-Lock-Down.md) | Pre-production review, public storage exposure, NSG rules, managed identity |
| 5 | [Tracing Private Storage Traffic Past a Forced Tunnel](https://github.com/Fynnesse/security-portfolio/blob/main/05-Network-the-Operative.md) | Private endpoints, private DNS, NSG and route table precedence |

## Lab Builds

| Project | What I built | Tools |
|---|---|---|
| [SOC Automation Lab](https://github.com/Fynnesse/SOC-Automation-Lab) | Detection rules for credential-dumping activity and an end-to-end SOAR pipeline from alert to case creation | Wazuh, Shuffle, TheHive, VirusTotal |
| [Active Directory Lab](https://github.com/Fynnesse/Active-Directory-Lab) | A virtualised AD environment with centralised logging, attacked and then detected | Windows Server, Splunk, Sysmon, Atomic Red Team, Hydra |
| [Malware Analysis Lab](https://github.com/Fynnesse/Malware-Analysis-w-REMnux-Lab) | Static analysis of a malicious document through to C2 identification and a findings report | REMnux, rtfdump, scdbg, VirusTotal |
| [Network Analysis Lab](https://github.com/Fynnesse/Network-Analysis-Lab) | Traffic monitoring and attack detection | Wireshark |

## Tools I've actually used

Nothing listed here that isn't behind a project above.

| Area | Tools |
|---|---|
| **Cloud & identity** | Azure · Entra ID · Conditional Access · Azure Policy · Microsoft Graph · RBAC · Active Directory · AWS (IAM, EC2, S3, VPC, CloudTrail) |
| **Detection & response** | Splunk · Wazuh · Microsoft Defender for Endpoint · TheHive · Shuffle · Sysmon · VirusTotal |
| **Analysis & forensics** | REMnux · Wireshark · Nmap · KQL · PowerShell |
| **Frameworks** | MITRE ATT&CK · NIST CSF |

## Certifications & education

| | | |
|---|---|---|
| **CompTIA Security+** | Renewed 2026 | [Verify](https://www.credly.com/badges/6e5b060b-26d7-401c-9477-71f0cac0c2e5/public_url) |
| **CompTIA Network+** | Renewed 2026 | [Verify](https://www.credly.com/badges/dbcc35d7-77ca-4db7-942c-28da1f8a026a/public_url) |
| **CompTIA CySA+** | Expected December 2026 | |
| **TryHackMe SAL1** | Expected December 2026 | |
| **MSc Cybersecurity Management** | University of Law, Manchester · 2025 | |
| **BSc Computer Science** | Babcock University, Nigeria · 2021 | |
