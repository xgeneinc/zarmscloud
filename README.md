# ZARMS for AI agents

English | [日本語](README.ja.md)

Agent Skills for [ZARMS](https://zarms.cloud), usable from Claude Code, Cursor, Codex and other agents.

## Install

```bash
npx skills add xgeneinc/zarmscloud
```

Install one skill for one agent:

```bash
npx skills add xgeneinc/zarmscloud --skill zarms -a claude-code
```

## Skills

| Skill                          | What it does                                                                                  |
| ------------------------------ | --------------------------------------------------------------------------------------------- |
| [zarms](skills/zarms/SKILL.md) | Look up and update boards, cards, steps and comments through the ZARMS MCP server or REST API |

## Requirements

You need a ZARMS team on the trial, Starter or a higher plan, and an MCP connection. See the [setup guide](https://help.zarms.cloud/en/mcp/overview).

[![skills.sh](https://skills.sh/b/xgeneinc/zarmscloud)](https://skills.sh/xgeneinc/zarmscloud)

## Issues and pull requests

Issues are for problems with the skills (wrong or unclear instructions) and suggestions. Small fixes are welcome as pull requests; for larger changes, open an issue first. For help with ZARMS itself, use the [help center](https://help.zarms.cloud/en). Details: [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE)
