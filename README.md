# SAT Vocab Mastery — 60 Advanced Words

> Master the 60 high-frequency advanced words SAT Reading & Writing actually tests — with distraction-free flashcards, SAT-style context practice, and an adaptive mastery quiz.

**Live Demo:** **https://flynntaggart26.github.io/SAT-Vocabulary/**

![SAT](https://img.shields.io/badge/SAT-60%20advanced%20words-6C5CFF?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/dependencies-zero-00D9A5?style=flat-square)
![Single File](https://img.shields.io/badge/app-single%20file%20HTML-blue?style=flat-square)
![Offline Ready](https://img.shields.io/badge/offline-ready-orange?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)
![Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-222222?style=flat-square)

---

## 📖 Table of Contents

- [Why This Exists](#-why-this-exists)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [How to Study With This App](#-how-to-study-with-this-app)
- [Word Categories](#-word-categories)
- [Getting Started](#-getting-started)
- [Usage Guide](#-usage-guide)
- [How Mastery Tracking Works](#-how-mastery-tracking-works)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Browser Support & Offline Use](#-browser-support--offline-use)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [FAQ](#-faq)
- [License](#-license)

---

## 💡 Why This Exists

Studying for the SAT, I kept hitting the same wall: I would look up a difficult word, read the dictionary definition, and move on — only to miss the same word again in the next practice test.

Passive definitions don't stick. The SAT doesn't test whether you can recite a definition. It tests whether you understand **nuance in context**: what a word implies, what it contrasts with, and which trap answer it is designed to create.

So I built myself a focused study webpage:

1. See every word **in a real SAT-style sentence**, not in isolation.
2. Actively recall — type the word, choose the usage, explain the nuance.
3. Track true mastery, without fooling myself with "I revealed the answer, so I know it."

This repository is that tool, made public for any student, teacher, tutor, or self-learner preparing for the SAT.

---

## 🌐 Live Demo

No install needed:

**https://flynntaggart26.github.io/SAT-Vocabulary/**

Open it on desktop or mobile. Your progress saves automatically in your browser.

> Tip: Add it to your home screen for an app-like study experience.

---

## ✨ Features

### 1. 📇 Flashcards — Pure Focus, One by One

Distraction-free studying: **one card at a time**, no cluttered grid.

- **60 words in 6 categorized groups** (10 words each, see [Word Categories](#-word-categories))
- Each card includes:
  - Word + pronunciation + part of speech
  - SAT-aligned definition
  - Real-life example sentence
  - Synonyms / antonyms
  - Mnemonic hint
  - SAT nuance note + SAT tip (revealed on demand)
- Navigation: click arrows, **← → keyboard**, mobile swipe, Shuffle
- Filters: All / To Learn / Mastered / ★ Saved
- In-category search
- Mark **Mastered** / **★ Saved** — persists in `localStorage`
- Keyboard shortcuts:
  - `Space` — Reveal nuance
  - `← / →` — Previous / Next
  - `F` — Toggle mastered
  - `S` — Toggle saved

### 2. ✍️ Fill in the Blank — Context Practice

Because recognition ≠ usage. Here you **type** the missing word.

- 4 curated sets (Words 1–15, 16–30, 31–45, 46–60) + Mixed random 12
- SAT-style sentence contexts, not dictionary repetition
- `Enter` to check quickly
- **Check** validates and auto-marks mastery only on a correct typed answer
- **Reveal** shows the answer **without** counting as mastered — you must type it yourself to earn it
- Bulk actions: Check All / Reveal Answers + per-set score

### 3. 🏆 Mastery Quiz — SAT-Style Assessment

Mixed question types exactly how the SAT tests vocabulary:

- **Definition** — choose the correct meaning
- **Sentence Use** — choose the word that fits the context
- **Synonym** — choose the closest equivalent
- 10-question standard round or 20-question challenge
- Progress bar, instant explanations, per-question auto-mastery
- Scoring levels:
  - 🌱 **Novice** (0–59%) — Keep reviewing flashcards
  - 📘 **Proficient** (60–79%) — Solid, but gaps remain
  - 🔥 **Advanced** (80–89%) — SAT-ready
  - 👑 **Master** (90–100%) — Elite vocab command

### 4. 📊 Progress & Word List

- Sticky header: mastered / total, % progress bar, best quiz score, study streak
- **Word List** table: all 60 words with category + CSV export for Anki / spreadsheets
- 100% offline after first load, zero backend, zero tracking

---

## 🧭 How to Study With This App

Recommended 20-minute loop that worked for me:

1. **Learn (8 min):** Pick one category in Flashcards. Go one-by-one. Reveal nuance only after you try to recall.
2. **Apply (7 min):** Do one Fill-in-the-Blank set for the same words. Type, don't guess.
3. **Test (5 min):** Run a 10-question Mastery Quiz. Aim for 80%+ before moving to the next category.
4. **Repeat:** Star difficult words, export them to CSV, and re-test the next day.

Honest mastery rule used throughout the app: **seeing the answer never counts. Only producing it counts.**

---

## 🗂️ Word Categories

| # | Category | Focus | Words |
|---|----------|-------|-------|
| 1 | 👁️ Clarity & Meaning | How clear, confusing, or precise an idea is | Abstruse, Ambiguous, Anomalous, Arcane, Convoluted, Enigmatic, Esoteric, Obfuscate, Opaque, Disparate |
| 2 | 💭 Feelings & Attitudes | Emotions, moods, and outlook | Antipathy, Apathy, Austere, Lethargic, Querulous, Rancorous, Sanguine, Wistful, Magnanimous, Solicitous |
| 3 | 💬 Voice & Social Style | How people speak and interact | Laconic, Loquacious, Verbose, Taciturn, Reticent, Gregarious, Reclusive, Demure, Diffident, Sardonic |
| 4 | ⚙️ Actions & Decisions | Choices and consequences | Belie, Capitulate, Circumvent, Mitigate, Exacerbate, Pragmatic, Fastidious, Scrupulous, Venerate, Vilify |
| 5 | ⏳ Time & Presence | Duration, frequency, abundance | Ephemeral, Immutable, Volatile, Pervasive, Ubiquitous, Sporadic, Prolific, Propitious, Resilient, Precocious |
| 6 | ⚔️ Conflict & Critique | Disagreement and criticism | Belligerent, Deride, Diatribe, Desultory, Hackneyed, Iconoclast, Impetus, Subversive, Cogent, Trenchant |

Each word includes SAT nuance (how College Board uses it), a common trap to avoid, synonyms/antonyms, and a fill-in-the-blank sentence.

---

## 🚀 Getting Started

No build step, no dependencies. Just open `index.html`.

```bash
# 1. Clone
git clone https://github.com/Flynntaggart26/SAT-Vocabulary.git
cd SAT-Vocabulary

# 2. Open
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

Or simply visit the Pages site — no clone required.

### Run with a local server (optional, recommended for mobile testing)

```bash
npx serve .
# or
python -m http.server 8000
```

Then open `http://localhost:8000`.

---

## 📘 Usage Guide

### Flashcards

- Select a category pill (e.g. Voice & Social Style).
- Use search to narrow within that category.
- Press `Space` or Reveal to see mnemonic + SAT nuance + tip.
- Mark mastered only when you can recall meaning + use without help.
- Use Shuffle for interleaved practice.

### Fill in the Blank

- Choose Set 1–4 or Mixed.
- Type the missing word in each sentence input.
- Press `Enter` in any input or click Check All.
- Green = correct and auto-mastered. Red = review the explanation and retry.

### Quiz

- Start 10-question quiz for daily check, 20-question for full review.
- Answer all types: definition, usage, synonym.
- Check your level at the end. Below 80%? Go back to flashcards for missed words — they are listed in the results.

### Word List & Export

- Open Word List tab for quick reference of all 60 words.
- Click Export CSV to download `sat-vocab.csv` for Anki, Quizlet, or Excel.

---

## 🧠 How Mastery Tracking Works

Progress is stored locally in your browser (`localStorage`), no account needed.

| Key | Purpose |
|-----|---------|
| `sat-mastered` | Set of mastered word strings |
| `sat-bookmarked` | Set of starred / saved words |
| `sat-best` | Best quiz score |
| `sat-streak` | Study streak metadata |

Rules:

- Flashcards: **Mark mastered** button → counts.
- Practice: **Check** with correct typed answer → auto-mastered.
- Quiz: correct answer → auto-mastered for that word.
- **Reveal never counts** — intentional to avoid false mastery.

Reset progress: Browser DevTools → Application → Local Storage → delete `sat-*` keys, or clear site data.

---

## 🏗️ Project Structure

```text
SAT-Vocabulary/
├── index.html   # single-file app (HTML + CSS + JS + 60-word dataset)
└── README.md    # documentation
```

All logic lives in `index.html` for maximum portability:

- 60-word dataset with definitions, nuance, examples, hints, fill sentences, categories
- Flashcard renderer + filters + search + shuffle
- Fill-in-the-blank generator + validator
- Quiz generator (definition / usage / synonym) + scoring
- Progress / streak / CSV export / localStorage persistence

Why single-file? Easy to share with classmates, email, host anywhere, and run offline from a USB stick.

---

## 🛠️ Tech Stack

- Vanilla HTML / CSS / JS — no frameworks, no build, no dependencies
- Google Fonts: Fraunces (display), Inter (UI), JetBrains Mono (phonetics)
- Responsive CSS: mobile swipe, sticky header, keyboard-first design
- Browser `localStorage` for persistence
- GitHub Pages for hosting

Lighthouse-friendly: one request after fonts, works offline after first load.

---

## 🌍 Browser Support & Offline Use

- Works in all modern browsers (Chrome, Edge, Firefox, Safari).
- 100% offline after first load — fonts aside, no network calls.
- Mobile-friendly: swipe between flashcards, large tap targets, responsive tables.

---

## 🗺️ Roadmap

- [ ] Spaced-repetition scheduling (next-review date + due queue)
- [ ] Audio pronunciations (Web Speech API)
- [ ] Export mastered list as Anki deck (`.apkg`)
- [ ] Dark / light theme toggle + print-friendly word list
- [ ] 120-word expansion + SAT Reading passage examples

Have an idea? Open an issue — study-focused suggestions are welcome.

---

## 🤝 Contributing

Contributions are welcome, especially from students and tutors:

1. Fork the repo
2. Create a branch: `git checkout -b feat/your-idea`
3. Edit `index.html` (words array, UI, or quiz logic)
4. Test by opening `index.html` locally
5. Commit and open a Pull Request

Small, focused PRs are best: fix a typo, improve an example sentence, add a mnemonic, or clarify an SAT nuance.

---

## ❓ FAQ

**Is this a complete SAT prep course?**
No. This is a focused vocabulary tool for high-frequency advanced words. Pair it with official practice tests for reading, writing, and math.

**Do I need to install anything?**
No. Open the live site or double-click `index.html`.

**Does it track me?**
No. No analytics, no backend, no cookies. Progress stays in your own browser.

**Can I use this in class?**
Yes. MIT licensed — teachers and tutors can use, fork, and adapt freely with credit.

---

## 📄 License

MIT — do what you want, credit appreciated.

Built while studying for the SAT: because looking up definitions wasn't enough, I built a tool that forces real recall in context.
