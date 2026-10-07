# SuperBot plugin for Claude Code and Cowork

SuperBot helps merchant teams investigate support conversations, understand
support health, find knowledge gaps, and add approved training answers. This
plugin bundles the public SuperBot remote MCP server and a small workflow skill
for safe support operations.

## Install

The plugin is designed for the Claude plugin directory. For local testing from
Claude Code, clone this repository and run from its parent folder:

```text
claude --plugin-dir ./superbot-claude-plugin
```

When the plugin is enabled, Claude will ask you to authenticate the remote
SuperBot server with OAuth. Sign in to the SuperBot workspace you want to use
and approve only the permissions you intend to grant.

## What it includes

- Ten read-only tools for search, transcripts, recent conversations, triage,
  knowledge lookup, support metrics, insights and trends, training gaps,
  knowledge sources, and captured leads.
- One separate additive tool for saving a user-approved trained answer.
- A `support-operations` skill that keeps evidence, tenant scoping, and
  training approval explicit.

The server does not provide refunds, campaigns, billing changes, outbound
customer messages, or cross-workspace access. See the public connector docs at
https://superbotapp.ai/docs/mcp and privacy policy at
https://superbotapp.ai/legal/privacy.

## Source and support

Source: https://github.com/shaggyistaken/superbot-claude-plugin

Support: support@superbotapp.ai
