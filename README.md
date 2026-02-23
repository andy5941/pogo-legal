# POGO – Legal Pages

This repository hosts the **Privacy Policy** and **Terms of Use** for the [POGO](https://apps.apple.com/app/pogo) vertical jump training app. These pages are linked from the app and from App Store Connect.

## Contents

| Page | File | Purpose |
|------|------|--------|
| Privacy Policy | [privacy.html](privacy.html) | How we collect, use, and protect your data |
| Terms of Use | [terms.html](terms.html) | Rules and disclaimers for using the app |

## Live URLs (GitHub Pages)

After **Settings → Pages** is set to deploy from the `main` branch (root):

- **Privacy:** https://andy5941.github.io/pogo-legal/privacy.html
- **Terms:** https://andy5941.github.io/pogo-legal/terms.html

Use these URLs in the app’s `.env` (`EXPO_PUBLIC_PRIVACY_POLICY_URL`, `EXPO_PUBLIC_TERMS_URL`) and in App Store Connect.

## Updating the pages

1. Edit `privacy.html` or `terms.html` in this repo.
2. Replace **support@yourdomain.com** with your real contact email if you haven’t already.
3. Commit and push; GitHub Pages will update within a few minutes.

No build step required—plain HTML only.
