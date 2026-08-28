# H-CORD Lab Hugo Website

This repository contains the official Hugo-based website for **H-CORD Lab — Human-Centered Robotics and Design Laboratory**.

中文名：人本机器人与智能设计实验室  
English Name: Human-Centered Robotics and Design Laboratory  
Abbreviation: H-CORD Lab

## Tech Stack

- Hugo static site generator
- Custom HTML templates
- Custom CSS, no npm required
- GitHub Actions deployment to GitHub Pages

## Local Preview

Install Hugo Extended, then run:

```bash
hugo server
```

Visit:

```text
http://localhost:1313
```

## Deployment

The site is automatically built and deployed by GitHub Actions when changes are pushed to the `main` branch.

In GitHub repository settings, use:

```text
Settings → Pages → Source → GitHub Actions
```

## Site Structure

```text
.
├── hugo.toml
├── content/
│   ├── research.md
│   ├── team.md
│   ├── outputs.md
│   ├── join.md
│   └── contact.md
├── layouts/
│   ├── index.html
│   ├── _default/
│   │   ├── baseof.html
│   │   └── single.html
│   └── partials/
│       ├── header.html
│       └── footer.html
├── static/
│   ├── assets/
│   │   ├── logo.svg
│   │   └── favicon.svg
│   └── css/
│       └── styles.css
└── .github/workflows/deploy.yml
```
