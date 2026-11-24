# Huzaifa Nabeel

Java full stack developer in the Dallas–Fort Worth area. I graduated from UT Dallas in December 2025 with a B.S. in Software Engineering and I'm currently going through Revature's full stack program.

My day-to-day stack is Spring Boot, Angular, and PostgreSQL. I also like the infrastructure side of things, which is why there's a Kubernetes cluster running in my house.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-SHNabeel-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/SHNabeel)
[![Email](https://img.shields.io/badge/Email-shn3501@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:shn3501@gmail.com)

---

## Things I've built

### Bank of CLI: full stack banking app
Started as a Java console app in Revature training, then grew into a team project with an Angular frontend, a Spring Boot REST API, and PostgreSQL on AWS RDS.

- Login and registration with client-side validation and CSRF-protected auth (session-based, no JWT)
- Backend split into API / Service / DAO layers, with JDBC and atomic transactions so money movements either fully happen or don't happen at all
- JUnit tests, and everything went through GitHub pull requests

**Stack:** Java, Spring Boot, Angular, TypeScript, PostgreSQL, AWS RDS, JUnit

### Godot Docs Chatbot
Ask a question about the Godot game engine and get an answer with links back to the docs it came from.

- Indexed 1,600+ documentation pages (roughly 30,000 chunks) into ChromaDB, chunked by HTML headers so sections stay intact
- Sentence-Transformers embeddings for semantic search, an LLM via OpenRouter for the answers, and source citations returned with each response
- FastAPI backend, Angular frontend
- Wrote a 32-question retrieval eval to check whether the right pages were actually being found, plus pytest tests

**Stack:** Python, LangChain, FastAPI, ChromaDB, Angular

### Secure IVAI: LLM security testing (Aug–Dec 2025)
My internship project. I led a team of six building a platform that tests how well LLMs hold up against the OWASP vulnerability categories. We ran 10 HuggingFace models through 10 categories.

- Python services that automated vulnerability detection and compliance checks, which cut manual analysis time by about 50%
- Three PostgreSQL schemas and data pipelines for test results and audit logs
- Git branching and CI/CD set up for the team, with no broken deployments over the whole project

### Homelab Kubernetes cluster
A 3-node K3s cluster on my own hardware, built mostly because I wanted to understand Kubernetes by running it instead of reading about it. It hosts DNS filtering, a media server, photo management, and file storage, deployed with Deployments, Services, and persistent volumes.

---

## What I work with

| | |
|---|---|
| **Back end** | Java, Spring Boot, REST APIs, JDBC, Maven, JUnit, SLF4J |
| **Front end** | Angular, TypeScript, JavaScript, HTML |
| **Data** | PostgreSQL, MySQL, AWS RDS |
| **Infra & tools** | Docker, Kubernetes (K3s), AWS, Git, GitHub, Jira, IntelliJ, VS Code |
| **Also** | Python, LangChain, Node.js |

I use Claude Code day to day for debugging, boilerplate, and writing tests, and I read and understand everything it writes before it goes in.

---

## Background

B.S. Software Engineering, University of Texas at Dallas (2023–2025). Coursework leaned toward algorithms, databases, cybersecurity, and machine learning.

## Get in touch

I'm looking for Engineering roles, and I'm happy to talk about backend, DevOps, or security-leaning work too. LinkedIn or email is the easiest way to reach me!
