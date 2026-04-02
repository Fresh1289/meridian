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
  <a href="#-download--setup"><img src="https://img.shields.io/badge/Download-v1.4.0_Beta-7c3aed?style=for-the-badge&logo=apple&logoColor=white" /></a>
  &nbsp;
  <a href="#-download--setup"><img src="https://img.shields.io/badge/Download-Windows-7c3aed?style=for-the-badge&logo=windows&logoColor=white" /></a>
  &nbsp;
  <a href="https://discord.gg/nvkEWVu5Wx"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  &nbsp;
  <a href="#-features"><img src="https://img.shields.io/badge/Features-→-4f46e5?style=for-the-badge" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.4.0-0a0a0f?style=flat-square&labelColor=1a1a2e&color=7c3aed" />
  <img src="https://img.shields.io/badge/platform-macOS_|_Windows_|_Linux-0a0a0f?style=flat-square&labelColor=1a1a2e&color=4f46e5" />
  <img src="https://img.shields.io/badge/commits-740+-0a0a0f?style=flat-square&labelColor=1a1a2e&color=059669" />
  <img src="https://img.shields.io/badge/agents_tested-20-0a0a0f?style=flat-square&labelColor=1a1a2e&color=f59e0b" />
  <img src="https://img.shields.io/badge/IPC_channels-130+-0a0a0f?style=flat-square&labelColor=1a1a2e&color=0ea5e9" />
  <img src="https://img.shields.io/badge/Electron_41-React_19-0a0a0f?style=flat-square&labelColor=1a1a2e&color=0ea5e9" />
</p>

<br />

> ### What's New in v1.4.0 — Full Stack
>
> **Major integrations release.** Git workflow, Obsidian two-way sync, and Laniakea intelligence engine.
>
> **Git:** Commit history with inline diffs, branch switcher, auto-commit in agent worktrees, PR creation via `gh` CLI.
>
> **Obsidian:** Knowledge entries as proper `.md` with YAML frontmatter + wikilinks. Auto-generated session notes. state.md auto-sync. Two-way: edit in Obsidian → Laniakea picks it up. Topology → Canvas export.
>
> **Laniakea:** LLM-powered CONSULT, predictive warnings, contradiction detection, conversational `/lk` chat, feedback loop, smart spawn briefing, cross-project knowledge transfer, Drive tab.
>
> **Command Palette:** Cmd+K — fuzzy search across everything.

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

---

<br />

## 💡 What Meridian Does

Meridian is a **native desktop app** that removes you from the middle.

You talk to **one agent** — the **Manager**. Manager handles everything else: analyzing your request, deploying the right team, routing work between agents, and reporting back when it's done.

You see everything happening in real time on a **visual topology**. One chat. Full visibility. No context-switching. No YAML. No config files. No learning a CLI.

<br />

| | Without Meridian | With Meridian |
|:---|:---|:---|
| 🖥️ | 6 terminal tabs open | 1 app window |
| 📋 | Copy-pasting between agents | Automatic routing |
| 🧠 | You decide who does what | Manager decides |
| 🔀 | You resolve merge conflicts | Manager handles git |
| 💭 | Context lost across sessions | Laniakea remembers everything |
| 🔇 | Agents don't know about each other | Full inter-agent communication |
| 📄 | Reading docs to configure YAML | Delaniakea your project in English |

<br />

---

<br />

## 📦 8 Built-In Templates — 60 Agents from 430k+ Stars

<p align="center">
  <img src="https://img.shields.io/badge/8_Templates-60_Agents-7c3aed?style=for-the-badge" />
  &nbsp;
  <img src="https://img.shields.io/badge/430k+_Stars-Combined-f59e0b?style=for-the-badge&logo=github&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/One_Click-Deploy-059669?style=for-the-badge" />
</p>

<br />

**We took the 8 most popular Claude Code workflows on GitHub and turned them into one-click agent teams.**

Every template ships built into Meridian. Pick one, click Apply, and Manager deploys the full team — each role becomes a **real parallel agent** on your topology. No config. No YAML. No setup.

These workflows have **430,000+ combined GitHub stars**. They're incredible prompt systems. But they all share the same limitation: one agent pretending to be 15 different roles. When gstack runs `/review`, it's the same process that just ran `/ship`. No parallelism. No shared memory. No visibility.

**Meridian makes them real.**

<br />

```
CLI workflow (single agent):   Plan → Build → Review → Test → Ship
                               ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
                               One process. One role at a time.

Meridian (real agents):        Planner ━━━━━━┓
                               Builder ━━━━━━┫
                               Reviewer ━━━━━╋━━→ Manager orchestrates
                               Tester ━━━━━━━┫    all in parallel
                               Security ━━━━━┛
```

