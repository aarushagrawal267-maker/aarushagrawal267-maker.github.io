# Penny to Billion website

Public website for the **Penny to Billion** YouTube channel, served by GitHub Pages at
https://aarushagrawal267-maker.github.io

| Page | Purpose |
|---|---|
| `index.html` | Homepage: what the channel teaches, schedule, accuracy promise, links to YouTube |
| `privacy.html` | Privacy policy for "Penny to Billion Uploader" (required for the Google OAuth consent screen and YouTube API audit) |
| `terms.html` | Terms of Service |
| `404.html` | Not-found page (GitHub Pages uses it automatically) |
| `styles.css`, `logo.png`, `favicon.png`, `og-image.jpg` | Shared style, logo, browser icon, link-preview image |

Plain HTML and CSS, no build step. To preview locally: `python3 -m http.server` in this folder, then open
http://localhost:8000. GitHub Pages publishes whatever is on the branch chosen under
**Settings > Pages** (normally `main`).

The video pipeline that makes the channel's videos lives in
[`money-channel`](https://github.com/aarushagrawal267-maker/money-channel); its `site/` folder keeps a copy of these pages.

License: the page code is MIT; the channel name, logo and text are (c) Penny to Billion, all rights reserved.
