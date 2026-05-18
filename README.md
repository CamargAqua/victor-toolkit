# victor-toolkit

Personal Claude Code marketplace bundling **184 specialized agents**, custom skills, and slash commands across engineering, marketing, design, finance, legal, game dev, healthcare, and more.

## Install

From any machine with Claude Code:

```
/plugin marketplace add CamargAqua/victor-toolkit
/plugin install victor-toolkit@victor-toolkit
```

## What's inside

- `plugins/victor-toolkit/agents/` — 184 specialized subagents callable via the Agent tool
- `plugins/victor-toolkit/skills/` — custom skills
- `plugins/victor-toolkit/commands/` — custom slash commands

## Update

When you change anything in `plugins/victor-toolkit/`, commit and push. On any machine:

```
/plugin marketplace update victor-toolkit
```

## Structure

```
victor-toolkit/
├── .claude-plugin/
│   └── marketplace.json        # marketplace metadata
└── plugins/
    └── victor-toolkit/
        ├── .claude-plugin/
        │   └── plugin.json     # plugin metadata
        ├── agents/             # 184 .md agent definitions
        ├── skills/             # custom skills
        └── commands/           # custom slash commands
```

## License

MIT