<br />

### The Templates

| Template | Source | Stars | Agents | What It Does |
|:---|:---|---:|:---:|:---|
| **gstack** | [Garry Tan](https://github.com/garrytan/gstack) | 54k | 8 | Full engineering org — CEO review, eng review, design, QA, security, shipping |
| **Superpowers** | [Jesse Vincent](https://github.com/obra/superpowers) | 122k | 7 | 7-phase pipeline — brainstorm, plan, execute, TDD, code review, debug, ship |
| **Everything Claude Code** | [Affaan Mustafa](https://github.com/affaan-m/everything-claude-code) | 115k | 8 | Production agent harness — planner, architect, security, TDD, build resolution |
| **GSD** | [TACHES](https://github.com/gsd-build/get-shit-done) | 44k | 7 | Wave-based parallel execution — research, plan, execute, verify, audit |
| **Agents** | [Seth Hobson](https://github.com/wshobson/agents) | 32k | 6 | Team-based orchestration — lead, implement, review, debug, secure, benchmark |
| **Ruflo** | [ruvnet](https://github.com/ruvnet/ruflo) | 28k | 7 | Hierarchical swarm — queen coordinator, domain architects, quality gates |
| **SuperClaude** | [SuperClaude Org](https://github.com/SuperClaude-Org/SuperClaude_Framework) | 22k | 7 | Cognitive architecture — frontend/backend/system architects, quality + security |
| **Oh My Claude Code** | [Yeachan Heo](https://github.com/Yeachan-Heo/oh-my-claudecode) | 15k | 10 | Full 19-agent org — analyst, architect, planner, executor, designer, QA, verifier |

<br />

### How It Works

1. **Pick a template** — browse the 8 built-in options in the Templates panel
2. **Click Apply** — Manager reads the template and deploys every agent
3. **Real agents spawn** — each role becomes a live subprocess on the topology
4. **Start building** — the team is ready. Just delaniakea what you want.

Or **paste any GitHub URL** — Meridian clones the repo, parses the skill files, and builds a custom template on the fly.

<br />

### Why This Matters

| | CLI Workflows | Meridian Templates |
|:---|:---|:---|
| 🤖 Roles | 1 agent switching personas | **Each role = real parallel agent** |
| ⚡ Speed | Sequential — one role at a time | **Parallel — all roles simultaneously** |
| 🧠 Memory | Context lost between role switches | **Laniakea tracks all inter-agent communication** |
| 🗺️ Visibility | Terminal output scrolling past | **Live topology map of every agent** |
| 🔄 Recovery | Start over if context resets | **Auto-restart with exponential backoff** |
| 📊 Cost tracking | None | **Per-agent token + cost breakdown** |

<br />

### Import Your Own

Templates aren't locked to our 8 built-ins. The system supports any workflow that uses markdown-based role definitions:

- **GitHub repos** — paste any URL, Meridian clones and parses
- **Local directories** — import from your filesystem
- **Your own workflows** — package your agent team as a shareable template

> **Think Docker Hub, but for AI agent teams.** Pick a template, deploy the team, start building.

<br />

---

<br />

## ✨ Features

<br />

### 🗺️ Visual Agent Topology

<p align="center">
  <img src="assets/screenshot-topology.png" width="100%" alt="Agent Topology" />
</p>

Real-time org chart of your agent team rendered on **Canvas 2D**. Each node shows the agent's role, status, and model. Connection lines animate when agents communicate — idle dash crawl, active packet animation. Top-down layout with Manager at the center, leads below, sub-agents beneath.

This isn't a text log you scroll through. It's a **live, visual map** of your entire agent team — what they're doing, who they're talking to, and whether they're healthy. **No other multi-agent tool has this.** Not as a CLI flag. Not as a dashboard. Not as an afterthought. It's the core of the experience.

<br />

### ⚡ Real Agents, Not State Objects

Every agent in Meridian is a **real CLI subprocess** — a full Claude Code process with its own working directory, config, and lifecycle.

| | Other Tools | Meridian |
|:---|:---|:---|
| 🤖 Agent type | In-memory state object | Real `child_process` subprocess |
| 📝 "Writes code" | Updates a JSON file | Actually writes to disk |
| 🧪 "Runs tests" | Returns simulated result | Tests actually execute |
| 💀 Crash recovery | State reset | Exponential backoff + auto-restart |
| 📊 Proof | Trust the marketing | Check Activity Monitor |

Some orchestrators manage agents as in-memory objects — they track state, update JSON files, and claim "100+ agents" while nothing actually executes. Meridian spawns real processes, monitors them with health checks, and restarts them with exponential backoff if they crash.

<br />

### 💬 One Chat, Full Control

<p align="center">
  <img src="assets/screenshot-dashboard.png" width="100%" alt="Manager Chat" />
</p>

Talk to Manager in natural language. Manager dispatches to the right agents, collects results, and reports back. **GitHub Copilot-style input** with model selector, file attachments, and full markdown rendering.

Every relay between agents is visible. You see exactly what Manager told the Builder, what the Builder responded, and what QA found. No black box. No "trust the swarm." 🔍

<br />

### 🛡️ Safety Gates (v1.2.0+)

Meridian now has **four layers of safety** between agent code and your codebase:

- **Worktree Isolation** — each builder agent works in its own git worktree. No clobbering.
- **Merge Approval UI** — diff review, approve/reject before any code lands on main
- **Relay Approval Panel** — intercept, edit, or drop any message between agents
- **Typecheck Gate** — `tsc --noEmit` runs in the merge flow. Broken code doesn't land.

<br />

### 🔄 Parallel DAG Dispatch (v1.2.0+)

Manager can now dispatch **up to 4 agents simultaneously** with dependency-aware scheduling. Tasks that don't depend on each other run in parallel. Agent locking prevents conflicts. Worktree-aware dispatch keeps builders isolated.

<br />

### 📡 Relay ACK + Dead Letter Queue (v1.2.0+)

Every inter-agent message is now **acknowledged**. SQLite-backed mail routing with 60-second timeouts, automatic retry, and a dead letter queue for messages that can't be delivered. No more fire-and-forget.

<br />

### 🎯 Dynamic Team Composition

There is no static agent list. No YAML files to configure. No "agent definitions" to write. **Manager is the only default agent.** When you delaniakea your project, Manager assembles the right team:

| Project Type | Team Deployed |
|:---|:---|
| 🔧 Backend-heavy | Manager + 3 Builders + QA + Laniakea |
| 🎨 Frontend/design-heavy | Manager + Builder + 2 Designers + QA + Laniakea |
| 🩹 Quick fix | Manager + Builder |
| 🏗️ Full-stack | Manager + 2 Builders + Designer + QA + Laniakea |

Agents appear on the topology as they're deployed. Manager can add, remove, or reassign agents mid-project based on what's needed. **You don't pre-configure your team — you delaniakea your goal and the team materializes.**

<br />

### 🧠 Laniakea — The Knowledge Engine

Laniakea is Meridian's crown jewel — an LLM-powered knowledge engine with total recall. Named after the cosmic supercluster that contains everything, it watches all agent communication and builds intelligence that compounds over time.

**Five capabilities:**
- **LLM-Powered CONSULT** — Ask anything. Laniakea retrieves relevant knowledge, sends it through Haiku for synthesis, and returns a cited, contextual answer. Not keyword search — actual reasoning.
- **Predictive Warnings** — Before you execute a plan, Laniakea checks it against historical failures: "3 similar plans failed. Common cause: no QA loop."
- **Contradiction Detection** — If Manager contradicts a past decision, Laniakea flags it in real-time: "This conflicts with the auth decision from March 30."
- **Decision Journaling** — Auto-extracts structured decisions from Manager output. Full audit trail of what was decided, why, and what alternatives were considered.
- **Conversational `/lk`** — Talk to Laniakea directly in chat. Ask "Why did we choose SQLite?" and get a synthesized narrative with source citations.

**It learns from feedback:** 👍/👎 on knowledge entries adjusts confidence scores. Good knowledge rises, bad knowledge decays. The system gets smarter the more you use it.

**Smart Spawn Briefing** — When any agent spawns, Laniakea injects the top 5 most relevant lessons for that role. Agents start with context, not a blank slate.

**Cross-Project Transfer** — Knowledge learned in Project A is available in Project B. Import with one click. Good patterns spread automatically.

**LaniakeaPanel** has 5 tabs: Timeline, Knowledge, Insights, Stats, and Drive (saved workflows + snippets + cross-project knowledge browser).

> 📂 Plain text JSONL on disk. Read it yourself. Search it with grep. Sync it to Obsidian.
> No proprietary binary format. No "memory engine" you can't inspect. LLM intelligence on top, not instead of.

<br />

### 🧙 Intelligence System — Effort Level + Wizard Mode

**Effort Level** gives you a 3-position dial on agent thinking depth:
- **Standard** — default behavior
- **Extended** — agents reason more carefully, consider edge cases, verify logic
- **Maximum** — deep analysis, exhaustive edge case coverage, double-checked output

**Wizard Mode** goes further — it enables **adversarial verification**. When active:

1. Agent produces output → sends to Manager
2. Manager **spawns a Critic agent** — an adversarial reviewer that assumes the output is wrong
3. Critic attacks: logic errors, edge cases, security issues, incorrect assumptions
4. Original agent defends: fixes real issues, justifies valid choices
5. They iterate until the Critic issues `VERDICT: APPROVED` (max 3 rounds)
6. Only battle-tested output gets delivered

The Critic is a real agent on the topology — you can watch the debate happen in real time. **No other multi-agent tool has built-in adversarial quality gates.**

> 🧪 Wizard Mode costs more tokens but catches bugs before they ship. Use it for critical features, skip it for quick fixes.

<br />

### 🔀 Mix Models Per Agent

Meridian currently runs on **Claude Code** — the most capable coding agent available. You can assign different Claude models to different agents:

- 🟣 **Opus** for Manager (planning + routing)
- 🔵 **Sonnet** for Builders (fast code generation)
- 🟡 **Haiku** for Laniakea (lightweight logging)

The right model for each job. Manager gets the big brain, builders get the fast one, utility agents get the cheap one. You control this per-agent from the settings panel.

> 🔮 **Coming soon:** Multi-provider support — run Codex, Gemini CLI, or any CLI agent alongside Claude. The architecture is designed for it.

<br />

### 🎛️ Human-in-the-Loop

You see everything. Every relay between agents, every decision Manager makes, every correction loop.

Intervene anytime:
- 🔀 Redirect work to a different agent
- ✏️ Adjust an agent's behavior mid-task
- ⏸️ Pause or kill an agent
- 🔄 Override Manager's routing

Manager rewrites agent configs on the fly based on your feedback. **The agents adapt to you**, not the other way around.

> 🛑 Autonomous agent swarms sound cool in demos. In practice, you want a kill switch.
> Meridian gives you one — plus full visibility into what's happening before you need to use it.

<br />

### 📡 Messages That Actually Arrive

Meridian's communication layer is built on **120+ typed IPC channels** between the Electron main process and the renderer.

```
Sub-agent → Lead → Manager → Lead → Sub-agent
     ✅        ✅       ✅       ✅       ✅
```

**14 end-to-end tests.** Including a **20-agent stress test** with full hierarchical routing. Messages don't get lost. Agents don't talk past each other. The communication bus works because it was **tested relentlessly**, not theorized about.

<br />

### 🖥️ Built-in Terminal

Run your app without leaving Meridian. Full shell access, embedded in the app. See your agents build it, then run it — same window. 🏃‍♂️

<br />

### 🎨 Industrial-Luxury Interface

<p align="center">
  <img src="assets/screenshot-settings.png" width="100%" alt="Settings and Configuration" />
</p>

**Mission control meets Linear.** Near-black base, agent-specific accent colors, glassmorphic panels, precise typography. Information-dense but clean. Every pixel considered.

Built with the same attention to craft as the tools you already use — GitHub, Linear, Vercel, Raycast. Not a CLI with a `--pretty` flag. Not a web dashboard bolted on after the fact. **A native desktop app designed from day one to be the interface.**

<br />

---

<br />

## 🚀 How It Works

<br />

### Step 1 — Sign in

<p align="center">
  <img src="assets/screenshot-login.png" width="720" alt="Sign in" />
</p>

GitHub OAuth or email. One click. No config files. No environment variables. No `npx init`. ✨

<br />

### Step 2 — Connect your AI provider

<p align="center">
  <img src="assets/screenshot-onboarding-cli.png" width="720" alt="Connect Claude" />
</p>

Meridian detects your Claude CLI automatically. Optionally add an API key for pay-per-token billing. Two options, one screen, done. ✅

<br />

### Step 3 — Delaniakea your project

<p align="center">
  <img src="assets/screenshot-onboarding-project.png" width="720" alt="Create Project" />
</p>

Name it, delaniakea what you're building, pick a directory. Meridian scaffolds the workspace with `.meridian/`, `.agents/`, and a `CLAUDE.md`. No YAML agent definitions to write. No topology configs to learn. **Just tell it what you're building.** 💬

<br />

### Step 4 — Manager assembles the team

<p align="center">
  <img src="assets/screenshot-chat.png" width="100%" alt="10 agents spawned" />
</p>

Manager reads your description and deploys the right agents — Frontend Lead, Backend Lead, QA, Designer, Laniakea, and sub-agents under each lead. **Each one is a real CLI process** with its own working directory. You watch the org chart populate in real time. 🎬

<br />

### Step 5 — Watch, iterate, ship

<p align="center">
  <img src="assets/screenshot-topology.png" width="100%" alt="Full topology" />
</p>

Agents code, review, and test. Manager orchestrates. Connection lines animate as messages flow. Ask for changes — Manager dispatches, agents fix, Manager reports. **Everything is committed to GitHub automatically.** 🚢

<br />

---

<br />

## 🏗️ Architecture

```
┌──────────────────────────────────────────────────────────┐
│                      Meridian App                         │
│                                                          │
│  ┌──────────────┐         ┌────────────────────────────┐ │
│  │  🔧 Electron  │         │  🎨 React 19 + Canvas 2D   │ │
│  │  Main Process │   IPC   │                            │ │
│  │               │◄───────►│  Topology · Chat ·         │ │
│  │  Agent        │   130+  │  Terminal · Settings ·     │ │
│  │  Spawner      │  chan   │  Vault · Status Bar        │ │
│  └──────┬───────┘         └────────────────────────────┘ │
│         │                                                │
│  ┌──────┴──────────────────────────────────────────────┐ │
│  │              🤖 Agent Processes                      │ │
│  │                                                      │ │
│  │  Manager · Builder · Designer · QA · Laniakea          │ │
│  │  (Claude Code — more providers coming soon)          │ │
│  └──────────────────────────────────────────────────────┘ │
└──────────────────────────────────────────────────────────┘
```

| Component | Technology | Why |
|:---|:---|:---|
| 🖥️ Runtime | **Electron** | Native performance, direct `child_process` spawning |
| ⚛️ UI | **React 19 + TypeScript + Tailwind 4** | Modern stack, domain-specific Zustand stores |
| 🗺️ Topology | **Canvas 2D** | Lightweight rendering — not WebGL, small bundle |
| 🔌 Bridge | **120+ IPC channels** | Typed, validated, bidirectional |
| 🤖 Agents | **Real CLI subprocesses** | Isolated worktrees, health monitoring, auto-restart |
| 🗄️ Storage | **SQLite (WAL mode)** | Specs, sessions, relay mail, agent state — all ACID |

> **No in-memory agent simulation.** No JSON file state management pretending to be orchestration. Real processes, real IPC, real results.

<br />

---

<br />

## 📊 How Meridian Compares

|  | Meridian | Claude Code Teams | Claude Squad | Opcode | Agentrooms |
|:---|:---:|:---:|:---:|:---:|:---:|
| 🤖 Multi-agent orchestration | ✅ | 🧪 Experimental | ❌ | ❌ | ⚠️ Limited |
| 🗺️ Visual topology | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🎯 Dynamic team composition | ✅ | ❌ | ❌ | ❌ | ❌ |
| ⚡ Real parallel agents | ✅ | ✅ | ✅ | ✅ | ⚠️ Partial |
| 🧠 LLM-powered knowledge engine | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🔮 Predictive warnings + contradiction detection | ✅ | ❌ | ❌ | ❌ | ❌ |
| ⌨️ Command palette (Cmd+K) | ✅ | ❌ | ❌ | ❌ | ❌ |
| 📦 Workflow templates | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🛡️ Merge approval + typecheck gate | ✅ | ❌ | ❌ | ❌ | ❌ |
| 📡 Relay ACK + dead letter queue | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🔀 Per-agent model selection | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🖥️ Native desktop app | ✅ | CLI | TUI | Tauri | Web |
| 🎛️ Human-in-the-loop | ✅ | ⚠️ Limited | ✅ | ✅ | ⚠️ Limited |
| 🧙 Adversarial verification | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🧪 Tested at 20 agents | ✅ | ❌ | ❌ | ❌ | ❌ |

<br />

---

<br />

## 🗺️ Roadmap

### ✅ v1.0 — Foundation
- [x] 🗺️ Visual agent topology with real-time status
- [x] 🎯 Dynamic team composition via Manager
- [x] 🧠 Laniakea agent for shared structured memory
- [x] 🔀 Per-agent model selection (Opus, Sonnet, Haiku)
- [x] 🖥️ Embedded terminal
- [x] 🔐 Supabase auth (GitHub OAuth + email)
- [x] 📦 One-click workflow templates — 8 built-in, 60 agents
- [x] 🔒 V8 bytecode + encrypted ASAR
- [x] 🪟 Windows + Linux support

### ✅ v1.1.0 — Laniakea Mentat + Reliability
- [x] 🧠 Laniakea Mentat wired — CONSULT/TEACH markers, knowledge injection
- [x] ⏱️ Request timeout (5 min) + circuit breaker (5 failures → cooldown)
- [x] 🔁 Manual retry re-sends messages
- [x] 📁 Files panel fixed — `~` paths resolve correctly
- [x] 🔄 Multi-project switching, per-project sessions, reinstall detection
- [x] 🧙 Intelligence System — Effort Level + Wizard Mode adversarial verification

### ✅ v1.2.0 — Battle Readiness (31 commits, ~2,300 lines)
- [x] 🛡️ Worktree isolation — agents work in isolated git worktrees
- [x] ✅ Merge approval UI — diff review, approve/reject before landing
- [x] 📨 Relay approval panel — intercept, edit, or drop any inter-agent message
- [x] 🔍 Typecheck gate — `tsc --noEmit` in merge flow, pass/fail badge
- [x] 💾 Session continuity — context snapshot survives resets
- [x] ⚡ Parallel DAG — concurrency 4, agent locking, worktree-aware dispatch
- [x] 📡 Relay ACK — SQLite mail routing, 60s timeout, auto-retry, dead letter queue
- [x] 📊 Context visibility — model-aware token calc, 70%/85% warnings, status bar
- [x] 🔄 Review loop — pipeline templates, execution engine, APPROVE/CORRECTION
- [x] 📝 Spec workflow — SQLite persistence, SpecPanel, auto-save directives
- [x] ⚡ Fast-track detection — auto-classify single-file tasks, `!fast`/`!full` override
- [x] 📋 Status dashboard — 5-section grid, auto-refresh

### ✅ v1.3.x — Immortal + Hardened (60+ commits)
- [x] 🔄 Manager hot-swap — dual slots, 70% context trigger, zero-downtime rotation
- [x] 🛡️ Master supervisor — Unix socket health pings, crash recovery, auto-restart
- [x] 🔁 Self-update engine — git watcher, typecheck gate, rollback on failure
- [x] 🔒 Security hardening — execFileSync, IPC try-catch, env whitelist, path validation
- [x] 📬 Relay ACK + deadletter — SQLite-backed delivery with exponential backoff retry
- [x] 💾 Session snapshot injection — context restored on agent reset
- [x] 🔐 Per-project file locks + worktree orphan cleanup
- [x] ⌨️ Full keyboard shortcuts (Ctrl/Cmd+1-9, 0, - for all panels)
- [x] 💰 Cost controls — 500K token budget, $5-50 warnings, 20 agent limit
- [x] 🎨 UI polish — dark dropdowns, z-index fixes, cancel button on project creation

### ✅ v1.3.4 — Laniakea (35+ commits)
- [x] 🧠 Laniakea — LLM-powered CONSULT (Haiku synthesis with source citations)
- [x] 🔮 Predictive warnings — risk analysis from historical failures
- [x] ⚡ Contradiction detection — auto-flags conflicting decisions
- [x] 📓 Decision journaling — auto-extracts structured decisions
- [x] 💬 Conversational `/lk` — talk to Laniakea directly in chat
- [x] 👍 Feedback loop — thumbs up/down adjusts knowledge confidence
- [x] 🎓 Smart spawn briefing — agents receive relevant lessons on start
- [x] 🔄 Cross-project knowledge transfer — import with one click
- [x] 🗂️ Drive — saved workflows, snippets, cross-project knowledge
- [x] ⌨️ Command Palette (Cmd+K) — fuzzy search across everything
- [x] 🔀 Worktree isolation active — code-writing agents get isolated branches
- [x] 📋 Pipeline automation — Designer→Builder→QA with auto-advancement
- [x] 📝 Spec auto-injection — active specs prepended on agent spawn
- [x] ✅ All audit items resolved — merge/relay approval, sign out, API key, fast-track
- [x] 🩺 Diagnostics panel + OTA patch system

### ✅ v1.4.0 — Full Stack
- [x] 📜 Git commit history panel with expandable inline diffs
- [x] 🔀 Branch switcher — list, checkout, create from status pill
- [x] 🤖 Auto-commit toggle — agent worktree changes committed automatically
- [x] 🔗 PR creation via `gh` CLI from the app
- [x] 📝 Obsidian knowledge as proper `.md` with YAML frontmatter + wikilinks
- [x] 📅 Auto-generated session notes on app quit
- [x] 🔄 state.md auto-sync with 30s debounce
- [x] ↔️ Two-way Obsidian sync — edit in Obsidian → Laniakea imports via fs.watch
- [x] 🗺️ Topology → Obsidian Canvas export

### 🔜 Coming Soon
- [ ] 🔓 Multi-provider support (Codex, Gemini CLI, any CLI agent alongside Claude)
- [ ] 🌐 Multi-machine orchestration — cluster your Mac Minis, distribute agents across machines
- [ ] 🧠 Context compaction — tiered eviction + LLM summarization
- [ ] 🪝 Hook system — lifecycle events, PreToolUse interception, middleware framework

### 🔮 Future
- [ ] 🏪 Agent marketplace
- [ ] 🎙️ Voice control
- [ ] 👥 Team collaboration (multiple humans, shared project)

<br />

---

<br />

## 💰 Pricing

### 🆓 Free — forever
Everything on a single machine. **No limits. No trials. No feature gates.**
Full orchestration, all agents, all models, all features.

### 💎 Pro — coming later
Multi-machine orchestration. Cluster your MacBook, Mac Mini, and build server into one fleet — distribute agents across hardware like exo does for inference, but for coding. Cloud sync. Team features.

> *We believe the single-machine experience should be completely free. You only pay when you need to scale beyond one computer.*

<br />

---

<br />

## 🛠️ Built With

<p align="center">
  <img src="https://img.shields.io/badge/Electron-41-47848F?style=for-the-badge&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Canvas_2D-native-F7DF1E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SQLite-WAL-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-auth-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

<br />

---

<br />

## 📥 Download & Setup

> **⚠️ Beta Software.** Meridian is under active development. Expect rough edges, breaking changes between versions, and occasional bugs. We ship fast and fix fast — check for updates regularly. Report issues on [GitHub](https://github.com/Fresh1289/meridian/issues) or [Discord](https://discord.gg/nvkEWVu5Wx).

<p align="center">
  <a href="https://github.com/Fresh1289/meridian/releases/latest"><img src="https://img.shields.io/badge/Mac_(Apple_Silicon)-v1.4.0_Beta-7c3aed?style=for-the-badge&logo=apple&logoColor=white" /></a>
  &nbsp;
  <a href="https://github.com/Fresh1289/meridian/releases/latest"><img src="https://img.shields.io/badge/Windows_(x64)-Installer-7c3aed?style=for-the-badge&logo=windows&logoColor=white" /></a>
  &nbsp;
  <a href="https://github.com/Fresh1289/meridian/releases/latest"><img src="https://img.shields.io/badge/Linux_(x64)-AppImage-7c3aed?style=for-the-badge&logo=linux&logoColor=white" /></a>
</p>

### Prerequisites

Before installing Meridian, you need two things:

**1. Node.js 18+**
```bash
# Check if installed:
node --version

# If not installed, download from https://nodejs.org/
# Or use nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
nvm install 22
```

**2. Claude Code (npm version)**
```bash
# Install Claude Code globally:
npm install -g @anthropic-ai/claude-code

# Authenticate:
claude auth login
# This opens your browser — sign in with your Anthropic account

# Verify it works:
claude --version
claude auth status
```

> ⚠️ **Important:** Meridian requires the **npm version** of Claude Code, not the standalone installer (`curl -fsSL https://claude.ai/install.sh`). The standalone binary uses a different format that Meridian cannot spawn. If you installed via curl, switch with: `npm install -g @anthropic-ai/claude-code`

**3. Claude Max plan or API key**
- **Claude Max** ($100/month or $200/month) — recommended, uses your plan credits directly
- **Anthropic API key** — pay-per-token, can be added during onboarding

### Setup — macOS (Apple Silicon)

```bash
# Step 1: Install prerequisites (if needed)
npm install -g @anthropic-ai/claude-code
claude auth login

# Step 2: Download the DMG
# → https://github.com/Fresh1289/meridian/releases/latest

# Step 3: Install
# Open the DMG → drag Meridian to Applications

# Step 4: Bypass Gatekeeper (app is unsigned)
# Option A: Right-click Meridian.app → Open → Click "Open" in the dialog
# Option B: Run in Terminal:
xattr -cr /Applications/Meridian.app

# Step 5: Launch Meridian
open /Applications/Meridian.app
```

**First launch walkthrough:**
1. **Sign in** — GitHub OAuth or email/password
2. **CLI check** — Meridian verifies Claude Code is installed and authenticated
3. **Create a project** — name it, delaniakea what you're building
4. **Start chatting** — Manager deploys agents and you're off

### Setup — Windows (x64)

```bash
# Step 1: Install prerequisites
npm install -g @anthropic-ai/claude-code
claude auth login

# Step 2: Download the installer
# → https://github.com/Fresh1289/meridian/releases/latest
# → Download Meridian.Setup.exe
```

3. **Run the installer** — Windows may show a SmartScreen warning → click "More info" → "Run anyway"
4. **Launch Meridian** — sign in, create a project, start building

### Setup — Linux (x64)

```bash
# Step 1: Install prerequisites
npm install -g @anthropic-ai/claude-code
claude auth login

# Step 2: Download
# → https://github.com/Fresh1289/meridian/releases/latest
# → Download Meridian.AppImage (or .deb)

# Step 3a: AppImage
chmod +x Meridian-*.AppImage
./Meridian-*.AppImage

# Step 3b: Debian/Ubuntu (.deb)
sudo dpkg -i meridian_*.deb
```

<br />

---

<br />

## ❓ FAQ

<details>
<summary><strong>What AI providers does Meridian support?</strong></summary>
<br />

Currently, Meridian runs on **Claude Code** (Anthropic). You can assign different Claude models (Opus, Sonnet, Haiku) to different agents. Multi-provider support (Codex, Gemini CLI, etc.) is on the roadmap — the architecture is built to support any CLI-based agent.

</details>

<details>
<summary><strong>Do I need a Claude API key?</strong></summary>
<br />

No. Meridian works with the **Claude CLI** using your Max plan credits — no API key required. If you prefer pay-per-token billing, you can optionally add an API key during onboarding.

</details>

<details>
<summary><strong>How many agents can I run at once?</strong></summary>
<br />

Meridian has been stress-tested with **20 concurrent agents** in a full hierarchical setup (leads, sub-agents, laniakea). In practice, most projects use 5-12 agents. Each agent is a real CLI process, so your limit is your machine's resources and API rate limits.

</details>

<details>
<summary><strong>Is this open source?</strong></summary>
<br />

The source code is currently private. This repo is a showcase of what Meridian is and does. We're evaluating open-source options for post-1.0.

</details>

<details>
<summary><strong>How is this different from just running multiple Claude Code sessions?</strong></summary>
<br />

When you run multiple Claude Code sessions yourself, **you** are the communication bus — reading output from one, pasting context into another, deciding who does what. Meridian replaces you in that role. Manager handles all inter-agent routing, Laniakea maintains shared memory, and the topology gives you real-time visibility into what every agent is doing. You go from being the bottleneck to being the overseer.

</details>

<details>
<summary><strong>How much does it cost to run?</strong></summary>
<br />

Meridian itself is **free**. Your cost is the AI usage — same as running Claude Code directly. A typical 10-agent session building a medium-sized feature costs roughly what 10 individual Claude Code sessions would cost. The difference is Meridian makes those 10 sessions work together instead of in isolation.

</details>

<details>
<summary><strong>What happens when an agent crashes?</strong></summary>
<br />

Meridian has **self-healing built in**. If an agent crashes, it automatically restarts with exponential backoff. If it keeps failing, Manager is notified and can reassign the work. Health monitoring runs continuously — you'll see the agent's status change on the topology in real time.

</details>

<details>
<summary><strong>Why Electron and not a web app?</strong></summary>
<br />

Meridian needs to spawn and manage CLI subprocesses (Claude Code, etc.) directly on your machine. A web app can't do that — it would need a local server or daemon, adding complexity. Electron gives us native process spawning, direct filesystem access, and a polished desktop experience in one package.

</details>

<br />

---

<br />

## 💬 Support

- **Bug reports & feature requests** → [GitHub Issues](https://github.com/Fresh1289/meridian/issues)
- **Questions & community** → [Discord](https://discord.gg/nvkEWVu5Wx)

<br />

---

<br />

<p align="center">
  <img src="assets/meridian-icon.svg" width="48" height="48" alt="" />
</p>

<p align="center">
  <code>740+ commits · 170+ source files · 140+ IPC channels · 87+ React components</code>
  <br />
  <code>11 SQLite tables · 14 end-to-end tests · 20-agent stress test cleared</code>
  <br /><br />
  <strong>⚡ Stop being the bottleneck.</strong>
  <br /><br />
  <a href="https://github.com/Fresh1289">
    <img src="https://img.shields.io/badge/Built_by-Matthew_Huang-7c3aed?style=flat-square&labelColor=1a1a2e" />
  </a>
</p>
