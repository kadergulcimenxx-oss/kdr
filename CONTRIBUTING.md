# Katkı kuralları

## Değişiklik akışı

1. İlgili görevi [görev listesinde](docs/TASKS.md) bulun veya bir issue ile problem ve kabul ölçütlerini yazın. Küçük belge düzeltmelerinde ayrı issue zorunlu değildir.
2. Güncel `main` üzerinden açıklayıcı bir dal oluşturun: `docs/kapsam`, `feat/ilk-senaryo` veya `fix/kisa-aciklama`.
3. Tek bir amaca yönelik, incelenebilir değişiklikler yapın. Yeni bağımlılık veya mimari seçim için gerekçeyi [karar kaydına](docs/PROJECT.md) ekleyin.
4. Değişiklikleri kontrol edip PR açın; neyin değiştiğini, nedenini ve nasıl doğrulandığını belirtin.
5. İnceleme ve geçerli kontroller tamamlandıktan sonra birleştirin. Bu bir çalışma kuralıdır; sunucu üzerinde dal korumasının etkin olduğu anlamına gelmez.

## Doğrulama

Şu an uygulama ve test çalıştırıcısı yoktur. Belge değişikliklerinde bağlantıları, görev durumlarını ve aşağıdaki çıktıları kontrol edin:

```sh
git diff --check
git diff --cached --check
git status --short
git diff --cached
```

`git diff` komutları izlenmeyen dosyaları kontrol etmez. Yeni dosyaları da okuyun ve yalnızca amaçlanan dosyaları `git add <dosya>` ile hazırladıktan sonra staged diff'i inceleyin. Bu komutlar gizli bilgi tarayıcısı değildir.

İlk uygulama koduyla birlikte kurulum, çalıştırma ve test komutlarını README'ye ekleyin. Başarı durumu, hata durumu ve ilgili sınır koşulları için anlamlı testler yazın. Çalıştırılmayan bir testi başarılı göstermeyin.

## Dosya ve veri kuralları

- Belgeleri anlaşılır Türkçe yazın; kod adları seçilecek ekosistemin kurallarına uysun.
- UTF-8, LF ve dosya sonunda yeni satır kullanın; proje ayarları `.editorconfig` içindedir.
- Gerçek erişim bilgilerini, kullanıcı verilerini ve üretim veritabanı kopyalarını commit etmeyin.
- Ortam ayarları gerektiğinde `.env.example` içinde yalnızca güvenli yer tutucular bulunsun.
- Lisans seçimi, dağıtım ve ücretli servis kararları proje sahibiyle netleştirilsin.
