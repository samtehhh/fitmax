# FitMax — legal pages

FitMax uygulamasının gizlilik politikası, kullanım şartları, destek ve veri
silme sayfaları. 7 dil (en, tr, de, fr, es, pt, ar), statik HTML, derleme yok.

## Yayına alma (tek seferlik, depo sahibi yapar)

**Settings → Pages → Build and deployment → Source: "Deploy from a branch"
→ Branch: `main`, klasör `/ (root)` → Save.**

Bir iki dakika sonra adresler:

- https://samtehhh.github.io/fitmax/
- https://samtehhh.github.io/fitmax/privacy/ · `/terms/` · `/support/` · `/delete/`
- diller: `/tr/privacy/`, `/de/terms/`, `/fr/support/`, `/es/`, `/pt/`, `/ar/`

Bu adresler App Store Connect'te gizlilik politikası, destek ve pazarlama
adresi olarak kayıtlı ve uygulamanın içinden (paywall, Ayarlar) açılıyor.
**Pages açılmadan uygulama incelemeye gönderilmemeli** — ölü bağlantı
App Review'da ret sebebi (Guideline 3.1.2).

## İçerik nasıl güncellenir

Sayfalar FitMax metin paketlerinden üretiliyor; kaynak üretici
`scratchpad/site-render/build-site.py` (FitnessAI-Swift çalışma alanı).
Elle düzenleme yapılacaksa doğrudan `index.html` dosyaları değiştirilebilir.
