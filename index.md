# TransLang Privacy Policy

_Last updated: 13 November 2026_

[Türkçe aşağıda](#turkce)

## English

TransLang is a browser extension that translates text you select on web pages.

**What TransLang processes**

- **Selected text:** when you ask TransLang to translate (by selecting text, clicking the icon,
  or using the context menu), the selected text is translated **on your device** by Chrome's
  built-in translator. It is **never sent** to the developer or to any other server.
- **Page address (hostname only):** the site name (for example `wikipedia.org`) is saved next to
  each entry in your translation history so you can see where it came from. Full page addresses
  are not stored.

**What TransLang stores, and where**

| Data                                                        | Where                                                    | Shared?                                                              |
| ----------------------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------------------- |
| Settings (target language, trigger mode, disabled sites, …) | Your browser's extension storage (`chrome.storage.sync`) | Synced only between your own browsers if you are signed in to Chrome |
| Translation cache                                           | Your device (IndexedDB)                                  | No                                                                   |
| Translation history (if enabled)                            | Your device (IndexedDB)                                  | No                                                                   |
| Language packs                                              | Managed by Chrome on your device                         | No                                                                   |

You can turn off history, clear the history and the cache in TransLang's settings, and uninstalling
the extension deletes all of its data.

**What TransLang does not do**

- No accounts, no analytics, no tracking, no advertising.
- No data is sold, transferred or shared with third parties.
- No remote code is loaded.

**Permissions**

- _Read and change data on all websites_ (content script): needed to read the text you select and
  show the translation tooltip next to it.
- `storage`: save your settings.
- `offscreen`: run Chrome's on-device translator in a hidden extension page.
- `contextMenus`: the "Translate with TransLang" right-click item.
- `activeTab`: show the current site's name in the popup (for "Active on this site").

**Contact**

Questions: open an issue in the project's repository or contact the developer through the
Chrome Web Store listing.

---

<a id="turkce"></a>

## Türkçe

TransLang, web sayfalarında seçtiğiniz metni çeviren bir tarayıcı eklentisidir.

**TransLang neyi işler**

- **Seçilen metin:** TransLang'den çeviri istediğinizde (metin seçerek, simgeye tıklayarak veya
  sağ tık menüsüyle), seçilen metin Chrome'un yerleşik çevirmeniyle **cihazınızda** çevrilir.
  Geliştiriciye veya başka bir sunucuya **asla gönderilmez**.
- **Sayfa adresi (yalnızca site adı):** çeviri geçmişindeki her kaydın yanına site adı (ör.
  `wikipedia.org`) kaydedilir. Tam sayfa adresi saklanmaz.

**TransLang neyi, nerede saklar**

| Veri                                                      | Nerede                                             | Paylaşılıyor mu?                                                              |
| --------------------------------------------------------- | -------------------------------------------------- | ----------------------------------------------------------------------------- |
| Ayarlar (çeviri dili, tetikleme şekli, kapalı siteler, …) | Tarayıcının eklenti deposu (`chrome.storage.sync`) | Yalnızca Chrome'da oturum açtıysanız kendi tarayıcılarınız arasında eşitlenir |
| Çeviri önbelleği                                          | Cihazınız (IndexedDB)                              | Hayır                                                                         |
| Çeviri geçmişi (açıksa)                                   | Cihazınız (IndexedDB)                              | Hayır                                                                         |
| Dil paketleri                                             | Cihazınızda Chrome tarafından yönetilir            | Hayır                                                                         |

Geçmişi kapatabilir, geçmişi ve önbelleği TransLang ayarlarından temizleyebilirsiniz. Eklentiyi
kaldırmak tüm verilerini siler.

**TransLang ne yapmaz**

- Hesap, analiz, izleme veya reklam yoktur.
- Hiçbir veri satılmaz, aktarılmaz veya üçüncü taraflarla paylaşılmaz.
- Uzaktan kod yüklenmez.

**İzinler**

- _Tüm web sitelerindeki verileri okuma ve değiştirme_ (içerik betiği): seçtiğiniz metni okumak ve
  çeviri kutucuğunu yanında göstermek için gereklidir.
- `storage`: ayarlarınızı kaydetmek.
- `offscreen`: Chrome'un cihaz üzerindeki çevirmenini gizli bir eklenti sayfasında çalıştırmak.
- `contextMenus`: "TransLang ile çevir" sağ tık seçeneği.
- `activeTab`: menüde mevcut sitenin adını göstermek ("Bu sitede etkin" için).

**İletişim**

Sorularınız için projenin deposunda bir konu açabilir veya Chrome Web Mağazası sayfası üzerinden
geliştiriciyle iletişime geçebilirsiniz.
