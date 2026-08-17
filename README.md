# sethtilliss.com

Personal site — one page of static HTML and CSS. No build step, no dependencies,
no JavaScript.

## Files

- `index.html` — the whole site
- `styles.css` — all styling; custom properties at the top, dark mode via `prefers-color-scheme`
- `profile.jpg` — avatar
- `speaking.jpeg` — photo section; the crop and zoom are done in CSS, not baked into the file

## Local preview

```bash
python3 -m http.server 8080
```

## Deploying

Pushes to `main` deploy automatically on Vercel.

Vercel also runs DNS (`ns1.vercel-dns.com`, `ns2.vercel-dns.com`). The domain is
registered at Squarespace. The apex redirects to `www`.
