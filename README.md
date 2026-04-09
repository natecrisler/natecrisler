# Nate Crisler — Principal Architect

**I build the infrastructure that makes AI possible — and the security that keeps it safe.**

15+ years engineering production systems at scale. Started at the network layer (ISP infrastructure, BGP, physical layer) and worked up through enterprise telemetry, cloud security, and platform engineering to where the interesting problems are now: self-hosted AI infrastructure with real security controls.

---

### What I build

**HashiStack** — Vault for secrets management, Consul for service mesh, Nomad for workload orchestration, Terraform for everything. Not just using these tools — running them in production on my own hardware, building the automation layer on top of them.

**AI Infrastructure** — Self-hosted LLM inference with Ollama. RAG pipeline architecture (ChromaDB, embedding models). MCP (Model Context Protocol) server development. Production AI systems with confidence-tiered response engines. Local deployments for security-sensitive environments with full data sovereignty.

**Security Engineering** — eBPF/Tetragon for kernel-level process attribution. OPA/Rego for policy-as-code enforcement. Passive AI traffic governance (shadow AI detection, PII-in-prompt, token exfiltration signals). SplunkCloud deployments with automated compliance controls (PCI-DSS, HIPAA, SOX, SOC2).

**Custom Tooling in Go** — Author of a custom Terraform provider for the Antsle hypervisor platform. 9 writable resource types, 15+ read-only data sources, full CRUD lifecycle. Most engineers use providers. I wrote one.

---

### Projects

| Project | What it is |
|---------|-----------|
| **INTERCEPT** | Passive network sensor — transparent proxy, 24-rule security scanner, eBPF/Tetragon process attribution, OPA/Rego behavioral enforcement. Self-hosted AI governance. |
| **SOVEREIGN** | Self-hosted HashiStack control plane on Antsle bare metal. Packer → hardened AlmaLinux 9 images → custom Terraform provider → Vault + Consul + Nomad + Traefik. git push to production. |
| **FULCRUM** | 15-agent multi-agent orchestration architecture. Cognitive profile-aware agent design. Claude API at depth. |
| **SPECTER** | RAG system automating enterprise security questionnaires. Flask + ChromaDB + Ollama. 85%+ automatic completion rate. |
| **Custom Terraform Provider** | Full provider in Go using Terraform Plugin SDK. Available on request. |

---

### Speaking

- **Splunk .conf 2017** — *"What Got You Here Won't Get You There — The Journey to Enterprise Cloud from a Customer's Perspective"* · Washington D.C.
- **Nutanix .NEXT 2018** — *"Splunk Enterprise on Nutanix: Keys to Success"* · New Orleans · 92.2% attendee approval rating
- **Nutanix + Splunk Global Webinar 2017** — *"Become a Big Data Superhero with Splunk and Nutanix"*
- **Nutanix Technology Champion** — 2018, 2019, 2020

---

### Currently

Principal Solutions Architect at C1. Open to the right opportunity at the Principal/Staff Architect level — AI infrastructure, platform engineering, DevSecOps.

📍 Remote · 📧 nate@nu11.info · 🌐 [imsre.dev](https://imsre.dev)
