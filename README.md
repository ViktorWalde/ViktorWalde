<p align="center">
  <img
    src="./assets/wallpaperPyshicsAmbient.png"
    alt="Vitor Hugo da Silva — development workspace"
    width="100%"
  />
</p>

<h1 align="center">Vitor Hugo da Silva</h1>

<p align="center">
  <strong>Java Backend Developer · Spring Boot · Angular · Linux</strong>
</p>

<p align="center">
  Backend-first full-stack development — Java and Spring as the core, Angular as the frontend complement.
</p>

<p align="center">
  <code>Java</code> •
  <code>Spring Boot</code> •
  <code>Angular</code> •
  <code>TypeScript</code> •
  <code>Linux</code> •
  <code>PostgreSQL</code> •
  <code>Docker</code> •
  <code>Industrial Systems &amp; IoT</code>
</p>

<p align="center">
  <a href="https://github.com/ViktorWalde">
    <img
      src="https://img.shields.io/badge/GitHub-ViktorWalde-181717?style=for-the-badge&logo=github"
      alt="GitHub"
    />
  </a>
  <a href="https://www.linkedin.com/in/vitor-hugo-da-silva-54359b312/">
    <img
      src="https://img.shields.io/badge/LinkedIn-Vitor%20Hugo%20da%20Silva-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"
      alt="LinkedIn"
    />
  </a>
  <a href="mailto:klaushugoruki@gmail.com">
    <img
      src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"
      alt="Email"
    />
  </a>
  <img
    src="https://img.shields.io/badge/Location-Paraná,%20Brazil-2E8B57?style=for-the-badge&logo=googlemaps&logoColor=white"
    alt="Location: Paraná, Brazil"
  />
</p>

---

## About Me

I'm a **Software Developer from Brazil** focused primarily on **backend development with Java and Spring**.

My strongest area is designing and implementing backend systems: domain models, REST APIs, authentication, persistence, integrations, automated tests and containerized execution on Linux.

I use **Angular and TypeScript** as the frontend complement to my Java work, allowing me to build complete applications while maintaining backend engineering as my main specialization.

Industrial systems and IoT are application domains in my portfolio rather than hardware-centered career paths. Through the **Synka ecosystem**, I explore how Java backend systems can collect, protect, process and expose operational data reliably.

> I aim to build software that is understandable, testable, observable and resilient under real operating conditions.

---

## Career Focus

My professional direction is centered on:

* Java backend development
* Spring Boot and the Spring ecosystem
* Backend-first full-stack development with Angular
* REST APIs and system integrations
* Authentication and authorization
* Relational data modeling
* Automated and integration testing
* Linux-based development and deployment
* Containerized applications
* Industrial and IoT software integration

### Target Roles

* Java Backend Developer
* Spring Boot Developer
* Java Software Developer
* Java and Angular Developer
* Backend-first Full-Stack Developer
* Backend Developer for industrial or IoT systems

---

## The Synka Ecosystem

**Synka** is an open-source software ecosystem for backend development, industrial integration, operational management and analytics.

Each project has an independent responsibility while contributing to the same operational flow.

```mermaid
flowchart LR
    DEVICES["Devices, sensors and OT data"]

    CORE["Synka Core<br/>Java integration middleware"]

    TELEMETRY[("TimescaleDB<br/>Telemetry")]

    LENS["Synka Lens<br/>Operational analytics"]

    USERS["Operators and managers"]

    STUDIO_API["Synka Studio Backend<br/>Java + Spring Boot"]

    STUDIO_WEB["Synka Studio Frontend<br/>Angular + TypeScript"]

    OPERATIONS[("PostgreSQL<br/>Operations")]

    DEVICES --> CORE
    CORE --> TELEMETRY
    TELEMETRY --> LENS

    USERS --> STUDIO_WEB
    STUDIO_WEB --> STUDIO_API
    STUDIO_API --> OPERATIONS

    classDef java fill:#2b2b2b,stroke:#ed8b00,color:#ffffff;
    classDef angular fill:#2b2b2b,stroke:#dd0031,color:#ffffff;
    classDef python fill:#2b2b2b,stroke:#3776ab,color:#ffffff;
    classDef database fill:#2b2b2b,stroke:#4169e1,color:#ffffff;

    class CORE,STUDIO_API java;
    class STUDIO_WEB angular;
    class LENS python;
    class TELEMETRY,OPERATIONS database;
```

---

## Featured Projects

### Synka Studio — Full-Stack Industrial Platform

