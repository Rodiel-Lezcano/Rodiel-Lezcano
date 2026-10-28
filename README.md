<!-- Header Banner -->
<div align="center">
  <img src="header-banner-hyperscaler.svg" alt="Rodiel Lezcano — Solutions Architect · Cloud & AI · IaC Automation" width="100%" />
</div>

<div align="center">

<br/>

<a href="https://www.linkedin.com/in/rodiellezcano" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-rodiellezcano-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="https://htperformance.ca" target="_blank"><img src="https://img.shields.io/badge/Portfolio-htperformance.ca-0891b2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>&nbsp;
<a href="mailto:rodiel.lezcano@htperformance.ca"><img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
<a href="https://www.credly.com/users/rodiel-lezcano" target="_blank"><img src="https://img.shields.io/badge/Credly-Verified_Badges-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly" /></a>

<img src="https://komarev.com/ghpvc/?username=rodiel-lezcano&label=Profile%20views&color=0891b2&style=flat" alt="Profile views" />

</div>

---

## 👨‍💻 About Me

> **Solutions Architect** certified at architect level on **AWS**, **Azure**, and **Google Cloud**. I build production-grade infrastructure & security from bare metal to Kubernetes, with AI integration and full-stack IaC automation. Everything is code, nothing is manual.

- 🌍 Based in the **Greater Toronto Area, Canada**
- ☁️ **Triple-Cloud Architect** — AWS Solutions Architect Professional · Azure Solutions Architect Expert · Google Professional Cloud Architect
- 🤖 **AI Platform Builder** — Claude Certified Architect; self-hosted LLM agents with 17 MCP tool servers behind an open-source AI gateway
- 🏗️ I build and operate a **35+ guest homelab** spanning Proxmox VE, a 7-node Talos Kubernetes cluster, and a GPU worker for local inference
- 🔒 Zero secrets in code · Zero SSH · Zero trust — security-first architecture everywhere
- 🧊 Immutable infrastructure advocate — **Talos Linux** for K8s, **Fedora CoreOS** for AI workloads
- 📱 **Unified Endpoint Management Expert** — enterprise MDM across Apple, Android, Samsung, and Windows
- 🌐 Bilingual — fluent in **English** and **Spanish**

---

## 🔭 Recently Shipped

