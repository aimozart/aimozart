<div align="center">

### aimozart

**Cloud Security Engineer**: Zero Trust identity · security posture & detection · HITRUST/HIPAA · post-quantum cryptography

`AWS Solutions Architect – Associate` · `Databricks Spark Developer` · `Microsoft SC-500 (Cloud & AI Security Engineer): in progress`

</div>

---

### Security has always been the job

Twelve years of security work across every layer, whatever the title said:

| Layer | What I've done |
|---|---|
| **Host & web** | Web-hosting security SME: Linux server hardening (iptables/CSF, fail2ban, ModSecurity, AppArmor, ClamAV/Maldet, cPanel/WHM & Plesk) plus WordPress hardening for 120+ enterprise accounts |
| **Governance & compliance** | Co-authored a healthcare security-policy framework and drove the remediation to official **HITRUST certification** and continuous HIPAA compliance; PHI chain of custody, vulnerability scanning (Qualys/OpenVAS) |
| **Incident response** | Led remediation during mission-critical outages in a 24/7 retail environment; wrote the SOPs |
| **Endpoint & identity** | Enterprise **EDR** across a global fleet, **privileged access management**, patch and baseline-configuration management |
| **Security by design** | Everything below: cryptography, cloud controls, supply chain, detection, built as code with the evidence public |

---

### 🔐 Entropa: a post-quantum, tamper-evident audit trail for AI decisions

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- **Post-quantum signatures:** every record signed with **ML-DSA-65 (NIST FIPS-204)**, verified byte-for-byte against
  NIST's official ACVP test vectors. A negative control proves the suite catches a single corrupted byte, and receipts
  were confirmed with an independent third-party ML-DSA implementation.
- **Tamper evidence:** a Certificate-Transparency-style **Merkle log** with a separate tree for each customer,
  signed checkpoints, and inclusion proofs. **Data-minimal:** only hashes are stored, never content.
- **HITRUST-informed cloud:** mapped Google's HITRUST Shared Responsibility Matrix (3,342 requirements: 77 fully
  inherited, 415 partially, **2,850 customer-owned**) and built the controls on my side of that split:
  least-privilege service accounts, secrets and signing keys only in Secret Manager, OAuth2/JWT at the gateway
  (Keycloak), SASL-authenticated Kafka, managed TLS. *Built and documented, not formally assessed.*
- **Supply chain & secrets:** gitleaks in pre-commit and CI (**0 leaks across 348 commits**), CodeQL code scanning,
  Dependabot + dependency review on every PR; the original Rust crates were published via **OIDC Trusted Publishing**.
- **Detection & response:** alerting on errors, uptime, a missing heartbeat, and queue age. Every incident is
  root-caused from logs, fixed test-first with a permanent regression test, and written up in a
  **[public incident log](https://github.com/aimozart/entropa-public/blob/main/README.md#real-incidents-found-and-fixed)**.
- **Independently reviewed:** 17+ third-party builder-verification reports (Paxel, Y Combinator's builder tool).

---

### 🔑 Secrets & supply-chain guardrails

Secrets don't get into my repos, and that's enforced by layered checks, not just intended:

| Layer | Guardrail |
|---|---|
| **Before the commit** | A local `pre-commit` hook runs **gitleaks** plus the full gate (format, lint, tests, file-size limits, dependency audit). A commit that fails any check is blocked |
| **At the push** | **GitHub secret scanning + push protection** are enabled on every public repo, so GitHub rejects a push that contains a recognized credential |
| **In CI** | **gitleaks** runs as its own CI job on every push, scanning the full git history, not just the diff |
| **Code scanning (SAST)** | **CodeQL** (security-extended queries) analyzes the Java services on every push, every PR, and weekly |
| **Dependencies** | **Dependabot** alerts + automatic security-fix PRs, weekly grouped updates for Gradle, GitHub Actions, and Docker base images; **dependency review** fails any PR that adds a known-vulnerable dependency |
| **Across history** | Periodic full-history scans: **0 leaks across 348 commits** on the flagship. Known-safe fixtures (NIST FIPS-204 test vectors look like keys to a naive scanner) are documented in an allowlist, never silently ignored |
| **Where secrets actually live** | GCP **Secret Manager** / Kubernetes secrets / encrypted **GitHub Actions secrets**. The only env file in a repo is `.env.example` with placeholders, and the real `.env` is gitignored |
| **Separation** | Keys and private strategy live in a separate private repo that never touches a public remote. The private/public split is checked by remote before every push |
| **Publishing** | Entropa's original Rust crates were published via **OIDC Trusted Publishing**: short-lived tokens, no long-lived registry credentials |
| **Human gate** | Irreversible actions (deploys, force-pushes, deletions, account-level changes) need an explicit approval step, including when an AI coding assistant is doing the work |

---

### 🛡️ In progress: Azure Zero Trust security capstone (SC-500)

A healthcare clinic's Azure environment, secured and monitored **entirely as code** (Bicep · PowerShell · KQL),
completing October 2026 with a public evidence site:

- **Identity:** PIM just-in-time roles, conditional access with phishing-resistant MFA, locked-down app consent,
  managed identities, Key Vault behind a private endpoint
- **Posture:** Defender for Cloud, HITRUST/HIPAA regulatory compliance, JIT VM access, Machine Configuration
  baselines, Secure Score measured **before and after**
- **Detection & response:** Microsoft Sentinel with custom KQL analytics rules (MITRE-mapped), playbooks, and
  PowerShell response runbooks, each validated with safe test signals and written up as an incident
- **AI security:** Azure OpenAI with Entra-only auth, network isolation, Prompt Shields, Defender for AI

---

### How I work

**Evidence over assertion.** Measure before and after. Every incident gets a write-up and a permanent regression
test. Secrets never touch the repo, and the scanners prove it. Irreversible actions wait for approval. The build
history, incident log, and third-party reports are all here to check.

### About the handle

`aimozart` is my handle, the name I build and ship under. Work history and references are on the résumé.

### Open to

**Cloud security engineering** roles (identity, posture, detection & response, Azure/GCP/AWS), full-time or contract.

**[→ Résumé + contact](https://entropa.space/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
