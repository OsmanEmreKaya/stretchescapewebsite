# Stretch Escape — website

Stretch Escape'in tanıtım, destek ve gizlilik sayfaları. GitHub Pages'ten
yayınlanıyor: <https://osmanemrekaya.github.io/stretchescapewebsite/>

| Sayfa | App Store Connect'te |
|---|---|
| `index.html` | Marketing URL |
| `support.html` | Support URL |
| `privacy.html` | Privacy Policy URL |
| `app-ads.txt` | — (AdMob doğrulaması, alan adının kökünden okunur) |

Görseller, bayraklar ve Baloo 2 fontu oyunun kendi varlıklarından kopyalandı;
site oyunla aynı görünsün diye. Kaynakları oyun deposunda duruyor.

`.nojekyll` duruyor çünkü Jekyll'e ihtiyaç yok ve alt çizgiyle başlayan
dosyaları atlamasını istemiyoruz.

`app-ads.txt` AdMob'un yayıncı hesabını doğrulaması için duruyor. Tarayıcı onu
yalnızca alan adının kökünden okur, yani `https://osmanemrekaya.github.io/app-ads.txt`
adresinden; bu depo alt dizinde yayınlandığı için dosyanın oradan da servis
edilmesi gerekiyor (`osmanemrekaya.github.io` deposu ya da siteye bağlanacak
kendi alan adı).
