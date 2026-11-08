# Steady Steps 🌱

A gentle **Grade-2 catch-up** app in **reading** and **math** — voice-first, no timers, confidence first. Single-file, installable PWA (works offline). Cornerstone Studio · *Glory to God alone · AMHG*.

Built for a child who is a little behind and needs encouragement, not pressure.

## What's inside

**📖 Reading**
- **Word Flash** — ~130 Grade-2 high-frequency (sight) words; hear it / sound it out.
- **Story Time** — 14 short decodable stories (one per phonics focus), read-aloud, **tap any word to hear it**, adjustable text size + easy-read spacing, and a gentle comprehension check (spoken, 2 tries then it shows you).
- **Build a Word** — 90 spelling words across 6 phonics sets (Magic-e, Blends, Digraphs, Vowel Teams, Bossy-R, Tricky Words); listen, then build the word from tiles.

**🔢 Math**
- A short **placement check** that "walks down to solid ground" so she starts where she actually is — *no grades, no marks*.
- **14 skill steps** with endless, randomized questions: Count & Compare · Add to 20 · Take Away to 20 · Tens & Ones · Add / Take Away Bigger Numbers (with carrying/borrowing) · Skip Counting · Even & Odd · Count Money · Tell the Time · Groups & Arrays · Story Problems · Halves & Quarters · Shapes & Sides.
- Spoken strategy hints + worked-answer reveals; mastery = 4 in a row; gentle error handling with KJV encouragement (never names the child).

**For grown-ups:** tap ⚙️ (code **2020**) for a progress snapshot and to change the name or reset.

## How it's made
- One file: `index.html` (ES5, no build step, no dependencies). `manifest.json` + `sw.js` + `icon.svg` make it an installable, offline PWA.
- Voice via the browser's SpeechSynthesis; all progress saved per-child in `localStorage`.
- Pedagogy and content reuse Cornerstone Studio's existing apps (solid-ground's diagnostic, Kingdom-Kids-Academy's strategy bank, dominion-speller's word sets).

## Run / deploy
- **Locally:** open `index.html`, or serve the folder (`python -m http.server`) and visit it.
- **GitHub Pages:** push this folder to a public repo and enable Pages (Settings → Pages → deploy from `main`, root).
