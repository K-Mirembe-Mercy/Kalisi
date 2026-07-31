# Ebenezer Miracle Center Church — Website (Flat Version)

A static, modern website for Ebenezer Miracle Center Church (Kalisizo Town Council, Uganda), built for GitHub Pages. No build step — plain HTML/CSS/JS. **All files sit at the root — no subfolders** — so they upload cleanly through GitHub's drag-and-drop file uploader.

## Publish on GitHub Pages
1. Go to your repo on GitHub.
2. Select **all files in this folder** (every `.html`, `style.css`, `main.js`, and every `.jpg`) and drag them all in at once via "Add file → Upload files." Selecting/dragging them together (not one at a time) is what matters — folders aren't required since there aren't any here.
3. Commit directly to `main`.
4. Go to **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Pages
- `index.html` — Home
- `about.html` — About the church
- `pastor.html` — Pastor Lubega William (bio + YouTube channel)
- `school.html` — The church's school ministry
- `building.html` — Old Church (worship tent) & New Church (sanctuary under construction)
- `ministries.html` — Services & ministries
- `gallery.html` — Filterable photo gallery with lightbox
- `watch.html` — Watch sermons on YouTube
- `donate.html` — Giving page — every button opens WhatsApp with Pastor Lubega William (+256 773 102 722)
- `contact.html` — Visit, map, and contact form

## Giving / WhatsApp
Give buttons link to `https://wa.me/256773102722`. To change the number, search-and-replace `256773102722` in `donate.html` and the footer of every page (international format, no `+`, no leading `0`).

## To customize later
- **Colors, fonts, spacing:** all in `style.css` (design tokens listed at the top).
- **Photos:** swap any `.jpg` file — keep the same filename, or update the matching `src=""` in the HTML.
- **Gallery:** add new `.gallery-item` blocks in `gallery.html`; set `data-category` to `worship`, `building`, or `school`.
- **Contact form:** opens the visitor's email client by default. To collect submissions instead, connect a service like Formspree.
- **Map:** `contact.html` embeds a Google Maps search for "Kalisizo Town Council, Uganda" — replace with your exact address for more precision.
