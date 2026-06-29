# Awesome Claw 🦞

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Claw - Curated OpenClaw Alternatives &amp; AI Agents" width="100%">
</p>

<div align="center">

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a> [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ishandutta2007/awesome-awesome-awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br />
<br />
<a href="https://github.com/ishandutta2007?tab=followers">
  <img alt="followers" title="Follow me on Github" src="https://custom-icon-badges.herokuapp.com/github/followers/ishandutta2007?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/>
</a>

<h1>Curated OpenClaw Alternatives &amp; Local AI Gateways</h1>

> A curated directory of **open-source GitHub projects**, local AI agents, and lightweight gateway alternatives to **[OpenClaw](https://github.com/openclaw/openclaw)**.

</div>

## 🔍 Overview

**OpenClaw** is a popular TypeScript gateway for persistent AI agents across messaging applications. This curated repository highlights the best **OpenClaw alternatives** and **ecosystem resources** that support self-hosting, local execution, messaging integrations (like Telegram, WhatsApp, and Discord), with a strong emphasis on privacy, minimal resource footprint, and security.

Whether you need a lightweight Python CLI, a micro-binary written in Rust or Zig, or a container-isolated assistant, this list helps you choose the perfect local AI gateway for your infrastructure.

---

## 📖 Table of Contents
- [🏆 Original](#-original)
- [🤖 Multi-Agent & Specialized](#-multi-agent--specialized)
- [📚 Awesome Lists & Ecosystems](#-awesome-lists--ecosystems)
- [🪶 Lightweight & Minimal](#-lightweight--minimal)
- [🛡️ Secure & Reimplementations](#-secure--reimplementations-rustziggo)
- [🚫 No-LLM / Safe Alternatives](#-no-llm--safe-alternatives)
- [📊 How to Choose](#-how-to-choose)

---

## 🏆 Original

| Project | Description | Stars |
| :--- | :--- | :--- |
| **[OpenClaw](https://github.com/openclaw/openclaw)** [![Stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social&color=white)](https://github.com/openclaw/openclaw/stargazers) | The full-featured personal AI assistant. Multi-channel messaging, skills, voice, canvas, 24/7 gateway. (TypeScript) | `377k+` |

## 🤖 Multi-Agent & Specialized

*   **[FreeClaw](https://github.com/openconstruct/freeclaw)** [![Stars](https://img.shields.io/github/stars/openconstruct/freeclaw?style=social&color=white)](https://github.com/openconstruct/freeclaw/stargazers)  
    *Minimal Python CLI.* NVIDIA NIM / OpenRouter / Groq compatible.

*   **[ClawSwarm](https://github.com/The-Swarm-Corporation/ClawSwarm)** [![Stars](https://img.shields.io/github/stars/The-Swarm-Corporation/ClawSwarm?style=social&color=white)](https://github.com/The-Swarm-Corporation/ClawSwarm/stargazers)  
    *Multi-agent version.* Built on Swarms framework. Natively multi-agent, Telegram-first, compiles to Rust.

## 📚 Awesome Lists & Ecosystems

*   **[VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills)** [![Stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social&color=white)](https://github.com/VoltAgent/awesome-openclaw-skills/stargazers) — 5,400+ skills for the OpenClaw ecosystem.
*   **[rohitg00/awesome-openclaw](https://github.com/rohitg00/awesome-openclaw)** [![Stars](https://img.shields.io/github/stars/rohitg00/awesome-openclaw?style=social&color=white)](https://github.com/rohitg00/awesome-openclaw/stargazers) — Resources, comparisons, tutorials.
*   **[machinae/awesome-claws](https://github.com/machinae/awesome-claws)** [![Stars](https://img.shields.io/github/stars/machinae/awesome-claws?style=social&color=white)](https://github.com/machinae/awesome-claws/stargazers) — Curated list of all Claw-inspired agents.
*   **[LAMBDASOFT-org/awesome-openclaw-ecosystem](https://github.com/LAMBDASOFT-org/awesome-openclaw-ecosystem)** [![Stars](https://img.shields.io/github/stars/LAMBDASOFT-org/awesome-openclaw-ecosystem?style=social&color=white)](https://github.com/LAMBDASOFT-org/awesome-openclaw-ecosystem/stargazers) — Infrastructure, tools, and alternative agents.

## 🪶 Lightweight & Minimal

*   **[Nanobot](https://github.com/HKUDS/nanobot)** [![Stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social&color=white)](https://github.com/HKUDS/nanobot/stargazers)  
    *Ultra-lightweight Python alternative.* ~4,000 lines, 99% smaller. Easy pip install, 8+ messaging channels, China platform support.

*   **[PicoClaw](https://github.com/sipeed/picoclaw)** [![Stars](https://img.shields.io/github/stars/sipeed/picoclaw?style=social&color=white)](https://github.com/sipeed/picoclaw/stargazers)  
    *Tiny single-binary Go implementation.* Runs on $10 edge hardware (Raspberry Pi, RISC-V), <10 MB RAM, sub-second startup.

*   **[NullClaw](https://github.com/nullclaw/nullclaw)** [![Stars](https://img.shields.io/github/stars/nullclaw/nullclaw?style=social&color=white)](https://github.com/nullclaw/nullclaw/stargazers)  
    *Smallest & fastest.* 678 KB Zig static binary, <2 ms boot, ~1 MB RAM. Zero dependencies, perfect for microcontrollers.

*   **[Mini-Claw](https://github.com/htlin222/mini-claw)** [![Stars](https://img.shields.io/github/stars/htlin222/mini-claw?style=social&color=white)](https://github.com/htlin222/mini-claw/stargazers)  
    *Minimalist Telegram bot.* Uses Pi agent. No extra API costs — uses your Claude/ChatGPT subscription directly.

## 🛡️ Secure & Reimplementations (Rust/Zig/Go)

*   **[ZeroClaw](https://github.com/zeroclaw-labs/zeroclaw)** [![Stars](https://img.shields.io/github/stars/zeroclaw-labs/zeroclaw?style=social&color=white)](https://github.com/zeroclaw-labs/zeroclaw/stargazers)  
    *Fast, tiny Rust framework.* <5 MB RAM. Autonomous runtime with model/tool/memory swapping. Excellent for production/low-power.

*   **[NanoClaw](https://github.com/qwibitai/nanoclaw)** [![Stars](https://img.shields.io/github/stars/qwibitai/nanoclaw?style=social&color=white)](https://github.com/qwibitai/nanoclaw/stargazers)  
    *Container-isolated agents.* For true OS-level security. ~500 lines core, WhatsApp + scheduled jobs + memory.

*   **[IronClaw](https://github.com/nearai/ironclaw)** [![Stars](https://img.shields.io/github/stars/nearai/ironclaw?style=social&color=white)](https://github.com/nearai/ironclaw/stargazers)  
    *Rust reimplementation.* Focused on privacy, memory safety, and WASM sandboxing. Full feature parity tracking.

## 🚫 No-LLM / Safe Alternatives

*   **[SafeClaw](https://github.com/princezuda/safeclaw)** [![Stars](https://img.shields.io/github/stars/princezuda/safeclaw?style=social&color=white)](https://github.com/princezuda/safeclaw/stargazers)  
    *Zero-LLM, rule-based.* Deterministic assistant. No prompt injection risk, text+voice, does ~90% of OpenClaw tasks for free.

*   **[BashClaw](https://github.com/shareAI-lab/bashclaw)** [![Stars](https://img.shields.io/github/stars/shareAI-lab/bashclaw?style=social&color=white)](https://github.com/shareAI-lab/bashclaw/stargazers)  
    *Pure Bash reimplementation.* No dependencies, no Node/Python runtime.

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

## ✨ Star History


[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Claw&type=date&legend=bottom-right)](https://www.star-history.com/#ishandutta2007/Awesome-Claw&type=date&legend=bottom-right)

---

<div align="center">

**Made with ❤️ for the Claw community**  
Last updated: March 2026

[**⬆ Back to Top**](#awesome-claw-)

</div>
