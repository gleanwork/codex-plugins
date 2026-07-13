# Glean Developer Docs

Search the public [Glean developer documentation](https://docs.glean.com) — APIs, SDKs,
MCP, authentication, indexing, and integration guides for building *with* Glean.

This is a separate, focused plugin for people building on the Glean platform. For
searching your own company's internal knowledge, use the main **Glean** plugin instead.

## Setup

### 1. Install the plugin

Install from your host's plugin marketplace (Claude Code, Cursor, or Codex).

### 2. Configure the Glean Dev Docs MCP server

This plugin uses the public Glean Developer Docs MCP server. No Glean account
is required. In Codex, add it with:

```bash
codex mcp add glean-dev-docs --url https://developers.glean.com/mcp
```

Then start a new Codex task. For another host, use its MCP setup to add
`https://developers.glean.com/mcp` and restart or refresh that host as needed.

## What's Included

A single skill that auto-triggers when you ask about building with Glean — API
syntax, SDK usage, MCP setup, indexing, authentication, and platform integration.
It searches the public developer documentation and returns cited answers.

## Support

- [Glean Developer Documentation](https://docs.glean.com)
- [GitHub Issues](https://github.com/gleanwork/agent-plugins/issues)

## License

MIT — see [LICENSE](LICENSE) for details.
