# PinYourBite website

Local working copy of https://github.com/oklinappsupport/pinyourbite-privacy.git.
The original privacy policy is preserved unchanged at `docs/privacy.html`.

## Preview

Open `docs/index.html` in a browser. This is a static, responsive site with local assets, system fonts, no JavaScript, no analytics, and no external font requests.

## Publish for AdMob

The existing project repository can host the homepage, but its URL would be `/pinyourbite-privacy/`. AdMob needs `/app-ads.txt` at the hostname root.

1. Create a public repository named `oklinappsupport.github.io` in the `oklinappsupport` account.
2. Upload the **contents of `docs/`** to that repository's root (including `assets/`, `privacy.html`, `styles.css`, `index.html`, and `app-ads.txt`).
3. Enable GitHub Pages from the main branch, root folder.
4. Verify https://oklinappsupport.github.io/ and https://oklinappsupport.github.io/app-ads.txt load publicly.
5. Set the Google Play developer website to https://oklinappsupport.github.io/ and publish that listing update, then ask AdMob to check again.

Keep the existing privacy repository live so the current privacy-policy URL continues to work. This local clone still points to the original privacy repository; do not push it expecting a root user-site deployment.

Google Play download link: https://play.google.com/store/apps/details?id=com.pinyourbite

Screenshots are existing approved store assets with illustrative restaurant data. No app databases, signing files or credentials belong in this website.
