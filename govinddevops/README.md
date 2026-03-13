<div align="center">

<!-- ANIMATED HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Govind&fontSize=52&fontColor=00d4ff&animation=fadeIn&fontAlignY=38&desc=Junior%20DevOps%20Engineer%20%7C%20Cloud-Native%20Infrastructure&descAlignY=58&descSize=18&descColor=a8dadc" width="100%" />

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=750&lines=🚀+Automating+Everything-as-Code+(EaC);☸️+Kubernetes+%7C+Docker+%7C+CI%2FCD+Engineer;⚙️+Building+99.9%25+Uptime+Infrastructure;🐧+Linux+Administration+%7C+Cloud-Native+Expert" alt="Typing SVG" />
</a>

<br/>

<!-- PROFILE VIEWS + FOLLOWERS -->
<img src="https://komarev.com/ghpvc/?username=govinddevops&label=Profile+Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
&nbsp;
<img src="https://img.shields.io/badge/Experience-1.5%20Years-brightgreen?style=for-the-badge&logo=devdotto&logoColor=white" />
&nbsp;
<img src="https://img.shields.io/badge/Uptime-99.9%25-blue?style=for-the-badge&logo=statuspage&logoColor=white" />

</div>

---

## 👨‍💻 About Me

> **Junior DevOps Engineer** with **1.5 years** of hands-on experience in **Linux Administration** and **Cloud-Native Infrastructure**. Proven expertise in architecting automated CI/CD pipelines, containerizing complex applications, and managing Kubernetes orchestration to maintain **99.9% system uptime**.

```yaml
Name        : Govind
Role        : Junior DevOps Engineer
Experience  : 1.5 Years
Focus       : Everything-as-Code (EaC) | Automation | Cloud-Native
Availability: Open to Opportunities ✅
```

- 🚀 **Focus:** Automating **Everything-as-Code (EaC)** to drive efficient, scalable workflows
- ☸️ **Expertise:** Production-grade **Kubernetes Cluster Management** & **Docker Multi-stage Optimization**
- ⚙️ **Automation:** Enterprise **CI/CD Workflow Design** & Infrastructure Monitoring
- 🌱 **Currently Learning:** Advanced GitOps, Helm Charts & ArgoCD
- 💬 **Ask me about:** Kubernetes, Docker, Jenkins, GitHub Actions, Linux

---

## 🧰 DevOps Toolchain

<div align="center">

### 🐧 Operating System & Shell
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### ☁️ Cloud & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

### ⚙️ CI/CD & Automation
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 📊 Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### 🗄️ Servers & Networking
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)

</div>

---

## ⚙️ Core Infrastructure Capabilities

| Domain | Skills |
|---|---|
| 🏗️ **Orchestration** | Advanced Kubernetes Pod lifecycle management, Replica scaling, HPA |
| 🌐 **Service Delivery** | Nginx Ingress Controllers, LoadBalancers, secure Port Mapping |
| 🤖 **Automation** | Custom Bash frameworks for health monitoring, backups, log rotation |
| 🔐 **Security & Config** | Kubernetes ConfigMaps, Secrets, RBAC management |
| 🔄 **CI/CD Pipelines** | Jenkins, GitHub Actions — build → test → deploy workflows |
| 📦 **Containerization** | Docker multi-stage builds, image optimization, Docker Compose |

---

## ☸️ Kubernetes Deployment Architecture

```
             🌐 User Request
                    │
                    ▼
      ┌─────────────────────────┐
      │  Nginx Ingress Controller│  ← SSL Termination, Routing Rules
      └────────────┬────────────┘
                   │
                   ▼
      ┌─────────────────────────┐
      │    Service (ClusterIP)   │  ← Internal DNS, Load Distribution
      └────────────┬────────────┘
                   │
                   ▼
      ┌─────────────────────────┐
      │  Deployment (ReplicaSets)│  ← Rolling Updates, Auto-Healing
      └────────────┬────────────┘
                   │
          ┌────────┴────────┐
          ▼                 ▼
      ┌────────┐       ┌────────┐
      │  Pod 1 │       │  Pod 2 │   ← HPA: Scales on CPU/Memory
      └───┬────┘       └───┬────┘
          │               │
          ▼               ▼
      ┌────────────────────────┐
      │  Containerized App      │  ← Docker Multi-stage Optimized
      │  (Docker Image)         │
      └────────────────────────┘
```

---

## 🔍 Operations & Troubleshooting Toolkit

```bash
#!/bin/bash
# ── Govind's Production Kubernetes Debugging Playbook ──────────────────────

# ✅ Verify health across all namespaces
kubectl get pods -A

# 📋 Inspect real-time application logs for debugging
kubectl logs -f <pod-name>

# 🔬 Deep-dive: Troubleshoot CrashLoopBackOff or Networking issues
kubectl describe pod <pod-name>

# 🔄 Manage and track deployment rollout status
kubectl rollout status deployment <deployment-name>

# ⏪ Emergency: Rollback a bad deployment instantly
kubectl rollout undo deployment <deployment-name>

# 📈 Monitor resource consumption across pods
kubectl top pods -A

# 🔑 Decode a Kubernetes Secret securely
kubectl get secret <secret-name> -o jsonpath="{.data.<key>}" | base64 --decode
```

---

## 📊 GitHub Stats & Activity

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=govinddevops&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=govinddevops&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=c9d1d9"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=govinddevops&theme=tokyonight&hide_border=true&background=0d1117&stroke=00d4ff&ring=00d4ff&fire=ff6e6e&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=00d4ff&sideLabels=00d4ff&dates=888" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=govinddevops&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d4ff&line=00d4ff&point=ffffff" width="100%" />

</div>

---

## 🚀 Featured Project

<div align="center">

[![cloud-native-cicd-delivery-platform](https://github-readme-stats.vercel.app/api/pin/?username=govinddevops&repo=cloud-native-cicd-delivery-platform&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9)](https://github.com/govinddevops/cloud-native-cicd-delivery-platform)

</div>

**🔥 cloud-native-cicd-delivery-platform** — Enterprise-grade Cloud Native CI/CD Platform

- ☸️ Full **Kubernetes** deployment manifests with HPA & Ingress configurations
- 🐳 **Docker** multi-stage optimized build pipelines
- 🔄 **GitHub Actions** & **Jenkins** CI/CD automation workflows
- 📊 Complete **Prometheus + Grafana** monitoring stack implementation
- 🔐 Security-hardened configs using K8s Secrets & ConfigMaps

---

## 🏆 Achievements & Highlights

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=govinddevops&theme=tokyonight&no-frame=true&row=1&column=6&margin-w=10&no-bg=true)

</div>

---

## 📫 Let's Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-govind.devops%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:govindsharma.devops@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Govind-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/govind-devops-a20ab33b6/)

<br/>

> 💼 **Open to Junior DevOps / Cloud Infrastructure roles**
> Feel free to reach out for collaborations, opportunities, or just a DevOps chat! 🚀

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer&animation=fadeIn" width="100%" />

**⭐ DevOps | ☸️ Kubernetes | 🐳 Docker | ⚙️ Jenkins | 🔄 CI/CD | 📊 Monitoring | 🤖 Automation | 🐧 Linux**

*"Automate everything. Monitor everything. Break nothing."*

</div>

