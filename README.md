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
- **Supply chain & secrets:** gitleaks in pre-commit and CI (**0 leaks across 348 commits**), daily dependency
  vulnerability audits, crates published via **OIDC Trusted Publishing** (no long-lived tokens).
- **Detection & response:** alerting on errors, uptime, a missing heartbeat, and queue age. Every incident is
  root-caused from logs, fixed test-first with a permanent regression test, and written up in a
  **[public incident log](https://github.com/aimozart/entropa-public/blob/main/README.md#real-incidents-found-and-fixed)**.
- **Independently reviewed:** 17+ third-party builder-verification reports (Paxel, Y Combinator's builder tool).

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
