# LLM Provider Compatibility

Which agentic tools work with which LLM providers. This is a companion reference to the main [readme](../readme.md).

> Last updated: February 2026

## IDEs & Editors

| Tool | OpenAI | Anthropic | Google | Local (Ollama) | Azure | AWS Bedrock | Custom API |
|------|--------|-----------|--------|----------------|-------|-------------|------------|
| Cursor | ✅ | ✅ | ✅ | ❌ | ✅ | ❌ | ✅ |
| Windsurf | ✅ | ✅ | ✅ | ❌ | ✅ | ❌ | ❌ |
| Kiro | ❌ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| Trae | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ |
| Zed | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ |
| JetBrains AI | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ |
| Amazon Q | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| Augment Code | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Tabnine | ✅ | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ |

## Terminal Agents

| Tool | OpenAI | Anthropic | Google | Local (Ollama) | Azure | AWS Bedrock | Custom API |
|------|--------|-----------|--------|----------------|-------|-------------|------------|
| Aider | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Claude Code | ❌ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| Gemini CLI | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ |
| Goose | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ |
| OpenAI Codex CLI | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| OpenCode | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Amp | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ |
| Crush | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ |
| Warp | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Qwen Code | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |

## VS Code Extensions

| Tool | OpenAI | Anthropic | Google | Local (Ollama) | Azure | AWS Bedrock | Custom API |
|------|--------|-----------|--------|----------------|-------|-------------|------------|
| Cline | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Roo Code | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Continue | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| GitHub Copilot | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ |
| Cody | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ |
| KiloCode | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |

## Legend

- ✅ Officially supported or well-documented community integration
- ❌ Not supported or no known integration

> **Note:** "Custom API" means the tool supports any OpenAI-compatible endpoint. Many local runners (Ollama, LM Studio, LocalAI, vLLM) expose OpenAI-compatible APIs, so tools with Custom API support can often use local models indirectly.

## Contributing

If you spot an inaccuracy or want to add a tool, please open a PR or issue in the main repo.
