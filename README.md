# Tuana Sanat Kulübü

Tuana Sanat Kulübü'nün web sitesi (tek sayfa, düz HTML/CSS/JS).

- Adres: https://tuanasanatkulubu.com (GitHub Pages, HTTPS zorunlu; DNS Netlify'da)
- Ana dosya: `index.html`, görseller `img/` klasöründe.
- Bilet sitesi ayrı: https://bilet.tuanasanatkulubu.com

Alan adı 17 Ekim 2026'da bu siteye bağlandı; ana sayfadan `noindex` kaldırıldı. `alternatif/` sayfası deneme tasarımı olduğu için `noindex` olarak kalıyor.

`CNAME` dosyası silinmemeli; silinirse alan adı bağlantısı kopar.

## İngilizce sayfa
- `en/index.html` Türkçe sayfadan otomatik üretilir (çeviri tablosu ve betik Claude'un çalışma alanında). Türkçe sayfada metin değişirse İngilizce sayfa da yeniden üretilmeli; doğrudan elle düzenlenmemeli.
- İngilizce logo: `img/logo-beyaz-en.png` (TUANA ART CLUB).

## Silinmemesi gereken dosyalar
- `CNAME`: alan adı bağlantısı.
- `googled238a960b5af2fbb.html`: Google Search Console sahiplik doğrulaması.
- `sitemap.xml`, `robots.txt`: arama motorları için.
