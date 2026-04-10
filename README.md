# psyXe

A native macOS AI assistant that connects to your Apple Notes, Reminders, Contacts, Weather, and Files — with multi-agent orchestration, scheduled tasks, custom tool creation, and more.

**[Visit psyxe.app](https://pro.psyxe.app/)** for screenshots, demos, and pricing.

## Download

**[Latest Release](https://github.com/bjenkinsgit/psyxe-app/releases/latest)** — Download the DMG, drag to Applications, and launch.

> Requires macOS 14 (Sonoma) or later on Apple Silicon.

## Free Trial

psyXe includes a **14-day free trial** with full access to all features. After the trial, the app continues to work with Apple ecosystem tools (Notes, Reminders, Contacts, Weather, Files). Premium features require a license key.

## Features

### Free Tier (always available)

| Category | What you get |
|----------|-------------|
| **Apple Notes** | Search, browse, create, semantic search (BERT-powered), tag indexing |
| **Apple Reminders** | Full CRUD, batch operations, list management |
| **Apple Contacts** | Search, create, edit, delete |
| **Weather** | Current conditions and forecasts via Apple WeatherKit |
| **Files** | Search, read, write in granted folders |
| **Utilities** | PDF generation, URL fetching, YouTube transcripts |

### Personal Tier (trial / licensed)

Everything in Free, plus:

| Category | What you get |
|----------|-------------|
| **Multi-Agent Swarm** | Parallel task execution with automatic planning and synthesis |
| **Agent Roles** | Specialized agents (Writer, Data Analyst, Web Researcher, etc.) with auto-routing |
| **Workflows** | Sequential multi-agent pipelines with Prolog FSM coordination |
| **Scheduled Tasks** | Cron-based recurring jobs (daily briefings, periodic checks) |
| **Playbooks** | Capture successful conversations as reusable templates |
| **Custom Tools** | Create and install WASM-based tools via natural language |
| **Web Search** | Brave Search integration (web, news, images, video) |
| **Image AI** | Generation, analysis, OCR, object detection via Gemini |
| **Code Interpreter** | Sandboxed Python execution |
| **iMessage/Email** | Other people can interact with your assistant via Messages or Mail |
| **Conversation Memory** | BERT-powered semantic recall of past conversations |

## How It Works

psyXe runs entirely on your Mac. It connects to a local or remote LLM (any OpenAI-compatible API) and uses macOS-native APIs to interact with your Apple apps. No data leaves your machine unless you configure an external LLM endpoint.

### Supported LLM Backends

- Local: Ollama, llama.cpp, vLLM, LM Studio
- Cloud: OpenAI, Anthropic, Azure OpenAI, Google Gemini, or any OpenAI-compatible endpoint

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon (M1/M2/M3/M4)
- An LLM backend (local or remote)

## Getting a License

After your trial expires, you can purchase a license to unlock all features permanently. Visit **[pro.psyxe.app](https://pro.psyxe.app/)** for pricing and to purchase a license key.

## Related Projects

- **[psyXe MCP Server](https://github.com/bjenkinsgit/psyxe-mcp)** — Free, open-source MCP server for Claude Code, Cursor, and other AI assistants. Same Apple ecosystem tools, no GUI required.
- **[memvid-rs](https://github.com/bjenkinsgit/memvid-rs)** — The BERT semantic search engine that powers psyXe's Notes search and conversation memory.

## Privacy

- All Apple ecosystem operations use macOS-native APIs (AppleScript, EventKit, Contacts framework)
- No data is sent to any server unless you configure an external LLM endpoint
- API keys and settings are stored in an encrypted SQLite database protected by Touch ID
- Access control lets you choose exactly which reminder lists, folders, and contacts the assistant can access

## Support

For questions, bug reports, or feature requests, please [open an issue](https://github.com/bjenkinsgit/psyxe-app/issues).