| When | What |
|:-----|:-----|
| Oct 2026 | 🎓 **Claude Certified Architect – Professional** (Anthropic) |
| Oct 2026 | 🤖 Moved 17 MCP tool servers into Kubernetes behind **agentgateway**, with per-tool access control and human approval for actions |
| Oct 2026 | 🎮 Added an **NVIDIA RTX A1000 GPU worker** to the Talos cluster for local LLM inference |
| Sep 2026 | 🎓 **AWS Certified Solutions Architect – Professional** |
| Jul 2026 | 🎓 **Azure Solutions Architect Expert** · **Google Cloud Generative AI Leader** |
| May 2026 | 🎓 **Azure Administrator Associate** |

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [☸️ k8s-homelab](https://github.com/Rodiel-Lezcano/k8s-homelab)
**Production-Grade Kubernetes on Proxmox**

7-node HA cluster on Talos Linux, managed by Sidero Omni — immutable OS, eBPF networking, GitOps delivery, a GPU worker for local AI, and multi-layer disaster recovery.

<p>
  <img src="https://img.shields.io/badge/Talos_Linux-v1.12-6C4DC4?style=flat-square" />
  <img src="https://img.shields.io/badge/K8s-v1.35-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Cilium-eBPF-F8C517?style=flat-square" />
  <img src="https://img.shields.io/badge/GPU-RTX_A1000-76B900?style=flat-square&logo=nvidia&logoColor=white" />
</p>

`Zero SSH` · `19 Network Policies` · `3-Replica Storage` · `Velero DR`

**Stack:** Cilium · Longhorn · Rancher · Traefik · agentgateway · Fleet GitOps · Velero · Prometheus · Grafana · cert-manager

</td>
<td width="50%" valign="top">

### [🏗️ infraops](https://github.com/Rodiel-Lezcano/infraops)
**Enterprise-Grade IaC for Proxmox Homelab**

Full lifecycle infrastructure automation — Terraform provisioning, Ansible config management, Vault secrets, Jenkins CI/CD, dual-SIEM security operations with IDS and crowd-sourced threat blocking.

<p>
  <img src="https://img.shields.io/badge/Terraform-1.10+-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-2.12+-EE0000?style=flat-square&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Vault-1.15+-FFEC6E?style=flat-square&logoColor=black" />
</p>

`35+ Guests` · `5 TF Modules` · `2-Min VM Deploy` · `Zero Secrets in Code`

**Stack:** Proxmox · Jenkins · Gitea · Semaphore · Wazuh · Splunk · Suricata · CrowdSec · Authentik · Headscale · NetBox · n8n

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🦞 openclaw](https://github.com/Rodiel-Lezcano/openclaw)
**Self-Hosted AI Agent Platform**

Four Telegram agents on Fedora CoreOS — local-first LLM inference on a GPU, semantic long-term memory, read-only MCP tools behind an AI gateway, and a human approval step before any action.

<p>
  <img src="https://img.shields.io/badge/Ollama-ornith:9b-0066FF?style=flat-square" />
  <img src="https://img.shields.io/badge/Fedora_CoreOS-Immutable-294172?style=flat-square&logo=fedora&logoColor=white" />
  <img src="https://img.shields.io/badge/NVIDIA-RTX_A1000-76B900?style=flat-square&logo=nvidia&logoColor=white" />
</p>

`4 Agents` · `17 MCP Servers` · `768-dim Vector Memory` · `27+ Agent Skills`

**Stack:** Docker · Ollama · Qdrant · agentgateway · Vault · Prometheus · Grafana · Wazuh

</td>
<td width="50%" valign="top">

### ☁️ AWS Labs

**[aws-serverless-lab](https://github.com/Rodiel-Lezcano/aws-serverless-lab)** — Complete serverless CRUD API using Lambda, API Gateway, and DynamoDB

**[aws-bedrock-genai-workshop](https://github.com/Rodiel-Lezcano/aws-bedrock-genai-workshop)** — No-code GenAI RAG workflow using Amazon Bedrock, OpenSearch, and S3

<p>
  <img src="https://img.shields.io/badge/Lambda-Serverless-FF9900?style=flat-square&logo=awslambda&logoColor=white" />
  <img src="https://img.shields.io/badge/Bedrock-GenAI-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/DynamoDB-NoSQL-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" />
</p>

</td>
</tr>
</table>

---

## 📊 Infrastructure at a Glance

<div align="center">

| Metric | Value |
|:-------|:------|
| 🖥️ **Proxmox Guests** | 35+ (LXC containers, VMs, Talos nodes) |
| ☸️ **Kubernetes Nodes** | 7 (3 CP + 3 Worker + 1 GPU) — Talos Linux via Omni |
| 🧱 **Terraform Modules** | 5 production-ready, reusable |
| 🛡️ **Security Stack** | Wazuh EDR · Suricata IDS · CrowdSec · Splunk |
| 🔐 **Network Policies** | 19 CiliumNetworkPolicies |
| 📈 **Prometheus Rules** | 18 alerting rules, 10 ServiceMonitors |
| 🤖 **AI Agents** | 4 agents · 17 MCP servers · 27+ skills |
| 📚 **Documentation** | 700KB+ across 29 guides |

</div>

---

## 🛠️ Tech Stack

<div align="center">

**Infrastructure & Orchestration**

<p>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
</p>

**Networking & Security**

<p>
  <img src="https://img.shields.io/badge/Cilium_eBPF-F8C517?style=for-the-badge&logo=cilium&logoColor=black" />
  <img src="https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pi--hole-96060C?style=for-the-badge&logo=pihole&logoColor=white" />
</p>

**Observability & Monitoring**

<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Wazuh-3C97DB?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Loki-2C3239?style=for-the-badge&logo=grafana&logoColor=white" />
</p>

**CI/CD & GitOps**

<p>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/Gitea-609926?style=for-the-badge&logo=gitea&logoColor=white" />
  <img src="https://img.shields.io/badge/Fleet-0075A8?style=for-the-badge&logo=rancher&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

**Cloud & AI**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-0066FF?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

**Operating Systems & Platforms**

<p>
  <img src="https://img.shields.io/badge/Talos_Linux-6C4DC4?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Fedora_CoreOS-294172?style=for-the-badge&logo=fedora&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" />
</p>

</div>

---

## 🏆 Certifications

<div align="center">
  <sub>Click a badge to verify it on Credly or Microsoft Learn · hover for the full name</sub>
</div>

<details open>
<summary><strong>☁️ Cloud Architecture (3)</strong></summary>
<br/>
<div align="center">
  <a href="https://www.credly.com/badges/c4892207-9a83-4627-9dea-d82cda72e8e1/public_url"><img src="badges/aws-solutions-architect-professional.png" alt="AWS Certified Solutions Architect – Professional" title="AWS Certified Solutions Architect – Professional" width="110" /></a>
  <a href="https://learn.microsoft.com/en-us/users/rodiel-lezcano/credentials"><img src="badges/azure-solutions-architect-expert.png" alt="Microsoft Certified: Azure Solutions Architect Expert" title="Microsoft Certified: Azure Solutions Architect Expert" width="110" /></a>
  <a href="https://www.credly.com/badges/8f62d4f7-4631-4a40-a626-cbb30f17fafd/public_url"><img src="badges/google-professional-cloud-architect.png" alt="Google Cloud Professional Cloud Architect" title="Google Cloud Professional Cloud Architect" width="110" /></a>
</div>
<br/>
</details>

<details open>
<summary><strong>🤖 AI & Machine Learning (4)</strong></summary>
<br/>
<div align="center">
  <a href="https://www.credly.com/badges/e42d17e4-dea9-4c5f-a596-65d266e53908/public_url"><img src="badges/claude-certified-architect-professional.png" alt="Claude Certified Architect – Professional" title="Claude Certified Architect – Professional" width="110" /></a>
  <a href="https://www.credly.com/badges/3c4604cb-2c30-4076-a437-a59b3169fcb0/public_url"><img src="badges/nvidia-ai-infrastructure-operations.png" alt="NVIDIA-Certified Associate: AI Infrastructure and Operations" title="NVIDIA-Certified Associate: AI Infrastructure and Operations" width="110" /></a>
  <a href="https://www.credly.com/badges/18e671ac-8d4a-4c8d-aabd-74457b2a6fd6/public_url"><img src="badges/aws-ai-practitioner.png" alt="AWS Certified AI Practitioner" title="AWS Certified AI Practitioner" width="110" /></a>
  <a href="https://www.credly.com/badges/2674e4f0-828e-4047-a834-16a22c7418a8/public_url"><img src="badges/google-generative-ai-leader.png" alt="Google Cloud Generative AI Leader" title="Google Cloud Generative AI Leader" width="110" /></a>
</div>
<br/>
</details>

<details>
<summary><strong>🎓 Cloud Associate & Foundations (5)</strong></summary>
<br/>
<div align="center">
  <a href="https://learn.microsoft.com/en-us/users/rodiel-lezcano/credentials"><img src="badges/azure-administrator-associate.png" alt="Microsoft Certified: Azure Administrator Associate" title="Microsoft Certified: Azure Administrator Associate" width="110" /></a>
  <a href="https://www.credly.com/badges/f3a5d593-8f1e-4fdd-9a07-43ae50fbf58b/public_url"><img src="badges/google-associate-cloud-engineer.png" alt="Google Cloud Associate Cloud Engineer" title="Google Cloud Associate Cloud Engineer" width="110" /></a>
  <img src="badges/google-cloud-computing-foundations.png" alt="Google Cloud Computing Foundations" title="Google Cloud Computing Foundations" width="110" />
  <img src="badges/google-cloud-cybersecurity.png" alt="Google Cloud Cybersecurity" title="Google Cloud Cybersecurity" width="110" />
  <img src="badges/google-cloud-data-analytics.png" alt="Google Cloud Data Analytics" title="Google Cloud Data Analytics" width="110" />
</div>
<br/>
</details>

<details>
<summary><strong>🛠️ DevOps & Platform Engineering (3)</strong></summary>
<br/>
<div align="center">
  <a href="https://www.credly.com/badges/f21724d5-d73d-4ab5-a878-025d8ab3882d/public_url"><img src="badges/terraform-associate.png" alt="HashiCorp Certified: Terraform Associate (003)" title="HashiCorp Certified: Terraform Associate (003)" width="110" /></a>
  <a href="https://www.credly.com/badges/cd56e18d-ffae-4ca7-9e87-43028484f914/public_url"><img src="badges/github-foundations.png" alt="GitHub Foundations" title="GitHub Foundations" width="110" /></a>
  <a href="https://www.credly.com/badges/26d41d24-517a-42b8-9f2a-b4488be8adce/public_url"><img src="badges/linux-essentials.png" alt="LPI Linux Essentials" title="LPI Linux Essentials" width="110" /></a>
</div>
<br/>
</details>

<details>
<summary><strong>📱 Enterprise Mobility Management (6)</strong></summary>
<br/>
<div align="center">
  <a href="https://www.credly.com/badges/1303d496-d468-4927-b16a-f333fd5cdcfa/public_url"><img src="badges/apple-certified-it-professional.png" alt="Apple Certified IT Professional" title="Apple Certified IT Professional" width="110" /></a>
  <a href="https://www.credly.com/badges/72c72dea-b8a8-4f4f-868e-22cc78f7a9cd/public_url"><img src="badges/jamf-pro-associate.png" alt="Jamf Certified Associate - Jamf Pro" title="Jamf Certified Associate - Jamf Pro" width="110" /></a>
  <a href="https://www.credly.com/badges/640a89c1-0ce8-4339-8a1f-90c204621965/public_url"><img src="badges/jamf-protect-associate.png" alt="Jamf Certified Associate - Jamf Protect" title="Jamf Certified Associate - Jamf Protect" width="110" /></a>
  <img src="badges/android-enterprise-expert.png" alt="Android Enterprise Certified Expert" title="Android Enterprise Certified Expert" width="110" />
  <img src="badges/samsung-knox-associate.png" alt="Samsung Knox Certified Associate" title="Samsung Knox Certified Associate" width="110" />
  <img src="badges/soti-mobicontrol-solution-expert.png" alt="SOTI MobiControl 2024 Solution Expert" title="SOTI MobiControl 2024 Solution Expert" width="110" />
</div>
<br/>
</details>

<details>
<summary><strong>🔶 AWS Skill Badges (16)</strong></summary>
<br/>
<div align="center">
  <a href="https://www.credly.com/badges/a5069c61-8d7c-43d2-9da8-f2299a683980/public_url"><img src="badges/aws-cloud-essentials.png" alt="AWS Knowledge: Cloud Essentials" title="AWS Knowledge: Cloud Essentials" width="90" /></a>
  <a href="https://www.credly.com/badges/ae7c20a3-5bf5-4a2f-b52b-63da577924eb/public_url"><img src="badges/aws-architecting.png" alt="AWS Knowledge: Architecting (Retired)" title="AWS Knowledge: Architecting (Retired)" width="90" /></a>
  <a href="https://www.credly.com/badges/f6378385-87bb-42dc-9e37-bba9a450e143/public_url"><img src="badges/aws-compute.png" alt="AWS Knowledge: Compute" title="AWS Knowledge: Compute" width="90" /></a>
  <a href="https://www.credly.com/badges/bfceee52-557e-4580-b7b5-7327c79ac0d4/public_url"><img src="badges/aws-networking-core.png" alt="AWS Knowledge: Networking Core" title="AWS Knowledge: Networking Core" width="90" /></a>
  <a href="https://www.credly.com/badges/8e127bc3-b7fb-404f-b3a1-ccb3fe7db658/public_url"><img src="badges/aws-amazon-eks.png" alt="AWS Knowledge: Amazon EKS" title="AWS Knowledge: Amazon EKS" width="90" /></a>
  <a href="https://www.credly.com/badges/4e4d9534-8e02-4a49-9a4c-60b09cb45a2f/public_url"><img src="badges/aws-serverless.png" alt="AWS Knowledge: Serverless" title="AWS Knowledge: Serverless" width="90" /></a>
  <a href="https://www.credly.com/badges/caf46b96-c418-4b05-b26b-e6d4f4807b9b/public_url"><img src="badges/aws-events-and-workflows.png" alt="AWS Knowledge: Events and Workflows" title="AWS Knowledge: Events and Workflows" width="90" /></a>
  <a href="https://www.credly.com/badges/43d032ae-515c-4121-929d-a73b6a46a500/public_url"><img src="badges/aws-migration-foundations.png" alt="AWS Knowledge: Migration Foundations" title="AWS Knowledge: Migration Foundations" width="90" /></a>
  <br/>
  <a href="https://www.credly.com/badges/6a325014-61e7-4db8-af24-eaebd4b68096/public_url"><img src="badges/aws-amazon-braket.png" alt="AWS Knowledge: Amazon Braket" title="AWS Knowledge: Amazon Braket" width="90" /></a>
  <a href="https://www.credly.com/badges/2d46cd59-28cb-4a0e-b63a-bdaeff179f25/public_url"><img src="badges/aws-file-storage.png" alt="AWS Knowledge: File Storage" title="AWS Knowledge: File Storage" width="90" /></a>
  <a href="https://www.credly.com/badges/f1675f24-e41e-4da6-a534-3664a1a4231b/public_url"><img src="badges/aws-data-migration.png" alt="AWS Knowledge: Data Migration" title="AWS Knowledge: Data Migration" width="90" /></a>
  <a href="https://www.credly.com/badges/f935c4cc-f56d-49b7-9336-24eb5159535b/public_url"><img src="badges/aws-data-protection-dr.png" alt="AWS Knowledge: Data Protection & Disaster Recovery" title="AWS Knowledge: Data Protection & Disaster Recovery" width="90" /></a>
  <a href="https://www.credly.com/badges/4b7efbb9-ba0d-49eb-8f34-c9bcbb3e833d/public_url"><img src="badges/aws-cloud-economics.png" alt="AWS Partner: Cloud Economics Essentials" title="AWS Partner: Cloud Economics Essentials" width="90" /></a>
  <a href="https://www.credly.com/badges/7a19ba43-25d6-4624-96c4-6533842f0c75/public_url"><img src="badges/aws-technical-accredited.png" alt="AWS Partner: Technical Accredited" title="AWS Partner: Technical Accredited" width="90" /></a>
  <a href="https://www.credly.com/badges/b8ca9651-fcdb-4934-9e1d-fdaca5baf1b8/public_url"><img src="badges/aws-cloud-quest-practitioner.png" alt="AWS Cloud Quest: Cloud Practitioner" title="AWS Cloud Quest: Cloud Practitioner" width="90" /></a>
  <a href="https://www.credly.com/badges/62236050-d59a-4003-88eb-3ae70779321d/public_url"><img src="badges/aws-security-champion.png" alt="AWS Knowledge: Security Champion" title="AWS Knowledge: Security Champion" width="90" /></a>
</div>
<br/>
</details>

<details>
<summary><strong>🔷 Google Cloud Skill Badges (10)</strong></summary>
<br/>
<div align="center">
  <img src="badges/gcp-gke-cost-optimization.png" alt="Optimize Costs for Google Kubernetes Engine" title="Optimize Costs for Google Kubernetes Engine" width="90" />
  <img src="badges/gcp-terraform-infrastructure.png" alt="Build Infrastructure with Terraform on Google Cloud" title="Build Infrastructure with Terraform on Google Cloud" width="90" />
  <img src="badges/gcp-cloud-architecture.png" alt="Cloud Architecture: Design, Implement, and Manage" title="Cloud Architecture: Design, Implement, and Manage" width="90" />
  <img src="badges/gcp-security-fundamentals.png" alt="Implement Cloud Security Fundamentals on Google Cloud" title="Implement Cloud Security Fundamentals on Google Cloud" width="90" />
  <img src="badges/gcp-secure-network.png" alt="Build a Secure Google Cloud Network" title="Build a Secure Google Cloud Network" width="90" />
  <br/>
  <img src="badges/gcp-network-setup.png" alt="Set Up a Google Cloud Network" title="Set Up a Google Cloud Network" width="90" />
  <img src="badges/gcp-develop-network.png" alt="Develop Your Google Cloud Network" title="Develop Your Google Cloud Network" width="90" />
  <img src="badges/gcp-load-balancing.png" alt="Implement Load Balancing on Compute Engine" title="Implement Load Balancing on Compute Engine" width="90" />
  <img src="badges/gcp-app-dev-environment.png" alt="Set Up an App Dev Environment on Google Cloud" title="Set Up an App Dev Environment on Google Cloud" width="90" />
  <img src="badges/gcp-ml-api-data.png" alt="Prepare Data for ML APIs on Google Cloud" title="Prepare Data for ML APIs on Google Cloud" width="90" />
</div>
<br/>
</details>

---

<div align="center">
  <sub>Built with ☕ and too many VMs — <a href="https://www.linkedin.com/in/rodiellezcano">Let's connect</a></sub>
</div>
