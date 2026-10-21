# Awesome-Enterprise-AI-Toolkits

# Top Enterprise AI Toolkits Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LLM Application Platforms, RAG Infrastructure & Enterprise AI Orchestration*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise AI Toolkits**. These tools enable organizations to build, deploy, and govern AI applications at scale—providing the infrastructure for retrieval-augmented generation (RAG), agent orchestration, model serving, observability, and compliance controls that enterprises require.

**Examples** include Vertex AI (Google), AWS SageMaker, Azure AI Studio, Databricks Mosaic AI, IBM watsonx.ai, Dataiku, DataRobot, Domino Data Lab, Scale AI, and Cohere Toolkit (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, vendor-agnostic deployment, and transparent AI infrastructure—ideal for enterprises that prioritize data sovereignty, avoid vendor lock-in, and require auditable AI systems. The open-source enterprise AI landscape spans all-in-one RAG platforms (Cohere Toolkit, Gebo.ai), agent orchestration frameworks (LangGraph, Semantic Kernel), LLMOps platforms (Agenta, Pezzo), and model serving engines (Xinference, LocalAI).

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Vertex AI (Google)](https://cloud.google.com/vertex-ai)**  
  Google Cloud's unified ML platform with Gemini model access, Agent Builder, RAG Engine, and enterprise governance. Tightly integrated with BigQuery and Google Workspace.

- **[AWS SageMaker](https://aws.amazon.com/sagemaker/)**  
  Amazon's end-to-end ML platform covering data preparation, training, inference, and MLOps. SageMaker JumpStart provides pre-trained models, while Canvas offers no-code AI for business analysts.

- **[Azure AI Studio](https://azure.microsoft.com/en-us/products/ai-studio/)**  
  Microsoft's platform for building generative AI applications with Azure OpenAI models, prompt flow, RAG evaluation, and responsible AI tooling.

- **[Databricks Mosaic AI](https://www.databricks.com/product/machine-learning)**  
  Unified data and AI platform with Model Serving, Vector Search, Agent Bricks, and fine-tuning capabilities. Strong for organizations already using Databricks for data engineering.

- **[IBM watsonx.ai](https://www.ibm.com/products/watsonx-ai)**  
  Enterprise AI studio for building, training, and deploying models with governance built in. Includes Prompt Lab, Tuning Studio, and integration with watsonx.governance for compliance.

- **[Dataiku](https://www.dataiku.com/)**  
  End-to-end data science and AI platform with visual and code-based workflows, LLM mesh for multi-model orchestration, and enterprise governance features.

- **[DataRobot](https://www.datarobot.com/)**  
  AI platform with automated machine learning, generative AI capabilities, and enterprise-grade MLOps. Focuses on accelerating model development with guardrails.

- **[Domino Data Lab](https://www.domino.ai/)**  
  Enterprise MLOps platform with on-demand compute, experiment tracking, and model deployment. Includes Domino Code Assist for AI-assisted development.

- **[Scale AI](https://scale.com/)**  
  Data platform for AI development, specializing in training data, model evaluation, and deployment for enterprise and government applications.

- **[Cohere (Enterprise Platform)](https://cohere.com/)**  
  Enterprise AI platform with Command models, Embed, Rerank, and RAG capabilities. Offers private deployment options (VPC, on-prem) and the open-source Cohere Toolkit for self-hosted RAG applications .

## Open-Source GitHub Projects

- **[Cohere Toolkit](https://github.com/cohere-ai/cohere-toolkit)**  
  Deployable all-in-one RAG application from Cohere. Includes a Next.js web UI, backend API, and support for multiple model providers (Cohere Platform, SageMaker, Azure, Bedrock, HuggingFace, local models). Docker Compose setup with production deployment guides for AWS, GCP, and Azure. Note: Cohere has archived the repository . Best for teams that want a reference implementation for enterprise RAG.

- **[Gebo.ai](https://github.com/geboai/gebo.ai)**  
  Open-source, vendor-agnostic enterprise AI and RAG platform. Supports 15+ LLM providers (OpenAI, Anthropic, Bedrock, Vertex AI, Ollama, vLLM), connects to enterprise systems (SharePoint, Confluence, Jira, S3, WebDAV), and includes SSO, multi-user support, MCP server integration, and A2A protocol for agent interoperability. Single-container deployment via Docker . Best for enterprises that need a complete, self-hosted RAG platform without vendor lock-in.

- **[LangGraph](https://github.com/langchain-ai/langgraph)**  
  Framework for building stateful, multi-actor agent applications as graphs. Provides persistent execution via checkpointing, human-in-the-loop controls, and time-travel debugging. Enterprise adopters include Klarna, Uber, LinkedIn, and JPMorgan. Python-first, with LangGraph Platform available for deployment . Best for production-grade agent orchestration in regulated industries.

- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)**  
  Microsoft's enterprise SDK for integrating AI into applications using plugins, planners, and memory. Supports Python, C#, and Java. Designed for enterprise and .NET-centric environments with structured approaches to combining LLMs with traditional software . Best for organizations standardized on Microsoft's ecosystem.

- **[Dify](https://github.com/langgenius/dify)**  
  Open-source LLM application development platform combining orchestration, prompt management, evaluation, and deployment. Visual workflow builder with agent capabilities. 127k+ stars . Best for teams that want a production-ready platform with a low-code interface.

- **[Agenta](https://github.com/Agenta-AI/agenta)**  
  Open-source LLMOps platform with integrated prompt management, evaluation, and observability. Supports 50+ models, version control for prompts, LLM-as-judge evaluators, and OpenTelemetry-native tracing. Self-hostable via Docker Compose . Best for teams that need rigorous prompt engineering and evaluation workflows.

- **[Pezzo](https://github.com/pezzolabs/pezzo)**  
  Cloud-native, open-source LLMOps platform for prompt design, version management, observability, and caching. Uses PostgreSQL, ClickHouse, Redis, and Supertokens. Apache 2.0 licensed . Best for developers who want a lightweight, self-hosted LLMOps solution.

- **[Xinference](https://github.com/xorbitsai/inference)**  
  Open-source library for serving LLMs, embedding models, speech, and image models behind a unified OpenAI-compatible API. Provides full model lifecycle management with high throughput and low latency. Outperforms BentoML and Ray Serve in comparative benchmarks . Best for teams that need a self-hosted model serving layer for enterprise AI applications.

- **[LocalAI](https://github.com/mudler/LocalAI)**  
  OpenAI-compatible server for text, speech, image, and video models. Docker-ready, MIT licensed, with 49k+ stars. Runs on CPU or GPU without requiring external dependencies . Best for air-gapped or privacy-sensitive deployments.

- **[Bifrost (Maxim AI)](https://github.com/maximhq/bifrost)**  
  Enterprise AI gateway supporting 1,000+ models with adaptive load balancing, guardrails, OAuth 2.0, and prompt-injection defense at the gateway layer. Sub-100-microsecond overhead at 5,000 RPS. Apache 2.0 licensed . Best for organizations that need centralized model access control and routing.

- **[Bisheng](https://github.com/dataelement/bisheng)**  
  Open-source enterprise LLM DevOps platform (Apache 2.0) with workflow editor, RAG, agent orchestration, fine-tuning, dataset management, and observability. 12k+ stars . Best for enterprises that want a comprehensive, self-hosted LLM operations platform.

### Additional Strong Open-Source Options

- **Octop Enterprise** — Self-hosted AI workspace with local task execution on employee devices, centralized model access, and team messaging. Based on TencentCloud/Octop . Best for organizations that want AI to run locally on employee machines while IT retains control.
- **Harnis** — Multi-tenant agent harness with SSO (OIDC), sandboxed execution, human approvals, and tenant isolation . Best for platform teams building internal agent platforms.
- **AIForge (zsh-aiforge)** — Enterprise AI application framework with Agent, Workflow, RAG, MCP, Memory, and RBAC. Core depends only on pydantic; all components auditable and replaceable . Best for teams that want a transparent, protocol-driven framework without heavy dependencies.
- **Frameworks for building custom systems**: Combine **LangGraph** for agent orchestration with **Agenta** for prompt management and evaluation, **Xinference** or **LocalAI** for model serving, and **Gebo.ai** for RAG infrastructure. Use **Bifrost** as the AI gateway for multi-provider routing and guardrails. For Microsoft-centric environments, **Semantic Kernel** integrates with Azure services.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise AI toolkits vary significantly in deployment complexity, compliance certifications, and vendor lock-in risk; evaluate based on your organization's data governance requirements.
- Self-hosted open-source solutions require proper infrastructure hardening, SSO integration, audit logging, and ongoing maintenance.

---

**Made for enterprise architects, AI platform engineers, MLOps teams, and technology leaders building production AI systems.**  
Let's make enterprise AI more open, governable, and vendor-agnostic.
