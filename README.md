<!-- Header Banner -->
<div align="center">
  <img src="header-banner-hyperscaler.svg" alt="Rodiel Lezcano — Solutions Architect · Cloud & AI · IaC Automation" width="100%" />
</div>

<div align="center">

<br/>

<a href="https://www.linkedin.com/in/rodiellezcano" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-rodiellezcano-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
<a href="https://htperformance.ca" target="_blank"><img src="https://img.shields.io/badge/Portfolio-htperformance.ca-0891b2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>&nbsp;
<a href="mailto:rodiel.lezcano@htperformance.ca"><img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;
<a href="https://www.github.com/rodiel-lezcano" target="_blank"><img src="https://img.shields.io/github/followers/rodiel-lezcano?logo=github&style=for-the-badge&color=0891b2&labelColor=1c1917" alt="Followers" /></a>

<img src="https://komarev.com/ghpvc/?username=rodiel-lezcano&label=Profile%20views&color=0891b2&style=flat" alt="Profile views" />

</div>

---

## 👨‍💻 About Me

> **Solutions Architect** building production-grade cloud infrastructure & security — from bare metal to Kubernetes — with multi-cloud expertise, AI integration, and full-stack IaC automation. Everything is code, nothing is manual.

- 🌍 Based in the **Greater Toronto Area, Canada**
- ☁️ **Multi-Cloud** — certified across **AWS**, **Azure**, and **GCP** with hands-on production experience
- 🏗️ I build and operate a **30+ host homelab** spanning Proxmox VE, Kubernetes, and GPU-accelerated AI
- 🔒 Zero secrets in code · Zero SSH · Zero trust — security-first architecture everywhere
- 🧊 Immutable infrastructure advocate — **Talos Linux** for K8s, **Fedora CoreOS** for AI workloads
- 🤖 **AI Practitioner** — local LLM inference with semantic vector memory on self-hosted GPU infrastructure
- 📱 **Unified Endpoint Management Expert** — enterprise MDM across Apple, Android, Samsung, and Windows
- 🌐 Bilingual — fluent in **English** and **Spanish**

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [☸️ k8s-homelab](https://github.com/Rodiel-Lezcano/k8s-homelab)
**Production-Grade Kubernetes on Proxmox**

6-node HA cluster running Talos Linux — immutable OS, eBPF networking, GitOps delivery, and multi-layer disaster recovery.

<p>
  <img src="https://img.shields.io/badge/Talos_Linux-v1.12-6C4DC4?style=flat-square" />
  <img src="https://img.shields.io/badge/K8s-v1.35-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Cilium-eBPF-F8C517?style=flat-square" />
</p>

`Zero SSH` · `19 Network Policies` · `3-Replica Storage` · `Velero DR`

**Stack:** Cilium · Longhorn · Rancher · Traefik · Fleet GitOps · Velero · Prometheus · Grafana · cert-manager

</td>
<td width="50%" valign="top">

### [🏗️ infraops](https://github.com/Rodiel-Lezcano/infraops)
**Enterprise-Grade IaC for Proxmox Homelab**

Full lifecycle infrastructure automation — Terraform provisioning, Ansible config management, Vault secrets, Jenkins CI/CD, dual-SIEM security operations.

<p>
  <img src="https://img.shields.io/badge/Terraform-1.10+-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-2.12+-EE0000?style=flat-square&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Vault-1.15+-FFEC6E?style=flat-square&logoColor=black" />
</p>

`30+ Hosts` · `5 TF Modules` · `2-Min VM Deploy` · `Zero Secrets in Code`

**Stack:** Proxmox · Jenkins · Gitea · Wazuh · Splunk · Authentik · Headscale · NetBox · n8n

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🦞 openclaw](https://github.com/Rodiel-Lezcano/openclaw)
**GPU-Accelerated Personal AI Infrastructure**

Self-hosted AI platform on Fedora CoreOS — local LLM inference with semantic long-term memory, GPU offloading, custom Prometheus exporter, and zero cloud dependency.

<p>
  <img src="https://img.shields.io/badge/Ollama-qwen2.5:7b-0066FF?style=flat-square" />
  <img src="https://img.shields.io/badge/CoreOS-43-294172?style=flat-square&logo=fedora&logoColor=white" />
  <img src="https://img.shields.io/badge/NVIDIA-P1000-76B900?style=flat-square&logo=nvidia&logoColor=white" />
</p>

`1-3s Inference` · `768-dim Vector Memory` · `27+ Agent Skills` · `3 Dashboards`

**Stack:** Docker · NVIDIA Container Toolkit · SQLite-vec · Prometheus · Grafana · Promtail

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
| 🖥️ **Managed Hosts** | 30+ (VMs, LXC, K8s nodes, bare metal) |
| ☸️ **Kubernetes Nodes** | 6 (3 CP + 3 Worker) — Talos Linux |
| 🧱 **Terraform Modules** | 5 production-ready, reusable |
| 🛡️ **Security Agents** | 14 Wazuh + 13 Splunk forwarders |
| 🔐 **Network Policies** | 19 CiliumNetworkPolicies |
| 📈 **Prometheus Rules** | 18 alerting rules, 10 ServiceMonitors |
| 🤖 **AI Agent Skills** | 27+ (1Password, GitHub, Hue, Sonos, Whisper…) |
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
  <img src="https://img.shields.io/badge/Ollama-0066FF?style=for-the-badge&logoColor=white" />
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

<details>
<summary><strong>🛠️ DevOps & Platform Engineering</strong></summary>
<br/>
<div align="center">
  <img src="https://images.credly.com/size/340x340/images/3d924691-436a-4fb6-b19b-1005ccbb6135/blob" alt="NVIDIA-Certified Associate: AI Infrastructure and Operations" width="110" />
  <img src="https://images.credly.com/size/340x340/images/0dc62494-dc94-469a-83af-e35309f27356/blob" alt="HashiCorp Terraform Associate" width="110" />
  <img src="https://images.credly.com/size/340x340/images/024d0122-724d-4c5a-bd83-cfe3c4b7a073/image.png" alt="GitHub Foundations" width="110" />
  <img src="https://images.credly.com/size/340x340/images/1d36cb36-20fc-4961-8d70-6307c015d1aa/blob" alt="Linux Essentials" width="110" />
</div>
</details>

<details>
<summary><strong>☁️ Google Cloud Certifications</strong></summary>
<br/>
<div align="center">
  <img src="https://images.credly.com/size/340x340/images/71c579e0-51fd-4247-b493-d2fa8167157a/image.png" alt="Professional Cloud Architect" width="110" />
  <img src="https://images.credly.com/size/340x340/images/08096465-cbfc-4c3e-93e5-93c5aa61f23e/image.png" alt="Associate Cloud Engineer" width="110" />
  <img src="https://images.credly.com/size/340x340/images/4dda8ae4-99ee-476c-bca3-6f0adbab42fe/image.png" alt="Google Cloud Computing Foundations" width="110" />
  <img src="https://images.credly.com/size/340x340/images/505080ad-3731-4b1d-98df-347655a45750/image.png" alt="Google Cloud Cybersecurity" width="110" />
  <img src="https://images.credly.com/size/340x340/images/f53c1eb6-d93d-4b9e-ae34-922046f6b15c/image.png" alt="Google Cloud Data Analytics" width="110" />
</div>
</details>

<details>
<summary><strong>☁️ Google Cloud Skill Badges (10)</strong></summary>
<br/>
<div align="center">
  <img src="https://images.credly.com/size/340x340/images/258d3147-f075-4308-bdb0-fb8d5e1d4d0e/image.png" alt="Optimize Costs for Google Kubernetes Engine" width="90" />
  <img src="https://images.credly.com/size/340x340/images/b18154fb-9bd3-47e5-a6f1-554be512947d/image.png" alt="Build Infrastructure with Terraform on Google Cloud" width="90" />
  <img src="https://images.credly.com/size/340x340/images/746b172c-bdae-4bd9-b29b-eecfc9ad3577/image.png" alt="Cloud Architecture: Design, Implement, and Manage" width="90" />
  <img src="https://images.credly.com/size/340x340/images/f1dbea96-0ef4-4857-bb85-3d208a82de10/image.png" alt="Implement Cloud Security Fundamentals on Google Cloud" width="90" />
  <img src="https://images.credly.com/size/340x340/images/e1131ae3-4a52-4af1-9801-b7853767cf79/image.png" alt="Build a Secure Google Cloud Network" width="90" />
  <img src="https://images.credly.com/size/340x340/images/189c5c31-67c6-4eae-87dc-3b8185a99043/image.png" alt="Set Up a Google Cloud Network" width="90" />
  <img src="https://images.credly.com/size/340x340/images/b126c61c-4781-4f03-9b2b-062963003abf/image.png" alt="Develop Your Google Cloud Network" width="90" />
  <img src="https://images.credly.com/size/340x340/images/eea11cba-2a98-4bbe-bad2-447878dd34a2/image.png" alt="Implement Load Balancing on Compute Engine" width="90" />
  <img src="https://images.credly.com/size/340x340/images/42326d44-14ff-4eda-b9c5-7d8f12919253/image.png" alt="Set Up an App Dev Environment on Google Cloud" width="90" />
  <img src="https://images.credly.com/size/340x340/images/68756311-9319-4eeb-a2b7-76defc8dd8a2/image.png" alt="Prepare Data for ML APIs on Google Cloud" width="90" />
</div>
</details>

<details>
<summary><strong>🔶 AWS Certifications</strong></summary>
<br/>
<div align="center">
  <img src="https://images.credly.com/size/340x340/images/4d4693bb-530e-4bca-9327-de07f3aa2348/image.png" alt="AWS Certified AI Practitioner" width="110" />
</div>
</details>

<details>
<summary><strong>🔶 AWS Cloud Skill Badges (16)</strong></summary>
<br/>
<div align="center">
  <img src="https://images.credly.com/size/340x340/images/7cf036b0-c609-4378-a7be-9969e1dea7ab/blob" alt="Cloud Essentials" width="90" />
  <img src="https://images.credly.com/size/340x340/images/519a6dba-f145-4c1a-85a2-1d173d6898d9/image.png" alt="Architecting" width="90" />
  <img src="https://images.credly.com/size/340x340/images/c2d44375-6567-495a-b868-d17828c62872/blob" alt="Compute" width="90" />
  <img src="https://images.credly.com/size/340x340/images/e1c202b1-bca1-469a-9149-127b4fe891d7/blob" alt="Networking Core" width="90" />
  <img src="https://images.credly.com/size/340x340/images/f5efafe6-ebdc-485c-9ffa-3a05533e634b/blob" alt="Amazon EKS" width="90" />
  <img src="https://images.credly.com/size/340x340/images/0c20a5b7-b4e9-4c2f-8b68-342e00a85e05/blob" alt="Serverless" width="90" />
  <img src="https://images.credly.com/size/340x340/images/b6050277-c769-4d17-8c77-3fa963830231/blob" alt="Events and Workflows" width="90" />
  <img src="https://images.credly.com/size/340x340/images/af87a78c-bd87-4f68-a179-d3edf6ac59d1/blob" alt="Migration Foundations" width="90" />
  <img src="https://images.credly.com/size/340x340/images/811c6414-b84e-4879-bc5c-863fa62be6aa/blob" alt="Amazon Braket" width="90" />
  <img src="https://images.credly.com/size/340x340/images/635449f2-3a53-40b3-bf08-5af4fb95df61/blob" alt="File Storage" width="90" />
  <img src="https://images.credly.com/size/340x340/images/f9092eff-1951-4b43-901c-d43df9034b22/blob" alt="Data Migration" width="90" />
  <img src="https://images.credly.com/size/340x340/images/94af532a-9586-4cc5-b313-6341d3e5fb89/blob" alt="Data Protection & DR" width="90" />
  <img src="https://images.credly.com/size/340x340/images/1ba189ae-4afb-4c3b-ae89-f3da3c054f05/blob" alt="Cloud Economics" width="90" />
  <img src="https://images.credly.com/size/340x340/images/8f006312-3154-45bf-a845-4a043641e83c/blob" alt="Technical Accredited" width="90" />
  <img src="https://images.credly.com/size/340x340/images/30816e43-2550-4e1c-be22-3f03c5573bb9/blob" alt="Cloud Quest" width="90" />
  <img src="https://images.credly.com/size/340x340/images/478cdcb9-9b92-4893-9c95-617ad0f28257/blob" alt="AWS Knowledge: Security Champion" width="90" />
</div>
</details>

<details>
<summary><strong>📱 Enterprise Mobility Management (6)</strong></summary>
<br/>
<div align="center">
  <img src="https://images.credly.com/size/340x340/images/f2834519-1861-4d48-942b-fe2a2f4ffe6d/image.png" alt="Apple Certified IT Professional" width="110" />
  <img src="https://images.credly.com/size/340x340/images/62bbd4cd-0ef3-450d-9d9b-160676e9dc47/blob" alt="Jamf Pro" width="110" />
  <img src="https://images.credly.com/size/340x340/images/e2e9c910-ac0c-447f-9d89-da362aec6203/blob" alt="Jamf Protect" width="110" />
  <img src="https://github.com/Rodiel-Lezcano/certificates-images/blob/main/android-enterprise-certified-expert.png" alt="Android Enterprise" width="110" />
  <img src="https://github.com/Rodiel-Lezcano/certificates-images/blob/942e26fb9391bf60ca64d54d4be61d3f15f6d21e/samsung-knox-certificate-associate.png" alt="Samsung Knox" width="110" />
  <img src="https://github.com/Rodiel-Lezcano/certificates-images/blob/942e26fb9391bf60ca64d54d4be61d3f15f6d21e/soti-mobicontrol-2024-solution-expert.png" alt="SOTI MobiControl" width="110" />
</div>
</details>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=rodiel-lezcano&show_icons=true&count_private=true&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true" alt="GitHub Stats" width="49%" />
  <img src="https://streak-stats.demolab.com/?user=rodiel-lezcano&stroke=ffffff&background=1c1917&ring=0891b2&fire=0891b2&currStreakNum=ffffff&currStreakLabel=0891b2&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true" alt="GitHub Streak" width="49%" />
</div>

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=rodiel-lezcano&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20Languages&layout=compact" alt="Top Languages" width="49%" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rodiel-lezcano&bg_color=1c1917&color=0891b2&line=0891b2&point=ffffff&area=true&area_color=0891b2&hide_border=true" alt="Contribution Graph" width="98%" />
</div>

---

<div align="center">
  <sub>Built with ☕ and too many VMs — <a href="https://www.linkedin.com/in/rodiellezcano">Let's connect</a></sub>
</div>
