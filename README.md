# Awesome MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers, clients, SDKs and tools.

The Model Context Protocol (MCP) is an open protocol published by [Anthropic](https://www.anthropic.com/) in November 2024. It lets LLM apps connect to external data and tools. This list covers the whole ecosystem around the protocol, organized **by use case** so you can find what you need fast.

_Servers are grouped by what they do. Each row shows the real language, repository activity (last push) and stars. **✅ = official / first-party.** Activity legend: 🟢 ≤3 mo · 🟡 ≤1 yr · 🔴 >1 yr · 🗄️ archived · ❔ unknown. Signals auto-refreshed; last update 2026-10-11._

## Contents

- [Servers](#servers)
  - [Dev, Code & Git](#dev-code--git) (21)
  - [Databases & Data](#databases--data) (2)
  - [Cloud, DevOps & Monitoring](#cloud-devops--monitoring) (9)
  - [Web, Search & Browser](#web-search--browser) (14)
  - [Productivity, Docs & Knowledge](#productivity-docs--knowledge) (9)
  - [Communication & Social](#communication--social) (8)
  - [Commerce, Ads & Business](#commerce-ads--business) (13)
  - [AI, Agents & Memory](#ai-agents--memory) (12)
  - [Media & 3D](#media--3d) (14)
  - [Finance & Crypto](#finance--crypto) (8)
  - [Other](#other) (8)
- [Clients](#clients)
- [SDKs](#sdks)
- [Tools](#tools)

## ⭐ Featured

Standout community servers by traction and activity.

| Server | Description | Lang | Activity | ⭐ |
|---|---|---|:--:|--:|
| [SocialRouter](https://github.com/socialrouter/mcp) | Unified API to fetch social media data across LinkedIn, Instagram, X, Reddit, TikTok, YouTube, and more, with automatic provider failover. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 13d | 1 |
| [MarkItDown](https://github.com/microsoft/markitdown/tree/main/packages/markitdown-mcp) ✅ | Lightweight STDIO and SSE MCP server for calling MarkItDown. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟢 7d | 189.5k |
| [Playwright](https://github.com/microsoft/playwright-mcp) ✅ | Provides browser automation capabilities using Playwright. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 3d | 38k |
| [Official Github](https://github.com/github/github-mcp-server) ✅ | Seamless integration with GitHub APIs, enabling advanced automation and interaction capabilities for developers and tools. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🟢 3d | 33.5k |
| [Blender](https://github.com/ahujasid/blender-mcp) | Interact with and control Blender using prompt assisted 3D modeling, scene creation, and manipulation. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟢 5d | 30.5k |
| [AWS](https://github.com/awslabs/mcp) ✅ | A suite of specialized MCP servers that bring AWS best practices directly to your development workflow. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟢 2d | 9.8k |
| [XcodeBuildMCP](https://github.com/cameroncooke/XcodeBuildMCP) | Provides Xcode-related tools for integration with AI assistants and other MCP clients. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 2d | 6.5k |
| [WhatsApp](https://github.com/lharries/whatsapp-mcp) | Search your personal Whatsapp messages, search your contacts and send messages to either individuals or groups. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🔴 1y | 6.5k |
| [Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) | Interact with Obsidian. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟢 5w | 4.5k |

> The canonical reference servers live in [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — listed by category below.

## Servers

### Dev, Code & Git

| Server | Description | Lang | Activity | ⭐ |
|---|---|---|:--:|--:|
| [FileSystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) ✅ | Secure file operations with configurable access controls. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Github](https://github.com/modelcontextprotocol/servers/tree/main/src/github) ✅ | Repository management, file operations, and GitHub API integration. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) ✅ | GitLab API, enabling project management. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) ✅ | Tools to read, search, and manipulate Git repositories. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Official Github](https://github.com/github/github-mcp-server) ✅ | Seamless integration with GitHub APIs, enabling advanced automation and interaction capabilities for developers and tools. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🟢 3d | 33.5k |
| [XcodeBuildMCP](https://github.com/cameroncooke/XcodeBuildMCP) | Provides Xcode-related tools for integration with AI assistants and other MCP clients. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 2d | 6.5k |
| [Filesystem](https://github.com/mark3labs/mcp-filesystem-server) | File operations with configurable access controls. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🟡 10mo | 695 |
| [Muvon/octocode](https://github.com/Muvon/octocode) | Semantic code indexer with GraphRAG knowledge graph and MCP server. Tree-sitter AST parsing, ast-grep structural search, code signatures view. 13+ languages. Local-first, Apache 2.0. | <picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/rust/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" width="18" alt="Rust" title="Rust"></picture> | 🟢 0d | 505 |
| [Node.js](https://github.com/hyperdrive-eng/mcp-nodejs-debugger) | Gives Cursor or Claude Code access to Node.js at runtime to help you debug. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🗄️ archived | 302 |
| [VSCode Devtools (Bifrost)](https://github.com/biegehydra/BifrostMCP) | Connect to VSCode IDE and use semantic tools like `find_usages`. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟡 6mo | 223 |
| [Hoofy](https://github.com/HendryAvila/Hoofy) | Spec-driven development companion with persistent memory (SQLite + FTS5 + knowledge graph), adaptive change pipeline, and greenfield project pipeline with Clarity Gate. 32 MCP tools, single binary, zero dependencies. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🟡 7mo | 15 |
| [preflight](https://github.com/preflight-dev/preflight) | 24-tool MCP server for Claude Code that scores prompts before execution, catches ambiguity, tracks correction patterns, and estimates token cost — reduces wasted tokens from vague prompts. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟡 6mo | 13 |
| [Bestax](https://github.com/allxsmith/bestax/tree/main/bestax-mcp) | Gives coding agents the props, examples, CSS variables and Agent Skills for the Bestax React component library (Bulma v1), served offline from a bundled index. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 0d | 12 |
| [Filesystem](https://github.com/philgei/mcp_server_filesystem) | File operations with configurable access controls. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🔴 1y | 5 |
| [wopee-mcp](https://github.com/Wopee-io/wopee-mcp) | Autonomous AI testing for web apps — generate test cases and user stories, dispatch test, analysis and AI-agent runs, and fetch artifacts and project status via Wopee.io. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 2w | 4 |
| [repomap](https://github.com/SylphxAI/repomap) | Local code graph for agents: hybrid search, symbol context with callers and callees, call paths, and change impact including git diff, plus a graph UI. | <picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/rust/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" width="18" alt="Rust" title="Rust"></picture> | 🟢 2d | 3 |
| [lockdocs](https://github.com/SylphxAI/lockdocs) | Library docs and exact API signatures for the versions pinned in your lockfile (npm, PyPI, crates.io, Go), read locally and offline, with each section cited to package, version, file and line. | <picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/rust/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" width="18" alt="Rust" title="Rust"></picture> | 🟢 2d | 1 |
| [ERIUS PHONE](https://github.com/Protremix/erius-phone-mcp) | Drives an ERIUS PHONE hosted Android phone or tablet: reads the screen as an accessibility tree or screenshot, taps, types, swipes, launches apps, installs APKs and pulls crash logs; requires an ERIUS PHONE API key. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟢 0d | 1 |
| [GhidraLens](https://github.com/hellosverre/ghidralens) | Interactive Ghidra views inside the client: decompile a binary, rename symbols in the live program, and navigate the call graph. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 6w | 0 |
| [sf-intelligence](https://github.com/PranavNagrecha/Salesforce-Intelligence) | Read-only, offline knowledge base of a Salesforce org's metadata that tells your AI what breaks before you change a field, Flow, Apex class or permission, with cited answers. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 0d | 0 |
| [Apple Docs 2.0 MCP](https://github.com/mishafyi/Apple-Docs-2.0-MCP) | Searches and reads Apple's developer documentation, Human Interface Guidelines and 1,700 WWDC sessions with code, with an offline index of 336,629 pages. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 0d | 0 |

### Databases & Data

| Server | Description | Lang | Activity | ⭐ |
|---|---|---|:--:|--:|
| [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) ✅ | Read-only database access with schema inspection. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) ✅ | Database interaction and business intelligence capabilities. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |

### Cloud, DevOps & Monitoring

| Server | Description | Lang | Activity | ⭐ |
|---|---|---|:--:|--:|
| [AWS Knowledge Base Retrieval](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval-server) ✅ | Retrieve information from the AWS Knowledge Base using the Bedrock Agent Runtime. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) ✅ | Retrieving and analyzing issues from Sentry.io. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [AWS](https://github.com/awslabs/mcp) ✅ | A suite of specialized MCP servers that bring AWS best practices directly to your development workflow. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟢 2d | 9.8k |
| [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) ✅ | Deploy, configure & interrogate your resources on the Cloudflare developer platform (e.g. Workers/KV/R2/D1). | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 2d | 4.4k |
| [stackql](https://github.com/stackql/stackql) | SQL for cloud APIs. Query AWS, GCP, Azure and dozens of other providers with SQL. Includes an MCP server for agent access. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🟢 0d | 1.1k |
| [ZenML](https://github.com/zenml-io/mcp-zenml) | Chat with your MLOps and LLMOps pipelines using the official ZenML MCP server. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟢 5d | 49 |
| [Raygun](https://github.com/MindscapeHQ/mcp-server-raygun) | Interact with your crash reporting and real using monitoring data on your Raygun account. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 5w | 22 |
| [Spinnaker](https://github.com/GeiserX/spinnaker-mcp) | Exposes a Spinnaker instance through the Gate API as 37 tools for applications, pipelines, executions, deployment strategies and infrastructure, with an optional read-only toolset. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🟢 1d | 5 |
| [Duplicacy](https://github.com/GeiserX/duplicacy-mcp) | Reads Duplicacy backup metrics from a duplicacy-exporter Prometheus endpoint: backup status, history, snapshots and prune status. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="18" alt="Go" title="Go"> | 🟢 0d | 0 |

### Web, Search & Browser

| Server | Description | Lang | Activity | ⭐ |
|---|---|---|:--:|--:|
| [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) ✅ | Browser automation and web scraping. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) ✅ | Web and local search using Brave's Search API. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) ✅ | Web content fetching and conversion for efficient LLM usage. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="18" alt="JavaScript" title="JavaScript"> | 🟢 0d | 91.1k |
| [Playwright](https://github.com/microsoft/playwright-mcp) ✅ | Provides browser automation capabilities using Playwright. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 3d | 38k |
| [Youtube](https://github.com/anaisbetts/mcp-youtube) | Uses `yt-dlp` to download subtitles from YouTube. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 8w | 548 |
| [Kagi](https://github.com/ac3xx/mcp-servers-kagi) | A Model Context Protocol server implementation for Kagi's API. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🔴 1y | 44 |
| [newsmcp](https://github.com/pranciskus/newsmcp) | Real-time world news for AI agents — events clustered from hundreds of sources, classified by 12 topics and 30+ geographic regions, ranked by importance. Free, no API key required. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟡 7mo | 35 |
| [Exa.ai](https://github.com/theishangoswami/exa-mcp-server) | Use the Exa AI Search API for web searches. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🔴 1y | 6 |
| [Find MCP](https://github.com/agentage/find-mcp) | Discover MCP servers by searching 17,000+ entries synced from the official MCP registry, via remote streamable HTTP or stdio. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 1d | 6 |
| [Arcmira: YouTube Transcript Search](https://github.com/arcmira/mcp) | Searches indexed YouTube transcripts for timestamped quotes, speaker appearances, sponsors, and recommendations. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 3d | 4 |
| [Naver Search MCP](https://github.com/uju777/mcp-server-naver-search) | Naver Shopping, Cafe, News search for Korean users. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="18" alt="Python" title="Python"> | 🟡 9mo | 1 |
| [StackScan](https://github.com/stackscan/stackscan-mcp) | Looks up the technologies on any domain and the company behind it, and reports how many sites run a given technology and where. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 9d | 1 |
| [Statsnet](https://github.com/usenetstate/statsnet-mcp) | Background check any company in the world: registration, executives, courts and finances via remote MCP. | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="18" alt="TypeScript" title="TypeScript"> | 🟢 3w | 0 |
| [looot](https://github.com/loootai/looot-mcp) | Work email an