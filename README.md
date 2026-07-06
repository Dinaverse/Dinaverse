# 🌐 Welcome to the Dinaverse

> *Architecting sovereign, high-performance local infrastructure through hardware revalorisation and hardened systems engineering.*

I approach technology with a research-and-development mindset. I leverage open-source documentation, technical whitepapers, and hands-on lab environments to master complex systems from scratch.

---

## 🚀 Core Technical Focus

* ⚡ **Sovereign AI Infrastructure:** Designing distributed, bare-metal compute clusters optimized for local inference (4×GPU clustering, multi-node orchestration, zero cloud dependencies).
* 🐧 **Hardened Linux Systems:** High-level administration of Arch Linux, Kali Linux, Debian, and Ubuntu environments with Docker containerization and distributed systems architecture.
* 🛡️ **Security Automation:** Autonomous agents for log monitoring, network reconnaissance, threat detection, and AI-driven security operations (NVIDIA Morpheus integration).
* ⚙️ **Infrastructure-as-Code:** Declarative deployments, configuration management, reproducible node recovery, and resilient system design.
* 🏗️ **Hardware Revalorisation:** Repairing, optimizing, and orchestrating recycled enterprise-grade hardware for high-performance local workloads.

---

## 🏗️ Flagship Projects

### Infrastructure & AI

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[sovereign-ai-infrastructure](https://github.com/Dinaverse/sovereign-ai-infrastructure)** | Centralized architecture documentation for distributed 5-node lab with multi-node topology, orchestr[...] | Multi-node topology, Orchestrati[...] | ✅ Active |
| **[local-ai-sovereign-stack](https://github.com/Dinaverse/local-ai-sovereign-stack)** | Docker-based AI stack with Ollama LLM runtime, GPU acceleration, and comprehensive monitoring dashboards |[...] | Docker Compose, CUDA, Monitoring | ✅ Active |
| **[arch-linux-multi-gpu-llm](https://github.com/Dinaverse/arch-linux-multi-gpu-llm)** | GPU cluster optimization guide for 4×NVIDIA P106-100 inference running Qwen 3.5:27B with CUDA multi-GPU s[...] | Arch Linux, CUDA, systemd, Ollama | ✅ Active[...] |
| **[infrastructure-as-code-lab](https://github.com/Dinaverse/infrastructure-as-code-lab)** | Terraform & Ansible frameworks for reproducible deployments across all infrastructure nodes | Terrafor[...] | Terraform, Ansible, IaC | 🔄 In Dev |

### Security & Automation

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[cybersecurity-lab-automation](https://github.com/Dinaverse/cybersecurity-lab-automation)** | Autonomous agents for continuous log monitoring, hourly network reconnaissance, and threat detecti[...] | Python, MCP Bridge, Morpheus | ✅[...] |
| **[sovereign-ai-security](https://github.com/Dinaverse/sovereign-ai-security)** | NVIDIA Morpheus + Triton integration for AI-driven security operations with real-time threat scoring and inciden[...] | Morpheus, Triton, Python | ✅ Active |
| **[sovereign-ai-skills](https://github.com/Dinaverse/sovereign-ai-skills)** | Custom AI skills and Gemini CLI integration enabling autonomous agent orchestration for security and infrastructure [...]  | Gemini CLI, Python, Ollama | ✅ Active |
| **[n8n-automation-hub](https://github.com/Dinaverse/n8n-automation-hub)** | 8+ workflow definitions for lab orchestration, security automation, infrastructure management, and autonomous incident[...] | n8n, Workflows | ✅ Active |
| **[ai-workflow-automation](https://github.com/Dinaverse/ai-workflow-automation)** | Gemini CLI tools for automated repository management, documentation generation, and Git orchestration across e[...] | Gemini CLI, Node.js, Git | ✅ Active |
| **[python-security-analytics](https://github.com/Dinaverse/python-security-analytics)** | 40+ Python scripts for log analysis, network reconnaissance, access control auditing, and threat detecti[...] | Python, NumPy | ✅ Active |

### Homelab & Networking

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[proxmox-homelab-setup](https://github.com/Dinaverse/proxmox-homelab-setup)** | Proxmox hypervisor deployment on Dell T1700 with LXC containers, Docker, and Tailscale remote access | Proxmox V[...] | ✅ Stable |
| **[network-labs-documentation](https://github.com/Dinaverse/network-labs-documentation)** | Cisco Packet Tracer labs: routing protocols (OSPF, BGP), VLANs, ACLs, security configurations, and CTF writeups |[...] | ✅ Active |

---

## ⚙️ Core Technology Stack

```text
🐧 Operating Systems  ::  Arch Linux, Kali Linux, Debian, Ubuntu Server, Raspbian
🐳 Containerization   ::  Docker, Docker Compose, Proxmox VE, LXC
🤖 AI Runtime         ::  Ollama, CUDA, Multi-GPU VRAM pooling, Qwen 3.5:27B
📊 Monitoring         ::  Prometheus, Grafana, custom Python agents, ELK stack
🛡️ Security           ::  Suricata IDS, NVIDIA Morpheus, MCP Bridge, custom log analytics
🌐 Networking         ::  VLAN segmentation, Tailscale, custom DNS, SSH hardening
⚙️ Orchestration      ::  n8n workflows, Gemini CLI, systemd, Bash/Python automation
🔧 IaC               ::  Terraform, Ansible (in development)
```

---

## 🏛️ Lab Architecture

### Node Topology

```
[Internet]
     │
[Dell Gateway / Monitoring Node]
     │
[Internal LAN (192.168.x.0/24)]
     ├── [Kali Master Orchestrator & SecOps Hub]
     ├── [Arch GPU Compute Cluster]  ← 4× NVIDIA P106-100 / 24 GB VRAM
     ├── [Raspberry Pi IDS / DNS / Network Services]
     └── [AMD Canwork189 Storage & CPU Worker]
```

### Hardware

- **Arch-GPU:** Arch Linux, 4× NVIDIA P106-100 (24 GB VRAM), local LLM inference, Ollama runtime
- **Kali-Master:** Kali Linux, master orchestration, security ops hub, MCP bridge, autonomous agents
- **Raspberry-Pi:** Raspbian, IDS (Suricata), DNS services, network monitoring, threat detection
- **Dell-Gateway:** Debian, internet gateway, Prometheus/Grafana monitoring, uptime sentinel
- **AMD-Storage:** Ubuntu Server, distributed storage, CPU-bound analytics, backup services

### Services

| Service | Host | Role | Port | Technology |
|---------|------|------|------|-----------|
| **Ollama** | Arch-GPU | LLM inference runtime | 11434 | Ollama + CUDA |
| **Grafana** | Dell-Gateway | Monitoring dashboards | 3000 | Grafana + Prometheus |
| **Prometheus** | Dell-Gateway | Metrics collection | 9090 | Prometheus time-series DB |
| **n8n** | Docker host | Workflow automation | 5678 | n8n workflow engine |
| **Suricata IDS** | Raspberry-Pi | Network intrusion detection | - | Suricata + Eve JSON |
| **Morpheus** | Kali-Master | AI-driven threat detection | - | NVIDIA Morpheus + Triton |
| **MCP Bridge** | Kali-Master | AI agent integration | - | Model Context Protocol |

---

## 📚 Documentation Guide

### Quick Navigation

| Goal | Repository | File |
|------|-----------|------|
| **Understand architecture** | `sovereign-ai-infrastructure` | `README.md` |
| **Deploy Docker services** | `local-ai-sovereign-stack` | `README.md` |
| **GPU optimization** | `arch-linux-multi-gpu-llm` | Repository docs |
| **Security automation** | `cybersecurity-lab-automation` | `README.md` |
| **Security analytics scripts** | `python-security-analytics` | `README.md` |
| **Networking: OSPF, ACLs, VLANs** | `network-labs-documentation` | `README.md` |
| **Proxmox setup** | `proxmox-homelab-setup` | `README.md` |
| **Workflow automation** | `n8n-automation-hub` | Repository docs |
| **IaC frameworks** | `infrastructure-as-code-lab` | `README.md` |
| **Repository orchestration** | `ai-workflow-automation` | `README.md` |

### Repository Dependencies

```
sovereign-ai-infrastructure (core docs)
     ├── local-ai-sovereign-stack (Docker AI stack)
     ├── arch-linux-multi-gpu-llm (GPU optimization)
     ├── cybersecurity-lab-automation (Security agents)
     ├── python-security-analytics (Analytics scripts)
     ├── sovereign-ai-security (Morpheus integration)
     ├── sovereign-ai-skills (AI skills)
     ├── n8n-automation-hub (Workflows)
     ├── ai-workflow-automation (Repo management)
     ├── infrastructure-as-code-lab (IaC)
     ├── proxmox-homelab-setup (Hypervisor)
     └── network-labs-documentation (Networking labs & certifications)
```

---

## ✅ Operational Status

| Component | Status | Last Updated |
|-----------|--------|---|
| Multi-GPU LLM Inference (Qwen 3.5:27B) | ✅ Stable | 2026-07-05 |
| Ollama Distributed Inference | ✅ Active | 2026-07-05 |
| Grafana / Prometheus Monitoring | ✅ Active | 2026-07-05 |
| Suricata IDS | ✅ Active | 2026-07-05 |
| Security Agents (Log Monitoring, Recon) | ✅ Active | 2026-07-05 |
| MCP Bridge (Kali) | ✅ Active | 2026-07-05 |
| n8n Workflows | ✅ Active | 2026-07-05 |
| Proxmox Hypervisor | ✅ Stable | 2026-07-05 |
| Docker Services | ✅ Operational | 2026-07-05 |
| AI Workflow Automation | ✅ Active | 2026-07-05 |
| Cisco Networking Labs (OSPF, ACL, VLAN) | ✅ Active | 2026-07-05 |

---

## 🔗 Complete Repository Map

### Infrastructure & Architecture
- **[sovereign-ai-infrastructure](https://github.com/Dinaverse/sovereign-ai-infrastructure)** — Central documentation hub with topology, hardware specs, and architecture
- **[infrastructure-as-code-lab](https://github.com/Dinaverse/infrastructure-as-code-lab)** — IaC deployment frameworks (Terraform, Ansible)
- **[proxmox-homelab-setup](https://github.com/Dinaverse/proxmox-homelab-setup)** — Hypervisor & LXC container setup

### AI & Compute
- **[local-ai-sovereign-stack](https://github.com/Dinaverse/local-ai-sovereign-stack)** — Docker AI stack (Ollama, Prometheus, Grafana, n8n)
- **[arch-linux-multi-gpu-llm](https://github.com/Dinaverse/arch-linux-multi-gpu-llm)** — GPU cluster optimization and CUDA tuning

### Security & Automation
- **[cybersecurity-lab-automation](https://github.com/Dinaverse/cybersecurity-lab-automation)** — Security agents, MCP Bridge, autonomous monitoring
- **[python-security-analytics](https://github.com/Dinaverse/python-security-analytics)** — 40+ security analysis scripts
- **[sovereign-ai-security](https://github.com/Dinaverse/sovereign-ai-security)** — NVIDIA Morpheus AI SecOps integration
- **[sovereign-ai-skills](https://github.com/Dinaverse/sovereign-ai-skills)** — Custom AI skills and Gemini CLI integration
- **[n8n-automation-hub](https://github.com/Dinaverse/n8n-automation-hub)** — Workflow automation and orchestration
- **[ai-workflow-automation](https://github.com/Dinaverse/ai-workflow-automation)** — Repository management and documentation automation

### Networking & Labs
- **[network-labs-documentation](https://github.com/Dinaverse/network-labs-documentation)** — Cisco Packet Tracer labs (OSPF, ACLs, VLANs, routing) and CTF challenges

---

## 📖 Current Studies & Validation

* **Academic:** Refining infrastructure methodologies through formal Network Infrastructure & Cybersecurity studies at *Collège de Bois-de-Boulogne*.
* **Certifications:** Pursuing enterprise networking validation (Cisco CCST & CCNA) with hands-on labs in OSPF configuration, advanced ACL filtering, and multi-area routing design.
* **Hands-On Research:** Continuous lab experimentation in distributed systems, security automation, and AI inference optimization.

---

## 🎯 Philosophy

> *Sovereignty through ownership. Resilience through design. Knowledge through practice.*

Every component runs locally. Every decision is documented. Every failure is a learning opportunity. The lab is not just infrastructure—it's a **living system for understanding distributed systems, security operations, and network engineering**.

This is not a theoretical exercise. These repositories contain:
- **Real hardware** optimized through hands-on troubleshooting
- **Real workflows** that automate actual security and infrastructure operations
- **Real performance data** from 24 GB GPU clusters running production LLMs
- **Real security tools** defending actual infrastructure
- **Real networking labs** with hands-on OSPF, ACL, and routing protocol configurations

The goal is not to rent cloud services. It's to architect, deploy, and maintain a **complete computing environment** that is:
- **Sovereign** — No dependency on external providers
- **Resilient** — Built on redundancy and automation
- **Performant** — Optimized for inference and analytics at scale
- **Observable** — Every component monitored and logged
- **Documented** — Every decision recorded for future reference

---

## 🤝 Contributing & Collaboration

This ecosystem is continuously evolving. If you're interested in:
- Multi-GPU LLM optimization
- Security automation at scale
- Infrastructure-as-Code best practices
- Autonomous AI agents for operations
- Hardware revalorization techniques
- Cisco networking certifications (CCST, CCNA)

Feel free to explore, reference, and adapt these approaches for your own infrastructure.

---

## 📝 License & Attribution

All repositories are openly documented to support the community and advance shared knowledge in:
- Distributed computing
- Security operations automation
- Sustainable hardware practices
- Local AI inference
- Enterprise networking and routing protocols

---

*Built with research-and-development mindset. Powered by repurposed hardware. Governed by open standards. Owned entirely.*
