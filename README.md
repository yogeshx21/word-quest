# Word Quest 🎮

**Team Visionaries** — Yogesh Mondhe (Team Leader), Khushi Wanjari

An educational quiz + sentence-building arcade game built as a single self-contained HTML file, with no backend or build step required.

---

## 🕹️ About the Game

Word Quest blends two learning formats into one continuous quest:

- **General Knowledge Quiz** — multiple-choice questions across Science, Technology, Geography, History, Finance, Computer, Logical Reasoning and more.
- **Sentence Building** — a Hindi sentence is shown, and the player arranges the scrambled English words into the correct order.

Both formats are woven across **10 escalating difficulty levels**, from *Very Easy* to a final *Boss Level*.

### Core Features
- Live HUD: Score, XP, Level, Timer, Combo streak, and 3 Lives
- Combo system with bonus XP for consecutive correct answers
- Random Mini Challenges that break up the normal quiz rhythm
- **Fruit Crash** — a bonus arcade mini-game (tap fruits, avoid bombs, beat the clock)
- Player Profile (name saved locally) and a Quest History log
- Sound effects, background music, confetti and level-up animations
- Fully responsive layout for mobile and desktop

---

## 📁 Project Structure

This is a **single-file app** — everything (HTML, CSS, JS) lives in one file:

```
index.html
```

No dependencies, no `npm install`, no build tools needed.

---

## 🚀 Running Locally

Just open the file in any browser:

```bash
# Option 1: double-click index.html

# Option 2: quick local server (optional, avoids any file:// quirks)
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## ☁️ Deploying to Vercel

Since this is a static HTML file, deployment is simple.

### Option A — Vercel CLI
```bash
npm i -g vercel
vercel
```
Run this from the folder containing `index.html` and follow the prompts.

### Option B — GitHub Import
1. Push this repo to GitHub (make sure the file is named `index.html`).
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → **Import Git Repository**.
3. Select the repo and click **Deploy**.

### Option C — Drag & Drop
1. Rename the file to `index.html` if it isn't already.
2. On the Vercel dashboard, choose **Add New Project** and drag the file/folder in.

No environment variables or configuration are required — it's a plain static site.

---

## 🧠 Built With

Built entirely through AI prompting — from concept to final polish — using plain HTML, CSS and JavaScript (no external frameworks). See the competition submission PDF for the full list of prompts used during development.

---

## 📜 License

Submitted for the **Prompt & Play** build challenge. All rights reserved by Team Visionaries.
