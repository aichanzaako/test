# 秘密情報の保管場所一覧（値は絶対に書かない）

| 秘密情報 | 保管場所 | 用途 |
|----------|----------|------|
| ANTHROPIC_API_KEY | ~/.openclaw/credentials/ | OpenClaw → Claude Code |
| GITHUB_TOKEN (GAS用) | GAS Script Properties | GAS → GitHub Issue作成 |
| GITHUB_TOKEN (OpenClaw用) | ~/.openclaw/credentials/ | OpenClaw → GitHub API |
| LINE_CHANNEL_ACCESS_TOKEN | GAS Script Properties | LINE通知送信 |
| LINE_CHANNEL_SECRET | GAS Script Properties | LINE Webhook検証 |
| VERCEL_TOKEN | GitHub Secrets | GitHub Actions → Vercel rollback |
| X_API_KEY / SECRET | ~/.openclaw/credentials/ | X投稿 |
