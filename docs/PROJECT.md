# Proje kapsamı ve karar kaydı

## 14 Kasım 2026 başlangıç incelemesi

GitHub API üzerinden depo metaverisi, kök içerik, dallar, commit'ler, tüm issue'lar ve açık PR'lar kontrol edildi:

- Depo: `kadergulcimenxx-oss/kdr`; görünürlük: herkese açık.
- Varsayılan dal adı: `main`.
- İçerik ve commit uç noktaları deponun boş olduğunu bildirdi; dal listesi boştu. Dolayısıyla `main` adı tanımlı olsa da ilk commit henüz yoktu.
- Issue ve açık PR listeleri boştu.
- Açıklama, konu etiketleri, ana dil ve lisans tanımlı değildi.
- Uygulanacak mevcut README, AGENTS.md veya katkı yönergesi yoktu.

Bu kayıt başlangıç anını anlatır; sonraki commit ve PR'ları yansıtmaz.

## Varsayımlar

1. Öncelik, sonraki geliştirmeye anlaşılır ve küçük bir temel sağlamaktır.
2. Belge dili Türkçedir.
3. Depo adı belirli bir ürüne veya önceki projeye bağlanmaz.
4. Gereksinim bilinmeden teknoloji, barındırma veya lisans seçimi yapılmaz.

Varsayımlar ürün kararı değildir; proje amacı açıklandığında güncellenebilir.

## Açık kararlar

| Karar | Yanıtlanacak soru | Durum |
| --- | --- | --- |
| Ürün amacı | Hangi kullanıcı, hangi sorunu çözmek istiyor? | Açık |
| İlk kapsam | İlk sürümdeki tek temel senaryo ve kapsam dışı işler neler? | Açık |
| Platform | Web, mobil, masaüstü, komut satırı veya başka bir araç mı? | Açık |
| Veri | Hangi veri gerekir; kişisel veri veya hesap ihtiyacı var mı? | Açık |
| Teknoloji | Kapsamı en az karmaşıklıkla hangi araçlar karşılar? | Açık |
| İşletim | Kim bakım yapacak; nerede ve hangi bütçeyle çalışacak? | Açık |
| Lisans | Proje hangi kullanım ve dağıtım koşullarıyla sunulacak? | Açık |

## Başlangıç kararları

| Kimlik | Karar | Gerekçe | Yeniden değerlendirme |
| --- | --- | --- | --- |
| B01 | Teknoloji bağımsız kaynak, test ve belge klasörleri | Ürün türü bilinmiyor | İlk senaryo netleşince |
| B02 | Bağımlılık ve çalıştırılabilir örnek eklememek | Gereksiz bakım ve yanlış mimari seçimini önlemek | Teknoloji seçilince |
| B03 | CI/CD ve dağıtımı açık görev olarak bırakmak | Henüz doğrulanacak uygulama komutu veya dağıtım hedefi yok | İlk çalışan özellikte |
| B04 | Lisans ve özel güvenlik kanalı uydurmamak | Sahiplik ve iletişim tercihi doğrulanmamış | Yayın öncesinde |

Yeni kararlar için tarih, karar, gerekçe, düşünülen seçenekler ve değişiklik etkisi kaydedilsin.
