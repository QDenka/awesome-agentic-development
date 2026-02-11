# Awesome Agentic Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Software development paradigm where AI agents autonomously write, debug, and deploy code.

## Contents

- [AI-Enhanced IDEs \& Editors](#ai-enhanced-ides--editors)
- [Terminal-Based Coding Agents](#terminal-based-coding-agents)
- [VS Code Extensions](#vs-code-extensions)
- [Agent Frameworks](#agent-frameworks)
- [MCP Ecosystem](#mcp-ecosystem)
- [Agent Skills \& Extensions](#agent-skills--extensions)
- [Context Engineering](#context-engineering)
- [Local Models \& Self-Hosted](#local-models--self-hosted)
- [Vibe Coding Platforms](#vibe-coding-platforms)
- [Agent Security](#agent-security)
- [Agent DevOps \& Automation](#agent-devops--automation)
- [Observability \& Tracing](#observability--tracing)
- [Testing \& Quality](#testing--quality)
- [Benchmarks \& Evaluation](#benchmarks--evaluation)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## AI-Enhanced IDEs & Editors

- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS coding assistant with autonomous refactoring and legacy modernization features. (`Freemium`)
- [Augment Code](https://www.augmentcode.com) - Enterprise AI platform with deep codebase understanding and 200K context window. (`Enterprise`)
- [Cursor](https://cursor.com) - AI-first VS Code fork with Composer for multi-file editing and agentic workflows. (`Freemium`)
- [JetBrains AI Assistant](https://www.jetbrains.com/ai/) - Native AI assistant across JetBrains IDEs for completion, refactors, and chat. (`Paid`)
- [Kiro](https://kiro.dev) - AWS spec-driven agentic IDE that generates requirements, designs, and tasks before coding. (`Freemium`)
- [Tabnine](https://www.tabnine.com) - Privacy-focused AI assistant with local and on-premise deployment options. (`Freemium`)
- [Trae](https://www.trae.ai) - ByteDance AI IDE with free Builder Mode and GPT-4/Claude integration. (`Free`)
- [Windsurf](https://windsurf.com/editor) - Agentic IDE from Codeium with Cascade Flow for intelligent multi-step tasks. (`Freemium`)
- [Zed](https://github.com/zed-industries/zed) - High-performance Rust-based editor with native AI features and real-time collaboration. (`OSS`)

## Terminal-Based Coding Agents

- [Aider](https://github.com/Aider-AI/aider) - AI pair programmer for the terminal with Git integration and benchmark-leading results. (`OSS`)
- [Amp](https://ampcode.com) - Sourcegraph agentic coding tool with unconstrained token usage and deep reasoning mode. (`Freemium`)
- [Claude Code](https://github.com/anthropics/claude-code) - Anthropic agentic coding CLI with repo-wide reasoning and CLAUDE.md support. (`Paid`)
- [Crush](https://github.com/charmbracelet/crush) - Charm TUI coding agent for the terminal with multi-model support and repo context. (`OSS`)
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google terminal agent with long-context, multimodal support and project recipes. (`Free`)
- [Goose](https://github.com/block/goose) - Block's on-machine AI agent with MCP support and Agentic AI Foundation governance. (`OSS`)
- [OpenAI Codex CLI](https://github.com/openai/codex) - OpenAI command-line interface for natural language to code workflows. (`OSS`)
- [OpenCode](https://opencode.ai) - SST terminal-native AI coding agent with LSP integration and support for 75+ LLMs. (`OSS`)
- [Qwen Code](https://github.com/QwenLM/qwen-code) - Command-line AI coding tool optimized for Qwen3-Coder models. Note: primarily Chinese ecosystem. (`OSS`)
- [Warp](https://www.warp.dev) - AI-enhanced terminal with natural language command generation and workflows. (`Freemium`)

## VS Code Extensions

- [Cline](https://github.com/cline/cline) - VS Code agent with plan-and-act workflow, repo analysis and human approval for each step. (`OSS`)
- [Cody](https://sourcegraph.com/cody) - Sourcegraph AI coding assistant with code graph context and refactor tools. (`Freemium`)
- [Continue](https://github.com/continuedev/continue) - Open-source AI assistant for VS Code/JetBrains with custom models and MCP support. (`OSS`)
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer with chat, agentic PR features, and multi-model support. (`Freemium`)
- [KiloCode](https://github.com/Kilo-Org/kilocode) - VS Code extension extending Roo/Cline with orchestrator mode and improved error recovery. (`OSS`)
- [Roo Code](https://github.com/RooCodeInc/Roo-Code) - Fork of Cline with role-based modes and multi-agent orchestration inside VS Code. (`OSS`)

## Agent Frameworks

### Multi-Agent Orchestration

- [AutoGen](https://github.com/microsoft/autogen) - Microsoft multi-agent framework with conversation patterns and AutoGen Studio UI. (`OSS`)
- [CrewAI](https://github.com/crewAIInc/crewAI) - Role-based multi-agent framework where specialized agents collaborate on tasks. (`OSS`)
- [Google ADK](https://github.com/google/adk-python) - Agent Development Kit for Gemini with Python/TS/Go/Java SDKs. (`OSS`)
- [LangGraph](https://github.com/langchain-ai/langgraph) - Graph-based orchestration for stateful, long-running agents with human-in-the-loop. (`OSS`)
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript agent framework from Gatsby team with workflows, RAG, and observability. (`OSS`)
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - Lightweight SDK for multi-agent workflows with handoffs, guardrails, and tracing. (`OSS`)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft SDK for integrating LLM agents into .NET, Python, and Java apps. (`OSS`)

### Lightweight & Specialized

- [Agno](https://github.com/agno-agi/agno) - Full-stack multi-agent runtime with memory, state, and support for many LLM providers. (`OSS`)
- [LlamaIndex Agents](https://github.com/run-llama/llama_index) - RAG-centered agent framework with connectors, retrievers, and evaluation tooling. (`OSS`)
- [PydanticAI](https://github.com/pydantic/pydantic-ai) - Type-safe agent framework with validated tool schemas and structured I/O. (`OSS`)
- [smolagents](https://github.com/huggingface/smolagents) - Minimalist code-first agent framework where agents write and execute Python tools. (`OSS`)

## MCP Ecosystem

### MCP Directories & Aggregators

- [awesome-mcp-servers (appcypher)](https://github.com/appcypher/awesome-mcp-servers) - Categorized MCP server list with security notes and tags. (`Free`)
- [awesome-mcp-servers (wong2)](https://github.com/wong2/awesome-mcp-servers) - Large curated directory of MCP servers with mcpservers.org companion. (`Free`)
- [Glama MCP Directory](https://glama.ai/mcp/servers) - Searchable MCP server index with ranking and usage statistics. (`Free`)
- [MCP Official Specification](https://modelcontextprotocol.io) - Anthropic Model Context Protocol spec, SDKs, and roadmap. (`Free`)

### Official MCP Servers

- [Brave Search MCP Server](https://github.com/brave/brave-search-mcp-server) - Web search with Brave Search API. (`OSS`)
- [Docker MCP Server](https://github.com/docker/mcp-gateway) - Container and image management via MCP. (`OSS`)
- [Filesystem MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Controlled file operations with configurable access. (`OSS`)
- [Git MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Git repo reading, searching and manipulation. (`OSS`)
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - Official GitHub MCP integration for repos, issues, and PR workflows. (`OSS`)
- [Memory MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Graph-based persistent memory for agents. (`OSS`)
- [PostgreSQL MCP Server](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/postgres) - Read-only DB queries and schema inspection. (`OSS`)
- [Slack MCP Server](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/slack) - Workspace messaging and channel access via MCP. (`OSS`)

### MCP Clients

> Cursor, Goose, Continue, and Zed listed above also function as MCP clients.

- [Claude Desktop](https://claude.ai) - Anthropic desktop app with first-class MCP support. (`Freemium`)
- [VS Code](https://code.visualstudio.com) - MCP support via extensions including GitHub Copilot and Claude Code. (`Free`)

## Agent Skills & Extensions

- [agent-skills (jdrhyne)](https://github.com/jdrhyne/agent-skills) - Community collection of skills for Claude Code and other coding agents. (`OSS`)
- [Anthropic Skills Repository](https://github.com/anthropics/skills) - Public repo with example Claude skills and templates. (`OSS`)
- [Claude Agent Skills](https://platform.claude.com/docs/en/build-with-claude/skills-guide) - Official Anthropic skill system for packaging tools and instructions. (`Free`)
- [skills.sh](https://skills.sh) - Marketplace for Claude and other agent skills installable in one command. (`Free`)

## Context Engineering

### Standards & Formats

- [.cursorrules / .cursor/rules](https://cursor.com/docs) - Cursor rule files that govern project-level behavior. (`Free`)
- [.windsurfrules](https://docs.windsurf.com/windsurf/context) - Windsurf context configuration format for agent behavior. (`Free`)
- [AGENTS.md](https://github.com/agentsmd/agents.md) - Open context-file standard under Linux Foundation Agentic AI Foundation. (`OSS`)
- [CLAUDE.md](https://code.claude.com/docs/en/memory) - Project-level context file format for Claude Code. (`Free`)
- [GEMINI.md](https://github.com/google-gemini/gemini-cli/blob/main/docs/cli/gemini-md.md) - Gemini CLI project context file format. (`Free`)
- [llms.txt](https://llmstxt.org) - Proposed standard for exposing documentation to LLMs via websites. (`Free`)

### Guides & References

- [Context Engineering for Coding Agents](https://martinfowler.com/articles/exploring-gen-ai/context-engineering-coding-agents.html) - Martin Fowler's guide to rules, skills, and subagents. (`Free`)
- [Context Engineering for AI Agents in OSS](https://arxiv.org/abs/2510.21413) - Academic study of AGENTS.md usage in open-source projects. (`Free`)
- [How to Write a Great agents.md](https://github.blog/ai-and-ml/github-copilot/how-to-write-a-great-agents-md-lessons-from-over-2500-repositories/) - GitHub analysis of 2,500+ AGENTS.md files. (`Free`)

## Local Models & Self-Hosted

### Model Runners & Inference

- [GPT4All](https://github.com/nomic-ai/gpt4all) - Local model runtime with GUI, embedding support, and broad model compatibility. (`OSS`)
- [Jan](https://github.com/janhq/jan) - Open-source desktop app for running local AI models with offline-first design. (`OSS`)
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Efficient C/C++ LLM inference with broad hardware support and GGUF format. (`OSS`)
- [LM Studio](https://lmstudio.ai) - Desktop app for running local LLMs with built-in server and chat UI. (`Free`)
- [LocalAI](https://github.com/mudler/LocalAI) - OpenAI-compatible local API server supporting multiple model formats. (`OSS`)
- [Ollama](https://github.com/ollama/ollama) - Run LLMs locally with a simple CLI and model library. (`OSS`)
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput LLM serving engine with PagedAttention for production. (`OSS`)

### Coding-Focused Local Models

- [CodeLlama](https://huggingface.co/codellama/CodeLlama-34b-Instruct-hf) - Meta coding model family (7B/13B/34B) based on LLaMA 2. (`OSS`)
- [Codestral](https://huggingface.co/mistralai/Codestral-25.01) - Mistral 25B coding model with fill-in-the-middle and 256K context. (`OSS`)
- [DeepSeek-Coder-V2](https://huggingface.co/deepseek-ai/DeepSeek-Coder-V2-Instruct) - MoE coding model with 236B params and 128K context window. (`OSS`)
- [Devstral](https://huggingface.co/mistralai/Devstral-Small-2505) - Mistral 24B agentic coding model optimized for SWE-bench tasks. (`OSS`)
- [Qwen3-Coder](https://huggingface.co/Qwen/Qwen3-Coder) - Alibaba 480B coding model with 256K context optimized for agentic workflows. (`OSS`)
- [StarCoder2](https://huggingface.co/bigcode/starcoder2-15b) - BigCode 15B model trained on The Stack v2 with 16K context. (`OSS`)

## Vibe Coding Platforms

- [Bolt.new](https://bolt.new) - StackBlitz AI environment for full-stack apps using WebContainers. (`Freemium`)
- [Devin](https://devin.ai) - Cognition autonomous software engineer for complex multi-step work. (`Paid`)
- [Firebase Studio](https://firebase.studio) - Google AI coding environment (ex-Project IDX) with Gemini agents. (`Free`)
- [Lovable](https://lovable.dev) - AI-powered platform that builds full-stack apps from natural language. (`Freemium`)
- [Pythagora](https://github.com/Pythagora-io/gpt-pilot) - Open-source AI developer with 14 specialized agents for React/Node. (`OSS`)
- [Replit Agent](https://replit.com) - Replit AI agent for building and deploying apps in browser IDE. (`Freemium`)
- [v0 by Vercel](https://v0.app) - AI UI generator that turns prompts into React code. (`Freemium`)

## Agent Security

### Frameworks & Standards

- [Meta Agents Rule of Two](https://ai.meta.com/blog/practical-ai-agent-security/) - Meta framework for reducing prompt injection impact. (`Free`)
- [OWASP Top 10 for Agentic Applications 2026](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/) - Top 10 risks for agentic AI systems with mitigations. (`Free`)

### Sandboxing & Isolation

- [E2B](https://github.com/e2b-dev/E2B) - Open-source secure sandboxes for AI-generated code execution in the cloud. (`Freemium`)
- [Firecracker](https://github.com/firecracker-microvm/firecracker) - MicroVM tech widely used for secure agent sandboxes. (`OSS`)
- [gVisor](https://github.com/google/gvisor) - Application kernel for stronger container isolation. (`OSS`)

### Research & Reports

- [Claude Skills Security Analysis](https://www.reddit.com/r/ClaudeAI/comments/1qh0400/) - Study showing ~26% Claude skills have at least one security issue. (`Free`)
- [Prompt Injection to RCE in AI Agents](https://blog.trailofbits.com/2025/10/22/prompt-injection-to-rce-in-ai-agents/) - Trail of Bits research on prompt injection to remote code execution. (`Free`)
- [State of MCP Server Security 2025](https://astrix.security/learn/blog/state-of-mcp-server-security-2025/) - Astrix report analyzing 20k+ MCP repos. (`Free`)

## Agent DevOps & Automation

### AI Code Review

- [CodeAnt AI](https://www.codeant.ai) - AI code review and quality/security scanning integrated with GitHub. (`Freemium`)
- [CodeRabbit](https://www.coderabbit.ai) - AI PR reviewer for GitHub/GitLab with diff-based analysis. (`Freemium`)
- [Graphite](https://graphite.com) - Developer productivity platform with stacked PRs and AI review. (`Freemium`)
- [Qodo](https://www.qodo.ai) - Enterprise AI code review with workflows and policy controls. (`Freemium`)

### CI/CD & Automation

- [Claude Code GitHub Action](https://github.com/anthropics/claude-code-action) - GitHub Action for AI PR reviews and issue resolution via Claude. (`OSS`)
- [awesome-lint](https://github.com/sindresorhus/awesome-lint) - Linter ensuring awesome-list structure and style. (`OSS`)

## Observability & Tracing

- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - Open-source LLM observability with tracing, evals, and experiment tracking. (`OSS`)
- [Braintrust](https://www.braintrust.dev) - End-to-end platform for evaluating, monitoring, and improving AI agents. (`Freemium`)
- [Helicone](https://github.com/Helicone/helicone) - Open-source LLM observability proxy with cost tracking, caching, and rate limiting. (`Freemium`)
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform with tracing, prompt management, and evals. (`OSS`)
- [LangSmith](https://smith.langchain.com) - LangChain observability platform for tracing, debugging, and evaluating agents. (`Freemium`)
- [OpenLIT](https://github.com/openlit/openlit) - OpenTelemetry-native LLM observability with GPU monitoring and prompt injection detection. (`OSS`)
- [Portkey](https://github.com/Portkey-AI/gateway) - AI gateway with unified API, load balancing, fallbacks, and observability across 200+ LLMs. (`Freemium`)
- [Weights & Biases Weave](https://github.com/wandb/weave) - LLM application tracking and evaluation framework from W&B. (`Freemium`)

## Testing & Quality

- [Agenteval](https://github.com/amazon-science/agenteval) - Amazon framework for evaluating LLM agents on task completion and correctness. (`OSS`)
- [DeepEval](https://github.com/confident-ai/deepeval) - Unit testing framework for LLMs with 14+ metrics including hallucination and toxicity. (`OSS`)
- [Evalite](https://github.com/mattpocock/evalite) - Lightweight TypeScript eval framework for testing LLM outputs locally. (`OSS`)
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) - UK AISI framework for evaluating and red-teaming LLM agents with sandboxing. (`OSS`)
- [promptfoo](https://github.com/promptfoo/promptfoo) - CLI and library for testing prompts, models, and RAG pipelines with automated red-teaming. (`OSS`)
- [Ragas](https://github.com/explodinggradients/ragas) - Evaluation framework for RAG pipelines with metrics for faithfulness and relevance. (`OSS`)

## Benchmarks & Evaluation

- [Aider Polyglot Benchmark](https://aider.chat/docs/leaderboards/) - 225 multi-language coding problems for agents. (`Free`)
- [HumanEval](https://github.com/openai/human-eval) - OpenAI code-generation benchmark. (`OSS`)
- [SWE-bench](https://github.com/SWE-bench/SWE-bench) - Benchmark suite of real GitHub issues for code LLMs, including Verified and Pro variants. (`OSS`)

## Learning Resources

### Articles & Guides

- [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents) - Anthropic patterns for agent design. (`Free`)
- [The Complete Guide to Building Skills for Claude](https://www.anthropic.com/news) - Anthropic PDF on Claude skills. (`Free`)

### Courses & Tutorials

- [DeepLearning.AI Multi-Agent Systems](https://www.deeplearning.ai/courses/) - Short courses covering CrewAI and multi-agent architectures. (`Free`)
- [LangChain Academy](https://academy.langchain.com) - Courses on LangGraph and LangChain agents. (`Free`)

### Community

- [r/AI_Agents](https://reddit.com/r/AI_Agents) - Forum for agent frameworks and tools. (`Free`)
- [r/ChatGPTCoding](https://reddit.com/r/ChatGPTCoding) - Community for AI-assisted coding workflows. (`Free`)
- [r/ClaudeCode](https://reddit.com/r/ClaudeCode) - Claude Code users and plugin developers. (`Free`)
- [r/vibecoding](https://reddit.com/r/vibecoding) - Vibe coding community for AI app builders. (`Free`)

## Related Awesome Lists

- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents#readme) - General AI agents and automation tools across domains.
- [awesome-code-agents](https://github.com/sorrycc/awesome-code-agents#readme) - Code agents and assistants in IDEs, browsers, and CLIs.
- [awesome-code-ai](https://github.com/sourcegraph/awesome-code-ai#readme) - AI coding assistants, completion tools, and related resources.
- [awesome-vibe-coding](https://github.com/filipecalegario/awesome-vibe-coding#readme) - Vibe coding tools and AI-first app builders.

## Contributing

See [contributing.md](contributing.md) for guidelines on adding entries to this list.

## Footnotes

**Legend:** `Free` `Freemium` `Paid` `Enterprise` `OSS` (Open Source) — see also [LLM Provider Compatibility](docs/llm-providers.md) | [Star Tracker](docs/stars.md).
