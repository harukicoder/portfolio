# Alvaro Serrano — Portfolio Website

Minimalist single-page portfolio. Plain HTML + CSS, no build step.

---

## Local preview

Just open `index.html` in a browser. That's it.

Or run a tiny local server (better for testing relative paths):

```bash
cd "Portfolio_Website"
python3 -m http.server 8080
# then open http://localhost:8080
```

---

## Deploy to Netlify (free, ~2 minutes)

### Option A — Drag & drop (fastest)

1. Go to https://app.netlify.com/drop
2. Drag the `Portfolio_Website` folder onto the page
3. Done. Netlify gives you a URL like `dazzling-marigold-1234.netlify.app`
4. (Optional) In Site Settings → Domain management → change subdomain to `alvaroserrano.netlify.app`

### Option B — Git-connected (auto-redeploy on push)

1. Push this folder to a new GitHub repo (e.g. `alvaroserrano/portfolio`)
2. In Netlify: Add new site → Import existing project → connect repo
3. Build command: *(leave blank)*
4. Publish directory: *(leave as `/`)*
5. Deploy

---

## Screenshot checklist

You need 5 screenshots saved to `assets/screenshots/`:

| Filename | What to capture | How |
|---|---|---|
| `myfinefix.png` | Hero/landing of myfinefix.com | Open in Chrome at 1440×900, ⌘⇧4 + space then click window |
| `jobtrail.png` | Dashboard view with a few sample jobs in pipeline | Open the demo, save 2–3 jobs, screenshot the dashboard |
| `inkpath.png` | Library view (the most visual page) | Open `harukicoder.github.io/InkPath/`, screenshot the library |
| `teachertcf.png` | The voice tutor interface mid-conversation | Start a session, screenshot when transcript is visible |
| `iqiyi.png` | The iQIYI screenshot you already have (with triple subtitles) | Save your existing screenshot here |

**Tips:**
- Aim for **1600×1200 px** or larger (the cards are 4:3)
- Zoom Chrome to 110–125% before capturing for crisper text
- Save as `.png` (not jpg) to avoid compression artefacts on text
- File size: <500KB each. Compress at https://tinypng.com if needed

## What's next (optional polish)

- Add a `favicon.ico` to `assets/` (any 32×32 logo will do)
- Add a custom domain (~£10/year on Namecheap, then point DNS to Netlify)
- Add Plausible or Google Analytics if you want visitor stats
