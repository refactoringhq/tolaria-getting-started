---
type: Note
related_to: "[[tolaria]]"
onboarding: 7
---
# AI in Tolaria

Tolaria embraces AI without making it a requirement. Choose between coding agents that can work with vault files and direct models that answer from note context without file-editing tools.

### Coding agents

Tolaria can launch installed versions of Claude Code, Codex, GitHub Copilot, OpenCode, Pi, Antigravity CLI, Kiro, and Hermes Agent.

Each agent owns its authentication and runtime. Tolaria gives it the active note and vault context, streams the conversation, and keeps file changes visible in the app.

Use **Vault Safe** for file, search, and edit work. Use **Power User** only when you intentionally want an agent to run supported shell commands inside the vault.

Agents that expose a reliable catalog can also show a model picker. Tolaria remembers model choices separately for each agent; **Agent default** lets the CLI choose.

### Direct models

Direct models are useful when you want chat over note context without giving the model vault-write tools. Tolaria supports local providers such as Ollama and LM Studio, hosted providers such as OpenAI, Anthropic, Gemini, and OpenRouter, and custom OpenAI-compatible endpoints.

Provider credentials stay in local app configuration or an environment variable, not in this vault.

### Try it

1. Open the AI panel with `Cmd+Shift+L` or `Ctrl+Shift+L`.
2. Choose an installed coding agent or a configured direct model.
3. Ask: “Explain how [[project-dashboard]] gets its values.”
4. With a coding agent in Vault Safe mode, ask: “Add one unchecked learning task to [[get-familiar-with-tolaria]].”
5. Review the resulting file diff before you commit it.

Use the stop control if an agent takes the wrong direction.

### External tools

Because this vault contains `AGENTS.md`, an external AI tool can understand its file conventions even without Tolaria's built-in panel. Tolaria can also register its MCP server with supported tools such as Claude Code and Cursor, so they can search, read, create, update, and append notes, open a note in Tolaria, and list or attach vaults through vault-scoped operations.
