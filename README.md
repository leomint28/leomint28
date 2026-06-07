# Minteena Prajith — Personal Portfolio

> Live site: **[leomint28.github.io](https://leomint28.github.io)**  
> Replace `yourusername` with your actual GitHub username after deploying.

---

## About

Personal portfolio website for Minteena Prajith — final year Computer & Autonomous Systems Engineering student at the University of Wollongong in Dubai, specialising in IoT, embedded systems, and robotics.

Built with plain HTML and CSS. No frameworks, no build tools, no dependencies — just upload and it works.

---

## Features

- Responsive single-page layout
- Smooth scroll reveal animations
- 8 project cards with images
- Skills, Experience, and Education sections
- Contact form powered by [Formspree](https://formspree.io) — messages go directly to email inbox
- Security hardened with CSP, X-Frame-Options, Permissions-Policy, and referrer controls

---

## Repository Structure

```
yourusername.github.io/
├── index.html          # Main portfolio file (edit this)
├── README.md           # This file
└── images/
    ├── profile_pic.JPG
    ├── project1.jpeg
    ├── project2.png
    ├── project3.png
    ├── project4.jpeg
    ├── project5.jpeg
    ├── project6.jpeg
    ├── project7.png
    └── project8.png
```

---

## How to Update

### Edit text content
Open `index.html` directly on GitHub (click the file → pencil ✏️ icon) and update any section. Commit when done — the site rebuilds automatically within ~1 minute.

### Add or replace a project image
1. Go to the `images/` folder in the repo
2. Click **Add file → Upload files**
3. Upload your new image with the correct filename (e.g. `project1.jpeg`)
4. Commit — done

### Add a new project
Copy an existing project card block in `index.html` and update the number, title, description, image src, and stack tags.

### Update the contact form
The form uses Formspree endpoint `https://formspree.io/f/mzdwageo`. To change the destination email, log into [formspree.io](https://formspree.io) and update the form settings there — no code changes needed.

---

## Deployment (GitHub Pages)

1. Create a repo named `yourusername.github.io` (must match your GitHub username exactly)
2. Upload `index.html`, `README.md`, and the `images/` folder
3. Go to **Settings → Pages → Source: Deploy from branch → main / root**
4. Save — site goes live at `https://yourusername.github.io` within 1–2 minutes

---

## Security

The following client-side security headers are set via `<meta>` tags in `index.html`:

| Header | Purpose |
|---|---|
| `Content-Security-Policy` | Blocks scripts/styles from untrusted sources |
| `X-Frame-Options: DENY` | Prevents clickjacking via iframes |
| `X-Content-Type-Options: nosniff` | Stops MIME-type sniffing attacks |
| `Referrer-Policy` | Limits information leaked via referrer headers |
| `Permissions-Policy` | Disables camera, mic, geolocation, and other unused APIs |

HTTPS is enforced automatically by GitHub Pages.

---

## Tech Stack

- HTML5 & CSS3 (no frameworks)
- Google Fonts — DM Serif Display, DM Mono, Instrument Sans
- [Formspree](https://formspree.io) — contact form backend
- GitHub Pages — hosting

---

*© 2026 Minteena Prajith*