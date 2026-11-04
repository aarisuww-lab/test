# Vietnam – The Hidden Charm
Static site: HTML, CSS and vanilla JS. No build step, no backend.

## Run locally
`python3 -m http.server 8000` in this folder, then open http://localhost:8000.
(Opening index.html directly also works.)

## Deploy
**GitHub Pages:** push to a repo, Settings → Pages → Deploy from branch `main` / root. GitHub Pages sends no X-Frame-Options header, so it embeds in Google Sites.
**Netlify:** drag the folder onto app.netlify.com/drop. The included `_headers` file allows iframe embedding.

## Embed in Google Sites
Insert → Embed → By URL → paste your site URL → Insert. Resize the block to full width and tall height; use a Full-width section.
Navigation links work inside the frame. The Google Maps links open in a new tab.

## Contribution form
Currently shows a thank-you message only. To collect real data, create a Google Form, then either embed it or point the form at its `formResponse` URL.

## Images (ACTION NEEDED)
Images load from Wikimedia Commons via `Special:FilePath/<filename>`; filenames are in `script.js` (DEST, HER, FOOD) and `index.html`. They were written without internet access and **not verified**. Open each page, replace any filename that fails (a gradient card with the place name shows instead of a broken image), and for the final version download optimized copies into `assets/images/`.
Credit each file's author and licence from its Commons page.
