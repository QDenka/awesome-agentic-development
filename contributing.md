# Contributing to awesome-agentic-development

Thank you for your interest in contributing! This list aims to be a high-quality, curated resource for agentic development tools and practices.

## How to Add an Entry

### Requirements

Before submitting, ensure your entry meets **all** of these criteria:

- [ ] **Active maintenance**: Last commit within the past 6 months.
- [ ] **Open-source threshold**: ≥50 GitHub stars, OR backed by a recognized company/organization.
- [ ] **Commercial products**: Must have documented user base or public traction.
- [ ] **Verified**: The tool/resource must be verifiable from at least 2 independent sources.
- [ ] **Relevant**: Directly related to agentic AI development (coding agents, MCP, frameworks, etc.).
- [ ] **No duplicates**: Check that the entry doesn't already exist in the list.

### Entry Format

```markdown
- [Name](https://url) - Description starting with capital letter, ending with period. (`Pricing`)
```

**Description guidelines:**

- One sentence, maximum 20 words.
- No promotional language ("best", "revolutionary", "#1", "leading").
- Focus on what makes the tool unique or its primary function.
- Start with a capital letter, end with a period.

### Examples

✅ **Good:**

```
- [Aider](https://github.com/Aider-AI/aider) - AI pair programmer with git integration, multi-file editing, and top benchmark scores. (`OSS`)
```

❌ **Bad:**

```
- [Aider](https://github.com/Aider-AI/aider) - The best AI coding tool that revolutionizes pair programming.
```

## Submitting a Pull Request

1. Fork this repository.
2. Create a branch: `git checkout -b add-tool-name`.
3. Add your entry in the appropriate category, in alphabetical order.
4. Verify the URL works and the description is accurate.
5. Run the linter: `npx awesome-lint` (optional but recommended).
6. Submit a Pull Request using our [PR template](.github/PULL_REQUEST_TEMPLATE.md).

## Category Placement

If unsure which category fits:

- **IDEs & Editors**: Standalone IDE or editor with built-in AI features.
- **Terminal Agents**: CLI tools that run in the terminal for coding tasks.
- **VS Code Extensions**: Plugins that extend VS Code with AI agent capabilities.
- **Agent Frameworks**: Libraries/SDKs for building multi-agent systems.
- **MCP Ecosystem**: MCP servers, clients, directories, and tools.
- **Agent Skills**: Skill packages, marketplaces, and extension systems.
- **Context Engineering**: Files, formats, and tools for providing context to AI agents.
- **Vibe Coding Platforms**: Browser-based tools for building apps from natural language.
- **Agent Security**: Security frameworks, sandboxing tools, and research.
- **Agent DevOps**: AI code review, CI/CD integration, and automation tools.
- **Benchmarks**: Evaluation frameworks and leaderboards for AI coding.
- **Learning Resources**: Articles, courses, videos, and community links.

## Reporting Issues

If you notice a broken link, outdated entry, or inaccuracy:

1. Open an [Issue](https://github.com/QDenka/awesome-agentic-development/issues/new).
2. Provide the entry name and the problem.
3. If possible, suggest the correction.

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

By participating, you agree to uphold this code. Report unacceptable behavior to the maintainers.
