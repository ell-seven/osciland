# OSCILAND · Demo

**Draw · ride · crash · repeat.**
A physics-driven bike game for the browser where the soundtrack is generated live with pure math, the same way oscilloscope music is made.

### ▶ [Play the demo in your browser](https://ell-seven.github.io/osciland/)
No install and no download. Works on desktop and mobile.

---

## What makes it different

- **Hand-made physics engine.** Verlet / position-based dynamics at a fixed 1/120 s step: a ragdoll rider, flips in the air, a wheelie that's actually hard. No game engine and no libraries.
- **Music made of math.** Every song and sound effect is synthesized in real time from parametric functions, oscillators and FM (Web Audio + AudioWorklet). There isn't a single audio file in the game. The intensity follows your speed.
- **16-bit pixel art worlds** with parallax layers, animated waterfalls, enemies and particles. The rendering pipeline was built for the game.
- **Corrupted mode.** Every level has a harder red version with meteors, diving flyers and lightning strikes, plus a roulette orb that can flip your run between Normal and Corrupted.
- **Mystery blocks with 10 abilities:** nitro, low gravity, giant jump, invincibility, hamster wheel, wall glue, echo rewind, time slow and more.
- **Level editor.** Draw your own tracks, add threats and abilities, tweak gravity, weather and music, then share them with a single link or code.
- **Ghosts, medals and replays.** Race your 3 best runs, replay your last crash and earn bronze through author medals.
- **Music studio.** Compose your own math-based songs on a virtual oscilloscope (draw a shape and hear it) and use them as level music.
- **Plays everywhere:** keyboard, gamepad and touch controls.

## This demo includes

| | |
|---|---|
| **00 · Tutorial** | Learn to ride, jump, double jump, duck and turn around |
| **01 · Abandoned Aqueduct** | 6 sectors in Normal and Corrupted |
| **Open canvas** | The full level editor |

🔒 **5 more worlds** (Stepped Quarry, Iron Roots, Chain Well, The Sleeping Machine, The Spire) are coming with the full game. **Coming soon to Steam.**

## Controls (keyboard)

| Key | Action |
|---|---|
| ↑ / ↓ | Pedal / brake |
| ← / → | Lean |
| X | Jump (press again in the air to double jump) |
| C | Duck |
| Z | Turn around |
| R | Restart |
| Esc | Pause |

Keys can be remapped in Options. Gamepads are supported. On mobile, hold the right half of the screen to pedal and the left half to brake.

## Tech

Vanilla JavaScript (ES modules), Canvas 2D and the Web Audio API, with zero dependencies. The game was built with an AI-assisted workflow (Claude Code), where I worked as designer and director, and it's covered by an automated test suite for physics, levels and audio.

---

## En español

**Osciland** es un juego de bici para el navegador, con física propia y una banda sonora generada en vivo con matemática pura, como la música de osciloscopio. Esta demo trae el Tutorial, el primer mundo (Acueducto abandonado, en modo Normal y Corrupted) y el editor de pistas. El juego completo llega pronto a Steam.

---

Created by **Lautaro Rodriguez · Seven**
Available for freelance work: HTML5 games, playable ads and interactive web.
📧 lauti.rod.2003@gmail.com · 📸 Instagram [@ellseven](https://www.instagram.com/ellseven/)

© 2026 Lautaro Rodriguez. All rights reserved.
