# VitalStack — Claude Plugin

> Health intelligence for your AI assistant

**VitalStack** is a Claude plugin (MCP server) that lets you:
- Check supplement interactions (1,100+ verified pairs from NIH, EFSA & PubMed)
- Build a personalized daily supplement stack
- Understand the science behind your supplements

## Plugin Manifests

This repository contains **only** the Claude plugin manifest files:

| File | Purpose |
|------|---------|
| `.claude-plugin/plugin.json` | Plugin metadata for Claude Code & Cowork |
| `.claude-plugin/marketplace.json` | Marketplace listing |
| `.claude-plugin/.mcp.json` | MCP server connection config |

## Install

Install via [Claude Code](https://claude.ai/code) or [Claude Cowork](https://claude.ai):

```bash
claude plugin install https://github.com/TilovD/vital-stack-plugin
```

## Links

- **API / Source**: Private (proprietary)
- **Homepage**: https://supplement-mvp-api.vercel.app/landing
- **Author**: [Tilo Jahnke](https://github.com/TilovD)

## License

MIT
