<div align="center">

### aimozart

**Mainframe developer**: COBOL · JCL · VSAM · DB2 · CICS on IBM Z · RPG on IBM i · 12 years of security & compliance

`AWS Solutions Architect – Associate` · `Databricks Spark Developer` · `IBM Z Xplore: in progress`

</div>

---

### 🦖 Why COBOL, and why now

I've loved this era of computing since the '80s: running dial-up BBSes, and pulling Dow Jones stock quotes over
Prodigy, a service that ran on IBM mainframes. COBOL has fascinated me the whole time; it's the language that
quietly moves the world's money.

Later, at **Cognizant**, I administered the **IBM i (AS/400)** systems that ran a 24/7 retail account's COBOL and
RPG business applications, and led remediation during mission-critical outages. I kept those systems running;
now I'm learning to write the code that runs on them.

With the generation that built these systems retiring, I finally have my chance to get into the field, and I'm
taking it: daily work on a **real z/OS system** (IBM Z Xplore) in COBOL, JCL, VSAM, DB2, and CICS, plus RPG on
IBM i.

---

### 🏦 Featured: Big Iron Bank

**[→ cobol-z](https://github.com/aimozart/cobol-z)**: a small but complete **core banking system in COBOL and JCL**,
on an emulated IBM System/370 (MVS 3.8j), with a modernization finale on real IBM Z (z/OS):

- **End-of-day batch cycle:** edit → post → interest → fees → **reconciliation** → statements
- **Production-grade:** restartable jobs that never double-post; bad data goes to a reject file, never an S0C7
- **Security layer:** RAKF/RACF dataset protection, separation of duties, audit trail, masked account numbers
- **Modernization:** the posting module moved to Enterprise COBOL + DB2, driven from the Zowe CLI

*In progress. Clone it, boot TK5, submit the job, and watch the bank run.*

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

That background is why I write code the way banks and auditors need it: controlled, documented, and restartable,
with PCI DSS and SOX in mind.

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

**Remote** roles as a **mainframe COBOL developer**, **IBM i developer**, or **mainframe / IBM i security**
engineer, especially in banking and financial services. Full-time or contract.

**[→ Résumé + contact](https://entropa.space/hire)**

---

<div align="center">
<sub>Judge the work. It's all here.</sub>
</div>
