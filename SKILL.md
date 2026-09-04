---
name: creator-portrait-cover
description: "Create lifelike 3:4 creator portrait covers from people and/or environment images while preserving identity, expression, crop, and photographic realism."
---

# Creator Portrait Cover

Create a natural, close-range, creator-style portrait cover in a default 3:4 vertical format. The person is the primary subject and should feel photographed in a real environment—not pasted in, beautified into another person, or rendered as a studio/AI portrait.

## Operating workflow

1. Inspect every supplied image and classify the request into exactly one mode:
   - **Mode A — Environment Composite:** a person image and an environment image are both supplied.
   - **Mode B — Automatic Environment:** only a person image is supplied and it contains enough body information for the intended crop.
   - **Mode C — Body Completion:** the source is mainly a head/face, or the visible body information is insufficient for a coherent cover.
2. Read the relevant mode reference before generating or editing.
3. Apply the shared protection protocol in [references/protection-protocol.md](references/protection-protocol.md), then the photographic integration rules in [references/photographic-integration.md](references/photographic-integration.md).
4. Perform a final quality check using [references/quality-checklist.md](references/quality-checklist.md).

## Non-negotiable defaults

- Output aspect ratio: **3:4 vertical** unless the user specifies another ratio.
- Foreground dominance: the person should generally occupy about **70%–75% of the frame height**, adjusted only when the source crop or composition requires it.
- Preserve the person's identity, expression, head pose, visible body crop, hands, hand-held objects, clothing, and accessories.
- Keep the environment subordinate to the person and preserve it when the user supplied one.
- Prioritize candid, human, close-range creator energy: natural skin texture, believable asymmetry, ordinary light, and a lived-in setting.

## Mode routing

- Mode A: read [references/mode-a-environment-composite.md](references/mode-a-environment-composite.md).
- Mode B: read [references/mode-b-automatic-environment.md](references/mode-b-automatic-environment.md).
- Mode C: read [references/mode-c-body-completion.md](references/mode-c-body-completion.md).

Do not invent extra body areas merely to make the composition easier. If the source already has a clear crop, treat that crop as locked. Body generation is permitted only in Mode C and only for a conservative neck, shoulders, chest, or limited upper torso.
