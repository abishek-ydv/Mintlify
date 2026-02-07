# Mintlify (Front-end Clone)

**Live Link :** https://abishek-ydv.github.io/Mintlify/ 

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

**Screenshots**

![Desktop screenshot](screenshots/desktop.png)
