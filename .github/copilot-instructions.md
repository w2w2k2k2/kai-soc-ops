# Copilot Instructions (Soc Ops)

## ✅ Dev Checklist
- [ ] `npm run lint` passes
- [ ] `npm run build` succeeds
- [ ] `npm run test` passes

## Quick Start
1. `npm install`
2. `npm run dev` → open `http://localhost:5173/`

## Key Commands
- `npm run dev` — start dev server
- `npm run build` — production build
- `npm run test` — run unit tests
- `npm run lint` — ESLint

## Core Structure
- `src/App.tsx` — root app (game state)
- `src/hooks/useBingoGame.ts` — game logic hook
- `src/components/` — UI (StartScreen, GameScreen, BingoBoard, etc.)
- `src/utils/bingoLogic.ts` — board generation + bingo detection
- `src/data/questions.ts` — bingo prompts + free space

## Notes / Conventions
- Uses React 19 + TypeScript + Tailwind CSS v4
- Styling is Tailwind-only (no custom CSS files)
- Tests are Vitest + jsdom

## When Updating
- Keep instructions short; focus on what an agent needs to run, build, and reason about the repo.
- If you add new areas (e.g., a backend service), add a brief “Relevant area” section.
