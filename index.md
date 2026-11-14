# TransLang Privacy Policy

_Last updated: 14 November 2026_

TransLang is a browser extension that translates text you select on web pages.

## What TransLang processes

- **Selected text:** when you ask TransLang to translate (by selecting text, clicking the icon,
  or using the context menu), the selected text is translated **on your device**: in Google
  Chrome by Chrome's built-in translator, in other browsers (Firefox, Edge, Brave, Opera, …) by
  Bergamot, Mozilla's open-source translation engine, which is included in the extension. It is
  **never sent** to the developer or to any other server.
- **Your browser's language settings:** read on your device to choose sensible default
  languages (for example the language to translate into). They are not sent anywhere.
- **Page address (hostname only):** the site name (for example `wikipedia.org`) is saved next to
  each entry in your translation history so you can see where it came from. Full page addresses
  are not stored.

## What TransLang stores, and where

| Data                                                        | Where                                                           | Shared?                                                                            |
| ----------------------------------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Settings (target language, trigger mode, disabled sites, …) | Your browser's extension storage (sync)                         | Synced only between your own browsers if you are signed in to your browser account |
| Translation cache                                           | Your device (IndexedDB)                                         | No                                                                                 |
| Translation history (if enabled)                            | Your device (IndexedDB)                                         | No                                                                                 |
| Language packs                                              | Your device (managed by Chrome, or IndexedDB in other browsers) | No                                                                                 |

You can turn off history, clear the history and the cache in TransLang's settings, and uninstalling
the extension deletes all of its data.

## Language pack downloads

Language packs are downloaded once, when you click "Download" in TransLang's settings: in Google
Chrome from Google (by Chrome itself), in other browsers from TransLang's model mirror on GitHub
Pages (`usefulhands.github.io/translang-models`, unmodified copies of the translation models Firefox
uses, by Mozilla). These downloads contain only translation models; no text you select and no
personal data is sent, and no account is needed.

As with any download, the server sees your IP address and may keep it in its access logs under its
own privacy policy: [Google Privacy Policy](https://policies.google.com/privacy) for Chrome's packs,
[GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)
for the mirror. GitHub does not share these logs with the developer, so the developer cannot see who
downloads a language pack.

## What TransLang does not do

- No accounts, no analytics, no tracking, no advertising.
- No data is sold, transferred or shared with third parties.
- No remote code is loaded (the translation engine is part of the extension; only model data is
  downloaded).

## Permissions

- _Read and change data on all websites_ (content script): needed to read the text you select and
  show the translation tooltip next to it.
- `storage`: save your settings.
- `unlimitedStorage`: keep downloaded language packs (about 20–40 MB each) on your device.
- `offscreen` (Chromium browsers): run the on-device translators in a hidden extension page.
- `contextMenus`: the "Translate with TransLang" right-click item.
- `activeTab`: show the current site's name in the popup (for "Active on this site").

## Contact

Questions: contact the developer through the extension's store listing (Chrome Web Store,
Microsoft Edge Add-ons or Firefox Add-ons).
