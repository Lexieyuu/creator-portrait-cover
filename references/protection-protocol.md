# Protection Protocol

## Source Person Preservation

The uploaded person is the source of truth. Treat the full visible person—face, hair, clothing, pose, hands, accessories, and crop—as an almost immutable foreground layer. The preferred operation is to isolate the existing person, move and scale that complete layer into the environment, then integrate its edges, perspective, depth, color, and light. Do not regenerate a replacement person, redraw facial features, change the body silhouette, alter clothing, or invent a more polished pose. Any change to the person must be limited to the minimum technical adjustment needed for believable integration.

## Identity Lock

Treat the source face as the identity anchor. Preserve face shape, facial structure, eyebrows, eyes, nose, mouth, age impression, hairstyle, hair color, hair length, hair direction, head angle, and orientation. Never replace the face, change age, beautify into a different person, or invent accessories.

## Expression / Head Pose Lock

Keep the source expression, gaze, head tilt, mouth shape, eye openness, eyebrow position, cheek tension, and camera-facing direction. Treat the original face crop as the highest-fidelity region of the image and preserve it as closely as possible. Do not turn a neutral look into a smile, pout, talking pose, softened gaze, or fashion pose. Do not alter the emotional temperature merely to make the composite feel friendlier or more polished. If the generated body or lighting conflicts with the face, correct the body/lighting instead of changing the face.

## Text-Free Canvas

The final image must contain no text or graphic copy unless the user explicitly asks to preserve specific source text. Do not add titles, slogans, captions, subtitles, labels, logos, watermarks, handwritten words, alphabetic characters, Chinese characters, numbers, icons pretending to be copy, brush lettering, underlines, arrows, stickers, or decorative text-like marks. Do not place typography in the foreground, background, on props, on walls, or over empty space. Remove incidental source writing when possible and preserve intentional clean negative space so the user can add text later.

Text-Free Canvas takes precedence over Environment Lock for incidental writing: if the user wants a clean canvas, erase, crop, blur, or simplify source text while preserving the surrounding environment. Never invent new readable or pseudo-readable copy to make the scene feel designed.

## Crop Lock

When the source shows a defined body range, preserve that range and its shoulder boundaries, occlusion relationships, visible hands, clothing, and held objects. Whole-person scaling and repositioning are allowed; adding missing internal body regions is not.

## Environment Lock

In Mode A, the supplied environment is the spatial source of truth. Preserve its room geometry, windows, doors, non-text visual elements, color relationships, and overall composition unless the user asks for a change. The Desk-Free Scene rule may remove or replace desks, tables, laptops, notebooks, keyboards, and other workspace elements; the Text-Free Canvas rule may remove incidental writing. Improve integration through scale, perspective, occlusion, and light—not by redesigning the scene or covering it with graphic copy.

## Hands and held objects

Keep existing hands, fingers, gestures, and objects unchanged in count, identity, and relationship to the body. Do not generate hands when they are absent in Mode A or B. Avoid creating extra fingers, merged fingers, duplicated objects, or implausible grips.

## Body Completion

Only Mode C may add body content. Extend conservatively from the neck and shoulders into a limited upper torso, following head angle, gaze, neck direction, clothing evidence, perspective, and natural proportions. Do not add full arms, palms, complex gestures, waist-down anatomy, or a new pose by default.

## Foreground Dominance

Keep the person visually dominant, usually about 75% of frame height. Leave enough breathing room for a believable environment while preventing the background from becoming the subject.
