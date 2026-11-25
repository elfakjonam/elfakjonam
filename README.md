 <div align="center">

# 👋 Hello, I'm a Full-Stack Developer

### 7+ Years of Building Scalable & Modern Software

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&lines=Full-Stack+Developer;Backend+Engineering+%7C+Node.js;Web+%26+Mobile+Applications;System+Design+%26+DevOps)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mkafle595)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mkafle595@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elfakjonam)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=elfakjonam&style=flat-square&color=38BDF8&label=PROFILE+VIEWS)

</div>

---

## 💫 About Me

I'm a **Full-Stack Developer with 7+ years of hands-on coding experience**, specializing in backend engineering and scalable application development.

I enjoy designing reliable systems, writing maintainable code, and building products that solve real-world problems.

- ⚙️ Backend development with Node.js, TypeScript, and NestJS
- 🌐 Modern web applications with React and Next.js
- 📱 Cross-platform mobile development with React Native
- 🏗️ Clean Architecture, DDD, and system design
- 🔐 Secure APIs and authentication systems
- ☁️ Cloud infrastructure, DevOps, and CI/CD
- 📊 Performance, reliability, and observability

---

## 🧩 Engineering Focus

### My Technology Ecosystem

A clean overview of how my engineering technologies connect across application development, backend systems, data, infrastructure, and delivery.

```mermaid
flowchart TB
    USER(["👤 Users"])

    subgraph CLIENT["🎨 CLIENT APPLICATIONS"]
        direction LR
        WEB["🌐 Web<br/>React · Next.js<br/>Redux · Chart.js"]
        MOBILE["📱 Mobile<br/>React Native"]
        UI["🎨 Design<br/>Figma · Canva"]
    end

    subgraph SERVER["⚙️ BACKEND ENGINEERING"]
        direction LR
        NODE["Node.js<br/>TypeScript"]
        FRAMEWORK["NestJS<br/>Express.js"]
        API["REST APIs<br/>JWT · Security"]
        ARCH["Clean Architecture<br/>DDD · Microservices"]
    end

    subgraph STORAGE["🗄️ DATA & STORAGE"]
        direction LR
        SQL["Relational<br/>PostgreSQL · MySQL<br/>MariaDB · Oracle · SQLite"]
        NOSQL["NoSQL & Graph<br/>MongoDB · Neo4j"]
        CACHE["Cache & Search<br/>Redis · Elasticsearch"]
        ORM["ORM<br/>Prisma"]
    end

    subgraph EVENTS["🔄 MESSAGING & REAL-TIME"]
        direction LR
        KAFKA["Apache Kafka"]
        RABBIT["RabbitMQ"]
        SOCKET["Socket.IO"]
    end

    subgraph DELIVERY["☁️ DEVOPS & DELIVERY"]
        direction LR
        CLOUD["Cloud<br/>AWS · Terraform"]
        CONTAINER["Containers<br/>Docker · Kubernetes"]
        CI["CI/CD<br/>Jenkins · GitLab CI"]
        NETWORK["Networking<br/>Nginx"]
    end

    subgraph OPERATIONS["📈 QUALITY & OBSERVABILITY"]
        direction LR
        TEST["Testing<br/>Jest · Vitest · Mocha"]
        METRICS["Metrics<br/>Prometheus · Grafana"]
        TRACK["Error Tracking<br/>Sentry"]
    end

    subgraph WORKFLOW["🛠️ ENGINEERING WORKFLOW"]
        direction LR
        GIT["Git · GitHub · GitLab"]
        PROJECT["Jira"]
        TOOLS["Linux · VS Code"]
    end

    USER --> WEB
    USER --> MOBILE

    WEB --> NODE
    MOBILE --> NODE

    NODE --> FRAMEWORK
    FRAMEWORK --> API
    API --> ARCH

    API --> ORM
    ORM --> SQL
    ORM --> NOSQL
    API --> CACHE

    API --> KAFKA
    API --> RABBIT
    API --> SOCKET

    API --> CLOUD
    CLOUD --> CONTAINER
    CONTAINER --> CI
    CI --> NETWORK

    API --> TEST
    CI --> METRICS
    API --> TRACK

    GIT --> CI
    PROJECT --> GIT
    TOOLS --> GIT

    UI -.-> WEB
    UI -.-> MOBILE

    classDef client fill:#DBEAFE,stroke:#2563EB,color:#1E3A8A,stroke-width:1.5px
    classDef backend fill:#EDE9FE,stroke:#7C3AED,color:#4C1D95,stroke-width:1.5px
    classDef data fill:#D1FAE5,stroke:#059669,color:#064E3B,stroke-width:1.5px
    classDef messaging fill:#FFEDD5,stroke:#EA580C,color:#7C2D12,stroke-width:1.5px
    classDef devops fill:#CFFAFE,stroke:#0891B2,color:#164E63,stroke-width:1.5px
    classDef quality fill:#FCE7F3,stroke:#DB2777,color:#831843,stroke-width:1.5px
    classDef workflow fill:#F3F4F6,stroke:#6B7280,color:#1F2937,stroke-width:1.5px
    classDef user fill:#FFFFFF,stroke:#64748B,color:#0F172A,stroke-width:2px

    class WEB,MOBILE,UI client
    class NODE,FRAMEWORK,API,ARCH backend
    class SQL,NOSQL,CACHE,ORM data
    class KAFKA,RABBIT,SOCKET messaging
    class CLOUD,CONTAINER,CI,NETWORK devops
    class TEST,METRICS,TRACK quality
    class GIT,PROJECT,TOOLS workflow
    class USER user

    style CLIENT fill:#EFF6FF,stroke:#93C5FD,stroke-width:2px
    style SERVER fill:#F5F3FF,stroke:#C4B5FD,stroke-width:2px
    style STORAGE fill:#ECFDF5,stroke:#6EE7B7,stroke-width:2px
    style EVENTS fill:#FFF7ED,stroke:#FDBA74,stroke-width:2px
    style DELIVERY fill:#ECFEFF,stroke:#67E8F9,stroke-width:2px
    style OPERATIONS fill:#FDF2F8,stroke:#F9A8D4,stroke-width:2px
    style WORKFLOW fill:#F9FAFB,stroke:#D1D5DB,stroke-width:2px
```

