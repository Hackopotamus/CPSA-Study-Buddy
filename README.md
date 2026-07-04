# 🛡️ CPSA Study Buddy

A free, offline-friendly study tool for the **CREST Practitioner Security Analyst (CPSA)** exam. Drill 800+ practice questions by topic, track your weak areas, and sit full timed mock exams that mirror the real format — all in a single HTML file with no installation, no dependencies, and no server.

Created by **Hackopotamus**, with the help of Claude.

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

### On your phone
Open the file in Chrome on Android, then tap the **⋮** menu → **Add to Home screen**. It'll launch full-screen like an app and works offline.

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

## ⚠️ Important Disclaimer

- This is a **community study aid**, not official CREST material and not affiliated with or endorsed by CREST.
- The mock exam replicates the **format, timing, and pacing** of the real thing — it does **not** contain real exam questions, and passing the mocks does **not** guarantee you'll pass the actual CPSA. Treat a consistent 75%+ across several full mocks as a readiness signal, not a certainty.
- Question content is provided for revision purposes only. Always cross-check anything you're unsure of against authoritative sources.

---

## 🤝 Contributing

Spotted a wrong answer, a typo, or want to add questions? Open an issue or a pull request. Improvements to question quality are especially welcome.

---

## 📄 Licence

Add a licence of your choice here (e.g. [MIT](https://choosealicense.com/licenses/mit/)) so others know how they can use and share it.

> **Before publishing:** please confirm the question bank is cleared for redistribution. Community-written questions are fine to share; content copied from official CREST exams is not. Credit the original source if the bank came from elsewhere.

---

*Good luck with your CPSA — you've got this.* 🎯
