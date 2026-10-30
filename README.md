<p align="center"><img src="icons/icon-512.png" width="160" alt="HUSH icon"></p>

<h1 align="center">HUSH — Sing Back the Silence</h1>
<p align="center"><i>A rhythm survival game of light &amp; sound. The world forgot its song. Sing it back.</i></p>

---

You are a small light in a world gone quiet. Dark **Hushlings** drift in to swallow every sound — and every weapon you wield is an *instrument*. Pulse fires on the beat, Thump is the kick drum, Snare Arc cracks on 2 &amp; 4, Glissando sweeps once a bar. **Your build is your band**: each voice you gain adds a layer to a soundtrack that is generated live from how you play. Every Hushling you silence plays a note; chain them into a harmony and the melody climbs.

## Play

- **Web:** open `index.html` in any modern browser — no build step, no dependencies.
- **Install it:** host it (e.g. GitHub Pages), open it on your phone, and choose *Add to Home Screen*. It runs fullscreen with its own icon and works offline after the first load.

**Controls** — drag anywhere to move (or WASD / arrows). Voices attack on their own, on the beat. Tap ✺ / Space for a Crescendo when the ring is full. `P`/`Esc` pauses, `1–4` pick harmonies, `R` rerolls.

## What's inside

- **8 voices** (weapons that are also instruments), 5 levels each, up to 6 at once
- **8 harmonies** — including *Tempo*, which literally speeds up the song and every voice with it
- **8 Singers** to unlock, each starting with a different voice
- **4 Songs** — Dawn, Dusk, Abyss, Dream — each its own musical mode, palette and difficulty
- Enemies that move to the rhythm: Lurchers lunge on the downbeat, Wisps spit on beat 3, Veils drop their shields only on 2 &amp; 4
- **The Hush** boss every three minutes — defeat it and the song modulates up a key
- Rare **Golden Notes** to chase down, a **Daily Hum** seeded challenge with a twist, **Resonance** meta-progression, 19 feats, endless mode
- An end-of-run **shape of your song** — your run drawn as a waveform

All audio is synthesized in real time with the Web Audio API; all art is drawn procedurally on canvas. One HTML file.

## Project layout

```
index.html            the whole game
manifest.webmanifest  install metadata
sw.js                 offline cache (bump VERSION each release)
icons/                app icon (icon.svg is the source)
CHANGELOG.md
```

Made with every note.
