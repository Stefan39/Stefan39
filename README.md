# Hi, I'm Stefan Jacomeit

**English** | [Deutsch](README.de.md)

AI automation consultant and builder from Bremerhaven, Germany. I help small and mid-sized businesses automate everyday processes with AI, from the first idea to a working integration. Behind it are 25+ years of PHP and Symfony engineering, so the solutions are built to last.

The projects below come out of that work. Most of them started in my own systems, the GuardedChatBundle for example protects the chat on [www.jacomeit.de](https://www.jacomeit.de). All of them are open source (MIT, Cockpit under Apache-2.0), tested and checked with static analysis.

## MCP servers: connect Claude to business software

| Project | What it does |
| --- | --- |
| [mite-mcp-server](https://github.com/Stefan39/mite-mcp-server) | MCP server for the mite time-tracking API: reports computed on the server, time entries and master data. Read-only by default; write tools appear only when you switch them on, narrowed by an allowlist. On [npm](https://www.npmjs.com/package/mite-mcp-server), listed in MCP directories, one-click install as a Claude Desktop extension (`.mcpb`). |
| [lexware-php-mcp](https://github.com/Stefan39/lexware-php-mcp) | Read-only MCP server for Lexware Office, written in PHP on the official MCP SDK. Search vouchers and contacts, open a voucher with net amounts, net revenue per period. Runs as a standalone download, PHAR or Claude Desktop extension, no PHP setup required. |

## Operating AI agents

| Project | What it does |
| --- | --- |
| [cockpit](https://github.com/Stefan39/cockpit) | Operations cockpit for an AI automation box, running next to n8n and PostgreSQL: see what your agents are doing, approve their drafts with one click, track AI usage and cost. Agents report over a documented API; Cockpit never sends, updates or deletes anything by itself. Passkeys, roles, strict CSP. |

## Symfony bundles and PHP libraries

| Project | What it does |
| --- | --- |
| [GuardedChatBundle](https://github.com/Stefan39/GuardedChatBundle) | Guardrails for public AI chats in Symfony apps, built on Symfony AI: injection prefilter, budget and rate limits, kill switch, prompt versioning, signed sessions, retention. Installs with a [Flex recipe](https://github.com/symfony/recipes-contrib/tree/main/stejac/guarded-chat-bundle). |
| [MiteBundle](https://github.com/Stefan39/MiteBundle) | Symfony bundle for the mite time-tracking API: typed services and DTOs for every resource. |
| [zeitangaben](https://github.com/Stefan39/zeitangaben) | Resolves colloquial German time expressions such as "in den Herbstferien" or "über Ostern" to a concrete period, or returns a clarifying question when it cannot decide. Knows school holidays by state. |
| [code-thresholds](https://github.com/Stefan39/code-thresholds) | Dependency-free size and complexity gate for PHP that checks only the files you changed: method count, parameters, returns, function length, nesting depth. Built to replace SonarCloud in a CI pipeline. |

Composer packages are published under [`stejac/*`](https://packagist.org/packages/stejac/) on Packagist.

## More

- What the tools do in practice, with setup guides (German and English): [www.jacomeit.de/werkzeuge](https://www.jacomeit.de/werkzeuge)
- Starting a new public PHP repository: [php-repo-template](https://github.com/Stefan39/php-repo-template) (README en/de, CI, community files)

Issues and pull requests are welcome.
