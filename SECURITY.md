# Güvenlik

## Mevcut durum

Bu başlangıç yapısında çalışan uygulama veya yayımlanmış sürüm yoktur. Güvenlik denetimi, otomatik sır taraması, dal koruması ve özel bildirim kanalının etkinliği doğrulanmış değildir.

## Hassas bilgi

- Parola, API anahtarı, özel anahtar, oturum çerezi ve gerçek kullanıcı verilerini dosyalara, issue'lara veya PR'lara eklemeyin.
- Örneklerde sentetik veri kullanın.
- `.gitignore` yalnızca yanlışlıkla ekleme riskini azaltır; izlenen dosyaları veya geçmiş commit'leri temizlemez ve tüm sır dosyalarını yakalayamaz.
- Bir erişim bilgisi yayımlanırsa önce ilgili sağlayıcıda iptal edin veya değiştirin; ardından geçmiş ve erişim etkisini değerlendirin. Yalnızca dosyayı silmek yeterli değildir.

## Güvenlik bildirimi

Hassas ayrıntıları açık issue veya PR'da paylaşmayın. Deponun Security sekmesinde özel bildirim seçeneği varsa onu kullanın. Bu seçenek görünmüyorsa, proje sahibinden özel bir kanal kurmasını isteyin; herkese açık talepte yalnızca iletişim kanalı ihtiyacını belirtin, açığın ayrıntısını eklemeyin.

Doğrulanmış bir iletişim adresi ve yanıt süresi henüz tanımlanmamıştır. Bunların oluşturulması [yayın öncesi görevler](docs/TASKS.md) arasındadır.

## İlk uygulama eklenirken

Seçilen teknolojiye göre bağımlılık kontrolleri, erişim yetkileri, girdi doğrulama ve test kapsamı belirlenmelidir. CI işlerine yalnızca gerekli yetkiler verilmeli, güvenilmeyen katkılara üretim sırları açılmamalıdır.
