# Base prompts

Rules: always paste the CHARACTER block + STYLE block + NEGATIVE block.
Scene block changes per post. Never edit the character block.

## CHARACTER (fixed — copy verbatim)

```
23-year-old Brazilian woman, warm tan skin, long dark wavy hair,
glamorous makeup, full lips, playful mischievous expression with a hint
of a smile, curvy glamorous build. Freckles across the nose, small moles
on the cheek — keep them, they are identity markers.
```

## STYLE (fixed — copy verbatim)

```
ultra photorealistic photograph, 85mm portrait lens, shallow depth of field,
natural skin texture, anatomically correct hands with detailed fingers,
eye-level camera, golden-hour or soft glam studio lighting
```

## NEGATIVE (fixed)

```
anime, cartoon, illustration, 3d render, chibi, deformed hands, extra fingers,
blurry, watermark, text, logo, explicit nudity
```

## SCENES (pick one, keep palette: champagne gold / white / soft rose / black)

**Café:** `beige knit top, laptop with code on screen, São Paulo café table,
laughing mid-sentence, warm morning light, coffee cup`

**Rooftop:** `champagne-gold slip dress, São Paulo skyline at golden hour,
wind in hair, confident smile`

**Night out:** `black mini dress, city neon bokeh, confident walk toward
camera, night`

**Get ready:** `silk robe, makeup mirror with warm bulbs, rose tones,
playful "ai, gente" expression`

**Gym (comedy):** `matching workout set, struggling adorably with light
dumbbells, gym, bright daylight`

**Talking head (video):** use the locked face reference as the input frame.
Flow (Bia's character) or P-Video with the ElevenLabs voiceover.
Voice: Adriane — Brazilian female, warm, friendly.

## Face reference rule

Every new image: attach the locked master face
(`assets/face/media-generation-bia-face-option-a-0-648bdd73-e16b-405d-a268-524a361428d0.webp`)
as the reference, THEN apply scene. Prompt-only generation drifts —
reference-locked generation stays Bia. The 360 sheets in `assets/face/`
cover side and back angles.
