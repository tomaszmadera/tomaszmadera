# Tomasz Madera
### Building agent-first developer tools & local workspaces

I build native, local-first environments that make AI coding agents usable in real engineering work: terminal PTY orchestration and deterministic workflows. Essays and experiments live at [quantumnoise.dev](https://quantumnoise.dev).

## Now building

**[NeKode](https://github.com/tomaszmadera/NeKode)** - the desktop workspace I spend my whole workday in. I wanted my coding agents, terminals and previews in one place, with only the features I actually use, as few clicks as possible, and a look I enjoy instead of another dull, corporate-looking tool. It runs CLI coding agents (Codex CLI, Claude Code, OpenCode, Gemini CLI) side by side on Windows 11.

- Native PTY sessions via `node-pty` + `xterm.js`, no cloud wrappers
- Local-first persistence in SQLite (`better-sqlite3`): workspaces, chats, layouts survive restarts
- Read-only Monaco editor and Markdown preview without leaving the agent context

**[Download the Windows installer](https://github.com/tomaszmadera/NeKode/releases/latest)**

<!-- [DEMO GIF/WebM: switching between agent sessions] -->

<!-- Enable when agent-harness is public:
**[agent-harness](https://github.com/tomaszmadera/agent-harness)** - a reproducible multi-agent task runner with deterministic verification gates and task records.
-->

## Also in the lab

- **[gitgeist](https://github.com/tomaszmadera/gitgeist)** - turns a Git repository into an emotional visual portrait.

## How I work

- **Proof of work over hype.** Every claim is backed by working code, benchmarks, or an ADR.
- **Local-first, low overhead.** Your tools, your machine, your data.
- **Deterministic where it matters.** Agents are stochastic; the harness around them shouldn't be.
- **Honest trade-offs.** Bugs, edge cases, and dead ends get documented, not hidden.

## Elsewhere

[quantumnoise.dev](https://quantumnoise.dev) · [X](https://x.com/quantumnoisedev)
