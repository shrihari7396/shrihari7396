<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Shrihari%20Kulkarni&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Backend%20Architecture%20%7C%20Security%20%7C%20Distributed%20Systems&descAlignY=60&descColor=a0a0ff&animation=fadeIn" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=7B8CDE&center=true&vCenter=true&width=650&lines=Building+resilient+backend+systems;Security+%7C+Performance+%7C+Scalability;Spring+Boot+%7C+Kafka+%7C+gRPC+%7C+Redis;Architecture+%E2%86%92+Implementation+%E2%86%92+Deployment)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shrihari-kulkarni-467767299/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shrihari7396)
[![Profile Views](https://komarev.com/ghpvc/?username=shrihari7396&label=Profile+Views&color=7B8CDE&style=for-the-badge)](https://github.com/shrihari7396)

<img src="https://img.shields.io/badge/🎯_Open_to_Work-SDE_Backend_%2F_Distributed_Systems-2ea44f?style=for-the-badge"/>

</div>

---

## ⚡ About Me

```yaml
name        : Shrihari Kulkarni
focus       : Backend Architecture · Distributed Systems · Security Engineering
status      : 3rd Year Computer Engineering, PICT (Class of 2027) — actively interviewing for SDE roles
currently   :
  - Building     → SentientGate — AI-powered API security gateway (Kafka + Redis + gRPC)
  - Contributing → Apache DolphinScheduler (Open Source)
  - Sharpening   → System Design · Kubernetes internals · Advanced Spring Security
strengths   :
  - Event-driven microservices: Kafka, gRPC, Redis-backed caching & consistency
  - High-throughput, stateless, production-oriented system design
  - Diagnosing and fixing distributed race conditions & cache-consistency edge cases
philosophy  : Architecture → Implementation → Deployment
highlights  :
  - CGPA        : 9.30
  - CTF Ranking : Top 7% · AICTE National CTF
  - DSA         : 900+ problems solved (LeetCode · Codeforces)
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

### 📡 Messaging & Streaming

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### 🗄️ Distributed Systems & Databases

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
* `Consistency` → Identified and resolved a race condition between Kafka consumer ordering and Redis cache writes using a write-through caching strategy

**Highlights:**

* 🪪 Cryptographically signed Visitor ID tracking for secure client identification
* ⚡ Kafka-based asynchronous threat analysis with fully decoupled security services
* 🎯 Strategy Pattern-driven detection engine for rate abuse, bot activity, and behavioral anomalies
* 🔄 Circuit Breaker optimization to terminate analysis immediately after threat detection
* 🚫 Dynamic Redis-backed blacklisting with configurable time-based enforcement
* 🤖 Ollama/Gemma 3 integration for AI-assisted threat classification when rule-based strategies fail
* 📊 Centralized security logging, SOC dashboard (React/TypeScript), and historical context analysis

![Spring](https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white)

</td>
<td width="50%" valign="top">

### 🥉 [Centralized KYC System](https://github.com/shrihari7396/Centralized-KYC-System)
**Consent-Driven Distributed Identity Platform** `Alpha 🚧`

A microservices-based KYC orchestration system that eliminates redundant verification across institutions while enforcing secure, consent-based data access.

**Key Design Decisions:**
- `Single Source of Truth` → One verified identity reusable across organizations
- `Consent` → Explicit user authorization required before any data access
- `Event-Driven` → Asynchronous communication using Kafka
- `Security` → JWT authentication, OTP-based DigiLocker verification, and encrypted data storage
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

### 🧬 [Heuristic PDF Malware Analyzer](https://github.com/shrihari7396/Pdf-Malware-Detection-System)
**Automated Threat Detection Pipeline**

Static analysis + ML pipeline to classify polymorphic malicious payloads hidden within PDF structures.

**Key Design Decisions:**
- `Innovation` → Custom structural parsers to identify high-entropy object streams in malformed PDFs
- `Accuracy` → XGBoost ensemble model with SHAP-based interpretability for classifying zero-day polymorphic variants
- `Usability` → Streamlit interface for quick, interactive scanning

**Highlights:**
- 🧠 XGBoost classification pipeline with SHAP explainability
- 🔬 Custom PDF structure parser for malformed documents
- 📈 High-entropy stream detection

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
<td width="50%" valign="top">

### 📈 [TradeSense-Algo](https://github.com/shrihari7396)
**Systematic Algorithmic Trading Engine**

An autonomous intraday/swing trading system for NSE/BSE that scores every candidate trade on a weighted, multi-factor model and enforces a hard risk gate before any order goes live.

**Key Design Decisions:**
- `Signal Fusion` → Composite scoring: 30% technical (EMA crossover) · 30% fundamental · 20% sentiment · 20% event-driven
- `Risk Management` → Hard-coded risk gate — 1.5% per-trade stop loss, 3% daily circuit breaker
- `Execution` → OpenAlgo/Zerodha integration for live order routing and TradingView-based charting

**Highlights:**
- 🧠 FinBERT-based sentiment analysis on market-moving news
- 📊 EMA crossover + composite multi-factor signal generation
- 🛑 Automated circuit breaker for capital protection
- 📉 Live order execution via Zerodha with real-time charting

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![FinBERT](https://img.shields.io/badge/FinBERT-NLP-blueviolet?style=flat-square)
![Risk Management](https://img.shields.io/badge/Risk_Gate-Circuit_Breaker-critical?style=flat-square)
![TradingView](https://img.shields.io/badge/TradingView-131722?style=flat-square&logo=tradingview&logoColor=white)

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
