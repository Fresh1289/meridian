<p align="center">
  <img src="assets/meridian-banner.png" width="600" alt="Meridian" />
</p>

<p align="center">
  <strong>🚀 The multi-agent orchestration platform for AI-native developers.</strong>
</p>

<p align="center">
  <em>Replace yourself as the communication bus between parallel coding agents.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/⚠️_Beta-Active_Development-f59e0b?style=flat-square&labelColor=1a1a2e" />
</p>

<p align="center">
  <a href="#-download--setup"><img src="https://img.shields.io/badge/Download-v1.5.0_Beta-7c3aed?style=for-the-badge&logo=apple&logoColor=white" /></a>
  &nbsp;
  <a href="#-download--setup"><img src="https://img.shields.io/badge/Download-Windows-7c3aed?style=for-the-badge&logo=windows&logoColor=white" /></a>
  &nbsp;
  <a href="https://discord.gg/nvkEWVu5Wx"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  &nbsp;
  <a href="#-features"><img src="https://img.shields.io/badge/Features-→-4f46e5?style=for-the-badge" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.5.0-0a0a0f?style=flat-square&labelColor=1a1a2e&color=7c3aed" />
  <img src="https://img.shields.io/badge/platform-macOS_|_Windows_|_Linux-0a0a0f?style=flat-square&labelColor=1a1a2e&color=4f46e5" />
  <img src="https://img.shields.io/badge/commits-770+-0a0a0f?style=flat-square&labelColor=1a1a2e&color=059669" />
  <img src="https://img.shields.io/badge/agents_tested-20-0a0a0f?style=flat-square&labelColor=1a1a2e&color=f59e0b" />
  <img src="https://img.shields.io/badge/IPC_channels-130+-0a0a0f?style=flat-square&labelColor=1a1a2e&color=0ea5e9" />
  <img src="https://img.shields.io/badge/Electron_41-React_19-0a0a0f?style=flat-square&labelColor=1a1a2e&color=0ea5e9" />
</p>

<br />

> ### What's New in v1.5.0 — Reliability & Flat Design
>
> **Massive reliability sprint.** 11 rounds, 25 commits, 72 issues identified and fixed from dogfood sessions.
>
> **Reliability:** Universal action logger (every action timestamped), auto-merge clean builds, auto-approve relays, hash-based loop detection with auto-restart, atomic relay processing, exclusive merge locks, graceful agent lifecycle, bounded resource management.
>
> **Flat Design:** GitHub-inspired aesthetic — glassmorphism killed, solid backgrounds, 1px borders, no shadows, muted agent colors, snappy 150ms transitions. The UI disappears so you see the work.
>
> **Laniakea Mentat v2:** Batch intelligence engine replacing per-event regex. Decision-point advisory, outcome tracking, knowledge quality gates.

<br />

<p align="center">
  <img src="assets/screenshot-chat.png" width="100%" alt="Meridian — 10 agents spawned from a single prompt" />
</p>

<p align="center">
  <sub>☝️ One prompt. 10 agents deployed. Full hierarchical team with leads, builders, QA, designer, and laniakea.</sub>
</p>

<br />

---

<br />

## 😤 The Problem

You run Claude Code in 3-10 terminal tabs in parallel. Each session is powerful on its own.

> **But you are the bottleneck.**

You read output from one agent. Copy context to another. Decide who works on what. Resolve conflicts. Relay messages. Manage state. The agents are fast. **You are the slowest link in the chain.**

As agent teams scale, this gets worse. More tabs, more context-switching, more dropped balls. The human communication bus doesn't scale.

Some tools claim to solve this with CLI wrappers, YAML configs, and buzzword architectures. They'll tell you they have "Q-learning routers" and "Byzantine consensus" and "neural self-optimization." But when you actually try to use them, nothing happens — because the agents are just state objects in memory, not real processes doing real work.

