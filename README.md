# Esha Nurani — Portfolio Website

A single-file, self-contained portfolio site (plain HTML/CSS/JS, no build step required).

## Run locally

Just open `index.html` in any modern browser, or serve it with a local server:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000

## Structure

- `index.html` — everything (markup, styles, and scripts) in one file.
  - Fonts are loaded from Google Fonts (Sora, IBM Plex Sans, IBM Plex Mono) via CDN link tags.
  - No external JS libraries — the network-graph hero animation, scroll reveals, and card tilt effect are all vanilla JS.
  - No images/assets required.

## Sections

1. Hero — name, title, positioning
2. About
3. Career Focus (target roles: NOC/Network Ops, Network Engineering, Cybersecurity, SOC/Security Monitoring, Cloud & Infrastructure, Digital Forensics)
4. Experience (timeline)
5. Featured Work
6. Skills
7. Education
8. Contact

## Customizing

- Update contact email/LinkedIn in the `#contact` section (currently placeholders: `your.email@example.com`, `linkedin.com/in/your-profile`).
- Colors and fonts are defined as CSS variables at the top of the `<style>` block in `:root`.
