# State of Onboarding 2026 by Adapty: Claude Skill

Ask Claude about onboarding benchmarks instead of reading the report.

This skill gives Claude the full [State of Onboarding 2026](https://adapty.io/state-of-onboarding-2026/) report by [Adapty](https://adapty.io): 12 months of App Store onboarding data, November 2025 to October 2026, across 5 regions (US, Europe, APAC, LATAM, MEA) and 7 categories, plus the onboarding flows of the top 50 US apps in each category.

## What you can ask

- **Benchmark your numbers.** "My Health & Fitness app sells mostly in the US. The onboarding has 18 screens and 61% of opens complete it. How do I compare?"
- **Check your length.** "How many screens do Education apps put in their onboarding?"
- **Audit your onboarding.** Send screenshots of every screen and ask "What would you change?" Claude compares your flow with the top apps in your category, checks it against completion and conversion data, and ranks the next 3 tests.
- **Find your next test.** "Users finish the onboarding but few of them pay. What should we test first?"

Claude answers with medians, the middle 50% of apps and the top 10% for your region, category and onboarding length.

## What's inside

- All five chapters: completion & conversion, onboarding length, onboarding design, from onboarding to paywall, personalization & testing
- Chart data: completion, drop-off by screen, trial starts, paid conversion and revenue per onboarding open, by region × category × flow length, plus 70+ countries
- Trial-to-paid and day-one cancellations, plans bought after the onboarding, ad vs. organic users, quizzes and personalization in top apps, paywall position, A/B test win rates

## Install

### Claude.ai (web, desktop)

1. Download [`state-of-onboarding-2026-by-adapty.zip`](https://github.com/vkharlan-adapt/state-of-onboarding-2026-skill/raw/main/state-of-onboarding-2026-by-adapty.zip).
2. In Claude, go to **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**, and select the ZIP.

Skills need **Code execution and file creation** turned on under **Settings > Capabilities**.

### Claude Code

```bash
git clone https://github.com/vkharlan-adapt/state-of-onboarding-2026-skill.git ~/.claude/skills/state-of-onboarding-2026-by-adapty
```

## Methodology

App Store data from onboarding flows built with Adapty. Benchmarks are calculated app by app, shown only when at least 10 apps qualify. Revenue in USD, before store fees, including renewals. The onboarding design chapter uses ScreensDesign's library of the top 50 US apps by estimated revenue in each category, so it describes patterns, not conversion impact. Full methodology is in the [report](https://adapty.io/state-of-onboarding-2026/).

## About Adapty

[Adapty](https://adapty.io) helps subscription apps grow revenue: build onboarding flows and paywalls without code, A/B test them, and target them by country, user attributes or acquisition source, all without an app release.
