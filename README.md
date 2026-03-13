# 🎉 Soc Ops

**Soc Ops** is a fast, friendly social bingo game for in-person mixers, team offsites, classrooms, and community events.

Instead of awkward small talk, players walk around, meet new people, and mark squares as they find someone who matches each prompt. First to get **5 in a row** wins.

👉 Want to customize this for your group? Start with the lab guide: **[.lab/GUIDE.md](.lab/GUIDE.md)**

---

## Why this project is fun

- 🧊 **Breaks the ice quickly** with simple conversation starters.
- 🤝 **Encourages real interactions** instead of staying in familiar circles.
- 📱 **Mobile-friendly gameplay** that works great during live events.
- ⚡ **Quick setup** with Vite + React + TypeScript.

---

## How it works

1. Open the app and tap **Start Game**.
2. Walk around and find people who match each square.
3. Tap squares as you get matches.
4. Hit **BINGO** by completing any full row, column, or diagonal.
5. Keep playing to fill more of the board.

---

## Quick start

### Prerequisites

- [Node.js 22+](https://nodejs.org/)

### Run locally

```bash
npm install
npm run dev
```

Then open the local URL shown by Vite.

### Build for production

```bash
npm run build
```

---

## Customize your bingo prompts

You can tailor the game to your event by editing the prompt list in:

- `src/data/questions.ts`

Replace the default questions with prompts relevant to your team, conference, or class.

---

## Scripts

```bash
npm run dev    # Start local dev server
npm run lint   # Run ESLint
npm run test   # Run test suite
npm run build  # Type-check and build
```

---

## Deployment

This project is configured to deploy automatically to **GitHub Pages** on pushes to `main`.
