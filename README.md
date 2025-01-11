# Uzay Savaşı Oyun Projesi - README

Bu doküman, "Uzay Savaşı" isimli basit bir tarayıcı tabanlı oyunun geliştirilmesi ve kullanımıyla ilgili detaylı bilgiler sunar.

---

## Oyun Tanımı
"Uzay Savaşı", kullanıcının bir uzay gemisi kahramanı kontrol ederek düşmanlarla savaştığı ve mermilerle düşman gemilerini vurduğu bir tarayıcı oyunudur. Oyuncu, dokunmatik ekran veya fare ile kahramanı hareket ettirebilir ve ateş edebilir. Düşmanlar, rastgele pozisyonlarda belirir ve bazen kahramana doğru mermi atar.

---

## Oyun Gereksinimleri
- Modern bir web tarayıcı (Google Chrome, Mozilla Firefox, Safari, Edge, vb.)
- HTML5 ve JavaScript desteği
- Mobil veya masaü;stü cihazların dokunmatik veya fare girdisi

---

## Dosya Yapısı
- **index.html**: Oyunun ana yapısını ve tüm kodları barındırır.
- **CSS**: Oyun için görsel tasarım ve animasyonlar CSS stilleri ile tanımlanmıştır.
- **JavaScript**: Oyunun temel mantığı ve dinamik davranışlar JavaScript ile sağlanmıştır.

---

## Oyun Bileşenleri

### Kahraman (Uzay Gemisi)
- Oyuncu tarafından kontrol edilir.
- Fare veya dokunmatik ekran ile hareket ettirilebilir.
- Otomatik olarak mermiler atarak düşmanlara zarar verir.

### Düşmanlar
- Ekranda rastgele pozisyonlarda belirir ve aşağı hareket eder.
- Bazen kahramana doğru mermi ateş eder.
- Kahraman mermileri ile öldürüldüğünde kaybolur.

### Can Barı
- Kahraman ve düşman gemileri, mevcut can durumlarını yansıtan bir can barına sahiptir.
- Kahramanın canı sıfıra düşerse oyun sona erer.

### Kullanıcı Ekranları
1. **Başlat Ekranı**: Oyuna başlamak için bir buton bulunur.
2. **İsim Ekranı**: Oyuncu adı girişi yapılır.
3. **Oyun Bitti Ekranı**: Oyun sona erdiğinde oyuncunun durumu görülür ve yeniden başlatma seçeneği sunulur.

---

## Kullanım Talimatları
1. **Oyunu Başlatın**: Ana ekrandaki "BAŞLAT" butonuna tıklayarak oyuna başlayın.
2. **Adınızı Girin**: İsim ekranında adınızı girip "OYNA" butonuna basın.
3. **Kahramanı Kontrol Edin**:
    - **Fare ile**: Fareyi hareket ettirerek kahraman gemisini hareket ettirin.
    - **Dokunmatik**: Ekranda bir yeri dokunarak kahraman gemisini o noktaya taşıyın.
4. **Ateş Edin**: Gemiyi hareket ettirdiğiniz sürece kahraman otomatik olarak ateş edecektir.
5. **Düşmanlardan Kaçın**: Düşman mermilerine çarpmamaya çalışın ve can barınızı koruyun.
6. **Oyunu Yeniden Başlatın**: "OYUN BİTTİ" ekranından "TEKRAR OYNA" butonuna tıklayarak oyunu yeniden başlatın.

---

## Özelleştirme
- **Kahraman ve Düşman Tasarımı**: HTML ve CSS kullanarak gemilerin tasarımlarını özelleştirin.
- **Hareket Hızı**: JavaScript kısmında "hiz" değerlerini değiştirerek kahraman veya düşman hızını arttırın veya azaltın.
- **Can Sayıları**: Kahraman ve düşmanların can değerlerini değiştirerek oyunun zorluğunu ayarlayabilirsiniz.

---

## Bilinen Sorunlar
- Tarayıcı desteği kısıtlamaları nedeniyle "screen.orientation.lock" bazı cihazlarda çalışmayabilir.
- Oyun performansı, cihaz donanımına bağlı olarak değişiklik gösterebilir.

---

## Geliştirici Notları
Bu oyun, basit bir tarayıcı tabanlı proje olarak tasarlanmıştır. Daha karmaşık özellikler ve eklemeler yapılması durumunda oyun performansını optimize etmek gerekebilir. Katkılarınızı ve önerilerinizi bekliyoruz!
