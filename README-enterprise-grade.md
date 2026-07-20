<div align="center">

# Luiz Hamilton Roberto da Silva

### Principal Identity Architect · Windows Security & DFIR · PowerShell Automation

**Active Directory · Microsoft Entra ID · Hybrid Identity · IAM · PKI · Zero Trust · Windows Server**

I engineer secure, auditable, resilient, and scalable identity and infrastructure solutions for enterprise and public-sector environments.

[![GitHub](https://img.shields.io/badge/GitHub-@brazilianscriptguy-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brazilianscriptguy)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-brazilianscriptguy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brazilianscriptguy/)
[![YouTube](https://img.shields.io/badge/YouTube-@brazilianscriptguy-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@brazilianscriptguy)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3705--7468-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-3705-7468)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luizhamilton.lhr@gmail.com)

</div>

---

## Executive Profile

I design, secure, automate, and govern Microsoft-centric identity and infrastructure platforms, with emphasis on:

- **Identity architecture:** Active Directory Domain Services, Microsoft Entra ID, hybrid identity, authentication, authorization, privileged access, and lifecycle governance.
- **Windows security engineering:** Group Policy, security baselines, PKI, certificate services, server hardening, auditability, and operational resilience.
- **Enterprise automation:** production-oriented PowerShell frameworks, repeatable provisioning, configuration enforcement, structured logging, and release engineering.
- **Cybersecurity and DFIR:** Windows Event Log and EVTX analysis, forensic readiness, threat hunting, incident investigation, and evidence-oriented workflows.
- **Governance and service management:** ITSM-aligned operations, risk-based controls, traceability, compliance support, and maintainable technical standards.

> **Engineering objective:** strengthen trust, governance, security, and operational excellence through systems that are measurable, supportable, and designed for production.

---

## Featured Engineering Platform

### [Windows-SysAdmin-ProSuite](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite)

[![Latest Release](https://img.shields.io/github/v/release/brazilianscriptguy/Windows-SysAdmin-ProSuite?style=for-the-badge&logo=github&label=Release)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/releases)
[![License](https://img.shields.io/github/license/brazilianscriptguy/Windows-SysAdmin-ProSuite?style=for-the-badge&logo=opensourceinitiative)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/blob/main/LICENSE.txt)
[![Stars](https://img.shields.io/github/stars/brazilianscriptguy/Windows-SysAdmin-ProSuite?style=for-the-badge&logo=github)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/stargazers)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18487320-1682D4?style=for-the-badge&logo=zenodo&logoColor=white)](https://doi.org/10.5281/zenodo.18487320)

An enterprise-grade, research-aligned automation platform for Windows Server and Windows workstation environments. The suite combines system administration, identity engineering, defensive security, ITSM-oriented provisioning, reusable automation components, and governed release practices.

### Architectural Principles

- **Security by design:** least privilege, credential hygiene, controlled execution, integrity validation, and traceable outcomes.
- **Repeatability:** standardized inputs, predictable behavior, reusable modules, and documented operational boundaries.
- **Auditability:** structured logs, evidence preservation, deterministic workflows, and reviewable configuration changes.
- **Modularity:** shared libraries, clear responsibility boundaries, composable tools, and centralized orchestration.
- **Operational safety:** validation, error handling, explicit dependencies, rollback-aware execution, and supportable implementation patterns.
- **Release integrity:** CI validation, static analysis, SARIF reporting, package automation, and SHA-256 verification.

---

## Platform Components

| Component | Operational Scope | Representative Capabilities |
|---|---|---|
| [`SysAdmin-Tools`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/SysAdmin-Tools) | Windows Server and infrastructure administration | AD and OU lifecycle, GPO operations, WSUS and SUSDB, DNS, DHCP, AD CS, and RDS |
| [`BlueTeam-Tools`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/BlueTeam-Tools) | Defensive security and DFIR | Evidence collection, EVTX parsing, credential auditing, event correlation, and threat hunting |
| [`Core-ScriptLibrary`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/Core-ScriptLibrary) | Shared PowerShell framework | Common functions, structured logging, validation, packaging, integrity checks, and release helpers |
| [`ITSM-Templates-WKS`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/ITSM-Templates-WKS) | Windows workstation lifecycle | Pre- and post-domain-join automation, profiles, printers, baselines, standardization, and compliance controls |
| [`ITSM-Templates-SVR`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/ITSM-Templates-SVR) | Windows Server lifecycle | Provisioning, role configuration, security baselines, hardening, configuration consistency, and audit logging |
| [`GPO-Templates`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/SysAdmin-Tools/GroupPolicyObjects-Templates) | Policy engineering | Reusable domain and forest policy templates, security controls, user-experience standards, and import/export automation |
| [`AD-SSO-Integrations`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/SysAdmin-Tools/ActiveDirectory-SSO-Integrations) | Application identity integration | LDAP and SSO implementation patterns for PHP, .NET, Flask, Node.js, and Spring Boot |
| [`ProSuite-Hub`](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/tree/main/ProSuite-Hub) | Central orchestration | Unified launcher, module discovery, menu-driven execution, and a consistent operator entry point |

---

## Engineering Assurance

### Continuous Integration and Release Management

[![Release Automation](https://img.shields.io/github/actions/workflow/status/brazilianscriptguy/Windows-SysAdmin-ProSuite/make-update-github-releases.yml?branch=main&style=flat-square&label=Release%20Automation&logo=githubactions)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/actions/workflows/make-update-github-releases.yml)
[![NuGet Publishing](https://img.shields.io/github/actions/workflow/status/brazilianscriptguy/Windows-SysAdmin-ProSuite/publish-nuget-package-to-github.yml?branch=main&style=flat-square&label=NuGet%20Publishing&logo=nuget)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/actions/workflows/publish-nuget-package-to-github.yml)

Release practices include automated packaging, changelog generation, artifact publication, and SHA-256 integrity validation.

### Code Quality and Static Analysis

[![EditorConfig](https://img.shields.io/github/actions/workflow/status/brazilianscriptguy/Windows-SysAdmin-ProSuite/editorconfig-check.yml?branch=main&style=flat-square&label=EditorConfig&logo=editorconfig)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/actions/workflows/editorconfig-check.yml)
[![Prettier](https://img.shields.io/github/actions/workflow/status/brazilianscriptguy/Windows-SysAdmin-ProSuite/prettier-code-format-check.yml?branch=main&style=flat-square&label=Prettier&logo=prettier)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/actions/workflows/prettier-code-format-check.yml)
[![PSScriptAnalyzer](https://img.shields.io/github/actions/workflow/status/brazilianscriptguy/Windows-SysAdmin-ProSuite/psscriptanalyzer-sarif-reports.yml?branch=main&style=flat-square&label=PSScriptAnalyzer&logo=powershell)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/actions/workflows/psscriptanalyzer-sarif-reports.yml)
[![VBScript Validation](https://img.shields.io/github/actions/workflow/status/brazilianscriptguy/Windows-SysAdmin-ProSuite/vbscript-syntax-validation.yml?branch=main&style=flat-square&label=VBScript%20Validation&logo=windows)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/actions/workflows/vbscript-syntax-validation.yml)

### Security Controls

[![Gitleaks](https://img.shields.io/github/actions/workflow/status/brazilianscriptguy/Windows-SysAdmin-ProSuite/secret-scan-gitleaks.yml?branch=main&style=flat-square&label=Gitleaks&logo=github)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/actions/workflows/secret-scan-gitleaks.yml)
[![Code Scanning](https://img.shields.io/badge/SARIF-Code%20Scanning-2EA44F?style=flat-square&logo=github)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/security/code-scanning)
[![Dependency Review](https://img.shields.io/badge/Supply%20Chain-Integrity%20Focused-0969DA?style=flat-square&logo=dependabot)](https://github.com/brazilianscriptguy/Windows-SysAdmin-ProSuite/security)

Security assurance emphasizes secret detection, static analysis, reviewable SARIF findings, artifact integrity, and controlled dependency management.

---

## Technical Domains

| Domain | Technologies and Practices |
|---|---|
| Identity and Access Management | Active Directory, Microsoft Entra ID, hybrid identity, LDAP, SSO, RBAC, privileged access, service accounts, gMSA, identity lifecycle, and access governance |
| Windows Infrastructure | Windows Server, Windows 10/11, DNS, DHCP, WSUS, RDS, Group Policy, AD CS, PKI, certificates, and server roles |
| Security Engineering | Zero Trust, security baselines, hardening, least privilege, credential protection, audit policy, secure administration, and control validation |
| Automation and DevSecOps | PowerShell, VBScript, GitHub Actions, NuGet, PSScriptAnalyzer, EditorConfig, Prettier, Gitleaks, SARIF, CodeQL, and SHA-256 |
| DFIR and Log Analytics | Windows Event Logs, EVTX, event correlation, forensic readiness, evidence collection, incident response, threat hunting, and SQL-based parsers |
| Governance and Operations | ITSM, ITIL, COBIT, operational controls, documentation, standardization, traceability, risk management, and compliance support |

---

## Research and Publications

My engineering work is informed by applied research in Windows event logging, auditability, digital forensics, Group Policy, and enterprise security.

### Peer-Reviewed Article

**SQL Syntax Models for Building Parsers to Query Event Logs in EVTX Format**  
*Revista FT — Computer Science*, Vol. 29, Issue 142, January 2025 · ISSN 1678-0817  
[![DOI](https://img.shields.io/badge/DOI-10.69849%2Frevistaft%2Fth102502121360-1682D4?style=flat-square&logo=crossref)](https://doi.org/10.69849/revistaft/th102502121360)

A structured SQL-oriented method for querying Windows Event Log data to support auditing, incident investigation, event correlation, and Active Directory authentication analysis.

### Books

**Event Logs: Applying a Log Analysis Model for Auditing Event Record Registration**  
Sorian, 1st edition, 2024 · Print ISBN `978-65-5453-346-1` · eBook ISBN `978-65-5453-366-9`  
[![DOI](https://img.shields.io/badge/DOI-10.54466%2Fsorianed.978--65--5453--366--9-1682D4?style=flat-square&logo=crossref)](https://doi.org/10.54466/sorianed.978-65-5453-366-9)

A practitioner-oriented work on event-log auditing, forensic readiness, vulnerability identification, Syslog concepts, and PowerShell-enabled analysis workflows.

**Computer Networking Technology: Using GPOs to Secure Corporate Domains**  
Ciência Moderna, 1st edition, 2009 · ISBN `978-85-7393-835-7`  
[![DOI](https://img.shields.io/badge/DOI-10.54236%2Fedcimo.001-1682D4?style=flat-square&logo=crossref)](https://doi.org/10.54236/edcimo.001)

A technical treatment of Group Policy as an enterprise mechanism for centralized security enforcement and Windows domain hardening.

### Master's Thesis

**Event Logs: Applying a Log Analysis Model for Auditing Event Record Registration**  
Federal University of Pernambuco — UFPE, 2017  
[![UFPE Repository](https://img.shields.io/badge/UFPE-Institutional%20Repository-003366?style=flat-square&logo=academia)](https://repositorio.ufpe.br/handle/123456789/27515)

The thesis defines a structured methodology for security monitoring, log auditing, and forensic analysis using Syslog principles and PowerShell-driven workflows.

### Academic Profiles

[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--3705--7468-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-3705-7468)
[![Lattes CV](https://img.shields.io/badge/Lattes-CNPq-006699?style=flat-square)](http://lattes.cnpq.br/0191525072495482)

---

## Professional Certifications

![ITIL 4 Foundation](https://img.shields.io/badge/ITIL%204%20Foundation-Certified-6C2DC7?style=flat-square)
![COBIT 4.1 Foundation](https://img.shields.io/badge/COBIT%204.1%20Foundation-Certified-4B0082?style=flat-square)
![COBIT 2019 Foundation](https://img.shields.io/badge/COBIT%202019%20Foundation-Certified-483D8B?style=flat-square)
![CompTIA Security+](https://img.shields.io/badge/CompTIA%20Security%2B-SY0--701-EA3C2D?style=flat-square&logo=comptia&logoColor=white)
![CISO Leader Certified](https://img.shields.io/badge/CISO%20Leader-Certified-B22222?style=flat-square)

---

## GitHub Activity

<div align="center">

![Profile Details](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=brazilianscriptguy&theme=tokyonight)

![GitHub Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=brazilianscriptguy&theme=tokyonight)
![Productive Time](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=brazilianscriptguy&theme=tokyonight&utcOffset=-3)

![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=brazilianscriptguy&theme=tokyo-night&hide_border=true&area=true)

</div>

---

## Professional and Community Channels

[![X](https://img.shields.io/badge/X-@brazscriptguy-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/brazscriptguy)
[![Instagram](https://img.shields.io/badge/Instagram-@4tetraforensics-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/4tetraforensics)
[![WhatsApp Channel](https://img.shields.io/badge/WhatsApp-PowerShellBR-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://whatsapp.com/channel/0029VaEgqC50G0XZV1k4Mb1c)
[![Location](https://img.shields.io/badge/Location-Macapá%2C%20Brazil-4285F4?style=flat-square&logo=googlemaps&logoColor=white)](https://www.google.com/maps/search/?api=1&query=2%C2%B037'13.0%22N+51%C2%B000'35.2%22W)
![Time Zone](https://img.shields.io/badge/Time%20Zone-UTC--03%3A00-2EA44F?style=flat-square)

---

## Support and Collaboration

For technical collaboration, research, enterprise automation, identity architecture, Windows security, or DFIR-related initiatives, use the professional channels above.

[![GitHub Sponsors](https://img.shields.io/badge/GitHub%20Sponsors-Support-EA4AAA?style=flat-square&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/brazilianscriptguy)
[![Patreon](https://img.shields.io/badge/Patreon-Support-FF424D?style=flat-square&logo=patreon&logoColor=white)](https://www.patreon.com/brazilianscriptguy)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support-FFDD00?style=flat-square&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/brazilianscriptguy)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support-FF5E5B?style=flat-square&logo=kofi&logoColor=white)](https://ko-fi.com/brazilianscriptguy)

---

<!--
Search and expertise layer:
PowerShell automation; Windows Server; Active Directory; Microsoft Entra ID; hybrid identity;
IAM; identity governance; privileged access; LDAP; SSO; gMSA; PKI; AD CS; certificates;
DNS; DHCP; WSUS; RDS; Group Policy; GPO; Zero Trust; security hardening; credential hygiene;
digital forensics; DFIR; EVTX; Windows Event Logs; event correlation; incident response;
ITSM; ITIL; COBIT; CI/CD; GitHub Actions; PSScriptAnalyzer; Gitleaks; SARIF; CodeQL;
NuGet; SHA256; enterprise architecture; Windows infrastructure automation.
-->

<div align="center">

**Luiz Hamilton Roberto da Silva** · [@brazilianscriptguy](https://github.com/brazilianscriptguy)

Profile content © 2026 Luiz Hamilton Roberto da Silva. Repository source code remains subject to the license declared in each respective project.

</div>
