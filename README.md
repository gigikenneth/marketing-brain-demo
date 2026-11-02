# Fernway marketing brain (sample)

This is a sample marketing repository for **Fernway**, a fictional project planning tool for creative agencies. It exists to demo [MarketingHQ](https://marketinghq-engine.lovable.app), which reads a repo like this and tells you what needs attention.

Everything here is made up. The company, people, numbers and competitors are fictional.

## How it's organised

| Folder | What lives there |
|---|---|
| `brand/` | Positioning, voice, visual identity |
| `strategy/` | Annual plan, SEO, channel mix |
| `research/` | Competitors, ideal customer profile, interviews |
| `campaigns/` | One folder per campaign: brief and results |
| `prompts/` | Reusable prompts for AI writing tools |
| `workflows/` | Step-by-step processes the team and AI agents follow |
| `context/` | Product facts and glossary that agents load as context |
| `CLAUDE.md` | Instructions for AI coding agents working in this repo |

## Metadata

Each document can start with front matter that MarketingHQ reads:

```yaml
---
title: Competitor landscape
type: competitor
owner: Priya
review_every: 30d
last_reviewed: 2026-09-02
---
```

`review_every` says how often the file should be checked. A competitor file goes stale in weeks; positioning can stay right for a year. When it's missing, MarketingHQ uses a default for the document type.

Some files here have deliberate problems (stale research, broken links, missing metadata) so the demo has something to find.
