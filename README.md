# Learning AI

Roadmap personal de aprendizaje e implementacion de inteligencia artificial: desde fundamentos hasta despliegue en produccion.

## Proposito

Centralizar experimentos, apuntes y proyectos practicos de AI/ML/DL a medida que se exploran nuevas tecnicas y herramientas. Cada modulo incluye teoria, implementacion de referencia y casos de uso real.

## Roadmap

| Modulo | Estado | Descripcion |
|--------|--------|-------------|
| Prompt Engineering | Avanzado | Tecnicas de prompting estructurado, few-shot, chain-of-thought |
| RAG (Retrieval Augmented Generation) | En progreso | Chunking, embeddings, vector stores, retrieval |
| LLM Fine-tuning | Planeado | LoRA/QLoRA, datasets, evaluacion |
| Agentes AI | Avanzado | Multi-agente, tool use, memory, planificacion |
| MCP (Model Context Protocol) | Exploracion | Estandar de contexto para LLMs |
| ML Clasico | Fundamentos | Regresion, clasificacion, arboles, ensambles |
| Vision/CV | Exploracion | CLIP, YOLO, Stable Diffusion |

## Arquitectura de Referencia

```
User Query
  └─► Orchestrator (Agente principal)
        ├─► RAG Pipeline (contexto)
        │     ├─► Embedding Model
        │     └─► Vector Store (Chroma/PGVector)
        ├─► Tool Layer (APIs, DB, filesystem)
        └─► LLM Backend (Groq / OpenRouter / Gemini / OpenAI)
```

## Documentacion

- [ROADMAP.md](docs/ROADMAP.md) — detalle de modulos y progreso
- [EXPERIMENTOS.md](docs/EXPERIMENTOS.md) — bitacora de experimentos y resultados