**Meridian takes a different approach.** Every agent is a real subprocess. Every message is actually delivered. Every node on the topology is a live process you can watch, talk to, pause, or kill. No theater. No simulated orchestration. Just agents that actually run.

<br />

## ✨ Features

### 🧠 Manager Agent — Your AI Team Lead
- Natural language task delegation — describe what you want, Manager builds the team
- Dynamic agent deployment — right team for each project (builders, designers, QA, scribe)
- Automatic task routing, progress tracking, and conflict resolution
- Hardcoded system prompt — Manager cannot be overridden or manipulated

### 🗺️ Real-Time Topology
- Live node graph of every agent — status, context usage, active files
- Canvas 2D rendering with GSAP state animations
- Click any node to inspect, message, restart, or kill
- Pipeline visualization — 5-stage phase rail (Plan → Build → Review → Test → Ship)

### 💬 Relay System
- SQLite-backed message routing with ACK, retry, and dead-letter queue
- Auto-approve relays by default — hands-off operation
- Manual intercept mode for sensitive operations
- Full delivery tracking with status badges

### 🔀 Git Workflow
- Auto-commit in agent worktrees
- Merge approval with inline diffs and typecheck gate
- Auto-merge clean builds by default
- Branch switcher, commit history, PR creation via `gh` CLI

### 🌌 Laniakea — Institutional Memory
- Batch intelligence engine — periodic LLM analysis, not per-event regex
- Decision-point advisory — consults before merges, spawns, and on errors
- Cross-project knowledge transfer
- Conversational `/lk` interface, feedback loop, Drive tab

### 🛡️ Reliability
- Universal action logger — every action timestamped to JSONL
- Hash-based loop detection with auto-restart (max 2x, then halt)
- Atomic relay processing, exclusive merge locks
- Graceful agent lifecycle — SIGINT → 3s → SIGTERM
- Bounded resources — capped caches, timers, maps
- Circuit breaker, health monitoring, crash recovery

### 🖥️ Built-in Terminal
- Integrated terminal for running your app
- Multiple terminal instances
- Full PTY support

### 📊 Multi-Project
- Switch between projects from the top navbar
- Each project gets its own agent team, sessions, and knowledge base
- Agent behavior configs carry over between projects

<br />

## 📥 Download & Setup

### macOS (Apple Silicon + Intel)

1. **Download** the latest `.dmg` from [Releases](https://github.com/Fresh1289/meridian/releases)
2. **Install** — drag to Applications
3. **First launch** — right-click → Open (bypasses Gatekeeper for unsigned beta)
4. **Prerequisites** — install Claude Code CLI:
   ```bash
   npm install -g @anthropic-ai/claude-code
   ```

### Windows

1. Download the `.exe` installer from [Releases](https://github.com/Fresh1289/meridian/releases)
2. Run the installer
3. Install Claude Code CLI: `npm install -g @anthropic-ai/claude-code`

### Linux

1. Download `.AppImage` or `.deb` from [Releases](https://github.com/Fresh1289/meridian/releases)
2. Make executable: `chmod +x Meridian-*.AppImage`
3. Install Claude Code CLI: `npm install -g @anthropic-ai/claude-code`

> ⚠️ **Important**: The standalone Claude Code installer (`curl`) is not supported. You must use `npm install`.

<br />

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Electron 41 |
| Frontend | React 19, TypeScript, Tailwind CSS 4 |
| Topology | Canvas 2D + GSAP |
| Database | SQLite (better-sqlite3) + Supabase |
| Terminal | node-pty + xterm.js |
| AI Agents | Claude Code CLI (subprocess) |
| Security | V8 bytecode (bytenode) + encrypted ASAR |

<br />

## 📜 License

Proprietary. See [LICENSE](LICENSE) for details.

<br />

---

<p align="center">
  <sub>Built with ☕ by <a href="https://github.com/Fresh1289">@Fresh1289</a> — and a swarm of AI agents.</sub>
</p>
