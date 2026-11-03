# Removalists4u landing page redesign — handoff notes

Open `index.html` in a browser (assets are in `./assets/`). Font: Barlow via Google Fonts (same as the live site).

## Placeholders to replace before launch
- **Partner logos** ("Brands we work with" marquee): dummy wordmarks. Swap each `.plogo` for a real `<img>`.
- **Numbers**: "480+ Google reviews", "12,000+ moves", "98% would recommend" — confirm or change (hero proof bar, Why section, Reviews, sticky bar).
- **Claims to confirm with the client**: "Transit protection / insured trucks", "No fuel, stairs or weekend surcharges", "Pay after the move, card or cash", "Floor protection / tool kit included", opening hours "7am – 8pm", email address.
- **Reviews**: copy taken from the live site; dates and move details ("Richmond → Hawthorn · 2 bed") are illustrative. Link "Read all reviews" to the Google profile.
- **Badges** are rebuilt in HTML/SVG (Google, ProductReview wordmark, 2022 winner ribbon, 2023/2024 seals) so they stay crisp. Replace with the official badge files from Google and ProductReview.com.au before launch. The "Vetted Movers", "Fully Insured" and "Australian Owned" seals are our own additions, confirm the claims.
- **Form**: `submit` is intercepted with a demo alert. Point it at the real endpoint.
- Truck illustrations are the client's own (`Small/Medium/Large_truck.png`, `van-blue.png`). The 12-tonne card reuses the Large truck scaled up; a dedicated XL image would be better.

## Not done
- Mobile layout is a basic single-column fallback only (desktop 1440 was the brief).

## Added in round 3 (human-touch elements, all placeholders to confirm)
- **Owner's note** ("A note from the team"): the name "Daniel M., Founder & Operations Manager" and the story are placeholders. Replace with the real owner's name, photo and words. Signature uses the Caveat Google Font.
- **Crew strip**: "Tom / Sam / Jay" with years of service are placeholders; use real crew first names and photos.
- **Track record timeline**: 2022 Awards Winner, 2023 and 2024 Service Awards are from the client's badge strip; the descriptions under each are generic and should be checked against the actual award category.
- Seals (hero strip, trust cards, footer, awards timeline) are HTML/SVG lookalikes; swap for official badge files when supplied. The stats row (4.8, 12,000+, 98%, 7 days) lives at the bottom of the navy "Why choose us" section.
