# Apple Tarzı Kullanma Kılavuzu Tasarım Rehberi

Aşağıdaki öneriler, iş yerinizde hazırladığınız kılavuzu Apple dokümantasyonu tadında, temiz ve kullanıcı dostu bir stile kavuşturmak için pratik bir yol haritası sunar.

## 1) Yapı ve Hiyerarşi
- **Ön kapak**: Ürün adı, kısa slogan ve temiz bir görsel ya da piktogram.
- **Hızlı başlangıç**: 1–2 sayfada kutu içeriği, bağlantı/kurulum adımları ve ilk kullanım.
- **Bölümleme**: Her ana konuyu tek bir amaca odaklayan kısa bölümler (örn. *Kurulum*, *Günlük Kullanım*, *Sorun Giderme*).
- **Özet kutuları**: Bölüm sonlarına "Bunu hatırla" veya "İpucu" kutuları ekleyin.
- **Teknik özellikler**: Arka sayfalarda tablo halinde; kullanıcı akışını bölmeyecek şekilde konumlandırın.

## 2) Dil ve Ton
- **Basit, net, yargısız**: Komut vermez; rehberlik eder. Örn. “Şunu yap” yerine “Şu şekilde yapabilirsiniz”.
- **Aktif cümleler**: "Cihaz açılır" yerine "Cihazı açın".
- **Kısa adımlar**: Her madde tek eylem; 5–7 kelimeyi aşmamaya çalışın.
- **Terim tutarlılığı**: Aynı kavram için hep aynı terimi kullanın (ör. “güç düğmesi” her yerde aynı kalsın).

## 3) Görsel Stil
- **Bol beyaz alan**: Satır aralığı 1.4–1.6; paragraflar arası nefes payı.
- **Tipografi**: Sans serif, açık ve modern (örn. SF Pro yoksa Inter, Roboto, Helvetica Neue). Başlık-kapak için kalın; gövde için normal ağırlık.
- **Renk paleti**: Ana renk + 1 vurgu + nötr gri tonları. Doygunluğu düşük, pastel tonlar.
- **İkonografi**: İnce çizgili, düz ikonlar. Aynı seti kullanın; stil karışıklığından kaçının.
- **Ekran/cihaz görselleri**: Gerçekçi ama abartısız; arayüz ekranlarını hizalı ve temiz tutun.

## 4) Sayfa Düzeni
- **Kılavuz ızgarası**: 8–12 kolonlu grid; kenar boşluklarını geniş tutun.
- **Başlık hiyerarşisi**: H1 için 24–28 pt, H2 için 18–22 pt, gövde için 11–12 pt.
- **Listeler**: Numaralı adımların yanında küçük daireler veya ince çizgi ikonları; gereksiz alt seviye listelemelerden kaçının.
- **İpucu kutuları**: Sol kenarda renkli şerit + açık renk arka plan; kısa metinler.
- **Uyarılar**: Üç seviye kullanın: Bilgi (mavi), Uyarı (sarı), Tehlike (kırmızı). Her biri için tutarlı ikon.

## 5) İçerik Akışı Örneği
1. **Kutu içeriği**: Parçaların isimli fotoğrafı + kısa tablo.
2. **Kurulum**: 4–6 adımda görselli hızlı başlangıç.
3. **Bağlantı**: Wi‑Fi/Bluetooth/USB eşleştirme akışı; ekran görüntüleri.
4. **Günlük kullanım**: En sık yapılan 3–5 senaryo için kısa akış.
5. **Bakım**: Temizlik, pil, yazılım güncelleme.
6. **Sorun giderme**: 5–10 yaygın sorun için tablo (Belirti / Olası Neden / Çözüm).
7. **Güvenlik ve yasal**: En sona, sade ve okunabilir tipografiyle.

## 6) Yazım ve Terminoloji Örnekleri
- "Dokunun" / "Seçin" / "Basın" gibi tutarlı eylem fiilleri.
- "Ayarlar > Bluetooth" gibi yol gösterirken ok işaretleri veya " > " ayırıcı kullanın.
- Düğme isimlerini *bold*, menü yollarını `monospace` ile yazın.

## 7) Görsel Şablon Önerisi
- **Kapak**: Büyük boşluk + tek renk arka plan + ürün silüeti.
- **İç sayfa**: Sol tarafta ince kenar boşluğu, sağ tarafta geniş açıklama alanı.
- **İkili kolon**: Solda adım numarası ve ikon, sağda kısa açıklama.
- **Ekran görüntüsü çerçevesi**: Köşeleri hafif yuvarlatılmış, ince gri kontur.

## 8) Dosya ve İhracat
- Kaynak dosya: Figma/Sketch/InDesign. Bileşenleri ve stilleri tanımlı tutun.
- Çıkış: İnteraktif PDF + baskı dostu PDF. Erişilebilirlik için metin seçimli ve alternatif metin ekli.

## 9) Kontrol Listesi
- [ ] Bölüm başlıkları sade ve tutarlı.
- [ ] Her adım tek eylem içeriyor.
- [ ] Görseller hizalı, aynı stil ikon seti kullanılmış.
- [ ] Renk paleti 3 ana tona sınırlı.
- [ ] Uyarı ve ipucu kutuları tutarlı biçimde kullanılmış.
- [ ] Yazım dili sade, aktif ve nazik.

## 10) Şablon Başlangıcı (Markdown)
Aşağıdaki yapıyı kendi içeriklerinize uyarlayarak kullanabilirsiniz:

```markdown
# [Ürün Adı] — Kullanma Kılavuzu

## Hızlı Başlangıç
1. [Adım]
2. [Adım]
3. [Adım]

## Kurulum
1. [Adım]
2. [Adım]
3. [Adım]

## Günlük Kullanım
- [Senaryo 1]
- [Senaryo 2]
- [Senaryo 3]

## Sorun Giderme
| Belirti | Olası Neden | Çözüm |
| --- | --- | --- |
|  |  |  |

## Güvenlik ve Yasal
- [Madde]
```

Bu rehberi temel alarak içeriklerinizi sadeleştirip Apple benzeri, tutarlı ve kullanıcı dostu bir kılavuz oluşturabilirsiniz.
