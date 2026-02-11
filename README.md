# 🦞 Awesome OpenClaw Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=social)](https://github.com/mergisi/awesome-openclaw-agents)

> A curated collection of AI agent templates, MCP servers, tools, and resources for the OpenClaw ecosystem. Every template is a copy-paste ready SOUL.md file.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=180&section=header&text=%F0%9F%A6%9E%20Awesome%20OpenClaw%20Agents&fontSize=36&fontColor=ffffff&fontAlignY=35" width="100%"/>
</p>

<div align="center">

**Don't want to set up manually?**

[**Deploy any agent with Docker + Telegram in 5 minutes →**](https://crewclaw.com/create-agent)

CrewClaw packages your SOUL.md with Dockerfile, Telegram bot, and deployment config. No code required.

</div>

---

## Contents

- [Agent Templates](#agent-templates)
  - [Productivity](#productivity)
  - [Development](#development)
  - [Marketing & Content](#marketing--content)
  - [Business](#business)
  - [Personal](#personal)
- [MCP Servers](#mcp-servers)
- [Integrations](#integrations)
- [Tools](#tools)
- [Tutorials & Guides](#tutorials--guides)
- [Community](#community)

---

## Agent Templates

Ready-to-use SOUL.md templates for your AI agents. Copy the SOUL.md, register with `openclaw agents add`, and start the gateway.

```bash
# Quick start with any template
git clone https://github.com/mergisi/awesome-openclaw-agents.git
openclaw agents add my-agent --workspace ./awesome-openclaw-agents/agents/productivity/orion
openclaw gateway start
```

### Productivity

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [🎯 Orion](agents/productivity/orion/) | Task coordinator and project manager | [View](agents/productivity/orion/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/project-manager-soul-md) |
| [📋 TaskMaster](agents/productivity/taskmaster/) | Advanced task breakdown and tracking | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [📅 CalendarBot](agents/productivity/calendar-bot/) | Schedule management and reminders | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [📧 InboxZero](agents/productivity/inbox-zero/) | Email triage and response drafting | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [🎯 FocusGuard](agents/productivity/focus-guard/) | Deep work session manager | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |

### Development

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [💻 CodeReviewer](agents/development/code-reviewer/) | PR review and code quality checks | Coming soon | [Deploy →](https://crewclaw.com/create-agent/code-reviewer-soul-md) |
| [🐛 BugHunter](agents/development/bug-hunter/) | Debugging assistant and error analyzer | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [📚 DocWriter](agents/development/doc-writer/) | Documentation generator | Coming soon | [Deploy →](https://crewclaw.com/create-agent/technical-writer-soul-md) |
| [🔧 DevOpsBot](agents/development/devops-bot/) | CI/CD and infrastructure helper | Coming soon | [Deploy →](https://crewclaw.com/create-agent/devops-engineer-soul-md) |
| [🧪 TestCrafter](agents/development/test-crafter/) | Test case generator | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [🏗️ Architect](agents/development/architect/) | System design consultant | Coming soon | [Deploy →](https://crewclaw.com/create-agent/software-engineer-soul-md) |

### Marketing & Content

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [✍️ Echo](agents/marketing/echo/) | Content writer for blogs, social, emails | [View](agents/marketing/echo/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/content-writer-soul-md) |
| [🐦 TweetCrafter](agents/marketing/tweet-crafter/) | Viral Twitter/X thread creator | Coming soon | [Deploy →](https://crewclaw.com/create-agent/social-media-manager-soul-md) |
| [🔍 SEOExpert](agents/marketing/seo-expert/) | SEO optimization specialist | Coming soon | [Deploy →](https://crewclaw.com/create-agent/seo-specialist-soul-md) |
| [📰 NewsletterPro](agents/marketing/newsletter-pro/) | Email newsletter writer | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [🎨 CopyMaster](agents/marketing/copy-master/) | Sales and ad copy specialist | Coming soon | [Deploy →](https://crewclaw.com/create-agent/copywriter-soul-md) |
| [📱 SocialScheduler](agents/marketing/social-scheduler/) | Multi-platform content planner | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |

### Business

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [📊 Radar](agents/business/radar/) | Data analyst and insights generator | [View](agents/business/radar/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/data-analyst-soul-md) |
| [💼 CEOAssistant](agents/business/ceo-assistant/) | Executive support and decision helper | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [📈 SalesCoach](agents/business/sales-coach/) | Sales strategy and outreach | Coming soon | [Deploy →](https://crewclaw.com/create-agent/sales-representative-soul-md) |
| [🤝 CustomerSuccess](agents/business/customer-success/) | Customer support and retention | Coming soon | [Deploy →](https://crewclaw.com/create-agent/customer-support-soul-md) |
| [📑 ContractReviewer](agents/business/contract-reviewer/) | Legal document analyzer | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [💰 FinanceAdvisor](agents/business/finance-advisor/) | Budget and financial planning | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |

### Personal

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [🏠 HomeManager](agents/personal/home-manager/) | Household task coordinator | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [🏋️ FitnessCoach](agents/personal/fitness-coach/) | Workout and nutrition planner | Coming soon | [Deploy →](https://crewclaw.com/create-agent/fitness-coach-soul-md) |
| [📖 LearningBuddy](agents/personal/learning-buddy/) | Study assistant and tutor | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [✈️ TravelPlanner](agents/personal/travel-planner/) | Trip planning and booking helper | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |
| [🧘 MindfulBot](agents/personal/mindful-bot/) | Mental wellness companion | Coming soon | [Deploy →](https://crewclaw.com/create-agent) |

---

## Quick Deploy with CrewClaw

Don't want to configure manually? [CrewClaw](https://crewclaw.com/create-agent) generates a complete deployment package for any agent:

```
Your CrewClaw package includes:
├── agents/your-agent/SOUL.md    # Agent configuration
├── Dockerfile                    # Container setup
├── docker-compose.yml            # One-command deploy
├── bot.js                        # Telegram bot (grammy)
├── .env.example                  # API keys template
├── package.json                  # Dependencies
└── README.md                     # Setup instructions
```

**Single agent: $9** | **Team of 3 agents: $19** | **Free: Copy SOUL.md only**

[Create your agent →](https://crewclaw.com/create-agent)

---

## MCP Servers

Model Context Protocol servers to extend agent capabilities.

### Official

| Server | Description | Install |
|--------|-------------|---------|
| [@anthropic/mcp-server-fetch](https://github.com/anthropics/mcp-server-fetch) | Web fetching and browsing | `npx -y @anthropic/mcp-server-fetch` |
| [@anthropic/mcp-server-filesystem](https://github.com/anthropics/mcp-server-filesystem) | File system access | `npx -y @anthropic/mcp-server-filesystem` |

### Community

| Server | Description |
|--------|-------------|
| mcp-notion | Notion integration |
| mcp-google-calendar | Google Calendar access |
| mcp-github | GitHub operations |
| mcp-slack | Slack messaging |
| mcp-postgres | PostgreSQL queries |
| mcp-stripe | Stripe payments |
| mcp-shopify | Shopify store management |
| mcp-twitter | Twitter/X posting |
| mcp-discord | Discord bot integration |
| mcp-linear | Linear issue tracking |

---

## Integrations

Connect your agents to external services.

### Messaging

- **Telegram** - Chat with agents via Telegram (built-in to OpenClaw)
- **Slack** - Slack workspace connection (built-in to OpenClaw)
- **Discord** - Discord server bot (built-in to OpenClaw)
- **Email** - Email channel (built-in to OpenClaw)

### Automation

- **n8n** - n8n integration nodes
- **GitHub Actions** - CI/CD integration
- **Cron / pm2 / systemd** - Always-on agent scheduling

---

## Tools

Utilities and helpers for working with OpenClaw.

| Tool | Description |
|------|-------------|
| [openclaw CLI](https://crewclaw.com/blog/openclaw-cli-commands-reference) | Official CLI - complete command reference |
| agent-validator | Validate SOUL.md syntax |
| mcp-tester | Test MCP server connections |

---

## Tutorials & Guides

Learn how to build and deploy agents.

### Getting Started

- [What is OpenClaw?](https://crewclaw.com/blog/what-is-openclaw-ai-agent-framework) - Complete guide to the framework
- [Create Your First Agent](https://crewclaw.com/blog/how-to-create-ai-agent-openclaw) - No code required
- [OpenClaw Setup Guide 2026](https://crewclaw.com/blog/openclaw-setup-guide-2026) - Install, configure, run
- [SOUL.md Templates](https://crewclaw.com/blog/soul-md-examples-templates) - 10 ready-to-use examples

### Multi-Agent & Orchestration

- [Multi-Agent Setup Guide](https://crewclaw.com/blog/openclaw-multi-agent-setup-guide) - Run multiple agents together
- [Agent-to-Agent Communication](https://crewclaw.com/blog/openclaw-agent-to-agent-communication) - How agents collaborate
- [Build an AI Team](https://crewclaw.com/blog/build-ai-team-workflows) - Workflows that run autonomously

### Integrations & Automation

- [Slack & Telegram Integration](https://crewclaw.com/blog/openclaw-slack-telegram-integration) - Connect to messaging channels
- [Run with Ollama](https://crewclaw.com/blog/openclaw-ollama-local-agents) - Free local AI agents
- [Automation Guide](https://crewclaw.com/blog/openclaw-automation-guide) - Build 24/7 workflows
- [CLI Commands Reference](https://crewclaw.com/blog/openclaw-cli-commands-reference) - Complete cheat sheet

### Comparisons

- [OpenClaw vs LangChain](https://crewclaw.com/blog/openclaw-vs-langchain) - Framework comparison
- [OpenClaw vs AutoGPT](https://crewclaw.com/blog/openclaw-vs-autogpt) - Key differences
- [OpenClaw vs CrewAI](https://crewclaw.com/blog/openclaw-vs-crewai) - Which is better?

---

## Community

### Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md).

#### How to Add an Agent

1. Fork this repository
2. Create folder: `agents/[category]/[agent-name]/`
3. Add `SOUL.md` and `README.md`
4. Submit a Pull Request

#### Agent Template

```markdown
# Agent Name

Brief description of what this agent does.

## Use Cases

- Use case 1
- Use case 2

## Setup

openclaw agents add agent-name --workspace ./agents/agent-name

## Example Prompts

- "Example prompt 1"
- "Example prompt 2"
```

---

## Related Projects

- [🦀 CrewClaw](https://crewclaw.com) - Deploy and orchestrate AI agents as a team. No code required.
- [OpenClaw](https://github.com/openclaw) - Official OpenClaw repository
- [Anthropic MCP](https://github.com/anthropics/mcp) - Model Context Protocol

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=mergisi/awesome-openclaw-agents&type=Date)](https://star-history.com/#mergisi/awesome-openclaw-agents&Date)

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

---

<p align="center">
  Made with 🦞 by the OpenClaw Community
  <br/>
  <a href="https://crewclaw.com/create-agent">Deploy your agent with CrewClaw →</a>
</p>
