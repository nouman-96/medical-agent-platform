# MedForma (Working Title)

> AI-powered SaaS platform to accelerate regulatory compliance and full-lifecycle development for medical devices (EU MDR, ISO 13485, 14971, IEC 62304, FDA).

## 🎯 MVP Goals

- AI agents (LangGraph) to answer compliance questions
- GSPR, SOPs, Risk Management files generation
- Document export (PDF/DOCX)
- RAG system on official regulatory standards
- Stripe-based subscription model

## 📁 Structure

- `frontend/`: Next.js web interface
- `backend/`: FastAPI agent APIs
- `agents/`: Independent LLM agents for tasks
- `vector-db/`: Rust tokenizer, Qdrant setup, embeddings
- `docgen/`: Template-based document generator
- `data/`: ISO/MDR PDF source files
- `infra/`: Docker, Dapr, CI/CD configs
