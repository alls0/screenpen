# ScreenPen kullanım kılavuzu

Mac uygulaması 0.7.0 · Chrome eklentisi 1.5.0

## Kurulum ve güncelleme

Çalışmanı kaydet ve eski ScreenPen'i menü çubuğundaki kalem simgesinden kapat. Paketteki `ScreenPen.app` dosyasını kullanacağın klasöre taşı ve aç. Mac uygulaması Apple Silicon içindir; macOS 13 veya üzeri gerekir.

Chrome için paketteki `ChromeExtension` klasörünü kalıcı bir yere çıkar. `chrome://extensions` sayfasında Geliştirici modu'nu aç; **Paketlenmemiş öğe yükle** ile bu klasörü seç. Zaten kuruluysa aynı klasörde dosyaları güncelle, eklenti kartındaki Yenile düğmesine bas ve çizim yaptığın sayfayı yenile. Sayfa yenilenince önceki çizimler silinir; önce kaydet.

Uygulamanın içindeki **?** düğmesi çevrimdışı kılavuzu açar. **☰ → Ayarlar** ekran ölçüsü, ölçü yazısı ve tablet kısayollarını içerir. **×** paneli gizler; çizimler kalır. Mac menüsündeki **Araçları göster**, Chrome eklenti simgesi veya **Ctrl+Alt+H** paneli yeniden açar. Kısayol için Mac'te Option, Alt tuşudur; uygulama dışında kullanacaksan aşağıdaki tablet ayarını aç.

## Çizim alanı

Mac panelinin üstünde, pencere seçiminin üzerindeki **PDF aç** kartıyla belge aç. Kart, araç listesini kaydırırken de görünür kalır. Önceki bir PDF açıksa **Son PDF'ye dön** düğmesi aynı yerde görünür. Başka bir uygulamanın üzerine çizmek için **Pencere seç** ile hedef pencereyi seç. Chrome'da normal bir web sayfasındayken eklenti simgesine bas. Kalemle çiz; Fare veya Esc ile alttaki uygulamayı kullan. Taşı çizimin tamamını taşır, Silgi dokunduğu çizimi siler. Geri al ve Yinele çizme, taşıma, silme ve temizlemeyi kapsar. Lazer kısa süreli işaretleme yapar.

Şekil aracında düz çizgi, ok, dikdörtgen, elips ve perspektif şekiller bulunur. Şift kare/daire veya çizgi/ok için 45° açıları sabitler.

## Cetvel: Çiz ve Ölç

**Cetvel → Çiz:** Başlangıçtan bitişe sürükle. Yeni bir çizgi oluşur. Şift açıyı 15° aralıklara sabitler. Ölçü yazısı açıksa uzunluk çizginin üzerinde kalır.

**Cetvel → Ölç:** Mevcut düz çizginin bir ucundan diğerine sürükleyip bırak. Sonuç sonraki ölçüme, araç/mod değişimine veya Esc'ye kadar görünür. İki ucu kendin seçersin; çizgiye otomatik yapışmaz. İki uç arasındaki düz mesafeyi ölçer; eğri çizginin toplam yol uzunluğunu ölçmez. Şift ölçüm uçlarını değiştirmez.

Ölç modu yeni çizgi, kalıcı ölçü etiketi veya geri alma adımı eklemez. **Ölçüyü çizime yaz** açık olsa da yalnızca ölçer. Geçici sonuç PDF/PNG'ye eklenmez. cm ayarı yapılmışsa cm, aksi halde Mac'te pt/px, Chrome'da px gösterir.

## Diğer geometri araçları

- **Pergel:** Merkezden yarıçapı sürükle. 360° daire, diğer yay açıları yay çizer.
- **Gönye:** 30°, 45°, 60° veya 90° seçip sürükle. Çizgi yataya göre seçilen açıda oluşur.
- **Açıölçer:** Önce köşeye, sonra iki kol üzerindeki birer noktaya tıkla. Küçük açı 0–180° olarak gösterilir. Noktalar çizgilere otomatik yapışmaz. Ekran boyutu ayarı gerekmez.

