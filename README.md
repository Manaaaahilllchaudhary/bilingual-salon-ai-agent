#  Bilingual AI Salon Assistant

A production-ready AI Salon Assistant built with **n8n**, **Groq LLM**, **Redis Memory**, **RAG (Retrieval-Augmented Generation)**, and **Docker**.

This project is part of my AI Agent Engineering journey and is being developed following professional software engineering and Git best practices.

---

#  Features

-  AI Salon Receptionist
-  Bilingual Support (English & Urdu)
- Conversational Memory (Redis)
-  Knowledge Base using RAG
-  Semantic Search with Embeddings
-  Markdown Knowledge Base
-  Dockerized Deployment
- Version Controlled with Git & GitHub

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | AI Workflow Automation |
| Groq | Large Language Model |
| Redis | Conversation Memory |
| Hugging Face Embeddings | Text Embeddings |
| Simple Vector Store | Knowledge Retrieval |
| Docker | Containerization |
| Git & GitHub | Version Control |

---

# 📂 Project Structure

```text
bilingual-salon-ai-agent/

├── workflows/
│   ├── bilingual-salon-ai-agent.json
│   └── knowledge-upload-workflow.json
│
├── prompts/
│   └── system-prompt.md
│
├── knowledge-base/
│   └── salon-info.md
│
├── docs/
├── screenshots/
├── demos/
├── assets/
│
├── PROJECT_LOG.md
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

#  Architecture

```
Customer
      │
      ▼
Chat Trigger
      │
      ▼
AI Agent
      │
 ┌───────────────┐
 │ Groq Chat     │
 │ Redis Memory  │
 │ Vector Search │
 └───────────────┘
      │
      ▼
Knowledge Base
      │
      ▼
Final Response
```

---

#  Current Capabilities

- Answer salon-related questions
- Use conversational memory
- Retrieve information from a knowledge base
- Support Urdu and English conversations
- Refuse unrelated questions politely
- Reduce hallucinations using RAG

---

#  Project Progress

## Phase 1 — Foundation

- Git
- GitHub
- Docker
- Docker Compose
- n8n
- Groq LLM
- Redis Memory
- AI Personality
- System Prompt

Completed 

---

##  Phase 2 — RAG

Completed

- Knowledge Upload Workflow
- Markdown Knowledge Base
- Hugging Face Embeddings
- Simple Vector Store
- Retrieval Testing
- Prompt Guardrails

In Progress

- Multi-document Knowledge Base
- Advanced Retrieval

---

##  Upcoming Phases

### Phase 3

- Qdrant Vector Database
- PDF Knowledge
- Website Crawling
- Multiple Knowledge Sources

### Phase 4

- Google Calendar
- Gmail
- WhatsApp Integration
- Instagram Integration
- Website Chat Widget

### Phase 5

- PostgreSQL
- MCP
- Voice AI
- Monitoring
- Production Deployment

### Phase 6

- AI Agent Agency
- Portfolio
- Client Templates
- SaaS Architecture

---

#  Running the Project

```bash
docker compose up -d
```

Open:

```
http://localhost:5678
```

---

#  Backup Strategy

Every major milestone includes:

- Export latest n8n workflows
- Save workflow JSON files
- Commit meaningful changes
- Push to GitHub

---

#  Learning Goals

This project is helping me learn:

- AI Agent Engineering
- n8n Automation
- Prompt Engineering
- Retrieval-Augmented Generation (RAG)
- Docker
- Git & GitHub
- Software Architecture
- Professional Documentation
- AI Deployment

---

#  Future Vision

The long-term goal is to transform this project into a reusable production-ready AI Agent template for future clients and eventually build an AI Agent Agency.

---

#  License

This project is currently being developed for educational, portfolio, and future commercial purposes.
