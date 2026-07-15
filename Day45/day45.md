# Decision Report Generator

**ABTalks 60-Day Claude AI Mastery Challenge**

An interactive, single-file HTML tool that turns a messy personal decision into a structured, data-driven report — built entirely through a guided conversational intake with Claude.

---

## What It Does

You're stuck between two (or three) options. Instead of spiraling in your head, you answer 4 focused questions and Claude generates a complete **Decision Report** — an interactive dashboard you can open in any browser, screenshot, and share.

## How It Works

1. **The Interview** — Claude asks exactly 4 questions, one at a time:
   - What's the decision and why is it hard?
   - What's the goal and timeline?
   - What does your gut say, and what's blocking you?
   - What are you most afraid of getting wrong — and is it reversible?
2. **The Build** — Once all 4 answers are collected, Claude generates a single self-contained `.html` file. No dependencies beyond a Google Fonts import.

## Report Contents

| Section | What's Inside |
|---|---|
| 1. The Real Decision | The core trade-off, stated plainly |
| 2. The Case for Each Option | Strongest case, hidden upside, biggest weakness, "best if you value" |
| 3. Assumption Buster | Hidden assumptions + named cognitive biases (sunk cost, loss aversion, etc.) |
| 4. Decision Matrix | 7-dimension scoring (out of 70) with animated bars |
| 5. Premortem | Top 2 options, imagined 12-month failure + early warning signs |
| 6. 7-Day Test Plan | Research → experiment → conversation → decision day |
| 7. The Verdict | A decisive pick, the reasoning, and what could flip it |
| 8. Shareable Cards | 3 screenshot-ready cards: matrix summary, verdict, LinkedIn caption |

## Design System

Consistent with the ABTalks visual brand:

- **Background:** deep near-black (`#0f0f14`)
- **Accents:** blue, green, purple, red, gold — mapped to section meaning
- **Typography:** Inter, dark-mode optimized
- **Motion:** animated matrix bars, card hover lift, smooth scroll

## Tech Stack

Vanilla HTML/CSS/JS. No frameworks, no build step, no external API calls. Fully offline-capable once loaded.

## Content Rules

- Every score, weakness, and warning is derived only from what the user actually said — nothing invented.
- The Verdict always commits to one option; it doesn't hedge.

---

*Built with Claude AI | ABTalks 60-Day Challenge*
