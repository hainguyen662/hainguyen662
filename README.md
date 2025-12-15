# Hi there, I'm Hải Nguyễn Phúc 👋

### DevSecOps / SRE Engineer | Kubernetes, ArgoCD, AWS | CI/CD & Cloud Security Automation

📍 **Ho Chi Minh City, Vietnam** 📧 **tfhoaha@gmail.com** 🔗 [**LinkedIn Profile**](https://www.linkedin.com/in/h%E1%BA%A3i-nguy%E1%BB%85n-ph%C3%BAc-a974b6397/)

---

## 📝 About Me

I am a DevSecOps/SRE Engineer with **2 years of hands-on experience**, specializing in building and operating systems on Kubernetes and AWS. I have strong skills in CI/CD automation (GitLab CI), implementing GitOps (ArgoCD), and migrating systems from EC2 to K8s. Currently pursuing a Master's degree in Information Security, I apply a **security-first mindset** to all tasks.

### 🎯 Areas of Expertise
| Domain | Technologies |
| --- | --- |
| **☸️ Orchestration** | Kubernetes (K8s), Docker, Helm, Rancher |
| **🔄 CI/CD & GitOps** | ArgoCD, GitLab CI |
| **☁️ Cloud (AWS)** | EC2, EKS, RDS, Route 53, ECR |
| **📈 Monitoring** | Prometheus, Grafana, Loki |
| **🛡️ DevSecOps** | Network Policies, Cloudflare, Fortigate Firewall |

---

## 💼 Experience

### **DevOps Engineer** | INCEPTIONLABS
*Jul 2024 - Present · 1 yr 6 mos*

* **System Migration (EC2 → K8s) & Hybrid Management:** Led technical support for migrating a large system from EC2 to Kubernetes (K8s) and maintained hybrid deployment pipelines using GitLab CI/CD.
* **SRE Operations & Troubleshooting:** Conducted Root Cause Analysis (RCA) for critical outages. Implemented mechanisms to persist dump files for OOMKilled Pods and configured auto-restart logic for high CPU usage.
* **Operational Task Automation:** Wrote Bash/Shell scripts to automate critical tasks: collecting debug info, sending Slack alerts, and server cleanup.
* **Network & Security:** Managed end-to-end domain/SSL setup (Nginx/Cloudflare). Periodically updated IP Whitelisting and performed security audits.
* **Monitoring:** Administered Prometheus/Grafana for hybrid environments.

### **DevOps Engineer** | Betall Technology JSC
*Sep 2023 - Jun 2024 · 10 mos*

* Monitored Cisco Switch 2960 network traffic using Zabbix deployed via Docker.
* Performed tuning and optimization for CentOS 7 operating systems.
* Adjusted QoS policies for the company network system using Fortigate Firewall.

---

## 🚀 Projects

### 🔐 Secure Internal Documentation System Deployment
*A practical security project focused on preventing Layer 7 bypass attacks (Defense-in-Depth).*
* **Access Control (Layer 3/4):** Deployed on K8s, enforcing strict IP Whitelisting via Nginx Ingress Controller.
* **Anti-Spoofing (Layer 7):** Configured Nginx to prevent HTTP Header Spoofing (e.g., X-Forwarded-For).
* **Zero-Trust Principle:** Explicitly ignored client-provided headers and only trusted the real remote IP to prevent bypass.

### ☸️ Deploying & Operating Google Microservices Demo (End-to-End)
*Full-stack deployment and automation of an 11-tier microservices application.*
* **IaC & GitOps:** Provisioned K3s cluster and synced entire application via **ArgoCD** (Helm Charts).
* **CI/CD & Security:** Built GitLab CI pipelines with automatic security scans before pushing to DockerHub.
* **SRE & Reliability:** Implemented liveness/readiness probes, **HPA**, and **Canary Deployments** via Argo Rollouts.
* **Networking:** Enforced Zero Trust model via Network Policies.

### 🧠 Cogni-Sim: Graph-Aware Transformer for Binary Code Similarity
*Academic project applying Deep Learning to software security.*
* **Objective:** Developed "Cogni-Sim" model to detect binary code similarities for vulnerability analysis.
* **Tech:** Python, PyTorch/TensorFlow.
* **Relevance:** Demonstrates deep understanding of Software Security at the binary level.

---

## 🎓 Education

**University of Information Technology (VNU-HCM)**
* **Master's degree, Information Security** (Nov 2024 - Nov 2026)
* **Bachelor's degree, Information Security** (Nov 2020 - Nov 2024)
    * *Grade:* Very Good
    * *Activities:* EUREKA 2023 Semi-Finalist.

---

## 📚 Publications

**[1] BinShoo: Binary Code Similarity Detection Using Optimized Function Embedding and Siamese Neural Network**
* *Presented at IEEE-RIVF '2024 (18th International Conference on Computing and Communication Technologies).*
* 🔗 [Read Paper on IEEE Xplore](https://ieeexplore.ieee.org/document/11009080)

**[2] Binary Representation Embedding and Deep Learning For Binary Code Similarity Detection in Software Security Domain**
* *Presented at SOICT '23 (12th International Symposium on Information and Communication Technology).*
* 🔗 [Read Paper on ACM Digital Library](https://dl.acm.org/doi/10.1145/3628797.3628996)

---
