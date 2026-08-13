TRAVIS KIRK LOWRY — PRODUCTION SITE

Files:
- index.html
- style.css
- merch.html
- assets/hero.png

Homepage:
- Uses the exact approved hero artwork.
- Shortform, Longform, Newsletter, and Merch are clickable via invisible hotspots.
- $1M CHECKS AT PRE-SEED remains non-clickable.

Links:
- Shortform -> LinkedIn
- Longform -> Substack
- Newsletter -> Google Form
- Merch -> /merch.html

Deploy:
Upload/overwrite these files in the GitHub repo root.
Netlify should auto-deploy from the connected repo.


MOBILE FIX:
- Corrected the mobile poster container so its clickable hotspot layer stays
  aligned to the visible 2:3 artwork.
- Added explicit mobile touch handling for Shortform, Longform, Newsletter,
  and Merch.


DESKTOP GUTTER FIX:
- Added a subtle repeating paper-grain background sampled to match the approved hero.
- Added a small edge blend so the portrait poster no longer reads as a hard rectangle
  against clean white side gutters.
- Poster proportions and mobile link hit areas are unchanged.
