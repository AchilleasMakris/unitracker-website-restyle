# UniTracker — Atelier Zero image prompts (for ChatGPT / Gemini app)

Paste the **STYLE ANCHOR** first, then add one **SLOT** line. Generate,
download the PNG, and save it into `assets/` with the exact filename shown.
Re-themed from the open-design-landing prompt pack to UniTracker's academic
subject matter. Keep all 9 in the same family so the page stays coherent.

After you drop the PNGs in, tell me and I'll repoint those 9 slots from
`.svg` back to `.png` and crop them to the right aspect ratios.

---

## STYLE ANCHOR (always prepend)

> Sophisticated digital collage in a modern Swiss editorial / Bauhaus style.
> Warm off-white handmade-paper background with subtle grain, faint vertical
> folds, thin drafting lines and registration marks. Matte materials only —
> plaster, limestone, concrete, paper. Museum-like calm, soft diffused
> daylight, every plane in focus (no bokeh, no lens flare, no glitch, no
> neon, no glossy 3D render). Palette: warm ivory, stone beige, soft
> concrete grey, deep charcoal, ONE washed coral-red accent (#ed6f5c),
> occasional muted mustard. Include thin hairline circles, crosshairs, and
> ONE small numbered tag baked into the image. No text/words, no logos, no
> human faces looking at camera. Flat, printed-page feeling — not a photo.

---

## METHOD TILES — square, render 816×816, save as `assets/method-N.png`

- **`method-1.png`** (Capture): a magnifying glass resting over an open course
  syllabus sheet and a small folded campus map, single coral pen alongside.
- **`method-2.png`** (Organize): a paper calendar grid with a few small task
  cards pinned to it and one coral marker, hairline grid behind.
- **`method-3.png`** (Track): a clipboard checklist of class sessions with tick
  marks, plus one small dotted dial gauge, one coral check.
- **`method-4.png`** (Improve): ascending plaster steps forming a bar-chart,
  a thin coral arrow rising along them, one numbered tag.

## LAB CARDS — portrait, render 768×1024, save as `assets/lab-N.png`

- **`lab-1.png`** (Courses): a vertical stack of textbooks / course folders with
  small credit tags, plaster fragment behind.
- **`lab-2.png`** (Tasks): a tall checklist column with deadline tags and a
  coral pen, paper ground.
- **`lab-3.png`** (Calendar): a single tall month calendar leaf with a few
  marked dates, hairline registration marks.
- **`lab-4.png`** (Attendance): a column of present/absent tally marks beside a
  dotted circular gauge, one coral accent.
- **`lab-5.png`** (Notes): an open notebook with faint study pages and a small
  botanical sprig, restrained soft shadow.

---

### Tips
- ChatGPT: ask for "1:1" (method) or "portrait 3:4" (labs) explicitly.
- Gemini (Imagen): set aspect ratio 1:1 or 3:4 in the prompt.
- Keep the coral to ONE element per image — that's what makes the set read
  as Atelier Zero and not generic AI art.

---

## BRAND SLOTS (optional) — currently real UniTracker screenshots

These 7 slots already hold real images, so they render fine. Only generate
these if you'd rather have collage art than screenshots. Same STYLE ANCHOR.

### `hero.png` — square, render 1024×1024 (the big right-edge image)
> A surreal academic collage: a cropped classical plaster head beside an
> open architectural archway, a delicate tree growing through it, a small
> floating calendar grid and a thin rising coral line standing in for
> academic progress. One small human figure at the base for scale. The
> single most composed, gallery-grade plate on the page.

### Square slots — render 1024×1024
- **`about.png`**: a quiet desk vignette in plaster + paper — an open book,
  a small calendar, a coffee cup as concrete forms, one coral bookmark.
- **`capabilities.png`**: six small plaster tiles in a loose grid (one per
  feature), one tile coral, hairline connectors between them.
- **`testimonial.png`**: a single plaster student bust in profile (eyes not
  to camera) beside a small speech-mark cut from paper, one coral dot.
- **`cta.png`**: a plaster hand reaching toward a small glowing phone-shaped
  paper cutout, coral screen glow, registration marks around it.

### Portrait slots — render 768×1024
- **`work-1.png`**: a tall paper mockup of an app home screen rendered as a
  flat collage (cards, a calendar strip), not a real screenshot.
- **`work-2.png`**: a vertical stack of documentation pages / guide spreads
  with tabbed dividers, one coral tab.

> Note: if you generate `hero.png` / `work-1` / `work-2` as collage, they
> replace the screenshots. Keep the screenshots if you want the page to
> still show the actual product UI somewhere.
