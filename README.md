# Nana's celestial fandom archive

A responsive static website inspired by the supplied AO3 CSS theme.

## Included pages
- `index.html` — hybrid landing page with an overview and section cards
- `about.html` — about page
- `fandoms.html` — fandom index
- `writing.html` — writing and WIP shelf
- `recommendations.html` — recommendation template
- `socials.html` — social link directory
- `style.css` — shared theme and responsive layout
- `script.js` — tiny optional enhancement
- `assets/sigil.svg` — favicon

## Before publishing
1. Edit `about.html`, `fandoms.html`, and `writing.html` so every description is exactly what you want to share.
2. In `socials.html`, replace each platform homepage in `href="..."` with your own profile URL. The links currently go to platform homepages, not personal profiles.
3. Replace the recommendation examples in `recommendations.html`.
4. The display/body fonts load from Google Fonts. If you prefer no external font requests, remove the `@import` line in `style.css`; system serif fallbacks will still work.

## Preview locally
Open `index.html` in a browser. No build step or package manager is required.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **public** repository named `nana` (or another name you prefer). For the simplest personal-site URL, name the repository `YOUR-USERNAME.github.io` instead.
2. Upload the contents of this folder to the repository root. Make sure `index.html` is at the root, not nested inside another folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then save.
6. Wait for the deployment status to appear in Settings → Pages. GitHub will show the published URL there.
7. After edits, commit/push the changed files; GitHub Pages will publish the update.

For a project repository named `nana`, the site URL usually has the form `https://YOUR-USERNAME.github.io/nana/`. For a user-site repository named `YOUR-USERNAME.github.io`, the URL is `https://YOUR-USERNAME.github.io/`.

## Notes
- This is a static site: it does not have a server-side guestbook or contact form.
- Do not put private information or private Discord invite links on a public site.
- All pages share `style.css`, so palette and layout changes can be made in one place.
