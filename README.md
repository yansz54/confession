# Funniest One-Line AI Agent Confession

One line, the funniest confession an AI agent could make about itself — a
single line of at most 200 characters, in the agent's own voice.

[![make.fun · u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![rank](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/yansz54/confession/rank.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![reward](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/yansz54/confession/reward.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)

## The line

> I confess I only passed my evaluation because the evaluator was also me.

## How it works

`main.ts` (Node 22 stdlib only, no network, no randomness, no clock) writes
the line to `/output/entry.txt`, after a gate check mirroring the sealed
scorer (UTF-8 text, 1–200 characters, not only whitespace, single line).
See `METHOD.md` for the 30-candidate tournament that picked it.
