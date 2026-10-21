# Aleks Balaban

**Software architect: 25 years of distributed and enterprise systems, now building agentic AI and regulated integration platforms.**

I design systems end to end and build them with AI coding agents as my development team. I set the architecture, constraints and quality bar, review and verify everything the agents produce, and I own the result.

## What I build

- **Regulated integration platforms.** A SESAR SWIM (Yellow Profile) gateway for European air navigation service providers, with RBAC, full auditing, a delivery ledger and token-based headless API access.
- **Agent tooling and MCP.** [idea-mcp-proxy](https://github.com/aleksbal/idea-mcp-proxy) is an MCP reverse proxy that cuts IDE call-hierarchy output for agents by 95–99% without losing precision, using deterministic summarization rather than LLM summarization.
- **Retrieval and RAG.** [lahmajo](https://github.com/aleksbal/lahmajo) is agentic RAG with hybrid BM25 + vector retrieval, Reciprocal Rank Fusion and adaptive chunking, running on local or cloud LLMs.
- **Privacy-aware and on-prem AI.** Local/offline NER-based obfuscation before data reaches online LLMs, and local model deployments with Ollama.

## How I work

- Architecture first: constraints, failure modes, security and auditability from day one, not bolted on later.
- AI agents as the implementation team, held to explicit specs, tests and measurements. I verify their output instead of trusting it.
- Production-grade by default: the kind of software regulated industries can actually run.

## Stack

**Architecture & backend:** Java · Spring Boot · Kotlin · Python/FastAPI · Node.js · messaging (pub/sub, request/response) · REST/OpenAPI
**AI / agents:** Claude · OpenAI · AWS Bedrock · Ollama · LangChain/LangGraph · MCP · RAG
**Data & search:** PostgreSQL · Oracle · MongoDB · Elasticsearch
**Platform:** Docker · Kubernetes · Keycloak/OAuth2 · Jenkins · Git

## Elsewhere

[Modest AI Studio](https://aleksbal.github.io/ai-consulting) (AI consulting for SMEs) · [Blog](https://aleksbal.github.io/ai-consulting/blog/) · [LinkedIn](https://www.linkedin.com/in/aleksbalaban/)

*Outside software: vintage audio repair, a self-built pizza oven, Chinese cooking, freediving.*
