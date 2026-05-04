# Apprentice

![Version](https://img.shields.io/badge/version-v1.0.0--beta.1-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![Status](https://img.shields.io/badge/status-alpha-orange)
![License](https://img.shields.io/badge/license-Proprietary-red)
[![Discord](https://img.shields.io/badge/chat-Discord-5865F2)](https://discord.gg/WmWxYbeJuu)

**Run AI agents on your own machine. No cloud. No per-run fees. Sandboxed in Docker.**

Apprentice is a cross-platform desktop app for building, running, and monitoring autonomous AI agents locally. Each agent lives in its own Docker container with a budget, permissions, guardrails, and memory, triggered by messaging channels, webhooks, or cron schedules.

> **Status:** Beta (v1.0.0-beta.1). The agentic core is complete and stabilizing toward beta.

This is **not** a coding IDE, chat client, or terminal wrapper. Apprentice is an **agent runtime** for people who want automations that run on their own hardware.

## What you can do

* **Security first**: nothing runs on your host. Every agent executes inside its own Docker container, isolated from your files, network, and other agents by default.
* **Create agents in a guided wizard**: identity, model, instructions, permissions, guardrails, budget.
* **Run agents in sandboxed Linux containers**, each as an isolated OS user with scoped filesystem, shell, and network access.
* **Trigger from anywhere**: Telegram, Discord, Slack, Signal, WhatsApp, Email (IMAP/SMTP), webhooks, or cron.
* **Control cost** with per-agent budget caps (daily, weekly, monthly resets), token limits, and overrun actions (pause, notify, hard-stop).
* **Enforce safety** via AI-moderated guardrails, directory allow-lists, command allow and block-lists, and website filtering.
* **Give agents memory** through persistent knowledge bases with local semantic embeddings. No external API.
* **Let agents browse the web** with isolated sessions per agent. Credentials and cookies stay scoped to each agent, and you choose what to share across them.
* **Use your own provider**: BYO Claude subscription, or run fully local via LM Studio. No vendor lock-in.
* **Audit everything your agent does**: every tool call, message, cost, and decision is logged locally so you can review exactly what happened and why.

## Who it's for

Practically anyone who wants automations that don't live in someone else's cloud.

* **Indie operators and solo founders** automating lead triage, support intake, content monitoring, and personal research.
* **Small businesses and startups** running back-office automations without paying per-seat SaaS for every workflow.
* **Privacy-conscious professionals** (lawyers, therapists, accountants, consultants) who can't send client data to cloud SaaS.
* **Self-hosters and homelab users** who want agentic workflows on their own servers.
* **Agencies** building white-labelable automations for clients.
* **Curious tinkerers** who just want to see what local, sandboxed AI agents can do.

## Requirements

* **Windows, macOS, or Linux**
* **Docker** (Docker Desktop on Windows and macOS, Docker Engine on Linux)
* **At least one AI provider**: an active Claude subscription, or a local LLM via LM Studio

## Community

Join the Discord: [discord.gg/WmWxYbeJuu](https://discord.gg/WmWxYbeJuu)

## Links

* **Website:** https://apprentice.viberden.com
* **Downloads and releases:** [Releases](../../releases)
* **Report an issue:** [Issues](../../issues)

---

© 2026 Triple Bits. Proprietary software. Community Edition is free for personal and commercial use within tier limits.

*Built for the builders* with love by [Ilgıt Yıldırım](https://triplebits.com).
