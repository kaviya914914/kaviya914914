<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0e75b6,100:1F3864&height=200&section=header&text=Kaviya%20Parthiban&fontSize=44&fontColor=ffffff&desc=Production%20Support%20%E2%86%92%20DevOps%20%2F%20SRE&descSize=18&descAlignY=68&animation=fadeIn" alt="header" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=0E75B6&center=true&vCenter=true&width=760&lines=3%2B+years+keeping+production+alive;I+turn+repeat+incidents+into+automation;Jenkins+%E2%86%92+Docker+%E2%86%92+EKS+%E2%86%92+Argo+CD+%E2%86%92+Prometheus+%E2%86%92+auto-rollback" alt="typing" />

<img src="https://komarev.com/ghpvc/?username=kaviya914914&label=visitors&color=0e75b6&style=flat-square" alt="" />

</div>

---

## 👩‍💻 Who I Am

I'm a **Software Engineer at CGI (Chennai)** who has spent **3+ years in production support** for business-critical telecom ordering and billing applications: monitoring batch jobs, handling incidents, doing RCA, and keeping SLAs green.

Every time the same failure came back, I asked *"why is a human fixing this?"* That question took me into **automation, CI/CD, Kubernetes and observability**, and it's why I'm now building toward **DevOps / SRE**.

🟢 **Open to:** DevOps · SRE · Cloud Support · Production Engineering roles

---

## 📈 By the Numbers

| 🗓️ | 🎫 | ⚠️ | 🖥️ | 🏆 | 🛠️ |
|:-:|:-:|:-:|:-:|:-:|:-:|
| **3+ yrs** | **~50 / month** | **2-3 / month** | **13 servers** | **Bronze Award** | **4 projects** |
| in production support | tickets & incidents (ServiceNow) | high-priority incidents handled | health checks automated (Ansible + PowerShell) | CGI, for automation | built end to end |

---

## 🔧 What I've Built

### 🚀 Auto-Rollback Guard: bad release in, healthy release back
> **Problem:** a bad deployment reaches production and someone has to notice, decide and roll back by hand.
> **What I built:** a GitOps pipeline that ships versioned images, watches error rates after every release, and rolls back to the last healthy version.

```mermaid
flowchart LR
    A[GitHub push] --> B[Jenkins: build & test]
    B --> C[Docker image → AWS ECR]
    C --> D[Argo CD → EKS]
    D --> E[Prometheus + Grafana]
    E -->|error rate high| F[Rollback to last healthy version]
```

`Jenkins` `Docker` `ECR` `EKS` `Argo CD` `Prometheus` `Grafana` · includes an **incident runbook** (detect → validate → rollback → RCA)  
🔗 [auto-rollback-guard](https://github.com/kaviya914914/auto-rollback-guard)

### 🩹 Crash-Loop Remediator: Kubernetes that heals itself
> **Problem:** pods stuck in `CrashLoopBackOff` need a person to investigate and restart them.
> **What I built:** a Python operator that detects crash-looping pods and remediates them automatically.

`Python` `kopf` `Kubernetes`  
🔗 [crash-loop-remediator](https://github.com/kaviya914914/crash-loop-remediator)

### 📜 JCL Failure Analyzer: from cryptic abend code to first fix
> **Problem:** mainframe batch failures show codes like S0C7 or S806, and triage means looking each one up.
> **What I built:** a Python tool that reads job logs and explains each abend code with its meaning and first checks. Built from real production support patterns and tested on sample logs.

`Python`  
🔗 [jcl-failure-analyzer](https://github.com/kaviya914914/jcl-failure-analyzer)

### 🔐 Cert Expiry Watchdog: no more surprise certificate outages
> **Problem:** expired TLS certificates take services down without warning.
> **What I built:** a Python checker that scans a list of sites and reports OK / warning / critical before anything expires.

`Python`  
🔗 [cert-expiry-watchdog](https://github.com/kaviya914914/cert-expiry-watchdog)

---

## 🧠 What I Bring to a Team

- **I've been on the other side of the alert.** I know what a good runbook, a clear alert and a clean handoff feel like at 3 AM.
- **RCA is a habit, not a step.** I don't stop at "restarted and fixed".
- **I automate the repeat.** Ansible, Python, Bash and PowerShell for the work nobody should do twice.
- **I ship and I verify.** CI/CD is only useful if you can see the result, so I pair every pipeline with monitoring.
- **SLA-minded.** Incidents, changes, releases and war rooms are part of my normal week.

---

## 🧰 Toolbox, by incident lifecycle

**🔍 Detect**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Control-M](https://img.shields.io/badge/Control--M-C8102E?style=for-the-badge)

**🚨 Respond**
![ServiceNow](https://img.shields.io/badge/ServiceNow-62D84E?style=for-the-badge&logo=servicenow&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**⚙️ Automate**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

**🚀 Ship**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

---

## 💼 Experience

**Software Engineer, CGI** · Sep 2025 – Present  
Production support for business-critical ordering & billing apps · Control-M batch monitoring · ServiceNow incidents (~50/month) · 5-6 BAU deployments a month · RCA, change & release management · war rooms, DR exercises, on-call

**Associate Software Engineer, CGI** · Sep 2023 – Aug 2025  
SLA-driven production support · automated health & sanity checks across 13 Windows servers (Ansible, PowerShell, YAML) · operational dashboards and Jira tracking · 🥉 CGI Bronze Award for automation

---

## 📊 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kaviya914914&show_icons=true&theme=tokyonight&hide_border=true" alt="stats" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=kaviya914914&theme=tokyonight&hide_border=true" alt="streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=kaviya914914&theme=react-dark&hide_border=true&area=true" alt="activity graph" />

</div>

---

## 📚 Learning Now

`Terraform & IaC` · `Kubernetes operators` · `Alerting & logging (Alertmanager, Loki/ELK)`

## 🎓 Education & Certifications

MBA, Business Data Analytics: University of Madras (2024 – 2026) · B.Sc. Computer Science: SDNB Vaishnav College for Women (2020 – 2023) · CGI Skillsoft: Docker, AWS, Linux · AWS Cloud Quest: Cloud Practitioner

---

<div align="center">

<a href="https://www.linkedin.com/in/kaviya-parthiban"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:parthibankaviya914@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F3864,100:0e75b6&height=100&section=footer" alt="footer" />

</div>
