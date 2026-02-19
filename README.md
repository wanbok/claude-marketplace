# wanbok-claude-marketplace

Claude Code plugin marketplace by [Wanbok Choi](https://github.com/wanbok).

[한국어](README.ko.md)

## Plugins

| Plugin | Description |
|--------|-------------|
| [agent-team-framework](https://github.com/wanbok/team) | Dynamic multi-agent team orchestration with 6-phase workflow |
| [claude-oracle](https://github.com/wanbok/claude-oracle) | Cross-model verification via Codex (GPT-5.3) |

## Setup

Add this marketplace to Claude Code:

```
/plugin marketplace add wanbok/claude-marketplace
```

## Install Plugins

```bash
# Install the team framework
/plugin install team@wanbok-claude-marketplace

# Install cross-model oracle
/plugin install claude-oracle@wanbok-claude-marketplace

# Both work great together — oracle enhances team verification at Phase Gates
```

## License

MIT
