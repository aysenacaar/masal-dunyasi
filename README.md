# Masal Dünyası

## Proje Hakkında

Masal Dünyası, Türk masallarını dijital ortamda bir araya getirmek amacıyla hazırlanmış etkileşimli bir web sitesidir.

Bu proje, İstanbul Medipol Üniversitesi Görsel İletişim Tasarımı Bölümü, Programlamaya Giriş dersi kapsamında hazırlanmıştır.

Projenin amacı, geleneksel masalları modern ve kullanıcı dostu bir arayüzle sunarak dijital ortamda erişilebilir hâle getirmektir.

## Web Sitesinin Özellikleri

- 10 farklı masal içeriği
- Masal adına göre arama yapabilme
- Masalları favorilere ekleme ve favorilerden çıkarma
- Yalnızca favori masalları görüntüleme
- Masalları açıp okuma ve kapatma
- Favorilerin tarayıcının yerel depolama alanında (localStorage) saklanması
- Bilgisayar ve telefon ekranlarına uyumlu (responsive) tasarım
- Pastel renkler ve masal temalı görsel arayüz

## Kullanılan Teknolojiler

**HTML5:** Web sitesinin sayfa yapısını, masal kartlarını, başlıklarını ve içeriklerini oluşturmak için kullanılmıştır.

**CSS3:** Web sitesinin renkleri, yazı tipleri, kart tasarımları, butonları ve mobil uyumluluğu için kullanılmıştır. CSS kodları `style.css` adlı harici dosyada bulunmaktadır.

**JavaScript:** Masal arama, favorilere ekleme, favorileri filtreleme ve masal okuma özellikleri için kullanılmıştır. JavaScript kodları `script.js` adlı harici dosyada bulunmaktadır.

**localStorage:** Kullanıcının favori masallarını tarayıcıda saklamak için kullanılmıştır.

## Proje Dosya Yapısı

```text
masal-dunyasi/
│
├── index.html
├── style.css
├── script.js
├── README.md
├── görseller/
│   └── Masallara ait görseller
└── latex-rapor/
    └── Vize raporu kaynak dosyaları
```

- `index.html`: Web sitesinin HTML yapısını ve içeriklerini barındırır.
- `style.css`: Tüm tasarım ve görsel biçimlendirme kodlarını içerir.
- `script.js`: Etkileşimli özellikleri ve masal metinlerini içerir.
- `görseller/`: Masal kartlarında kullanılan görselleri içerir.
- `latex-rapor/`: Vize projesinin LaTeX rapor kaynaklarını içerir.

## Harici CSS ve JavaScript Kullanımı

Vize projesinin ilk sürümünde HTML, CSS ve JavaScript kodları tek bir `index.html` dosyasında bulunmaktaydı.

Yeni ödev kapsamında bu yapı üç ayrı dosyaya dönüştürülmüştür.

CSS kodları `style.css`, JavaScript kodları ise `script.js` dosyasına taşınmıştır. Bu dosyalar HTML sayfasına harici dosya bağlantılarıyla eklenmiştir.

Bu düzenleme sayesinde kodların okunabilirliği, düzenlenebilirliği ve sürdürülebilirliği artırılmıştır.

Projenin mevcut tasarımı ve etkileşimli özellikleri korunmuştur.

## Proje Nasıl Çalıştırılır?

1. GitHub üzerinden proje dosyalarını indirin.
2. `index.html`, `style.css` ve `script.js` dosyalarının aynı klasörde bulunduğundan emin olun.
3. `görseller` klasörünü mevcut konumunda tutun.
4. `index.html` dosyasını Safari, Google Chrome veya başka bir internet tarayıcısında açın.
5. Masalları inceleyin, arama yapın ve favori özelliklerini kullanın.

## Web Sitesi

https://aysenacaar.github.io/masal-dunyasi/

## GitHub Proje Bağlantısı

https://github.com/aysenacaar/masal-dunyasi

## Sunum Videosu

https://youtu.be/NXXDDQcXguQ

## Yapay Zekâ Kullanımı

Projenin geliştirilmesi sırasında ChatGPT'den kodların düzenlenmesi, HTML, CSS ve JavaScript dosyalarının ayrılması ve teknik sorunların çözülmesi konularında destek alınmıştır.

## Hazırlayan

**Ayşenur Naçar**

Öğrenci Numarası: 86220039

İstanbul Medipol Üniversitesi

Görsel İletişim Tasarımı Bölümü

Programlamaya Giriş Dersi
