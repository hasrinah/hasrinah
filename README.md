<div align="center">

# Hi, I'm Hasrinah 👋

**Software Development · Automation · System Engineering · IoT**

I build and deploy web applications end to end: the interface, the API, the database and the server setup around them.

</div>

---

## 🧑‍💻 About Me

- 🔭 **Main project:** an internal **Performance Appraisal System**. It has a React + TypeScript frontend and a Python FastAPI backend, uses MySQL, and is deployed with Docker Compose behind Apache / Nginx.
- ⚙️ **Automation:** n8n workflows for PDF reporting, HR approvals and IoT sensor monitoring; automated frontend and backend regression testing; and file-processing tools that generate integrity hashes and encrypt data.
- 🖥️ **System engineering:** containerised deployment, reverse-proxy setup and frontend serving.
- 📚 **Also on GitHub:** projects in **Java Spring Boot**, **PHP** and **Node.js / Express**.

---

## 🌟 Featured Project

### Performance Appraisal System
*Full-stack internal web application · private repository*

A web platform for running staff performance appraisals, with separate access for HR administrators, appraisers and employees.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)

| Area | Capability |
|---|---|
| 🔐 **Access control** | Role-based authentication for HR administrators, appraisers and employees |
| 🏢 **Organisation data** | Employee and company management |
| 🔄 **Appraisal cycles** | Cycle management; employees can be added to an active cycle without affecting existing appraisal records |
| 📝 **Assessments** | Employee self-assessments, appraiser reviews and independent assessments |
| 📊 **HR oversight** | Monitoring and reporting, with PDF and Excel exports |
| 🌐 **Localisation** | English, Chinese and Malay |
| ✅ **Quality** | Automated frontend and backend regression testing |

**Architecture overview**

```mermaid
flowchart LR
    U["Users<br/>HR administrators · Appraisers · Employees"] --> P["Apache / Nginx<br/>reverse proxy & frontend serving"]
    P --> F["React + TypeScript<br/>frontend"]
    P --> B["Python FastAPI<br/>backend"]
    B --> D[("MySQL")]
```

<sub>Deployed with Docker Compose · version-controlled with Git and GitHub</sub>

> 🔒 The source code, data and deployment details are confidential. This section is a high-level summary only.

---

## 🏆 Award-Winning Project

### Smart Visitor Management System for an Animal Garden
*Final Year Project · IoT*

An IoT system that counts visitors automatically and shows real-time crowd information, to help manage visitor flow.
<img width="810" height="1080" alt="image" src="https://github.com/user-attachments/assets/cabe4883-9a22-489f-9b95-e04649b94be7" />

![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![ESP8266](https://img.shields.io/badge/NodeMCU_ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)

- Built an IoT visitor-monitoring system with a NodeMCU ESP8266 and infrared sensors
- Automated visitor counting, with real-time crowd information shown on LCD screens
- Sent sensor data to Firebase over HTTP for real-time storage and retrieval
- Designed for crowd monitoring and better visitor-flow management

**Awards**
- 🥇 **Most Innovative and Creative Award**, Engineering Science & Technology Exhibition 2025 (ESTE'25), MAHSA University
- 🏅 **Fourth Place**, Malaysia Network Idea Competition 2024, Department of Communication Technology and Network, FSKTM, UPM

---

## 📂 Public Projects

| Project | Description | Stack |
|---|---|---|
| [**n8n-automation-workflows**](https://github.com/hasrinah/n8n-automation-workflows) | n8n workflows: daily QC reports turned into PDFs and sent to Telegram, an early-leave approval flow with Approve/Reject email buttons, and hourly IoT temperature monitoring from InfluxDB | n8n · JavaScript · MySQL · InfluxDB · Google Sheets · Gmail · Telegram |
| [**Customerapp**](https://github.com/hasrinah/Customerapp) | One-page customer management (CRUD) app with a layered controller → service → repository design and MySQL persistence | Java 17 · Spring Boot · Spring Data JPA · Thymeleaf · MySQL · Maven |
| [**secure-db-file**](https://github.com/hasrinah/secure-db-file) | Takes pipe-delimited `.unl` data files, writes per-field MD5 integrity files, encrypts each field with AES-256-CBC (OpenSSL) and shows decrypted records in a paginated DataTables view | PHP · OpenSSL · jQuery · DataTables |
| [**resume-analyzer**](https://github.com/hasrinah/resume-analyzer) | Node.js API that accepts PDF résumé uploads and extracts their text | Node.js · Express · Multer · pdf-parse |

---

## 🛠️ Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white) ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **DevOps & Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white) |
| **IoT & Cloud** | ![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white) ![NodeMCU ESP8266](https://img.shields.io/badge/NodeMCU_ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white) |
| **Tools** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white) |

---

## 📈 GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=hasrinah&show_icons=true&hide_rank=true&hide_border=true&theme=dark">
  <img alt="GitHub stats for hasrinah" height="165" src="https://github-readme-stats.vercel.app/api?username=hasrinah&show_icons=true&hide_rank=true&hide_border=true">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=hasrinah&hide_border=true&theme=dark">
  <img alt="GitHub contribution streak for hasrinah" height="165" src="https://streak-stats.demolab.com?user=hasrinah&hide_border=true">
</picture>

</div>

<!--
## 📫 Connect
Uncomment and fill in only the channels you want to share publicly.
- LinkedIn: https://www.linkedin.com/in/<your-handle>
- Email: <your-public-email>
-->
