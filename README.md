<p align="center">
  <img src="assets/banner.svg" alt="Mohan Varma, AI Engineer building production LLM platforms" width="100%">
</p>

<p align="center">
  <a href="https://mohanvarmaa22.github.io/mohan-portfolio/"><img src="https://img.shields.io/badge/Portfolio-e0a02e?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/mohan-varma-bh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mohanvarma1022@gmail.com"><img src="https://img.shields.io/badge/Email-1e2430?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

**AI Engineer at Cornerstone OnDemand.** I build the platform layer that takes LLMs from prototype to secure, reliable production.

## What I do at work

I work on Cornerstone's centralized AI Gateway, a single governed endpoint for LLM, embedding and reranker models.

<p align="center">
  <img src="assets/gateway.svg" alt="Enterprise applications and the Agentic Platform reach LLM, embedding, reranker and Laya models through one governed gateway, served across five regions." width="100%">
</p>

- **Scale:** serves 30+ enterprise applications and the internal Agentic Platform
- **Models:** onboarded ~10 security-approved models through hot-reloadable routing
- **Infrastructure:** led the GCP to AWS migration of 4 self-hosted embedding models and 1 reranker, sharing GPUs with NVIDIA time-slicing

Before that, I automated LLM evaluation with DeepEval and MLflow, and built a Docling-based document processing service for enterprise RAG pipelines.

## Selected projects

| Project | What it is | Built with |
| --- | --- | --- |
| [laya-finetuning](https://github.com/mohanvarmaa22/laya-finetuning) | Fine-tuned a prompt safety classifier on BeaverTails. Accuracy rose from 51–57% at baseline to 75% on a balanced 400-prompt test set, and calibration error fell to 0.035, at 34 ms per prompt. | Python, PyTorch DDP, Kaggle 2×T4 |
| [Decision-logs](https://github.com/mohanvarmaa22/Decision-logs) | Keeps the "why" behind AI-written code. Captures short decision notes from Claude Code sessions, secret-scans them and stores them locally. *Prototype, in active development.* | Go, Claude Code plugin |
| [jev-testing](https://github.com/mohanvarmaa22/jev-testing) | Experiments with Jev decision models through Vercel AI Gateway: choice routing, safety gating and ticket priority scoring. | Python |

## Tech I use

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,pytorch,fastapi,aws,kubernetes,docker,prometheus,grafana&theme=dark" alt="Python, Go, PyTorch, FastAPI, AWS, Kubernetes, Docker, Prometheus, Grafana">
</p>

- **GenAI:** AWS Bedrock, RAG, embeddings, rerankers, model routing, LangChain, Docling
- **Evaluation and safety:** DeepEval, MLflow, Bedrock Guardrails, PII anonymization
- **Backend:** Python, FastAPI, AsyncIO, Pydantic, Apache Pulsar, ClickHouse
- **Infrastructure:** Kubernetes (EKS), Helm, Docker, AWS, GPU/CUDA
- **Observability:** Splunk, New Relic, Prometheus, Grafana
