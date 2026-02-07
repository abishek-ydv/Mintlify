# Mintlify (Front-end Clone)

This repository is a front-end-only clone of the Mintlify marketing website implemented with plain HTML and CSS.

**What this is**
- **Type:** Front-end clone (HTML + CSS only).
- **Notes:** No backend, no scripts, no build tools. Icons are provided by Font Awesome (CDN link added to `index.html`).

**Sections Recreated**
- **Navigation:** Top sticky navbar with logo and links.
- **Hero / Main Section:** Large headline, subtext, email input CTA, hero images, and a small feature bar.
- **Logos Grid:** Customer / partner logos section.
- **Feature Sections:** Several marketing blocks (section-2, section-3, section-4, section-5) reproducing layout and cards.
- **Footer:** Full footer with social icons, link lists, certificates area, system status chip, copyright, and the dark-mode toggle.

**Fonts Used**
Pulled (via Google Fonts imports in `CSS/main.css`) — the project imports multiple font families; primary ones used in styles are:
- Cascadia Code
- Fira Code
- Geist Mono
- Google Sans Code
- Google Sans Flex
- Source Code Pro
- Inter (used as the main UI font)

**Colors and CSS variables**
Primary variables (declared in `CSS/main.css` :root):
- **--text-color:** #ffffff (white)
- **--btn-background-color:** #ffffff (white)
- **--background-color:** #08090a (very dark)

Other notable colors used across the stylesheet:
- **Accent / green:** #13e299
- **Section background:** #151616
- **Light hover / subtle borders:** rgba(255,255,255,0.1) and rgba(255,255,255,0.2)

**Icons**
- Font Awesome is used for UI icons (e.g., `fa-solid fa-sun`, `fa-solid fa-moon`, `fa-solid fa-desktop`). The stylesheet link was added to `index.html` head:

  https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css

**Screenshots (placeholders)**
- I recommend adding screenshots of the final output to the repository to document results.
- Create a `screenshots/` folder and add images such as:
  - `screenshots/desktop.png`
  - `screenshots/mobile.png`

To include them here, add the images and then reference them in the README like:

![Desktop screenshot](screenshots/desktop.png)

(Replace the placeholder files with your actual captures.)

**Live link / Hosting**
- This repo does not include a hosted live demo. You can host on GitHub Pages or Netlify.
- Example GitHub Pages URL (replace `USERNAME` with your GitHub username):

  https://USERNAME.github.io/Mintlify/

- Quick publish steps for GitHub Pages:
  1. Commit and push the repository to GitHub under a repo named `Mintlify` (or any name).
  2. In the repository Settings → Pages, enable Pages from the `main` (or `gh-pages`) branch.
  3. After a few minutes your site will be available at `https://USERNAME.github.io/<repo-name>/`.

**How to run locally**
- Open `index.html` in your browser (double-click or `File > Open` in browser).
- Or serve locally (recommended) using a simple static server, for example with Python 3.x in the project root:

```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

**Why icons were not showing (fix applied)**
- Problem: `fa-*` icons were not loading because Font Awesome CDN stylesheet was missing.
- Fix: Font Awesome stylesheet link was added to the head of `index.html`.

**Files changed**
- `index.html` — added Font Awesome CDN stylesheet link in `<head>`.

**Notes / Next steps**
- Add screenshots to `screenshots/` and update the README image links.
- If you want, I can help deploy this to GitHub Pages and provide the final live URL. 

---

If you want me to add actual screenshots, say which pages/viewport sizes to capture and I will add instructions for taking and adding them, or you can drop the images into `screenshots/` and I'll embed them in the README for you.