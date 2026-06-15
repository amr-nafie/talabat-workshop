# Duck Duck Fight — Workshop Context

## What is this?
A workshop series for product managers at talabat with basic technical experience. The site is called **"Duck Duck Fight"** 🐤🍳🐦.

## Teams
- **Team 1 → KakSquad** (😇) — pond/green theme, quack sounds
- **Team 2 → Fowl Play** (😈) — purple theme, dark mode surprise

---

## Workshop 1 — Git Basics ✅
**Status:** Completed

### What they did
- Split into 2 teams (2 people each)
- Customized their team pages: name, slogan, picture, full restyle
- Used Claude to help write and restyle pages
- Learned: `git clone`, `checkout -b`, `pull`, `commit`, `push`, PRs

### What the teams built

**KakSquad** (PR #2 by @malakbedier)
- Pond/water theme — green gradient, water shimmer, lily pads (🪷), water drops (💧)
- Quack sound effects using Web Audio API
- Slogan: "All quack, no slack 🦆"

**Fowl Play** (PR #3 by @salmasaleh1)
- Purple theme with "Surprise" dark mode button
- Suspense background music (`suspense.mp3`)
- Slogan: "We don't play fair, we play fowl. 😈"

---

## Workshop 2 — Prompting Claude 🤖
**Status:** In progress

### Topic
Using Claude more efficiently — learning commands, concepts, and prompting techniques.

### What they'll do
- Each team builds an **Angry Birds** game on their game page
- Game is built entirely through Claude prompts
- Game lives inside a `<canvas>` element in `game.html`

### Concepts & commands taught
- **Tokens** — How Claude reads input (its "fuel")
- **CLAUDE.md** — Permanent project context file
- **/model** — Switch between Sonnet (fast) and Opus (smartest)
- **/clear** — Reset conversation when Claude gets confused
- **Plan mode** — Think first, build second (shift+tab)
- **MCP** — Plug-ins that give Claude superpowers (web, docs, APIs)
- **Skills** — Reusable prompt templates

### Prompting tips taught
- Be specific
- Break it down
- Iterate
- Debug together
- Give context

---

## Theme & Design
- **Duck theme**: Good Duck (😇) vs Evil Duck (😈)
- **Light background** (#FFFDF4 cream), cartoon/comic-book style
- **Font**: Bangers (headings) + Space Grotesk (body) from Google Fonts
- **Team 1 color**: Sunny yellow/gold (#FFD93D, #B8860B)
- **Team 2 color**: Purple/violet (#B794F6, #6D28D9)
- **Emojis**: 🐤 for Team 1, 🐦 for Team 2, 🍳 for VS badge
- Thick black borders, hard offset shadows, speech bubbles, floating emoji animations
- No frameworks, no build tools

## File structure
```
talabat-workshop/
├── .gitignore
├── CLAUDE.md               ← this file
├── index.html              ← Homepage: links to team pages
├── slides.html             ← Workshop 1 slides (Git basics)
├── slides2.html            ← Workshop 2 slides (Prompting Claude)
├── team1/
│   ├── index.html          ← KakSquad page (pond theme, quack sounds)
│   ├── game.html           ← KakSquad game page (canvas, Angry Birds)
│   ├── picture.png         ← Original placeholder
│   └── new picture.png     ← KakSquad's custom picture
└── team2/
    ├── index.html          ← Fowl Play page (purple + dark mode surprise)
    ├── game.html           ← Fowl Play game page (canvas, Angry Birds)
    ├── picture.png         ← Fowl Play's custom picture
    └── suspense.mp3        ← Background music for surprise button
```

## Repo
- GitHub: https://github.com/amr-nafie/talabat-workshop.git
- Main branch: `main`
