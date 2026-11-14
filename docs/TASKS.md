# Başlangıç görevleri

Bu liste planı gösterir. Tamamlanma ölçütü karşılanmadan kutuyu işaretlemeyin.

## 1. Amacı netleştir

- [ ] **Ürün özeti:** hedef kullanıcıyı ve çözülmek istenen problemi bir paragrafta yaz.
- [ ] **İlk senaryo:** kullanıcının başlangıç, işlem ve beklenen sonuç adımlarını tanımla; başarı ölçütü ve kapsam dışı işler kaydedilsin.
- [ ] **Veri ihtiyacı:** tutulacak verileri, saklama süresini, hesap ve izin ihtiyacını belirle; gereksiz kişisel veri toplanmasın.

Tamamlanma ölçütü: `docs/PROJECT.md` içindeki ürün amacı, ilk kapsam, platform ve veri kararları proje sahibi tarafından netleştirilmiş olmalı.

## 2. En küçük çalışan uygulamayı kur

- [ ] **Teknoloji kararı:** dil, araçlar ve desteklenen sürümler gerekçeleriyle kaydedilsin.
- [ ] **Yerel kurulum:** temiz bir ortamda belgelenmiş kurulum ve çalıştırma komutları çalışsın; gerekiyorsa bağımlılık kilit dosyası eklensin.
- [ ] **İlk özellik:** tek temel senaryo `src/` altında uçtan uca çalışsın.
- [ ] **Test:** başarı, hata ve ilgili sınır durumları `tests/` altında doğrulansın; gerçek komutlar ve sonuçlar PR'da bulunsun.

Tamamlanma ölçütü: başka bir geliştirici yalnızca README ile uygulamayı çalıştırabilmeli ve test sonucunu yeniden üretebilmeli.

## 3. İnceleme ve güvenlik tabanını tamamla

- [ ] **CI:** gerçek biçim, derleme ve test komutlarını çalıştıran bir iş akışı ekle; en az yetki, süre sınırı ve sabitlenmiş üçüncü taraf action sürümleri kullan.
- [ ] **Depo koruması:** mevcut hesap ve depo özelliklerinin desteklediği PR incelemesi ve zorunlu kontrolleri değerlendir; uygulanmış ayarları ayrıca doğrula.
- [ ] **Gizli bilgi ve bağımlılıklar:** uygun tarama araçlarını seç; sonuçları incele, etkinliği doğrulanmadan tamamlandı sayma.
- [ ] **Özel güvenlik bildirimi:** kullanılabilir kanalı doğrula ve SECURITY.md'yi güncelle.

Tamamlanma ölçütü: kontrollerin çalıştığına dair kayıt bulunmalı; önerilen ayarlar ile gerçekten etkin ayarlar ayrılmalı.

## 4. İlk yayın öncesi kararları al

- [ ] **Lisans:** proje sahibi tercihini belirlesin; seçilen lisans metni ve README bilgisi uyumlu olsun.
- [ ] **Yayın ve bakım:** hedef ortam, maliyet, sorumlu kişi ve geri alma yöntemi belirlensin.
- [ ] **Veri koruması:** kalıcı veri varsa yedekleme ve geri yükleme denensin; yoksa gerekçe yazılsın.

Tamamlanma ölçütü: yayın öncesi açık riskler ve sorumlular kayıtlı olmalı; çalışan uygulama ve kontroller doğrulanmadan üretime çıkılmamalı.
