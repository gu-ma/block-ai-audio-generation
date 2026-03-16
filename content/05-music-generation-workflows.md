---
title: "05 — Music Generation Workflows"
draft: false
---

# 05 — Music Generation Workflows

Music generation is most effective when treated as an **iterative workflow**, not a one-shot prompt.

## Three practical generation modes

## 1) Prompt-to-music

Generate short pieces from textual briefs.

Best for:

- ideation sprints,
- mood exploration,
- quick soundtrack drafts.

## 2) Continuation/inpainting

Provide a reference clip and ask the model to continue or transform it.

Best for:

- extending loops,
- generating transitions,
- variation around a strong initial idea.

## 3) Style/reference-conditioned generation

Use stylistic references or descriptors to guide arrangement and sonic identity.

Best for:

- art direction consistency,
- genre studies,
- project-specific sound worlds.

## Prompt design template (music)

Use a layered prompt format:

1. **Function:** where this music will be used
2. **Emotion:** target feeling arc
3. **Style cues:** genre/instrumentation/era
4. **Structure:** intro-build-release, loopable, etc.
5. **Constraints:** BPM range, density, avoid vocals, duration

Example:

> “Create a 30-second loop for a reflective exploration game scene. Warm analog synths, soft pulse, sparse percussion, no vocals, low dynamic intensity, seamless loop ending.”

## Iteration loop for studio

1. Generate 3–5 candidates quickly.
2. Select top 1–2 using a listening rubric.
3. Refine prompts with specific deltas (“less dense drums”, “more harmonic movement”).
4. Export stems/versions if available.
5. Finalize in DAW with edits, EQ, transitions, and level balancing.

## Listening rubric (music)

- Fit to brief
- Emotional clarity
- Section coherence
- Sonic quality/artifacts
- Integration readiness (can it sit in your project mix?)

## Practical takeaway

Great results come from **direction and curation**, not just model choice. Prompt quality + iterative listening = creative control.
