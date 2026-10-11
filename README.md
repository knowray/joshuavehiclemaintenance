# Joshua Vehicle Maintenance Services — website

Static one-page site for GitHub Pages. No build step.

## Publish
1. Create a public repo (e.g. `joshuavehiclemaintenance`).
2. Upload `index.html` and `logo.jpg` to the repo root.
3. Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
4. Live in ~1 minute at `https://<username>.github.io/joshuavehiclemaintenance/`.

## Add shop photos later
Make an `img/` folder, add resized JPGs (~1200px wide, <300 KB), then uncomment the
`PHOTOS` block in `index.html` and update file names + alt text.

## Edit hours
Change both the table in the "Visit the shop" section **and** the `H` array in the script
(minutes after midnight, Sunday first) so the live open/closed badge stays correct.
Also update `openingHoursSpecification` in the JSON-LD block at the top.
