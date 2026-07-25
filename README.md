<p align="center">
  <img src="./assets/wallpaperPyshicsAmbient.png" alt="Workspace banner" width="100%" />
</p>

<h1 align="center">Vitor Hugo da Silva</h1>

<p align="center">
  <strong>Software Developer · Industrial Systems & Data Engineering · Java · Python · C++</strong>
</p>

<p align="center">
  Building the <a href="#-the-synka-ecosystem"><strong>Synka</strong></a> ecosystem — open-source software that takes industrial data from the factory floor to business insight.
</p>

<p align="center">
  <a href="https://github.com/ViktorWalde">
    <img src="https://img.shields.io/badge/GitHub-ViktorWalde-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/vitor-hugo-da-silva-54359b312/">
    <img src="https://img.shields.io/badge/LinkedIn-Vitor%20Hugo%20da%20Silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:klaushugoruki@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/Location-Jaguapitã,%20PR%20—%20Brazil-2E8B57?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
</p>

---

## 👋 About Me

I'm a **Software Developer from Brazil** focused on **industrial software**, **data engineering** and **distributed systems**.

My work lives at the **OT/IT boundary** — connecting the operational side of the factory floor to modern backend services, and turning that raw telemetry into decision-ready data. That's the problem I'm solving with the **Synka ecosystem**, a set of open-source projects covering the full path from industrial protocols on the edge, through a resilient middleware, into a clean backend, and finally into an ETL/ELT analytics pipeline — designed to be **simple, observable and resilient**.

Right now I'm deepening my mastery of **Java**, **Python for data pipelines**, **modern C++** and **Embedded Linux**, turning real industrial problems into practical, well-engineered software — end to end, from sensor to dashboard.

> 💡 I believe industrial data should be **simple to collect, observable in transit, and trustworthy by the time it reaches a decision-maker** — because in the field, downtime is not an option and neither is a wrong number on a dashboard.

---

## 🏭 The Synka Ecosystem

Synka is an open-source ecosystem that takes data **from the factory floor to business insight** — from raw industrial protocols on the edge, through a resilient middleware, into a clean backend platform and finally into an analytics pipeline.

```
  ┌──────────────┐      ┌──────────────┐      ┌──────────────┐      ┌──────────────┐
  │   Field /    │      │  Synka Core  │      │ Synka Studio │      │  Synka Lens  │
  │   OT Layer   │ ───▶ │  Middleware  │ ───▶ │   Backend    │ ───▶ │  Analytics   │
  │ OPC UA·MQTT  │      │ Store&Forward│      │ Spring·SQL   │      │ ETL·DuckDB   │
  └──────────────┘      └──────────────┘      └──────────────┘      └──────────────┘
       Sensors            Resilient edge         OT/IT bridge          Insights
```

### 🧠 Synka Core — *Industrial Middleware*

![Status](https://img.shields.io/badge/status-v1.2%20·%20active%20development-2E8B57?style=flat-square)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

The edge of the ecosystem. Connects operational technology to backend services through industrial protocols, keeping data flowing even when the network doesn't — the reliability foundation everything downstream depends on.

- 🔌 **Protocols:** OPC UA · MQTT
- 🛡️ **Resilience:** Store-and-forward buffering, reconnection handling
- ⚙️ **Goal:** A dependable bridge between the plant floor and the cloud

➡️ **[github.com/ViktorWalde/SynkaCore](https://github.com/ViktorWalde/SynkaCore)**

### 🏢 Synka Studio — *Industrial Backend Platform*

![Status](https://img.shields.io/badge/status-v1.0%20·%20active%20development-2E8B57?style=flat-square)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

A Java backend built for industrial environments, providing a clean foundation for MES-style applications and OT/IT integration.

- 🧱 **Architecture:** Clean Architecture · Multi-tenancy
- 🧰 **Stack:** Spring Boot · PostgreSQL · Docker · REST APIs
- ⚙️ **Goal:** A solid, extensible backend for industrial operations

➡️ **[github.com/ViktorWalde/SynkaStudio](https://github.com/ViktorWalde/SynkaStudio)**

### 🔎 Synka Lens — *Industrial Data Engineering & Analytics*

![Status](https://img.shields.io/badge/status-v1.0%20·%20active%20development-2E8B57?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Turns raw telemetry into business information through a layered ETL/ELT pipeline (bronze → silver → gold), with explicit data-quality checks — gap detection, status classification — at every stage before a number ever reaches a dashboard.

- 📊 **Stack:** Python · DuckDB · Parquet · Streamlit
- 🔁 **Pipeline:** Raw telemetry → bronze (raw copy) → silver (cleaned) → gold (metrics) → dashboard
- 🧪 **Quality:** Automated test suite covering domain rules, each transformation layer, and edge cases (data gaps, multiple machines)
- ⚙️ **Goal:** Make industrial data actionable — and trustworthy — for decision-making

➡️ **[github.com/ViktorWalde/SynkaLens](https://github.com/ViktorWalde/SynkaLens)**

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

**Data Engineering**

![ETL/ELT](https://img.shields.io/badge/ETL%2FELT-4479A1?style=flat-square)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=flat-square)

**Industrial / IoT**

![OPC UA](https://img.shields.io/badge/OPC%20UA-0067B1?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![Modbus](https://img.shields.io/badge/Modbus-444444?style=flat-square)
![Industrial IoT](https://img.shields.io/badge/Industrial%20IoT-00979D?style=flat-square)

**Platform & Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ViktorWalde&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ViktorWalde&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</p>

---

## 🌱 Currently Learning

Data Engineering (PySpark · Airflow) · Modern C++ · Embedded Linux (Yocto · QEMU) · Software Architecture

---

## 🎯 Interests

`Data Engineering` · `Industrial Software` · `Embedded Linux` · `Edge Computing` · `AgTech` · `Distributed Systems` · `Industrial IoT` · `Backend Engineering` · `Industrial Automation`

---

## 📫 Get in Touch

<p align="center">
  <a href="https://www.linkedin.com/in/vitor-hugo-da-silva-54359b312/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/ViktorWalde">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
  <a href="mailto:klaushugoruki@gmail.com">
    <img src="https://img.shields.io/badge/Email-Reach%20out-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  📍 <strong>Jaguapitã — Paraná — Brazil</strong>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ViktorWalde&style=flat-square&color=0A66C2" alt="Profile views" />
</p>
