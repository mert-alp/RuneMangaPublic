# Sites, browsers and files: where RuneManga works

**[← Back to the README](../README.md)** · **[Features & plans](features.md)** · **[Troubleshooting](troubleshooting.md)** · **[Website](https://runemanga.com/?utm_source=github&utm_medium=readme&utm_campaign=runemanga-public)**

RuneManga gets to your pages in one of two ways. The **browser extension** reads the page images on the reader site you are on and swaps the translations in place. The **WebApp** takes the files you already have: images, a folder or a ZIP. This page covers which browsers the extension runs in, how it behaves on different kinds of reader sites, what to do on sites that hide their images, and exactly which files the WebApp accepts.

---

## Contents

- [Supported browsers](#supported-browsers)
- [How the extension works on a reader site](#how-the-extension-works-on-a-reader-site)
- [Which readers work](#which-readers-work)
- [Translate an area for sites that hide their images](#translate-an-area-for-sites-that-hide-their-images)
- [What the extension reads and sends](#what-the-extension-reads-and-sends)
- [WebApp file inputs: images, a folder or a ZIP](#webapp-file-inputs-images-a-folder-or-a-zip)
- [Files the WebApp does not accept](#files-the-webapp-does-not-accept)
- [Long webtoon strips](#long-webtoon-strips)
- [WebApp upload messages and what they mean](#webapp-upload-messages-and-what-they-mean)

---

## Supported browsers

| Browser | Status | Where to get it |
|---|---|---|
| **Google Chrome** | ✅ Available | [Chrome Web Store](https://chromewebstore.google.com/detail/runemanga/cmclohfalopabbnmeoocelikbibbpppn) |
| **Microsoft Edge** | ✅ Available | [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/gmhdmcggedcjfmijpkladmmimfahnhjm), keeps itself up to date |
| **Opera** | ✅ Available | [Chrome Web Store](https://chromewebstore.google.com/detail/runemanga/cmclohfalopabbnmeoocelikbibbpppn) |
| **Brave** | ✅ Available | [Chrome Web Store](https://chromewebstore.google.com/detail/runemanga/cmclohfalopabbnmeoocelikbibbpppn) |
| **Vivaldi, Arc and other Chromium-based browsers** | ✅ Available | [Chrome Web Store](https://chromewebstore.google.com/detail/runemanga/cmclohfalopabbnmeoocelikbibbpppn) |
| **Firefox** | In review | Submitted to Firefox Add-ons, not listed yet |
| **Safari** | Not available | No Safari version |
| **Any browser, phone or tablet** | ✅ WebApp | [runemanga.com](https://runemanga.com/?utm_source=github&utm_medium=readme&utm_campaign=runemanga-public), nothing to install |

The extension is the same in every Chromium browser. After installing, pin it to the toolbar from the browser's Extensions button so the RuneManga popup is one click away. Signing in (Google, Discord or email) is needed to translate; new accounts get 30 free credits.

---

## How the extension works on a reader site

1. **Open a chapter** on the site you read on.
2. **Rest the pointer on a page.** The RuneManga button appears in a corner of the page image. Click it to translate that page, or rest on it to open the page's bar.
3. **Turn on Auto** in the bar, or *Auto-translate as you scroll* in the popup, to translate every page as it scrolls into view.
4. **Pick the language you read** in the popup under *Translate into*. The original language is detected by itself.
5. **Compare.** Click a translated page's button, choose *Show original* in its bar, or press and hold the page to peek at the original.

**Translation follows your scrolling.** RuneManga does not send a whole chapter at once. It translates from about half a screen behind you to about two screens ahead, nearest first, and the zone moves as you scroll. A page that is still waiting can look blurred for a moment; if you scroll very fast, slow down for a second and the pages catch up.

**Auto is per site and remembered.** Turning it on for one reader does not touch any other site, and the next time you open that site its pages translate by themselves. Turn Auto off in a page's bar or the popup and the pages stay as the site made them.

**Only real pages.** The *Smallest image to translate* setting keeps icons, ads and thumbnails from being translated by themselves and using credits. Smaller images still get a button you can click.

📖 **[Translate manga while you read in your browser](https://runemanga.com/guides/translate-manga-while-you-read)** · **[Manga translator browser extension: how it works](https://runemanga.com/guides/manga-translator-browser-extension)**

---

## Which readers work

| Kind of reader | Does it work? |
|---|---|
| Pages shown as ordinary images | ✅ Yes, including readers that load pages lazily as you scroll |
| Long-strip webtoon readers made of image slices | ✅ Yes, page images are translated as they come into view |
| Pages drawn on a canvas the browser lets extensions read | ✅ Yes |
| Pages drawn on a protected canvas | The browser blocks reading them, and the extension says so. Use [Translate an area](#translate-an-area-for-sites-that-hide-their-images) |
| Images a site passes through another address | Can fail: the extension reports that it cannot follow them yet |
| Images on a different image server that is not allowed yet | Open the popup and press *Allow* for the extra image site, then click the page's button again |
| Images inside a frame embedded in the page | Not translated by the page button; RuneManga translates images in the page itself |

RuneManga does not work around a site's protection. If the extension cannot read a reader at all, the WebApp works with pages you have the right to process.

---

## Translate an area for sites that hide their images

Some readers draw their pages so that no extension can read them. **Translate an area** works there anyway, because it does not read the site's image: it takes a picture of the part of the tab you select.

1. Start it from the popup's *Translate an area* button, by right-clicking the page and choosing *Translate an area...*, or with its keyboard shortcut.
2. **Drag a box** over the text you want to read.
3. The translation of that box appears on top of it. Close it when you are done.

Only the box you drew is sent. One area is translated at a time, and *Repeat last area* in the right-click menu translates the same box again, which is handy when you scroll through panels of the same size. It also works for a single panel on any site.

---

## What the extension reads and sends

- **Nothing is sent from a site until you ask.** RuneManga checks the images on a page on your device to tell whether it is a reader and show its button; nothing leaves your browser until you click the button there or turn Auto on.
- **What goes out:** the page images you translate, sent to the RuneManga service under a neutral file name, and for Translate an area, a picture of the box you drew.
- **What never goes out:** the address of the page, the image's own file name, your browsing history and your cookies. Images are fetched without your cookies.
- **What stays in your browser:** your settings and your History of translated pages.
- **Taking it back:** turn a site off in the popup, change RuneManga's site access in your browser's extension settings, or remove the extension.

The [Privacy Policy](https://runemanga.com/privacy) is the full text.

📖 **[Is RuneManga safe? What happens to your pages](https://runemanga.com/guides/what-happens-to-your-pages)**

---

## WebApp file inputs: images, a folder or a ZIP

| Input | How | Notes |
|---|---|---|
| **Choose files** | Press *Choose files* and select several images | Sorted by name, numbers in natural order |
| **Choose a folder** | Press *Choose folder*, or drop a folder onto the box | Subfolders are read too |
| **Drag and drop** | Drop files or a folder onto the box | Same as choosing them |
| **ZIP** | Choose it or drop it | Opened in your browser; nothing is uploaded until you press the button |
| **CBZ** | Rename it from `.cbz` to `.zip` | A CBZ is a ZIP with another name |
| **Paste** | Copy an image and press Ctrl+V on the page | Click an empty part of the page first: paste is ignored while a text box or drop-down has focus |

| | |
|---|---|
| **Image formats** | PNG, JPG, WebP, GIF and AVIF |
| **Size per page** | Up to 20 MB. A page can also be refused if it has an extreme number of pixels |
| **Pages per job** | 50 on Free, 100 on Supporter, 200 on Pro, 500 on Ultimate |
| **Order** | `2.png` comes before `10.png`. Name files with leading zeros (001, 002, 003) to be certain |
| **Inside a ZIP** | Only images are kept, folders inside are flattened, `__MACOSX` and hidden files are skipped |
| **Result** | Each page as a PNG, or all pages in one ZIP |

After the first pages are in, the box becomes *Add more pages*; new pages go to the end. Remove one with the cross on its thumbnail, or *Clear all* to start again.

📖 **[Upload a ZIP, a folder or a pasted image](https://runemanga.com/guides/upload-zip-folder-paste)**

---

## Files the WebApp does not accept

| File | What to do |
|---|---|
| **PDF** | Convert it into one image per page first, for example with `pdftoppm -png -r 200 chapter.pdf page`, a PDF reader's export option, or Preview on a Mac. See [How to translate a manga PDF](https://runemanga.com/guides/translate-manga-pdf) |
| **TIFF, BMP, HEIC** | Export as PNG or JPG. One unsupported file stops the whole job |

---

## Long webtoon strips

Webtoon episodes are often a few very tall images. Each image can be up to 20 MB, and very tall strips count by their full size. If an upload is refused, split the strip at a gap between panels and send the parts in order. Do not stitch separate pages into one image: separate pages are processed in order with the same settings, and one problem page is easier to spot.

---

## WebApp upload messages and what they mean

| Message | What it means |
|---|---|
| *X is not an image or zip* | The file is a PDF, a document or something else. Convert it to an image |
| *One of the pages is not a supported image* | A HEIC, TIFF or BMP got into the list. Convert it, press *Clear all* and add the pages again |
| *The upload is too large* | One page or the pages together are over the limit. Send fewer pages per job |
| *X is not a readable zip* | The ZIP is damaged or uses a format your browser cannot open. Make a new ZIP |
| *X has no images in it* | The ZIP holds only other files or hidden ones |
| *X is over 20 MB* | Save the page at a lower quality, or split a very tall strip |
| *Only N pages fit in one job* | N is your plan's limit. Split the chapter and run each part |
| *You are out of credits* | Buy a pack or upgrade on your account page |

---

**[← Back to the README](../README.md)** · **[Features & plans](features.md)** · **[Languages](languages.md)** · **[Comparison](comparison.md)** · **[FAQ](faq.md)** · **[Troubleshooting](troubleshooting.md)**
