# Hi, I'm Bernard 👋

### Security engineer who turns certification requirements into automated, auditable controls-as-code.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bernard_Aderhold-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bernard-aderhold-jr-dba-963ab9305)
[![Email](https://img.shields.io/badge/Email-bernard.aderholdjr%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:bernard.aderholdjr@gmail.com)
![Location](https://img.shields.io/badge/Southern_California-open_to_relocation-555?style=flat&logo=googlemaps&logoColor=white)
![Clearance](https://img.shields.io/badge/TS%2FSCI-2015--2020_%C2%B7_eligible_for_reinstatement-2E7D32?style=flat)

I build the plumbing that makes compliance provable: GitOps review gates, CI policy checks, evidence lifecycle automation, and AI-assisted intake with a human approving every change. Before that I spent five years running a 24/7 regional security operations center for the Marine Corps Enterprise Network (30 staff, 90k endpoints, 700+ incidents), and seven in the Army as a signal NCO.

My doctorate studied how frontline SOC/NOC analysts actually adopt, trust, and work alongside AI — which is why everything I build keeps a human in the loop by design.

---

## 🛠️ What I'm building

### 🔐 ONI — GRC-as-code platform &nbsp;`grc-readiness`
Automates ISO/IEC 42001, ISO/IEC 27001, and SOC 2 readiness. Each client's compliance record is version-controlled YAML; every change to a control, evidence item, or gap goes through a reviewed pull request; CI blocks merges that overstate readiness, and no automated step can mark a control verified.
- ✅ Audit logic as code: four-part evidence test, evidence expiry, approver/auditor independence, corrective-action lifecycle
- 🧩 Framework-neutral engine — SOC 2 added via catalog/playbook files, with an ISO 27001 ↔ SOC 2 crosswalk
- 🤖 AI-assisted document ingestion (Anthropic API) drafts gaps for analyst approval
- ⚙️ 15 GitHub Actions workflows · 244-test suite · 4 synthetic client engagements with planted findings
- ☁️ Client portal on Cloudflare Workers behind Cloudflare Access

### 🧠 Aderhold A.R.C. — AI-adoption governance framework &nbsp;`aderhold-arc`
A 45-item diagnostic scoring 15 risk dimensions across **A**cceptance, **R**eliance, **C**ollaboration, and a Foundation of human authority — derived from my dissertation research and mapped to NIST AI RMF and ISO/IEC 42001.
- 📊 Apps Script survey → Google Sheets → Python scoring engine on nightly GitHub Actions
- 📈 Three-wave measurement with statistically reliable change detection (≥5 pts, p < .05)
- 🔍 Leader-vs-staff gap analysis, Value Leakage ROI model, automated psychometrics (Cronbach's α, EFA)
- 🔒 Privacy by design: no PII, small-group suppression, least-privilege service accounts

### 🛡️ Talia — AI-assisted SOC/NOC/GRC operations platform &nbsp;`Talia-project` *(prototype, 2025)*
Six containerized FastAPI/PostgreSQL microservices: SOC (YAML detection rules, UEBA, VirusTotal enrichment, LLM log parsing), NOC (nmap discovery, SNMP metrics), GRC (policy-to-control mapping), security-awareness gamification, a status dashboard, and a Docker-SDK deployment agent for hybrid cloud/on-prem rollout.

---

## 🧩 Stack

**Languages**&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat&logo=yaml&logoColor=white)

**Platforms**&nbsp;
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_API-191919?style=flat&logo=anthropic&logoColor=white)

**Frameworks**&nbsp;
![ISO 27001](https://img.shields.io/badge/ISO%2FIEC_27001-1F3A5F?style=flat)
![ISO 42001](https://img.shields.io/badge/ISO%2FIEC_42001-1F3A5F?style=flat)
![SOC 2](https://img.shields.io/badge/SOC_2-1F3A5F?style=flat)
![NIST RMF](https://img.shields.io/badge/NIST_800--53_%2F_RMF-1F3A5F?style=flat)
![NIST AI RMF](https://img.shields.io/badge/NIST_AI_RMF-1F3A5F?style=flat)
![FedRAMP](https://img.shields.io/badge/FedRAMP-1F3A5F?style=flat)

---

## 💼 Background

| | |
| --- | --- |
| 🟢 **Now** | GRC Engineer, Trustology — ISO 42001 / 27001 / SOC 2 / FedRAMP / TxRAMP readiness |
| 🏵️ **2015–2020** | RNOSC Senior Cyberspace Analyst (GS-12), U.S. Marine Corps Forces, Pacific — led a 24/7 regional SOC; stood up its CTI cell; RMF ATO lead for its SIEM; 2× Excellence in Federal Government Award |
| 🖥️ **2012–2015** | Lockheed Martin / AT&T / Jacobs contracts at MARFORPAC — RNOSC analyst lead, STIG hardening, workstation lifecycle automation |
| 🎖️ **2005–2012** | U.S. Army Staff Sergeant, Signal (25U) — Iraq, Okinawa, Fort Campbell; DIACAP ATO packages, IASO, COMSEC |
| 🎓 **Education** | DBA Information Technology (National University, 2026) · MBA · BA International Business |

📖 **Dissertation:** *Acceptance, Reliance, and Collaboration: The Lived Experiences of SOC and NOC Professionals* — a phenomenological study of AI adoption on the security front line.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Baderholdjr&show_icons=true&hide_border=true&count_private=true&theme=default" alt="GitHub stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Baderholdjr&layout=compact&hide_border=true&theme=default" alt="Top languages" height="150" />
</p>

<p align="center">📬 Open to Security Engineering, GRC Engineering, and AI Governance roles — <a href="https://www.linkedin.com/in/bernard-aderhold-jr-dba-963ab9305">let's talk</a>.</p>
