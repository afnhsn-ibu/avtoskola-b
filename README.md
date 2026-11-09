# Makedonya Ehliyet Sınavı Soruları — Türkçe Açıklamalı (B Kategorisi)

**▶ Online çalış: https://afnhsn-ibu.github.io/avtoskola-b/**

Kuzey Makedonya sürücü belgesi (ehliyet) teorik sınavına **Türkçe** hazırlanmak
isteyenler için ücretsiz deneme sınavı: 40 test, 621 soru, doğru cevaplar ve her
soru için Türkçe açıklama. Üyelik yok, telefonda da çalışır.

*Авто-тест Б категорија · возачки испит · Avtoškola B test Türkçe*

---

Kuzey Makedonya B kategorisi sürücü belgesi teorik sınavının **40 testinin tamamı**
— 621 soru, hepsi cevaplı — tek bir HTML sayfasında. Kurulum yok, hesap yok,
internet gerekmez.

**Demo:** https://afnhsn-ibu.github.io/avtoskola-b/ — veya `index.html` dosyasını tarayıcıda açın.

## İçerik

| | |
|---|---|
| Test | 40 / 40 (test başına 31 soru, 1240 soru yuvası) |
| Benzersiz soru | 621 — 406 görselli, 215 görselsiz |
| Cevap | 621 / 621 |
| Görsel | 531 |

Konu sekmeleri: levha adı, ek tabela, levha grubu, levha yorumu,
polis/ışık/gösterge, kavşakta öncelik, geçiş sırası, güzergâh A→B,
yolda durum, görselsiz sorular.

## Özellikler

- **Üç kip.** *Atlas* (doğru şık yeşil), *Sınav* (şıkka tıkla, anında doğru/yanlış),
  *Anahtar* (cevabı kendin işaretle).
- **Türkçe açıklama.** Her sorunun altında ne sorulduğunu anlatan bir not, her
  Makedonca şıkkın altında Türkçe karşılığı. Tek kutucukla kapanır — Kiril metin
  hiç değişmez.
- **Test sırası.** Açılır listeden bir test seçince o testin 31 sorusu sitedeki
  sırayla gelir.
- **Varyant bağlantıları.** Aynı Makedonca cümleyi paylaşan kartları yan yana
  gösterir — tuzakların çoğu burada.
- **İlerleme.** "Öğrendim" işaretleri tarayıcıda saklanır.

## Yapı

```
index.html      tek dosya: sorular, cevaplar, çeviriler, arayüz
images/         531 görsel
.nojekyll       GitHub Pages'in klasörü olduğu gibi sunması için
```

`index.html` görselleri `./images/` klasöründen okur. Görselleri dosyanın
**içine** gömmek isterseniz (tek dosya, tamamen taşınabilir), sayfadaki
`IMGDATA` tablosu bunun içindir.

## GitHub Pages ile yayınlamak

1. Yeni bir depo oluşturun ve bu klasörün içeriğini yükleyin.
2. Settings → Pages → Source: `main` / `root`.
3. Birkaç dakika sonra `https://<kullanıcı>.github.io/<depo>/` adresinde yayında.

## Kaynaklar ve haklar

- **Sorular:** Kuzey Makedonya İçişleri Bakanlığı'nın resmî teorik sınav soru
  bankası (arhiva.mvr.gov.mk). Soru numaralandırması bu projedeki görsel
  numaralarıyla birebir aynıdır.
- **Görseller ve test düzeni:** avtoskolaonline.mk üzerinden derlenmiştir.
  Görseller bu depoda yeniden barındırılmaktadır; telif hakkı asıl sahibine
  aittir. Hak sahibi talep ederse kaldırılmalıdır.
- **Türkçe açıklamalar:** bu proje için yazılmıştır; birebir çeviri değil,
  sorunun ne sorduğunu anlatan açıklamalardır.

Bu bir çalışma yardımcısıdır, resmî bir kaynak değildir. Sınav soruları ve
kurallar değişebilir; şüphede kaldığınızda resmî siteye ve yürürlükteki
*Zakon za bezbednost na soobraḱajot na patishtata*'ya bakın.
