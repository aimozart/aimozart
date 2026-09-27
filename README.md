<div align="center">

### aimozart

**AI governance & security**: NIST AI RMF · ISO/IEC 42001 · EU AI Act · HITRUST/HIPAA · 12 years of security & compliance

`AWS Solutions Architect – Associate` · `Databricks Certified Associate Developer for Apache Spark` · `IAPP AIGP: in preparation`

</div>

---
### 🔒 Security has always been the job

Twelve years of security work across every layer, whatever the title said:

| Layer | What I've done |
|---|---|
| **Governance & compliance** | Co-authored a healthcare security-policy framework and drove the remediation to official **HITRUST certification** and continuous HIPAA compliance; CIS Benchmark hardening of a live Windows fleet; PHI chain of custody on encrypted drives |
| **Platform operations** | **IBM i (AS/400)** user administration and outage remediation in a 24/7 retail environment |
| **Endpoint & identity** | Enterprise **EDR** across a global fleet, **privileged access management**, patch and baseline-configuration management |
| **Host & web** | Linux server hardening and WordPress security for 120+ enterprise accounts |
| **Security by design** | Everything below: cryptography, controls, supply chain, and detection, built as code with the evidence public |

AI needs the same discipline: know what's running, assess the risk, map the controls instead of assuming them,
keep a human on anything irreversible, and leave a record that can be checked later. That's the work I do now.

---

### 🔐 Entropa: a tamper-evident audit trail for AI-agent decisions

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- The record-keeping and traceability that NIST AI RMF and the EU AI Act expect, built rather than promised
- Every record signed with **ML-DSA-65 (NIST FIPS-204)**, verified byte-for-byte against NIST's official test vectors
- A Certificate-Transparency-style **Merkle log** with per-customer trees, signed checkpoints, and inclusion proofs;
  only hashes are stored, never customer content
- Controls mapped from Google's HITRUST shared-responsibility matrix: least privilege, secrets only in Secret
  Manager. *Built and documented, not formally assessed.*
- gitleaks in pre-commit and CI (**0 leaks across 348 commits**), CodeQL, Dependabot, and a **public incident log**

---

### How I work

**Evidence over assertion.** Measure before and after. Every incident gets a write-up and a permanent fix. Secrets
never touch the repo, and the scanners prove it. My own AI coding agents work under written guardrails: tests
first, scans on every change, and a human approval before anything irreversible.

### About the handle

`aimozart` is my handle, the name I build and ship under. Work history and references are on the résumé.

### Open to

**Remote** roles in **AI governance, AI risk and AI security**: policy, risk assessments, control mapping, and the
engineering behind them. Full-time or contract.

**[→ Résumé + contact](https://entropa.space/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
