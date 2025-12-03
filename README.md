# Yerel Gezi Noktaları ve Aktivite Rehberi 🗺️  
Bu proje, bir şehirdeki **gezi noktaları, aktiviteler, etkinlikler, yorumlar ve ulaşım seçeneklerini** içeren bir rehber sisteminin veri tabanı tasarımını içerir.

---

## 🎯 Projenin Amacı
Kullanıcıların:
- Gezilecek yerleri keşfetmesini  
- Aktiviteleri görüntülemesini  
- Ulaşım seçeneklerini değerlendirmesini  
- Mekanlara yapılan yorumları incelemesini  

sağlayabilecek **ilişkisel bir veritabanı modeli** oluşturmaktır.

---

## 🧱 Temel Varlıklar
Bu projede yer alan temel varlıklar ve anlamları:

- **Mekan** → Gezilecek yerler, parklar, müzeler  
- **Aktivite** → Mekana bağlı yapılabilecek aktiviteler  
- **Etkinlik** → Belirli tarih ve saatlerde gerçekleşen planlı etkinlikler  
- **Kullanıcı** → Sistemi kullanan kişiler  
- **Yorum** → Kullanıcıların mekan/aktivite hakkında geri bildirimleri  
- **Ulaşım** → Mekanlara ait ulaşım yöntemi bilgileri  
Referans: yerel gezi noktaları.pdf

---

## 🔗 İlişkiler (Kısaca)
- Bir **mekanın birden çok aktivitesi** olabilir  
- Bir **aktivitenin birçok yorumu** olabilir  
- Bir **kullanıcı birçok yorum** yazabilir  
- Bir **mekanın birçok ulaşım seçeneği** olabilir  

Bu yapı sayesinde sistem ölçeklenebilir ve yönetilebilir hale gelir.

---

## 📂 Dosyalar
- `yerel gezi noktaları.pdf` → Tam proje dokümantasyonu

---

## 🧪 İleride Eklenebilecekler
- `database.sql` dosyası (CREATE TABLE komutları)  
- ER diyagramının PNG versiyonu  
- Örnek test verileri  
- Basit bir Python/Java arayüzü  

---

## 👩‍💻 Geliştirici  
**Elif İrem Kaya**  
Veri Tabanı Tasarımı • SQL • Sistem Analizi  
