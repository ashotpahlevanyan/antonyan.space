# antonyan.space

Personal CV / portfolio site for **Nerses Antonyan** — DevOps Engineer &amp; Infrastructure Consultant.

## Structure

- `index.html` — the entire site, self-contained (CSS, JS and the profile photo are inlined; no external requests). This is what GitHub Pages serves.
- `CNAME` — custom domain (`antonyan.space`) for GitHub Pages.
- `files/` — source assets (original CV PDF, profile photo).

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. **Settings → Pages** → *Deploy from a branch* → `main` / `/ (root)`.
3. Set the custom domain to `antonyan.space` and enable **Enforce HTTPS**.
4. DNS at the registrar:
   - Apex `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `www` `CNAME` → `<username>.github.io`

## Editing

- Portfolio project cards live in the `#portfolio` section of `index.html` — replace the placeholder copy, tech chips and add links.
- The page supports light/dark themes automatically and includes a print-to-PDF stylesheet.
