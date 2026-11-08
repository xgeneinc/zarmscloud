# ZARMS for AI agents

[English](README.md) | 日本語

[ZARMS](https://zarms.cloud) 用の Agent Skills です。Claude Code、Cursor、Codex などのエージェントで使えます。

## インストール

```bash
npx skills add xgeneinc/zarmscloud
```

スキルとエージェントを指定して入れる場合:

```bash
npx skills add xgeneinc/zarmscloud --skill zarms -a claude-code
```

## スキル

| スキル                         | できること                                                                                            |
| ------------------------------ | ----------------------------------------------------------------------------------------------------- |
| [zarms](skills/zarms/SKILL.md) | ZARMS の MCP サーバーまたは REST API で、ボード・カード・ステップ・コメントを調べたり更新したりします |

## 必要なもの

トライアル中、または Starter 以上のプランのチームと、MCP の接続が必要です。手順は[接続ガイド](https://help.zarms.cloud/ja/mcp/overview)にあります。

[![skills.sh](https://skills.sh/b/xgeneinc/zarmscloud)](https://skills.sh/xgeneinc/zarmscloud)

## Issue と Pull Request

Issue は、スキルの問題（指示の誤りやわかりにくさ）と提案のために使います。小さな修正はそのまま Pull Request を出してください。大きな変更は先に Issue で相談してください。ZARMS 自体のことは[ヘルプセンター](https://help.zarms.cloud/ja)へ。詳しくは [CONTRIBUTING.ja.md](CONTRIBUTING.ja.md) をご覧ください。

## ライセンス

[MIT](LICENSE)
