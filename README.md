# Etkinlik-Sosyalle-me-Uygulamas-
ETKİNLİK ORGANİZASYON UYGULAMASI
PROJE PLANLAMA DOKÜMANTASYONU
1. GİRİŞ
Bu doküman, Etkinlik Organizasyon Uygulaması'nın proje planlamasını ve geliştirme sürecini
tanımlamaktadır. Uygulamanın geliştirme süreci, temel işlevlerin belirlenmesi, teknik
altyapının planlanması ve proje yönetim süreci ile ilgili detayları içermektedir.
2. PROJE KAPSAMI
Etkinlik Organizasyon Uygulaması, kullanıcıların etkinlikler oluşturmasını, etkinliklere
katılmasını ve arkadaşlık ilişkileri kurmasını sağlayan web ve mobil tabanlı bir platformdur.
Uygulama şu temel işlevleri sunacaktır:
 Kullanıcı kaydı ve girişi
 Etkinlik oluşturma ve düzenleme
 Etkinliklere katılma ve davet gönderme
 Kullanıcı profili ve arkadaş listesi yönetimi
 Harita entegrasyonu ile etkinlik konumlarını görüntüleme
 Gerçek zamanlı bildirimler ve mesajlaşma sistemi
3. PROJE TAKVİMİ
Aşama Başlangıç Tarihi Bitiş Tarihi
Gereksinim Analizi 1. Hafta 2. Hafta
UI/UX Tasarım 3. Hafta 4. Hafta
Veritabanı Tasarımı 5. Hafta 6. Hafta
Backend Geliştirme 6. Hafta 9. Hafta
Frontend Geliştirme (Web & Mobil) 10. Hafta 13. Hafta
Test ve Hata Giderme 14. Hafta 15. Hafta
Yayın ve Sürüm Yönetimi 16. Hafta 17. Hafta
4. TEKNİK ALTYAPI VE ARAÇLAR
 Frontend (Web): HTML ,Css
 Frontend (Mobil): Flutter
 Backend: Node.js, JavaScript.js
 Veritabanı: SQL
 Bildirim Sistemi: SQL
5. GÖREV DAĞILIMI
Takım Üyesi Rol Sorumluluklar
Proje Yöneticisi Proje Planlama Proje takibini yapar, takım
koordinasyonunu sağlar
FrontendTasarımcısı Arayüz Tasarımı Kullanıcı dostu bir tasarım oluşturur
Backend Geliştirici Sunucu tarafı kodlama Veritabanı entegrasyonu yapar
Frontend Geliştirici
(Web)
Web Arayüz
Geliştirme Web uygulamasını geliştirir
Frontend Geliştirici
(Mobil)
Mobil Uygulama
Geliştirme Flutter ile mobil uygulamayı geliştirir
Test Uzmanı Yazılım Testi Test senaryolarını hazırlar, hata raporları
oluşturur
6. RİSK ANALİZİ
Risk Olasık Etki Önleyici Tedbir
Gereksinim Değişikliği Orta Yüksek Esnek planlama, düzenli toplantılar
Teknik Zorluklar Yüksek Yüksek Deneyimli geliştiriciler, alternatif yaklaşımlar
Takvim Kaymaları Orta Orta Haftalık ilerleme toplantıları
Performans Problemleri Orta Yüksek Kod optimizasyonu, testler
7. TEST PLANLAMASI
 Birim Testleri: Backend API ve frontend bileşenleri ayrı ayrı test edilecektir.
 Entegrasyon Testleri: Backend ile frontend arasındaki veri alışverişi test edilecektir.
 Kullanıcı Kabul Testleri: Gerçek kullanıcıların uygulamayı test etmesi sağlanacaktır.
 Güvenlik Testleri: SQL injection ve kimlik doğrulama testleri uygulanacaktır.
8. SONUÇ
Bu proje planı, Etkinlik Organizasyon Uygulaması'nın başarıyla geliştirilmesi ve yayına
alınması için detaylı bir yol haritası sunmaktadır. Proje ekibinin belirlenen zaman çizelgesine
ve teknik gereksinimlere uygun çalışmasıyla uygulamanın başarıyla tamamlanması
hedeflenmektedir

----------------

