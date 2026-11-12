<h1 align="center">Sukhmandeep Singh</h1>
<h3 align="center">ML Engineer · Protein &amp; Antibody Design · Computational Biology</h3>

<p align="center">
I build the ML pipelines that turn protein models into design decisions: protein language models, structure prediction, candidate scoring and ranking, on HPC and cloud.
</p>

<p align="center">
<b>Open to full-time roles in protein design and AI drug discovery · open to relocation</b><br>
<a href="mailto:sukhnansaran@gmail.com">sukhnansaran@gmail.com</a> · <a href="https://www.linkedin.com/in/sukhmand-singh/">LinkedIn</a>
</p>

---

## Experience

### AI Engineer, Nucleovir Therapeutics · Mar – Oct 2026 · Pune, India
In silico antibody and protein design. *Project details are under NDA.*

- Built evaluation, filtering and ranking pipelines combining structure predictions with sequence- and structure-based scoring; on one antibody-design project this **narrowed ~1,500 generated candidates to a top 30** for experimental testing.
- Integrated **protein language model and structure-prediction pipelines** into design workflows with computational biology and R&amp;D teams.
- Optimised GPU structure-prediction runs with batched inference and multi-worker CPU parallelism.
- Deployed and orchestrated pipelines across **AWS, SLURM and Nextflow**, containerised with Docker.

### ML Research Engineer, NIT Warangal · Aug 2025 – Feb 2026
Deep learning models deployed offline on **Android, Raspberry Pi and Jetson Nano**: 10–33 FPS, &lt;350 ms end-to-end latency, model size cut from 10 MB to ~3 MB with quantization. Mentored 10+ interns.

---

## Open source

**[Graphein](https://github.com/a-r-j/graphein)** — graph representations of protein structures · 4 merged PRs

- Fixed PyTorch Geometric conversion misaligning edge features with `edge_index` — [#497](https://github.com/a-r-j/graphein/pull/497)
- Fixed hydrogen-bond detection in `add_hydrogen_bond_interactions` — [#458](https://github.com/a-r-j/graphein/pull/458)
- Kept atom charges when saving PDB files — [#498](https://github.com/a-r-j/graphein/pull/498)
- Fixed the extras flag on import messages — [#459](https://github.com/a-r-j/graphein/pull/459)
- Under review: alternate-location conformer mixing — [#515](https://github.com/a-r-j/graphein/pull/515)

**[BioPandas](https://github.com/BioPandas/biopandas)** — pandas tools for molecular structure files

- Under review: Mol2 bond parsing — [#170](https://github.com/BioPandas/biopandas/pull/170) · `read_mol2` fix when ATOM ends the input — [#171](https://github.com/BioPandas/biopandas/pull/171)

---

## Selected work

### Fine-tuning RFdiffusion3 for antibody CDR design · in progress
Fine-tuning a diffusion model to redesign antibody CDR loops against a target epitope, with a held-out benchmark against the released weights. *Write-up coming; code available on request.*

### Alzheimer's research assistant — grounded RAG over biomedical literature
[`alzheimers-rag`](https://github.com/sukhmansaran/alzheimers-rag) · Python

Hybrid dense + BM25 retrieval with rank fusion, local LLM inference, cited answers and a hallucination guard. Evaluated on 44 labelled questions (hit@5, MRR); tested with pytest and GitHub Actions CI.

### Production RAG platform
[`visa-rag-llm`](https://github.com/sukhmansaran/visa-rag-llm) · FastAPI · Next.js · PostgreSQL · Redis · Celery

Self-hosted RAG system with an autonomous crawler, change detection, verified-answer path and a full pytest suite.

---

## Tech stack

**Computational biology** — AlphaFold · ColabFold · ESM · ProteinMPNN · RFdiffusion · Biopython · PyMOL · Graphein · BioPandas

**ML** — Python · PyTorch · TensorFlow · Hugging Face Transformers &amp; Diffusers · scikit-learn · XGBoost

**HPC &amp; MLOps** — SLURM · Nextflow · AWS · Docker · batched GPU inference · ONNX · quantization

**Backend** — FastAPI · PostgreSQL · Redis · Celery · pytest

---

Working on protein design, antibody engineering or ML for drug discovery? I'd love to talk: **sukhnansaran@gmail.com**
