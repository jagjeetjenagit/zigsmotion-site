# ZigsMotion — image slots & generation prompts

Every image the site expects is listed below. **Generate it, name it exactly as
the filename says, and drop it in this folder (`public/media/`).** The page picks
it up on the next reload.

Until a file exists the slot renders an empty-frame placeholder built from the
design system's palette — nothing breaks, nothing shows a broken-image icon,
so you can add them one at a time.

> **These prompts are tuned for the "Midnight" palette** — blue-black canvas,
> ice-blue accent, indigo second light. Every prompt below is cool-toned on
> purpose. Warm/orange images will fight the UI badly.

## House style (apply to every prompt)

To keep the site feeling like one film rather than a stock-photo bin, append
this to whatever you generate:

> cool ice-blue key light with a deep indigo counter-light, near-black
> shadows, fine 35mm film grain, slight halation on highlights, desaturated
> cool midtones, cinematic blue-steel colour grade, no warm tones, no orange,
> no text, no watermark, no logo, no UI

**Global rules**
- Dark overall. The site is a near-black blue canvas (`#07090F`); bright, airy
  images will fight it.
- **Cool only.** No golden hour, no tungsten, no ember. If a scene needs a
  second colour, reach for indigo or violet, never amber.
- Leave the **left third** relatively empty on wide plates — headlines sit there.
- No readable text anywhere in the image.
- Export as **JPEG, quality ~82**, sRGB. Keep each file under ~400 KB.

---

## 1 · Hero plate — `hero-plate.jpg`
**21:9 · 2400×1030 · wide, atmospheric, mostly dark**
Shown behind the headline at 34% opacity, so it should read as texture and
mood rather than a subject you need to see clearly.

> A lone figure in a long coat stands at the edge of a rain-slick rooftop at
> deep blue hour, the sprawling city far below and out of focus in cold cyan
> and indigo, steam rising from vents lit blue, volumetric light rays cutting
> through drizzle, cool anamorphic lens flare, shot on ARRI Alexa with a 40mm
> anamorphic lens, extreme negative space on the left, subject positioned
> right of centre

---

## 2 · Auth side panel — `auth-plate.jpg`
**3:4 · 1200×1600 · portrait**
Fills the left half of the login / signup screen.

> Anime-styled protagonist waiting alone on an empty suburban train platform
> at deep blue hour, cold fluorescent platform lights, long shadows across wet
> concrete, snow drifting, distant mountains in cool haze, cel-shaded with
> painterly background, cyan key against deep indigo shade, quiet and
> cinematic, Makoto Shinkai composition

---

## 3 · CTA band — `cta-plate.jpg`
**21:9 · 2400×1030 · very dark**
Sits behind the final call-to-action at 50% opacity.

> Motes of cold blue light drifting slowly through a dark forest clearing at
> night, a single distant lantern out of focus glowing pale cyan, deep blacks,
> shallow depth of field, bokeh sparks, almost abstract, extremely moody,
> mostly negative space

---

## 4 · Style thumbnails (8 files)
**1:1 · 600×600 each**
These are the swatches in the Studio's "Choose a look" row and the cards in the
landing page's Styles section. Each must be *instantly* readable as its style
at thumbnail size — pick a bold, simple subject and let the treatment do the
talking.

| File | Prompt |
|---|---|
| `style-anime.jpg` | Close-up of an anime girl with wind-blown hair against a vivid twilight sky of cyan and deep indigo, cel-shaded, clean confident line art, expressive eyes, cool saturated palette, dramatic cyan rim lighting, hand-painted cloud background |
| `style-anime-noir.jpg` | Anime detective in a trench coat under a flickering blue neon sign in heavy night rain, hard chiaroscuro shadows, cyan neon bloom on wet asphalt, muted teal and steel blue, cinematic 2.39:1 crop, moody and quiet |
| `style-3d.jpg` | Charming stylised 3D animated character — a small round robot with big expressive eyes — sitting in a workshop lit by cool monitor glow, subsurface scattering, soft global illumination, physically based rendering, shallow depth of field, feature-animation quality, cool blue key |
| `style-vfx.jpg` | Photoreal VFX shot: a glowing ice-blue energy portal tearing open above a desert highway at night, crackling electric arcs, volumetric god rays, cool anamorphic flare, live-action plate quality, blue-steel colour grade |
| `style-cinematic.jpg` | Cinematic 35mm film still of a traveller silhouetted in a doorway of cold light, dust motes in the air, shallow focus, natural film grain, blue-steel grade, anamorphic bokeh |
| `style-product.jpg` | High-end product photograph of a brushed titanium dive watch on wet black slate, seamless dark backdrop, softbox key with hard cyan rim light, glossy reflections, macro detail, commercial advertising quality |
| `style-portrait.jpg` | Editorial portrait of an older craftsperson, 85mm lens, creamy bokeh, cool north-facing window light with subtle fill, natural skin texture, muted cool film palette, magazine cover quality |
| `style-retro.jpg` | 1980s VHS aesthetic: a synthwave car driving a neon grid horizon, chromatic aberration, scanlines, tape tracking noise, oversaturated cyan and electric blue, CRT phosphor glow |

