# 1. Hafta · Kapsam ve Gereksinimler

**Hazırlayan:** Mehmet Emin Gülseren

Birinci sürüm, ücretsiz araçlarla 3 haftada bitecek bir tanıtım sitesidir. İşlem yapan (sunucu, ödeme, bildirim) her özellik kapsam dışındadır.

## Kullanıcı hikâyeleri ve kabul kriterleri

Öncelik: **M** = mutlaka, **S** = olmalı, **C** = olsa iyi olur (MoSCoW)

| Kod | Kullanıcı hikâyesi | Öncelik | Kabul kriteri |
| --- | --- | --- | --- |
| G1 | Bir ziyaretçi olarak ana sayfada Nova Beauty'nin ne sunduğunu görmek istiyorum. | M | Ana sayfa logo, kısa tanıtım ve "Randevu al" butonu içerir; telefonda kaydırmadan görünür. |
| G2 | Bir ziyaretçi olarak hizmetleri liste halinde görmek istiyorum. | M | Her hizmet bir kartta adı, görseli ve kısa açıklamasıyla gösterilir. |
| G3 | Bir ziyaretçi olarak bir hizmetin ayrıntısını okumak istiyorum. | M | Karta dokununca hizmetin detay sayfası açılır; geri dönüş bağlantısı vardır. |
| G4 | Bir ziyaretçi olarak randevu talebini hızlıca iletmek istiyorum. | M | "Randevu al" butonu en fazla 2 dokunuşta Instagram DM'e veya WhatsApp sohbetine götürür. |
| G5 | Bir ziyaretçi olarak merkeze nasıl gideceğimi bilmek istiyorum. | S | Adres ve "Yol tarifi" bağlantısı Google Maps'i yeni sekmede açar. |
| G6 | Bir ziyaretçi olarak çalışma saatlerini ve telefonu görmek istiyorum. | S | İletişim bölümü saatleri ve tıklanabilir telefon numarasını gösterir. |
| G7 | İşletme sahibi olarak sitenin telefonda düzgün görünmesini istiyorum. | M | 360 px, 390 px ve 768 px genişlikte yatay kaydırma yoktur, yazılar okunur. |
| G8 | İşletme sahibi olarak fiyatları gösterebilmek istiyorum. | C | Müşteri fiyat verirse hizmet kartında fiyat alanı görünür. |

## Kapsam içi

- Ana sayfa ve Nova Beauty marka alanı (G1)
- Hizmet kartları ve detay sayfaları (G2, G3)
- Instagram ve WhatsApp'a yönlendiren randevu butonu (G4)
- İletişim, adres, çalışma saatleri, Maps bağlantısı (G5, G6)
- Mobil uyumlu tasarım ve temel testler (G7)

## Kapsam dışı

- SMS veya web push bildirimi (2. sürüm adayı)
- Çevrim içi ödeme
- Üyelik, giriş ve rol sistemi (yönetici, personel, müşteri)
- Takvimli randevu sistemi
- Google Maps API ve diğer ücretli API'ler
- İçerik yönetim paneli
