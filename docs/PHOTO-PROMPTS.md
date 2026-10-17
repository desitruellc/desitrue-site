# DesiTrue photo prompts

Prompts for the website's remaining photos, written for Microsoft Copilot (or any image tool). They match the look of the photo already on the site: Desirée's bright high-rise office with rose-gold accents.

## How to hand them back

1. Generate each image. If Copilot offers aspect ratios, pick the one listed; if not, pick the closest landscape or portrait option. The images get cropped to size afterwards.
2. Save the images into `incoming-photos/` at the top of this folder (it is ignored by git, so the originals never get published). Name each file after its slot, e.g. `svc-financial.png`.
3. Ask Claude: *"Place the photos in incoming-photos and check them."* Claude crops, resizes and compresses each one into `assets/img/`, then inspects every page at phone and desktop width before publishing.

## Rules for every prompt

Copilot images garble words and invent fake documents, so every prompt below already says:

- **No readable text, words, logos or brand names.** The real DesiTrue logo is already in the main photo.
- **No framed certificates or diplomas.** Credentials shown on the site should be real ones.
- **Same palette:** cream walls, dark walnut desk, rose-gold and brass accents, soft daylight from tall windows, a city view.

---

## 1. Service card: Money & bookkeeping

- **File:** `svc-financial` · **Shape:** landscape 3:2 · **Used on:** home page, first service card

```text
Professional photograph, overhead three-quarter view of a dark walnut executive desk in a bright high-rise office. A laptop showing a simple colourful bar chart, a calculator, neatly stacked printed financial reports with pie charts, a rose-gold pen, a brass desk lamp edge in frame, a glass of water. Soft natural daylight from floor-to-ceiling windows, cream wall in the background, rose-gold and brass accents. Calm, organized, trustworthy. No people, no readable text, no logos, no certificates. Landscape 3:2.
```

## 2. Service card: Administrative support

- **File:** `svc-admin` · **Shape:** landscape 3:2 · **Used on:** home page, second service card

```text
Professional close-up photograph of a woman's hands with a gold ring and a red blazer sleeve organizing a leather-bound planner beside a smartphone showing a calendar, on a dark walnut desk. A passport and a boarding pass tucked beside the planner suggest travel arrangements. Pastel sticky notes, a rose-gold pen. Soft daylight from tall windows, shallow depth of field, cream and rose-gold tones. Orderly and unhurried. No faces, no readable text, no logos. Landscape 3:2.
```

## 3. Service card: Creative & marketing

- **File:** `svc-creative` · **Shape:** landscape 3:2 · **Used on:** home page, third service card

```text
Professional photograph of a modern creative workspace on a dark walnut desk in a bright high-rise office: an open laptop showing a blog page layout with soft pastel photos, a smartphone displaying a social media grid, blush and rose-gold colour swatches, a notebook of sketched content ideas, a small potted plant. Soft natural light from floor-to-ceiling windows with a blurred city view. Airy, modern, warm. No people, no readable text, no real brand logos. Landscape 3:2.
```

## 4. Founder headshot

- **File:** `about-portrait` · **Shape:** portrait 4:5 · **Used on:** About page and the home page's "Meet the founder" section, replacing the second copy of the office photo

**Attach the existing office photo as a reference** so Copilot keeps her likeness. Then ask Desirée whether the result looks like her before it goes on the site.

```text
Using the attached photo as a reference for the same woman, create a professional, warm headshot of her: a Black woman with short curly copper-auburn hair, wearing a red blazer over a cream silk blouse, smiling naturally at the camera. Chest-up framing, standing by floor-to-ceiling windows in a bright modern office, softly blurred city view behind her, rose-gold and cream tones. Natural, true-to-life skin tones and features, approachable and confident. No text, no logos, no name plate. Portrait 4:5.
```

## 5. Link preview image

- **File:** `og-image` · **Shape:** wide 1.91:1 (1200 × 630) · **Used on:** the preview card shown when the site link is shared in texts or on social media

```text
Wide, elegant brand banner photograph: a bright modern high-rise office with a cream wall, a dark walnut desk with a brass lamp and a small vase of blush roses on the right third of the frame, soft daylight from floor-to-ceiling windows with a softly blurred city skyline. Large calm empty area of cream wall on the left two-thirds, where a logo will be placed later. Rose-gold and brass accents. No people, no text, no logos, no certificates. Very wide landscape, 1200 by 630.
```

---

## Optional extras

These have no spot on the site yet. If any of them turns out well, ask Claude to add a section for it.

- **Contact page:** Desirée on a video call at her desk, smiling, laptop facing her. Attach the reference photo. Landscape 3:2.
- **About page, "Who we help":** a small business owner and Desirée reviewing a laptop together across a desk, both smiling. Faces turned away from the camera, or attach the reference photo. Landscape 3:2.
