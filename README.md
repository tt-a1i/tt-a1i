## Hi, I'm tt-a1i

**Building tools for AI coding agents.** Currently exploring multi-agent simulation, long-term memory for LLMs, and the developer infrastructure that makes AI coding assistants observable, memorable, and verifiable.

---

### Orchestration & Collaboration — [@mco-org](https://github.com/mco-org)
*Neutral orchestration and collaboration layers for AI coding agents.*

- **[mco](https://github.com/mco-org/mco)** — Orchestrate AI coding agents. Any prompt × any agent × any IDE — works with Claude Code, Codex CLI, Gemini CLI, OpenCode, and Qwen Code, from Cursor, Trae, Copilot, Windsurf, or plain shell. `Python`
- **[squad](https://github.com/mco-org/squad)** — Multi-AI agent terminal collaboration tool. `Rust`

### Claude Code Skills — [@awesome-skills](https://github.com/awesome-skills)
*A curated collection of skills I've authored for Claude Code.*

- **[code-review-skill](https://github.com/awesome-skills/code-review-skill)** — Comprehensive code review skill covering React 19, Vue 3, Rust, TypeScript, TanStack Query v5, and more.
- **[first-principles-skill](https://github.com/awesome-skills/first-principles-skill)** — Systematic first-principles thinking — analyze designs, challenge assumptions, build from fundamental truths.
- **[5-whys-skill](https://github.com/awesome-skills/5-whys-skill)** — Five-Whys root cause analysis based on Toyota Production System methodology.
- **[mobile-app-design](https://github.com/awesome-skills/mobile-app-design)** — Mobile UI/UX design skill — iOS, Android, accessibility, React Native best practices.
- **[mermaid-syntax-skill](https://github.com/awesome-skills/mermaid-syntax-skill)** — Generate error-free Mermaid diagrams; handles special characters, reserved words, and escaping.
- **[memex](https://github.com/awesome-skills/memex)** — Local full-text search engine for Claude Code and Codex session history.
- **[manim-skill](https://github.com/awesome-skills/manim-skill)** — Manim animation skill — create programmatic animations for technical blogs and educational content.

### AI Coding Infrastructure
*Make AI agents more observable, memorable, and verifiable.*

- **[agmon](https://github.com/tt-a1i/agmon)** — htop for AI Agents. Real-time token cost and tool-call observability across Claude Code and Codex, with TUI and web dashboard. `Go`
- **[archify](https://github.com/tt-a1i/archify)** — Claude Skill that turns plain-language descriptions into export-ready architecture diagrams with dark/light themes and 4× PNG/SVG export.
- **[agent-inspect](https://github.com/tt-a1i/agent-inspect)** — Parallel multi-agent code audit slash command for Claude Code, OpenCode, and Codex CLI.
- **[evermemos-mcp](https://github.com/tt-a1i/evermemos-mcp)** — MCP memory server giving AI coding assistants persistent cross-session recall — benchmarked 60/60 accuracy on EverMemOS Cloud. `Python · MCP`
- **[vscode-ai-commit](https://github.com/tt-a1i/vscode-ai-commit)** — VS Code extension that streams AI-generated commit messages from staged diffs with commitlint awareness. `TypeScript`

### LLM Applications & Simulations
*From multi-agent worlds to AI-powered editors and durable memory.*

- **[MiroFish-local](https://github.com/tt-a1i/MiroFish-local)** — Local-privacy edition of the MiroFish multi-agent social simulation. Replaces Zep Cloud with Graphiti + Neo4j; runs fully air-gapped. `Python · Neo4j`
- **[chat_edit](https://github.com/tt-a1i/chat_edit)** — Dual-mode AI app combining streaming chat and rich-text AI editing, with Mermaid, Monaco diff, multi-format export, offline-first storage. `Vue 3.5 · TypeScript`
- **[mnemo](https://github.com/tt-a1i/mnemo)** — AI assistant with three-layer durable memory (episodic / semantic / procedural) that reconstructs full session context from EverMemOS Cloud. `Next.js · FastAPI`

### Reference & Utilities
*Built to ship — or to understand.*

- **[coding-cli-guide](https://github.com/tt-a1i/coding-cli-guide)** — 158-page interactive visual guide to Gemini CLI internals: Agent Loop, tool scheduling, security sandboxing, MCP. [Live demo](https://tt-a1i.github.io/coding-cli-guide/). `React 19 · Vite 7`
- **[pkg-analyzer](https://github.com/tt-a1i/pkg-analyzer)** — Published npm CLI that visualizes node_modules size, duplicates, and unused deps, with clipboard export for AI-powered optimization. `TypeScript`
