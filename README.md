# Agentic AI avec LangChain (Ollama)

TP Master AIDC — FST Béni Mellal (USMS) : agents LangChain `create_agent`, modèle dynamique, mémoire
(InMemory / SQLite / PostgreSQL), outils, PythonREPL, middleware, RAG (FAISS), guardrails, human-in-the-loop.

## Lancer le projet
```bash
uv sync
cp .env.example .env
ollama pull qwen3:4b && ollama pull nomic-embed-text
```
Ouvrir `AI_Agentic.ipynb`, choisir le kernel `.venv`, puis *Run All*.

Sections optionnelles (ignorées proprement si absentes) : PostgreSQL, Tavily, NVIDIA.
