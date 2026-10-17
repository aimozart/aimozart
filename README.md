<div align="center">

### Scott Baker · aimozart

**Security analyst · AWS security · threat hunting · incident response · SIEM and EDR · healthcare security (HIPAA)** · 12+ years in enterprise IT, security and compliance

`AWS Solutions Architect – Associate` · `Databricks Certified Associate Developer for Apache Spark` · `SCCM Administration certificate`

</div>

---
### ⚡ Start here: 10 things worth your time (each one is a click)

1. **[Paxel builder report and the public record behind it](https://github.com/aimozart/entropa-public/blob/rust-archive/PAXEL_CHAT_LOG.md)**: an independent analysis of my AI-orchestrated engineering. It credits production-proof discipline and steering AI at the architecture level, and the thread shows me challenging its findings with evidence until it agreed.
2. **[Auditing the auditor](https://github.com/aimozart/entropa-public/blob/rust-archive/ANALYSIS_NOTES.md)**: documented blind spots of automated review, each with a command anyone can run to check.
3. **[Official NIST FIPS-204 (ML-DSA) known-answer tests](https://github.com/aimozart/entropa-public/blob/rust-archive/crates/core/tests/nist_kat.rs)**: standard test vectors verified byte for byte.
4. **[A public incident log](https://github.com/aimozart/entropa-public/blob/rust-archive/OBSERVABILITY.md)**: every bug with its root cause next to the guardrail that now prevents it, including my own mistakes.
5. **[Verify it without trusting me](https://github.com/aimozart/entropa-public/blob/rust-archive/VERIFICATION.md)**: how to independently check a receipt, run against a live production receipt before it was written down.
6. **[Secret-scanning gate](https://github.com/aimozart/entropa-public/blob/rust-archive/scripts/security/secret-scan.sh)** with the written policy in **[SECURITY.md](https://github.com/aimozart/entropa-public/blob/rust-archive/SECURITY.md)**: gitleaks before any public push.
7. **[Automated pipelines](https://github.com/aimozart/entropa-public/tree/main/.github/workflows)**: CI, CodeQL, dependency review, Dependabot, and a CD workflow that deploys to GKE only after CI passes.
8. **[Trusted Publisher on crates.io](https://github.com/aimozart/entropa-public/blob/rust-archive/.github/workflows/publish.yml)**: my Rust crates (**[entropa-core](https://crates.io/crates/entropa-core)**, **[entropa-node](https://crates.io/crates/entropa-node)**) publish through GitHub OIDC, so there is no long-lived token anywhere. Secretless by design.
9. **Kubernetes, observability and identity as code**: a **[Helm chart with autoscaling](https://github.com/aimozart/entropa-public/tree/main/helm/entropa)** for the Java (Spring Boot) microservices on GKE, the **[Prometheus, Loki, Tempo and Grafana configuration](https://github.com/aimozart/entropa-public/tree/main/observability)**, and the **[Keycloak OAuth2/JWT realm](https://github.com/aimozart/entropa-public/tree/main/security/keycloak)**.
10. **Built on a $20-a-month AI plan, funded by a Google for Startups grant**: **[Entropa](https://entropa.space)** was built end to end by directing AI tools under rules I wrote (test first, forecast then prove): method over budget. Awarded a **Google for Startups Cloud Program grant ($2,000 in credits)**. On the Microsoft Agentic DevOps Engineer path: AZ-401 (beta) scheduled Nov 9, 2026 (result pending), GH-300 scheduled.

*Entropa is designed and directed by me and built with AI coding assistance under rules I wrote. The numbers and links above are checkable; that is the point.*

---
### What I do best: find and contain threats

My strongest work has been defensive security: running a **SIEM** (LogRhythm), triaging and containing threats with **CrowdStrike EDR** across a global fleet, building a vulnerability-scanning program from scratch (**OpenVAS**, Qualys), and analyzing network traffic with **Wireshark**. **Threat hunting is my favorite part of the job.** I taught myself most of it, and I come from healthcare, so I also know how a security finding becomes a reportable **HIPAA** breach.

---
### Now: hands-on threat hunting and cloud security

Studying and practicing, not yet claimed as professional experience: network threat hunting and forensics (Wireshark, Zeek, RITA, MITRE ATT&CK), AWS security (GuardDuty, CloudTrail, Security Hub), and building a hunt-and-report capstone for a fictional healthcare organization with a HIPAA breach-assessment layer. Results will be posted here only when they are measured.

---
### How I work

**Evidence over assertion.** I check my own claims and correct them in public. The record of that habit, including an over-claim I caught and fixed, is the [Paxel chat log](https://github.com/aimozart/entropa-public/blob/rust-archive/PAXEL_CHAT_LOG.md).

**Test first, deterministic by default.** Forecast the outcome, pin every input, confirm a test fails for the stated reason before writing the code, then prove the result against the forecast.

---
### 🔐 Entropa: a post-quantum, tamper-evident audit trail

Designed and directed by me, built with AI coding assistance under rules I wrote (test-first changes, secret scanning, human approval before irreversible actions).

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- Rust implementation: **229 passing automated tests, 0 failures** across the full workspace (run on 2026-10-17; the public archive branch runs 106 of them), official NIST FIPS-204 ACVP known-answer vectors verified byte for byte, JSON contract tests, lease lifecycle tests with a fake store and clock
- gitleaks in pre-commit and CI (**0 real leaks across the full history**), CodeQL, Dependabot, and a **public incident log** where every bug lists its root cause next to the guardrail that now prevents it
- Current system: Java (Spring Boot) microservices on Kubernetes (GKE) with Kafka; a database migration with a zero-loss cutover and a hash chain re-verified afterward (35 records, 0 broken)

---
### Background: 12+ years of enterprise systems, security and compliance

| Where | What |
|---|---|
| **CIOX Health (now Datavant)**, 2014 – 2017 | Helped take a HIPAA environment to official **HITRUST certification**: evidence for every control, **Qualys and OpenVAS** vulnerability scanning turned into remediation plans, endpoint data-loss-prevention monitoring; Windows administration (Active Directory, Group Policy, SCCM) |
| **Cognizant (TJ Maxx)**, 2018 – 2019 | Active Directory and Hyper-V for roughly 3,400 stores; Intune for the enterprise's mobile devices; the SOPs and remediation documentation that enforced procedure across Tier 1 and 2 |
| **Ultra Clean**, 2019 – 2022 | Baseline-configuration audits across a global fleet; Intune and SCCM, all functions; EDR and privileged access management; Windows 7 to 11 migration (team effort) |
| **Endurance International**, 2012 – 2014 | Level 3 Linux engineer for 120+ enterprise accounts; migration team across Bluehost, HostGator and others |

Full history: [Résumé](https://bigironbank.online/hire).

---
### Open to

**Remote or Phoenix** roles in **security operations, incident response and threat hunting**, especially in healthcare or other regulated industries where security and compliance matter. Full-time or contract. Phoenix, AZ.

**[→ Résumé + contact](https://bigironbank.online/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
