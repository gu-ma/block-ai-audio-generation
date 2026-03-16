---
title: "02 — Sequence vs Raw Audio Generation"
draft: false
---

# 02 — Sequence vs Raw Audio Generation

One of the most useful creative decisions is choosing **what the model generates**:

- a sequence representation (notes/tokens/events), or
- raw/near-raw audio content (waveform, spectrogram-based decoding).

## Two paradigms, two creative mindsets

## A) Sequence generation (symbolic/token-based)

The model generates structured events (for example notes, durations, chords, or audio tokens).

**Strengths**

- Stronger high-level structure (form, motif repetition, harmonic logic)
- Easier editing after generation
- Better for arrangement exploration and compositional control

**Limits**

- Raw timbre realism is often weaker unless paired with a synthesis/render stage
- Expressive micro-details can feel mechanical without extra processing

## B) Raw audio generation

The model generates signal-level output directly or near-directly.

**Strengths**

- Rich texture and timbral nuance
- Strong realism for voice, ambience, and some musical contexts
- Great for fast concept “feel” and sonic mood

**Limits**

- Harder to surgically edit structure
- Long-range coherence can degrade over time
- Compute cost can be higher

## Creative rule of thumb

- Use **sequence-first** when composition/arrangement control matters most.
- Use **raw-audio-first** when timbre/atmosphere/texture matters most.
- In practice, many projects use a **hybrid pipeline**.

## Hybrid workflow example

1. Generate a rough musical structure (sequence approach).
2. Render/synthesize with selected instruments or model.
3. Add voice/ambience layers with raw-audio generation.
4. Curate, edit, and mix in DAW tools.

## Mini comparison rubric (for class)

When comparing outputs, rate each from 1–5:

- Structural coherence
- Sonic realism
- Emotional fit to brief
- Editability
- Time-to-good-result

Use this rubric to decide which paradigm fits your project constraints.
