# SAT Vocab Mastery — 60 Advanced Words

> Learn the 60 high-frequency advanced words SAT Reading & Writing actually tests — with pure one-by-one flashcards, context practice, and an adaptive mastery quiz.

Live site: **https://flynntaggart26.github.io/SAT-Vocabulary/**

![SAT Vocab](https://img.shields.io/badge/SAT-60%20words-6C5CFF?style=flat)
![No dependencies](https://img.shields.io/badge/dependencies-zero-00D9A5)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## Why this exists

SAT vocab isn't about memorizing dictionary definitions — it's about **nuance in context**. Each word here is curated from real SAT passages and shown how College Board actually uses it: what it implies, what it contrasts with, and what trap it sets.

## Features

### 1. 📇 Flashcards — Pure Focus (One by One)
- **One card at a time**, distraction-free — no cluttered grid.
- **6 categorized groups** (10 words each):
  - 👁️ **Clarity & Meaning** — Abstruse, Ambiguous, Anomalous, Arcane, Convoluted, Enigmatic, Esoteric, Obfuscate, Opaque, Disparate
  - 💭 **Feelings & Attitudes** — Antipathy, Apathy, Austere, Lethargic, Querulous, Rancorous, Sanguine, Wistful, Magnanimous, Solicitous
  - 💬 **Voice & Social Style** — Laconic, Loquacious, Verbose, Taciturn, Reticent, Gregarious, Reclusive, Demure, Diffident, Sardonic
  - ⚙️ **Actions & Decisions** — Belie, Capitulate, Circumvent, Mitigate, Exacerbate, Pragmatic, Fastidious, Scrupulous, Venerate, Vilify
  - ⏳ **Time & Presence** — Ephemeral, Immutable, Volatile, Pervasive, Ubiquitous, Sporadic, Prolific, Propitious, Resilient, Precocious
  - ⚔️ **Conflict & Critique** — Belligerent, Deride, Diatribe, Desultory, Hackneyed, Iconoclast, Impetus, Subversive, Cogent, Trenchant
- Each card: word + pronunciation + POS + **SAT-aligned definition + real-life example + synonyms/antonyms**.
- **Reveal** for mnemonic, SAT nuance, and SAT tip (space bar).
- Navigate with click, **← →**, swipe, or Shuffle. Mark **Mastered** / **★ Saved** — progress persists in `localStorage`.

### 2. ✍️ Fill in the Blank — Context Practice
- SAT-style sentences where you **type** the missing word (not just recognize it).
- 4 sets (1–15, 16–30, 31–45, 46–60) + Mixed random 12.
- **Check** validates and only then counts toward mastery. **Reveal** shows the answer **without** counting as mastered — you must type it yourself to earn it.
- Keyboard: Enter to check.

### 3. 🏆 Mastery Quiz
- 10 or 20 questions per round — mixed types: **Definition**, **Sentence Use**, **Synonym** — exactly how SAT tests vocab.
- Progress bar, instant explanations, per-question mastery.
- Scoring levels: 🌱 Novice (0–59%), 📘 Proficient (60–79%), 🔥 Advanced (80–89% SAT-ready), 👑 Master (90–100%).

### Other
- **Header progress** — mastered / total, % bar, best quiz score.
- **Word List** table with category + CSV export.
- Zero dependencies, 100% offline after load, auto-saves to browser storage.

## Getting Started

Just open `index.html` — no build step.

```bash
# clone
git clone https://github.com/Flynntaggart26/SAT-Vocabulary.git
cd SAT-Vocabulary
# open
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

Or visit the Pages site.

## Project Structure

```
SAT-Vocabulary/
├── index.html   # single-file app (HTML + CSS + JS)
└── README.md
```

All logic lives in `index.html` for portability: 60-word dataset with definitions, nuance, examples, hints, fill sentences, categories, spaced-repetition state, quiz generator.

## How Mastery Works

- `mastered` and `bookmarked` are stored as sets in `localStorage` (`sat-mastered`, `sat-bookmarked`).
- Flashcards: **Mark mastered** button.
- Practice: **Check** with correct typed answer → auto-mastered.
- Quiz: correct answer → auto-mastered.
- **Reveal never counts** — intentional to avoid false mastery.

Reset progress: clear site data in browser DevTools → Application → Local Storage.

## Tech

- Vanilla HTML / CSS / JS, Google Fonts (Fraunces, Inter, JetBrains Mono), no frameworks.
- Responsive: mobile swipe, keyboard shortcuts.

## Roadmap ideas

- Spaced-repetition scheduling (next-review date)
- Audio pronunciations
- Export mastered list as Anki deck

## License

MIT — do what you want, credit appreciated.
