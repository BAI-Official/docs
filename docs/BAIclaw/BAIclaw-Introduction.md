---
sidebar_position: 1
slug: /
---

# BAIclaw Introduction

BAIclaw is a personal AI agent desktop application built on [OpenClaw](https://openclaw.ai/) and [ClawX](https://github.com/ValueCell-ai/ClawX/blob/main/README.md). It combines the power of OpenClaw with a graphical user interface, enabling users to have a complete personal AI assistant without writing code or configuration files.

![BAIclaw](assets/BAIclaw.png)

## The Problem It Solves

Traditional AI tools often face these challenges:

- **Complex Configuration**: Requires manually editing configuration files and using command-line operations
- **Limited Capabilities**: Only capable of conversation, unable to connect to external services or execute tasks automatically
- **Difficult Extension**: Adding new features requires programming knowledge

BAIclaw's design philosophy is to make AI agents **work out of the box** like ordinary applications, while retaining sufficient flexibility and extensibility.

## Architecture

```
┌─────────────────────────────────────┐
│           BAIclaw (GUI)             │  ← Graphical Interface, Zero-Config Experience
├─────────────────────────────────────┤
│            OpenClaw                 │  ← Agent Runtime, Extension Framework
├─────────────────────────────────────┤
│           BAI LLM API               │  ← Intelligence Source
└─────────────────────────────────────┘
```

- **OpenClaw**: Provides core capabilities including agent runtime, multi-channel communication, and task scheduling
- **BAIclaw**: Graphical wrapper that presents these capabilities through an intuitive interface

## Core Design

### Multi-Agent Collaboration

Unlike a single chatbot, BAIclaw supports configuring multiple specialized agents:

- Each agent has independent system prompts and context memory
- Quick switching via the `@agent` command, directly entering that agent's conversation context
- Different tasks can be routed to the most suitable agent for processing

### Channel-Based Communication

BAIclaw extends AI capabilities to the external world through **channels**:

- **Local Channel**: Chat interface within the desktop application
- **Messaging Platforms**: Bidirectional message synchronization with Telegram, Discord, WhatsApp, and other platforms
- **Each channel operates independently**, capable of binding to different agents and accounts

### Plug-and-Play Skills

Skills are the capability extension units of BAIclaw:

- Built-in skill panel, no package manager or command line required
- Automatically deploys document processing (PDF, Excel, Word, PPT) and search skills on startup
- Supports loading from multiple sources: built-in directory, workspace, and additional configuration directories

### Automated Workflows

Achieve 7×24 autonomous operation through scheduled tasks:

- Custom trigger conditions and time intervals
- Preset task templates for quick configuration of common scenarios
- Agents execute automatically according to schedule without manual intervention

## Interface Overview

BAIclaw's main interface consists of the following functional modules, working together to form a complete workflow:


| Module              | Purpose                                  | Typical Use Case                                   |
| ------------------- | ---------------------------------------- | -------------------------------------------------- |
| **Chat**            | Real-time conversation with AI agents    | Daily Q&A, multi-turn discussions, task delegation |
| **Models**          | Configure AI models and API keys         | Adding BAI API Key                          |
| **Agents**          | Manage multiple agent configurations     | Creating an agent specialized for code review      |
| **Channels**        | Connect external communication platforms | Integrating agents into Telegram groups            |
| **Skills**          | Install and manage capability extensions | Adding browser automation skills                   |
| **Scheduled Tasks** | Create timed automation tasks            | Setting up daily morning report generation         |
| **Settings**        | Application global configuration         | Appearance theme, proxy settings, auto-start       |


## Getting Started
:::warning[Compatibility Note]
If you have previously installed OpenClaw or ClawX, we recommend uninstalling and deleting the configuration directory (`~/.openclaw`) to avoid conflicts.
:::

If you're new to BAIclaw, we recommend following this order:

1. **Install the App**: Ensure your system is macOS 11+ with 4GB+ RAM
2. **Complete the Wizard**: Follow the setup wizard on first launch to complete basic configuration
3. **Get API Key**: Visit [Get API Key](./operation-guide/Get-API-Key.md) to obtain your BAI access key
4. **Start Chatting**: Have your first conversation with an agent on the Chat page



## Further Reading

- [OpenClaw Official Documentation](https://docs.openclaw.ai/) — Learn about the underlying runtimeruntime