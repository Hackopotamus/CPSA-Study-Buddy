# 🛡️ CPSA Study Buddy

A free, offline-friendly study tool for the **CREST Practitioner Security Analyst (CPSA)** exam. Drill 800+ practice questions by topic, track your weak areas, and sit full timed mock exams that mirror the real format — all in a single HTML file with no installation, no dependencies, and no server.

Created by **Hackopotamus**, with the help of Claude.

**▶️ Try it online:** [hackopotamus.github.io/CPSA-Study-Buddy](https://hackopotamus.github.io/CPSA-Study-Buddy/)

---

## ✨ Features

- **803 practice questions** covering the full CPSA syllabus, auto-sorted into 13 topic areas (Networking, Cryptography & PKI, Web Application, Windows & Active Directory, Linux & Unix, VPN & Tunnelling, Wireless, and more).
- **Three study modes:**
  - *All Questions* — shuffled across everything.
  - *Weak Only* — revisits questions you've got wrong more often than right.
  - *Spaced Repetition* — prioritises new and struggling questions, deprioritises ones you know.
- **Mock exam mode** — a full simulation of the real exam:
  - 120 questions / 2 hours / 60% (72/120) to pass, or shorter 60- and 30-question runs.
  - Live countdown timer that warns you as time runs low.
  - Flag questions and jump back to them, just like the real interface.
  - Free navigation between questions via a question-navigator grid.
  - Pass/fail result with a per-topic breakdown and full answer review.
- **Progress tracking** — every answer is remembered. A dashboard shows lifetime accuracy and which topics need work.
- **Save / load** — export your progress to a file and reload it anytime, so it survives across sessions and devices.
- **Works completely offline** — everything is embedded in one file. Great for quiet night shifts with no internet.

---

## 🚀 Getting Started

### Option 1 — Just open it
1. Download `cpsa-study-buddy.html` (or whatever you've named the file).
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari).
3. That's it — start studying.

### Option 2 — Host it with GitHub Pages
1. Add the HTML file to your repo (rename it to `index.html` if you want a clean URL).
2. Go to **Settings → Pages**, set the source to your main branch, and save.
3. Your study buddy will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## 💾 Saving Your Progress

The app tries to save progress automatically in your browser, but some environments block this. To be safe:

- Hit **Save** at the end of each session to download a small `.json` backup.
- Hit **Load** next time to restore it.
- Keep the backup in a cloud folder (e.g. Google Drive) if you want your progress to follow you between devices.

> **Note:** Progress is tied to each copy of the file. A `.json` backup will load into any copy, so it's your real save state.

---

## 🛠️ Tech Stack

Vanilla **HTML, CSS & JavaScript** — no frameworks, no build step, no dependencies. Everything (including the question bank) lives in a single self-contained file that runs entirely in your browser.

---

## 🙏 Credits

- **Question bank** sourced from the excellent work of **[cy83rv1p3r](https://github.com/cy83rv1p3r)** on GitHub — huge thanks for compiling and sharing it. Go check out their repos.
- **App** built by **Hackopotamus**, with the help of Claude.

> The original question set was last updated in **2024**. Some questions in this version may have been reworded, corrected, or updated since then, and the security landscape moves fast — always cross-check anything you're unsure of against authoritative sources.

---

## ⚠️ Important Disclaimer

- This is a **community study aid**, not official CREST material and not affiliated with or endorsed by CREST.
- The mock exam replicates the **format, timing, and pacing** of the real thing — it does **not** contain real exam questions, and passing the mocks does **not** guarantee you'll pass the actual CPSA. Treat a consistent 75%+ across several full mocks as a readiness signal, not a certainty.
- Question content is provided for revision purposes only.

---

## 🤝 Contributing

Spotted a wrong answer, a typo, or want to add questions? Open an issue or a pull request. Improvements to question quality are especially welcome.

---

## 📄 Licence & Use

**Free to use, free to share.** This project is openly distributed and available to anyone — study with it, fork it, host your own copy, pass it to a colleague. No restrictions.

Credit to the original question-bank author, [cy83rv1p3r](https://github.com/cy83rv1p3r), is appreciated if you build on this further.

---

*Good luck with your CPSA — you've got this.* 🎯
