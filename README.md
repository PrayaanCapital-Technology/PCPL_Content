# PCPL_Content — Prayaan Capital Content Repository

Content-only repo for the Prayaan Capital website. No code lives here.

## Structure
- `global/` — sitemap, brand, navbar, footer, SEO defaults
- `pages/`  — one JSON per page (29 pages)
- `assets/` — images, PDFs, documents

## Branches
| Branch        | Purpose                                        |
|---------------|------------------------------------------------|
| `main`        | Live production content                        |
| `development` | Draft content — preview via `?preview=true`    |

## Editing
1. Edit JSON on `development` branch
2. Preview at `https://prayaancapital.org?preview=true`
3. PR: `development` → `main`
4. Merge → site updates in ~60 seconds

> ⚠️  RBI compliance pages require Compliance Officer sign-off before merging to main.
