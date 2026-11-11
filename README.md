<div align="center">

# 🚀 Learning Journey: Zero to AI Application Developer

**A 44-week, build-in-public path from programming fundamentals to GenAI engineering.**

![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![Current Week](https://img.shields.io/badge/current%20week-1%20of%2044-blue)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)

[Roadmap](#-roadmap) · [Projects](#-projects) · [Progress](#-progress-tracker) · [Repo Structure](#-repository-structure) · [Resources](#-resources-i-use) · [Connect](#-connect)

</div>

---

## 👋 About This Repository

Hi, I'm **Lekhan**. This repo is my public learning log. Every exercise, mini project, note, and weekly review lives here, so my progress is visible, honest, and measurable.

**Goal:** become a job-ready **AI Application Developer** (Java/Python full stack + LLM applications), then grow toward **GenAI Engineer**, and land a role at a product-based company.

**Why public?** Accountability, a record of real work instead of certificates, and a reference I can come back to.

---

## 🎯 How I'm Learning

1. **Learn → Build → Ship.** Every phase ends with a working project.
2. **No copy-paste solutions.** I type everything myself. Struggling is part of learning.
3. **60% building, 40% studying.**
4. **Small, meaningful commits** at least 4 days a week.
5. **Weekly review** every Sunday: what I learned, what confused me, what's next.
6. **DSA runs in parallel** throughout the whole journey.

~20 hours a week · ~44 weeks · free resources only.

---

## 🗺 Roadmap

| Phase | Weeks | Focus | Project |
|:-:|:-:|---|---|
| 1 | 1–8 | Programming foundations: Java, Python, Git, Linux, SQL, web basics | Small CLI apps |
| 2 | 9–20 | Full stack: HTML/CSS/JS/TS, React, Spring Boot, MySQL, JWT | **Project 1** |
| 3 | 21–28 | Python backend, AI foundations, LLM APIs, RAG | **Project 2** |
| 4 | 29–36 | Agents, tool calling, MCP, evaluation | **Project 3** |
| 5 | 37–44 | Docker, AWS, CI/CD, system design | **Project 4** |
| 6 | 45+ | Real-world projects and job applications | Invoice/GST automation and more |

### Tech stack (planned)

| Area | Tools |
|---|---|
| Languages | Java, Python, JavaScript, TypeScript, SQL |
| Frontend | HTML5, CSS3, React, Tailwind CSS |
| Backend | Spring Boot, Spring Security (JWT), Hibernate/JPA, FastAPI |
| Databases | MySQL, PostgreSQL, Redis, vector DBs (Chroma, pgvector, Qdrant) |
| AI / GenAI | LLM APIs (Claude and others), embeddings, RAG, LangGraph, MCP, RAGAS, Langfuse |
| DevOps / Cloud | Git, Docker, GitHub Actions, AWS (IAM, EC2, S3, RDS, ECS) |
| Practice | DSA on LeetCode, OWASP Top 10, system design basics |

---

## 🛠 Projects

Each project lives in its **own repository** (linked below) so it can be reviewed like real work. This repo holds the learning around them.

### Phase projects

| # | Project | Stack | Status | Links |
|:-:|---|---|:-:|---|
| 1 | **Inventory and Billing App**: JWT login, roles, products, customers, bills | React · Spring Boot · MySQL | ⬜ Not started | _coming soon_ |
| 2 | **RAG Chatbot over my own PDFs**: citations, measured accuracy across configurations | FastAPI · vector DB · LLM API | ⬜ Not started | _coming soon_ |
| 3 | **Business AI Agent**: web search, read-only SQL, email with human approval | Function calling · LangGraph · MCP | ⬜ Not started | _coming soon_ |
| 4 | **AI Business Assistant Platform (capstone)**: deployed on AWS, CI/CD, evaluation dashboard | Docker · AWS · GitHub Actions | ⬜ Not started | _coming soon_ |

> The four projects are designed to **stack into one product**: Project 1's data feeds Project 3's agent, Project 2 becomes a tool inside it, and Project 4 deploys everything together.

### After the learning phases

- [ ] AI Invoice and GST Processing Automation
- [ ] Secure Text-to-SQL Analytics Agent
- [ ] AI Customer Support Copilot
- [ ] _(optional)_ COD Return Predictor / Security Operations Assistant

**Status key:** ⬜ Not started · 🟨 In progress · ✅ Done

---

## 📈 Progress Tracker

### Phase checklist

- [ ] **Phase 1:** Foundations (Weeks 1–8)
- [ ] **Phase 2:** Full stack + Project 1 (Weeks 9–20)
- [ ] **Phase 3:** AI foundations + RAG + Project 2 (Weeks 21–28)
- [ ] **Phase 4:** Agents + Project 3 (Weeks 29–36)
- [ ] **Phase 5:** Cloud + DevOps + Project 4 (Weeks 37–44)
- [ ] **Phase 6:** Real-world projects + applications (Week 45+)

### Weekly log

| Week | Focus | Output | Notes |
|:-:|---|---|:-:|
| 1 | Setup, Java basics, Git, terminal, Python intro | Number guessing game (Java + Python) | [📝](week-01/NOTES.md) |
| 2 | _Java OOP, SQL basics_ | _planned_ | |
| 3 | | | |
| 4 | | | |

_(Rows get added as the weeks go by.)_

### DSA tracker

| Topic | Target | Solved |
|---|:-:|:-:|
| Arrays and strings | 30 | 0 |
| Hashing | 15 | 0 |
| Two pointers / sliding window | 20 | 0 |
| Stacks and queues | 15 | 0 |
| Linked lists | 15 | 0 |
| Trees | 25 | 0 |
| Binary search | 15 | 0 |
| Graphs | 25 | 0 |
| Heaps | 10 | 0 |
| Dynamic programming | 25 | 0 |

---

## 📁 Repository Structure

```text
learning-journey/
├── README.md
├── week-01/
│   ├── java/              # Java exercises
│   ├── python/            # Python exercises
│   └── NOTES.md           # weekly review
├── week-02/
│   └── ...
├── dsa/
│   ├── arrays/
│   ├── strings/
│   └── ...                # problem solutions grouped by topic
├── notes/                 # concept notes (HTTP, JWT, embeddings, RAG, ...)
└── resources/             # useful links and cheat sheets
```

### Conventions

- **Folders:** `week-XX/language-or-topic`
- **Commit messages:** short and meaningful, such as `Add prime checker exercise` or `Fix off-by-one in array reversal`
- **Every week ends with** a `NOTES.md` covering what I learned, what confused me, and what I'd explain differently

---

## ▶️ Running the Code

**Java** (JDK 17 or newer)

```bash
cd week-01/java
javac Main.java
java Main
```

**Python** (3.10 or newer)

```bash
cd week-01/python
python main.py
```

---

## 📚 Resources I Use

| Topic | Resource |
|---|---|
| Java | University of Helsinki Java Programming MOOC · Telusko · Java Brains |
| Python | Harvard CS50P |
| Git | Pro Git book |
| Linux | Linux Journey |
| SQL | SQLBolt |
| Web | freeCodeCamp · The Odin Project · MDN · react.dev |
| Spring Boot | spring.io/guides · Amigoscode · Baeldung |
| LLMs and RAG | Hugging Face LLM Course · DeepLearning.AI short courses · Microsoft Generative AI for Beginners |
| Agents and MCP | Hugging Face Agents Course · LangChain Academy · Anthropic Academy |
| Cloud and DevOps | AWS Skill Builder · Docker docs · TechWorld with Nana |
| DSA | NeetCode · Striver's A2Z · LeetCode |
| Security | OWASP Top 10 · OWASP Top 10 for LLM Apps · PortSwigger Web Security Academy |

---

## 🏁 Milestones

- [ ] First 8 weeks done: foundations solid
- [ ] Project 1 live
- [ ] Project 2 with measured accuracy table
- [ ] Project 3 with agent success-rate report
- [ ] Project 4 deployed on AWS with CI/CD and evaluation dashboard
- [ ] 300+ DSA problems solved
- [ ] First product-company interview
- [ ] First offer 🎉

---

## 🤝 Connect

I'm learning in public, and feedback, code reviews, and study partners are welcome.

- **LinkedIn:** [Lekhan](https://www.linkedin.com/in/lekhan-sagar/)
- **GitHub:** [@lekhan-03](https://github.com/lekhan-03)
- **Email:** lekhandayananda@gmail.com

If this repo helps you, give it a ⭐ and follow along.

---

<div align="center">

_"Consistency beats intensity. One commit a day adds up."_

</div>
