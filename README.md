# NEXORA — Free Tools by Zeus

This is a **static HTML website** designed to work directly on GitHub Pages. It does not require Node.js, Next.js, npm, a build step, or a framework deployment. This avoids the blank-page issue caused by uploading a Next.js source project to GitHub Pages without building and publishing it correctly.

## Publish on GitHub Pages

1. Download and extract this ZIP.
2. Open your GitHub repository.
3. Upload `index.html` and `README.md` directly into the repository's **root** (not inside an extra nested folder).
4. Commit the files.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select your main branch and `/(root)`, then Save.
7. Wait for GitHub Pages to finish deploying, then refresh the published website.

## Included free tools

- Weather explorer (Open-Meteo geocoding and forecast APIs)
- Currency converter (Frankfurter reference rates)
- Country explorer (REST Countries)
- QR code studio (public QR image service; internet required)
- Text toolkit
- JSON formatter/validator
- Password generator using browser crypto
- Quick notes stored in this browser's local storage

Public APIs require internet and can have downtime or rate limits. Currency rates are reference data, not guaranteed transaction rates. Do not put passwords or other secrets into QR codes. The quick-notes tool stores content locally in the current browser and should not be used for sensitive data on shared devices.

## Owner and support

- Owner: **Zeus**
- WhatsApp: **+234 906 676 0078** — https://wa.me/2349066760078
- Customer care: **ge5853987@gmail.com**

## Technical notes

This is plain HTML, CSS, and JavaScript, with no external JavaScript framework dependencies. It works as a static GitHub Pages site. A network connection is required for the live-data tools and QR generation. There are no paid tiers or premium gates.