![Status](https://img.shields.io/badge/status-active%20development-2E8B57?style=flat-square)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square\&logo=angular\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)

A full-stack platform for MES-style industrial applications, built with a **Java and Spring Boot backend** and an **Angular frontend**.

Synka Studio is my primary portfolio project for demonstrating professional backend development together with the ability to deliver complete web applications.

**Backend**

* Java and Spring Boot
* Clean Architecture
* Multi-module Maven project
* REST APIs
* Spring Security and JWT
* Multi-tenant data isolation
* Spring Data JPA and Hibernate
* PostgreSQL and Flyway
* JUnit and Testcontainers
* Docker and Docker Compose

**Frontend**

* Angular
* TypeScript
* Component-based user interface
* REST API integration
* Authentication and authorization flows
* Forms and data validation
* Operational and administrative screens
* Responsive web interface

**Main responsibility:** Java backend architecture and implementation.

**Frontend role:** Angular as the presentation and application interface for the Java backend.

➡️ **[github.com/ViktorWalde/SynkaStudio](https://github.com/ViktorWalde/SynkaStudio)**

---

### Synka Core — Resilient Java Integration Middleware

![Status](https://img.shields.io/badge/status-v1.2%20·%20active-2E8B57?style=flat-square)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-593DF7?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)

A Java middleware for collecting, normalizing, persisting and exposing industrial telemetry.

Synka Core applies backend engineering concepts to continuous integration workloads, including fault tolerance, local buffering, database recovery and operational observability.

**Highlights**

* Java and Spring Boot multi-module architecture
* Domain-oriented architecture
* Continuous data-collection worker
* REST API for telemetry access
* PostgreSQL and TimescaleDB
* SQLite store-and-forward buffer
* Circuit breaker, retry and timeout
* Resilience4j
* OPC UA integration with Eclipse Milo
* Health checks and structured logging
* JUnit, Mockito and Testcontainers
* Docker-based infrastructure

➡️ **[github.com/ViktorWalde/SynkaCore](https://github.com/ViktorWalde/SynkaCore)**

---

### Synka Lens — Supporting Analytics Project

![Status](https://img.shields.io/badge/status-v1.0%20·%20active-2E8B57?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square\&logo=duckdb\&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square\&logo=streamlit\&logoColor=white)

A read-only analytics application that transforms industrial time-series data into operational metrics.

Synka Lens complements my Java portfolio by demonstrating how data generated by backend and integration systems can be validated, transformed and presented.

**Highlights**

* Python data pipeline
* TimescaleDB as the source
* Bronze, silver and gold transformation layers
* DuckDB and Parquet
* Data-quality validation
* Gap detection
* Operational metrics
* Streamlit dashboard
* Automated tests

➡️ **[github.com/ViktorWalde/SynkaLens](https://github.com/ViktorWalde/SynkaLens)**

---

## Technical Stack

### Primary — Java Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square\&logo=springsecurity\&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square\&logo=hibernate\&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square\&logo=apachemaven\&logoColor=white)

* Java
* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate
* Maven
* REST APIs
* JWT authentication
* Clean Architecture
* Modular monoliths
* Background workers
* System integrations

### Full-Stack Complement — Angular

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square\&logo=angular\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)

* Angular
* TypeScript
* HTML
* CSS
* Components and services
* Reactive forms
* REST API consumption
* Route protection
* Authentication flows
* Administrative interfaces

### Databases and Persistence

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-593DF7?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square\&logo=sqlite\&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square\&logo=flyway\&logoColor=white)

* PostgreSQL
* TimescaleDB
* SQLite
* SQL
* JPA and Hibernate
* Flyway migrations
* Relational data modeling
* Time-series data

### Testing and Software Quality

![JUnit](https://img.shields.io/badge/JUnit%205-25A162?style=flat-square\&logo=junit5\&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square\&logo=docker\&logoColor=white)

* JUnit 5
* Mockito
* Testcontainers
* Unit tests
* Integration tests
* End-to-end backend tests
* Static analysis
* Reproducible builds
* Architecture boundaries

### Platform and Delivery

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)

* Linux-first development
* Docker
* Docker Compose
* Git and GitHub
* GitHub Actions
* Containerized databases
* CI-oriented workflows
* Application configuration

### Industrial Systems and IoT

![OPC UA](https://img.shields.io/badge/OPC%20UA-0067B1?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square\&logo=mqtt\&logoColor=white)
![Industrial IoT](https://img.shields.io/badge/Industrial%20IoT-00979D?style=flat-square)

* OPC UA
* MQTT
* Industrial telemetry
* OT/IT integration
* Store-and-forward
* Fault-tolerant ingestion
* Edge-to-backend communication
* Operational observability

### Supporting Data Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square\&logo=duckdb\&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square\&logo=streamlit\&logoColor=white)

Python is a supporting technology in my portfolio, used primarily for analytics, data validation and transformation pipelines around Java-based systems.

---

## Currently Developing

* Advanced Java and Spring architecture
* Secure REST APIs
* Angular applications integrated with Spring Boot
* Authentication and authorization flows
* PostgreSQL modeling and migrations
* JUnit and Testcontainers
* Docker-based deployment
* System observability
* Resilient integration services
* Industrial and IoT backend applications

---

## Professional Interests

`Java Backend` ·
`Spring Boot` ·
`Angular` ·
`TypeScript` ·
`Software Architecture` ·
`API Design` ·
`PostgreSQL` ·
`Linux` ·
`Docker` ·
`Distributed Systems` ·
`Industrial Systems` ·
`IoT Integration`

---

## GitHub Activity

<p align="center">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api?username=ViktorWalde&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"
    alt="Vitor Hugo's GitHub statistics"
  />
</p>

---

## Get in Touch

<p align="center">
  <a href="https://www.linkedin.com/in/vitor-hugo-da-silva-54359b312/">
    <img
      src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"
      alt="Connect on LinkedIn"
    />
  </a>
  <a href="https://github.com/ViktorWalde">
    <img
      src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github"
      alt="Follow on GitHub"
    />
  </a>
  <a href="mailto:klaushugoruki@gmail.com">
    <img
      src="https://img.shields.io/badge/Email-Reach%20out-D14836?style=for-the-badge&logo=gmail&logoColor=white"
      alt="Contact by email"
    />
  </a>
</p>

<p align="center">
  <strong>Paraná — Brazil</strong>
</p>