---

## 5 · Showreel (10 files)
Three of these overlap in the hero collage; the rest form the film strip below
it and reappear in the "how it works" section. **Aspect ratios differ — match
them**, the layout depends on it.

| File | Ratio · px | Prompt |
|---|---|---|
| `reel-anime-city.jpg` | **9:16** · 900×1600 | Anime girl standing on a rooftop railing at deep dusk, wind in her hair, vast cool city lights blurred below, cel-shaded with painterly background, cyan and indigo palette, vertical composition |
| `reel-3d-robot.jpg` | **4:5** · 1000×1250 | A small stylised 3D repair robot waking up in a dim workshop lit by cool blue monitor glow, dust in the light beams, subsurface scattering, soft global illumination, feature-animation character design |
| `reel-vfx-dragon.jpg` | **16:9** · 1600×900 | Photoreal dragon banking low over a misty coastal fishing village at cold dawn, live-action plate, heavy blue atmosphere, volumetric light, motion blur on the wings, cool anamorphic flare |
| `reel-cine-desert.jpg` | **4:5** · 1000×1250 | Lone traveller crossing vast sand dunes in pre-dawn blue light, tiny in frame, long shadow, 35mm film still, natural grain, cold indigo sky, desaturated cool sand |
| `reel-product-watch.jpg` | **1:1** · 1000×1000 | Brushed titanium dive watch on wet slate, studio softbox key with hard cyan rim light, water droplets, glossy reflection, seamless dark backdrop, macro commercial photography |
| `reel-portrait-astro.jpg` | **4:5** · 1000×1250 | Astronaut with helmet off resting against a capsule wall, tired eyes, cool blue light from the porthole, natural skin texture, muted cool cinematic palette, editorial portrait |
| `reel-anime-mecha.jpg` | **16:9** · 1600×900 | Anime mecha powering down in a flooded hangar, steam rising from vents, hard shadows, single overhead work light, deep blues with one cyan warning lamp, cinematic wide shot |
| `reel-vfx-portal.jpg` | **9:16** · 900×1600 | A crackling portal tearing open above a deserted desert highway at night, electric arcs, sand lifting, photoreal VFX on a live-action plate, cool cobalt core with pale ice-blue spill, vertical composition |
| `reel-3d-diorama.jpg` | **1:1** · 1000×1000 | Tiny floating island diorama with a waterfall spilling into cloud, miniature house and one tree, stylised 3D render, tilt-shift, soft global illumination, cool twilight key |
| `reel-cine-noir.jpg` | **16:9** · 1600×900 | Detective seated under a single hanging bulb in a dark 1953 office, cigarette smoke curling through the beam, venetian-blind shadows, high-contrast film noir, cold moonlight blue against deep black |

---

## Optional: use video instead of stills

Any `reel-*` slot will also accept a short silent loop. Save it as `.mp4`
(H.264, 3–6 s, no audio, under ~2 MB) and change that entry's `src` in
`src/lib/showcase.js` from `.jpg` to `.mp4` — the component handles both.

---

## Checklist

- [ ] `hero-plate.jpg` (21:9)
- [ ] `auth-plate.jpg` (3:4)
- [ ] `cta-plate.jpg` (21:9)
- [ ] 8 × `style-*.jpg` (1:1)
- [ ] 10 × `reel-*.jpg` (ratios per table)
