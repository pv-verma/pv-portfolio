# 🎮 Prisha Verma — Quest Log Portfolio

A single-page, gamified "RPG save file" portfolio. No build step, no dependencies, no server — just `index.html`.

## ✨ Features

- **Retro RPG HUD** — level badge, XP bar, and scroll-to-gain-XP mechanic that levels you up as you explore
- **Press Start intro screen** with CRT-style scanline flicker
- **Player Profile** — character card with avatar, HP bar, class, PATH, and LOADOUT
- **Character Stats** — RPG attribute meters (INT / CHA / CRE / WIS / VIT) and a skill tree with segmented bars
- **Quest Log** — project cards styled as completed quests, newest first, each with difficulty stars, dates, tech tags, and GitHub/live links
- **Badges** — certification cards (CS50P, Claude Companion, GenAI Adept, Prompt Engineer, Python Master)
- **Chronicles, Lore & Backstory** — achievements, interests, and an education timeline
- **8-bit sound effects** (mutable with the 🔊 button or the `M` key)
- **Fully responsive** — two-column desktop grid collapses to a single column under 760px

## 🕹 How to View

Open `index.html` directly in any modern browser — that's it.

Or serve it locally if you prefer:

```bash
# Python
python -m http.server 8000
# then visit http://localhost:8000

# Node
npx serve .
```

## 🗂 Structure

| Section | What's inside |
|---|---|
| Player Profile | Avatar, HP, class line, intro lines (PATH & LOADOUT) |
| Character Stats | Attribute meters + skill tree |
| Quest Log | Projects as quests — GitHub Repo Health Analyzer, Keystroke, Password Generator & Strength Checker, Caption Forge, Number Oracle |
| Badges | Certifications, newest first |
| Chronicles | Events, leadership, creative side-quests |
| Lore | Interests & "special trait" |
| Backstory | Education timeline |
| Contact | Email + socials |

## 🛠 Built With

- **HTML5 + CSS3 + Vanilla JavaScript** — no frameworks, no dependencies
- **Google Fonts** — `Press Start 2P` (headings/HUD) & `VT323` (body)
- **Inline SVG icons** (GitHub mark)

## 📜 Customizing

All content lives in `index.html`:

- **Projects** → the `#quests` section; each `<article class="card">` is one quest
- **Skills/attributes** → the `#stats` section (`seg` bars use filled `<i class="on">` segments)
- **Colors** → CSS variables in `:root` (`--gold`, `--cyan`, `--pink`, `--green`, `--red`)
- **Quest order** → newest first; renumber the `QUEST 01…` labels after reordering

## 📬 Contact

- ✉ [prisha.verma@proton.me](mailto:prisha.verma@proton.me)
- 💻 [github.com/pv-verma](https://github.com/pv-verma)
- 🎨 [@pxvie.lab](https://instagram.com/pxvie.lab)

---

© 2026 Prisha Verma · QUEST COMPLETED · THANKS FOR PLAYING!
