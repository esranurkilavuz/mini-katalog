[README.md](https://github.com/user-attachments/files/28277044/README.md)
# Mini Katalog Uygulaması

Bu proje, Flutter temel eğitimi kapsamında geliştirilmiş bir "Mini Katalog Uygulaması"dır. Uygulama, Flutter mimarisinin temel özellikleri olan widget ağacı, sayfalar arası geçiş (navigator), model sınıfı kullanımı ve GridView tabanlı listeleme mantığını pratik etmek amacıyla hazırlanmıştır.

## Özellikler
- **Ana Sayfa (Home Screen):** Mock JSON verilerinden beslenen ürünlerin `GridView` kullanılarak listelenmesi.
- **Detay Sayfası (Detail Screen):** Seçilen ürünün detaylarının gösterildiği, sayfalar arası veri taşıma mantığıyla kurgulanmış ekran.
- **Sepet Simülasyonu:** Ürün detay sayfasında sepete ekle butonuna basıldığında ana sayfaya geri dönülmesi ve basit bir *state* güncellemesi ile sepet sayısının artması.

## Kullanılan Teknolojiler
- **Kullanılan Flutter Sürümü:** Flutter 3.x ve üzeri (SDK: '>=3.0.0 <4.0.0')
- **Dil:** Dart
- **Paketler:** Sadece temel `material.dart` kullanılmış, harici bir paket (http vb.) eğitim yönergesi gereği kullanılmamış ve JSON veri statik (mock_data) olarak simüle edilmiştir.

## Projeyi Çalıştırma Adımları
Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

1. Bu depoyu (repository) bilgisayarınıza klonlayın veya zip olarak indirin.
2. Terminal veya Komut İstemcisi üzerinden proje klasörüne gidin:
   ```bash
   cd mini_katalog
   ```
3. Flutter bağımlılıklarını indirin:
   ```bash
   flutter pub get
   ```
4. Uygulamayı bağlı bir cihazda veya emülatörde çalıştırın:
   ```bash
   flutter run
   ```
   
> **Not:** Projeyi çalıştırmak için bilgisayarınızda Flutter SDK, Dart SDK ve Android Studio / VS Code kurulu olmalıdır.
