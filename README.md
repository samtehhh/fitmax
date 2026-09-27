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

**2026-09-27:** Android (Google Play) bölümleri 7 dilde gizlilik, şartlar,
destek ve silme sayfalarına **elle** eklendi; üretici bu metni bilmiyor
(ve artık çalışma alanında da yok). Yeniden üretim yapılırsa Android
bölümleri kaybolur, önce üreticiye taşınmalı.

## Play yayını öncesi

- Play geliştirici adı sayfalarda geçmiyor (2026-09-27): Google Play
  tarafı "Google Play'de de mevcut" / "Google Play'deki yayıncı" diye
  anılıyor, "biz" = yüklenen sürümün yayıncısı. Play'deki geliştirici adı
  sayfalara yazılmak istenirse 7 dilde gizlilik (giriş, Android bölümü,
  İletişim), şartlar (kapsam, sorumluluk), silme ve destek Android
  bölümleri elle güncellenir.
- Play Console'da gizlilik politikası adresi `/privacy/`, veri güvenliği
  formundaki silme adresi `/delete/`. Politika metni Data safety beyanıyla
  (`fitmax-android/docs/PLAY_KONSOL_HAZIRLIK.md` §2.7) çelişmemeli; biri
  değişirse öbürü aynı gün güncellenir.
