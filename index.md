# TransLang Privacy Policy

_Last updated: 14 November 2026_

[Türkçe aşağıda](#turkce)

## English

TransLang is a browser extension that translates text you select on web pages.

**What TransLang processes**

- **Selected text:** when you ask TransLang to translate (by selecting text, clicking the icon,
  or using the context menu), the selected text is translated **on your device**: in Google
  Chrome by Chrome's built-in translator, in other browsers (Firefox, Edge, Brave, Opera, …) by
  Bergamot, Mozilla's open-source translation engine, which is included in the extension. It is
  **never sent** to the developer or to any other server.
- **Page address (hostname only):** the site name (for example `wikipedia.org`) is saved next to
  each entry in your translation history so you can see where it came from. Full page addresses
  are not stored.

**What TransLang stores, and where**

| Data                                                        | Where                                                           | Shared?                                                              |
| ----------------------------------------------------------- | --------------------------------------------------------------- | -------------------------------------------------------------------- |
| Settings (target language, trigger mode, disabled sites, …) | Your browser's extension storage (`chrome.storage.sync`)        | Synced only between your own browsers if you are signed in to Chrome |
| Translation cache                                           | Your device (IndexedDB)                                         | No                                                                   |
| Translation history (if enabled)                            | Your device (IndexedDB)                                         | No                                                                   |
| Language packs                                              | Your device (managed by Chrome, or IndexedDB in other browsers) | No                                                                   |

You can turn off history, clear the history and the cache in TransLang's settings, and uninstalling
the extension deletes all of its data.

**Language pack downloads**

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

**What TransLang does not do**

- No accounts, no analytics, no tracking, no advertising.
- No data is sold, transferred or shared with third parties.
- No remote code is loaded (the translation engine is part of the extension; only model data is
  downloaded).

**Permissions**

- _Read and change data on all websites_ (content script): needed to read the text you select and
  show the translation tooltip next to it.
- `storage`: save your settings.
- `unlimitedStorage`: keep downloaded language packs (about 20–40 MB each) on your device.
- `offscreen` (Chromium browsers): run the on-device translators in a hidden extension page.
- `contextMenus`: the "Translate with TransLang" right-click item.
- `activeTab`: show the current site's name in the popup (for "Active on this site").

**Contact**

Questions: contact the developer through the extension's store listing (Chrome Web Store,
Microsoft Edge Add-ons or Firefox Add-ons).

---

<a id="turkce"></a>

## Türkçe

TransLang, web sayfalarında seçtiğiniz metni çeviren bir tarayıcı eklentisidir.

**TransLang neyi işler**

- **Seçilen metin:** TransLang'den çeviri istediğinizde (metin seçerek, simgeye tıklayarak veya
  sağ tık menüsüyle), seçilen metin **cihazınızda** çevrilir: Google Chrome'da Chrome'un yerleşik
  çevirmeniyle, diğer tarayıcılarda (Firefox, Edge, Brave, Opera, …) eklentinin içinde gelen,
  Mozilla'nın açık kaynak çeviri motoru Bergamot ile. Geliştiriciye veya başka bir sunucuya
  **asla gönderilmez**.
- **Sayfa adresi (yalnızca site adı):** çeviri geçmişindeki her kaydın yanına site adı (ör.
  `wikipedia.org`) kaydedilir. Tam sayfa adresi saklanmaz.

**TransLang neyi, nerede saklar**

| Veri                                                      | Nerede                                                    | Paylaşılıyor mu?                                                              |
| --------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------------------------- |
| Ayarlar (çeviri dili, tetikleme şekli, kapalı siteler, …) | Tarayıcının eklenti deposu (`chrome.storage.sync`)        | Yalnızca Chrome'da oturum açtıysanız kendi tarayıcılarınız arasında eşitlenir |
| Çeviri önbelleği                                          | Cihazınız (IndexedDB)                                     | Hayır                                                                         |
| Çeviri geçmişi (açıksa)                                   | Cihazınız (IndexedDB)                                     | Hayır                                                                         |
| Dil paketleri                                             | Cihazınız (Chrome yönetir; diğer tarayıcılarda IndexedDB) | Hayır                                                                         |

Geçmişi kapatabilir, geçmişi ve önbelleği TransLang ayarlarından temizleyebilirsiniz. Eklentiyi
kaldırmak tüm verilerini siler.

**Dil paketi indirmeleri**

Dil paketleri, TransLang ayarlarında "İndir"e tıkladığınızda bir kez indirilir: Google Chrome'da
Google'dan (Chrome'un kendisi tarafından), diğer tarayıcılarda TransLang'in GitHub Pages
üzerindeki model kopyasından (`usefulhands.github.io/translang-models`; Mozilla'nın Firefox'ta
kullandığı çeviri modellerinin değiştirilmemiş kopyaları). Bu indirmeler yalnızca çeviri
modellerini içerir; seçtiğiniz metin veya kişisel veri gönderilmez ve hesap gerekmez.

Her indirmede olduğu gibi sunucu IP adresinizi görür ve kendi gizlilik politikasına göre erişim
kayıtlarında tutabilir: Chrome paketleri için [Google Gizlilik Politikası](https://policies.google.com/privacy?hl=tr),
model kopyası için [GitHub Genel Gizlilik Bildirimi](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
GitHub bu kayıtları geliştiriciyle paylaşmaz; geliştirici dil paketini kimin indirdiğini göremez.

**TransLang ne yapmaz**

- Hesap, analiz, izleme veya reklam yoktur.
- Hiçbir veri satılmaz, aktarılmaz veya üçüncü taraflarla paylaşılmaz.
- Uzaktan kod yüklenmez (çeviri motoru eklentinin parçasıdır; yalnızca model verisi indirilir).

**İzinler**

- _Tüm web sitelerindeki verileri okuma ve değiştirme_ (içerik betiği): seçtiğiniz metni okumak ve
  çeviri kutucuğunu yanında göstermek için gereklidir.
- `storage`: ayarlarınızı kaydetmek.
- `unlimitedStorage`: indirilen dil paketlerini (her biri yaklaşık 20–40 MB) cihazınızda tutmak.
- `offscreen` (Chromium tarayıcılar): cihaz üzerindeki çevirmenleri gizli bir eklenti sayfasında
  çalıştırmak.
- `contextMenus`: "TransLang ile çevir" sağ tık seçeneği.
- `activeTab`: menüde mevcut sitenin adını göstermek ("Bu sitede etkin" için).

**İletişim**

Sorularınız için eklentinin mağaza sayfası (Chrome Web Mağazası, Microsoft Edge Eklentileri veya
Firefox Eklentileri) üzerinden geliştiriciyle iletişime geçebilirsiniz.
