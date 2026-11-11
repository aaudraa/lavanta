# ✦ lavanta

Tarayıcıda çalışan, tek sayfalık ASCII animasyonu: bir göz açılır, göz kırpar, gözbebeğinin içinden yıldızlı uzaya dalınır ve orada bir lavanta buketi açar.

- Hiçbir kütüphane yok; her şey `index.html` içinde, karakterler WebGL ile çiziliyor (WebGL yoksa canvas 2D'ye düşer).
- Bilgisayarda yatay, telefonda dikey ekrana kendini uyarlar.
- Müzik `music.m4a` (15 sn), animasyon zamanlaması buna göre ayarlı.

Yerelde denemek için klasörü bir yerel sunucuyla açmak yeterli, örn. `python -m http.server`.

Geliştirme kancaları: `?t=6` animasyonu 6. saniyede dondurur, `?nogl` canvas 2D yolunu zorlar, `?bench` kare sürelerini ölçer.
