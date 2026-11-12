# The Family Thanksgiving Lookbook

A single-page site built around the Ralph Lauren Fall 2026 color palette for family Thanksgiving photos.

## What's included

- Overview section (placeholder for your generated lookbook image)
- The Fall 2026 Palette: all 20 colors grouped into 4 families, with exact hex codes
- The Lookbook: each color lists Baby & Toddler / Kids & Teens / Adults, each with
  - a **Ralph Lauren** designer pick
  - a **cheaper dupe** (Uniqlo, H&M, Gap, Amazon, or Target)
- Styling tips for coordinated family photos

## Publishing on GitHub Pages

1. Create a new repo (or use the one you'll send).
2. Copy `index.html` into the repo root (or a folder if you're using a subfolder).
3. Add your generated images:
   - `images/lookbook-hero.jpg` — your generated lookbook image
   - `images/palette-chart.jpg` — your generated color palette chart
4. Push, then enable GitHub Pages (Settings → Pages → deploy from branch, main).
5. Your site will be live at `https://<username>.github.io/<repo>/`.

If you skip adding the images, the site still works — it shows a colorful palette backdrop with a note about where to drop the image.

## Editing

To change a color's shopping links or queries, edit the `COLORS` list in
`generate_site.py` (in this folder) and re-run `python3 generate_site.py`.
