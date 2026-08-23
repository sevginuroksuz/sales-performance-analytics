# Satış Performansı Veri Analizi

Bu proje, satış verilerinin Power BI kullanılarak analiz edilmesi ve
karar alma süreçlerini destekleyen etkileşimli dashboardların
geliştirilmesi amacıyla hazırlanmıştır. Çalışmada satış performansı;
ciro, kârlılık, müşteri segmentleri, bölgeler ve ürünler açısından
incelenmiştir.

## 📊 Power BI Raporu

**[Power BI Service Üzerinde Etkileşimli Raporu Görüntüle](https://app.powerbi.com/groups/me/reports/3e5c434e-b8cc-4b85-aad5-512a7e87188b/9e0f127bd610f324b6b5?experience=power-bi)**

> Rapor Power BI Service üzerinde yayımlanmıştır. Görüntüleme için erişim yetkisi gerekebilir.

## Projenin Amacı

Projenin temel amacı, ham satış verilerini analiz edilebilir bir veri
modeline dönüştürerek yönetimsel ve operasyonel içgörüler üretmektir. Bu
kapsamda müşteri davranışları, bölgesel satış ve kârlılık performansı,
ürün bazlı ciro ve kâr sonuçları ile dönemsel satış değişimleri analiz
edilmiştir.

## Yapılan Çalışmalar

- Power Query ile veri temizleme ve dönüştürme işlemleri gerçekleştirildi.
- Satış verileri; Tarih, Müşteri, Ürün Master ve Satış Türü tabloları ile ilişkilendirilerek veri modeli oluşturuldu.
- Tablolar arasında 1:N ilişkiler kuruldu ve filtre yönleri düzenlendi.
- DAX ölçüleri kullanılarak Toplam Ciro, Toplam Maliyet, Toplam Kâr, Kâr Marjı, Toplam Sipariş, Toplam Müşteri, Satılan Ürün Sayısı ve Son Yıl Büyüme oranları hesaplandı.
- Müşteriler satın alma davranışlarına göre segmentlere ayrıldı.
- Fiyat Skalası ve Ürün Satış Yaşı gibi analiz alanları oluşturuldu.
- Yıl, Çeyrek ve Ay hiyerarşisi kullanılarak drill-down analizi hazırlandı.
- Slicer ve sayfa navigasyonu ile etkileşimli rapor deneyimi oluşturuldu.
- Rapor Power BI Service üzerinde yayımlandı.

## Dashboardlar

### 1. Satış Performansı – Yönetim Özeti

![Satış Performansı - Yönetim Özeti](pages/Yönetim%20Özeti.png)

Satış performansının üst düzey görünümünü sunar. Toplam ciro, büyüme,
sipariş, müşteri ve satılan ürün sayısı KPI'larının yanında aylık ciro
trendi, bölgesel ciro, ürün ailesi performansı ve en yüksek ciroya sahip
müşteriler incelenmektedir.

### 2. Müşteri Segmentasyonu ve Değer Analizi

![Müşteri Segmentasyonu ve Değer Analizi](pages/Müşteri%20Segmentasyonu.png)

Müşterilerin segment dağılımını, toplam ciroya katkısını, ortalama
sipariş tutarını ve satın alma sıklığını karşılaştırır. VIP, Sadık
Müşteri, Düzenli Müşteri ve Düşük Etkileşim segmentleri üzerinden
müşteri değerinin değerlendirilmesini sağlar.

### 3. Bölgesel Satış ve Kârlılık Analizi

![Bölgesel Satış ve Kârlılık Analizi](pages/Bölgesel%20Satış%20Stratejileri.png)

Bölgelerin ciro, kâr, kâr marjı ve son yıl büyüme performanslarını
karşılaştırır. Ayrıca bölge ve ürün ailesi kırılımında satış dağılımının
incelenmesini sağlar.

### 4. Ürün Optimizasyonu ve Kârlılık Analizi

![Ürün Optimizasyonu ve Kârlılık Analizi](pages/Ürün%20Optimizasyon%20Stratejileri.png)

Ürün bazında ciro, kâr ve kâr marjı performansını analiz eder. En yüksek
ciroya ve kâra sahip ürünlerin yanı sıra ürün bazında ortalama satış
fiyatı ile ortalama birim maliyet karşılaştırmasını içerir.

## Temel KPI ve Ölçüler

- Toplam Ciro EUR
- Toplam Maliyet EUR
- Toplam Kâr EUR
- Kâr Marjı %
- Toplam Sipariş
- Toplam Müşteri
- Satılan Ürün Sayısı
- Son Yıl Büyüme %
- Ortalama Sipariş Tutarı EUR
- VIP Müşteri Sayısı
- VIP Ciro Payı %

## Veri Modeli

Rapor modeli, satış hareketlerinin merkezde bulunduğu bir yapı üzerine
kurulmuştur. `Satış Verileri` tablosu; `Tarih`, `Müşteri`, `Ürün Master`
ve `Satış Türü` tabloları ile ilişkilendirilmiştir. Boyut tablolarından
satış tablosuna doğru 1:N ilişkiler ve tek yönlü filtreleme
kullanılmıştır.

## Kullanılan Teknolojiler

- Microsoft Power BI Desktop
- Power BI Service
- Power Query
- DAX

## Etkileşimli Özellikler

Rapor sayfalarında Yıl, Bölge, Ürün Ailesi ve Müşteri Segmenti gibi
alanlar için slicerlar kullanılmıştır. Sayfalar arası geçiş Page
Navigator ile sağlanmış, zaman bazlı analizlerde Yıl → Çeyrek → Ay
drill-down yapısı kullanılmıştır.

## Proje Çıktısı

Çalışma sonucunda satış performansını farklı iş perspektiflerinden
değerlendiren dört etkileşimli Power BI dashboardu oluşturulmuş ve Power
BI Service üzerinde yayımlanmıştır.

## Dosyalar ve Bağlantılar

- `Satis_Performansi_Veri_Analizi_Case_Study.pbix` — Power BI rapor dosyası
- `README.md` — Proje dokümantasyonu
- [Power BI Service Raporu](https://app.powerbi.com/groups/me/reports/3e5c434e-b8cc-4b85-aad5-512a7e87188b/9e0f127bd610f324b6b5?experience=power-bi)

---

Bu çalışma, satış verilerinin veri hazırlama, modelleme, DAX
hesaplamaları ve görselleştirme adımlarından geçirilerek karar destek
odaklı bir Power BI raporuna dönüştürülmesini kapsamaktadır.
