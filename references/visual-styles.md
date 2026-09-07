# Visual style registry

Use a three-digit sequence: `001`, `002`, `003`, and so on. State the applied style number when delivering images. Add a new entry only when the user asks to retain a new style. Preserve older entries unless the user explicitly asks to replace or remove one.

## Style 001 — Retro Bold-Line Editorial Cartoon

**Status:** Default.

**Reference asset:** `../assets/style-001-reference.png`. Use it as a style reference for image generation when the tool accepts image references. It controls visual language only; never copy its traveler, buggy, road signs, flag, or scene composition unless the requested subject requires them.

### Defining traits

- Bold, irregular black ink outlines with a lively hand-drawn wobble.
- Simplified, mildly exaggerated characters with readable poses and a light humorous tone.
- Flat fills in a limited palette: coral red, deep forest green, cool gray, black, and white.
- Selective halftone dots and short hatch marks that recall vintage magazine or screen-print production.
- Large clean white areas, strong silhouettes, clear visual hierarchy, and restrained detail.
- Minimal shading; depth comes from overlap, line weight, gray blocks, hatching, and halftone texture.
- One editorial idea expressed as one coherent scene.
- Text appears only when indispensable to the physical scene; otherwise use none. Never place Chinese body copy in the image.

### Generation recipe

Include this block in every Style 001 brief, adapted only where the subject requires it:

```text
Style 001 — Retro Bold-Line Editorial Cartoon. Use the supplied reference for visual language only, not its subjects or composition. Bold irregular black ink outlines, lively hand-drawn wobble, flat limited color fills, simplified and slightly exaggerated characters, selective halftone dots and short hatch marks, crisp white background, vintage magazine editorial-cartoon feeling. Palette: coral red, deep forest green, cool gray, black, and white. Strong silhouette, ample white space, minimal shading. No photorealism, 3D rendering, painterly watercolor, soft pencil realism, glossy gradients, or dense background detail.
```

Retain the global Read & Teach constraints: exactly one generation call per image, one canvas, one scene, no Chinese body text, article page, screenshot, poster, infographic, long image, collage, panels, montage, contact sheet, or multiple variants.

