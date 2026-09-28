<div align="center">

### aimozart

**Cloud data engineer**: Azure · GCP · Databricks · Spark · SQL · Python · 12 years of security & compliance

`AWS Solutions Architect – Associate` · `Databricks Certified Associate Developer for Apache Spark`

</div>

---
### 🏦 Now building: Big Iron Bank, a bank's data platform

A fictional Arizona community bank and the pipeline behind its books, built on Azure and then Google Cloud:

- Daily branch transaction files land raw, get validated, and post to balances in a Bronze/Silver/Gold lakehouse
- The books must balance to the cent, every day: opening + deposits − withdrawals = closing, or nothing publishes
- Bad records are quarantined with a reason code; rerunning a day never double-posts
- Account numbers masked, least-privilege access, and an audit trail of every load
- Card transactions streamed through Kafka and flagged in real time

The repository goes public as each piece lands.

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

That background is why I build data platforms the way regulated companies need them: controlled, documented, and
recoverable, with PCI DSS and SOX in mind.

---

### 🔐 Entropa: a post-quantum, tamper-evident audit trail

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- Every record signed with **ML-DSA-65 (NIST FIPS-204)**, verified byte-for-byte against NIST's official test vectors
- A Certificate-Transparency-style **Merkle log** with per-customer trees, signed checkpoints, and inclusion proofs
- Controls mapped from Google's HITRUST shared-responsibility matrix: least privilege, secrets only in Secret
  Manager. *Built and documented, not formally assessed.*
- gitleaks in pre-commit and CI (**0 leaks across 348 commits**), CodeQL, Dependabot, and a **public incident log**

---

### How I work

**Evidence over assertion.** Measure before and after. Every incident gets a write-up and a permanent fix. Secrets
never touch the repo, and the scanners prove it. Irreversible actions wait for approval.

### About the handle

`aimozart` is my handle, the name I build and ship under. Work history and references are on the résumé.

### Open to

**Remote** roles in **cloud data engineering** (Azure, GCP, Databricks), especially where security, governance and
compliance matter. Full-time or contract.

**[→ Résumé + contact](https://entropa.space/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
