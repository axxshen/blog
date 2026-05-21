---
title: "I Built a Prediction Market Bot. It Failed."
description: "A post-mortem on building a Polymarket bot, losing the EV test, and what I learned about systems, bets, and stopping."
publishDate: "21 May 2026"
tags: ["crypto", "engineering", "reflection"]
draft: false
---

For the past few months, I built and ran a bot on Polymarket — a prediction market platform where you bet on real-world outcomes using crypto.

The thesis was simple: find mispriced probabilities, exploit the edge, scale. The execution was not simple at all.

## What I Built

The bot targeted weather and temperature markets — niche enough that I thought I could find inefficiencies. I built it in Python, connected it to the Polymarket API, deployed it on a server, and watched it run.

Two bots. Real money. Real skin in the game.

## What Happened

I set a clear test: Bot 1 reaches $350, Bot 2 stays above $300 by a set deadline. Both failed.

The failure wasn't dramatic. No catastrophic bug, no massive loss. Just a quiet underperformance that told me the edge wasn't there — or I hadn't found it yet.

I shut it down.

## What I Actually Learned

**Stopping is a skill.** Most people who build things have trouble killing them. I set the success criteria before I started, and when the criteria weren't met, I stopped. That discipline is worth more than any individual trade.

**Systems thinking applies to trading too.** You don't just need an edge — you need to understand *why* the edge exists, whether it's durable, and whether you can size it correctly. I understood the mechanics but not the edge deeply enough.

**Building is the curriculum.** I learned more about APIs, server deployment, async programming, and market microstructure in two months of building this bot than I would have in a year of reading about it.

---

This is the first post on this blog. I write about what I'm building, what I'm learning, and what I'm thinking about.
