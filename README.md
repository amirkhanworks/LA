# Luminox Automation — Static Site (v6)

Plain HTML/CSS/JS, no dependencies beyond Google Fonts. All files sit flat at the repo root (matches what's actually live on GitHub Pages).

## Files
- `index.html`, `about.html`, `services.html`
- `styles.css`, `script.js`
- `fahad.png`, `saad.png`, `amir.png` — team photos

## What changed this round
- **Subtle brand-colored glow** added behind the Home and About hero sections (soft amber + blue radial gradients, very low opacity) — Services untouched, as before.
- **Footer**: simplified to "Mumbai, India" only; phone, email, and LinkedIn are now icon-only circular buttons (no text labels), on all three pages. "Get in Touch" column now shows phone + email icons instead of text links.
- **Team cards** (About): each person now has their personal LinkedIn icon-link below their name — Fahad, Saad, and Amir's actual profile URLs.
- All icons are hand-coded inline SVG (no icon-library dependency, renders consistently everywhere) — this also resolves the earlier "emoji icons render inconsistently" flag for the footer and team section specifically. The card icons elsewhere (Why Choose Us, Services, etc.) still use text/emoji symbols — say the word if you want those converted to SVG too.

## Still open
- **Smart Home Solutions image** (Home page): still a placeholder box, waiting on your pick from the four shown earlier, or your own photo.
- Track-record stats (years in business, patent, GCC deployments) — still only live on Services, dropped from Home/About per your last request. Still flagging in case that's not what you want long-term.
- Contact form and og:image — unchanged, still open, low priority.

## Uploading
Same as before: on GitHub, open each changed file, click the pencil (edit) icon, select all, paste in the new content, commit. Changed this round: `index.html`, `about.html`, `services.html`, `styles.css`. (`fahad.png`, `saad.png`, `amir.png`, `script.js` are unchanged, no need to re-upload those.)
