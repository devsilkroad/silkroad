# Personel Yaka Kartı (9×13 cm)

Kobaküs Ödeme Hizmetleri A.Ş. için dikey personel kimlik kartı tasarımı.

## Dosyalar
- `yaka-karti.html` — Düzenlenebilir kaynak. Ad/soyad, görev ve sicil no buradan değiştirilir.
- `yaka-karti.png` — 300 DPI önizleme/baskı görseli.
- `yaka-karti.pdf` — Tam 9×13 cm baskıya hazır PDF.

## Yapı
- Üst: Kobaküs logosu (wordmark + simge)
- Orta: Yeşil bantta "Kobaküs Ödeme Hizmetleri A.Ş."
- Alt: Personel fotoğrafı, adı, görevi ve sicil numarası

## Marka
- Kurumsal yeşil: `#1AA662` (Brandfetch'ten alınan resmi marka rengi)

## ÖNEMLİ — Logo notu
Resmi logo dosyası `kobakus.com` adresinden indirilemedi (oturumun ağ
politikası bu alan adına erişimi engelliyor). Karttaki logo, marka yeşili
kullanılarak yeniden oluşturulmuş bir temsilî wordmark'tır. Resmi `.svg`/`.png`
logo dosyası elde edilince `yaka-karti.html` içindeki `.logo` bölümündeki SVG
ile değiştirilmelidir.

## Yeniden render
HTML'i bir tarayıcıda açıp yazdırın veya Chromium/Playwright ile PNG/PDF
üretin (9cm × 13cm, kenar boşluğu 0, arka plan açık).
