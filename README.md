# Exam Guru Hindi — starter Android-installable web app

## What's included
- Hindi + English language toggle
- Maths, Reasoning, GK, DSSSB/SSC sections
- Five sample questions per section with answer explanations
- Local test history and best score (saved in this browser)
- PWA manifest and service worker for installation/offline caching

## Important
This is a Progressive Web App (PWA), not a signed Android APK. It can be installed on Android from Chrome after it is hosted on an HTTPS website. A Play Store release requires a separate Android packaging/signing and developer-account process.

## Free publishing route
1. Create a free GitHub account at https://github.com/
2. Create a new public repository named `exam-guru-hindi`.
3. Upload all files and folders from this ZIP (keep the folder structure).
4. In the repository, open Settings → Pages.
5. Under Build and deployment, select Deploy from a branch → `main` → `/ (root)` → Save.
6. Wait for GitHub Pages to publish the site. Open the published HTTPS address on your Android phone in Chrome.
7. In Chrome, use menu (⋮) → Install app or Add to Home screen.

## Editing
Questions are in `index.html` inside the JavaScript `data` object. Keep each question's options and correct-answer index aligned. The correct-answer index starts at 0.

## Monetization later
Do not add ads until the app has useful original content and regular users. Ad networks have eligibility and policy requirements. Subscription/payment features also need a secure backend; do not collect payment details in this starter app.
