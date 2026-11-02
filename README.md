# AMEA Intelligent Systems

Website for AMEA Intelligent Systems, including the interactive HelloBand product demo.

Live website: https://www.ameaintelligent.com

## Preview locally

Run `python3 -m http.server 8000 --directory dist` and open http://localhost:8000

## Files

- `dist/index.html` — page content
- `dist/styles.css` — responsive styles and phone-to-bracelet animation
- `dist/app.js` — interactive demo and browser-local project brief form
- `dist/assets/` — branding and concept images

No build step is required. Serve the `dist` folder using any static web host.

## Demo limitations

HelloBand is a work-in-progress product concept. The demo does not place calls or contact a nurse. The enquiry form downloads a project brief locally and does not submit information to a server.

The live website is hosted separately. Uploading to this repository does not automatically redeploy it.
