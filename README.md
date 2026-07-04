# Awesome AI Operations [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated tools, frameworks, and platforms for running AI agents and LLM applications in production.

The operations layer of AI: orchestration, guardrails, observability, gateways,
evaluation, retrieval, durable workflows, serving, data ops, and AI search
optimization. The focus is on production use, not demos. Maintained by
[Digiton Dynamics](https://www.digiton.ai).

Each entry is tagged `open source`, `hosted`, or `open source + hosted`. Vendor
descriptions are intentionally neutral; if a number or positioning claim changes,
open a PR with a source.

## Contents

- [Agent frameworks and orchestration](#agent-frameworks-and-orchestration)
- [Guardrails, safety and governance](#guardrails-safety-and-governance)
- [Observability, tracing and evaluation](#observability-tracing-and-evaluation)
- [LLM gateways, routing and caching](#llm-gateways-routing-and-caching)
- [Prompt engineering, evaluation and testing](#prompt-engineering-evaluation-and-testing)
- [RAG, retrieval and vector databases](#rag-retrieval-and-vector-databases)
- [Workflow automation and durable execution](#workflow-automation-and-durable-execution)
- [Model serving and inference infrastructure](#model-serving-and-inference-infrastructure)
- [Data, labeling and fine-tuning ops](#data-labeling-and-fine-tuning-ops)
- [AI search optimization (AEO / GEO)](#ai-search-optimization-aeo--geo)


## Agent frameworks and orchestration

- **[AutoGen](https://github.com/microsoft/autogen)** - Microsoft multi-agent framework; newer Microsoft agent tooling is listed below. `open source`
- **[CrewAI](https://github.com/crewAIInc/crewAI)** - Python framework for role-based multi-agent crews and event-driven flows. `open source + hosted`
- **[LlamaIndex](https://github.com/run-llama/llama_index)** - Data framework for connecting LLMs to sources, indices, and agent workflows. `open source + hosted`
- **[LangGraph](https://github.com/langchain-ai/langgraph)** - Low-level graph based framework for stateful, durable multi-agent execution. `open source + hosted`
- **[OpenAI Agents SDK](https://github.com/openai/openai-agents-python)** - Lightweight provider-agnostic SDK for agents, handoffs, tools, and guardrails. `open source`
- **[Haystack](https://github.com/deepset-ai/haystack)** - deepset's orchestration framework for RAG pipelines and tool-calling agents. `open source + hosted`
- **[Mastra](https://github.com/mastra-ai/mastra)** - TypeScript framework for agents, workflows, RAG, and observability. `open source + hosted`
- **[Google ADK (Agent Development Kit)](https://github.com/google/adk-python)** - Google's code-first toolkit for building, evaluating, and deploying agents. `open source`
- **[Pydantic AI](https://github.com/pydantic/pydantic-ai)** - Type-safe, model-agnostic Python agent framework from the Pydantic team. `open source`
- **[Microsoft Agent Framework](https://github.com/microsoft/agent-framework)** - Microsoft SDK for building agentic applications and workflows. `open source`
- **[AWS Strands Agents SDK](https://github.com/strands-agents/harness-sdk)** - Open-source model-driven SDK for building and running agents. `open source`
- **[Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents)** - Lightweight modular Python framework for composable, schema-driven agents. `open source`

## Guardrails, safety and governance

- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)** - Python framework of input/output validators that catch and correct LLM risks. `open source`
- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails)** - Programmable toolkit for dialogue rails, topic control and jailbreak detection. `open source`
- **[Llama Guard](https://github.com/meta-llama/PurpleLlama)** - Meta's fine-tuned safeguard models for classifying LLM prompts and responses. `open source`
- **[Garak](https://github.com/NVIDIA/garak)** - Open-source scanner that probes LLMs for jailbreaks, leakage and toxic output. `open source`
- **[Lakera Guard](https://www.lakera.ai/lakera-guard)** - Hosted API detecting prompt injection, jailbreaks and data leakage in real time. `hosted`
- **[Invariant Labs](https://github.com/invariantlabs-ai/invariant)** - Guardrails and trajectory analysis for securing agent and MCP tool use. `open source + hosted`
- **[Microsoft Presidio](https://github.com/microsoft/presidio)** - Detects and anonymizes PII in text, images and structured data. `open source`
- **[Promptfoo](https://github.com/promptfoo/promptfoo)** - CLI and library for LLM eval plus red-teaming and vulnerability scanning. `open source`
- **[Microsoft PyRIT](https://github.com/microsoft/PyRIT)** - Open-source framework for automated red teaming of generative AI systems. `open source`
- **[OpenAI Moderation API](https://developers.openai.com/api/docs/guides/moderation)** - Hosted endpoint for classifying text and images against safety categories. `hosted`

## Observability, tracing and evaluation

- **[LangSmith](https://www.langchain.com/langsmith)** - LangChain's tracing, evaluation and monitoring platform for LLM apps and agents. `hosted`
- **[Langfuse](https://github.com/langfuse/langfuse)** - Open source LLM engineering platform: tracing, evals, prompt management, datasets. `open source + hosted`
- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** - Open source AI observability and evaluation, OpenTelemetry-native tracing for LLM apps. `open source`
- **[Weights & Biases Weave](https://github.com/wandb/weave)** - W&B toolkit for tracing, evaluating and scoring LLM and agent applications. `open source + hosted`
- **[MLflow (GenAI/Tracing)](https://github.com/mlflow/mlflow)** - Open source ML platform with OpenTelemetry-compatible tracing and evals for LLM apps. `open source`
- **[Datadog LLM Observability](https://www.datadoghq.com/product/ai/llm-observability/)** - Enterprise APM vendor's monitoring and tracing for LLM and agent workloads. `hosted`
- **[Helicone](https://github.com/Helicone/helicone)** - Open source LLM observability platform with one-line proxy-based monitoring. `open source + hosted`
- **[Braintrust](https://www.braintrust.dev/)** - AI evaluation and observability platform for tracing, scoring and iterating on LLM apps. `hosted`
- **[Opik (Comet)](https://github.com/comet-ml/opik)** - Comet's open source platform to debug, evaluate and monitor LLM and RAG applications. `open source + hosted`
- **[OpenLLMetry (Traceloop)](https://github.com/traceloop/openllmetry)** - Open source OpenTelemetry-based instrumentation library for LLM application observability. `open source`
- **[Laminar](https://github.com/lmnr-ai/lmnr)** - Open source, OpenTelemetry-native observability platform built specifically for AI agents. `open source + hosted`

## LLM gateways, routing and caching

- **[LiteLLM](https://github.com/BerriAI/litellm)** - Open-source proxy and SDK calling 100+ LLM APIs in one OpenAI-compatible format. `open source + hosted`
- **[OpenRouter](https://openrouter.ai/)** - Hosted unified API and marketplace for routing requests across many models and providers. `hosted`
- **[Portkey AI Gateway](https://github.com/Portkey-AI/gateway)** - Open-source gateway for LLM routing, guardrails, retries, and fallbacks. `open source + hosted`
- **[Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/)** - Hosted proxy adding caching, rate limiting, retries and logging in front of AI providers. `hosted`
- **[Kong AI Gateway](https://github.com/Kong/kong)** - Kong Gateway plugins adding LLM proxying, load balancing and semantic caching. `open source + hosted`
- **[Helicone AI Gateway](https://github.com/Helicone/ai-gateway)** - Open-source Rust gateway for LLM routing, caching, failover and observability. `open source + hosted`
- **[GPTCache](https://github.com/zilliztech/GPTCache)** - Semantic caching library for LLM responses, integrated with LangChain and LlamaIndex. `open source`

## Prompt engineering, evaluation and testing

- **[Promptfoo](https://github.com/promptfoo/promptfoo)** - CLI and library to test, evaluate, and red-team prompts, RAGs, and agents. `open source`
- **[DSPy](https://github.com/stanfordnlp/dspy)** - Stanford framework for programming, not prompting, language model pipelines. `open source`
- **[Ragas](https://github.com/vibrantlabsai/ragas)** - Reference-free evaluation metrics and test-set generation for RAG pipelines. `open source`
- **[DeepEval](https://github.com/confident-ai/deepeval)** - Pytest-style unit testing framework for LLM outputs, hallucination, relevancy. `open source`
- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** - Open-source LLM tracing, evaluation, and prompt playground via OpenTelemetry. `open source`
- **[Braintrust](https://www.braintrust.dev/)** - Eval-centric platform unifying offline experiments and production scoring. `hosted`
- **[Agenta](https://github.com/Agenta-AI/agenta)** - Open-source LLMOps platform for prompt playground, versioning, and evaluation. `open source + hosted`
- **[BAML](https://github.com/BoundaryML/baml)** - Typed prompt/schema language compiling functions into reliable model calls. `open source`
- **[Giskard](https://github.com/Giskard-AI/giskard-oss)** - Open-source testing library for LLM agents, including red-teaming checks. `open source + hosted`
- **[Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai)** - UK AI Security Institute framework for large language model evaluations. `open source`

## RAG, retrieval and vector databases

- **[Pinecone](https://www.pinecone.io/)** - Fully managed vector database for semantic search and RAG at scale. `hosted`
- **[Elasticsearch](https://github.com/elastic/elasticsearch)** - Search engine with native kNN vector search and hybrid BM25 retrieval. `open source + hosted`
- **[Weaviate](https://github.com/weaviate/weaviate)** - Open-source vector database combining vector search with structured filtering. `open source + hosted`
- **[Milvus](https://github.com/milvus-io/milvus)** - Open-source distributed vector database for billion-scale similarity search. `open source + hosted`
- **[Qdrant](https://github.com/qdrant/qdrant)** - Rust-based vector search engine with filtering and payload storage. `open source + hosted`
- **[pgvector](https://github.com/pgvector/pgvector)** - Open-source vector similarity search extension for PostgreSQL. `open source`
- **[Chroma](https://github.com/chroma-core/chroma)** - Open-source embedding database for building LLM apps with retrieval. `open source + hosted`
- **[Faiss](https://github.com/facebookresearch/faiss)** - Meta's library for efficient similarity search and clustering of vectors. `open source`
- **[MongoDB Atlas Vector Search](https://www.mongodb.com/products/platform/atlas-vector-search)** - Vector search built into MongoDB Atlas alongside operational data. `hosted`
- **[LanceDB](https://github.com/lancedb/lancedb)** - Embedded multimodal vector database built on the Lance columnar format. `open source + hosted`
- **[turbopuffer](https://turbopuffer.com/)** - Serverless vector and full-text search built directly on object storage. `hosted`
- **[Vespa](https://github.com/vespa-engine/vespa)** - Open-source engine combining vector, text and structured data serving. `open source + hosted`

## Workflow automation and durable execution

- **[Temporal](https://github.com/temporalio/temporal)** - Durable execution engine; replays event history so workflows survive crashes and restarts. `open source + hosted`
- **[Apache Airflow](https://github.com/apache/airflow)** - Long-standing DAG-based scheduler for authoring and monitoring data and ML pipelines. `open source`
- **[n8n](https://github.com/n8n-io/n8n)** - Fair-code visual workflow builder with integrations and native AI nodes. `open source + hosted`
- **[Inngest](https://github.com/inngest/inngest)** - Event-driven durable step functions that run on existing serverless or server compute. `open source + hosted`
- **[Prefect](https://github.com/PrefectHQ/prefect)** - Python-native orchestration framework; decorate functions into resilient data pipelines. `open source + hosted`
- **[Trigger.dev](https://github.com/triggerdotdev/trigger.dev)** - Open-source background jobs platform for long-running tasks with retries and queues. `open source + hosted`
- **[Dagster](https://github.com/dagster-io/dagster)** - Asset-centric orchestrator with built-in lineage and metadata for data pipelines. `open source + hosted`
- **[Windmill](https://github.com/windmill-labs/windmill)** - Fast open-source platform turning scripts into webhooks, workflows, and UIs. `open source + hosted`
- **[Hatchet](https://github.com/hatchet-dev/hatchet)** - Postgres-backed orchestration engine for background tasks, queues, and AI agents. `open source + hosted`
- **[DBOS](https://github.com/dbos-inc/dbos-transact-py)** - Lightweight library adding durable, Postgres-checkpointed workflows to existing app code. `open source + hosted`
- **[Restate](https://github.com/restatedev/restate)** - Rust-built runtime turning agents, workflows, and services into durable, resumable processes. `open source + hosted`
- **[AWS Step Functions](https://aws.amazon.com/step-functions/)** - Managed serverless state-machine service for orchestrating Lambda and AWS services. `hosted`

## Model serving and inference infrastructure

- **[vLLM](https://github.com/vllm-project/vllm)** - High-throughput, memory-efficient LLM inference engine using PagedAttention and continuous batching. `open source`
- **[Ollama](https://github.com/ollama/ollama)** - Run and manage open-weight LLMs locally via a simple CLI and REST API. `open source`
- **[NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server)** - Multi-framework inference server for cloud, data center, and edge deployment. `open source`
- **[NVIDIA TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM)** - Python library and optimized kernels for high-performance LLM inference on NVIDIA GPUs. `open source`
- **[SGLang](https://github.com/sgl-project/sglang)** - High-performance serving framework for LLMs and multimodal models with RadixAttention caching. `open source`
- **[Ray Serve](https://docs.ray.io/en/latest/serve/index.html)** - Scalable, framework-agnostic model serving library built on the Ray distributed compute engine. `open source`
- **[BentoML](https://github.com/bentoml/BentoML)** - Framework for packaging models into inference APIs, with optional managed BentoCloud hosting. `open source + hosted`
- **[LMDeploy](https://github.com/InternLM/lmdeploy)** - Toolkit for compressing, quantizing, and serving LLMs and vision-language models. `open source`
- **[Modal](https://modal.com/)** - Serverless GPU cloud for running and scaling AI inference and training without managing servers. `hosted`

## Data, labeling and fine-tuning ops

- **[Label Studio](https://github.com/HumanSignal/label-studio)** - Open-source data labeling and annotation tool for text, image, audio, and video. `open source + hosted`
- **[Argilla](https://github.com/argilla-io/argilla)** - Collaboration tool for AI engineers and domain experts to build and curate high-quality datasets. `open source + hosted`
- **[Axolotl](https://github.com/axolotl-ai-cloud/axolotl)** - YAML-configured framework for fine-tuning and post-training a wide range of LLMs. `open source`
- **[Unsloth](https://github.com/unslothai/unsloth)** - Fine-tunes and trains LLMs faster with significantly reduced GPU memory usage. `open source`
- **[LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory)** - Unified toolkit for efficient fine-tuning of LLMs and vision-language models. `open source`
- **[Snorkel AI](https://snorkel.ai/)** - Programmatic data labeling and curation platform using weak supervision at enterprise scale. `hosted`
- **[Distilabel](https://github.com/argilla-io/distilabel)** - Framework for generating synthetic data and AI feedback pipelines for LLM training. `open source`
- **[Cleanlab](https://github.com/cleanlab/cleanlab)** - Data-centric library that detects label errors, outliers, and quality issues in datasets. `open source + hosted`
- **[Prodigy](https://prodi.gy/)** - Scriptable, paid annotation tool for building NLP and computer vision training data. `hosted`

## AI search optimization (AEO / GEO)

- **[Profound](https://www.tryprofound.com/)** - Tracks brand mentions and citations across ChatGPT, Perplexity, Gemini, and AI Overviews. `hosted`
- **[Ahrefs Brand Radar](https://ahrefs.com/brand-radar)** - Ahrefs feature tracking brand visibility and share of voice across six AI search surfaces. `hosted`
- **[Peec AI](https://peec.ai/)** - Berlin-based GEO platform tracking prompt-level brand visibility across ChatGPT, Gemini, Perplexity. `hosted`
- **[Otterly.AI](https://otterly.ai/)** - Daily automated monitoring of brand and link citations across ChatGPT, Perplexity, Google AI Overviews. `hosted`
- **[AthenaHQ](https://athenahq.ai/)** - AI search visibility tracking with citation-source analysis and an agentic optimization copilot. `hosted`
- **[Scrunch AI](https://scrunch.com/)** - Enterprise AI visibility platform for monitoring and optimizing how brands appear in AI search. `hosted`
- **[Goodie AI](https://higoodie.com/)** - AEO platform combining AI-visibility monitoring, content workflow, and optimization tooling. `hosted`
- **[Writesonic GEO](https://writesonic.com/generative-engine-optimization-geo)** - GEO platform crawling AI interfaces directly to track visibility and close content gaps. `hosted`

## Contributing

Suggestions and additions are welcome. Open a pull request or an issue. Entries should be production-relevant, actively maintained, and described neutrally. One tool per line, alphabetical or by adoption within each section.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Digiton Dynamics has waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE).