## Ölçüyü çizime yaz

**☰ → Ayarlar → Ölçüyü çizime yaz** başlangıçta kapalıdır; tercihin kaydedilir. Açılınca cetvelin Çiz modunda uzunluk, gönyede uzunluk ve açı, pergelde yarıçap yeni çizimlere eklenir. Açıölçerde üçüncü tıklama dereceyi ve küçük bir yayı ayrı çizim olarak ekler; ölçülen eski çizgilere bağlanmaz.

Yazı ve bağlı olduğu çizim birlikte taşınır, silinir, geri alınır ve PDF/PNG'ye kaydedilir. Seçeneği kapatmak eski yazıları silmez. Değer çizildiği anki ölçüdür; yakınlaştırma veya cm ayarı sonradan değişince yeniden hesaplanmaz.

## Gerçek santimetre ayarı

**☰ → Ayarlar → Santimetre cetveli** bölümüne gir. Mac fiziksel ekran boyutunu okuyabiliyorsa cm otomatik etkinleşir. Bilgi yoksa veya Chrome kullanıyorsan ekran köşegenini inç olarak girip **Uygula**'ya bas. Örneğin `13,3`. Çözünürlük (`1920 × 1080` gibi) inç boyutu değildir.

Mac'te  → Bu Mac Hakkında ile modelini bul; modelin teknik özelliklerinden ekran köşegenini öğren. Windows'ta Ayarlar → Sistem → Ekran → Gelişmiş ekran bölümünden doğru monitörün modelini bulup üreticinin teknik özelliklerini kontrol et. Sistem her zaman inç değerini göstermez. Alternatif olarak ışık veren alanın köşegenini cm ile ölçüp 2,54'e böl; çerçeveyi dahil etme.

5 cm kontrol çizgisini fiziksel cetvelle karşılaştır. Çizgiler kısa kalıyorsa İnce ayar yüzdesini artır; uzunsa azalt. Monitör veya sistem ölçeği değişince tekrar kontrol et. Ölçü kendi ekranındaki fiziksel uzunluktur; baskı boyutu veya karşı tarafın ekranındaki uzunluk farklı olabilir. Cetveli tek monitör içinde kullan.

## Klavye ve grafik tablet

Mac'te **Ctrl + Option (⌃⌥)**, Chrome'da **Ctrl + Alt** ile aşağıdaki tuşu birlikte kullan. Mac'te Option, Alt tuşudur. Üst sıradaki rakamlar kullanılır; sayısal tuş takımı kullanılmaz. Harfler Q klavye konumuna göredir.

| Tuş | İşlem |
| --- | --- |
| Ctrl + Alt + 1 | Kalem |
| Ctrl + Alt + 2 | Silgi |
| Ctrl + Alt + 3 | Taşı |
| Ctrl + Alt + 4 | Şekil |
| Ctrl + Alt + 5 | Lazer |
| Ctrl + Alt + 6 | Cetvel · Çiz |
| Ctrl + Alt + 7 | Cetvel · Ölç |
| Ctrl + Alt + 8 | Pergel |
| Ctrl + Alt + 9 | Gönye |
| Ctrl + Alt + 0 | Açıölçer |
| Ctrl + Alt + V | Fare |
| Ctrl + Alt + Z | Geri al |
| Ctrl + Alt + Y | Yinele |
| Ctrl + Alt + W | Ölçü yazısını aç / kapat |
| Ctrl + Alt + H | Paneli göster |

### Tablet düğmelerine atama

1. Tabletinin sürücü uygulamasını aç.
2. Kalem düğmesini veya tablet üzerindeki tuşu seç.
3. **Klavye kısayolu / Keystroke** eylemini seçip kombinasyonu kaydet. Örneğin bir düğmeye Ctrl+Alt+1, diğerine Ctrl+Alt+2 atayabilirsin.
4. Tek basışta kısayol gönderimini kullan; tekrar/makro modunu kapat.
5. Uygulama profili kullanıyorsan ScreenPen veya Chrome'u seç. Başka uygulamaların üzerine çiziyorsan o uygulamaya da aynı atamayı yap veya genel profili kullan.

