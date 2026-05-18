# Josh Conkel

**Lead Product Security Engineer** &nbsp;|&nbsp; Docusign &nbsp;|&nbsp; Rio Vista / Oakland, CA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-josh--conkel-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/josh-conkel)
[![Email](https://img.shields.io/badge/Email-josh.conkel%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:josh.conkel@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-joshconkel-181717?style=flat&logo=github)](https://github.com/joshconkel)

---

## What I Do

Product security engineer with 20+ years building security programs that engineering teams actually adopt. I work at the intersection of **secure SDLC**, **agentic AI security**, and **software supply chain**, translating risk into practical controls that ship into CI/CD pipelines without slowing delivery.

At Docugign I lead our Security Champions program, build security tools for developers to use on a daily basis, and coding security guardrails across product teams. Before that: principal-level consulting at KPMG and EY (AppSec, data security, and regulatory readiness for multiple large clients), and a DevSecOps practice lead at Slalom.

Currently building open tooling for the **MCP and agentic AI attack surface**, a risk area that is moving faster than most teams' defenses.

---

## Currently Building

### [mcp-sentinel](https://github.com/joshconkel/mcp-sentinel) &nbsp;`active`

Static and dynamic security auditor for MCP (Model Context Protocol) servers — the tool layer between LLMs and the systems they act on. Maps findings to **OWASP MCP Top 10**, **OWASP Top 10 for Agentic Applications (2026)**, and **MITRE ATLAS** via a pluggable, versioned rule engine.

Built because the agentic AI attack surface (tool poisoning, supply chain compromise, over-permissioned schemas, prompt injection via tool results) is largely undefended and moving into production at speed.

`python` &nbsp; `mcp` &nbsp; `llm-security` &nbsp; `agentic-ai` &nbsp; `appsec` &nbsp; `owasp`

---

### [Veritas-POC](https://github.com/joshconkel/Veritas-POC) &nbsp;`active`

An AI driven local code security scanner built to help developers perform more effective manual secure code reviews. This approach an agentic AI approach with JSON artifact pipelines to let developers know where the needles are in the haystack.

The pipeline scans a directory of source files, runs each file through a chain of specialized security agents (scope → threat model → hypotheses → evidence → fix → gate), and produces structured JSON artifacts and a Markdown report per file, plus a merged summary across all files.

`python` &nbsp; `agenticAI` &nbsp; `security-champions` &nbsp; `securecode` &nbsp; `llm` &nbsp; `owasp`

---

## Focus Areas

<table>
<tr>
<td valign="top" width="33%">

**Program & Process**
- Security Champions Programs
- Secure SDLC (Shift-Left)
- Threat Modeling & Secure Design Reviews
- Vulnerability Management Automation
- Third-Party / OSS Governance
- Regulatory Readiness (FedRAMP, FISMA, ISO 27001, SOX)

</td>
<td valign="top" width="33%">

**Engineering & Tooling**
- CI/CD Security Guardrails (policy-as-code, secrets, scanning)
- Software Supply Chain (SLSA, code signing, SBOM, integrity)
- Cloud Security (AWS, Azure)
- Secrets Management
- Data Security & DLP
- Application Security Architecture

</td>
<td valign="top" width="33%">

**Emerging (2025-2026)**
- MCP Server Security
- Agentic AI Threat Modeling
- LLM Security (prompt injection, tool misuse)
- AI Supply Chain Risk
- AI-Assisted Security Automation

</td>
</tr>
</table>

---

## Featured Projects

| Project | What It Is | Stack |
|---|---|---|
| [**mcp-sentinel**](https://github.com/joshconkel/mcp-sentinel) | MCP server security auditor (OWASP MCP Top 10, Agentic Top 10, MITRE ATLAS) with pluggable multi-source rule engine | Python |
| [**security-champions-kit**](https://github.com/joshconkel/security-champions-kit) | 36-month Security Champions program framework (intake, enablement tracks, metrics, governance playbooks) built from real program experience | Markdown / Templates |
| [**Veritas-POC**](https://github.com/joshconkel/Veritas-POC) | Multi-stage agentic LLM pipeline for automated security code review | Python |
| [**Dome9toDD**](https://github.com/joshconkel/Dome9toDD) | Dome9 cloud security findings bridge to DefectDojo for centralized vulnerability tracking | Python |

---

## Certifications

![CISSP](https://img.shields.io/badge/CISSP-2007--Present-003087?style=flat&logo=isc2&logoColor=white)
![OSCP](https://img.shields.io/badge/OSCP-2024-E84A27?style=flat&logo=offensive-security&logoColor=white)
![AWS SAA](https://img.shields.io/badge/AWS_Solutions_Architect-Associate-FF9900?style=flat&logo=amazonaws&logoColor=white)
![AWS ML](https://img.shields.io/badge/AWS_ML_Specialty-2022--2025-FF9900?style=flat&logo=amazonaws&logoColor=white)
![DevSecOps](https://img.shields.io/badge/Certified_DevSecOps_Professional-2021-4B0082?style=flat)
![CISM](https://img.shields.io/badge/CISM-2015--2023-003087?style=flat)

> The CISSP (2007) paired with OSCP (2024) along with other certifications along the way reflects both program-level governance experience and continued investment in hands-on technical depth.

---

## Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub_Enterprise-181717?style=flat&logo=github)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat&logo=gitlab&logoColor=white)

---

## Education

**M.S. Engineering Management** - Ohio University &nbsp;|&nbsp; **B.S. Computer Engineering** - Shawnee State University

---

## Selected Wins (From the Field)

- **80%+ reduction in security review time** (multiple sprints to a single sprint before release) by delivering end-to-end pipeline automation of application security scanning at Slalom (global diagnostics client)
- **Data Security Program Office** for one of the largest U.S. utilities, safeguarding data for 40M+ customers and 50K+ employees across cloud and on-prem environments (KPMG)
- **Software Supply Chain Security program** at DocuSign: code signing, artifact integrity verification, and dependency risk management across multiple products
- **Security Champions program** at DocuSign: gamified hands-on training (Security Journey), self-service tooling, and embedded security ownership across product engineering teams
- **NERC CIP v3 to v5 migration** training and delivery as cybersecurity SME for SCADA/IoT environments (EY)
- **FISMA/FedRAMP ATO** achieved within first year of building program from scratch (TPMC/SAIC)

---

*Open to conversations about senior product security, AI/LLM security, and security program leadership roles.*

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-LinkedIn-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/josh-conkel)
[![Email](https://img.shields.io/badge/Email_Me-josh.conkel%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:josh.conkel@gmail.com)

<!--
**joshconkel/joshconkel** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
