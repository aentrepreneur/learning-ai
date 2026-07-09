<div align="center">

# Learning AI

AI/ML Engineering Roadmap — foundations to production deployment

![Status](https://img.shields.io/badge/status-Stable-28a745?style=flat-square)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
![Updated](https://img.shields.io/github/last-commit/aentrepreneur/learning-ai?style=flat-square)

</div>

## Purpose

Centralized experiments, notes, and practical projects covering AI/ML/DL as new techniques and tools are explored. Each module includes theory, reference implementation, and real-world use cases.

## Roadmap

| Module | Status | Description |
|--------|--------|-------------|
| Prompt Engineering | Advanced | Structured prompting, few-shot, chain-of-thought |
| RAG | In Progress | Chunking, embeddings, vector stores, retrieval |
| LLM Fine-tuning | Planned | LoRA/QLoRA, datasets, evaluation |
| AI Agents | Advanced | Multi-agent, tool use, memory, planning |
| MCP Protocol | Exploring | Model Context Protocol standard |
| Classical ML | Foundations | Regression, classification, trees, ensembles |
| Vision/CV | Exploring | CLIP, YOLO, Stable Diffusion |

## Reference Architecture

```text
User Query
  └─► Orchestrator (Main Agent)
        ├─► RAG Pipeline (context)
        │     ├─► Embedding Model
        │     └─► Vector Store (Chroma/PGVector)
        ├─► Tool Layer (APIs, DB, filesystem)
        └─► LLM Backend (Groq / OpenRouter / Gemini / OpenAI)
```

## Documentation

- `docs/ROADMAP.md` — detailed module breakdown and progress
- `docs/EXPERIMENTOS.md` — experiment log and results

## Related Projects

- [Uncensored LLM](https://github.com/aentrepreneur/uncensored-llm) — local inference runtime
- [Nexus One](https://github.com/aentrepreneur/nexus-one) — agent deployment framework

## License

MIT — see [LICENSE](LICENSE)

## Author

Angel Esquivel — [@aentrepreneur](https://github.com/aentrepreneur)
