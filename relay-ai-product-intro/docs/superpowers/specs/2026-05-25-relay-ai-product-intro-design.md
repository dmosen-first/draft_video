# Relay AI 15-Second Product Intro

## Deliverable

Create a reusable HyperFrames product-promo template and rendered MP4 for a fictional AI workflow product named Relay AI. The composition is a 15-second, 1920x1080, English-language product introduction with English narration.

## Storyboard

| Time | Scene | On-screen content | Narration |
| --- | --- | --- | --- |
| `0.0-3.2s` | Brand opening | Relay AI mark, `Move work from brief to done.`, orchestration tag | Turn every request into a coordinated workflow. |
| `3.2-7.0s` | Routing | Prompt panel and three connected agent modules: Route, Tools, Approval | Relay AI routes tasks, tools, and approvals in one place. |
| `7.0-11.5s` | Execution | Progress dashboard, completed checks, `3.4x faster delivery` metric | So your team moves from brief to done, faster. |
| `11.5-15.0s` | CTA | Relay AI logo lockup and `Build with Relay AI` button | Relay AI. Workflows that move with you. |

## Production Decisions

- Use a cool light technical palette and modular UI mockups; no outside brand assets are required.
- Use `"IBM Plex Mono"` across display, interface, and data copy; the originally approved display candidates are not auto-supplied by the installed HyperFrames renderer.
- Use directional push transitions for workflow continuity and a blur crossfade for the closing brand reveal.
- Generate four separate narration clips with HyperFrames TTS voice `af_nova`, timed on a single audio track.
- Provide editable HTML source, Studio preview, and a rendered MP4.

## Acceptance Checks

- `hyperframes lint`, `validate`, and `inspect --samples 15` report no blocking composition defects.
- Animation map shows the intended scene entrances and three transitions without unintended motion gaps.
- Rendered output is approximately 15 seconds, 1920x1080, includes audible narration, and ends on the CTA.
