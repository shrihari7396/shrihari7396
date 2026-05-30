<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Shrihari%20Kulkarni&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Backend%20Architecture%20%7C%20Security%20%7C%20Distributed%20Systems&descAlignY=60&descColor=a0a0ff&animation=fadeIn" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=7B8CDE&center=true&vCenter=true&width=600&lines=Building+resilient+backend+systems;Security+%7C+Performance+%7C+Scalability;Spring+Boot+%7C+Kafka+%7C+Distributed+Systems;Architecture+%E2%86%92+Implementation+%E2%86%92+Deployment)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shrihari-kulkarni-467767299/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shrihari7396)
[![Profile Views](https://komarev.com/ghpvc/?username=shrihari7396&label=Profile+Views&color=7B8CDE&style=for-the-badge)](https://github.com/shrihari7396)

</div>

---

## ⚡ About Me

```yaml
name        : Shrihari Kulkarni
focus       : Backend Architecture · Security Engineering · Distributed Systems
currently   :
  - Building  → Centralized KYC Verification System
  - Contributing → Apache DolphinScheduler (Open Source)
  - Learning  → Advanced Spring Security · Kubernetes · AWS/GCP · System Design
strengths   :
  - Core backend layers: auth, authorization, logging, monitoring, service integration
  - High-throughput, stateless, production-oriented system design
philosophy  : Architecture → Implementation → Deployment
highlights  :
  - CGPA        : 9.30
  - CTF Ranking : Top 7% · AICTE National CTF
  - DSA         : 850+ algorithmic problems solved
```

---

## 💻 Tech Stack

### 🔷 Core Backend & Frameworks

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### 🗄️ Distributed Systems & Databases

![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-0089D6?style=for-the-badge&logo=hyperledger&logoColor=white)

### 🔐 Security & DevOps

![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![OAuth2](https://img.shields.io/badge/OAuth2-00599C?style=for-the-badge&logo=openid&logoColor=white)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">
  
### 🛡️ [SentientGate](https://github.com/shrihari7396/SentientGate)

**AI-Powered Security API Gateway**

A stateless, high-throughput security gateway that detects and mitigates malicious traffic in real time using an event-driven architecture, enforcing gateway-level protection before requests reach backend services.

**Key Design Decisions:**

* `Problem` → Detect and block malicious clients without increasing request-path latency or consuming backend resources
* `Solution` → Fire-and-forget Kafka event pipeline with Redis-backed blacklist enforcement, Strategy Pattern-based threat detection, and AI-assisted analysis

**Highlights:**

* 🪪 Cryptographically signed Visitor ID tracking for secure client identification
* ⚡ Kafka-based asynchronous threat analysis with fully decoupled security services
* 🎯 Strategy Pattern-driven detection engine for rate abuse, bot activity, and behavioral anomalies
* 🔄 Circuit Breaker optimization to terminate analysis immediately after threat detection
* 🚫 Dynamic Redis-backed blacklisting with configurable time-based enforcement
* 🤖 Ollama LLM integration for AI-assisted threat classification when rule-based strategies fail
* 📊 Centralized security logging and historical context analysis

![Spring](https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=flat-square\&logo=spring\&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square\&logo=apache-kafka\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square\&logo=redis\&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square\&logo=docker\&logoColor=white)


</td>
<td width="50%" valign="top">

### 🥉 [Centralized KYC System](https://github.com/shrihari7396/Centralized-KYC-System)
**Consent-Driven Distributed Identity Platform** `Alpha 🚧`

A microservices-based KYC orchestration system that eliminates redundant verification across institutions while enforcing secure, consent-based data access.

**Key Design Decisions:**
- `Single Source of Truth` → One verified identity reusable across organizations
- `Consent` → Explicit user authorization required before any data access
- `Event-Driven` → Asynchronous communication using Kafka
- `Security` → JWT authentication, RBAC, and encrypted data storage
- `Lifecycle` → Automated renewal, revocation, and update workflows

**Highlights:**
- 🔐 Consent-based identity sharing with strict access control
- ⚡ Event-driven microservices using Apache Kafka
- 🏛️ Multi-institution KYC orchestration
- 📊 Strong data governance and trust boundary enforcement

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-D82C20?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [NEXUS: Architecture Intelligence Platform](https://github.com/shrihari7396/Today_Project)
**AI-Powered Repository Understanding & Architecture Visualization System**

Intelligent codebase analysis platform that accepts Git repository URLs, performs AST-driven source code analysis, constructs dependency graphs, and enables natural-language interaction with complete software architectures.

**Key Design Decisions:**
- `Architecture Mapping` → AST-based parsing to identify file dependencies, imports, and structural relationships
- `Knowledge Retrieval` → RAG pipeline for repository-wide semantic search and architecture-aware question answering
- `Visualization` → Interactive dependency graph generation for large-scale codebase exploration

**Highlights:**
- 🔍 Automated Git repository cloning and codebase indexing
- 🌐 Interactive file-to-file dependency graph visualization
- 🧠 RAG-powered architecture intelligence and repository Q&A
- 📂 File location tracing, dependency discovery, and workflow explanation
- ⚡ FastAPI backend integrated with Anthropic AI for contextual code understanding

**Demo:**  
🔗 https://drive.google.com/drive/folders/1FaOFA_c6KlkVEYwn5Hyu9Hnfw-ba03CM?usp=sharing

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_AI-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Pipeline-blue?style=flat-square)</td>
<td width="50%" valign="top">

### 🧬 [Heuristic PDF Malware Analyzer](https://github.com/shrihari7396/Pdf-Malware-Detection-System)
**Automated Threat Detection Pipeline**

Static analysis + ML pipeline to classify polymorphic malicious payloads hidden within PDF structures.

**Key Design Decisions:**
- `Innovation` → Custom structural parsers to identify high-entropy object streams in malformed PDFs
- `Accuracy` → XGBoost ensemble model for classifying zero-day polymorphic variants

**Highlights:**
- 🧠 XGBoost + TensorFlow classification pipeline
- 🔬 Custom PDF structure parser for malformed documents
- 📈 High-entropy stream detection

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)

</td>
</tr>
</table>

---

## 🛠️ Open Source Contributions

### [Apache DolphinScheduler](https://github.com/apache/dolphinscheduler) — *Systems Contributor*

> A distributed and extensible visual workflow task scheduling platform. ⭐ 11k+ GitHub Stars

| Area | Contribution |
|------|-------------|
| 🔧 **Core Engine** | Engineering workflow engine modules and integration pipelines for distributed visual DAG task scheduling |
| 🧪 **Testing** | Architecting fault-tolerant test suites covering edge-case timeout scenarios in Dockerized environments |
| ✅ **Database Assertions** | Strengthened database assertion logic to improve test reliability across distributed execution contexts |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=shrihari7396&theme=tokyonight&hide_border=true&border_radius=8" height="170"/>

<br/><br/>
</div>

---

## 📈 Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=shrihari7396&theme=tokyo-night&hide_border=true&radius=8" width="100%"/>
</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer&animation=fadeIn" />

*"Building secure, observable, and resilient systems — one layer at a time."*

</div>
