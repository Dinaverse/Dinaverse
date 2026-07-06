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

## 📸 LIVE OPERATIONAL PROOF

### **🖼️ [VIEW SCREENSHOT GALLERY](IMAGE-GALLERY.md)** ← CLICK HERE

**All 8 systems running right now with proof:**
- ✅ **Proxmox VE** — 5 containers operational
- ✅ **OPNsense Gateway** — 6.5h uptime
- ✅ **Syncthing** — 3-node sync confirmed
- ✅ **Gitea** — 14 automated tasks
- ✅ **Prometheus** — 7h+ uptime, zero corruption
- ✅ **Pi-hole DNS** — 162,812 blocklists
- ✅ **Arch GPU Cluster** — 24 GB VRAM, LLM inference
- ✅ **Raspberry Pi** — Multi-service hub

**[→ FULL SCREENSHOT GALLERY WITH CLICKABLE LINKS](IMAGE-GALLERY.md)**  
**[→ DETAILED OPERATIONAL ANALYSIS](OPERATIONAL-EVIDENCE.md)**

---

## 🏗️ Flagship Projects

### Infrastructure & AI

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[sovereign-ai-infrastructure](https://github.com/Dinaverse/sovereign-ai-infrastructure)** | Centralized architecture documentation for distributed 5-node lab with multi-node topology, orchestr[...] | Multi-node, Orchestration | ✅ Active |
| **[local-ai-sovereign-stack](https://github.com/Dinaverse/local-ai-sovereign-stack)** | Docker-based AI stack with Ollama LLM runtime, GPU acceleration, and comprehensive monitoring dashboards |[...] | Docker, CUDA, Monitoring | ✅ Active |
| **[arch-linux-multi-gpu-llm](https://github.com/Dinaverse/arch-linux-multi-gpu-llm)** | GPU cluster optimization guide for 4×NVIDIA P106-100 inference running Qwen 3.5:27B with CUDA multi-GPU s[...] | Arch Linux, CUDA | ✅ Active |
| **[infrastructure-as-code-lab](https://github.com/Dinaverse/infrastructure-as-code-lab)** | Terraform & Ansible frameworks for reproducible deployments across all infrastructure nodes | IaC, Automation | 🔄 In Dev |

### Security & Automation

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[cybersecurity-lab-automation](https://github.com/Dinaverse/cybersecurity-lab-automation)** | Autonomous agents for continuous log monitoring, hourly network reconnaissance, and threat detecti[...] | Python, MCP, Morpheus | ✅ Active |
| **[sovereign-ai-security](https://github.com/Dinaverse/sovereign-ai-security)** | NVIDIA Morpheus + Triton integration for AI-driven security operations with real-time threat scoring and inciden[...] | Morpheus, Triton | ✅ Active |
| **[sovereign-ai-skills](https://github.com/Dinaverse/sovereign-ai-skills)** | Custom AI skills and Gemini CLI integration enabling autonomous agent orchestration for security and infrastructure [...]  | Gemini CLI, Python | ✅ Active |
| **[n8n-automation-hub](https://github.com/Dinaverse/n8n-automation-hub)** | 8+ workflow definitions for lab orchestration, security automation, infrastructure management, and autonomous incident[...] | n8n, Workflows | ✅ Active |
| **[ai-workflow-automation](https://github.com/Dinaverse/ai-workflow-automation)** | Gemini CLI tools for automated repository management, documentation generation, and Git orchestration across e[...] | Gemini CLI, Git | ✅ Active |
| **[python-security-analytics](https://github.com/Dinaverse/python-security-analytics)** | 40+ Python scripts for log analysis, network reconnaissance, access control auditing, and threat detecti[...] | Python, NumPy | ✅ Active |

### Homelab & Networking

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[proxmox-homelab-setup](https://github.com/Dinaverse/proxmox-homelab-setup)** | Proxmox hypervisor deployment on Dell T1700 with LXC containers, Docker, and Tailscale remote access | Proxmox, LXC | ✅ Stable |
| **[network-labs-documentation](https://github.com/Dinaverse/network-labs-documentation)** | Cisco Packet Tracer labs: routing protocols (OSPF, BGP), VLANs, ACLs, security configurations, and CTF[...] | Cisco, Networking | ✅ Active |

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

| Goal | Resource | Link |
|------|----------|------|
| **See running systems** | Screenshot Gallery | [IMAGE-GALLERY.md](IMAGE-GALLERY.md) |
| **Full operational details** | Detailed Evidence | [OPERATIONAL-EVIDENCE.md](OPERATIONAL-EVIDENCE.md) |
| **Understand architecture** | Core Docs | `sovereign-ai-infrastructure` README |
| **Deploy Docker services** | AI Stack | `local-ai-sovereign-stack` README |
| **GPU optimization** | CUDA Tuning | `arch-linux-multi-gpu-llm` docs |
| **Security automation** | SecOps | `cybersecurity-lab-automation` README |
| **Security scripts** | Analytics | `python-security-analytics` README |
| **Networking labs** | OSPF/ACL | `network-labs-documentation` README |
| **Proxmox setup** | Hypervisor | `proxmox-homelab-setup` README |
| **IaC frameworks** | Automation | `infrastructure-as-code-lab` README |

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
| **Prometheus Metrics** | ✅ **7h+ Uptime** | **2026-07-06 00:32 UTC** |
| **OPNsense Gateway** | ✅ **6.5h Uptime** | **2026-07-06 00:32 UTC** |
| **Syncthing 3-node Sync** | ✅ **Live** | **2026-07-06 00:32 UTC** |
| **Gitea Automation** | ✅ **14 Tasks** | **2026-07-06 00:32 UTC** |
| **Pi-hole DNS** | ✅ **Active** | **2026-07-06 00:32 UTC** |

---

## 📊 Proof of Operations

### ➡️ [🖼️ VIEW SCREENSHOT GALLERY](IMAGE-GALLERY.md)

**8 operational screenshots with clickable full-size links:**

1. **Proxmox VE Dashboard** - [View](IMAGE-GALLERY.md#-screenshot-1-proxmox-ve-dashboard)
2. **OPNsense Firewall** - [View](IMAGE-GALLERY.md#-screenshot-2-opnsense-firewall-gateway)
3. **Syncthing Sync** - [View](IMAGE-GALLERY.md#-screenshot-3-syncthing-multi-node-sync)
4. **Gitea Automation** - [View](IMAGE-GALLERY.md#-screenshot-4-gitea-repository-automation)
5. **Prometheus Metrics** - [View](IMAGE-GALLERY.md#-screenshot-5-prometheus-metrics-collection)
6. **Pi-hole DNS** - [View](IMAGE-GALLERY.md#-screenshot-6-pi-hole-dns--ad-blocking)
7. **Arch GPU Cluster** - [View](IMAGE-GALLERY.md#-screenshot-7-arch-linux-gpu-compute-cluster)
8. **Raspberry Pi Hub** - [View](IMAGE-GALLERY.md#-screenshot-8-raspberry-pi-infrastructure-hub)

**[→ FULL OPERATIONAL ANALYSIS](OPERATIONAL-EVIDENCE.md)**

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

*Built with research-and-development mindset. Powered by repurposed hardware. Governed by open standards. Owned entirely. Proven in operation.*
