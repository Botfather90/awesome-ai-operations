# Awesome AI Operations [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, and practical resources for building, shipping, and running production AI agents, workflow automation, RAG systems, and AI search optimization (AEO/GEO).

Most AI content is about demos. This list is about what survives contact with production: the agent frameworks, automation platforms, retrieval stacks, evaluation tools, and deployment patterns teams actually ship with.

Maintained by [Digiton Dynamics](https://www.digiton.ai), a Lisbon AI agency that builds these systems in production across 8 countries.

## Contents

- [AI Agent Frameworks](#ai-agent-frameworks)
- [Workflow Automation](#workflow-automation)
- [RAG and Knowledge Systems](#rag-and-knowledge-systems)
- [LLM Providers](#llm-providers)
- [Evaluation and Observability](#evaluation-and-observability)
- [AI Search Optimization (AEO / GEO)](#ai-search-optimization-aeo--geo)
- [Deployment and Infrastructure](#deployment-and-infrastructure)
- [Practical Guides](#practical-guides)

## AI Agent Frameworks

- [LangGraph](https://github.com/langchain-ai/langgraph) - Stateful, graph-based orchestration for agentic workflows.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Role-based multi-agent orchestration.
- [Microsoft AutoGen](https://github.com/microsoft/autogen) - Multi-agent conversation framework.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - Lightweight agent loop and tools.
- [Claude Agent SDK](https://docs.claude.com/en/api/agent-sdk/overview) - Building agents on Claude with tools and memory.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Type-safe agent framework for Python.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript agent framework with workflows and RAG.

## Workflow Automation

- [n8n](https://github.com/n8n-io/n8n) - Source-available workflow automation with 400+ integrations.
- [Activepieces](https://github.com/activepieces/activepieces) - Open-source automation, an MIT-licensed alternative to Zapier.
- [Windmill](https://github.com/windmill-labs/windmill) - Developer platform to turn scripts into workflows and UIs.
- [Make](https://www.make.com) - Visual automation platform.
- [Zapier](https://zapier.com) - Hosted automation across thousands of apps.
- [Pipedream](https://pipedream.com) - Code-first integration and workflow platform.
- [Temporal](https://github.com/temporalio/temporal) - Durable execution for long-running, reliable workflows.

## RAG and Knowledge Systems

- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for LLM applications and retrieval.
- [LangChain](https://github.com/langchain-ai/langchain) - Building blocks for LLM apps and retrieval chains.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end framework for RAG and search.
- [pgvector](https://github.com/pgvector/pgvector) - Vector similarity search inside PostgreSQL.
- [Weaviate](https://github.com/weaviate/weaviate) - Open-source vector database.
- [Qdrant](https://github.com/qdrant/qdrant) - Vector database built for production search.

## LLM Providers

- [Anthropic Claude](https://www.anthropic.com) - Claude model family for reasoning, coding, and agents.
- [OpenAI](https://platform.openai.com) - GPT model family and APIs.
- [Google Gemini](https://ai.google.dev) - Gemini models and developer APIs.
- [Mistral](https://mistral.ai) - Open-weight and hosted European models.

## Evaluation and Observability

- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM tracing, evals, and observability.
- [LangSmith](https://www.langchain.com/langsmith) - Tracing and evaluation for LLM apps.
- [Ragas](https://github.com/explodinggradients/ragas) - Evaluation framework for RAG pipelines.
- [Promptfoo](https://github.com/promptfoo/promptfoo) - Test and evaluate prompts and models.

## AI Search Optimization (AEO / GEO)

Getting cited by ChatGPT, Claude, Perplexity, and Google AI Overviews is its own discipline (answer engine optimization and generative engine optimization).

- [llms.txt](https://llmstxt.org) - Proposed standard for exposing site content to language models.
- [Schema.org](https://schema.org) - Structured data vocabulary (FAQPage, Article, Organization) that helps engines parse and cite content.
- [IndexNow](https://www.indexnow.org) - Instant indexing protocol that feeds Bing and, by extension, Copilot and ChatGPT.
- [NotFair](https://github.com/nowork-studio/NotFair) - Open-source Claude Code skills for SEO, GEO, and AEO audits, bundling Google Search Console MCP, Google Analytics (GA4) MCP, Google Ads MCP, and Meta Ads MCP servers for live data.
- [Digiton AI answers knowledge base](https://www.digiton.ai/answers) - A worked example of an AEO citation surface built with FAQ schema and direct-answer content.

## Deployment and Infrastructure

- [Vercel](https://vercel.com) - Frontend and serverless deployment.
- [Railway](https://railway.app) - Simple container and service hosting.
- [Supabase](https://github.com/supabase/supabase) - Open-source Postgres, auth, and vector store.
- [Upstash](https://upstash.com) - Serverless Redis and rate limiting.

## Practical Guides

Vendor-neutral guides on buying, scoping, and running AI work, written from production delivery:

- [How to choose an AI agency](https://www.digiton.ai/how-to-choose-an-ai-agency)
- [How much does an AI agent cost](https://www.digiton.ai/how-much-does-an-ai-agent-cost)
- [What to look for in a RAG vendor](https://www.digiton.ai/what-to-look-for-in-a-rag-vendor)
- [How to measure the ROI of AI](https://www.digiton.ai/how-to-measure-ai-roi)
- [In-house AI team vs hiring an agency](https://www.digiton.ai/in-house-ai-team-vs-agency)

## Contributing

Contributions are welcome. Open a pull request to add a tool or resource that is genuinely useful for shipping AI to production. Keep entries alphabetical within a section, with a one-line, factual description.

## Maintainer

Curated by [Digiton Dynamics](https://www.digiton.ai), an AI infrastructure company and product studio in Lisbon, Portugal. Digiton builds production AI agents, workflow automation, RAG knowledge systems, and AI search optimization, and runs its own product [Parci](https://parci.eu) (real-estate intelligence covering 308 Portuguese municipalities, full analysis in 47 seconds).

## License

[CC0 1.0 Universal](LICENSE) - Public domain dedication.
