# 📊 TCS NQT 2026 — Full Prep Tracker

> A sleek, fully offline-capable progress tracker for the **TCS NQT 2026** course by GeeksforGeeks — covering Verbal Ability, Numerical Reasoning, and Coding.

🔗 **[Live Demo → samar.github.io/tcs-nqt-tracker](https://samar.github.io/tcs-nqt-tracker)**

---

## ✨ Features

- **3 Sections covered** — Verbal (13 lectures), Numerical (14 lectures), Coding (13 lectures)
- **Per-lecture tracking** — mark practice questions, homework, articles, notes, and watch status
- **Real-time stats** — overall progress %, topics done, lectures completed
- **Target date system** — set a deadline per lecture, get overdue alerts
- **GitHub Gist sync** — save progress to a private Gist and access it from any device
- **Live countdown** — counts down to the TCS NQT exam (26 March 2026, 7:00 AM)
- **Dark / Light mode** — toggle with persistence via localStorage
- **Confetti 🎉** — fires when you complete a lecture 100%
- **No backend required** — pure HTML/CSS/JS, works entirely in the browser

---

## 🖼️ Preview

| Dark Mode | Light Mode |
|-----------|------------|
| ![dark](https://via.placeholder.com/400x220/0d0d0f/00f5ff?text=Dark+Mode) | ![light](https://via.placeholder.com/400x220/fdf6e3/0088aa?text=Light+Mode) |

---

## 🚀 Getting Started

### Option 1 — Use the live site
Just visit the [GitHub Pages link](https://samar.github.io/tcs-nqt-tracker) — no install needed.

### Option 2 — Run locally
```bash
git clone https://github.com/samar/tcs-nqt-tracker.git
cd tcs-nqt-tracker
# Open index.html in your browser
open index.html
```

No build step. No dependencies. Just open the file.

---

## 💾 Saving Progress

Progress is saved in two ways:

### Local (default)
Your progress is automatically saved to `localStorage` under your username. It persists across browser sessions on the same device.

### GitHub Gist Sync (cross-device)
1. [Create a private GitHub Gist](https://gist.github.com/) with a file named `nqt-progress.json`
2. [Generate a GitHub Personal Access Token](https://github.com/settings/tokens) with `gist` scope
3. Click **⚙ Sync** in the tracker, enter your Gist ID and token
4. Your progress is now synced across all devices

> Your token is stored only in your browser's localStorage — never sent anywhere except the GitHub API.

---

## 📚 Syllabus Covered

### Verbal Ability (13 lectures)
Nouns · Pronouns · Verbs · Adjectives · Adverbs · Prepositions · Conjunctions · Interjections & Determiners · Direct & Indirect Speech · Active & Passive Voice · Reading Comprehension · Jumbled Sentences · Vocabulary

### Numerical Ability & Reasoning (14 lectures)
Time & Work · Speed & Distance · Percentage · Ratio & Proportion · Profit & Loss · SI & CI · Number System · Mensuration · Clocks & Calendars · Series & Coding · Blood Relations · Seating Arrangement · Non-Verbal Reasoning · Algebra & Progressions

### Coding (13 lectures)
Arrays I–IV · Strings I–IV · Number Theory I–II · PYQ Practice Sets I–III

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | DM Mono · Syne · DM Sans (Google Fonts) |
| Sync | GitHub Gist REST API |
| Hosting | GitHub Pages |

---

## 📁 Project Structure

```
tcs-nqt-tracker/
└── index.html      # Everything — markup, styles, and logic in one file
```

---

## 🤝 Contributing

Found a broken link, wrong question, or missing lecture? PRs are welcome!

1. Fork the repo
2. Make your changes in `index.html`
3. Open a pull request with a brief description

---

## 📄 License

MIT — free to use, modify, and share.

---

<p align="center">made with ❤️ by <strong>samar</strong></p>
