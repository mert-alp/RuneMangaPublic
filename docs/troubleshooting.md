# Troubleshooting

**[← Back to the README](../README.md)** · **[Guides](https://runemanga.com/guides)** · **[Ask on Discord](https://discord.gg/TRwM9zgJPG)**

Common problems when translating manga, manhwa and webtoons with RuneManga, and what actually fixes them.

**Before anything else: look at the image.** Most bad results are not translation problems. They start earlier, when the text on the page was hard to read: a small, blurry or heavily compressed image loses the thin strokes that tell characters apart, and a misread word is faithfully translated into the wrong one. The largest, cleanest copy of the page fixes more than any setting.

---

## Contents

- [Some text is still in the original language](#some-text-is-still-in-the-original-language)
- [A line came out as nonsense](#a-line-came-out-as-nonsense)
- [The translated text is tiny or crowded](#the-translated-text-is-tiny-or-crowded)
- [Faint marks where the old lettering was](#faint-marks-where-the-old-lettering-was)
- [The wrong language was detected](#the-wrong-language-was-detected)
- [The extension does nothing on a site](#the-extension-does-nothing-on-a-site)
- [A page says it cannot be read](#a-page-says-it-cannot-be-read)
- [The extension stopped translating](#the-extension-stopped-translating)
- [An upload is refused](#an-upload-is-refused)
- [A page or a job failed](#a-page-or-a-job-failed)
- [The first page is slow](#the-first-page-is-slow)
- [Google Translate did not answer](#google-translate-did-not-answer)
- [You are out of credits](#you-are-out-of-credits)
- [Still stuck](#still-stuck)

---

## Some text is still in the original language

Look at where the untranslated text sits:

| What stayed untranslated | Why | What to do |
|---|---|---|
| Narration boxes, captions, signs, loose text on the art | Text outside speech bubbles is not translated yet | A known gap, being worked on |
| Large, stylised lettering drawn like art | A sound effect, left as drawn on purpose | Nothing; an option may come later |
| A line inside a bubble | Usually resolution or an unusual font | Use a larger, less compressed image and run the page again |
| A clean, large bubble that was skipped | Should not happen | Tell us: [Report a problem](#still-stuck) |

Webtoons often place lettering straight on the art with no bubble, so more of it can stay in Korean than on Japanese manga.

📖 **[Why RuneManga misses some text on a page](https://runemanga.com/guides/translator-misses-some-text)** · **[Why manga sound effects are not translated](https://runemanga.com/guides/why-sound-effects-are-not-translated)**

---

## A line came out as nonsense

The text was most likely misread before it was translated. Check the original for:

- **Furigana** beside the kanji, which can blur into the main text on a small scan
- **A decorative or handwritten font**, or text that is tilted, curved or very small
- **Low contrast**, such as pale lettering on screentone or a dark panel
- **A pun or wordplay**, the weak spot of any machine translation

Try a larger, sharper copy of the page. Do not upscale a small image yourself: it does not add the detail that is missing.

📖 **[Best image quality for manga translation](https://runemanga.com/guides/best-image-quality-for-manga-translation)**

---

## The translated text is tiny or crowded

The translation is longer than the original and the bubble cannot grow, so the text is shrunk until it fits rather than running over the art. Tall, narrow bubbles made for vertical Japanese are the hardest case.

1. Use a larger scan: the same lettering gets more pixels.
2. If you read several languages, a shorter one usually fits better. English often fits better than Spanish or German.
3. Do not crop the edges of bubbles: the outline is how the space is measured.

If it is both tiny *and* touching the bubble edge, send us the page type and the language pair at support@runemanga.com.

📖 **[Why translated text does not fit the bubble](https://runemanga.com/guides/translated-text-does-not-fit-the-bubble)**

---

## Faint marks where the old lettering was

Text on top of screentone, gradients or detailed art is harder to erase cleanly, and you can see ghost marks even when the text itself was translated. A larger, cleaner scan helps. For a single bubble, the result is a normal PNG you can retouch in any image editor.

---

## The wrong language was detected

The original language is detected from the page, and a page with only a word or two can be guessed wrong. There is no source-language setting to override it.

- Run the page again: in the extension, click its button; in the WebApp, start over with that page.
- Use a larger, cleaner image, so there is more readable text to detect from.
- Make sure the page is one of the [11 source languages](languages.md#source-languages-what-runemanga-reads).

If the original and the language you picked are the same, the page is not translated and costs nothing.

---

## The extension does nothing on a site

1. **Reload the page.** After the extension is installed or updated, open tabs need a reload.
2. **Check that you are signed in.** The popup shows your plan and credits; translating needs a free account.
3. **Click the page's button,** or check that Auto is on in a page's bar or the popup.
4. **Accept the browser's prompt** if it asks for access to the site and the servers its images load from.
5. **Check the image size.** Very small images are not translated by themselves (*Smallest image to translate* in Settings), but you can still click their button.
6. **Frames.** RuneManga translates images in the page itself, not in a frame embedded in it. Open the frame's page directly, or use Translate an area.

---

## A page says it cannot be read

| Message | Fix |
|---|---|
| The reader protects its pages | The site draws pages in a protected canvas the browser does not let extensions read. Use **Translate an area**: right-click the page, choose *Translate an area...* and drag a box over the text |
| RuneManga isn't allowed to read images from this image's site yet | Open the popup and press *Allow* for the extra image site, then click the page's button again |
| This image's site sends it from another site | The site redirects its images, which RuneManga cannot follow yet. Use Translate an area |
| Not a page image | RuneManga skipped it as an icon or banner. Click it to translate it anyway |

📖 **[Translate an area for sites that hide their images](sites-and-browsers.md#translate-an-area-for-sites-that-hide-their-images)**

---

## The extension stopped translating

- **Paused:** press *Resume* in the popup.
- **You scrolled faster than the translation:** slow down for a second and the pages catch up.
- **Busy:** pages that hit a busy moment try again by themselves; click one to try at once.
- **Out of credits:** see [You are out of credits](#you-are-out-of-credits).
- **"RuneManga was updated or reloaded":** reload the page.

---

## An upload is refused

| Message | Fix |
|---|---|
| *X is not an image or zip* | Convert the PDF or document to images. See [How to translate a manga PDF](https://runemanga.com/guides/translate-manga-pdf) |
| *One of the pages is not a supported image* | A HEIC, TIFF or BMP got in. Convert it to PNG or JPG, press *Clear all* and add the pages again |
| *X is over 20 MB* | Save the page at a lower quality, or split a very tall strip at a gap between panels |
| *Only N pages fit in one job* | Split the chapter: 50 pages per job on Free, 100 on Supporter, 200 on Pro, 500 on Ultimate |
| *X is not a readable zip* | Make a new ZIP |
| *X has no images in it* | The ZIP holds only other files or hidden ones |
| *The upload is too large* | Send fewer pages per job |

A CBZ needs renaming from `.cbz` to `.zip` first.

📖 **[Upload a ZIP, a folder or a pasted image](https://runemanga.com/guides/upload-zip-folder-paste)**

---

## A page or a job failed

- A failed page shows its own message. A page that fails costs nothing.
- If a whole job failed, wait a moment and try again: the service may be busy.
- *Lost track of the job:* it may have expired. Results are deleted about an hour after a job finishes, so download what you need first.
- *Too many jobs at once:* wait a moment, or the number of seconds shown, and try again.

---

## The first page is slow

After a quiet spell the translator has to start up. The first page can take up to a minute, and the next ones a few seconds each. The extension says *Waking up the translator* while it happens.

---

## Google Translate did not answer

A few target languages, and pages translated while RuneLingua is briefly unavailable, go to Google Translate from your browser. If Google does not answer from your connection, try again in a minute. If Google blocks translations from your network (often a VPN or an office network), turn the VPN off for Google, or, after the next extension update, use your own AI key in the extension.

---

## You are out of credits

Buy a credit pack (1,000, 2,500 or 6,000 credits, never expiring) or pick a plan for credits every month, from your account page or the extension's popup. If you are on a plan, its credits come back on your next renewal date. Pages you already translated stay translated.

---

## Still stuck

- **In the extension:** popup → *Report a problem*. Attach a capture of the page if it helps; diagnostics cut every address down to the site's name.
- **On the website:** the Support page at [runemanga.com/support](https://runemanga.com/support), after signing in. Replies appear on your report's page.
- **[Discord](https://discord.gg/TRwM9zgJPG)**, or email **[support@runemanga.com](mailto:support@runemanga.com)** with the language pair and what kind of text went wrong.

Please only send pages you have the right to share.

---

**[← Back to the README](../README.md)** · **[Features & plans](features.md)** · **[Languages](languages.md)** · **[Sites & browsers](sites-and-browsers.md)** · **[Comparison](comparison.md)** · **[FAQ](faq.md)**
