# sethtilliss.com

Personal site. Static HTML and CSS — no build step, no dependencies, no JavaScript.

## Files

| | |
|---|---|
| `index.html` | The entire site, single page |
| `styles.css` | All styling. Custom properties at the top, dark mode via `prefers-color-scheme` |
| `profile.jpg` | Avatar |
| `speaking.jpeg` | Photo section image, cropped and zoomed in CSS rather than in the file |

## Local preview

```
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deploying

Pushes to `main` deploy automatically via Vercel.

DNS runs on Vercel (`ns1.vercel-dns.com`, `ns2.vercel-dns.com`). The domain is
still registered at Squarespace. `sethtilliss.com` redirects to `www`.
