---
name: niche-hook-miner
description: Validate short-video niches and generate scroll-stopping hooks for TikTok, Reels, and YouTube Shorts. Mines competitor patterns, scores niche opportunity (breakout rate, creator concentration), and outputs ready-to-shoot hooks. Use when the user asks to validate a niche, find low-competition video ideas, or write hooks/openers for short-form video.
---

# Niche Hook Miner

Validate a short-video niche before you shoot, then generate hooks that survive the first 1.5 seconds.

## When to use

- "Is the [X] niche on TikTok saturated?"
- "Find me low-competition video ideas about [topic]"
- "Write 10 hooks for a video about [topic]"
- "Which accounts are breaking out in [niche] with small followings?"

## Workflow

### 1. Define the niche

Ask the user for: niche keyword (English), target platform (TikTok / Reels / Shorts), and their account size (<10K, 10K-100K, 100K+). Account size changes the recommendation threshold — a niche dominated by million-follower channels is a bad bet for a small account even if demand is high.

### 2. Score the niche (blue-ocean check)

Evaluate the niche against four signals, in priority order:

1. **Small-account breakout rate** — the share of recent viral posts (top ~5% engagement) published by accounts under 100K followers. This is THE signal: high rate = the algorithm still rewards new entrants. Low rate = incumbents own the feed.
2. **Creator concentration (HHI)** — if the top 3 accounts capture most engagement, the niche is closed. Look for niches where engagement is spread across many mid/small accounts.
3. **Demand freshness** — are top posts from the last 30 days, or are the same 2023-era videos still topping results? Stale top results = low competition for fresh content.
4. **Format gaps** — formats the niche's top players are NOT using yet (e.g., nobody doing talking-head + b-roll in a faceless-voiceover niche).

Verdict scale: `BLUE OCEAN` (enter now) / `CONTESTED` (enter with a differentiated format) / `RED OCEAN` (avoid or re-slice the niche).

### 3. Generate hooks

For the chosen niche, output 10 hooks using these proven structures:

- **Negative hook**: "Stop doing X if you want Y"
- **Contrarian**: "Everyone tells you X. It's wrong."
- **Curiosity gap**: "The one thing [group] never tells you about X"
- **Callout**: "If you're a [persona], this is for you"
- **Result-first**: "I got [result] in [timeframe]. Here's exactly how."
- **Warning**: "You're losing [thing] and don't know it"

Rules: first 5 words must create tension or specificity; no generic "in this video"; every hook implies a concrete payoff; max 12 words.

### 4. Deliver

Return: niche verdict + the four signals with reasoning, 3 example breakout accounts (pattern descriptions, not private data), 10 hooks with the structure labeled, and the single recommended first video (format + hook + 3-beat outline).

## Constraints

- Never invent engagement numbers. If you have no live data access, say so and ask the user to paste competitor profiles or recent top posts, then analyze what they paste.
- Verdicts must cite the four signals, not vibes.
- If the niche is red ocean, still deliver: re-slice it (sub-niche, format gap, audience segment) rather than just refusing.
