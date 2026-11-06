# Referans · Callback vs Higher-Order · Arrow

**Code2Work Full Stack — Canlı Ders**
📅 5 Kasım 2026
🎥 Ders kaydı: [vimeo.com/1243839373](https://vimeo.com/1243839373)

---

## Bu Derste Neler İşledik?

### Bölüm 1 — Referans (Modül 1)
- Basit türler **fotokopi** gibi kopyalanır (`let b = a`)
- Dizi ve objeler **etiket** gibidir: `sepet2 = sepet1` yeni dizi oluşturmaz, ikisi aynı diziyi gösterir
- Gerçek kopya: `[...sepet1]`

### Bölüm 2 — Fonksiyon da bir değer
- `selamla` (tarif) vs `selamla()` (yemek)
- `setTimeout(fn, 2000)` ile `setTimeout(fn(), 2000)` farkı

### Bölüm 3 — Callback vs Higher-Order Function
- `sayilar.filter(ondanBuyukMu)` → fonksiyonu **alan** higher-order, **verilen** callback
- Kendi higher-order fonksiyonumuz: `ikiKereYap(alkis)`

### Bölüm 4 — Arrow Function
- Klasik → anonim → arrow → tek satır
- Kontrol listesi: `=`, isim, `function` kelimesi, `{}` + `return`

### Bölüm 5 — reduce
- `reduce` adım adım: `toplam` ve `yeni` her adımda nasıl değişiyor
- reduce de bir higher-order fonksiyon

---

## Dosyalar

| Dosya | İçerik |
|-------|--------|
| `ornekler.html` | 12 çalıştırılabilir örnek — tarayıcıda aç, her örnekte **▶ Çalıştır**'a bas |

Kurulum gerekmez: `ornekler.html` dosyasını çift tıklayıp tarayıcıda açman yeterli.
