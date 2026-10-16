# Hi, I build payment infrastructure for AI agents

I run [APIbase.pro](https://apibase.pro), an MCP and REST gateway where AI agents find and pay for real-world APIs per call, in USDC, with no accounts or API keys. Payments go over **x402** on Base or **MPP** on Tempo. Based in Bangkok.

### What I'm building

| Project | What it is | Links |
|---|---|---|
| **APIbase** | MCP + REST gateway: 1,400+ paid API tools from 400+ providers in 25 categories, one endpoint `https://apibase.pro/mcp`. Failed calls are not billed. | [site](https://apibase.pro) · [repo](https://github.com/whiteknightonhorse/APIbase) |
| **Integrator** (part of APIbase) | Agent checkout for online shops. One "Buy with your AI agent" link on a product page; the agent gets a fixed quote and pays the shop's wallet directly. APIbase never holds funds. | [apibase.pro/integrator](https://apibase.pro/integrator) |
| **MCP Protocol Tester** | Open-source test suite for paid MCP servers: discovery, x402 and MPP payment flows, replay and double-spend protection, payment-bypass attempts. | [repo](https://github.com/whiteknightonhorse/mcp-protocol-tester) |
| **Provek** | Measures how much of a company runs without a human in the loop, per business operation, with the evidence behind every number. Public registry of tested projects. | [provek.dev](https://provek.dev) · [repo](https://github.com/whiteknightonhorse/provek) · [method](https://github.com/whiteknightonhorse/provek-method) |
| **AIPUSH** | Free AEO analyzer: is a website ready for AI agents and answer engines? 0–100 score with copy-ready fixes. | [aipush.app](https://aipush.app) · [repo](https://github.com/whiteknightonhorse/AIpush) · [agent skills](https://github.com/whiteknightonhorse/aipush-agent-skills) |

### Listed on

[![Smithery](https://img.shields.io/badge/Smithery-Live-brightgreen)](https://smithery.ai/servers/apibase-pro/api-hub)
[![Glama](https://img.shields.io/badge/Glama-Live-blue)](https://glama.ai/mcp/servers/whiteknightonhorse/APIbase)
[![MCP Registry](https://img.shields.io/badge/MCP_Registry-Live-blue)](https://registry.modelcontextprotocol.io/v0/servers?search=apibase)
[![awesome-x402](https://img.shields.io/badge/awesome--x402-Listed-orange)](https://github.com/xpaysh/awesome-x402)

### Writing

| Date | Article |
|---|---|
| 2026-10-14 | [Your analytics shows AI agents on your site. Here is how we let them pay](https://dev.to/whiteknightonhorse/your-analytics-shows-ai-agents-on-your-site-here-is-how-we-let-them-pay-2afc) |
| 2026-10-06 | [Agents that shop: what a16z's Top 100 consumer AI data says about agentic commerce](https://dev.to/whiteknightonhorse/agents-that-shop-what-a16zs-top-100-consumer-ai-data-says-about-agentic-commerce-4e8) |
| 2026-05-27 | [Pay for any API from inside Claude with Base MCP + APIbase](https://dev.to/whiteknightonhorse/pay-for-any-api-from-inside-claude-with-base-mcp-apibase-443o) |
| 2026-05-19 | [What happens to the $0.001 when an AI agent pays for an API call](https://dev.to/whiteknightonhorse/what-happens-to-the-0001-when-an-ai-agent-pays-for-an-api-call-389a) |
| 2026-05-01 | [How we replaced our x402 payment facilitator in a single afternoon](https://dev.to/whiteknightonhorse/how-we-replaced-our-x402-payment-facilitator-in-a-single-afternoon-f84) |

All posts: [dev.to/whiteknightonhorse](https://dev.to/whiteknightonhorse)

### Community contributions

| Project | What | Status |
|---|---|---|
| [x402-foundation/x402](https://github.com/x402-foundation/x402/issues/1759) | Feedback: agent onboarding complexity | Open |
| [jaw9c/awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers/pull/157) | Add APIbase remote MCP server | Open |
| [Rodert/awesome-mcp](https://github.com/Rodert/awesome-mcp/pull/4) | Add APIbase gateway | Open |
| [caramaschiHG/awesome-ai-agents-2026](https://github.com/caramaschiHG/awesome-ai-agents-2026/pull/31) | Add APIbase to AI agents list | Open |

### Stack

`TypeScript` `Node.js` `PostgreSQL` `Redis` `Docker` `MCP` `x402` `MPP` `USDC` `Base` `Tempo`

### Elsewhere

[X @apibase_pro](https://x.com/apibase_pro) · [LinkedIn](https://www.linkedin.com/in/whiteknight-apibase/) · [dev.to](https://dev.to/whiteknightonhorse) · [apibase.pro](https://apibase.pro)
