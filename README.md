# Kolonoskopi Hazırlık Uygulaması

**Doç. Dr. Cem Şimşek — Gastroenteroloji**

Kolonoskopi öncesi hasta hazırlık rehberi. Web tabanlı, tek dosya, backend gerektirmez.

## Özellikler

- 📱 **Mobil öncelikli tasarım** — PWA olarak ana ekrana eklenebilir
- 📊 **Geri sayım** — İşleme kalan gün + günlük görev listesi
- 🥗 **Türk mutfağı diyet rehberi** — Gün gün ne yenmeli, nelerden kaçınılmalı
- 💊 **4 ilaç protokolü** — Pegdin (PEG 2L), Picoprep, Fortrans (PEG 4L), Fleet Fosfo-Soda
- 📈 **Dışkı takibi** — 5 seviyeli görsel skala + anlık feedback
- ✅ **İnteraktif kontrol listesi** — 15 maddelik hazırlık checklist'i
- ⚠️ **İlaç uyarıları** — GLP-1, kan sulandırıcı, diyabet, demir
- 🔴 **Acil durum** — 112 tek tuşla arama

## Kullanım

`index.html` dosyasını herhangi bir web sunucusuna yükleyin veya doğrudan tarayıcıda açın.

```
# Lokal test
open index.html

# veya basit sunucu
python3 -m http.server 8080
```

## Teknik

- Tek HTML dosyası — harici bağımlılık yok
- Vanilla JS + CSS — framework gerektirmez
- `localStorage` ile veri saklama (sunucu tarafı yok)
- Responsive tasarım (iPhone / Android uyumlu)
- Hacettepe bordeaux (#C8102E) renk teması

## Tasarım

Editorial/magazine-quality estetik: Georgia serif tipografi, Hacettepe Üniversitesi bordeaux aksanı, temiz beyaz arka plan, ince çizgiler.

## Lisans

© 2025 Doç. Dr. Cem Şimşek. Tüm hakları saklıdır.
