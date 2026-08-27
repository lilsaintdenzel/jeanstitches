# Jean Stitches Portfolio

A single-page portfolio site for **Jean Stitches** (Stitches by Jean), handmade
crochet made with love. Beanies, scrunchies, headbands, flower bracelets, mini
pouches and more, presented across six themed collections.

> Handmade with love · Local · Sustainable · Timeless

## What's inside

| Path | Description |
| --- | --- |
| `index.html` | The portfolio page (semantic HTML, no build step) |
| `assets/css/styles.css` | All styling: responsive, animated, brand palette |
| `assets/images/` | Brand poster, lookbook grid, and collection cards |

### Sections
1. **Hero**: brand promise and call to action
2. **Our Collection**: product categories
3. **The Lookbook**: full lookbook image + six themed collection cards
   (Soft Girl, Blue Skies, Earthy, Chocolate & Cream, Berry, Sunset)
4. **Why Choose Us**: the three brand values
5. **Our Story**: about the maker
6. **Get in Touch**: TikTok, Instagram, Facebook, phone

## Running it

It's a static site with no dependencies or build step. Open `index.html` directly,
or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Contact

- TikTok / Instagram / Facebook: **@jean_stitches**
- WhatsApp: **+233 53 464 1657** (`https://wa.me/233534641657`)

## Customising

- **Colours & fonts** live as CSS variables at the top of `assets/css/styles.css`.
- **Collection palettes** are set inline per card via `--c1`…`--c4` in `index.html`.
- Swap or add product photos in `assets/images/` and reference them in `index.html`.
