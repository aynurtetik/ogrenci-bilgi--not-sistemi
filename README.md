# ogrenci-bilgi--not-sistemi
Python OOP ile geliştirilmiş Öğrenci Bilgi ve Not Takip Sistemi
# Öğrenci Bilgi ve Not Takip Sistemi

## Proje Amacı
Bu projenin amacı, bir eğitim kurumundaki öğrenci, ders, öğretmen ve not verilerini nesne yönelimli programlama (OOP) prensiplerini kullanarak sistematik bir şekilde yönetmek, verileri kalıcı olarak saklamak ve akademik başarı analizleri yapmaktır.

## Kullanılan Teknolojiler
- Python
- JSON
- OOP (Nesne Yönelimli Programlama)

## Kullanılan OOP Yapıları
Proje, ödev yönergesinde belirtilen tüm zorunlu yapıları içermektedir:
- **Class & Object:** Tüm varlıklar (Öğrenci, Ders, Not, Öğretmen) sınıflarla temsil edilmiştir.
- **Inheritance (Kalıtım):** Ogrenci ve Ogretmen sınıfları SistemUyesi sınıfından türetilmiştir.
- **Encapsulation (Kapsülleme):** Not listeleri ve hassas verilere erişim getter/setter metodları ve private/protected erişim belirleyicileri ile kontrol altına alınmıştır.
- **Polymorphism (Çok Biçimlilik):** Farklı sınıflardaki bilgileri_goster() metodları aynı isimle farklı çıktılar verecek şekilde ezilmiştir (method overriding).
- **Abstraction (Soyutlama):** SistemUyesi sınıfı ABC modülü kullanılarak abstract (soyut) sınıf olarak tanımlanmıştır.

## Proje Özellikleri
- Öğrenci, ders ve öğretmen ekleme
- Not girişi ve öğrenci bazlı not görüntüleme
- Genel ortalama hesaplama ve başarı analizi (Baraj üstü öğrencileri listeleme)
- İsim veya numaraya göre öğrenci arama
- Tüm verileri data.json dosyasına kaydetme ve geri yükleme

## Kurulum
Projeyi çalıştırmak için Google Colab üzerinde hücreyi çalıştırmanız veya yerel ortamda şu komutu vermeniz yeterlidir:
```bash
python main.py

Geliştiren

Ad Soyad: Aynur TETİK-Ravza DAĞAŞAN
Ders: Programlama2
