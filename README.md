<div align="center">

### aimozart

**Elixir & Erlang/OTP**: fault-tolerant, distributed systems on the BEAM · 12 years of security & compliance

`AWS Solutions Architect – Associate` · `Databricks Certified Associate Developer for Apache Spark`

</div>

---
### ⚡ Now: Erlang and Elixir on the BEAM

I wanted the hardest challenge I'd actually love. I wrote Erlang and Haskell before AI coding tools existed,
and the BEAM's model is the systems work I want to do: millions of isolated processes, supervisors that
restart what fails, nodes that keep going through a network partition.

Eight weeks, in public:

- **Production drills:** ten tickets modeled on real outages (a flooded mailbox, cascading crashes, a
  netsplit, memory blowing up under a firehose), each closed only when tests prove the behavior under load
- **BEAM Ledger:** a distributed, tamper-evident event ledger that grows every week: a SHA-256 hash chain,
  supervision trees, ETS reads, signed receipts, quorum across three nodes, back-pressure, then Phoenix,
  LiveView and Postgres

Repositories go public here as each piece lands.

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

The same instinct drives the BEAM work: build systems that expect failure and recover by design.

---

### 🔐 Entropa: a tamper-evident audit trail for AI-agent decisions

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- Every record signed with **ML-DSA-65 (NIST FIPS-204)**, verified byte-for-byte against NIST's official test vectors
- A Certificate-Transparency-style **Merkle log** with per-customer trees, signed checkpoints, and inclusion proofs;
  only hashes are stored, never customer content
- Controls mapped from Google's HITRUST shared-responsibility matrix: least privilege, secrets only in Secret
  Manager. *Built and documented, not formally assessed.*
- gitleaks in pre-commit and CI (**0 leaks across 348 commits**), CodeQL, Dependabot, and a **public incident log**

---

### How I work

**Evidence over assertion.** Measure before and after. Every incident gets a write-up and a permanent fix. Secrets
never touch the repo, and the scanners prove it. Tests define the target before the code is written.

### About the handle

`aimozart` is my handle, the name I build and ship under. Work history and references are on the résumé.

### Open to

**Remote** backend roles in **Elixir and Erlang/OTP**: distributed systems, reliability, and anything where
security and uptime both matter (fintech, health, telecom). Full-time or contract.

**[→ Résumé + contact](https://entropa.space/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
