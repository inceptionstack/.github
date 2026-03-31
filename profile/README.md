<div align="center">

# InceptionStack ⚡

### Your AI agent that lives in your AWS account

*Deploy a stateful, always-on AI ops partner — builds code, infrastructure, and deployments inside your own AWS account.*

---

**[Get Started →](https://github.com/inceptionstack/loki-agent)**

</div>

## Loki Agent

An open-source AI agent that runs 24/7 in your AWS account. It writes code, provisions infrastructure, sets up CI/CD, configures security, and debugs production issues — all using standard AWS services. No vendor lock-in, no proprietary runtime. You own everything it builds.

Choose your agent runtime: **OpenClaw** (full stateful gateway, multi-channel) or **Hermes** (lightweight CLI agent by Nous Research).

```bash
curl -sfL https://raw.githubusercontent.com/inceptionstack/loki-agent/main/install.sh -o /tmp/loki-install.sh && bash /tmp/loki-install.sh
```

**[Read more →](https://github.com/inceptionstack/loki-agent)**

## Repositories

| Repo | Description |
|------|-------------|
| **[loki-agent](https://github.com/inceptionstack/loki-agent)** | Deploy templates (CloudFormation, SAM, Terraform), pack system, bootstrap scripts, brain files |
| **[loki-skills](https://github.com/inceptionstack/loki-skills)** | Agent skills library — AWS infrastructure, observability, payments, and more (OpenClaw + Hermes) |
| **[bedrockify](https://github.com/inceptionstack/bedrockify)** | OpenAI-compatible proxy for Amazon Bedrock — chat completions + embeddings in one binary |
| **[ai-patterns](https://github.com/inceptionstack/ai-patterns)** | AI Agent Architecture Patterns — definitions, naming, and design considerations |

## Links

- **[Wiki & Docs](https://github.com/inceptionstack/loki-agent/wiki)** — Deployment guide, bootstrap scripts, architecture
- **[OpenClaw](https://github.com/openclaw/openclaw)** — Stateful agent engine (gateway, memory, multi-channel)
- **[Hermes](https://github.com/NousResearch/hermes-agent)** — CLI agent by Nous Research (skills, learning loop, lightweight)

---

<div align="center">

Apache 2.0 · Contributions welcome

</div>
