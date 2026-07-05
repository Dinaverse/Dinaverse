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
| **[sovereign-ai-infrastructure](https://github.com/Dinaverse/sovereign-ai-infrastructure)** | Centralized architecture documentation for distributed 5-node lab | Multi-node topology, Orchestration, Security | ✅ Stable |
| **[local-ai-sovereign-stack](https://github.com/Dinaverse/local-ai-sovereign-stack)** | Docker-based AI stack: Ollama, Grafana, Prometheus, n8n | Docker Compose, CUDA, Monitoring | ✅ Active |
| **[arch-linux-multi-gpu-llm](https://github.com/Dinaverse/arch-linux-multi-gpu-llm)** | GPU cluster optimization for 4×NVIDIA P106-100 inference | Arch Linux, CUDA, systemd, Ollama | ✅ Active |
| **[infrastructure-as-code-lab](https://github.com/Dinaverse/infrastructure-as-code-lab)** | Terraform & Ansible frameworks for reproducible deployments | Terraform, Ansible, IaC | 🔄 In Dev |

### Security & Automation

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[cybersecurity-lab-automation](https://github.com/Dinaverse/cybersecurity-lab-automation)** | Autonomous agents for log monitoring, recon, threat detection | Python, MCP Bridge, Morpheus | ✅ Active |
| **[sovereign-ai-security](https://github.com/Dinaverse/sovereign-ai-security)** | NVIDIA Morpheus + Triton integration for AI-driven SecOps | Morpheus, Triton, Python | ✅ Active |
| **[sovereign-ai-skills](https://github.com/Dinaverse/sovereign-ai-skills)** | Custom AI skills & Gemini CLI integration for agent orchestration | Gemini CLI, Python, Ollama | ✅ Active |
| **[n8n-automation-hub](https://github.com/Dinaverse/n8n-automation-hub)** | Workflow definitions for lab orchestration and automation | n8n, Workflows | ✅ Active |
| **[ai-workflow-automation](https://github.com/Dinaverse/ai-workflow-automation)** | Gemini CLI tools for repo management & documentation automation | Gemini CLI, Node.js, Git | ✅ Active |

### Homelab & Networking

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[proxmox-homelab-setup](https://github.com/Dinaverse/proxmox-homelab-setup)** | Proxmox hypervisor on Dell T1700 with LXC, Docker, Tailscale | Proxmox VE, LXC, Docker, Tailscale | ✅ Stable |
| **[network-labs-documentation](https://github.com/Dinaverse/network-labs-documentation)** | Cisco Packet Tracer network topology analysis & documentation | Cisco, Networking | ✅ Active |

---

## ⚙️ Core Technology Stack

```text
🐧 Operating Systems  ::  Arch Linux, Kali Linux, Debian, Ubuntu Server, Raspbian
🐳 Containerization   ::  Docker, Docker Compose, Proxmox VE, LXC
🤖 AI Runtime         ::  Ollama, CUDA, Multi-GPU VRAM pooling, Qwen 3.5:27B
📊 Monitoring         ::  Prometheus, Grafana, custom Python agents
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
[Dell Gateway / Monitoring]
     │
[Internal LAN]
     ├── [Kali Master Orchestrator & SecOps]
     ├── [Arch GPU Compute Cluster]  ← 4× NVIDIA P106-100 / 24 GB VRAM
     ├── [Raspberry Pi IDS / DNS / Network Services]
     └── [AMD Canwork189 Storage & CPU Worker]
```

### Hardware
- **Arch-GPU:** Arch Linux, 4× NVIDIA P106-100 (24 GB VRAM), local LLM inference
- **Kali-Master:** Kali Linux, master orchestration, security ops, MCP bridge
- **Raspberry-Pi:** Raspbian, IDS (Suricata), DNS, network monitoring
- **Dell-Gateway:** Debian, internet gateway, Prometheus/Grafana monitoring
- **AMD-Storage:** Ubuntu Server, distributed storage, CPU-bound workloads

### Services
| Service | Host | Role | Port |
|---------|------|------|------|
| **Ollama** | Arch-GPU | LLM inference runtime | 11434 |
| **Grafana** | Dell-Gateway | Monitoring dashboards | 3000 |
| **Prometheus** | Dell-Gateway | Metrics collection | 9090 |
| **n8n** | Docker host | Workflow automation | 5678 |
| **Suricata IDS** | Raspberry-Pi | Network intrusion detection | - |
| **Morpheus** | Kali-Master | AI-driven threat detection | - |

---

## 📚 Documentation Guide

### Quick Navigation

| Goal | Repository | File |
|------|-----------|------|
| **Understand architecture** | `sovereign-ai-infrastructure` | `README.md` |
| **Deploy Docker services** | `local-ai-sovereign-stack` | `README.md` |
| **GPU optimization** | `arch-linux-multi-gpu-llm` | Repository docs |
| **Security automation** | `cybersecurity-lab-automation` | `README.md` |
| **Proxmox setup** | `proxmox-homelab-setup` | `README.md` |
| **Workflow automation** | `n8n-automation-hub` | Repository docs |
| **IaC frameworks** | `infrastructure-as-code-lab` | `README.md` |

### Repository Dependencies

```
sovereign-ai-infrastructure (core docs)
     ├── local-ai-sovereign-stack (Docker AI stack)
     ├── arch-linux-multi-gpu-llm (GPU optimization)
     ├── cybersecurity-lab-automation (Security agents)
     ├── sovereign-ai-security (Morpheus integration)
     ├── sovereign-ai-skills (AI skills)
     ├── n8n-automation-hub (Workflows)
     ├── infrastructure-as-code-lab (IaC)
     └── proxmox-homelab-setup (Hypervisor)
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

---

## 🔗 Complete Repository Map

### Infrastructure & Architecture
- **[sovereign-ai-infrastructure](https://github.com/Dinaverse/sovereign-ai-infrastructure)** — Central documentation hub
- **[infrastructure-as-code-lab](https://github.com/Dinaverse/infrastructure-as-code-lab)** — IaC deployment frameworks
- **[proxmox-homelab-setup](https://github.com/Dinaverse/proxmox-homelab-setup)** — Hypervisor & LXC setup

### AI & Compute
- **[local-ai-sovereign-stack](https://github.com/Dinaverse/local-ai-sovereign-stack)** — Docker AI stack
- **[arch-linux-multi-gpu-llm](https://github.com/Dinaverse/arch-linux-multi-gpu-llm)** — GPU cluster optimization

### Security & Automation
- **[cybersecurity-lab-automation](https://github.com/Dinaverse/cybersecurity-lab-automation)** — Security agents & analytics
- **[sovereign-ai-security](https://github.com/Dinaverse/sovereign-ai-security)** — NVIDIA Morpheus integration
- **[sovereign-ai-skills](https://github.com/Dinaverse/sovereign-ai-skills)** — Custom AI skills
- **[n8n-automation-hub](https://github.com/Dinaverse/n8n-automation-hub)** — Workflow automation
- **[ai-workflow-automation](https://github.com/Dinaverse/ai-workflow-automation)** — Gemini CLI automation

### Networking & Labs
- **[network-labs-documentation](https://github.com/Dinaverse/network-labs-documentation)** — Cisco Packet Tracer labs

---

## 📖 Current Studies & Validation

* **Academic:** Refining infrastructure methodologies through formal Network Infrastructure & Cybersecurity studies at *Collège de Bois-de-Boulogne*.
* **Certifications:** Pursuing enterprise networking validation (Cisco CCNA / CCST).

---

## 🎯 Philosophy

> *Sovereignty through ownership. Resilience through design. Knowledge through practice.*

Every component runs locally. Every decision is documented. Every failure is a learning opportunity. The lab is not just infrastructure—it's a living system for understanding distributed systems, security architecture, and AI infrastructure at scale.

---

*Built with research-and-development mindset. Powered by repurposed hardware. Governed by open standards.*
