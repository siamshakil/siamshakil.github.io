# Shakil Islam — Portfolio Site

Jekyll-powered portfolio. Design is fixed in layouts/CSS — content lives in Markdown and YAML.

## One-time setup

1. **Rename this repo** to `<your-github-username>.github.io` for it to auto-publish at
   `https://<your-github-username>.github.io`
2. In repo **Settings → Pages → Source**, select **GitHub Actions** (the included workflow
   handles the rest)
3. Edit `_config.yml` — set `url`, your email, LinkedIn, GitHub links
4. Add your real CV PDF to `assets/cv-shakil.pdf` (match the filename or update `cv_path` in
   `_config.yml`)
5. Push to `main`. Site builds and deploys automatically in ~1 minute.

## Day-to-day: how to add content (this is the entire workflow)

### Add a blog post

Create a new file in `_posts/` named `YYYY-MM-DD-short-title.md`:

```markdown
---
title: "Your Post Title"
tags: [Tag1, Tag2]
excerpt: "One-line summary shown in the post list."
---

Your content here, in plain Markdown.
```

Commit and push. Done — it appears on `/writing/` and the homepage automatically, newest first.

### Add a project

Create a new file in `_projects/` (filename doesn't matter, just keep it lowercase-hyphenated):

```markdown
---
title: "Project Name"
year: 2025
status: "Ongoing"
tags: [Tag1, Tag2]
excerpt: "One-line summary shown in the project list."
---

Full project writeup in Markdown.
```

Commit and push. Appears on `/projects/` and the homepage (latest 4), sorted by year.

### Update your skills

Open `_data/skills.yml` — edit ratings (1–5) or add new skills/domains. No HTML touched.

### Update credentials

Open `_data/credentials.yml` — add/edit entries directly.

### Update bio, contact info, name, org

Open `_config.yml` under the `author:` block — every field there is wired into the homepage.

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`. Not required — you can also just push and check the live site
after the Action finishes (~1 min), but local preview is faster while drafting.

## What you should never need to touch again

`_layouts/`, `_includes/`, `assets/css/main.css`, `index.html`, `projects.html`, `writing.html`
— this is the design system. Only open these if you want to change how the site *looks*, not
to add content.
