# Relay AI Product Intro - Visual System

## Style Prompt

A precise, daylight technical product launch film for Relay AI, an AI workflow tool. The frame feels like a well-instrumented operating system: cool white space, crisp navy copy, blue signal paths, restrained cyan status lights, and clean product panels. Motion is deliberate and directional, emphasizing orchestration rather than spectacle.

## Brand Tokens

| Token | Value | Use |
| --- | --- | --- |
| Product name | Relay AI | Logo lockup and closing card |
| Headline | Move work from brief to done. | Opening statement |
| CTA | Build with Relay AI | Final action |
| Result metric | 3.4x faster delivery | Dashboard payoff |

## Colors

| Role | Color |
| --- | --- |
| Canvas | `#F4F8FC` |
| Panel | `#FCFEFF` |
| Primary text | `#10253D` |
| Secondary text | `#536D87` |
| Primary accent | `#0B61C9` |
| Signal cyan | `#39B9D6` |
| Success state | `#086A48` |
| Border / grid | `#D4E3F0` |

## Typography

- Display, interface, and data copy: `"IBM Plex Mono"`, confirmed by the HyperFrames font audit.
- The approved Space Grotesk / IBM Plex Sans candidates were replaced because this renderer cannot auto-supply either family.
- Headlines use heavy weight with tight tracking; status values use tabular numerals.

## Motion Language

- Four scenes over 15 seconds at `1920x1080`.
- Every scene introduces its content with entrance animation from a resolved static layout.
- Scenes 1 to 2 and 2 to 3 use directional push handoffs; scene 3 to 4 uses a restrained blur crossfade.
- The final card may fade down at the end; earlier scenes remain visually complete until their transition.

## Replaceable Content

- Product name, copy, CTA, workflow node labels, metric and narration are ordinary HTML text in `index.html`.
- Replace colors and type choices here first, then mirror changes in the CSS variables in `index.html`.
- Replace narration WAV files in `assets/audio/` while preserving their clip start times or retime the audio elements.

## What Not To Do

- Do not introduce dark neon or purple gradient styling.
- Do not add glitch effects, rapid cuts, or decorative motion that competes with the interface.
- Do not use generic stock footage; the UI flow is the product proof.
- Do not overcrowd screens with feature lists; keep one clear claim per scene.
