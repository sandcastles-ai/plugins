# Sandcastles plugins

Plugins that connect AI assistants to [Sandcastles](https://sandcastles.ai), your content strategist for Instagram, TikTok, and YouTube Shorts. Each plugin connects to the Sandcastles MCP server and adds skills for researching formats, hooks, topics, channels, and top-performing videos. A Sandcastles account is required.

| Folder | Contents |
| --- | --- |
| `claude/` | Claude plugin, also listed in Anthropic's directory |
| `chatgpt/` | ChatGPT plugin package, ready to upload to the ChatGPT plugin directory |
| `cursor/` | Cursor plugin, also available in Grok Bot through the Cursor Marketplace |
| `grok-build/` | Grok Build plugin |

## Install in Claude Code

```
/plugin marketplace add sandcastles-ai/plugins
/plugin install sandcastles@sandcastles
```

## Install in Grok Build

```
grok plugin marketplace add sandcastles-ai/plugins
grok plugin install sandcastles --trust
```

## Install in Cursor

Open **Customize** in the Cursor sidebar, search for Sandcastles, and select **Install**.

## Generated files

Everything in `claude/`, `chatgpt/`, `cursor/`, and `grok-build/` is generated from the Sandcastles API repository by `make build-plugin`. Don't edit these files by hand; changes are overwritten by the next build.

## Support

- Support: https://sandcastles.ai/contact
- Privacy policy: https://sandcastles.ai/legal/privacy-policy
- Terms of service: https://sandcastles.ai/legal/terms-of-service
