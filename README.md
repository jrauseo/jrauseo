<!-- Profile README for github.com/jrauseo. Publish as the README.md of a PUBLIC repo named "jrauseo" (jrauseo/jrauseo). -->

<h1 align="center">Hi, I'm Jimmy 👋</h1>

<p align="center">
  <b>Managed services &amp; infrastructure engineer at <a href="https://infonaligy.com">Infonaligy Partners</a></b><br/>
  Automating IT operations, hardening systems, and making AI agents safe to run in production.
</p>

---

### 🔭 What I work on

- **Managed services operations:** client onboarding, patch management, monitoring, and runbook-driven incident response.
- **Microsoft 365 & Windows automation:** Entra ID, Conditional Access, Graph API, and PowerShell with least-privilege scopes.
- **Security-first engineering:** secrets management, vault integration, container hardening, and threat modeling (STRIDE, MITRE ATT&CK, NIST CSF 2.0).
- **AI-assisted workflows:** reusable Claude Code skills and MCP integrations that put security guardrails around everyday operations.

---

### 🛡️ How I build

I follow a hardened-by-default standard on everything I ship:

1. **No hardcoded secrets.** Credentials come from a vault or environment placeholders, never from source.
2. **No exposed internals.** Private IPs and hostnames stay out of code, logs, and docs.
3. **Safe execution.** Argument-array commands, no concatenated shell strings.
4. **Least privilege.** Read-only audit steps are separated from admin and write steps.
5. **Atomic, reversible changes.** Temp-file writes, transactions, and backups before anything destructive.
6. **Proof before findings.** A vulnerability isn't reported until the exploit path is traced and verified.
7. **Object-level authorization.** Every resource ID is checked against the authenticated owner on the server (OWASP API1, IDOR/BOLA).

---

### 🧰 Tech stack

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat&logo=microsoft365&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)

- **Platforms & tooling:** ConnectWise, Veeam, Axcient, Windows Server, Linux
- **Automation:** PowerShell (Pester), Bash, GitHub Actions with pinned runners
- **Security & compliance:** STRIDE, OWASP API Top 10, CIS benchmarks, secret scanning, incident response
- **AI & agents:** Claude Code skills, Model Context Protocol (MCP), spec-driven development

---

### 🌱 Currently

- Building and maintaining a library of security-hardened automation skills for day-to-day MSP work.
- Extending those skills with object-level authorization (IDOR/BOLA) rules across design, coding, QA, and audit.
- Exploring safer patterns for running AI agents against real infrastructure.

---

### 📬 Reach me

- **Company:** [Infonaligy Partners](https://infonaligy.com)
- **LinkedIn:** <!-- TODO: add your LinkedIn URL -->
- **Also on GitHub:** [@rauseoj89](https://github.com/rauseoj89), where I publish public blueprints and write-ups.

<sub>Opinions and projects here are my own.</sub>
