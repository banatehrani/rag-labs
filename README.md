# rag-labs

Hands-on **RAG engineering labs** focused on building, testing, and understanding Retrieval-Augmented Generation systems in a structured, professional way.

This repository is organized as an engineering lab notebook — not a tutorial dump — with small modules, experiments, and design notes documenting trade-offs and improvements.

---

## Repository Structure

```
rag-labs/
│
├── foundations/      # Core RAG building blocks (ingestion, retrieval, etc.)
├── experiments/      # Controlled experiments (chunk size, embeddings, retrieval)
├── src/              # Shared utilities and reusable code
├── notes/            # Learning log + design notes
├── data/             # Local sample docs (not tracked in git)
├── pyproject.toml
└── README.md
```

---

## Goal of This Repo

- Build RAG systems from first principles
- Understand retrieval quality vs latency trade-offs
- Experiment with chunking, embeddings, and retrieval strategies
- Develop production-oriented coding practices

---

## Environment Setup (uv)

Install dependencies:

```bash
uv sync
```

Activate environment:

```bash
source .venv/bin/activate
```

---

## Working Philosophy

Each module should include at least one of:

- A measurable experiment (A vs B comparison)
- A small evaluation or benchmark
- A short design note explaining engineering decisions

The focus is **understanding and engineering**, not just running tutorial code.

---

## Attribution

Concepts and inspiration come from public educational resources (including Harish Neel’s RAG materials).  
This repository is independently structured, implemented, and extended as my own engineering work.