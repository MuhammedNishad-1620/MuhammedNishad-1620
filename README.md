# Muhammed Nishad

**AI Engineer · LLMs · RAG · Agentic Systems**

📍 Bangalore, India &nbsp;·&nbsp; 🎓 MSc Big Data Analytics, St. Joseph's University &nbsp;·&nbsp; 🟢 Open to AI Engineering roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammednishad1620/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MuhammedNishad-1620)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:muhammednishad1620@gmail.com)

---

I build **production-grade AI systems** — not demos. My work spans LLM pipelines, retrieval-augmented generation, and multi-step agentic workflows that are observable, reliable, and deployable. I've shipped RAG systems with hybrid retrieval strategies, agentic travel planners using LangGraph, NLP interfaces over enterprise knowledge graphs, and anomaly detection systems for medical triage. I care deeply about **hallucination control, system design, and the gap between "it works in a notebook" and "it works in production."**

---

## 🛠 Technical Skills

| Area | Tools & Technologies |
|---|---|
| **LLM & Agents** | LangChain, LangGraph, LlamaIndex, Groq, OpenAI API, Hugging Face |
| **ML & Deep Learning** | PyTorch, Transformers, BERT, YOLOv8, LSTM |
| **Data & Infra** | FAISS, Neo4j, MongoDB, Docker, AWS, RabbitMQ |
| **Languages & Tools** | Python, FastAPI, Flask, Streamlit, SQL, Git |

---

## 🚀 Featured Projects

### 🔍 [Drug & Medicine Assistant](https://github.com/MuhammedNishad-1620/drug-rag-assistant)
A production-oriented RAG pipeline for medical Q&A. Users query a curated drug knowledge base via semantic search over FAISS embeddings, with Groq Llama 3 for inference. A Tavily-powered web search fallback activates when retrieval confidence drops below threshold — ensuring answers stay grounded even outside the local corpus.

> **Engineering detail:** 0.75 relevance threshold for hybrid retrieval; Dual Response Mode toggle; Git LFS for FAISS index management at scale.

`LangChain` `FAISS` `Groq Llama 3` `Tavily` `Streamlit`

---

### 🗄️ [Graph-Based NL Query System](https://github.com/MuhammedNishad-1620/Graph_Based_Data_Modeling-Query_System)
A natural language interface over a real SAP Order-to-Cash enterprise dataset ingested into Neo4j. The system translates plain-English questions into Cypher queries using an LLM, applies domain guardrails to prevent hallucinated or off-topic queries, and surfaces results through a live Cytoscape.js graph visualization UI. Deployed on Render.

> **Key challenge:** Constraining open-ended LLM generation to valid Cypher patterns on a fixed enterprise schema — solved via schema-aware prompt design and query validation.

`Neo4j` `LangChain` `Flask` `Cytoscape.js` `Render`

---

### ✈️ [TravelWAI — Agentic Travel Planner](https://github.com/MuhammedNishad-1620/AI/tree/main/TravelWAI)
A multi-step AI travel agent built with LangGraph. The agent autonomously breaks down a travel request into planning subtasks — destination research, itinerary generation, budget estimation — using web search tool integrations and Groq for fast inference. Demonstrates stateful agentic reasoning with conditional branching.

> **Design note:** Uses LangGraph's state machine to manage agent context across turns — enabling coherent multi-hop planning without prompt engineering hacks.

`LangGraph` `Groq` `Agentic AI` `Web Search`

---

### 🚑 [Smart Ambulance Triage System](https://github.com/MuhammedNishad-1620/Smart_ambulance)
A PyTorch LSTM Autoencoder trained on synthetic physiological time-series data (heart rate, SpO₂, blood pressure, motion) to detect anomalies and classify patient transport urgency. The synthetic dataset covers 8 clinical scenarios with statistically grounded signal generation to simulate real-world ICU variability.

> **Dataset design:** Pre-generation statistical analysis of a 200K-record real vitals dataset to ensure synthetic signals reflected genuine clinical distributions.

`PyTorch` `LSTM` `Autoencoder` `Synthetic Data` `Time-Series`

---

## 💼 Experience

- **AI Research Intern** — SeraphGuard Labs
- **Data Science Intern** — Analytics Vidhya
- **ML Engineering Intern** — Techciti Technologies

---

## 📌 Currently

| | |
|---|---|
| **Deepening** | Hallucination control, LLM evaluation frameworks, Transformer internals & CNN architectures |
| **Reading** | *Designing ML Systems* — Chip Huyen · *System Design Interview* — Alex Xu |
| **Looking for** | AI Engineering roles working on LLM pipelines, agents, and intelligent infrastructure |

---

> *"Build systems that work — not just systems that demo."*
