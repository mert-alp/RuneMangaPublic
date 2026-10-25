# Frequently asked questions

**[← Back to the README](../README.md)** · **[More answers at runemanga.com/faq](https://runemanga.com/faq)** · **[Website](https://runemanga.com/?utm_source=github&utm_medium=readme&utm_campaign=runemanga-public)**

---

## Contents

- [Getting started](#getting-started)
- [The browser extension](#the-browser-extension)
- [Languages and quality](#languages-and-quality)
- [Plans, credits and payments](#plans-credits-and-payments)
- [Privacy and legality](#privacy-and-legality)
- [About RuneManga](#about-runemanga)

---

## Getting started

### What is RuneManga?

A service that translates manga, manhwa, manhua and webtoon pages into your language. It finds the speech bubbles, reads the lettering, translates it with RuneLingua, erases the original text, fills in the background and sets the translation back into each bubble. You use it in the WebApp at [runemanga.com](https://runemanga.com/?utm_source=github&utm_medium=readme&utm_campaign=runemanga-public) or with the browser extension, right on the sites you read.

### What do I need to start?

A browser and a free account. Sign in with Google, Discord or a link we email you: no password, no card, and 30 free credits arrive at once. For the extension, add it from the Chrome Web Store or Edge Add-ons.

### How do I translate a chapter in the WebApp?

Add the pages (files, a folder, a ZIP or a pasted image), pick the language you want to read, press the button, then download one page as a PNG or the whole chapter as a ZIP. The original language is detected for you.

### How do I translate while reading online?

Install the extension, open a chapter, rest the pointer on a page and click the RuneManga button in its corner. Turn on *Auto* and pages translate as they scroll into view.

### How long does it take?

It depends on the number of pages and how busy the service is; progress is shown page by page. After a quiet spell the translator can need a moment to wake up: the first page then takes longer, and the next ones a few seconds each.

### Can I translate a PDF or a CBZ?

A CBZ, yes: rename it from `.cbz` to `.zip` and add it like any ZIP. A PDF, not directly: convert it to page images first. The guide [How to translate a manga PDF](https://runemanga.com/guides/translate-manga-pdf) shows how.

### Does it work on my phone?

The WebApp does: upload pages in any mobile browser. The extension is for desktop Chromium browsers.

### Is RuneManga a place to read manga?

No. RuneManga translates the pages you open or upload. It does not host, list or publish comics.

---

## The browser extension

### Which browsers are supported?

Chrome, Edge, Opera, Brave, Vivaldi, Arc and other Chromium-based browsers. Install it from the [Chrome Web Store](https://chromewebstore.google.com/detail/runemanga/cmclohfalopabbnmeoocelikbibbpppn), or from [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/gmhdmcggedcjfmijpkladmmimfahnhjm) in Edge. A Firefox version is in review. There is no Safari version.

### What does Auto do?

It translates the pages near you as you scroll: from about half a screen behind to about two screens ahead, nearest first. It does not push a whole chapter through at once. Auto is remembered per site, so the next time you open that reader its pages translate by themselves.

### What if a site hides its images?

Some readers draw their pages in a protected canvas no extension can read. Use **Translate an area**: from the popup, the right-click menu or its shortcut, drag a box over the text and the translation appears on top of it.

### Can I see the original again?

Yes. Click a translated page's button, choose *Show original* in its bar, or press and hold the page to peek. *Show originals* in the popup flips the whole tab.

### Does the extension keep my translated pages?

In your browser only. History keeps your last translated pages and their originals, never uploaded, with auto-delete after a day, a week, a month or never. An image you already translated with the same settings shows its translation again without a new credit.

### Can I use my own AI provider?

Yes, with the next extension update. In the popup's Options you will be able to connect your own key for OpenRouter, Google, OpenAI, Anthropic, DeepSeek, xAI or any OpenAI-compatible service. The key stays in your browser and goes only to that provider, which bills you for its use; pages still use your RuneManga credits. RuneLingua stays the default on every plan.

### What does the extension see?

It checks the images on a page on your device to show its button on readers. Nothing is sent from a site until you click the button there or turn Auto on. Then it sends the page images under a neutral file name, never the page address, your browsing history or your cookies.

### Is there a keyboard shortcut?

Three: turn translation on or off for the site, translate an area, and show originals or translations on the tab. You can rebind them in your browser's extension shortcut settings.

---

## Languages and quality

### Which languages are supported?

RuneManga reads Japanese, Korean, Simplified and Traditional Chinese, English, Spanish, French, Portuguese, Indonesian, Vietnamese and Thai, and detects which one a page is in. It translates into 89 languages, including English, Turkish, Spanish, Portuguese, French, German, Russian, Indonesian and Vietnamese. Arabic and Thai output is experimental: their lettering is not verified yet. The full list is in [languages.md](languages.md).

### Can I choose the original language myself?

There is no source-language setting: the language on the page is detected automatically. If a page with very little text is guessed wrong, run it again from a larger, cleaner image.

### Is it only for Japanese and Korean into English?

No. Any of the 11 sources goes into any of the 89 targets, so an English comic can be read in Spanish or a French one in Turkish.

### Why is a translation wrong?

Usually because the text was hard to read: a small, blurry or heavily compressed image loses the strokes that tell characters apart, and a misread word is faithfully translated into the wrong one. Slang, puns, names and honorifics are the weak spot of any machine translation. Use the largest, cleanest scan you have.

### Does it translate sound effects?

Not today. Sound effects are drawn into the art and stay as drawn, on purpose. An option for them may come later.

### What about narration boxes and text outside bubbles?

They are not translated yet. Translating text outside speech bubbles is the next big piece being worked on.

### Can it handle vertical Japanese text?

Yes, bubble by bubble, set horizontally in your language. Vertical lettering and text drawn into the art are the hardest cases and are still improving.

### Does it work on coloured manhwa?

Yes. Translate changes only the lettering, and the colours stay untouched.

### Can I colourise a black-and-white page?

Not yet. Colorizer: coming soon. We're working on it now; until then, use Translate.

### Why is the translated text so small?

A translation is often longer than the original and the bubble cannot grow, so the text is shrunk until it fits instead of running over the art. A larger scan helps, and so does a target language that runs shorter. The guide [Why translated text does not fit the bubble](https://runemanga.com/guides/translated-text-does-not-fit-the-bubble) explains it.

### Can I edit the translation?

Not on the site yet. The result is a normal PNG, so you can retouch a bubble in any image editor.

---

## Plans, credits and payments

### Is RuneManga free?

Yes. Every new account gets 30 free credits once, one credit per page, and they never expire. Free uses the same translator, RuneLingua, as every other plan.

### How do credits work?

One credit translates one page, in the WebApp and in the extension. Pages that fail, or that are already in your language, cost nothing. Paid plans get their credits on each renewal date, and plan credits left at the end of the period do not carry over. Credits from a pack never expire, and your plan's credits are always used first.

### What do the plans cost?

Supporter $2.99 a month (750 credits), Pro $4.99 (2,000) and Ultimate $9.99 (5,000). Credit packs are 1,000 credits for $4.99, 2,500 for $7.99 and 6,000 for $14.99, and never expire. Prices are in USD; the current ones are always at [runemanga.com/#pricing](https://runemanga.com/?utm_source=github&utm_medium=readme&utm_campaign=runemanga-public#pricing).

### What changes on a paid plan?

More credits, bigger jobs in the WebApp (100, 200 or 500 pages instead of 50) and more pages translated at the same time (2, 3 or 4 instead of 1). The translator and the pipeline are the same, so a missed bubble or a cramped line is not fixed by upgrading.

### Can I change or cancel my plan?

Yes, any time, from *Manage subscription* on your account page. A cancelled plan keeps working until the end of the period you paid for, then you are back on Free. See the [refund policy](https://runemanga.com/refunds).

### Who handles payments?

Lemon Squeezy handles the payment, tax and invoices. Card details never reach RuneManga, and the receipt comes from Lemon Squeezy.

### What happens when I run out of credits?

Translating stops until you have credits again: buy a pack, or wait for your plan's credits on the next renewal. Pages you already translated stay translated.

### Can I earn credits?

Yes: your account page has an invite link, and friends who join and translate earn you credits. Gift codes can also unlock a plan for a while.

---

## Privacy and legality

### What happens to my pages?

They are processed on our servers and deleted automatically about an hour after the job finishes. They are not used to train models, not sold and not shown to other users. Download what you want to keep before the hour is up.

### Does my image go to the translator?

No. Only the text found on the page is sent to the translator, never the image.

### What does RuneManga store about my account?

What a free account needs: your email, your name and profile picture link if you sign in with Google, your plan, your credits and their history, and your sign-in sessions. There is no password. You can delete the account at any time on the Account page. The [Privacy Policy](https://runemanga.com/privacy) lists everything.

### Does the website track me?

The only analytics is Google Analytics counting visits, with its advertising features off. In the EU and EEA, the UK, Switzerland and Türkiye it runs only after you accept it, and *Cookie settings* at the bottom of every page turns it off. It never receives your pages.

### Is it legal to use?

Use RuneManga only on pages you have the right to process, such as your own work, licensed work or material you may read for personal use. You are responsible for how you use the results. See the [Terms](https://runemanga.com/terms).

---

## About RuneManga

### Who makes RuneManga?

Two founders, Engin (the API and the machine-learning pipeline) and Mert (the website and the browser extension). RuneManga is a RuneTranslate product, operated from Türkiye. More at [runemanga.com/about](https://runemanga.com/about).

### Is RuneManga open source?

No. RuneManga is closed-source, and this repository holds documentation only.

### Is RuneLingua better than Google Translate?

We built RuneLingua for manga and manhwa dialogue, and it is still improving. We do not claim it beats Google Translate; try it on your own series.

### How do I get help or suggest a feature?

*Report a problem* in the extension, the Support page on the website when signed in, [Discord](https://discord.gg/TRwM9zgJPG), or [support@runemanga.com](mailto:support@runemanga.com). See [SUPPORT.md](../SUPPORT.md).

---

**[← Back to the README](../README.md)** · **[Features & plans](features.md)** · **[Languages](languages.md)** · **[Sites & browsers](sites-and-browsers.md)** · **[Comparison](comparison.md)** · **[Troubleshooting](troubleshooting.md)**
