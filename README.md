<h1 align="center">Sukhmandeep Singh</h1>
<h3 align="center">Applied ML Engineer — Production ML Systems · Edge AI · Scientific ML</h3>

<p align="center">
I build and deploy machine learning systems that run under real constraints — limited compute, tight latency budgets, and messy real-world data. Not just notebooks.
</p>

<p align="center">
<b>Open to contract and full-time work</b> · <a href="mailto:sukhnansaran@gmail.com">sukhnansaran@gmail.com</a>
</p>

---

## What I do

- Take models from **prototype → optimized → deployed**, on hardware that isn't a GPU cluster
- Compress and accelerate inference with **quantization, ONNX export, and architecture-level optimization**
- Ship **full systems, not scripts** — API, database, task queue, containers, migrations, tests
- Build **end-to-end pipelines**: training → evaluation → inference → deployment
- Apply ML to **scientific and high-stakes domains** where correctness matters more than leaderboard scores

---

## Selected work

### Immigration Intelligence Platform — production RAG system
[`visa-rag-llm`](https://github.com/sukhmansaran/visa-rag-llm) · Python · FastAPI · Next.js 14

A full-stack retrieval-augmented generation platform for Canadian immigration guidance, built as a real production system rather than a demo.

- **Hybrid RAG pipeline** — Llama 3.2 via Ollama, Nomic embeddings, ChromaDB vector store
- **Autonomous crawler** over official policy sources with robots.txt compliance, deduplication, and rate limiting
- **Change detection** that monitors regulatory updates and notifies on policy shifts
- **Production backend** — PostgreSQL + SQLModel, Alembic migrations, Redis + Celery workers, Dockerized, pytest suite
- **Typed frontend** — Next.js 14 App Router, React 18, TypeScript, Tailwind

### Edge ML deployment — NIT Warangal
Deep learning models for image classification deployed across **Android, Raspberry Pi, and Jetson Nano** under strict hardware limits.

- **10–33 FPS** real-time inference
- **<350 ms** end-to-end latency
- **~3 MB** compressed model footprint

*Focus: real-time performance where compute, memory, and power are all constrained.*

### Generative model fine-tuning
[`fine-tuning-stable-diffusion-models-lora-dreambooth`](https://github.com/sukhmansaran/fine-tuning-stable-diffusion-models-lora-dreambooth) · Jupyter

Stable Diffusion fine-tuning with **LoRA and DreamBooth**, optimized for training in **<16 GB VRAM** environments.

### ML on biological data
[`classification-of-mice-based-on-protein-expression-levels`](https://github.com/sukhmansaran/classification-of-mice-based-on-protein-expression-levels) · Jupyter

Multi-class classification over protein expression profiles — feature selection and model comparison on high-dimensional biological measurements.

---

## Tech stack

**Core** — Python · PyTorch · TensorFlow · scikit-learn · NumPy · pandas

**Generative AI** — Transformers · HuggingFace · Diffusers · LoRA/DreamBooth · RAG · Ollama

**Backend & infra** — FastAPI · PostgreSQL · SQLModel · Alembic · Redis · Celery · Docker · pytest

**Deployment & optimization** — ONNX · quantization · Jetson Nano · Raspberry Pi · Android

**Data** — ChromaDB · Pinecone · Firebase

---

## Contact

- **Email** — sukhnansaran@gmail.com
- **LinkedIn** — [in/sukhmand-singh](https://www.linkedin.com/in/sukhmand-singh/)
- **Kaggle** — [sukhmansaran](https://www.kaggle.com/sukhmansaran)

Working on production ML, edge inference, or ML for scientific discovery? Get in touch.
