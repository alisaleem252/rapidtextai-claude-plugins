# RapidTextAI plugins for Claude

Claude plugins from [RapidTextAI](https://app.rapidtextai.com), the AI content platform for researched articles, content refreshes, auto-blogging and WordPress publishing.

## Plugins

| Plugin | Status | What it does |
|---|---|---|
| [`rapidtextai-seo-audit`](plugins/rapidtextai-seo-audit) | 0.1.0 | Free SEO audit of any public page: scorecard, fact-check, content refresh ideas and originality spot check. No account needed. |
| `rapidtextai-content-studio` | Planned | Keyword to brief to Pro Article in your brand voice, refresh by URL, competitor gap. Uses the RapidTextAI connector. |
| `rapidtextai-blog-autopilot` | Planned | Brand from your URL, a month of topics, and a campaign that publishes to WordPress. |
| `rapidtextai-wordpress-publisher` | Planned | Drafts, featured images, SEO meta and WooCommerce product descriptions through wp-woo-mcp. |

## Install in Claude Code

```
/plugin marketplace add alisaleem252/rapidtextai-claude-plugins
/plugin install rapidtextai-seo-audit@rapidtextai
```

On claude.ai and in Cowork, add the plugins from the directory in **Customize > Plugins**.

## Develop

Each plugin is a folder under `plugins/` with its manifest at `.claude-plugin/plugin.json`. Validate before pushing:

```
claude plugin validate . --strict
claude plugin validate ./plugins/rapidtextai-seo-audit --profile directory --strict
```

Raise `version` in a plugin's `plugin.json` on every release.

## License

MIT
