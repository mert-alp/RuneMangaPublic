# Security policy

RuneManga is a closed-source service: a browser extension distributed through the [Chrome Web Store](https://chromewebstore.google.com/detail/runemanga/cmclohfalopabbnmeoocelikbibbpppn) and [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/gmhdmcggedcjfmijpkladmmimfahnhjm), and a WebApp at **[runemanga.com](https://runemanga.com/?utm_source=github&utm_medium=readme&utm_campaign=runemanga-public)**. This repository, RuneMangaPublic, holds public documentation only; it contains no application code.

## Reporting a vulnerability

**Please report privately, never as a public issue or a public Discord message.** Use either:

- Email **[support@runemanga.com](mailto:support@runemanga.com)**
- A direct message to the team on **[Discord](https://discord.gg/TRwM9zgJPG)**

Please include what you found, how to reproduce it, where it applies (the extension and its version, the WebApp, the website's account pages), and what you think the impact is.

Please do not publish details or a working exploit before the issue has been fixed, and do not access, change or delete other people's data while testing.

## Scope

**In scope:** the RuneManga browser extension, `runemanga.com` (the WebApp, sign-in, the account and support pages) and the RuneManga API the extension and the WebApp talk to.

**Out of scope:** third-party services RuneManga relies on or can send text to, such as Google sign-in and Google Translate, Discord, Lemon Squeezy, and the AI providers you can connect your own key for in the extension. Report those to the provider. The reader sites the extension runs on are out of scope too.

## Installing safely

**Only install RuneManga from the [Chrome Web Store](https://chromewebstore.google.com/detail/runemanga/cmclohfalopabbnmeoocelikbibbpppn) or [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/gmhdmcggedcjfmijpkladmmimfahnhjm).** Opera, Brave, Vivaldi, Arc and other Chromium-based browsers install from the Chrome Web Store. A Firefox version is in review. Nothing is distributed from this repository.

RuneManga never asks for a password: you sign in with Google, Discord or a one-time link we email you. Card details are handled by Lemon Squeezy and never reach us.
