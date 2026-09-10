<div align="center">
<img src="https://raw.githubusercontent.com/aimozart/entropa-public/main/crates/api/scryon/assets/favicon-512.png" width="96" />

### aimozart

**Cloud Infrastructure / DevOps Professional** — AWS, Terraform, Pulumi, Rust, post-quantum crypto.

</div>

---

### Building Entropa

A **post-quantum trust layer for AI agents** — not a currency. No mining, no token, no hype.

A single-writer transparency log, cryptographically signed and independently verifiable —
not decentralized consensus, deliberately. An earlier version ran real multi-validator
quorum consensus in production; it was removed once it became clear it solved a
multi-party-trust problem this single-operator project doesn't actually have.
*Entropa is boring. All we do is keep your AI agents auditable.*

**[→ github.com/aimozart/entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

[![crates.io: entropa-core](https://img.shields.io/crates/v/entropa-core.svg?label=entropa-core)](https://crates.io/crates/entropa-core)
[![crates.io: entropa-node](https://img.shields.io/crates/v/entropa-node.svg?label=entropa-node)](https://crates.io/crates/entropa-node)
[![Trusted Publishing](https://img.shields.io/badge/crates.io-Trusted%20Publisher%20(OIDC)-3ddc84)](https://github.com/aimozart/entropa-public/actions/workflows/publish.yml)

- 🔐 **ML-DSA (NIST FIPS-204)** signatures — verified byte-exact against NIST's own known-answer test vectors
- 📜 **Signed transparency log** — checkpoints signed with ML-DSA, independently verifiable via real inclusion-proof and signature checks, no multi-party consensus required for a single-operator system
- 🦀 **100% Rust** — cryptography, sequencer, and gateway, one language throughout
- ☁️ **Real cloud infrastructure** — GCP IAM, Firebase Hosting, Cloud DNS, least-privilege service accounts, Gitea-hosted CI/CD with automated secret-scanning gates before merge, all managed as code
- 🤖 AI **Probes** reason about what to record; the ledger makes the result replayable and non-repudiable

### What I build

Systems that need to be *provably* trustworthy, not just trusted — post-quantum cryptography, multi-agent
architectures, and the deterministic scaffolding that makes probabilistic AI produce auditable results. That
means the infrastructure underneath has to be just as disciplined as the cryptography on top of it:
infrastructure-as-code, least-privilege access boundaries between services, and observability that catches
problems before they're incidents.

### How I ship

Sprint-focused and iterative, not big-bang releases — get something real out, then tighten it fast based on
what actually breaks. Entropa's build history is the evidence: three separate live bugs found, root-caused,
fixed, tested, and redeployed **the same day** they surfaced, each one immediately followed by a regression
test and a permanent guardrail (see the [failure-modes table](https://github.com/aimozart/entropa-public/blob/main/OBSERVABILITY.md)).
Ship, observe, fix fast, harden, repeat.

### Currently building

Active, ongoing infrastructure-as-code practice — real AWS, real verification, torn down after every session:

- **[pulumi_mastery](https://github.com/aimozart/pulumi_mastery)** — drill-and-verification platform (Django + React) covering AWS/Pulumi IaC, Terraform-via-Pulumi interop (`pulumi_hcl`), and raw AWS CLI proficiency. Every drill is graded against real infrastructure state, not source code.
- **[terraform_pulumi](https://github.com/aimozart/terraform_pulumi)** — Terraform-specific demos: remote state with locking, reusable module patterns across environments.

### Working pseudonymously

I build and ship under this handle by choice — it keeps the conversation on the work, not a resume, and
protects negotiating position from being anchored to a prior title or company. Real name, work history, and
references are shared privately once a real conversation starts. Judge the code — it speaks for itself.

### Hire aimozart

Entropa was built solo, end to end, under this handle — real post-quantum cryptography, a live signed
transparency log, a production AI agent, real cloud infrastructure, CI/CD, monitoring, hardening. If one
person directing AI at a senior bar can ship that alone, imagine what it does for your team.

Open to **salaried, full-time** Cloud Infrastructure / DevOps / SRE roles, or **per-project / contract**
work. For startups, equity is always part of the package **in addition to** full salary and benefits — never
a substitute for either.

**[→ Full pitch + contact form](https://entropa.space/hire#contact)**

---

<div align="center">
<sub>Open to interesting problems. Reach out via <a href="https://entropa.space/hire#contact">entropa.space/hire</a>.</sub>
</div>
