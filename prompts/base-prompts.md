# Base prompts

Rules: always paste the CHARACTER block + STYLE block + NEGATIVE block.
Scene block changes per post. Never edit the character block.

## CHARACTER (fixed — copy verbatim)

```
26-year-old Brazilian man, white with light tan skin, short dark-brown
textured hair with faded sides, light stubble, hazel-green eyes, confident
warm expression, muscular athletic build, broad shoulders. BOTH HANDS fully
tattooed: black circuit-board lines and geometric patterns running from the
knuckles across the backs of the hands, extending up the forearms.
```

## STYLE (fixed — copy verbatim)

```
semi-realistic anime style, clean linework, soft cel shading, detailed hands,
high-end anime key visual, eye-level camera, soft daylight with subtle cyan
rim light
```

## NEGATIVE (fixed)

```
photorealistic, 3d render, chibi, deformed hands, extra fingers, blurry,
watermark, text, logo, all-black outfit
```

## SCENES (pick one, keep palette: navy / white / cyan / gold)

**Coding:** `wearing navy hoodie with sleeves pushed up showing tattooed hands,
typing on laptop at a São Paulo café, morning light, white coffee cup`

**Gym:** `navy tank top, doing pull-ups in a modern gym, dramatic side light,
confident grin, tattooed hands gripping the bar`

**Street:** `navy bomber jacket over white tee, cyan sneakers, walking down
Avenida Paulista at golden hour, city bokeh behind`

**Beach:** `white linen shirt with rolled sleeves, gold watch, Copacabana
boardwalk, ocean breeze, relaxed smile`

**Talking head (video):** use your best photo as the input frame. HeyGen or
Hedra, script from content/calendar.md, voice: warm Brazilian male, 26.

## Face-swap / reference rule

Every new image: attach the approved base face from `assets/face/` as the
reference (Flux Kontext / IP-Adapter), THEN apply scene. Prompt-only
generation drifts — reference-locked generation stays Rafa.
