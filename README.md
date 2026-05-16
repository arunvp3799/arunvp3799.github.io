# arunvp3799.github.io

Personal website of Arun Purohit — built with [Jekyll](https://jekyllrb.com/) + [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/).

Live at: **https://arunvp3799.github.io**

---

## Editing Content

| File | What to update |
|---|---|
| `_config.yml` | Bio, social links, LinkedIn/Twitter URLs |
| `_pages/about.md` | About me, experience, education, skills |
| `_pages/projects.md` | Projects and publications |
| `_pages/resume.md` | Full CV/resume |
| `_pages/blog.md` | Blog landing page |
| `_posts/` | Add new blog posts here |
| `assets/images/profile.jpg` | Your profile photo |
| `assets/Arun_Purohit_CV.pdf` | Your resume PDF |

## Still needs your info

Open `_config.yml` and update:
- `YOUR-LINKEDIN` → your LinkedIn profile slug
- `YOUR-TWITTER` → your Twitter/X handle (or delete that block)

## Adding a Blog Post

Create `_posts/YYYY-MM-DD-post-title.md`:

```markdown
---
title: "Your Post Title"
date: 2026-06-01
categories:
  - machine-learning
tags:
  - llms
excerpt: "One-line summary shown in the blog listing."
---

Your content here...
```

## Running Locally

```bash
gem install bundler
bundle install
bundle exec jekyll serve
# → http://localhost:4000
```

## Deploying

Push to `main` — GitHub Pages builds and deploys automatically.
