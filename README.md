<div align="center">

### Scott Baker · aimozart

**Test automation engineer (SDET)** · TypeScript · Playwright · API testing · CI/CD · custom test frameworks · 12+ years in enterprise IT, security and compliance

`AWS Solutions Architect – Associate` · `Databricks Certified Associate Developer for Apache Spark` · `SCCM Administration certificate`

</div>

---
### Now: building a TypeScript + Playwright test framework

Quality first: test, then produce. I'm mastering **TypeScript and Playwright** full time and building a public capstone, the **Big Iron Bank quality platform**: a framework with a typed API client and schema validation, page objects, a separate test environment for every parallel worker, and GitHub Actions and Jenkins pipelines, scored against **15 seeded defects** in a bank application (the suite must pass on the clean build and catch every defect). In progress, and not yet claimed as professional experience; results will be posted here only when they are measured.

---
### How I work

**Test first, deterministic by default.** Forecast the outcome, pin every input, confirm a test fails for the stated reason before writing the code, then prove the result against the forecast. A fixed defect gets a regression test; a flaky test gets investigated, never rerun until it turns green.

**Evidence over assertion.** I check my own claims and correct them in public. The record of that habit, including an over-claim I caught and fixed, is the [Paxel chat log](https://github.com/aimozart/entropa-public/blob/rust-archive/PAXEL_CHAT_LOG.md).

---
### 🔐 Entropa: a post-quantum, tamper-evident audit trail

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- Rust implementation: **207 passing automated tests** (documented 2026-08-23), official NIST FIPS-204 ACVP known-answer vectors verified byte for byte, JSON contract tests, lease lifecycle tests with a fake store and clock
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

**Remote** roles in **QA automation / SDET** (TypeScript, Playwright, API testing, CI/CD), especially where quality, security and compliance matter. Full-time or contract. Phoenix, AZ.

**[→ Résumé + contact](https://bigironbank.online/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
