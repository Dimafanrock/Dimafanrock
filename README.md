
<div align="center">

<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExYTBidTVwYzg5aWQ2am12bDJ2cXB0bmx2NGhsMmNkdHhjaW1nOTlreCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/26tn33aiTi1jkl6H6/giphy.gif" width="100%" alt="Banner"/>

# ⚙️ Dmytro Voznyi  
### **System Architect & Engineer | Edge-AI / Industrial IoT / Intelligent Automation**

*Turning complex systems into autonomous, observable, and reliable machines.*

</div>

---

### 🚀 About Me

I design and build **end-to-end systems where hardware, data, and software operate as one** —  
from edge devices and real-time data pipelines to resilient backends and predictive analytics.

- **Edge-AI & Industrial IoT** — local intelligence, sensor fusion, and autonomous control loops.  
- **Cloud & SaaS Backends** — scalable multi-tenant Rails platforms powering device networks.  
- **DevOps & Reliability** — containerized infrastructure with metrics, health checks, and fail-safe orchestration.

Driven by precision and clarity — I believe in **systems that keep working, keep learning, and keep improving**.

---

### 🌐 Featured Projects

| Project | Domain | Core Focus |
|:--|:--|:--|
| **SmartHydro / Magic Box** | Edge-AI IoT | Offline-first automation hub with MQTT, InfluxDB v2, Prometheus + Grafana observability. |
| **Control Server** | Edge Runtime | Python-supervised orchestrator for relays & sensors → Influx persistence → Prometheus metrics. |
| **OutSail / Club.Core** | SaaS Ecosystem | Multi-tenant Rails 7/8 platform with JWT/HMAC auth, Redis + Sidekiq jobs, HubSpot integration. |
| **watchdog exporter** | Monitoring | Custom Prometheus exporter for IoT health loops and device uptime tracking. |

---

### 🧩 Architecture Overview

```mermaid
flowchart LR
    subgraph Edge["Edge Layer – SmartHydro / Control Server"]
        A[Raspberry Pi 4 / Sensors / Relays] -->|MQTT| B(Mosquitto Broker)
        B --> C(Python Control Server)
        C --> D[(InfluxDB 2 – Time-Series)]
        C --> E(Prometheus / Watchdog Exporter)
        E --> F(Grafana Dashboards)
    end

    subgraph Cloud["Cloud / SaaS Layer – OutSail / Club.Core"]
        H(Rails API / Multi-Tenant) --> I[(PostgreSQL DB Cluster)]
        H --> J(Redis + Sidekiq Workers)
        H --> K(AWS / Docker Infra)
    end

    C <--> H
    F --> H
```

---

### 🧠 Core Stack

**Edge / Control Systems**  
> Python · MQTT · Flask · InfluxDB · Prometheus · Grafana · Supervisor · Docker Compose  

**Backend / SaaS**  
> Ruby on Rails 7/8 · Redis · Sidekiq · JWT/HMAC · PostgreSQL · CI/CD · AWS  

**DevOps / Infrastructure**  
> Docker · Portainer · systemd · OpenSSL TLS CA · SSH Automation · ASDF · PyCharm Remote Interpreter  

**Hardware / 3D & Design**  
> Raspberry Pi 4 · RS-485 (Modbus/RTU) · PoE Switches · Fusion 360 · Blender · Unity · Klipper Firmware  

---

### 💡 Personal Operating System

> **Strategic | Analytical | Independent | Builder Mindset**

INTJ-A by structure — I plan from the system level down, design for failure, and iterate until elegance emerges.  
I lead through architecture: clear goals, transparent metrics, reproducible outcomes.

---

### 📈 GitHub Insights

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Dimafanrock&theme=github_dark" height="150"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Dimafanrock&theme=github_dark" height="150"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Dimafanrock&theme=github_dark" height="150"/>
</div>

---

### 🤝 Connect

<div align="center">
  <a href="https://www.linkedin.com/in/dmytro-voznyi">
    <img src="https://img.shields.io/badge/LinkedIn-Dmytro%20Voznyi-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Dimafanrock">
    <img src="https://img.shields.io/badge/GitHub-Dimafanrock-000000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://t.me/Knight866">
    <img src="https://img.shields.io/badge/Telegram-@Knight866-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/>
  </a>
  <a href="mailto:dimafanrock1@gmail.com">
    <img src="https://img.shields.io/badge/Email-dimafanrock1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</div>

---

<div align="center">
  <sub>© 2025 Dmytro Voznyi · Edge-AI & IIoT Architect · Built with clarity and precision.</sub>
</div>
