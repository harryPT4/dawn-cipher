<div align="center">

# Dawn Cipher

### A solstice cipher game about light, liberation, and Alan Turing.

<p>
  <img alt="Pure HTML" src="https://img.shields.io/badge/Pure-HTML%20%2B%20CSS%20%2B%20JS-ffb700?style=for-the-badge">
  <img alt="No build step" src="https://img.shields.io/badge/No-Build%20Step-39ff14?style=for-the-badge">
  <img alt="Optional Gemini" src="https://img.shields.io/badge/Gemini-Optional-004dff?style=for-the-badge">
</p>

<p>
  <strong>Four ciphers. One longest day. Daylight is finite.</strong>
</p>

</div>

---

## Play

Open [`dawn-cipher.html`](./dawn-cipher.html) in any modern browser.

No installs. No build tools. No account required. The Gemini-powered final level is optional and gracefully falls back to scripted responses.

## The Game

It is June 21, the solstice. A daylight meter drains in real time while you solve four connected puzzles. Each answer unlocks a narrative fragment tying together Alan Turing, Pride Month, Juneteenth, and the idea of truths hidden in plain sight.

| Cipher | Mechanic | What You Do |
| --- | --- | --- |
| I. The Shift | Caesar cipher | Rotate the decoder until the message reveals itself. |
| II. The Signal | Morse code | Decode dots and dashes into a world-changing name. |
| III. The Machine | Binary / ASCII | Convert 8-bit values into a word about liberation. |
| IV. The Question | Turing Test | Ask ENTITY-1 five questions, then choose Human or AI. |

## Highlights

- Real-time daylight meter with pressure, penalties, and low-light feedback.
- Typewriter narrative fragments between solved ciphers.
- Synthesized sound effects via the Web Audio API.
- Optional Gemini API integration for a live final Turing Test.
- Fully playable as a single static HTML file.
- Mobile-friendly layout with no external assets required.

## Why It Exists

Dawn Cipher treats the solstice as more than a visual theme. Light is the resource, ciphers are the mechanic, and the story is about people and truths that were delayed, hidden, or forced into shadow.

Alan Turing sits at the center: codebreaker, computing pioneer, and a gay man whose work changed the world while his own life was criminalized. The game ends by asking the question his work made famous: can a machine think?

## Optional Gemini Mode

The final level can run in two modes:

- **Scripted mode:** default, private, and fully playable offline.
- **Gemini mode:** paste a Gemini API key in the final level for live ENTITY-1 responses.

If the live API call fails, the game switches back to scripted mode so players are never stuck.

## Development

This project intentionally avoids a build pipeline. To edit:

```bash
open dawn-cipher.html
```

For local browser testing:

```bash
python3 -m http.server 4173
```

Then visit:

```text
http://127.0.0.1:4173/dawn-cipher.html
```

## Submission Notes

Built for the DEV.to June Solstice Game Jam 2026.

Prize categories:

- Best Ode to Alan Turing
- Best Google AI Usage

---

<div align="center">

**The cipher can be broken.**

</div>