ETKİNLİK ORGANİZASYON UYGULAMASI
GEREKSİNİM ANALİZİ DOKÜMANI
1. GİRİŞ
Bu gereksinim analizi dokümanı, Etkinlik Organizasyon Uygulaması'nın temel fonksiyonel ve teknik
gereksinimlerini tanımlamaktadır. Bu uygulama, kullanıcıların etkinlikler oluşturup katılabilecekleri, diğer
kullanıcılarla arkadaşlık kurabilecekleri web ve mobil tabanlı bir platform olarak tasarlanmıştır.
2. GENEL BAKIŞ
Etkinlik Organizasyon Uygulaması, kullanıcıların hesap oluşturup giriş yapabileceği, etkinlikler düzenleyebileceği
ve katılabileceği, sosyal etkileşimler kurabileceği bir platformdur. Uygulama HTML/CSS/JavaScript ile web
tarafını, Flutter ile mobil tarafını sunacaktır. Veritabanı olarak SQL kullanılacaktır.
3. FONKSİYONEL GEREKSİNİMLER
3.1. Kullanıcı Yönetimi
| Gereksinim ID | Gereksinim Açıklaması | Öncelik |
|---------------|------------------------|---------|
| FR-101 | Kullanıcılar sisteme kayıt olabilmelidir (sign up) | Yüksek |
| FR-102 | Kullanıcılar sisteme giriş yapabilmelidir (login) | Yüksek |
| FR-103 | Kullanıcı bilgileri SQL veritabanında saklanmalıdır | Yüksek |
| FR-104 | Kullanıcılar isim, soyisim, yaş, e-posta, şifre bilgilerini girebilmelidir | Yüksek |
| FR-105 | Kullanıcılar profil bilgilerini güncelleyebilmelidir | Orta |
| FR-106 | Kullanıcılar şifrelerini sıfırlayabilmelidir | Orta |
3.2. Etkinlik Yönetimi
| Gereksinim ID | Gereksinim Açıklaması | Öncelik |
|---------------|------------------------|---------|
| FR-201 | Kullanıcılar etkinlik oluşturabilmelidir | Yüksek |
| FR-202 | Etkinlik oluşturulurken yer, tarih, kişi sayısı ve etkinlik adı belirtilebilmelidir | Yüksek |
| FR-203 | Kullanıcılar etkinliği yayınlayabilmelidir | Yüksek |
| FR-204 | Etkinlik bilgileri SQL veritabanında saklanmalıdır | Yüksek |
| FR-205 | Kullanıcılar etkinlikleri güncelleyebilmelidir | Orta |
| FR-206 | Kullanıcılar etkinlikleri iptal edebilmelidir | Orta |
| FR-207 | Etkinlik detay sayfasında tüm bilgiler görüntülenebilmelidir | Orta |
3.3. Etkinliğe Katılım
| Gereksinim ID | Gereksinim Açıklaması | Öncelik |
|---------------|------------------------|---------|
| FR-301 | Kullanıcılar mevcut etkinlikleri görüntüleyebilmelidir | Yüksek |
| FR-302 | Kullanıcılar etkinliklere katılım talebi gönderebilmelidir | Yüksek |
| FR-303 | Kullanıcılar etkinliğe katılırken isim, soyisim, yaş ve kaç kişi geleceğini belirtebilmelidir | Yüksek |
| FR-304 | Etkinlik katılım bilgileri SQL veritabanında saklanmalıdır | Yüksek |
| FR-305 | Kullanıcılar katıldıkları etkinlikleri görüntüleyebilmelidir | Orta |
| FR-306 | Kullanıcılar etkinlik katılımlarını iptal edebilmelidir | Orta |
3.4. Arkadaşlık Sistemi
| Gereksinim ID | Gereksinim Açıklaması | Öncelik |
|---------------|------------------------|---------|
| FR-401 | Kullanıcılar diğer kullanıcıları arkadaş olarak ekleyebilmelidir | Yüksek |
| FR-402 | Kullanıcılar etkinliğe katılan diğer kullanıcıları görüntüleyebilmelidir | Yüksek |
| FR-403 | Kullanıcılar etkinliği oluşturan kişiyi arkadaş olarak ekleyebilmelidir | Yüksek |
| FR-404 | Arkadaşlık bilgileri SQL veritabanında saklanmalıdır | Yüksek |
| FR-405 | Kullanıcılar arkadaş listelerini görüntüleyebilmelidir | Orta |
| FR-406 | Kullanıcılar arkadaşlıktan çıkarma işlemi yapabilmelidir | Düşük |
3.5. Arayüz Gereksinimleri
| Gereksinim ID | Gereksinim Açıklaması | Öncelik |
|---------------|------------------------|---------|
| FR-501 | Ana sayfada etkinlik oluşturma formu bulunmalıdır | Yüksek |
| FR-502 | Ana sayfada mevcut etkinlikler listelenmelidir | Yüksek |
| FR-503 | Etkinlik arama ve filtreleme seçenekleri olmalıdır | Orta |
| FR-504 | Kullanıcı profil sayfası olmalıdır | Orta |
| FR-505 | Arkadaş listesi sayfası olmalıdır | Orta |
| FR-506 | Etkinlik detay sayfası olmalıdır | Orta |
4. VERİTABANI GEREKSİNİMLERİ
4.1. Tablolar
| Tablo Adı | Açıklama |
|-----------|----------|
| Kullanıcılar | Kullanıcı hesap bilgilerinin saklandığı tablo |
| Etkinlikler | Etkinlik detaylarının saklandığı tablo |
| Katılımlar | Kullanıcıların etkinliklere katılım bilgilerinin saklandığı tablo |
| Arkadaşlar | Kullanıcılar arasındaki arkadaşlık ilişkilerinin saklandığı tablo |
4.2. Tablo Yapıları
Kullanıcılar Tablosu:
- kullanici_id (PK)
- ad
- soyad
- yas
- email
- sifre
- kayit_tarihi
Etkinlikler Tablosu:
- etkinlik_id (PK)
- olusturan_id (FK)
- etkinlik_adi
- yer
- tarih
- kisi_sayisi
- aciklama
- olusturma_tarihi
Katılımlar Tablosu:
- katilim_id (PK)
- etkinlik_id (FK)
- kullanici_id (FK)
- katilimci_sayisi
- katilim_tarihi
Arkadaşlar Tablosu:
- arkadas_id (PK)
- kullanici_id_1 (FK)
- kullanici_id_2 (FK)
- arkadas_olma_tarihi
5. TEKNİK GEREKSİNİMLER
5.1. Yazılım Gereksinimleri
| Gereksinim ID | Gereksinim Açıklaması | Öncelik |
|---------------|------------------------|---------|
| TR-101 | Web uygulaması HTML/CSS/JavaScript ile geliştirilmelidir | Yüksek |
| TR-102 | Mobil uygulama Flutter ile geliştirilmelidir | Yüksek |
| TR-103 | Veritabanı olarak SQL (MySQL veya PostgreSQL) kullanılmalıdır | Yüksek |
| TR-104 | Backend için Node.js ve Express.js kullanılmalıdır | Orta |
| TR-105 | Responsive tasarım ile farklı cihaz boyutlarına uyum sağlanmalıdır | Orta |
5.2. Güvenlik Gereksinimleri
| Gereksinim ID | Gereksinim Açıklaması | Öncelik |
|---------------|------------------------|---------|
| TR-201 | Kullanıcı şifreleri hash algoritması ile saklanmalıdır | Yüksek |
| TR-202 | Oturum yönetimi JWT token ile sağlanmalıdır | Orta |
| TR-203 | SQL injection saldırılarına karşı önlem alınmalıdır | Yüksek |
| TR-204 | Etkinlik oluşturma ve katılma işlemleri yetkilendirme kontrolüne tabi olmalıdır | Orta |
6. KISITLAMALAR
- Proje 7 hafta içerisinde tamamlanmalıdır
- Veritabanı ve sunucu maliyetleri minimumda tutulmalıdır
- Uygulama performansı mobil cihazlarda da yeterli düzeyde olmalıdır
7. VARSAYIMLAR VE BAĞIMLILIKLAR
- Kullanıcıların internet bağlantısına sahip olduğu varsayılmaktadır
- Kullanıcıların web tarayıcısı veya mobil cihaz kullanabildiği varsayılmaktadır
- Proje kapsamında Google Maps API entegrasyonu gerekebilir
- Bildirim sistemi için Firebase kullanılabilir
8. KABUL KRİTERLERİ
- Kullanıcılar başarıyla kayıt olup giriş yapabilmelidir
- Etkinlik oluşturma ve katılma işlemleri sorunsuz çalışmalıdır
- Arkadaşlık sistemi doğru şekilde işlev görmelidir
- Veritabanı ilişkileri doğru kurulmuş olmalıdır
- Arayüz tasarımı kullanıcı dostu olmalıdır
9. EK DOKÜMANLAR
- UI/UX tasarım taslakları
- Veritabanı ER diyagramı
- API dokümantasyonu
Hazırlayan: Mustafa Talha Demir
Tarih: 23 / 03 /2025 
