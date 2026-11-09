# RapidTextAI Free SEO Audit

Audit any public web page for SEO in a conversation with Claude. Free, with no account, sign-up or API key.

## What it does

The plugin adds four skills. Claude picks the right one from what you ask, or you can run one by name in Claude Code and Cowork (for example `/rapidtextai-seo-audit:seo-audit`).

| Skill | Ask Claude something like | You get |
|---|---|---|
| `seo-audit` | "Audit the SEO of https://example.com/blog/post" | A score out of 100, the top fixes with rewritten title and meta description, and a full scorecard |
| `fact-check` | "Fact-check the stats in this post" | Each claim marked correct, outdated, inaccurate, unsupported or misattributed, with sources and corrected sentences |
| `content-refresh` | "This post lost traffic. What should I update?" | Stale facts with current figures, missing sections as proposed headings, and a new title |
| `originality-check` | "Is this article copied from anywhere?" | Exact-phrase spot checks against the web and a rating of the content's original value |

Each report ends with a short note on how RapidTextAI can do the fix automatically, with a link to a free account.

## Install

- **Claude (web, desktop, Cowork):** add "RapidTextAI Free SEO Audit" from the plugin directory in **Customize > Plugins**.
- **Claude Code:**

  ```
  /plugin marketplace add alisaleem252/rapidtextai-claude-plugins
  /plugin install rapidtextai-seo-audit@rapidtextai
  ```

## Data

The plugin is instructions only. It runs no code, contains no MCP server and sends nothing to RapidTextAI. Claude fetches the page you name and runs web searches with its own built-in web tools, under your Claude account's settings. Nothing is stored by the plugin. Links to app.rapidtextai.com in reports carry UTM parameters so RapidTextAI can count visits that came from this plugin.

## About RapidTextAI

[RapidTextAI](https://app.rapidtextai.com) writes researched, sourced Pro Articles in your brand voice, refreshes old posts, and runs auto-blogging campaigns that publish to WordPress. Support: alisaleem252@gmail.com.

## License

MIT
