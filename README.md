# Turkish Genocide Map

Bu proje, tarih boyunca Türklerin uğradığı soykırım, katliam, işkence ve suikastları interaktif bir harita üzerinde gösteren web tabanlı bir veri görselleştirme uygulamasıdır.

## 🌟 Özellikler

* **İnteraktif Harita:** Leaflet.js altyapısı ve karanlık tema (CartoDB Dark Matter) ile modern ve amaca uygun görünüm.
* **Dinamik Veri Çekme:** Tüm olaylar dışa aktarılmış `veri.json` dosyasından okunur. Kod tabanına dokunmadan kolayca yeni veri eklenebilir veya güncellenebilir.
* **Kategorize Edilmiş İkonlar:** Soykırım, katliam, işkence ve suikast gibi farklı olay türleri için özelleştirilmiş FontAwesome ikonları.
* **Senkronize Liste Paneli:** Haritadaki işaretçiler (marker) ile yan paneldeki liste birbiriyle entegre çalışır. Listeden bir öğeye tıklandığında harita otomatik olarak o noktaya odaklanır (flyTo animasyonu). Haritadaki popup üzerinden liste detayları açılabilir.
* **Açılış Ekranı (Splash Screen):** Gazi Mustafa Kemal Atatürk'ün *"Tarihini bilmeyen milletler, yok olmaya mahkûmdur."* sözüyle kullanıcıyı karşılayan sinematik giriş ekranı.
* **Responsive Tasarım:** Mobil, tablet ve masaüstü cihazlarla tam uyumlu arayüz.

## 🛠️ Kullanılan Teknolojiler

* **HTML5, CSS3, Vanilla JavaScript**
* **[Leaflet.js](https://leafletjs.com/):** Harita renderlama motoru.
* **[FontAwesome](https://fontawesome.com/):** Vektörel UI ikonları.

## 🚀 Kurulum ve Çalıştırma

Proje, verileri dışarıdan bir `veri.json` dosyasından `fetch` API kullanarak çektiği için, `index.html` dosyasını doğrudan tarayıcıda (çift tıklayarak / `file://` protokolüyle) açtığınızda CORS (Cross-Origin) politikaları gereği veriler yüklenmeyebilir. 

Projeyi sorunsuz çalıştırmak için yerel bir web sunucusuna ihtiyacınız vardır:

1. Repoyu bilgisayarınıza indirin veya klonlayın:
   ```bash
   git clone [https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git](https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git)
