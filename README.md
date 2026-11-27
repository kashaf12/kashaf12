# Kashaf Ahmed

Senior software engineer (SDE 3 at goHighLevel). I ship mobile apps and developer tools for AI agents, plus the TypeScript and Node.js backends behind them.

Lately that means making agents do real work safely: watching video files, and staying inside a budget and a set of permissions.

## Selected work

**[Vamio](https://vamio.app)** · React Native, Expo, TypeScript, Firebase · iOS and Android\
Group drives in sync: one person creates a trip, shares an invite code, and everyone's location shows on one live map. Live on the [App Store](https://apps.apple.com/app/vamio/id6760580479) and [Google Play](https://play.google.com/store/apps/details?id=app.vamio), with 900+ users signed up.

**[vwatch](https://github.com/kashaf12/vwatch)** · Python · MCP server and Claude Code plugin\
Lets a coding agent watch local videos: timestamped frame grids, dense seeks, crops, a transcript and model-free glitch signals. On a pre-registered benchmark of 48 unseen videos it matched plain Claude Code on accuracy at 36% lower cost and 29% less time. On PyPI and the official MCP Registry, and works with Claude Code, Codex, Gemini CLI and Cursor.

**[Mandate](https://github.com/kashaf12/mandate)** · TypeScript SDK\
Runtime enforcement for AI agent authority. Budgets, tool allowlists, rate limits, a kill switch and an audit trail are enforced in code, not in the prompt, and fail closed. Budget checks stay atomic across servers through Redis Lua scripts.

**[Logical Diff](https://github.com/kashaf12/logical-diff)** · TypeScript · Chrome extension\
Shows only the logic changes in a GitHub pull request. It compares ASTs to hide import reorders, consistent renames and whitespace, so reviewers read what actually changed.

**[Bulk Action Platform](https://github.com/kashaf12/bulk-action-platform)** · Node.js, PostgreSQL, Redis, BullMQ, MinIO\
Runs bulk operations on large CSV uploads asynchronously: chunking and processing workers, validation and deduplication, progress tracking and per-account rate limiting.

Also: a [URL shortener](https://github.com/kashaf12/url-shortener) monorepo (NestJS, Next.js, Supabase) with a [live demo](https://url-shortener-frontend-plum.vercel.app/).

## Stack

TypeScript, Node.js, NestJS, React, Next.js, React Native (Expo), Python, Firebase, PostgreSQL, Redis, Docker.

## Contact

[LinkedIn](https://www.linkedin.com/in/kashaf-ahmed/)
