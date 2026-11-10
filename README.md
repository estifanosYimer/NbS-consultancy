# NbS+C website

Static website hosted on Vercel. No build step.

- `index.html`: the whole site (page, styles, scripts). All solution and tool texts are in the JSON block `id="content"` near the end.
- `land.json`: world outline for the global NbS map.
- `media/`: explainer videos and posters.
- `vercel.json`: redirects for old page addresses and caching for videos.
- `404.html`: "page not found" page.

## Update a text
Open `index.html` on GitHub → pencil icon → search (Ctrl+F) for the text → edit → Commit changes. Vercel publishes it within a minute.

## To fill in
- Contact email: search `hello@your-domain.eu`.
- Search for `ph"` to find every placeholder tag (team, photos, project summaries, durations).
