# Happy Birthday, Tahreem! 🎀 — Website Guide

A one-page animated birthday website made for Tahreem Batool's 21st birthday, themed around her BS Fashion Design major.

## What's Inside

Just one file: **`index.html`**. All 19 of her photos are already embedded inside it, so the file is fully self-contained — no folders, no extra images, nothing else to manage.

## How to Open It

Double-click `index.html`, or right-click → **Open with** → any web browser (Chrome, Safari, Edge, Firefox). No internet connection is required except to load two Google Fonts on first open.

## How to Share It

- **WhatsApp / Email**: send the `index.html` file directly — it works the same on the receiving end.
- **Put it online** (optional, if you want a shareable link instead of a file):
  1. Go to [netlify.com/drop](https://app.netlify.com/drop)
  2. Drag `index.html` onto the page
  3. You'll get a live link in seconds — no account needed.

## What's on the Page

| Section | What it does |
|---|---|
| **Hero** | Name reveal, rising balloons, twinkling stars, confetti burst on load |
| **The Garment Tag** | Click the tag to flip it and reveal "Size: Fabulous, Age: 21" |
| **Birthday Message** | A written wish, with falling petals and fireworks that fire as you scroll into it |
| **Moments Worth Framing** | A photo grid — all 19 photos, sliding in as you scroll |
| **The Lookbook** | A real 3D flipbook — click "Next ›" / "‹ Prev" to turn the pages |
| **On The Runway** | A 3D carousel of all 19 photos — auto-rotates, or use the arrows/dots |
| **Blow Out The Candles** | Click the button to blow out the candles and make a wish |
| **Footer** | Closing sign-off |

A soft gold sparkle trail follows the cursor throughout the whole page.

## Customizing It

If you want to make changes yourself, open `index.html` in any text editor (Notepad, TextEdit, VS Code, etc.) and look for these spots:

- **The birthday message**: search for the section with `id="message"` — the wish text is inside a `<p class="script">` tag.
- **The name in the hero**: search for `Tahreem Batool` near the top of the file.
- **Colors**: near the very top of the file, inside `:root { ... }`, you'll find the color palette (`--blush`, `--lavender`, `--sky`, `--plum`, `--gold`). Change the hex codes there to shift the whole site's color scheme at once.
- **Photos**: since the photos are embedded as data directly in the code, swapping them isn't a simple drag-and-drop. If you'd like different or additional photos added later, just send them back and they can be re-embedded the same way.

## Notes

- Works best in a modern browser (Chrome, Safari, Edge, Firefox) — very old browsers may not render the 3D effects correctly.
- The file is about 1.1 MB because the photos are built into it — that's expected and won't affect how it runs.
- Best viewed on a phone or laptop screen with the sound off (no audio) — it's a purely visual experience.

---
Made with 💜 for Tahreem's 21st birthday.
