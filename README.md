# gxanesh.github.io

Personal academic portfolio website for **Ganesh Sapkota.**

**Live site:** [https://gxanesh.github.io](https://gxanesh.github.io)

---

## Structure

```
_pages/          # Site pages (About, Research, Publications, CV)
_config.yml      # Site-wide configuration (name, bio, links, theme)
_data/           # Navigation and UI text
_includes/       # HTML partials (header, footer, sidebar)
_layouts/        # Page layout templates
_sass/           # Stylesheets and themes
images/          # Profile photo, favicons
cv/              # CV PDF for download
assets/          # CSS, JS, fonts
```

---

## How to Use This Template

### 1. Fork or Clone

```bash
git clone https://github.com/gxanesh/gxanesh.github.io.git
cd gxanesh.github.io
```

### 2. Configure

Edit `_config.yml` to set your name, bio, email, social links, and theme:

```yaml
title: "Your Name"
author:
  name: "Your Name"
  bio: "Your tagline"
  email: "you@example.com"
  github: "yourusername"
  linkedin: "yourusername"
  googlescholar: "your-scholar-url"
site_theme: "mint"  # Options: default, air, sunrise, mint, dirt, contrast
```

### 3. Edit Pages

All pages live in `_pages/`:

- `about.md` — Homepage (permalink: `/`)
- `research.md` — Research details
- `publications.md` — Publication list
- `cv.md` — Full CV with PDF download link

### 4. Update Navigation

Edit `_data/navigation.yml` to add or remove nav links:

```yaml
main:
  - title: "About"
    url: /
  - title: "Research"
    url: /research/
  - title: "Publications"
    url: /publications/
  - title: "CV"
    url: /cv/
```

### 5. Add Profile Photo

Place your photo in `images/` and update `avatar` in `_config.yml`:

```yaml
author:
  avatar: "your-photo.jpg"
```

### 6. Add CV PDF

Place your CV PDF in `cv/` (e.g., `cv/Your_Name_CV.pdf`) and link it in `_pages/cv.md`.

### 7. Run Locally (Optional)

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` to preview.

### 8. Deploy

Push to the `main` branch — GitHub Pages will build and deploy automatically.

```bash
git add .
git commit -m "Update site"
git push origin main
```

---

## Credits

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, a fork of [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/).
