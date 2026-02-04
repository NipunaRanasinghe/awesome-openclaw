# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [OpenClaw](https://openclaw.ai/) resources — tools, libraries, tutorials, workflows, extensions, skills, and practical examples for building with the open-source personal AI assistant. 🦞

[OpenClaw](https://github.com/openclaw/openclaw) is an open-source personal AI assistant you run on your own devices. It connects to the channels you already use (WhatsApp, Telegram, Slack, Discord, Signal, iMessage, and more), features voice capabilities, and offers a live Canvas for visual interactions.

## Contents

- [Official Resources](#official-resources)
- [Installation & Setup](#installation--setup)
- [Channels & Integrations](#channels--integrations)
- [Skills & Extensions](#skills--extensions)
- [Tools & Automation](#tools--automation)
- [Platforms & Apps](#platforms--apps)
- [Configuration & Customization](#configuration--customization)
- [Security](#security)
- [Development](#development)
- [Community](#community)
- [Tutorials & Guides](#tutorials--guides)
- [Videos & Talks](#videos--talks)
- [Related Projects](#related-projects)

## Official Resources

- [OpenClaw Repository](https://github.com/openclaw/openclaw) - The main open-source repository.
- [Official Documentation](https://docs.openclaw.ai/) - Comprehensive documentation and guides.
- [OpenClaw Website](https://openclaw.ai/) - Official project website.
- [DeepWiki](https://deepwiki.com/openclaw/openclaw) - Deep wiki for OpenClaw knowledge.
- [Discord Community](https://discord.gg/clawd) - Official Discord server for support and discussions.
- [ClawHub](https://clawhub.com/) - Official skills registry for discovering and sharing skills.

## Installation & Setup

### Installation Methods

- [Getting Started Guide](https://docs.openclaw.ai/start/getting-started) - Official beginner-friendly installation guide.
- [Onboarding Wizard](https://docs.openclaw.ai/start/wizard) - Interactive CLI wizard for guided setup.
- [Docker Installation](https://docs.openclaw.ai/install/docker) - Container-based deployment guide.
- [Nix Installation](https://github.com/openclaw/nix-clawdbot) - Declarative Nix-based configuration.
- [Updating Guide](https://docs.openclaw.ai/install/updating) - How to update OpenClaw to the latest version.
- [Development Channels](https://docs.openclaw.ai/install/development-channels) - Stable, beta, and dev release channels.

### Platform-Specific Setup

- [macOS Guide](https://docs.openclaw.ai/platforms/macos) - Setup and configuration for macOS.
- [Linux Guide](https://docs.openclaw.ai/platforms/linux) - Linux installation and configuration.
- [Windows (WSL2) Guide](https://docs.openclaw.ai/platforms/windows) - Windows setup using WSL2.
- [iOS Setup](https://docs.openclaw.ai/platforms/ios) - iOS node configuration.
- [Android Setup](https://docs.openclaw.ai/platforms/android) - Android node configuration.

## Channels & Integrations

OpenClaw supports multiple messaging platforms as channels for interaction.

### Messaging Platforms

- [WhatsApp](https://docs.openclaw.ai/channels/whatsapp) - WhatsApp integration using Baileys.
- [Telegram](https://docs.openclaw.ai/channels/telegram) - Telegram bot integration using grammY.
- [Slack](https://docs.openclaw.ai/channels/slack) - Slack workspace integration using Bolt.
- [Discord](https://docs.openclaw.ai/channels/discord) - Discord server integration using discord.js.
- [Signal](https://docs.openclaw.ai/channels/signal) - Signal messenger integration via signal-cli.
- [Google Chat](https://docs.openclaw.ai/channels/googlechat) - Google Chat integration via Chat API.
- [Microsoft Teams](https://docs.openclaw.ai/channels/msteams) - Microsoft Teams integration.
- [Matrix](https://docs.openclaw.ai/channels/matrix) - Matrix protocol integration.

### iMessage Integrations

- [BlueBubbles (Recommended)](https://docs.openclaw.ai/channels/bluebubbles) - Modern iMessage integration for macOS.
- [iMessage Legacy](https://docs.openclaw.ai/channels/imessage) - Legacy macOS-only iMessage integration.

### Additional Channels

- [Zalo](https://docs.openclaw.ai/channels/zalo) - Zalo messaging integration.
- [WebChat](https://docs.openclaw.ai/web/webchat) - Browser-based chat interface served from the Gateway.
- [Feishu/Lark](https://docs.openclaw.ai/channels/feishu) - Feishu/Lark messaging integration.

## Skills & Extensions

Skills extend OpenClaw's capabilities with specialized tools and integrations.

### Skills Platform

- [Skills Documentation](https://docs.openclaw.ai/tools/skills) - Understanding bundled, managed, and workspace skills.
- [Skills Configuration](https://docs.openclaw.ai/tools/skills-config) - Configuring and customizing skills.
- [ClawHub Registry](https://clawhub.com/) - Discover and install community skills.

### Built-in Tools

- [Browser Control](https://docs.openclaw.ai/tools/browser) - Automated Chrome/Chromium control with CDP.
- [Canvas](https://docs.openclaw.ai/platforms/mac/canvas) - Agent-driven visual workspace with A2UI.
- [Nodes](https://docs.openclaw.ai/nodes) - Camera, screen recording, location, and notifications.
- [Session Tools](https://docs.openclaw.ai/concepts/session-tool) - Multi-agent coordination via sessions.

## Tools & Automation

### Automation Features

- [Cron Jobs](https://docs.openclaw.ai/automation/cron-jobs) - Schedule recurring tasks and wakeups.
- [Webhooks](https://docs.openclaw.ai/automation/webhook) - HTTP webhook triggers for external events.
- [Gmail Pub/Sub](https://docs.openclaw.ai/automation/gmail-pubsub) - Email-triggered automation via Gmail.

### CLI Commands

- [Agent Commands](https://docs.openclaw.ai/tools/agent-send) - CLI interface for agent interactions.
- [Doctor Command](https://docs.openclaw.ai/gateway/doctor) - Diagnostics and health checks.

## Platforms & Apps

### Companion Applications

- [macOS App](https://docs.openclaw.ai/platforms/macos) - Menu bar app with Voice Wake, PTT, and WebChat.
- [macOS Menu Bar](https://docs.openclaw.ai/platforms/mac/menu-bar) - Control plane and health monitoring.
- [iOS Node](https://docs.openclaw.ai/platforms/ios) - Canvas, Voice Wake, Talk Mode, and camera integration.
- [Android Node](https://docs.openclaw.ai/platforms/android) - Canvas, Talk Mode, camera, and screen capture.

### Voice Features

- [Voice Wake](https://docs.openclaw.ai/nodes/voicewake) - Always-on voice activation.
- [Talk Mode](https://docs.openclaw.ai/nodes/talk) - Continuous conversation with ElevenLabs TTS.

### Visual Features

- [Canvas](https://docs.openclaw.ai/platforms/mac/canvas) - Agent-driven visual workspace.
- [A2UI](https://docs.openclaw.ai/platforms/mac/canvas#canvas-a2ui) - Agent-to-UI rendering system.
- [Control UI](https://docs.openclaw.ai/web/control-ui) - Web-based control interface.
- [Dashboard](https://docs.openclaw.ai/web/dashboard) - Gateway monitoring dashboard.

## Configuration & Customization

### Configuration

- [Full Configuration Reference](https://docs.openclaw.ai/gateway/configuration) - Complete settings documentation.
- [Gateway Configuration](https://docs.openclaw.ai/gateway) - Gateway setup and options.
- [Model Configuration](https://docs.openclaw.ai/concepts/models) - Configuring AI models.
- [Model Failover](https://docs.openclaw.ai/concepts/model-failover) - Auth rotation and fallback strategies.

### Prompt Templates

- [AGENTS Template](https://docs.openclaw.ai/reference/templates/AGENTS) - Agent behavior configuration.
- [SOUL Template](https://docs.openclaw.ai/reference/templates/SOUL) - Personality customization.
- [TOOLS Template](https://docs.openclaw.ai/reference/templates/TOOLS) - Tool availability configuration.
- [USER Template](https://docs.openclaw.ai/reference/templates/USER) - User context customization.

### Workspace

- [Workspace Structure](https://docs.openclaw.ai/concepts/workspace) - Understanding the workspace layout.
- [Default AGENTS](https://docs.openclaw.ai/reference/AGENTS.default) - Default agent configuration reference.

## Security

- [Security Guide](https://docs.openclaw.ai/gateway/security) - Comprehensive security documentation.
- [DM Policies](https://docs.openclaw.ai/gateway/security#dm-access) - Direct message access control.
- [Sandbox Mode](https://docs.openclaw.ai/gateway/configuration#sandbox) - Per-session Docker sandboxing.
- [Tailscale Integration](https://docs.openclaw.ai/gateway/tailscale) - Secure remote access via Tailscale.
- [Remote Access](https://docs.openclaw.ai/gateway/remote) - SSH tunnels and secure exposure.

## Development

### Architecture

- [Architecture Overview](https://docs.openclaw.ai/concepts/architecture) - Understanding the Gateway and protocol model.
- [Agent Loop](https://docs.openclaw.ai/concepts/agent-loop) - How the agent processes requests.
- [Session Model](https://docs.openclaw.ai/concepts/session) - Session management and isolation.
- [RPC Adapters](https://docs.openclaw.ai/reference/rpc) - Remote procedure call interfaces.

### Contributing

- [Contributing Guide](https://github.com/openclaw/openclaw/blob/main/CONTRIBUTING.md) - How to contribute to OpenClaw.
- [Development Setup](https://docs.openclaw.ai/platforms/mac/dev-setup) - Setting up a development environment.

### Technical Deep Dives

- [Presence System](https://docs.openclaw.ai/concepts/presence) - Online/offline status handling.
- [Queue System](https://docs.openclaw.ai/concepts/queue) - Message queuing and processing.
- [TypeBox Schemas](https://docs.openclaw.ai/concepts/typebox) - Schema validation system.
- [Streaming](https://docs.openclaw.ai/concepts/streaming) - Response streaming and chunking.

## Community

- [Discord Server](https://discord.gg/clawd) - Official community chat.
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Community Q&A and discussions.
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Bug reports and feature requests.
- [Twitter/X](https://x.com/openclaw) - Official social media.

### Notable Contributors

- [Peter Steinberger](https://steipete.me/) - Project creator.
- [Mario Zechner](https://mariozechner.at/) - Pi-mono contributor.

## Tutorials & Guides

### Getting Started

- [Onboarding Tutorial](https://docs.openclaw.ai/start/onboarding) - Step-by-step first-time setup.
- [FAQ](https://docs.openclaw.ai/start/faq) - Frequently asked questions.
- [Showcase](https://docs.openclaw.ai/start/showcase) - Example use cases and demos.

### Troubleshooting

- [Troubleshooting Guide](https://docs.openclaw.ai/channels/troubleshooting) - Common issues and solutions.
- [Browser Troubleshooting (Linux)](https://docs.openclaw.ai/tools/browser-linux-troubleshooting) - Linux-specific browser issues.
- [Logging](https://docs.openclaw.ai/logging) - Debug logging configuration.

### Operations

- [Gateway Runbook](https://docs.openclaw.ai/gateway) - Operational procedures.
- [Health Checks](https://docs.openclaw.ai/gateway/health) - Monitoring gateway health.
- [Background Process](https://docs.openclaw.ai/gateway/background-process) - Running as a background service.

## Videos & Talks

*Coming soon - Contributions welcome!*

## Related Projects

### AI Coding Assistants

- [Claude Code](https://github.com/anthropics/claude-code) - Terminal-based AI coding assistant by Anthropic.
- [Gemini CLI](https://github.com/Piebald-AI/awesome-gemini-cli) - Terminal-based AI coding assistant by Google.
- [Copilot Agents](https://github.com/Code-and-Sorts/awesome-copilot-agents) - AI pair programming by GitHub.

### Supporting Projects

- [Pi-mono](https://github.com/badlogic/pi-mono) - Agent runtime support.
- [soul.md](https://soul.md/) - Personality and soul configuration.

### Similar Awesome Lists

- [Awesome Claude Code](https://github.com/hesreallyhim/awesome-claude-code) - Resources for Claude Code.
- [Awesome ChatGPT](https://github.com/sindresorhus/awesome-chatgpt) - ChatGPT resources.
- [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) - Generative AI tools and resources.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
