# Nöbet Asistanı · Kasım 2026

Telefon ve masaüstünde kullanılabilen, çevrimdışı destekli PWA nöbet listesi.

## Uygulama
https://trustindestiny.github.io/nobet/

## Özellikler
- Günlük nöbet ve hafta sonu ek görev tabloları
- Kasım 2026 içinde cihaz tarihine göre otomatik gün seçimi
- İsim araması ve eşleşen satırların filtrelenmesi
- Haftanın günlerine göre nöbet ve icap özeti
- Tamamen boş hafta sonu sayacı
- Tablo hücrelerini düzenleme ve tarayıcıda saklama
- Telefonda yatay kaydırma olmadan kompakt görünüm
- PWA olarak ana ekrana yükleme
- Service worker ile uygulama kabuğunun çevrimdışı açılması

## GitHub Pages
Depo ayarlarında **Settings → Pages → Build and deployment → Source → GitHub Actions** seçilidir. main dalına gönderilen her commit, .github/workflows/deploy.yml üzerinden siteyi yayınlar.

## Telefona yükleme
- **Android:** Chrome'da uygulamayı açın ve “Uygulamayı yükle” düğmesini kullanın; uygun olduğunda Chrome menüsünde de yükleme seçeneği görünür.
- **iPhone/iPad:** Safari'de açın → Paylaş → Ana Ekrana Ekle.

Uygulama ilk kurulumda internet bağlantısı ister. İlk başarılı açılıştan sonra uygulama dosyaları önbellekten çevrimdışı açılabilir. Nöbet düzenlemeleri şu an cihazın kendi tarayıcı hafızasında tutulur; cihazlar arasında otomatik senkronizasyon yoktur.
