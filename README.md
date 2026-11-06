# Gigi's Appalachia — investor microsite

The scrollytelling site behind **bit.ly/gigisforinvestors**, plus the research
publications page.

| File | What it is |
|---|---|
| `index.html` | The main one-page site |
| `publications.html` | Research & publications (served at `/publications/`) |
| `pubs/` | Hosted publication PDFs (see `pubs/README.md`) |
| `netlify.toml` | Netlify config (pretty URLs, headers) |

## How deploys work
Netlify watches the `main` branch. Any push to `main` goes live automatically —
there is no build step; the site deploys as-is.

## Making changes
Edit the HTML (or have Claude produce a new version), commit, push. For content
changes, the brand source of truth is the SOT (Brand & Messaging) and the Gigi's
Design System in the "Gigi's Custom Outreach" Claude project.
