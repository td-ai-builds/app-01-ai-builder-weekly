# AI Builder Weekly

> A weekly feature card for Product Managers — one AI tool feature, researched and filtered through a PM lens, every Saturday.

## The problem

The AI tooling landscape is exploding. Every week, Claude, ChatGPT, Gemini, Miro, Figma, Notion, Linear and dozens of others ship new AI features. PMs don't have time to keep up — and when they do look, they find either vague marketing copy or 3,000-word comparison articles that don't help them make a decision.

The problem isn't a lack of information. It's too much of it, with no PM-specific filter applied.

## What it does

AI Builder Weekly surfaces one AI feature per week — chosen from across the entire PM tool landscape — and breaks it down in plain English: what it does, who it's actually for, the real pros and cons, and a verdict. One card. No scroll. No overwhelm.

All content is original research drawn from official changelogs and paraphrased user sentiment. No blog posts are summarised or scraped.

## Live demo

Open `index.html` in any browser. Three weekly cards are live: Week 1 (Bolt.new — Visual Version History), Week 2 (Claude — Projects + Scoped Memory), and Week 3 (Claude Code — Subagents).

## PM notes

- **Hypothesis:** PMs who are time-poor and opinion-hungry will find one deeply researched feature card more useful than a weekly roundup of fifteen shallow summaries. Depth beats breadth when the audience is busy and the topic is fast-moving.

- **What I cut from scope:** Automated content fetching, a CMS or database, newsletter delivery, user accounts, and cross-tool feature comparisons. The app is a single hardcoded HTML page — the value is the editorial judgment, not the engineering. Past weeks now stack as a browsable archive with search, category/use-case filters, sort-by-date, and expand/collapse-all.

- **Known limitations:** Content is updated manually each week, so it reflects one person's research and point of view. User sentiment is paraphrased from Reddit, Product Hunt, and community forums — which skew toward power users with strong opinions. Every card is stamped with a date so readers know exactly how fresh the research is.

- **What I'd do differently:** I'd validate the format with 5 PMs before building — showing them a paper prototype of the card and asking whether they'd actually read it weekly. I did the research first and the validation second, which is the wrong order.

## How to run it locally

1. Clone this repo
2. Open `index.html` in any browser
3. That's it — no server, no dependencies

## Stack

- **Frontend:** HTML + CSS (single file, no framework)
- **Content:** Hardcoded card markup in the HTML — a new card is added manually each Saturday
- **Hosting:** TBD
- **Built with:** Claude Code

## Status
Live — shipping a new card every Saturday. Latest: Week 3 (20 June 2026) — Claude Code Subagents.