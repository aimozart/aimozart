<div align="center">

### aimozart

**Database administrator: MongoDB Atlas** · Lotus Notes → MySQL → MongoDB · 12 years of security & compliance

`AWS Solutions Architect – Associate` · `Databricks Certified Associate Developer for Apache Spark` · `MongoDB Associate Atlas Administrator: in preparation`

</div>

---
### 🗄️ Databases, the whole way through

I've been running online systems since my BBS sysop days in the '80s, and administering databases in every job since.

| When | Where | Databases |
|---|---|---|
| **1980s** | As a teenager | BBS sysop; **HyperCard** (summer classes every year at Haverford), **FileMaker** and **4th Dimension** on the Mac, plus OS/2. Mostly D&D characters |
| **1990s** | | **Lotus Notes / Domino**: a document database, decades before "NoSQL" had a name |
| **Early 2000s** | My own business | **MySQL on Windows**, installed, backed up and run myself |
| **2012 – 2014** | Endurance International Group | **MySQL + phpMyAdmin** behind WordPress hosting for 120+ enterprise accounts: tuning, repairs, restores, hardening |
| **2014 – 2017** | ECS (now Datavant) | **MySQL** administration in a HIPAA environment I helped take to **HITRUST certification** |
| **2018 – 2019** | Cognizant (TJ Maxx / HomeGoods) | **Lotus Notes / Domino** and database administration; **IBM i** user administration; C-level escalation support for down stores across the enterprise |
| **2019 – 2022** | Ultra Clean Technologies | **MySQL** administration, alongside enterprise EDR and privileged access management |
| **Recent years** | Many projects | **MongoDB** and **Databricks** (Spark, Delta Lake) |

Now: taking that into **MongoDB Atlas** administration, with the Associate Atlas Administrator certification on the way.

---
### 🏦 Now building: Big Iron Bank on MongoDB

A fictional Arizona community bank, run the way a DBA runs production:

- **Data model** for customers, accounts and card transactions, with schema validation that rejects bad documents
- **Indexes proven with `explain()`**, and a slow query found with the profiler and fixed
- **Money moves in multi-document ACID transactions**, and the books reconcile to the cent
- **A replica set that survives a failover drill**, and a sharded transactions collection with a shard key I can defend
- **Backups actually restored**: `mongodump`, Atlas snapshots, point-in-time recovery
- **Security first:** least-privilege roles (tellers read, the batch job writes, auditors audit), network isolation,
  encryption at rest with AWS KMS, and SSNs protected with client-side field-level encryption

The repository goes public as each piece lands.

---
### 🔒 Security has always been the job

| Layer | What I've done |
|---|---|
| **Governance & compliance** | Co-authored a healthcare security-policy framework and drove the remediation to official **HITRUST certification** and continuous HIPAA compliance; CIS Benchmark hardening of a live Windows fleet; PHI chain of custody on encrypted drives |
| **Endpoint & identity** | Enterprise **EDR** across a global fleet, **privileged access management**, patch and baseline-configuration management |
| **Host & web** | Linux server hardening and WordPress security for 120+ enterprise accounts |
| **Security by design** | Entropa, below: cryptography, controls, supply chain and detection, built as code with the evidence public |

That's why I run databases the way regulated companies need them: least privilege, encrypted, audited, and recoverable.

---

### 🔐 Entropa: a post-quantum, tamper-evident audit trail

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- Every record signed with **ML-DSA-65 (NIST FIPS-204)**, verified byte-for-byte against NIST's official test vectors
- A Certificate-Transparency-style **Merkle log** with per-customer trees, signed checkpoints, and inclusion proofs
- gitleaks in pre-commit and CI (**0 leaks across 348 commits**), CodeQL, Dependabot, and a **public incident log**

---

### How I work

**Evidence over assertion.** Measure before and after. Every incident gets a write-up and a permanent fix. Backups
don't count until they've been restored. Irreversible actions wait for approval.

### About the handle

`aimozart` is my handle, the name I build and ship under. Work history and references are on the résumé.

### Open to

**Remote** roles in **MongoDB / Atlas database administration**, especially where security, compliance and uptime
all matter. Full-time or contract.

**[→ Résumé + contact](https://entropa.space/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
