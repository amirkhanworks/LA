# Luminox Automation — Static Site (v5)

Plain HTML/CSS/JS. Push this whole folder to your GitHub repo and enable Pages.

## Files
- `index.html` — Home: consumer-focused, centered hero, Smart Home Solutions section, Why Choose Us (4 cards), Our Services (3 cards), Mobile App teaser, Final CTA
- `about.html` — About: your Vision/Mission quotes, Why Choose Us (3 cards), Meet the Team with real photos
- `services.html` — unchanged, still the full B2B engineering content
- `styles.css` — updated with new centered-layout styles for Home/About (Services' look is untouched)
- `script.js` — unchanged
- `assets/team/fahad.png`, `assets/team/saad.png`, `assets/team/amir.png` — the real team photos, referenced by `about.html`

## What changed this round
- Home and About rewritten around the consumer smart-home experience — warmer copy, centered layout, dropped the "IoT Engineers by Trade" B2B framing (that stays on Services)
- Vision/Mission on About updated to your exact quotes
- Real team photos wired in: Fahad Khan (Founder & CEO), Saad Khan (Founder & CPO), Amir Khan (Co-founder & CTO)
- "Request a Demo" is now the primary CTA throughout Home/About, in blue per your spec
- Added a Mobile App "Coming Soon" section
- Dropped from Home/About: the patent-pending case-study panel, CamelX/AgriTech teasers, and credibility stats (6+ years, GCC deployments, etc.) — all B2B material that was clashing with the consumer tone.

**Flagging again since it's easy to miss:** after this change, none of the site shows your track record (years in business, patent pending, GCC deployments) — it all moved to Services. Not a problem if that's what you want, just don't want it to vanish by accident. Say the word if you'd like a toned-down trust strip added back to Home or About.

## Still open
- **Smart Home Solutions image** (Home page): still a placeholder box. Pick one of the four I showed earlier, or send your own photo, and I'll wire in the real file.
- Contact form, real icon set, og:image — unchanged from before, still open, lower priority.

## Uploading to GitHub
Same as last time (Add file → Upload files, drag files in, Commit), with one addition: this time also drag in the whole `assets` folder so it lands at `assets/team/...` relative to the repo root — the team photos on About need that exact path. If your browser's drag-and-drop doesn't preserve folders, upload the 6 files at the root first, then open "Add file → Upload files" again and drag just the 3 photos in — GitHub will let you type `assets/team/` as the target path before confirming.

Pages is already turned on from last time, so it'll pick up these changes automatically once you commit.
