# Contributing

English | [日本語](CONTRIBUTING.ja.md)

Thanks for helping improve the ZARMS agent skills. This repository holds only the skills (instructions for AI agents). The ZARMS product itself is not developed here.

## Where to go

| You want to...                                                         | Go to                                                                                                                |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Report a wrong or confusing instruction in a skill, or suggest a skill | [Open an issue](../../issues/new/choose)                                                                             |
| Fix a typo, an outdated tool name, or an unclear sentence               | [Open a pull request](../../pulls)                                                                                   |
| Get help with ZARMS itself (accounts, billing, bugs in the app)        | [Help center](https://help.zarms.cloud/en) or support@zarms.cloud. Issues here are not monitored for product support |
| Report a security problem                                              | Email contact@zarms.cloud. Please do not open a public issue                                                         |

## Issues

- Search existing issues first.
- Say which agent you use (Claude Code, Cursor, Codex, ...), what you asked it to do, what it did, and what you expected.
- Do not paste API keys, tokens, or private card content. Remove anything confidential from logs.
- One problem per issue.

## Pull requests

- Small fixes (typos, wording, tool names that no longer match the ZARMS MCP server): open a pull request directly.
- Larger changes (a new skill, a new section, a changed workflow or safety rule): open an issue first so we can agree on the direction.
- Keep each pull request to one topic. Describe what changed and why.
- Use ZARMS's own words: "card", "step" (not "checklist"), "team" (not "tenant"). Do not name AI models.
- Skills must stay safe by default: confirm before irreversible actions, never ask users to paste secrets into chat.
- Skill folders follow the [Agent Skills format](https://skills.sh/docs): `skills/<name>/SKILL.md` with `name` and `description`.

Maintainers review on a best-effort basis, with no guaranteed response time. We may close issues or pull requests that are out of scope, inactive for 30 days, or need product changes that this repository cannot make.

## License

By contributing, you agree that your contribution is licensed under the [MIT License](LICENSE).
