# Hi, I'm Gaurav 👋

**Final-year B.Tech student in Artificial Intelligence Engineering | Java Backend Developer**

I build backend systems and low-level infrastructure — the kind of code where correctness, memory safety, and measured performance matter more than framework trends. Most of my time goes into Java/Spring Boot services and systems programming in C++.

- 🎓 B.Tech (AI Engineering), G.H. Raisoni College of Engineering, Nagpur — CGPA **8.35**
- 🏅 **NPTEL Elite + Gold**, *Programming in Java* (IIT Kharagpur) — **94%** consolidated score
- 🔭 Currently working on semantic search infrastructure and network packet analysis
- 🌱 Preparing for **GATE CSE 2027** alongside campus placements
- 💼 Open to **Software Engineer / Java Backend Developer** roles
- 📫 Reach me at: `<your-email@example.com>`

---

## 🛠 Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/JPA/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)

**Data & Infrastructure**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

**Frontend & Tooling**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📌 Featured Projects

### 🔍 SemanticDocs — Semantic Document Search & RAG Platform
A full-stack platform for semantic document retrieval, built around a **hand-written HNSW vector index in Java** rather than an off-the-shelf vector database.

- Implemented the HNSW graph index from scratch — layered skip-list navigation, neighbour heuristics, and tunable `ef` search
- Benchmarked **recall@10 = 1.0 at ef=64** with a **7.9× speedup over brute-force** search on 20,000 clustered vectors
- Secured REST API with Spring Security; PostgreSQL for document/chunk storage, Redis for caching
- React + Vite frontend, Flyway-managed schema migrations, Docker-based local setup

**Stack:** Java 17 · Spring Boot · Spring Security · PostgreSQL · Redis · React/Vite · Docker

---

### 📡 FlowScope — Zero-Dependency Deep Packet Inspection Engine
A multi-threaded network traffic analysis engine written in modern C++ with **no external dependencies** — every component implemented from the standard library up.

- **129/129 tests passing**, zero warnings under `-Wall -Wextra`
- Clean under **AddressSanitizer, UndefinedBehaviorSanitizer, and ThreadSanitizer**
- Near-perfect work distribution across 4 worker threads
- Layered architecture separating capture, protocol parsing, flow tracking, and reporting

**Stack:** C++17 · CMake · POSIX threads · Sanitizer-driven testing

---

## 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=GruvDev&show_icons=true&hide_border=true&theme=default" height="160" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GruvDev&layout=compact&hide_border=true&theme=default" height="160" alt="Top languages" />

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/GruvDev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:your-email@example.com)

---

<sub>Currently focused on distributed systems, information retrieval, and low-level performance engineering.</sub>
