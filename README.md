# Uchiha Itachi — Vercel-ready static website

An animated, mobile-responsive Itachi showcase built with HTML, CSS, JavaScript, and local image-frame assets.

## Deploy to Vercel

1. Open https://vercel.com/new and sign in.
2. Choose **Import Git Repository**.
3. Select **Anandsinghsarkar/itachi**.
4. In Project Settings, keep **Framework Preset: Other**.
5. Leave **Build Command** and **Output Directory** empty (or use `./` as the output directory).
6. Click **Deploy**.

No environment variables, server, database, or build step are required.

## Project files

- `index.html` — page structure
- `style.css` — responsive styling and animations
- `main.js` — scroll, canvas, and pointer interactions
- `frames/main/` — 27 scroll-animation frames
- `frames/eyes/` — 51 eye-tracking frames
- `frames/storm.jpg` — background image
- `vercel.json` — static deployment and asset cache headers

## Notes

The animation loader is configured for the 27 main frames that are present in this repository. The eye animation uses all 51 eye frames. Keep the numbered image names unchanged when replacing assets.

This is a static front-end project. It does not need `package.json`, Node.js runtime functions, or a backend.
