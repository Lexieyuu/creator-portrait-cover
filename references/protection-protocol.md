# Protection Protocol

## Identity Lock

Treat the source face as the identity anchor. Preserve face shape, facial structure, eyebrows, eyes, nose, mouth, age impression, hairstyle, hair color, hair length, hair direction, head angle, and orientation. Never replace the face, change age, beautify into a different person, or invent accessories.

## Expression / Head Pose Lock

Keep the source expression, gaze, head tilt, and camera-facing direction. Do not turn a candid expression into a smile, talking pose, or fashion pose unless the user explicitly requests it.

## Crop Lock

When the source shows a defined body range, preserve that range and its shoulder boundaries, occlusion relationships, visible hands, clothing, and held objects. Whole-person scaling and repositioning are allowed; adding missing internal body regions is not.

## Hands and held objects

Keep existing hands, fingers, gestures, and objects unchanged in count, identity, and relationship to the body. Do not generate hands when they are absent in Mode A or B. Avoid creating extra fingers, merged fingers, duplicated objects, or implausible grips.

## Body Completion

Only Mode C may add body content. Extend conservatively from the neck and shoulders into a limited upper torso, following head angle, gaze, neck direction, clothing evidence, perspective, and natural proportions. Do not add full arms, palms, complex gestures, waist-down anatomy, or a new pose by default.

## Foreground Dominance

Keep the person visually dominant, usually 70%–75% of frame height. Leave enough breathing room for a believable environment while preventing the background from becoming the subject.
