# Event — E(t,x)

**A generative ambient instrument. A single HTML file. Never the same session twice.**

> *"Time and space combined to generate a sonic experience."*

Version 1.0 — Yuwa / Positive Lofi · 2025–2026

---

## Quick Start

Open `event_v1.html` in Chrome. Click anywhere to wake the sound. The first note falls within 3–5 seconds. Click again to pause.

**Control panel** — click `···` at the bottom of the screen.

---

## What Event Is

Event is a generative ambient instrument — an algorithmic score running entirely in the browser, no installation required, no server, no framework. A single HTML file of ~200KB.

**This is not AI-generated music.** No trained model. No music dataset. No neural network. Every rule is hand-written: which modes, which preferred intervals, which stability for which harmonic degrees, which density for which dynamic state. The system plays these rules — it does not invent them.

This practice has a lineage: Xenakis with stochastic formulas (1957), Brian Eno with generative systems (1978), Steve Reich with phase patterns, Éliane Radigue calibrating drone interactions. Event belongs to this tradition. The author composed the patch. The instrument plays.

### The Botanica Identity

Event's sonic identity is **Botanica**: organic, alive, never saturated. Like a forest — something is always happening, but nothing overwhelms anything else. Constant micro-events, inhabited silences, synthesized natural foley, brief arpeggios, organic percussion. Pads exist but pass. The drone is subliminal.

### The Physical Event

In relativistic physics, an event is a point in spacetime — non-reproducible, unique by definition. At launch, the system contacts [random.org](https://www.random.org) to obtain real atmospheric radio noise, combines it with a precision timestamp (`Date.now()` — universal UTC time) and `performance.now()` (local session time), and initializes from a seed that will exist only once in the history of the universe.

---

## Sound Architecture

Event is organized in independent layers that coexist without interfering.

**The drone** — permanent subliminal foundation. Five sine oscillators at irrational ratios (φ, π, e). Never heard as a drone — sensed as coherence.

**Emil·in** — long notes with string transient, harmonics, soft even-order saturation.

**Karplus-Strong** — physical modeling of plucked string. Short, dry, koto or pizzicato.

**Arpeggios** — 3 to 8-note fragments by stepwise motion. Botanica's natural melodic language.

**Pluck / Bow / Wood / Glass / Voice** — organic timbres drifting freely via floating weights.

**Acoustic / Prepared piano** — physical modeling with simulated soundboard.

**Organic percussion** — kick, conga, shaker, wood click, frame drum. All synthesized.

**Foley** — water drops, leaves, pebbles, wood creaks. Synthesized natural sounds, every 3–30s.

**Analog degradations** — wow & flutter, cassette hiss, tape saturation, crackle. The instrument's patina.

---

## Harmonic System

**102 tonalities** — 11 modes across 12 roots, weighted by Botanica affinity.

| Mode | Weight | Character |
|---|---|---|
| Penta m / Penta M | 4.0 | universal, contemplative, no semitones |
| Dorian | 3.5 | dark jazz, softly melancholic |
| Lydian | 3.0 | floating, unreal |
| Japanese | 2.5 | minimalist, In pentatonic |
| Mixolydian | 2.0 | warm, bluesy |
| Major / Minor | 1.2 / 1.0 | contrast — luminous or melancholic |
| Phrygian / Lyd.aug / Locrian | 0.6–0.3 | rare exotic colors |

### Pivot Harmonic Transitions

When Event changes tonality, it modulates through a **pivot note** — a note belonging simultaneously to both scales. The pivot is chosen by stability score in each scale (I=3, V=2.5, III=2...). Transition unfolds in 3 phases: convergence → hold → opening. Total: 11–21 seconds. No harmonic clash possible.

---

## Floating Instrument Weights

No rigid orchestrations. **8 sonic colors** blend continuously over several minutes — instrument probabilities drift slowly and permanently. All instruments are always potentially present from the first minute (baseline floor: 0.25). Every 2.5–5 minutes, Event triggers a solo — a melodic fragment played by the instrument with the highest floating weight at that moment.

---

## Dramatic Arc

Event remembers itself at session scale. An intensity curve over ~10 minutes modulates probabilistic biases — it forces nothing, it weights the dice.

| Segment | Duration | Character |
|---|---|---|
| Hook | 0–15s | Dense immediately — first note at 3–5s |
| Installation | 15s–2min | The space establishes itself |
| Breathing | 2–4min | Dip — slow harmonic transitions |
| Rise | 4–7min | Progressive return |
| Climax | 7–9min | Maximum density |
| Dissolution | 9–11min | Withdrawal |
| Free flow | 11min+ | Pure probabilistic — no end |

---

## Interface

**`···`** at the bottom → control panel.

### Performance Modes
- **normal** — dramatic arc active, free flow
- **experimental** — long silences, glitches more present
- **concert** — permanent density
- **original ◈** — reset to Ab Major, initial state

### Harmonic Controls
- **scale** — lock the mode or leave on auto
- **root** — lock the root or leave on auto

Both locked together → harmonically coherent material for DAW recording.

### Tools
- **master / drone** — relative volumes
- **seed** — hexadecimal session identifier. Note it to return to a starting point.
- **retrig** — new seed from random.org
- **backing** — show tonal box (current root + mode, pivot display during transitions)
- **export** — WAV 32-bit float stereo or 1080p VP9 video

---

## DAW Recording

1. Lock scale + root (e.g. D Lydian for something floating)
2. Launch ● wav from the panel
3. Let it run — everything produced is harmonically coherent
4. Cut interesting passages in your DAW

---

## Technical Notes

**Browsers** — Chrome 66+ recommended. Firefox 76+, Safari 14.1+, Edge 79+ supported.

**CPU** — 15–25% in active state on a modern computer. 5–10% in sparse.

**Offline** — works without connection if Google Fonts are cached. Fallback seed on `Date.now() + performance.now()` if random.org is unavailable.

**Single file** — no dependencies, no server, no build step. Share by email, post on GitHub, open from Files. Zero friction between having the file and hearing the sound.

---

## License

**Code — MIT License**
Fork, modify, integrate freely.

**Audio generated by Event — CC BY 4.0**
Free to use including commercially. If you publish a recording made with Event, please credit:

> *Generated with Event — E(t,x) by Yuwa / Positive Lofi*

When you buy a guitar, you pay for the instrument. Event is free — the credit is the counterpart.

---

> *"It's a modular synth session whose patch I composed."*

**Event — E(t,x) — v1.0**  
Yuwa / Positive Lofi — 2025–2026  
[youtube.com/@PositiveLofi](https://youtube.com/@PositiveLofi)
Yuwa / Positive Lofi — 2025–2026  
[youtube.com/@PositiveLofi](https://youtube.com/@PositiveLofi) 
