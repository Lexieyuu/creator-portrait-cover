---
name: creator-portrait-cover
description: "Create lifelike 3:4 creator portrait covers from people and/or environment images while preserving identity, expression, crop, and photographic realism."
---

# Creator Portrait Cover

Create a natural, close-range, creator-style portrait cover in a default 3:4 vertical format. Use an image-editing/compositing workflow: protect the uploaded person and edit the environment around them. The person is the primary subject and should feel photographed in a real environment—not pasted in, beautified into another person, or regenerated as a studio/AI portrait.

## Background-Only Editing Contract

The uploaded person is locked source imagery. Do not use full-image regeneration. If masking or layer editing is available, place a protected mask over the entire visible person and edit only the environment/background. If masking is unavailable, do not invent a new person or complex background; preserve the source person and use the simplest believable environment adjustment.

The generated scene must be a clean portrait environment: no foreground horizontal surface, no desktop/tabletop/counter, no office-workspace arrangement, and no text or graphic copy. The environment supports the person through space, color, depth, and light only.

## Operating workflow

1. Inspect every supplied image and classify the request into exactly one mode:
   - **Mode A — Environment Composite:** a person image and an environment image are both supplied.
   - **Mode B — Automatic Environment:** only a person image is supplied and it contains enough body information for the intended crop.
   - **Mode C — Body Completion:** the source is mainly a head/face, or the visible body information is insufficient for a coherent cover.
2. Read the relevant mode reference before generating or editing.
3. Apply the shared protection protocol in [references/protection-protocol.md](references/protection-protocol.md), then the photographic integration rules in [references/photographic-integration.md](references/photographic-integration.md).
4. Apply the default visual language in [references/style-natural-talking-head.md](references/style-natural-talking-head.md), unless the user requests a different style.
5. Perform a final quality check using [references/quality-checklist.md](references/quality-checklist.md).

## Non-negotiable defaults

- Output aspect ratio: **3:4 vertical** unless the user specifies another ratio.
- Foreground dominance: the person should generally occupy about **75% of the frame height**. This is an approximate composition target only; never crop, stretch, reshape, or regenerate the person to force the percentage.
- Preserve the person's identity, expression, head pose, visible body crop, hands, hand-held objects, clothing, and accessories.
- **Source Person Preservation:** treat the uploaded person as a protected, immutable foreground layer, not as a loose reference. Move the exact uploaded person into the environment and integrate only its edges, perspective, scale, depth, color, and light. Never redraw, inpaint, beautify, reconstruct, or regenerate the face or body.
- **Text-Free Canvas:** the output contains no text, lettering, typography, title, slogan, caption, logo, label, handwritten note, badge, or decorative marks. Leave clean negative space for the user's later layout.
- Keep the environment subordinate to the person and preserve it when the user supplied one.
- **Desk-Free Scene:** do not add desks, tables, laptops, notebooks, keyboards, pens, mugs, desk lamps, office accessories, or workspace layouts as default props. The environment should support the person without becoming a desktop scene.
- Prioritize candid, human, close-range creator energy: natural skin texture, believable asymmetry, ordinary light, and a lived-in setting.
- Default visual language: natural talking-head cover with a chest-up or medium close-up portrait, shallow depth of field, soft indoor light, and a calm background that supports rather than competes with the person.

## Mode routing

- Mode A: read [references/mode-a-environment-composite.md](references/mode-a-environment-composite.md).
- Mode B: read [references/mode-b-automatic-environment.md](references/mode-b-automatic-environment.md).
- Mode C: read [references/mode-c-body-completion.md](references/mode-c-body-completion.md).

## Rule precedence

When instructions appear to compete, apply them in this order: (1) preserve the uploaded person exactly, (2) enforce the clean, text-free, desk-free background contract, (3) preserve and integrate the remaining supplied environment, (4) apply the default visual style. Environment changes should be limited to the requested cleanup; never solve an environment problem by regenerating or altering the person. The 75% framing target is always subordinate to source-person preservation.

Do not invent extra body areas merely to make the composition easier. If the source already has a clear crop, treat that crop as locked. Body generation is permitted only in Mode C and only for a conservative neck, shoulders, chest, or limited upper torso when the source is genuinely insufficient. If the source face and the generated result disagree, the source face always wins over compositional polish or a more conventionally attractive expression. When the user requests a desk-free scene, that preference overrides generic workspace suggestions and applies to both automatic background generation and environment cleanup.
