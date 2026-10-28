# Runner App — Geneva Marathon 2027

A static, installable web app prototype for personal marathon training.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and the `/(root)` folder, then save.
4. Wait for GitHub Pages to finish deploying, then open the HTTPS site URL.
5. On iPhone, open that URL in Safari → Share → Add to Home Screen. Choose **Open as Web App** if shown.

## Privacy and local storage

This repository intentionally contains only static app code, a web manifest, service worker, icons, and this README. It excludes personal activity logs, JSON activity backups, and the editable personal starter-data YAML file.

Activity records are stored in that browser's localStorage on that device and do not sync automatically across devices. Export a backup regularly and keep it in private storage (such as iCloud Drive), never in this public repository. Do not commit activity exports, personal data, or private configuration files.

## Notes

The app shell can be cached for offline loading after the site has been opened once. Initial font loading requires an internet connection. This is a personal prototype, not a replacement for medical advice or the race organiser's official information.
