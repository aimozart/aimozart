<div align="center">

### Scott Baker · aimozart

**Systems administration** · Windows Server · Active Directory · Group Policy · SCCM · Hyper-V · Linux · 12 years of security & compliance

`AWS Solutions Architect – Associate` · `Databricks Certified Associate Developer for Apache Spark` · `SCCM Administration certificate`

</div>

---
### Migrations experience

At Endurance International Group, migrations never stopped across its hosting brands (Bluehost, HostGator, iPower and others): databases, WordPress sites, domains, DNS and Linux hosts. I was on the migration team every time, including moving acquired domains into larger platforms, and I led the WordPress and hosting-account migrations. Big Iron West, below, is that same discipline rehearsed on purpose: predictions written before every run, validation before cutover, a rollback path, and a cost ceiling set in advance.

On the Windows side, I've done more version-to-version migrations than I can count: **Windows XP → 7 → 10 at ECS** and **Windows 7 → 11 across a global fleet at Ultra Clean**, with SCCM imaging. Also at ECS: a legacy **Windows NT domain (about 300 users) and individual NT servers moved to Windows Server 2012 R2**, policies and user accounts included.

---
### 🖥️ Windows and Linux administration, the whole way through

I've been running online systems since my BBS sysop days in the '80s, and administering servers in every job since.

| When | Where | What I administered |
|---|---|---|
| **2012 – 2014** | Endurance International Group | **Linux hosting** (Ubuntu/RHEL, cPanel/WHM, Plesk) and Windows duties, for 120+ enterprise accounts: tuning, repairs, restores, hardening; the **migration team** for platform migrations across Bluehost, HostGator, iPower and others |
| **2014 – 2017** | ECS / CIOX Health (now Datavant) | Heavy **Windows administration: Active Directory, Group Policy, SCCM across all its functions** (imaging, policy, node setups, PXE servers), in a HIPAA environment I helped take to **HITRUST certification**; MySQL administration |
| **2018 – 2019** | Cognizant (TJ Maxx / HomeGoods) | **Active Directory** and **Windows virtualization (Hyper-V)** for the stores; **Lotus Notes / Domino**; **IBM i** user administration; C-level escalation support for down stores |
| **2019 – 2022** | Ultra Clean Technologies | Windows-heavy: **SCCM, all functions** (node and PXE server setups, imaging, policy, patching, baselines), **Active Directory, Group Policy**, run heavily on **RBAC, group administration and global policy**; enterprise **EDR** and **privileged access management**; MySQL |

Earlier: **Lotus Notes / Domino** in the 1990s, and my own business running **MySQL on Windows** in the early 2000s. Databases came along the whole way: MySQL, PostgreSQL, Databricks.

---
### 🧪 Now: an IT admin lab, built from scratch

Refreshing Windows Server and Linux administration hands-on: a nine-machine lab on **QEMU/KVM** (Windows Server 2022, Windows 11, AlmaLinux, Ubuntu) for Active Directory, Group Policy, PKI, storage and failover clustering. In progress, and written up as I go.

---
### 🔒 Security has always been the job

| Layer | What I've done |
|---|---|
| **Governance & compliance** | Co-authored a healthcare security-policy framework and drove the remediation to official **HITRUST certification** and continuous HIPAA compliance; CIS Benchmark hardening of a live Windows fleet; PHI chain of custody on encrypted drives |
| **Endpoint & identity** | Enterprise **EDR** across a global fleet, **privileged access management**, patch and baseline-configuration management |
| **Host & web** | Linux server hardening and WordPress security for 120+ enterprise accounts |
| **Security by design** | Entropa, below: cryptography, controls, supply chain and detection, built as code with the evidence public |

That's why I run systems the way regulated companies need them: least privilege, encrypted, audited, and recoverable.

---

### 🔐 Entropa: a post-quantum, tamper-evident audit trail

**[→ entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- Every record signed with **ML-DSA-65 (NIST FIPS-204)**, verified byte-for-byte against NIST's official test vectors
- A Certificate-Transparency-style **Merkle log** with per-customer trees, signed checkpoints, and inclusion proofs
- **Database migration (Sep 28, 2026):** the Java (Spring Boot) service's audit log moved off Postgres to a new managed database, provisioned
  with Pulumi, switched test-first, a zero-loss cutover through Kafka, and the hash chain
  re-verified on the new database (35 records, 0 broken)
- gitleaks in pre-commit and CI (**0 leaks across 348 commits**), CodeQL, Dependabot, and a **public incident log**

---

### 💰 FinOps, since my first AWS build

Nearly 10 years of FinOps, starting with an electronic medical records (EMR) system I designed and built on AWS as an
independent side project. I forecast cloud spend before building, choose for price-performance against the business
goal, and reconcile the bill afterward: budgets and alerts tied to the forecast, cost per GB and per job, and a
forecast-vs-actual review after every teardown. In every role I've also picked hardware and software licensing and gone to vendors for the best deal.

---

### How I work

**Deterministic by default.** Forecast the outcome and the cost first, pin every input, then prove the result against
the forecast. It saves labor and money and keeps projects on time and on budget.

**Evidence over assertion.** Measure before and after. Every incident gets a write-up and a permanent fix. Backups
don't count until they've been restored. Irreversible actions wait for approval.

### About me

I'm **Scott Baker**, in Phoenix, Arizona. `aimozart` is the handle I build and ship under. Résumé, work history and references: [bigironbank.online/hire](https://bigironbank.online/hire) · [entropa.space/hire](https://entropa.space/hire).

### Open to

**Remote** roles in **systems administration** (Windows Server, Active Directory, Group Policy, SCCM, Linux), especially where security, compliance and uptime all matter. Full-time or contract.

**[→ Résumé + contact](https://bigironbank.online/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
