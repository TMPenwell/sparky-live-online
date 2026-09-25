# Sparky ⚡ Excel for the Trades

Sparky is an AI tutor that teaches electricians to use Excel for real job tasks: bid sheets, circuit sizing, load calculations, and voltage drop.

It doesn't hand over answers. It asks questions, has you work the logic by hand first, then shows you how Excel does it for you.

**Try it:** https://tmpenwell.github.io/sparky-live-online/

---

## Who it's for

Apprentices, journeymen, and master electricians who know the trade but haven't spent much time in spreadsheets. Pick your level when you start and Sparky adjusts how it teaches.

## How it works

1. Download the sample bid sheet (or use your own workbook).
2. Open it in Excel.
3. Ask Sparky about any cell you're stuck on.

Sparky reads the sheet you have open and builds the lesson from it. There's no separate setup for each exercise.

## The teaching approach

Sparky is built on **Kolb's Experiential Learning Cycle**. Instead of giving the answer, it moves you through four stages:

| Stage | What Sparky does |
|---|---|
| **Reflect** | Asks what you're looking at and what you're trying to figure out |
| **Concept** | Works out the logic by hand, the math before the software |
| **Apply** | Walks you through doing it in Excel |
| **Challenge** | Gives you a new problem to try on your own |

If you get stuck, Sparky goes back to Reflect. It explains ideas in terms you already know. Voltage drop is an extension cord that's too thin for the tool you're running.

## ⚠️ Help catch mistakes

Sparky was built by an Excel professor whose son is an electrician. I know spreadsheets better than I know the trade.

AI can be confidently wrong. Sparky has already stated at least one electrical formula incorrectly, and I didn't catch it. **You're more likely to spot these errors than I am.**

If Sparky tells you something that's wrong about electrical work, formulas, or code:

👉 **[Report wrong electrical info](../../issues/new?template=wrong-trade-info.yml)**

You'll need a free GitHub account. Screenshots help.

Excel problems, bugs, and ideas are welcome too. [Open an issue](../../issues/new).

## Important

Sparky is a learning tool for Excel skills. It is **not** a substitute for the NEC, your local code, your AHJ, or a licensed electrician's judgment. Always verify calculations before using them on a job.

## Built with

- HTML/JavaScript web app and Excel add-in (task pane)
- AI model: <!-- TODO: confirm, Gemma 4 (local) or Gemini 2.0 Flash -->

## About

Created by Tasha Penwell, Assistant Professor of Instruction, Analytics & Information Systems, Ohio University.

Interested in using Sparky with apprentices or partnering on it? [Open an issue](../../issues/new) or get in touch.
