# ConnectMachine plugin for Claude

Your professional network in Claude Code and Cowork. Find people by how you remember them, save contacts from the conversation, and write follow-ups with the context of where you met.

The plugin bundles the hosted [ConnectMachine MCP server](https://github.com/connectmachine/mcp-server) (`https://mcp.connectmachine.ai/mcp`) with skills that show Claude how to use it.

## Install

```bash
claude plugin marketplace add connectmachine/claude-plugin
claude plugin install connectmachine@connectmachine
```

Or inside a session: `/plugin marketplace add connectmachine/claude-plugin`, then `/plugin install connectmachine@connectmachine`.

The first time Claude uses ConnectMachine, you sign in with your ConnectMachine account. Any account works, including free ones.

## What's included

| Component | What it does |
|---|---|
| **ConnectMachine MCP server** | Contacts, networks, events, digital business cards and notifications |
| **`connectmachine` skill** | Loaded automatically when you talk about people you know. Teaches Claude to search by what you remember, check before updating, and attach where you met |
| **`/connectmachine:save-contact`** | Save someone from a description: `/connectmachine:save-contact Sara Khan, fintech founder, met at WebSummit` |
| **`/connectmachine:follow-up`** | Draft follow-ups: `/connectmachine:follow-up people I met at WebSummit` |

## Try asking

- "Which founders do I know in fintech?"
- "I met Sara Khan from Northstar Pay at WebSummit, save her."
- "Draft follow-ups to the people I met last week."
- "Put John William in my Investors network."

## Links

- [Docs](https://www.connectmachine.ai/docs/mcp/)
- [Privacy Policy](https://connectmachine.ai/legal/privacy) · [Terms](https://www.connectmachine.ai/legal/terms-of-service)
- Support: [open an issue](https://github.com/connectmachine/claude-plugin/issues) or email hi@connectmachine.ai

## License

MIT
