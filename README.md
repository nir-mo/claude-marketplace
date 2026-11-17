# nir-mo's Claude plugin marketplace

Personal [Claude Code plugin marketplace](https://code.claude.com/docs/en/plugins/create-marketplace).

## Use it

```bash
claude plugin marketplace add nir-mo/claude-marketplace
claude plugin install hahishook-shopping@nir-mo-plugins
```

## Skills

| Plugin | What it does |
|---|---|
| [hahishook-shopping](https://github.com/nir-mo/hahishook-shopping) | Weekly grocery cart on hahishook.com — search, conversational list, cart handoff (never automates payment). |

This marketplace is also the skill manifest for my self-hosted NanoClaw WhatsApp
bot: its `ops/install-marketplace-skills.sh` reads `marketplace.json` and installs
every listed skill into the bot's agent containers. One index, two consumers.
