# FormPilot AI PWA starter

This is an installable Progressive Web App (PWA) starter. It is a static app and does not require Python or a paid API.

## Important limitation
Browsers prevent a website from silently reading arbitrary Google Forms pages. This starter opens the form, then lets you paste questions into the app and prepare cautious editable draft answers. It does not automatically inspect or fill Google Forms. It never submits anything. True AI generation and browser autofill need a properly hosted backend or browser extension/automation layer.

## Easiest install path
The app must be hosted at an HTTPS URL before Android Chrome can install it. One free path is GitHub Pages:
1. Create/sign in to a GitHub account.
2. Create a new public repository named `formpilot-ai`.
3. Upload all files in this folder to the repository root.
4. In repository Settings -> Pages, choose deploy from the `main` branch and `/ (root)`, then Save.
5. Wait for the published URL shown on the Pages screen.
6. Open that HTTPS URL in Chrome on Android -> menu ⋮ -> Install app or Add to Home screen.
7. On Windows, open the same URL in Chrome/Edge and use the install icon or browser menu.

Do not publish private student data or form responses to GitHub. This repository should contain only the app files.

## Files
- index.html: app interface and answer drafting logic
- manifest.json: installable app metadata
- sw.js: basic offline cache
- icon-192.png and icon-512.png: app icons
- icon.svg: vector icon
