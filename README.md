# ScreenPen

**Ders anlatırken ekranın, PDF’nin ve web sayfalarının üzerine çizim yap.**

ScreenPen, Türkçe arayüzlü bir macOS çizim uygulaması ve Chrome eklentisidir. Kalem, şekiller ve geometri araçlarını aynı panelde toplar.

[![Mac uygulaması](https://img.shields.io/badge/macOS-13%2B-blue)](https://github.com/alls0/screenpen/releases/latest)
[![Apple Silicon](https://img.shields.io/badge/Apple_Silicon-arm64-black)](https://github.com/alls0/screenpen/releases/latest)
[![Sürüm](https://img.shields.io/badge/ScreenPen-0.7.0-007aff)](https://github.com/alls0/screenpen/releases/tag/v0.7.0)

## İndir

| Paket | İndirme |
| --- | --- |
| **Mac uygulaması 0.7.0** — Apple Silicon, macOS 13+ | [ScreenPen Mac paketi](https://github.com/alls0/screenpen/releases/download/v0.7.0/ScreenPen-0.7.0-macOS-arm64.zip) |
| **Chrome eklentisi 1.5.0** | [ScreenPen Chrome paketi](https://github.com/alls0/screenpen/releases/download/v0.7.0/ScreenPen-Chrome-1.5.0.zip) |
| Dosya doğrulama | [SHA-256 değerleri](https://github.com/alls0/screenpen/releases/download/v0.7.0/SHA256SUMS.txt) |

Mac paketi uygulamayı, Chrome eklentisini ve Türkçe kullanım kılavuzunu içerir. Bu hazır Mac sürümü Intel işlemciler için değildir. Uygulama yerel ad-hoc imzalıdır; Apple Developer ID ve notarizasyon onayı içermez.

**[Kullanım kılavuzu](KULLANIM-KILAVUZU.md)** · **[Tüm sürümler](https://github.com/alls0/screenpen/releases)**

## Özellikler

- **Çizim:** Kalem uçları, renk ve kalınlık seçimi; çizgi, ok ve şekiller; taşıma, silgi ve geri al/yinele.
- **PDF:** Üstteki PDF aç kartı, alt alta kaydırma veya yan yana iki sayfa, yakınlaştırma ve sayfa numarasıyla gezinme. Çizimler sayfaya bağlı kalır; her sayfanın geçmişi ayrıdır.
- **Geometri:** Pergel, cetvel, gönye ve üç noktayla açıölçer.
- **Cetvel — Ölç / Çiz:** Çiz modunda yeni çizgi ekle; Ölç modunda mevcut düz çizginin uçları arasında sürükleyerek yalnızca uzunluğu ölç.
- **Ölçü yazıları:** İsteğe bağlı olarak uzunluk, yarıçap veya açı değerini çizime ekle. cm için ekran boyutunu ayarla ve fiziksel cetvelle kontrol et.
- **Kayıt:** Çizimli PDF kopyası ve büyütülmüş çalışmayı PNG olarak kaydet.
- **Klavye ve tablet:** Araç kısayollarını tablet sürücüsünden kalem/tablet düğmelerine ata.
- **Chrome:** Web sayfasına çiz; Chrome sekmesi veya pencere paylaşımında çizimleri göster.

## Mac kurulumu

1. Mac paketini indir ve ZIP’i aç.
2. `ScreenPen.app` dosyasını Uygulamalar klasörüne taşıyıp aç.
3. Başka uygulama üzerine çizmek için **Pencere seç** ile hedef pencereyi seç. PDF için panelin üstündeki **PDF aç** kartını kullan.
4. **Kalem** ile çiz; **Fare** veya **Esc** ile alttaki uygulamayı kullan.

**☰** ayarları, **?** çevrimdışı kılavuzu açar. **×** yalnızca paneli gizler. Menü çubuğundaki ScreenPen simgesinden **Araçları göster** ile yeniden açabilirsin.

Güncellemeden önce çizimlerini kaydet ve eski ScreenPen’i kapat. Ardından yeni uygulamayı aç.

## Chrome kurulumu

1. Chrome paketini indir ve ZIP’i kalıcı bir klasöre çıkar.
2. `chrome://extensions` adresinde **Geliştirici modu**nu aç.
3. **Paketlenmemiş öğe yükle** ile `ChromeExtension` klasörünü seç.
4. Normal bir web sayfasında eklenti simgesine tıkla.

Güncellemede aynı klasördeki dosyaları yenile, eklenti kartındaki **Yenile** düğmesine bas ve web sayfasını yenile. Sayfa yenilenince çizimler silinir; önce kaydet.

Chrome ayarları, Chrome Web Store ve yerleşik PDF görüntüleyicisinde eklenti çalışmaz. PDF için Mac uygulamasını kullan.

## PDF ile çalışma

Belge açıldığında üst çubuktan **Alt alta** veya **Yan yana** seç. Fare tekerleği/trackpad ile sayfaları kaydır. Sayfa numarasını yazıp Enter ile doğrudan git. **+/−**, trackpad kıstırma veya **⌘ + kaydırma** ile yakınlaştır; **Sığdır** görünüm genişliğine döndürür.

**Çizimli PDF kopyası kaydet** kaynak belgeyi değiştirmeden yeni bir PDF oluşturur. Kalıcı çizimler ve ölçü yazıları çıktıya dahil edilir. Cetvelin Ölç modu ve geçici araç kılavuzları kaydedilmez.

## Grafik tablet kısayolları

Mac’te **Ctrl + Option**, Chrome’da **Ctrl + Alt** ile aşağıdaki tuşu kullan. Option, Mac’te Alt tuşunun adıdır.

| Tuş | İşlem |
| --- | --- |
| 1 / 2 / 3 | Kalem / Silgi / Taşı |
| 4 / 5 | Şekil / Lazer |
| 6 / 7 | Cetvel–Çiz / Cetvel–Ölç |
| 8 / 9 / 0 | Pergel / Gönye / Açıölçer |
| V | Fare |
| Z / Y | Geri al / Yinele |
| W | Ölçü yazısını aç / kapat |
| H | Paneli göster |

Tablet sürücüsünde **Klavye kısayolu / Keystroke** seçerek kombinasyonu düğmeye ata. Üst sıra rakamları kullanılır; harfler Q klavye konumuna göredir.

Mac’te başka uygulama odaktayken kısayol kullanmak için **Ayarlar → Tablet kısayollarını tüm uygulamalarda kullan** seçeneğini aç. Chrome eklentisini kullanırken bu seçeneği kapat. Ayrıntılar [kılavuzda](KULLANIM-KILAVUZU.md#klavye-ve-grafik-tablet).

## Ekran paylaşımı

| Çalışma alanı | Paylaşılacak görüntü |
| --- | --- |
| Başka uygulama üzerine Mac ScreenPen ile çizim | Çizim yaptığın ekranın tamamı |
| ScreenPen içinde açılan PDF | ScreenPen PDF penceresi veya tüm ekran |
| Chrome eklentisi | İlgili Chrome sekmesi veya Chrome penceresi |

Paylaşımı görüşme uygulamandan başlat. Mac’te başka uygulamanın yalnızca penceresini paylaşmak çizim katmanını içermeyebilir. Ders öncesinde karşı taraftaki görüntüyü kontrol et.

## Notlar

- Mac ve Chrome arasında çizim veya ayar eşitlemesi yoktur.
- Ekrandaki cm ölçüsü baskı boyutundan veya karşı tarafın ekranındaki uzunluktan farklı olabilir.
- Diğer uygulamalar üzerindeki kaydedilmemiş çizimler Mac uygulaması kapanınca; Chrome çizimleri sayfa yenilenince kaybolur.
- Bu depo hazır indirme paketlerini ve kullanım belgelerini içerir.
