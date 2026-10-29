# Runner App — Geneva Marathon & 10K Plans

A static, installable training web app prototype with Marathon and 10K race modes.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and the `/(root)` folder, then save.
4. Open the HTTPS site URL after deployment.
5. On iPhone, use Safari → Share → Add to Home Screen. On Android, use Chrome → menu → Install app or Add to Home screen (the wording varies by device).

## Race modes and plans

The app provides a Marathon mode targeting 9 May 2027, plus a 10K mode with a configurable race date from 1–30 April 2027 (default placeholder: 25 April). 10K plans offer three, four or five running days per week, with easier base training before a 12-week race-specific phase and a taper before race day.

The 10K plan is a suggested starter template, not a medical assessment or personalised coaching prescription. Tempo work is optional and introduced only in later weeks. Runners new to running may want to start with the [NHS Couch to 5K plan](https://www.nhs.uk/better-health/get-active/get-running-with-couch-to-5k/running-with-couch-to-5k-plan/), which progresses through run/walk sessions and rest days.

## Profiles and privacy

The in-app **Jacob / Romy** selector keeps activity history, plan preferences and race mode in separate browser-local profiles. Selecting Romy on a shared device shows a separate activity history, but this is not cloud sync.

Your partner can open the same public app URL on a Google Pixel or other Android phone and optionally install it from Chrome. Each phone/browser has its own storage: activities logged on one device will not automatically appear on another.

This public repository intentionally contains only static app code, assets, configuration and documentation. It excludes personal activity logs, JSON activity backups and editable personal starter-data files. Export backups regularly and keep them in private storage, never in this public repository.

## Technical notes

The app shell can be cached for offline loading after the site has been opened once. Initial font loading requires an internet connection. The profile selector is a local-device profile switch, not an authenticated account system. Anyone with access to a device/browser can switch profiles on that device.
