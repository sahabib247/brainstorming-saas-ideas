# Brainstorming SaaS & App Ideas: a Claude Skill

**A free Claude skill that brainstorms unique SaaS & app ideas, not the usual "AI tool for X".**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Works with Claude](https://img.shields.io/badge/Works%20with-Claude-D97757)
![Platforms](https://img.shields.io/badge/Ideas%20for-SaaS%20%7C%20Web%20%7C%20Android%20%7C%20iOS-blue)

---

## The problem

Ask any AI for SaaS ideas and you'll usually get a habit tracker, an AI resume builder, or a "ChatGPT for lawyers." Five people asking the same question get the same five ideas, and every one of them already has 100 competitors.

This skill makes Claude brainstorm like a sceptical founder instead of a hype machine. It covers **SaaS, web apps, Android, iOS, browser extensions and marketplace plugins**.

## Features

- 🔍 **Researches real pain first.** It mines Reddit, HN, niche forums, 1–3★ reviews on G2/Capterra/Play Store/App Store, and Upwork/Fiverr gigs people keep paying for. Every claim gets a source, and anything it can't check is marked `[assumption]`.
- 🧠 **Has an originality engine.** It rejects common ideas by default (generic AI chatbots, to-do apps, expense trackers, "Uber for X"). Then it uses 12 techniques to make ideas unique: domain collision, inversion, extreme niche, trigger-moment design, insider workflows, constraint forcing, "ugly data" and more.
- 👥 **Runs the five-people test.** If five smart people with the same prompt would land on the idea, it gets pushed further or cut.
- 🔎 **Checks for clones.** It searches for competitors and labels each idea *Blue*, *Wedge*, *Clone* or *Empty*. Unique-but-nobody-needs-it ideas get cut too.
- 🎯 **Generates 25+ ideas privately and shows you only the best 3.** You get a safe bet, a sharp wedge and a bold bet.
- 🚧 **Filters hard.** 11 hard gates (IP issues, regulated industries, cold-start traps, no reachable buyer, and more) plus an 11-criteria scoring rubric. Low pain, willingness to pay, reachability or originality cuts an idea no matter its total.
- 🔴 **Red-teams the shortlist.** Each finalist gets a pre-mortem and a "what if the incumbent copies this next quarter?" check.
- 📱 **Picks the right platform.** It tells you when SaaS, a PWA, Android, iOS or an extension fits best, with fees and store rules to check.
- 📋 **Gives you cards you can act on.** Each idea comes with an ICP, pain evidence, named competitors, pricing, napkin unit economics (including AI cost), a plan for the first 100 users, MVP scope, a 7-day validation test with a success threshold, and kill criteria.
- 🙋 **Fits you.** It asks one question about your skills, budget, hours and goals, then favours ideas built on *your* unfair advantage. It even handles payment options in countries without Stripe.

## Installation

### Option A: Claude Skills (recommended)

1. Download **`brainstorming-saas-ideas.zip`** from the [latest release](../../releases/latest).
2. In Claude, open **Settings → Capabilities → Skills** and upload the zip.
3. Make sure the skill is turned on.

### Option B: Claude Projects

1. Download [`brainstorming-saas-ideas/SKILL.md`](brainstorming-saas-ideas/SKILL.md).
2. Create a Project in Claude and upload the file as project knowledge.

> Tip: the skill works best when Claude has web search turned on, so it can pull live evidence. Without it, the skill still works but labels market claims `[unverified]`.

## Usage

Just ask in plain language:

```
Give me SaaS ideas.
```

```
I'm a solo Flutter developer with $300 and 10 hours a week. Give me Android app ideas for small shops.
```

```
Only B2B ideas, please. I worked 5 years in logistics.
```

```
Here's my idea: an app that reminds people to water plants. Remix it.
```

```
Deep dive into idea #2.
```

## Modes

| Mode | What it does |
|---|---|
| **Fresh batch** (default) | Full research → 25+ ideas → originality engine → gates → scoring → red team → top 3 cards |
| **Quick** | Faster run without deep research; still filters clichés and scores ideas |
| **Remix** | Reviews *your* idea honestly and gives you 2 sharper variants |
| **Direction** | "Only B2B", "only iOS", "more like #2": a new top 3 within your constraint |
| **Deep dive** | Interview questions, landing page copy, a first-100-users outreach plan, MVP spec and a 4-week build plan |

## What you get

For each of the top 3 ideas, Claude writes an idea card with:

> One-liner · Ideal customer · Pain + evidence · Current workaround · Why now · Originality · Closest competitors · Wedge · Core workflow & aha moment · Platform · Pricing · Unit economics · First 100 users · Retention loop · MVP scope · Not in MVP · 7-day validation test · Kill criteria · Risks · Moat · Expansion path · Scores (/55)

## Contributing

Found a bug, got a weird result, or have an idea to make the skill sharper? [Open an issue](../../issues). Pull requests are welcome too.

If you built something from an idea this skill gave you, I'd love to hear about it!

## License

[MIT](LICENSE): free to use, modify and share.

---

If this helped you, please give the repo a ⭐. It helps other builders find it.
