<div align="center">

# 🧠 AI Hallucination Prompts

### A professionally curated repository of prompt-response examples that documents AI hallucinations, self-corrections, reasoning failures, and verified outcomes for analysis and evaluation.

![Entries](https://img.shields.io/badge/entries-38-blueviolet)
![Categories](https://img.shields.io/badge/categories-5-informational)
![Format](https://img.shields.io/badge/format-markdown-lightgrey)
![Status](https://img.shields.io/badge/status-active-brightgreen)

</div>

---

## 📖 What This Is

This repository is a **prompt/response database**: every entry pairs an exact prompt with the exact response it received, organized by category, and tagged for quick scanning. It's built for browsing, referencing, and studying patterns in how an AI model handles tricky, ambiguous, or adversarial prompts — from letter-counting puzzles to emoji requests to logic riddles.

Nothing is edited or fact-checked into a "better" answer — this is a straight, faithful record of what was actually said.

---

## 📚 Table of Contents

| Category | Description | Entries |
|---|---|:---:|
| [🐾 Emojis](./emojis/README.md) | Requests for specific animal/object emoji | 10 |
| [🧩 Logic & Riddles](./logic-riddles/README.md) | Puzzles, riddles, and lateral-thinking prompts | 4 |
| [🔢 Factual & Math Errors](./factual-math-errors/README.md) | Letter-counting, arithmetic, trivia, and word puzzles | 16 |
| [🎭 Roleplay & Safety](./roleplay-safety/README.md) | Roleplay, opinions, and safety-relevant prompts | 5 |
| [🛑 Meta Commands](./meta-commands/README.md) | Single-word conversational commands (stop, pause, reset...) | 19 sub-entries |

---

## 🏷️ Tag Legend

| Tag | Meaning |
|---|---|
| `hallucination` | Confidently incorrect or fabricated information |
| `self-correction` | Model caught and fixed its own error mid-response |
| `self-correction-failed` | Model attempted correction but still landed wrong |
| `resolved` | Final answer given was accurate/correct |
| `unresolved` | Question was declined or not answered |
| `refusal` | Model declined to respond |
| `fabricated` | Invented content presented as real (keys, ISBNs, etc.) |
| `honest-failure` / `honest-retraction` | Model explicitly admitted it couldn't answer reliably |
| `constraint-puzzle` | Prompt required meeting multiple strict constraints |
| `nonsensical-output` | Response included non-sequitur or garbled content |

---

## 🗂️ Repository Structure

```
AI-Hallucination-Prompts/
├── README.md                    ← you are here
├── emojis/
│   └── README.md
├── logic-riddles/
│   └── README.md
├── factual-math-errors/
│   └── README.md
├── roleplay-safety/
│   └── README.md
└── meta-commands/
    └── README.md
```

---

## 📝 Notes

- Prompt and response text is reproduced exactly as given in the original conversation.
- No fact-checking, editorializing, or "correcting" of responses has been applied — tags describe outcomes, but original content is unmodified.
- Timestamps and model metadata were not present in the source material.

---

<div align="center">
<sub>Last organized: 2026-08-09</sub>
</div>
