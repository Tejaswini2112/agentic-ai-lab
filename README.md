# agentic-ai-lab

A hands-on lab for learning and building **agents, multi-agent systems, and agentic AI** with [LangChain](https://python.langchain.com/) and [LangGraph](https://langchain-ai.github.io/langgraph/) — with a focus on **guardrails** and **evaluation**.

## Goals

- 🤖 Build single agents (tool-calling, reasoning loops)
- 🕸️ Build multi-agent systems and orchestration with LangGraph
- 🛡️ Apply guardrails (input/output validation, safety, constraints)
- 📊 Evaluate agent behavior and quality

## Setup

This project uses [uv](https://github.com/astral-sh/uv) for dependency management.

```bash
# install dependencies
uv sync

# copy the env template and add your own keys
cp .env.example .env
```

Then fill in your API keys in `.env` (it is git-ignored and must never be committed):

```
GROQ_API_KEY=...
GOOGLE_API_KEY=...
OPENAI_API_KEY=...
```

## Structure

- `updatedLangchain/` — notebooks and experiments
- `main.py` — entry point / scratch

## Notes

This is a learning repository — expect experiments, notebooks, and works-in-progress.
