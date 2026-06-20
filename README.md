# Siam Shakil - Portfolio

Personal portfolio website built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Running locally

Preview the site on your machine before pushing changes.

### One-time setup

1. Install **Ruby + DevKit** (Windows): `choco install ruby -y`, then in a fresh terminal run `ridk install 3`.
   (Or download from [rubyinstaller.org](https://rubyinstaller.org/downloads/).)
2. Install the project's gems:
   ```powershell
   gem install bundler
   bundle install
   ```

### Start the dev server

From the project folder:

```powershell
bundle exec jekyll serve --livereload --force_polling
```

Then open **http://localhost:4000/**.

- Edit any file → Jekyll auto-rebuilds and the browser refreshes.
- Changes to `_config.yml` require a **server restart** (`Ctrl+C`, then rerun).
- Stop the server with `Ctrl+C`.

## Adding photos

Drop image files (`.jpg`, `.jpeg`, `.png`, `.webp`, `.gif`, `.avif`) into `assets/photos/`.
They appear automatically on the [Photos](photos.html) page - no config or file list to maintain.

## Project structure

| Path | Purpose |
|------|---------|
| `_config.yml` | Site config - name, role, links, collections |
| `index.html`, `projects.html`, `writing.html`, `photos.html` | Top-level pages |
| `_layouts/` | Page templates (default, post, project) |
| `_includes/` | Reusable fragments (head, nav, footer) |
| `_posts/` | Blog articles (`YYYY-MM-DD-title.md`) |
| `_projects/` | Project case studies |
| `_data/` | Structured data (skills, credentials) |
| `assets/` | CSS, photos, CV, images |

## Deployment

Pushing to `main` triggers the GitHub Actions workflow (`.github/workflows/jekyll.yml`),
which builds and publishes the site to GitHub Pages automatically.
