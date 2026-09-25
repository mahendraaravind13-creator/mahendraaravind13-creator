# Kuppannagari Mahendra Aravind


<p align="center">
  <a href="https://www.linkedin.com/in/mahendra-aravind-128a0a28a/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:mahendraaravind13@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/mahendraaravind13-creator">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
</p>

---

## About

I'm a fourth-year B.Tech student at **The LNM Institute of Information Technology (LNMIIT)** focused on backend engineering and AI-powered systems.

I enjoy designing systems that combine:

- High-performance backend services
- Distributed and event-driven architectures
- AI/LLM integrations
- Retrieval-Augmented Generation (RAG)
- Secure and scalable APIs
- Cloud deployment and automation

Currently focused on **Java, Spring Boot, system design, and AI engineering**.

---

## Technical Stack

### Languages

`Java` `Python` `JavaScript` `SQL`

### Backend & Architecture

`Spring Boot` `Spring Security` `Hibernate/JPA`  
`FastAPI` `REST APIs` `Flyway`  
`Apache Kafka` `Redis`

### AI Engineering

`RAG Pipelines` `Vector Search` `LLM Integration`  
`Gemini` `Groq` `Qdrant` `TensorFlow/Keras`

### Frontend

`React.js` `Next.js` `HTML` `CSS` `Tailwind CSS`

### Cloud & DevOps

`AWS EC2` `Docker` `GitHub Actions` `Postman` `Git`

### Databases

`PostgreSQL` `MySQL` `Redis` `Qdrant`

---

# Featured Work

## Project Atlas

### AI Project Intelligence Platform

**Python · FastAPI · PostgreSQL · Qdrant · Docker · AWS**

An AI-powered platform designed to trace specification deviations through their downstream impact on procurement, schedules, and commissioning.

**Highlights**

- Hybrid RAG using dense retrieval + BM25
- Rank fusion and cross-encoder reranking
- Citation verification down to document, page and clause
- Per-project RBAC
- 222 backend tests
- Dockerized AWS deployment
- Automated CI/CD using GitHub Actions

**Finalist — Economic Times AI Hackathon 2.0**

---

## PulseOps

### Multi-Tenant Monitoring & Incident Management Platform

**Java · Spring Boot · Kafka · PostgreSQL · Redis · React · Docker · AWS**

Agents push host metrics, server-side alert rules evaluate them over sliding windows, and incidents open, deduplicate and resolve themselves. [Live demo](https://pulseops.atlas-theproject.duckdns.org)

**Highlights**

- Kafka ingestion with partition keys, consumer groups and a dead-letter topic
- Exactly one active incident per service and rule, enforced by a PostgreSQL partial unique index
- Composite index cut rule-window queries from 69.8 ms to 0.29 ms on 2M rows
- Redis API-key cache and per-tenant rate limiting
- Two stateless replicas behind nginx; 30/30 requests served during a failover test
- Gemini root-cause suggestions and post-mortem drafts, kept off the critical path
- 37 backend tests, including Testcontainers integration tests

---

## UAV ISAC Scheduling (Research)

### Learning MILP-Optimal Sensing & Communication Scheduling

**Python · TensorFlow/Keras · MATLAB (MILP) · Numba**

A Conv3D-LSTM that imitates a MILP optimiser deciding, at each of 15 waypoints, whether a UAV senses, communicates or does both. [Repository](https://github.com/mahendraaravind13-creator/uav-isac-milp-cnn-lstm-)

- 66K+ MILP-labelled trajectories (1M+ rows) from a randomised dataset generator
- **92.9% per-waypoint test accuracy** on 60,690 unseen trajectories, vs 86.5% for a CNN baseline
- Joint-mode recall raised from 41% to 75%
- Manuscript prepared for submission to IEEE VTC

---

# Engineering Interests

```text
Backend Engineering       ████████████████████
Java / Spring Boot        ███████████████████░
AI Engineering            ██████████████████░░
Distributed Systems       ████████████████░░░░
System Design             ███████████████░░░░░
Cloud & DevOps            ██████████████░░░░░░
