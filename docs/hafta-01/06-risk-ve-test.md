# 1. Hafta · Risk Analizi ve Test Kontrol Listesi

**Hazırlayan:** Ömer Faruk Haskul

## Risk tablosu

Puan = olasılık (1–3) × etki (1–3)

| # | Risk | Olasılık | Etki | Puan | Önlem | Sorumlu |
| --- | --- | --- | --- | --- | --- | --- |
| R1 | **Randevu akışı çalışmaz:** Instagram hesabı yok, müşterinin tercih ettiği kanal belli değil | 3 | 3 | **9** | Kanal görüşmede netleşir; WhatsApp kısa linki yedek olarak hazır tutulur | Elif, Emre |
| R2 | Hoca akışı fazla basit bulur, ücretli SMS'e kayma baskısı doğar | 2 | 2 | 4 | SMS 2. sürüm kartı olarak bekler; gerekçe raporda yazılı | Ali |
| R3 | Müşteri içerik (logo, fotoğraf, fiyat) vermez | 2 | 2 | 4 | Telifsiz geçici görseller kullanılır, sonra değiştirilir | Elif |
| R4 | Rotasyon yüzünden raporlar arasında biçim farkı | 2 | 1 | 2 | Tek şablon; README'deki depo yapısı | Ali |
| R5 | Düşük katılım (bu hafta 4/7 yazılı katkı) | 2 | 2 | 4 | Trello kart sahipliği ve haftalık durum kontrolü | Emine |
| R6 | Mobil görünüm bozuk | 1 | 2 | 2 | Aşağıdaki test listesi her hafta çalıştırılır | Ömer |

**En riskli parça:** R1, randevu talebi akışı. Sitenin tek işlevsel akışıdır ve iki dış bağımlılığı vardır.

## Test kontrol listesi (2. haftadan itibaren her sürümde)

### Mobil görünüm
- [ ] 360 px genişlikte yatay kaydırma yok
- [ ] 390 px genişlikte yazılar okunur, butonlar en az 44 px
- [ ] 768 px (tablet) görünümde düzen bozulmuyor
- [ ] En az 3 farklı telefonda açıldı (Android ve iPhone)

### Bağlantılar
- [ ] "Randevu al" butonu Instagram DM'i açıyor
- [ ] WhatsApp kısa linki doğru numaraya sohbet açıyor
- [ ] "Yol tarifi" Google Maps'i yeni sekmede açıyor
- [ ] Telefon numarası tıklanınca arama başlatıyor
- [ ] Kırık bağlantı sayısı 0

### Sayfa akışı
- [ ] Ana sayfa → hizmet kartı → detay → geri dönüş çalışıyor
- [ ] Tüm görseller yükleniyor, alternatif metinleri var
- [ ] Sayfa başlıkları ve Nova Beauty adı her sayfada doğru

### Test kaydı

| Tarih | Cihaz | Sonuç | Bulunan hata | Düzelten |
| --- | --- | --- | --- | --- |
| | | | | |
