# Mode A — Environment Composite

Use when both a person image and an environment image are provided.

## Rules

- The environment image is the spatial and compositional baseline: do not redesign it or casually recrop it. Remove only the desk/workspace elements and incidental text prohibited by the active Desk-Free Scene and Text-Free Canvas rules.
- The person image controls identity, expression, head pose, posture, visible body range, clothing, hands, and held objects.
- Treat the uploaded person as an immutable finished foreground layer. Preserve the person's crop, face, expression, hair, clothes, pose, hands, and silhouette; move and scale the complete exact person layer as needed, without expanding, redrawing, inpainting, or regenerating the body internally.
- Match camera perspective, apparent lens distance, scale, depth of field, edge occlusion, contact with surfaces, and environmental depth.
- Apply lighting integration: direction, softness, color temperature, contrast, shadow density, and reflected color must agree with the environment.
- Keep the person near and conversational, with foreground dominance around 75% of frame height when compatible with the source.

## Failure conditions to avoid

Pasted cutout edges, haloing, mismatched sharpness, floating feet or shoulders, impossible scale, studio lighting in a lived-in scene, background replacement, face changes, person regeneration, accidental body completion, foreground desks, tabletops, or workspace props.
