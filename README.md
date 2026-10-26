# LingoRoots — free prototype package

This package contains the interactive LingoRoots browser prototype plus basic Progressive Web App (PWA) files.

## What is included
- `index.html` — interactive prototype with language browsing, lesson demo, lesson test/retry flow, Kids Club mini activities, progress UI and subscription preview.
- `manifest.webmanifest` — installable-app metadata.
- `service-worker.js` — basic offline caching once hosted over HTTPS.

## Important limits
- This is a prototype, not a production app-store build.
- Sample pronunciation uses browser speech synthesis where available; it is not verified native-speaker audio.
- Speaking feedback and subscription checkout are demo-only.
- Progress is prototype-level and is not synced to an account or database.
- No API keys or paid services are required to try the prototype.

## Free way to publish a test version
A PWA must be hosted on HTTPS for installation/offline features to work reliably. One free route is GitHub Pages:
1. Create/sign in to a GitHub account.
2. Create a public repository named `lingoroots`.
3. Upload all three files from this folder to the repository root.
4. In repository Settings, open Pages and enable deployment from the `main` branch and `/ (root)`.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS address on your iPhone.
6. In Safari, tap Share → Add to Home Screen.

GitHub's interface may vary by device. If uploading files on an iPhone is awkward, the files can be uploaded later from any computer; no paid plan is required for a public GitHub Pages site.

## Before a real launch
Add a database and authentication, store-backed subscriptions, privacy/parental controls, reviewed lesson content, rights-cleared native audio, accessibility testing, and robust server-side enforcement of lesson test results.
