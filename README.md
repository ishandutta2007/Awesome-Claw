# Awesome Claw 🦞

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated list of **open-source GitHub projects** similar to **[OpenClaw](https://github.com/openclaw/openclaw)**.

OpenClaw is the viral original (200k+ stars): a full-featured TypeScript gateway for persistent AI agents across chat apps. This list focuses on alternatives that are self-hosted, run locally, integrate with messaging platforms, and emphasize privacy, lightness, or security.

---

## 📖 Table of Contents
- [🏆 Original](#-original)
- [🪶 Lightweight & Minimal](#-lightweight--minimal)
- [🛡️ Secure & Reimplementations](#-secure--reimplementations-rustziggo)
- [🚫 No-LLM / Safe Alternatives](#-no-llm--safe-alternatives)
- [🤖 Multi-Agent & Specialized](#-multi-agent--specialized)
- [📚 Awesome Lists & Ecosystems](#-awesome-lists--ecosystems)
- [📊 How to Choose](#-how-to-choose)

---

## 🏆 Original

| Project | Description | Stars |
| :--- | :--- | :--- |
| **[OpenClaw](https://github.com/openclaw/openclaw)** | The full-featured personal AI assistant. Multi-channel messaging, skills, voice, canvas, 24/7 gateway. (TypeScript) | `200k+` |

## 🪶 Lightweight & Minimal

*   **[Nanobot](https://github.com/HKUDS/nanobot)**  
    *Ultra-lightweight Python alternative.* ~4,000 lines, 99% smaller. Easy pip install, 8+ messaging channels, China platform support.

*   **[PicoClaw](https://github.com/sipeed/picoclaw)**  
    *Tiny single-binary Go implementation.* Runs on $10 edge hardware (Raspberry Pi, RISC-V), <10 MB RAM, sub-second startup.

*   **[NullClaw](https://github.com/nullclaw/nullclaw)**  
    *Smallest & fastest.* 678 KB Zig static binary, <2 ms boot, ~1 MB RAM. Zero dependencies, perfect for microcontrollers.

*   **[Mini-Claw](https://github.com/htlin222/mini-claw)**  
    *Minimalist Telegram bot.* Uses Pi agent. No extra API costs — uses your Claude/ChatGPT subscription directly.

## 🛡️ Secure & Reimplementations (Rust/Zig/Go)

*   **[IronClaw](https://github.com/nearai/ironclaw)**  
    *Rust reimplementation.* Focused on privacy, memory safety, and WASM sandboxing. Full feature parity tracking.

*   **[ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw)**  
    *Fast, tiny Rust framework.* <5 MB RAM. Autonomous runtime with model/tool/memory swapping. Excellent for production/low-power.

*   **[NanoClaw](https://github.com/qwibitai/nanoclaw)**  
    *Container-isolated agents.* For true OS-level security. ~500 lines core, WhatsApp + scheduled jobs + memory.

## 🚫 No-LLM / Safe Alternatives

*   **[SafeClaw](https://github.com/princezuda/safeclaw)**  
    *Zero-LLM, rule-based.* Deterministic assistant. No prompt injection risk, text+voice, does ~90% of OpenClaw tasks for free.

*   **[BashClaw](https://github.com/shareAI-lab/bashclaw)**  
    *Pure Bash reimplementation.* No dependencies, no Node/Python runtime.

## 🤖 Multi-Agent & Specialized

*   **[ClawSwarm](https://github.com/The-Swarm-Corporation/ClawSwarm)**  
    *Multi-agent version.* Built on Swarms framework. Natively multi-agent, Telegram-first, compiles to Rust.

*   **[FreeClaw](https://github.com/openconstruct/freeclaw)**  
    *Minimal Python CLI.* NVIDIA NIM / OpenRouter / Groq compatible.

## 📚 Awesome Lists & Ecosystems

*   **[machinae/awesome-claws](https://github.com/machinae/awesome-claws)** — Curated list of all Claw-inspired agents.
*   **[rohitg00/awesome-openclaw](https://github.com/rohitg00/awesome-openclaw)** — Resources, comparisons, tutorials.
*   **[LAMBDASOFT-org/awesome-openclaw-ecosystem](https://github.com/LAMBDASOFT-org/awesome-openclaw-ecosystem)** — Infrastructure, tools, and alternative agents.
*   **[VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills)** — 5,400+ skills for the OpenClaw ecosystem.

---

## 📊 How to Choose

| Project | Language | RAM Footprint | Security Focus | Best For |
| :--- | :--- | :--- | :--- | :--- |
| **OpenClaw** | TS | `1GB+` | App-level | Full-featured daily driver |
| **Nanobot** | Python | `~100MB` | Medium | Quick start, China support |
| **PicoClaw** | Go | `<10MB` | Medium | Edge / Raspberry Pi |
| **NullClaw** | Zig | `~1MB` | High (static bin) | Ultra-low-power hardware |
| **ZeroClaw** | Rust | `<5MB` | High (WASM) | Production / low-power |
| **IronClaw** | Rust | `~500MB` | Very High | Privacy-first |
| **NanoClaw** | TS | `~200MB` | Very High (containers) | Security paranoid users |
| **SafeClaw** | Python | `Minimal` | Extreme (no LLM) | Zero-risk / offline |

> **Note:** Stars & activity change fast — check the repos for latest metrics.

---

<div align="center">

**Made with ❤️ for the Claw community**  
Last updated: March 2026

[**⬆ Back to Top**](#awesome-claw-)

</div>
