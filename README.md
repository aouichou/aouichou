<h1 align="center">Hi 👋, I'm Amine</h1>
<h3 align="center">A bakend and DevOps developer and student at 42Paris</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=Agrippa2023&label=Profile%20views&color=0e75b6&style=flat" alt="Agrippa2023" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=Agrippa2023" alt="Agrippa2023" /></a> </p>

- ⚡ Fun fact **I have approximate knowledge of many things**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/amine-ouichou-168236345" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="amine ouichou" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://grafana.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="grafana" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.elastic.co/kibana" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/elasticco_kibana/elasticco_kibana-icon.svg" alt="kibana" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://mariadb.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="mariadb" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> </p>

## 🌟 Featured Portfolio Project (WIP)

[![Production Status](https://img.shields.io/badge/status-live-success?style=for-the-badge&logo=azure-devops)](https://aouichou.me)
[![GitHub Repo](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aouichou/My-Portfolio)

**Cloud-Native Full-Stack Architecture**  
*Django 4.2 | Next.js 14 | Kubernetes | Azure DevOps*

### 🚀 Key Features
- **Production-Grade Deployment**
  - Multi-stage Docker builds with Alpine optimization
  - Kubernetes cluster on Azure AKS
  - Automated CI/CD with GitHub Actions
  - TLS certificates via cert-manager

- **Observability Stack**
  - Prometheus/Grafana monitoring
  - ELK Stack logging
  - Application performance tracing

- **Security Posture**
  - Rate-limited API endpoints
  - CSP headers enforcement
  - HashiCorp Vault integration (WIP)

```bash
# Local development setup
docker-compose up -d frontend backend reverse-proxy

# Production deployment
kubectl apply -f kubernetes/ --recursive
```

### 📊 Infrastructure Overview
```mermaid
graph TD
    A[User] --> B[Azure CDN]
    B --> C[NGINX Ingress]
    C --> D[Next.js Frontend]
    C --> E[Django Backend]
    E --> F[PostgreSQL]
    E --> G[Azure Blob Storage]
```

[Explore the Code →](https://github.com/aouichou/My-Portfolio) | [Live Demo](https://aouichou.me)

---


## Notable 42Paris Projects

### [miniRT](https://github.com/aouichou/miniRT)
- Generate images using Raytracing with the **MiniLibX**.  
- Scene specification uses the “.rt” format.  
- Fully supported plane, sphere, and cylinder, plus bonus features like reflections and color patterns.  
- Achieved a final mark of **125%**.

### [minishell](https://github.com/aouichou/minishell)
- Custom shell in C supporting redirections, pipes, and custom signals.  
- Used `readline`, `fork`, and many other Linux system calls.  
- Achieved a final mark of **101%**.

### ft_transcendence
- Real-time Pong-like web app, with user tournaments, AI opponents, and advanced security.  
- Achieved a final mark of **125%**.  
- **Modules I developed independently**:  
  - Framework-based backend  (Django)
  - Standard user management and authentication  
  - Remote authentication  
  - GDPR compliance (user anonymization, data management, account deletion)  
  - Two-Factor Authentication (2FA) with JWT  
  - Microservices-based backend

## Currently working on the following 42Paris Kernel Projects
- **ft_linux**: Building a functional Linux distro from scratch.  
- **KFS_1**: Developing a custom kernel loader, linking process, and minimal OS environment.  
- **little-penguin-1**: Linux kernel programming challenges, drivers, and subsystem maintenance.

## Currently Learning

   - ### [Kernel programming](https://en.wikipedia.org/wiki/Kernel_%28operating_system%29)

   - ### [Kubernetes](https://en.wikipedia.org/wiki/Kubernetes)

   - ### low-latency programming


<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=aouichou&show_icons=true&locale=en&layout=compact" alt="aouichou" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=aouichou&show_icons=true&locale=en" alt="aouichou" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=aouichou&" alt="aouichou" /></p>