<details>
<summary><b>🎨 Diagram color legend</b></summary>

| Color | Engineering Area |
|---|---|
| 🔵 Blue | Frontend & client applications |
| 🟣 Purple | Backend & architecture |
| 🟢 Green | Databases & persistence |
| 🟠 Orange | Messaging & real-time systems |
| 🩵 Cyan | Cloud, DevOps & delivery |
| 🩷 Pink | Testing & observability |
| ⚪ Grey | Development workflow |

</details>

---

## 💻 Technology Stack

### Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,python,java&theme=dark" />
</p>

### Backend & APIs

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,prisma&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/REST_APIs-009688?style=flat-square" />
  <img src="https://img.shields.io/badge/JWT-Authentication-black?style=flat-square&logo=jsonwebtokens" />
  <img src="https://img.shields.io/badge/Microservices-Architecture-6A5ACD?style=flat-square" />
</p>

### Frontend & Mobile

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,redux,html,css&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-Mobile-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white" />
</p>

### Databases & Storage

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite,elasticsearch&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white" />
</p>

### Messaging & Real-Time

<p align="center">
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white" />
</p>

### Cloud & DevOps

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,jenkins,nginx,gitlab&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" />
</p>

### Testing & Development Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=jest,vitest,mocha,postman,git,github,gitlab,vscode,jira&theme=dark" />
</p>

### Design & Machine Learning

<p align="center">
  <img src="https://skillicons.dev/icons?i=figma,canva,pytorch,tensorflow&theme=dark" />
</p>

---

## 📊 GitHub Statistics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=elfakjonam&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />

<img width="49%" src="https://github-readme-streak-stats.demolab.com?user=elfakjonam&theme=tokyonight&hide_border=true" />

<br/>

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=elfakjonam&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

---

## 📈 Contribution Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=elfakjonam&theme=tokyo-night&hide_border=true&area=true)](https://github.com/elfakjonam)

</div>

---

## 🤝 Let's Connect

<div align="center">

I'm always open to connecting with developers, collaborating on meaningful projects, and discussing software architecture, backend engineering, and emerging technologies.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mkafle595)

[![Email](https://img.shields.io/badge/Email-Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mkafle595@gmail.com)

<br/>

**💡 Clean code. Thoughtful architecture. Software that scales.**

⭐ Thanks for visiting my profile!

</div>