Tablet düğmeleri ScreenPen içinden değil, tablet sürücüsünden atanır. ScreenPen klavye kısayolunu alır ve ilgili aracı seçer; paneldeki seçim de güncellenir.

### Kısayolların çalışma alanı

Mac'te ScreenPen çizim alanı veya paneli odaktayken çalışırlar. Fare modunda başka bir uygulama odaktayken de araç seçmek için **☰ → Ayarlar → Tablet kısayollarını tüm uygulamalarda kullan** seçeneğini aç. Bu tercih kaydedilir; başlangıçta kapalıdır. Kaydedilemeyen kısayollar Ayarlar'da belirtilir.

**Chrome eklentisini kullanırken Mac'teki bu seçeneği kapat.** Aksi halde kombinasyonu Mac uygulaması yakalayabilir. Eklenti kısayolları etkin web sayfasında çalışır; Chrome adres çubuğunda, alt çerçevelerde veya başka uygulamalarda çalışmaz.

Metin girişlerinde, ayar/kılavuz açıkken ve alan seçimi sırasında araç kısayolları uygulanmaz. Mac'in tüm uygulamalarda kısayol seçeneği açıksa, başka uygulamalarda da bu kombinasyonlar ScreenPen'e ayrılır. Çakışan sistem veya uygulama kısayollarını kontrol et. Eklenti AltGr metin girişini kısayol saymaz. Bir tuşu basılı tutmak işlemi tekrar etmez.

Diğer kısayollar: **Esc** fareye döner; **⌘Z / ⇧⌘Z** geri alır/yineler (Chrome Windows/Linux'ta Ctrl). Eklentide seçili çizim **Delete/Backspace** ile silinir.

## PDF ve kayıt

Mac'te **PDF aç** ile belgeyi seç. PDF üst çubuğundan **Alt alta** veya **Yan yana** düzenini seç; sayfaları aşağı kaydırarak gez. Sayfa numarası + Enter ile doğrudan istediğin sayfaya git. +/−, trackpad kıstırma veya ⌘ ile kaydırma yakınlaştırır. Fare modunda sürükleyerek gezin. **Sığdır** seçilen düzeni görünümün genişliğine sığdırır. Çizdiğin sayfa etkinleşir; çizimler ve geri alma geçmişi her sayfada ayrı korunur. ⌘+/⌘− yakınlaştırır, ⌘0 sığdırır, Page Up/Page Down sayfa değiştirir.

**Çizimli PDF kopyası kaydet** yeni bir dosya oluşturur; çizimler ve kalıcı ölçü yazıları sayfaya birleştirilir. Kaynak PDF değişmez. Geçici araç kılavuzları ve cetvelin Ölç sonucu kaydedilmez. Bu görünüm metin seçme ve form doldurma sunmaz.

**Alan seç ve büyüt** ile sabit bir ekran bölgesini alıp üzerinde çalışabilirsin. Mac ilk kullanımda Ekran Kaydı izni isteyebilir. Çalışmayı PNG olarak kaydet. Chrome'da **PNG kaydet** büyütülmüş çalışmayı kaydeder. Diğer uygulamaların üstündeki Mac çizimleri belgeye yazılmaz ve uygulama kapanınca kaybolur.

## Ekran paylaşımı

Akıllı Kütüphane gibi başka uygulamaların üstüne Mac ScreenPen ile çiziyorsan görüşme uygulamasından **ekranın tamamını** paylaş. Yalnızca hedef pencereyi paylaşmak çizim katmanını içermeyebilir. PDF ScreenPen içinde açıksa ScreenPen PDF penceresi paylaşılabilir. Chrome eklentisinde ilgili sekme veya Chrome penceresi paylaşılabilir. Paylaşımı görüşme uygulamasından başlat ve ders öncesi karşı taraftan kontrol et.

Chrome ayarları, Chrome Web Store ve yerleşik PDF görüntüleyicisi eklentiyi desteklemez. PDF için Mac uygulamasını kullan. Mac ve eklenti arasında çizim veya ayar eşitlemesi yoktur.
