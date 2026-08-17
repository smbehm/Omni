# OMNISCIENCE — Official Film Site

A single-page showcase site for the feature film **OMNISCIENCE**, submitted for the Future Vision XPRIZE 2026.

> An optimistic, technology-forward vision of humanity's future in which advanced AI learns the highest form of intelligence: LOVE.

**Main showcase:** https://youtu.be/heZjkVHYP_8

---

## Structure

```
.
├── index.html          # entire site — HTML, CSS, JS in one file
├── assets/
│   └── img/            # WebP imagery (~770 KB total)
├── .nojekyll           # tells GitHub Pages to serve files as-is
└── README.md
```

No build step, no dependencies, no framework. Open `index.html` in a browser and it runs.

## Sections

Hero · Film embed · Logline + stats · Synopsis · Three-act treatment (accordion) · The World / tone & visual style · Characters · Themes · Personal statement · Audience & production · Credits · Contact

## Deploy

### GitHub Pages
```bash
git init
git add .
git commit -m "OMNISCIENCE film site"
git branch -M main
git remote add origin git@github.com:USERNAME/REPO.git
git push -u origin main
```
Then: **Settings → Pages → Source: `main` / root**. Live at `https://USERNAME.github.io/REPO/`.

### Netlify / Vercel / Cloudflare Pages
Drag the folder in, or connect the repo. Build command: *none*. Publish directory: `/`.

### Custom domain
Add a `CNAME` file containing your domain (e.g. `omniscience.film`) at the repo root, then point a DNS `CNAME` record at `USERNAME.github.io`.

## Editing

- **Copy** — plain HTML, search for the section heading and edit in place.
- **Colors** — CSS custom properties in the `:root` block at the top of `index.html` (`--gold`, `--bg`, `--ink`, …).
- **Video** — replace the YouTube ID `heZjkVHYP_8` in the `<iframe src>` (and the two `youtu.be` links).
- **Images** — drop replacements into `assets/img/` keeping the same filenames, or update the `src` paths. Export WebP at ~1000–1200 px wide, quality 75–80.
- **Fonts** — Space Grotesk (display) + Inter (body), loaded from Google Fonts in `<head>`.

## Credits

Written by Arash Romaeo Jahroudi & Martin De Bokay
Produced by Arash Romaeo Jahroudi, Jeronimas Vysniauskas, Sean Behm
Contact: omnixprize@gmail.com

© OMNISCIENCE. All rights reserved.
