<div align="center">

### aimozart

**Backend / Systems Engineer** — Java 21, Spring Boot / Spring Cloud microservices, Kafka, Kubernetes, AI-agent infrastructure.

</div>

---

### Building Entropa

A **tamper-evident audit-trail platform for AI-agent decisions** — a real Java 21 / Spring Boot /
Spring Cloud microservices system: Eureka service discovery, a centralized Config Server, an
OAuth2/JWT-secured Spring Cloud Gateway, Kafka-driven event flow between an ingest service and a
single-writer transparency/hash-chain service, PostgreSQL persistence, Keycloak identity, and a
Stripe-integrated demo signup flow — containerized with Docker and deployed on Kubernetes (GKE)
via a templated Helm chart, behind a real SSL-terminated load balancer.

Zero real customers by design — this is a portfolio/demo project, not a live commercial product.
A visitor signs up with a real Stripe **test-mode** checkout ($0, no real charge) and gets into a
live dashboard showing real mock AI-agent decisions flowing through the actual pipeline, so the
architecture is visibly real without anyone handing over real payment info.

**[→ github.com/aimozart/entropa-public](https://github.com/aimozart/entropa-public)** · **[entropa.space](https://entropa.space)**

- 🍃 **Java 21 / Spring Boot 3 / Spring Cloud** — Eureka, Config Server, Gateway, Resilience4j circuit breakers
- 📨 **Event-driven architecture** — Apache Kafka connects ingest → transparency → notification services
- 🔐 **Real identity & security** — Keycloak (OAuth2/OIDC) machine-to-machine auth, JWT validated at the gateway
- ☁️ **Real cloud infrastructure** — Kubernetes (GKE), Helm, GCE HTTPS load balancers with Google-managed TLS, Cloud DNS, Secret Manager, IAM
- 🧾 **Tamper-evident hash chain** — every record persisted via JPA/Hibernate to PostgreSQL, independently verifiable
- ⚙️ Prior credential: designed and shipped Entropa's original **Rust** implementation (real ML-DSA/FIPS-204 post-quantum signatures, verified byte-exact against NIST's own ACVP test vectors) before migrating the system to its current Java/Spring architecture

### What I build

Systems that need to be *provably* correct, not just trusted — audit-trail infrastructure, event-driven
microservices, and the deterministic scaffolding that makes AI-driven decisions accountable. That means
the infrastructure underneath has to be as disciplined as the design on top of it: real service boundaries,
least-privilege access, and observability that catches problems before they're incidents.

### How I ship

Sprint-focused and iterative, not big-bang releases — get something real running, then harden it fast
based on what actually breaks. Entropa's build history is the evidence: real production incidents
(a Kafka authentication misconfiguration, a config-server packaging bug that left every service running
on empty configuration, JVM startup tuning under constrained CPU) found via actual logs, root-caused,
fixed, and redeployed the same session — see the
[real incidents log](https://github.com/aimozart/entropa-public/blob/main/README.md#real-incidents-found-and-fixed).
Ship, observe, fix fast, harden, repeat.

### Working pseudonymously

I build and ship under this handle by choice — it keeps the conversation on the work, not a résumé, and
protects negotiating position from being anchored to a prior title or company. Real name, work history, and
references are shared privately once a real conversation starts. Judge the code — it speaks for itself.

### Hire aimozart

Entropa was built solo, end to end, under this handle — real Java/Spring microservices, event-driven
architecture, Kubernetes deployment, real production incidents found and fixed live. If one person
directing AI at a senior bar can ship that alone, imagine what it does for your team.

Open to **salaried, full-time** Backend / Systems Engineering roles, or **per-project / contract** work.
For startups, equity is always part of the package **in addition to** full salary and benefits — never a
substitute for either.

**[→ Full résumé + contact](https://entropa.space/hire)**

---

<div align="center">
<sub>Open to interesting problems. Reach out via <a href="https://entropa.space/hire">entropa.space/hire</a>.</sub>
</div>
