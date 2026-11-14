# kdr

Proje amacı henüz belirlenmemiştir. Bu depo, gereksinimler netleştirilene kadar teknoloji bağımsız bir başlangıç yapısı sunar.

## Durum

- Ürün, hedef kullanıcı ve ilk kullanım senaryosu: açık karar.
- Dil, uygulama çatısı, veritabanı ve dağıtım ortamı: seçilmedi.
- Çalışan uygulama, bağımlılık, otomatik test ve CI/CD: henüz yok.
- Lisans: henüz seçilmedi; bu başlangıç bir lisans kararı içermez.

Depo adı tek başına ürün amacını açıklamaz. Başka bir projeyle bağlantısı varsayılmamıştır.

## Başlangıç

Depoyu bilgisayarınıza almak için Git yeterlidir:

```sh
git clone https://github.com/kadergulcimenxx-oss/kdr.git
cd kdr
```

Ardından [proje kapsamını ve açık kararları](docs/PROJECT.md), [görev listesini](docs/TASKS.md) ve [katkı kurallarını](CONTRIBUTING.md) okuyun. Henüz kurulum, çalıştırma veya uygulama testi komutu bulunmaz. Bunlar teknoloji seçildiğinde ilk çalışan özellik ile birlikte eklenecektir.

## Dosya düzeni

| Yol | Amaç |
| --- | --- |
| `src/` | Seçilecek teknolojiye uygun uygulama kodu |
| `tests/` | İlk özellikten itibaren davranış testleri |
| `docs/PROJECT.md` | Kapsam, varsayımlar ve karar kaydı |
| `docs/TASKS.md` | Sıralı görevler ve tamamlanma ölçütleri |
| `CONTRIBUTING.md` | Dal, PR ve doğrulama kuralları |
| `SECURITY.md` | Hassas veriler ve güvenlik bildirimi |
| `.github/` | Görev ve PR şablonları |
| `.editorconfig` | Ortak metin biçimi |
| `.gitattributes` | Satır sonu kuralları |
| `.gitignore` | Yerel ayarlar, sırlar ve geçici dosyalar için temel dışlamalar |

## İlk hedef

Bir kullanıcı problemini ve tek bir uçtan uca senaryoyu tanımlayın. Ardından buna uygun en küçük teknoloji seçimini yapın ve çalışan senaryoyu anlamlı testlerle ekleyin. Ayrıntılar [görev listesinde](docs/TASKS.md).

## Güvenlik ve katkı

Depo herkese açıktır. Parola, erişim anahtarı, gerçek kişisel veri veya üretim verisi eklemeyin. Güvenlik bildirimleri için [SECURITY.md](SECURITY.md), değişiklikler için [CONTRIBUTING.md](CONTRIBUTING.md) belgesini izleyin.

Belge kuralları, GitHub üzerinde dal koruması veya otomatik güvenlik taraması etkinleştirmez. Bu ayarların değerlendirilmesi görev listesinde açık tutulmuştur.
