# Epeke Vuyisani — The Cosmic Digital Universe

An interactive, multi-world personal website: cosmic dreamcore, webcore textures, celestial symbolism, a red-thread motif, and a portrait-led Observatory whose body dissolves into stars and haze.

## Run locally

1. Install Node.js 20 or newer.
2. Open this project folder in a terminal.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL Vite prints.
5. Before deploying, run `npm run build`.

## Deploy to GitHub Pages (beginner-friendly)

1. Create or open the GitHub repository where you want the website to live.
2. Upload the **contents** of this folder (the `src`, `public`, `.github`, `index.html`, `package.json`, and lock file) to the repository root. Do not upload the ZIP itself as the only file.
3. Commit the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **GitHub Actions**.
6. Open the **Actions** tab and wait for **Deploy to GitHub Pages** to finish successfully.
7. Return to **Settings → Pages** and open the published URL.

The app uses `HashRouter` and relative asset URLs, so navigation works on a repository URL such as `https://USERNAME.github.io/REPOSITORY/` without server-side rewrite configuration.

## What is included

- Observatory home with portrait/cosmic-body composition, moving star field, hidden message, red thread, and five interactive world portals.
- Five separate worlds: Solar Coast, Moon Ocean, Angel Veil, Living Tree, and Overflow.
- Archive with selectable story, skills, and current-direction panels.
- Constellation of projects, Creator's World / UGC, Workshop / services, Social Orbits, and Invitation / contact pages.
- Local artwork in `public/assets/`, local CV PDF, favicon, responsive navigation, motion toggle, signal-disturbance effect, visit tracking, and accessible motion fallbacks.
- GitHub Actions deployment workflow and source audit.

## Update your content

- Edit `src/data.js` to change contact links, portfolio links, project listings, or skills.
- Replace artwork in `public/assets/worlds/` or `public/assets/portraits/` with your own optimized images, keeping the filenames the same if you do not also update `src/App.jsx`.
- Replace `public/cv.pdf` with your current CV PDF.
- Keep all assets inside the project; do not rely on private file paths or hotlinked image URLs.

## Notes

The visual system uses React, CSS, SVG, and Canvas for atmospheric interactions rather than requiring WebGL. This is intentional: the requested style is flat-but-alive, tactile, and surreal, and the site needs to remain practical on Android phones and static GitHub Pages hosting. See `SOURCE_AUDIT.md` for the source choices and trade-offs.
