# Hey, I'm Dor 👋

**Troubleshooting · Infrastructure · Automation · Self-hosting**

I enjoy figuring out how things work, why they break, and how to make them better.

My professional background is in Tier 3 technical support, investigating complex production issues across SaaS and on-premises systems, working with R&D teams, and helping other engineers troubleshoot difficult problems.

Outside of work, I run a multi-host homelab. Over time, it has become my playground for DevOps practices, infrastructure automation, self-hosted services and AI agents. I like taking a manual process, understanding its failure points and finding a better way to run it.

## What I'm working on

- **My homelab:** running and maintaining containerized services across multiple hosts.
- **Git-based deployments:** managing Docker Compose configurations in Forgejo, automating deployments and improving validation and recovery workflows.
- **Reliability:** centralized secrets management, monitoring, offsite backups and disaster recovery.
- **AI-assisted operations:** exploring how AI agents can help with technical investigations and day-to-day infrastructure tasks.

### A look inside my homelab

```mermaid
flowchart TD
    G["Forgejo · Git"] --> C["CI/CD · Validation"]
    C --> D["Dockhand · Deployments"]
    S["Infisical · Secrets"] --> D
    D --> H["Docker hosts"]
    H --> A["Application workloads"]
    H --> B["GPU & media workloads"]
    H --> R["Backup & recovery services"]
    H -. Metrics .-> M["Prometheus · Grafana"]
    R --> O["Offsite backups"]
```

*Simplified view of my personal infrastructure and deployment workflows.*

## Tools I work with

**Systems & troubleshooting**

![Linux](https://img.shields.io/badge/Linux-344054?style=flat&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

REST APIs · SQL · Networking · TLS · AWS EC2

**Infrastructure & automation**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Forgejo](https://img.shields.io/badge/Forgejo-FB923C?style=flat&logo=forgejo&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-454545?style=flat&logo=tailscale&logoColor=white)

Docker Compose · Dockhand · Infisical · CI/CD · AI-agent workflows

## Selected projects

### [Israeli Sure Importer](https://github.com/dorko87/israeli-sure-importer)

A self-hosted integration that imports Israeli bank and credit card transactions into Sure Finance. It runs in Docker and includes scheduled imports, REST API integration, duplicate detection, dry-run mode and failure notifications.

I'm also interested in documenting more of my homelab, including the decisions behind its architecture and the problems I've encountered along the way.

---

I'm open to opportunities in technical engineering, infrastructure, DevOps and automation, building on my experience in production troubleshooting.

[Connect with me on LinkedIn](https://www.linkedin.com/in/dor-konviser-97883364/)
