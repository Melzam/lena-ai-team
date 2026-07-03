# Lena AI Team

Personal AI team for Elena: market intelligence, content strategy, content drafts, design briefs, and future publishing workflows.

## First goal

Build **Scout v0.1**: an AI market scout that reads Elena's source list from Google Sheets, checks Telegram sources first, analyzes what matters for Elena's business, and sends a concise report to Telegram.

## Principles

- Built for Elena first.
- No secrets in GitHub.
- Agents are described as employees with clear roles.
- Start small, then expand.
- The system should help Elena decide what to do next, not just collect links.

## Planned agents

- `scout` — monitors market, competitors, trends, client opportunities.
- `strategist` — turns scout findings into content and offer decisions.
- `writer` — writes posts, scripts, emails in Elena's style.
- `designer` — prepares carousel, infographic, and visual prompts.
- `analyst` — studies what performs well and what does not.

## MVP scope

1. Read sources from Google Sheets.
2. Process Telegram sources.
3. Analyze recent posts with OpenAI.
4. Send a short report to Elena in Telegram.

## Security

Secrets must be stored only in `.env` or deployment environment variables. Never commit tokens, passwords, API keys, or Telegram session files.