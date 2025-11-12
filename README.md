# KML Birleştirme ve Stil Aracı

Bu web uygulaması, birden fazla KML dosyasını yüklemenize, her biri için çizgi rengi, çizgi kalınlığı, dolgu rengi ve dolgu opaklığı gibi stilleri özelleştirmenize ve ardından tüm dosyaları tek bir KML dosyasında birleştirip indirmenize olanak tanır.

Tüm işlemler sunucuya herhangi bir dosya yüklenmeden, tamamen sizin tarayıcınızda (client-side) gerçekleşir. Bu sayede verileriniz güvende kalır.

## Özellikler

*   Sürükle-bırak veya dosya seçme yoluyla çoklu KML dosyası yükleme.
*   Her KML dosyası için ayrı ayrı stil belirleme:
    *   Çizgi Rengi
    *   Çizgi Kalınlığı
    *   Dolgu Rengi
    *   Dolgu Opaklığı
*   Seçilen KML dosyalarını tek bir dosyada birleştirme.
*   İsteğe bağlı olarak bir çıktı dosyası adı belirleme.
*   Koyu/Açık tema desteği.

## Nasıl Kullanılır?

Bu uygulamayı kullanmak için herhangi bir kurulum yapmanıza gerek yoktur. Sadece `index.html` dosyasını bir web tarayıcısında (Google Chrome, Firefox, vb.) açmanız yeterlidir.

1.  **KML Dosyalarını Seçin:** "Select KML Files" butonuna tıklayarak veya dosyalarınızı sürükleyip bırakarak KML dosyalarınızı yükleyin.
2.  **Stilleri Özelleştirin:** Yüklediğiniz her dosya için istediğiniz renk, kalınlık ve opaklık ayarlarını yapın.
3.  **Dosya Adı Belirleyin (İsteğe Bağlı):** İndirilecek dosya için özel bir isim belirleyebilirsiniz. Boş bırakırsanız, varsayılan olarak `merged.kml` olarak adlandırılacaktır.
4.  **Dosyaları Birleştirin:** "Merge Files" butonuna tıklayın.
5.  **İndirin:** Birleştirilmiş ve stillendirilmiş yeni KML dosyanız tarayıcınız tarafından otomatik olarak indirilecektir.
