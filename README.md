# Geektime Code 2026

The public website for the Geektime Code 2026 conference (Tel Aviv, Nov 12, 2026).

Static site, no build step — open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Files
- `index.html` — landing page
- `speakers.html` — the confirmed speaker lineup
- `styles.css` — styling

## Speaker lineup

The cards on `speakers.html` live between the `<!-- speakers:start -->` and
`<!-- speakers:end -->` markers. Each confirmed speaker is one `<article class="speaker">`
block. New speakers are added by pull request once they've confirmed their title,
abstract, and bio.
