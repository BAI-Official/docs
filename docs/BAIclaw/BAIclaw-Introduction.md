---
id: baiclaw-intro
title: BAIclaw
sidebar_position: 1
slug: /
---

## Introduction

**BAIclaw** is a personal AI agent application built on [OpenClaw](https://openclaw.ai/) and [ClawX](https://github.com/ValueCell-ai/ClawX/blob/main/README.md). BAIclaw inherits the core capabilities of OpenClaw while providing users with an out-of-the-box experience and graphical user interface.

For more tips and tricks, refer to the [OpenClaw Documentation](https://docs.openclaw.ai/)

---

## Core Features

### 🎯 Out-of-the-Box

Complete all configurations from installation to conversation entirely through the graphical user interface (GUI), with no need to execute terminal commands or manually write configuration files.

### 💬 Smart Interaction Interface

- **Immersive Experience:** Supports multi-session context management, history retention, and Markdown rich text rendering.
- **Agent Direct Routing:** Supports precise routing via the `@agent` command in the main input box. After switching, you'll directly enter the target Agent's independent conversation context, rather than being forwarded through the default Agent.

### 📡 Channel Management

- **Independent Operation:** Supports configuring multiple independently running AI channels to adapt to specific task flows.
- **Account Binding:** Each channel supports multi-account management. Users can complete Agent account binding and default account switching directly on the Channels page.

### ⏰ Automated Scheduling

Customizable triggers and time intervals, combined with preset scheduled tasks, enable AI Agents to perform 7×24 hour uninterrupted automated execution.

### 🧩 Skill Extension System

- **No Package Manager Required:** Built-in integrated skill panel, supporting skill browsing, installation, and management.
- **Pre-installed Skills:** Automatically deploys document processing skills (PDF, XLSX, DOCX, PPTX) and common search skills to the managed directory (default `~/.openclaw/skills`) on startup.
- **Source Tracking:** Automatically identifies and displays skill sources from the managed directory, workspace, and additional directories, supporting direct navigation to the skill's physical installation path.

### ⚙️ System Settings

- **Adaptive Theme:** Supports light, dark mode, or follows system global settings.
- **Auto-start on Boot:** Supports configuring automatic startup after system login in 【Settings → General】.

---

## Quick Start

### System Requirements

- **Operating System:** macOS 11+
- **Memory:** Minimum 4GB RAM (8GB recommended)
- **Storage:** 1GB available disk space

### First Launch

When launching BAIclaw for the first time, the **Setup Wizard** will guide you through the following steps:

1. **Language & Region** – Configure your preferred language and region
2. **Add BANK OF AI Model** – Enter the BANK OF AI API Key to get top-tier large model capabilities (see: [Get API Key](./Get-API-Key.md))
3. **Skill Pack** – Choose pre-configured skills for common scenarios
4. **Verification** – Test your configuration before entering the main interface

---

## Core Pages

| Page | Description |
|------|-------------|
| **Chat** | The core interface for real-time conversation with AI agents, supporting multi-turn dialogue, message rendering, and input interaction |
| **Models** | Configure and manage AI model providers (OpenAI, Claude, Gemini, etc.), set default models and API Keys |
| **Agents** | Add and manage multiple AI agents |
| **Channels** | Connect and manage external communication platforms (Telegram, Discord, etc.), enabling message sending and receiving |
| **Skills** | Install and manage AI skills/plugins, extending agent capabilities (such as browser control, file processing, etc.) |
| **Scheduled Tasks** | Create and manage automated scheduled tasks, periodically triggering AI to execute workflows, achieving 7×24 hour uninterrupted operation |
| **Settings** | Global application configuration, including appearance, notifications, proxy, and other advanced options |
