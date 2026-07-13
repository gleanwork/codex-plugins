# Glean Plugins for Codex

> **Generated repository.** Built from
> [gleanwork/agent-plugins](https://github.com/gleanwork/agent-plugins) via
> [pluginpack](https://github.com/gleanwork/pluginpack). Don't hand-edit managed
> files here — changes are made in `agent-plugins` and synced down automatically.

Official Glean plugins for [Codex](https://developers.openai.com/codex) —
enterprise knowledge, search, people, code, meetings, and Glean developer docs.

## Install

```bash
codex plugin marketplace add gleanwork/codex-plugins
codex plugin add glean@glean-codex-plugins
codex plugin add glean-dev-docs@glean-codex-plugins
```

Start a new Codex task after installation so the bundled skills are available.

Then connect the MCP server used by the plugin you installed:

- **Glean enterprise knowledge:** ask Codex to "set up Glean" and the `glean`
  plugin's `connect-glean` skill will walk you through it.
- **Glean developer docs:** run
  `codex mcp add glean-dev-docs --url https://developers.glean.com/mcp`.

## Plugins

| Plugin | Description |
|--------|-------------|
| **[glean](plugins/glean)** | Enterprise knowledge — search docs/Slack/email, cross-repo code exploration, people & experts, meetings, onboarding, and productivity. |
| **[glean-dev-docs](plugins/glean-dev-docs)** | Search Glean's public developer documentation — APIs, SDKs, MCP, and integration guides. |

## Migrating from the Claude marketplace

Codex can read the legacy Claude marketplace, but the native Codex marketplace
has richer metadata and is the supported install path. If you previously
installed these plugins from `gleanwork/claude-plugins`, remove those plugin
installs before running the commands above:

```bash
codex plugin remove glean@glean-plugins
codex plugin remove glean-dev-docs@glean-plugins
```

## Requirements

- [Codex](https://developers.openai.com/codex) with plugin support
- A Glean account with MCP access (for the `glean` plugin)

## Support

- [Glean MCP Documentation](https://docs.glean.com/mcp)
- [Glean Support](https://help.glean.com)
- [GitHub Issues](https://github.com/gleanwork/codex-plugins/issues)

## License

MIT License — see [LICENSE](LICENSE) for details.
