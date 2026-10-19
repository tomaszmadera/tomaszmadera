# Tomasz Madera
### Building agent-first developer tools & local workspaces

I build native, local-first environments that make AI coding agents usable in real engineering work: terminal PTY orchestration, passive attention signals, and deterministic workflows. Essays and experiments live at [quantumnoise.dev](https://quantumnoise.dev).

## Now building

**[NeKode](https://github.com/tomaszmadera/NeKode)** - a desktop workspace for running multiple CLI coding agents (Codex CLI, Claude Code, OpenCode, Gemini CLI) side by side on Windows 11.

- Native PTY sessions via `node-pty` + `xterm.js`, no cloud wrappers
- Amber attention badge driven by terminal bell and OSC 9 signals from agents
- Local-first persistence in SQLite (`better-sqlite3`): workspaces, chats, layouts survive restarts
- Read-only Monaco editor and Markdown preview without leaving the agent context

<!-- Enable after the first NeKode release:
**[Download the Windows installer](<installer-release-url>)**
-->

<!-- [DEMO GIF/WebM: attention badge firing, switching between agent sessions] -->

<!-- Enable when agent-harness is public:
**[agent-harness](https://github.com/tomaszmadera/agent-harness)** - a reproducible multi-agent task runner with deterministic verification gates and task records.
-->

<!-- Enable when the gitgeist README is in English:
## Also in the lab

- **[gitgeist](https://github.com/tomaszmadera/gitgeist)** - turns a Git repository into an emotional visual portrait.
-->

## How I work

- **Proof of work over hype.** Every claim is backed by working code, benchmarks, or an ADR.
- **Local-first, low overhead.** Your tools, your machine, your data.
- **Deterministic where it matters.** Agents are stochastic; the harness around them shouldn't be.
- **Honest trade-offs.** Bugs, edge cases, and dead ends get documented, not hidden.

## Elsewhere

[quantumnoise.dev](https://quantumnoise.dev)
<!-- Add when handles are set: · [X](https://x.com/<handle>) · <contact> -->
