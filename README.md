# Awesome Claude Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best AI **agent skills**, **MCP servers**, **plugins** and **subagents** for Claude Code, Cursor and other AI coding agents — ranked by real install counts and GitHub stars.

Every entry links to its live listing on **[aaaa.fyi](https://aaaa.fyi)**, the directory this list is drawn from, where you can search 40,000+ tools, compare install stats, and copy a one-line install command.

**Browse the full live directory → [aaaa.fyi](https://aaaa.fyi)**
· [Skills](https://aaaa.fyi/skills) · [MCP Servers](https://aaaa.fyi/mcp) · [Plugins](https://aaaa.fyi/plugins) · [Subagents](https://aaaa.fyi/subagents)

_Stats are live from GitHub, npm and PyPI and refreshed regularly. Ordering reflects actual usage, not editorial preference._

## Contents

- [🧠 Skills](#-skills)
- [🔌 MCP Servers](#-mcp-servers)
- [🧩 Plugins](#-plugins)
- [🤖 Subagents](#-subagents)
- [Contributing](#contributing)

## What is what?

- **Skill** — a reusable `SKILL.md` instruction set that teaches an agent one task. [What is a skill?](https://aaaa.fyi/glossary/claude-skills)
- **MCP server** — exposes tools, APIs and data to an agent over the Model Context Protocol. [What is MCP?](https://aaaa.fyi/glossary/mcp-server)
- **Plugin** — a bundle of skills, subagents, hooks and MCP servers installed as one package.
- **Subagent** — a specialized single-file assistant you delegate focused tasks to.

---

### 🧠 Skills

- **[find-skills](https://aaaa.fyi/skills/vercel-labs/skills/find-skills)** (`2.6M installs, 27k⭐`) — Helps users discover and install agent skills when they ask questions like "how do I do X", "find a — [source](https://github.com/vercel-labs/skills)
- **[grill-me](https://aaaa.fyi/skills/mattpocock/skills/grill-me)** (`633k installs, 182k⭐`) — A relentless interview to sharpen a plan or design. — [source](https://github.com/mattpocock/skills)
- **[vercel-react-best-practices](https://aaaa.fyi/skills/vercel-labs/agent-skills/vercel-react-best-practices)** (`573k installs, 29k⭐`) — Vercel's official collection of agent skills — [source](https://github.com/vercel-labs/agent-skills)
- **[agent-browser](https://aaaa.fyi/skills/vercel-labs/agent-browser/agent-browser)** (`571k installs, 39k⭐`) — Browser automation CLI for AI agents. Use when the user needs to interact with websites, including n — [source](https://github.com/vercel-labs/agent-browser)
- **[microsoft-foundry](https://aaaa.fyi/skills/microsoft/azure-skills/microsoft-foundry)** (`476k installs, 1k⭐`) — Deploy, evaluate, fine-tune, and manage Foundry agents end-to-end with azd: hosted agent scaffold/ru — [source](https://github.com/microsoft/azure-skills)
- **[lark-doc](https://aaaa.fyi/skills/larksuite/cli/lark-doc)** (`384k installs, 16k⭐`) — 飞书云文档（Docx / Wiki 文档）：读取和编辑飞书文档内容。当用户给出文档 URL 或 token，或需要查看、创建、编辑文档、插入或下载文档图片附件时使用。文档中嵌入的电子表格、多维表格、画 — [source](https://github.com/larksuite/cli)
- **[caveman](https://aaaa.fyi/skills/juliusbrussee/caveman/caveman)** (`374k installs, 92k⭐`) — Ultra-compressed communication mode. Cuts output tokens 65% (measured) by speaking like caveman whil — [source](https://github.com/JuliusBrussee/caveman)
- **[supabase-postgres-best-practices](https://aaaa.fyi/skills/supabase/agent-skills/supabase-postgres-best-practices)** (`302k installs, 2k⭐`) — Postgres performance optimization and best practices from Supabase. Use this skill when writing, rev — [source](https://github.com/supabase/agent-skills)
- **[ai-video-generation](https://aaaa.fyi/skills/101-skills/skills/ai-video-generation)** (`292k installs, 642⭐`) — inference.sh Agent skills for using our API to give your agents access to hundreds of apps and other — [source](https://github.com/inference-sh/skills)
- **[brainstorming](https://aaaa.fyi/skills/obra/superpowers/brainstorming)** (`291k installs, 259k⭐`) — You MUST use this before any creative work - creating features, building components, adding function — [source](https://github.com/obra/superpowers)
- **[design-taste-frontend](https://aaaa.fyi/skills/leonxlnx/taste-skill/design-taste-frontend)** (`280k installs, 66k⭐`) — Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop — [source](https://github.com/Leonxlnx/taste-skill)
- **[ui-ux-pro-max](https://aaaa.fyi/skills/nextlevelbuilder/ui-ux-pro-max-skill/ui-ux-pro-max)** (`280k installs, 109k⭐`) — UI/UX design intelligence for web and mobile. Searchable local database with 84 styles, 192 color pa — [source](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)

### 🔌 MCP Servers

- **[fastmcp](https://aaaa.fyi/mcp/prefecthq/fastmcp)** (`85.6M installs, 27k⭐`) — 🚀 The fast, Pythonic way to build MCP servers and clients. — [source](https://github.com/PrefectHQ/fastmcp)
- **[playwright-mcp](https://aaaa.fyi/mcp/microsoft/playwright-mcp)** (`25.5M installs, 35k⭐`) — Playwright MCP server — [source](https://github.com/microsoft/playwright-mcp)
- **[playwright-mcp](https://aaaa.fyi/mcp/cloudflare/playwright-mcp)** (`25.5M installs, 250⭐`) — Playwright MCP fork that works with Cloudflare Browser Rendering — [source](https://github.com/cloudflare/playwright-mcp)
- **[fastapi_mcp](https://aaaa.fyi/mcp/tadata-org/fastapi_mcp)** (`18.9M installs, 12k⭐`) — Expose your FastAPI endpoints as Model Context Protocol (MCP) tools, with Auth! — [source](https://github.com/tadata-org/fastapi_mcp)
- **[chrome-devtools-mcp](https://aaaa.fyi/mcp/chromedevtools/chrome-devtools-mcp)** (`11.0M installs, 47k⭐`) — Chrome DevTools for coding agents — [source](https://github.com/ChromeDevTools/chrome-devtools-mcp)
- **[ext-apps](https://aaaa.fyi/mcp/modelcontextprotocol/ext-apps)** (`8.5M installs, 3k⭐`) — Official repo for spec & SDK of MCP Apps protocol - standard for UIs embedded AI chatbots, served by — [source](https://github.com/modelcontextprotocol/ext-apps)
- **[langchain-mcp-adapters](https://aaaa.fyi/mcp/langchain-ai/langchain-mcp-adapters)** (`7.0M installs, 4k⭐`) — LangChain 🔌 MCP — [source](https://github.com/langchain-ai/langchain-mcp-adapters)
- **[ddgs](https://aaaa.fyi/mcp/deedy5/ddgs)** (`6.5M installs, 3k⭐`) — A metasearch library that aggregates results from diverse web search services — [source](https://github.com/deedy5/ddgs)
- **[Context7](https://aaaa.fyi/mcp/context7-mcp)** (`3.8M installs, 60k⭐`) — Up-to-date library docs injected straight into your prompts — [source](https://github.com/upstash/context7)
- **[mcporter](https://aaaa.fyi/mcp/openclaw/mcporter)** (`2.5M installs, 5k⭐`) — Call MCPs via TypeScript, masquerading as simple TypeScript API. Or package them as cli. — [source](https://github.com/openclaw/mcporter)
- **[redis-vl-python](https://aaaa.fyi/mcp/redis/redis-vl-python)** (`2.5M installs, 416⭐`) — Redis Vector Library (RedisVL) -- the AI-native Python client for Redis. — [source](https://github.com/redis/redis-vl-python)
- **[mcp-databricks-server](https://aaaa.fyi/mcp/rafaelcartenet/mcp-databricks-server)** (`2.4M installs, 40⭐`) — Model Context Protocol (MCP) server for Databricks that empowers AI agents to autonomously interact — [source](https://github.com/RafaelCartenet/mcp-databricks-server)

### 🧩 Plugins

- **[superpowers](https://aaaa.fyi/plugins/obra/superpowers)** (`259k⭐`) — An agentic skills framework & software development methodology that works. — [source](https://github.com/obra/superpowers)
- **[ECC](https://aaaa.fyi/plugins/affaan-m/ecc)** (`232k⭐`) — The agent harness performance optimization system. Skills, instincts, memory, security, and research — [source](https://github.com/affaan-m/ECC)
- **[andrej-karpathy-skills](https://aaaa.fyi/plugins/multica-ai/andrej-karpathy-skills)** (`195k⭐`) — A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations — [source](https://github.com/multica-ai/andrej-karpathy-skills)
- **[skills](https://aaaa.fyi/plugins/mattpocock/skills)** (`181k⭐`) — Skills for Real Engineers. Straight from my .agents directory. — [source](https://github.com/mattpocock/skills)
- **[skills](https://aaaa.fyi/plugins/anthropics/skills)** (`163k⭐`) — Public repository for Agent Skills — [source](https://github.com/anthropics/skills)
- **[next.js](https://aaaa.fyi/plugins/vercel/next.js)** (`141k⭐`) — The React Framework — [source](https://github.com/vercel/next.js)
- **[claude-code](https://aaaa.fyi/plugins/anthropics/claude-code)** (`139k⭐`) — Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and he — [source](https://github.com/anthropics/claude-code)
- **[ui-ux-pro-max-skill](https://aaaa.fyi/plugins/nextlevelbuilder/ui-ux-pro-max-skill)** (`109k⭐`) — An AI SKILL that provide design intelligence for building professional UI/UX multiple platforms — [source](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)

### 🤖 Subagents

- **[a11y-architect](https://aaaa.fyi/subagents/affaan-m/ecc/a11y-architect)** (`232k⭐`) — Accessibility Architect specializing in WCAG 2.2 compliance for Web and Native platforms. Use PROACT — [source](https://github.com/affaan-m/ECC)
- **[design-review](https://aaaa.fyi/subagents/nextlevelbuilder/ui-ux-pro-max-skill/design-review)** (`109k⭐`) — Expert design reviewer for web UI. Use PROACTIVELY after any front-end change and before calling UI — [source](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
- **[cavecrew-builder](https://aaaa.fyi/subagents/juliusbrussee/caveman/cavecrew-builder)** (`92k⭐`) — Surgical 1-2 file edit. Typo fixes, single-function rewrites, mechanical renames, comment removal, f — [source](https://github.com/JuliusBrussee/caveman)
- **[code-reviewer](https://aaaa.fyi/subagents/addyosmani/agent-skills/code-reviewer)** (`80k⭐`) — Senior code reviewer that evaluates changes across five dimensions — correctness, readability, archi — [source](https://github.com/addyosmani/agent-skills)
- **[impeccable-asset-producer](https://aaaa.fyi/subagents/pbakaus/impeccable/impeccable-asset-producer)** (`49k⭐`) — Produces clean reusable raster assets from approved Impeccable mock references without redesigning t — [source](https://github.com/pbakaus/impeccable)
- **[CLAUDE](https://aaaa.fyi/subagents/alirezarezvani/claude-skills/claude)** (`23k⭐`) — This guide provides comprehensive instructions for creating **cs-* prefixed agents** that seamlessly — [source](https://github.com/alirezarezvani/claude-skills)
- **[seo-backlinks](https://aaaa.fyi/subagents/agricidaniel/claude-seo/seo-backlinks)** (`12k⭐`) — Backlink profile analyst using free and paid sources. Fetches data from Moz API, Bing Webmaster Tool — [source](https://github.com/AgriciDaniel/claude-seo)
- **[verifier](https://aaaa.fyi/subagents/agricidaniel/claude-obsidian/verifier)** (`10k⭐`) — Pre-commit audit specialist. Dispatched by a workstream owner AFTER staging changes but BEFORE commi — [source](https://github.com/AgriciDaniel/claude-obsidian)

---

## Contributing

Found a skill or MCP server that belongs here? Two ways:

1. **Submit it to the directory** — [open a listing suggestion](https://aaaa.fyi/feedback) on aaaa.fyi and it flows into the rankings automatically.
2. **Open a PR** on this list with your entry in the right section.

Please only add tools that are open-source, actively maintained, and genuinely useful.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related rights to this work.
