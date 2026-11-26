# Hey, I'm Gninho 👋

Backend-first full-stack engineer. Java / Spring Boot by trade, React when a project needs to work end to end.

I graduated from ENSA Al Hoceima in June 2026. Two internships at TechPal on stacks I'd never used, plus the side projects below.

**Currently:** looking for a full-time Backend or Full-Stack Java role in Casablanca, hybrid or remote.

---

## What I've built

**[Banking Microservices](https://github.com/Gninho-silue/banking-microservices)**: Spring Cloud banking system, extended past the course it started from
Java 21 · Spring Boot 4 · Spring Cloud · Kafka · MySQL · Keycloak · Testcontainers
Idempotent transfers that never debit twice, even under 20 concurrent requests. Events published through a transactional outbox to Kafka. Loan amortization schedule in BigDecimal. 205 tests against real MySQL and Kafka, CI on 7 services. The tests caught a lost-update bug on account balances; the README tells the story.

**[JobPilot](https://jobpilot-jet.vercel.app)**: tailors your CV to each job offer and flags anything your original CV does not support. Next.js, Prisma, Postgres, Groq. Live demo.

**[Cortex](https://cortex-tau-five.vercel.app)**: agentic RAG assistant about my own career
Python · FastAPI · LangGraph · ChromaDB · React
Answers questions from my CVs and recommendation letters, cites the source of every answer, or says it doesn't know. Code is private because it holds my personal documents.

**[DevScope](https://devscope-lake.vercel.app)**: AI GitHub profile analyzer
Next.js 14 · TypeScript · Groq · GitHub REST API
Scores a GitHub profile from 0 to 100, flags stack gaps and suggests matching roles. 31 tests, CI through to Vercel.

**[AgentFlow](https://agentflow-alpha-azure.vercel.app)**: 5-agent data analysis pipeline
Python · FastAPI · LangGraph · Ollama / Groq · React
Planner → FileAgent → CodeAgent → Reporter → Supervisor. Generated code runs in an isolated subprocess and fixes itself from its own tracebacks; every number and ranking in the final report is checked against the computed results. Runs fully local with Ollama; the hosted demo uses Groq.

---

## Stack I actually use

**Backend:** Java 21 · Spring Boot · Spring Cloud · Kafka · Python · FastAPI · Odoo 17  
**Frontend:** React · Next.js · TypeScript  
**Data:** PostgreSQL · MySQL · Redis · MongoDB   
**Testing & infra:** JUnit · Mockito · Testcontainers · Docker · GitHub Actions · Kubernetes manifests / Helm

**Certifications:** Oracle Certified Professional, Java SE 17 · OCI DevOps Professional

---

## The unglamorous part

At TechPal I was handed Odoo and Flutter, two stacks I'd never touched, with real deadlines. I shipped an internship-management ERP the HR team still uses, then a 9-module e-commerce platform with its mobile app. That's the part that doesn't fit in a bullet point.

---

**gninninmaguignonsilue@gmail.com** · [LinkedIn](https://linkedin.com/in/gninema-silue) · [Portfolio](https://silue-dev.vercel.app)
