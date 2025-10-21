# MyNutrio Gizlilik Politikası

**Son Güncelleme:** 21 Ekim 2025  
**Geçerlilik Tarihi:** 21 Ekim 2025

---

## 1. Giriş

MyNutrio uygulamasını kullandığınız için teşekkür ederiz. Gizliliğiniz bizim için son derece önemlidir. Bu Gizlilik Politikası, MyNutrio mobil uygulamasının ("Uygulama") hangi bilgileri topladığını, nasıl kullandığını, sakladığını ve koruduğunu açıklar.

**Uygulama Sahibi:** Dayzen Studio  
**İletişim:** info@dayzenstudio.com  
**Web Sitesi:** https://bayalkan.github.io

Bu Gizlilik Politikası, yalnızca MyNutrio mobil uygulaması için geçerlidir ve Google Play Store üzerinden indirilen uygulama kullanımını kapsar.

---

## 2. Toplanan Bilgiler

### 2.1 Sağlık ve Beslenme Verileri

Uygulamayı kullanırken aşağıdaki sağlık ve beslenme verilerini **gönüllü olarak** sağlarsınız:

**Hedefler ve Limitler:**
- Günlük kalori, protein, karbonhidrat, yağ hedefleri
- Mikro besinler: Vitamin A, B1, B2, B3, B5, B6, B12, C, D, E, K
- Mineraller: Kalsiyum, demir, magnezyum, fosfor, potasyum, sodyum, çinko, bakır, manganez, selenyum, iyot, krom, molibden, florür, klorür
- Diğer besinler: Lif, şeker, kolesterol, omega-3, omega-6, kolin, beta-karoten, likopen, lutein

**Yemek Kayıtları:**
- Tüketilen yiyecekler ve içecekler
- Porsiyon miktarları ve öğün türleri (kahvaltı, öğle, akşam, ara öğün)
- Tüketim zaman damgaları
- Detaylı besin değerleri (50+ besin öğesi)

**Kişisel Sağlık Bilgileri:**
- Kilo hedefi (kilo verme/koruma/artırma)
- Haftalık kilo değişim hedefi (0.25 kg - 1 kg arası)
- Aktivite seviyesi (hareketsiz, hafif aktif, aktif, çok aktif, aşırı aktif)
- Adım sayısı verileri (pedometer entegrasyonu ile)
- Kilo takibi kayıtları

**Alerjiler ve Tercihler:**
- Gıda alerjileri (süt, yumurta, fıstık, soya, buğday, kabuklu deniz ürünleri, vb.)
- Tıbbi durumlar (diyabet, hipertansiyon, kalp hastalığı, vb.)
- Beslenme tercihleri (vegan, vejetaryen, glutensiz, laktozsuz, vb.)

### 2.2 Cihaz ve Kullanım Verileri

**Cihaz Bilgileri (device_info_plus):**
- İşletim sistemi ve versiyonu
- Cihaz modeli ve üreticisi
- Uygulama versiyonu
- Benzersiz cihaz tanımlayıcısı (anonim)

**Kullanım İstatistikleri:**
- Uygulama açılış sayısı ve süreleri
- Hangi özelliklerin kullanıldığı (öğün ekleme, grafik görüntüleme, vb.)
- Hata ve çökme raporları
- Performans metrikleri (Firebase Performance Monitoring)

**Adım Sayacı Verileri (pedometer):**
- Günlük adım sayısı
- Adım sayacı etkinlik geçmişi
- Fiziksel aktivite verileri

### 2.3 Kullanıcı Tercihleri

- Uygulama dili (Türkçe/İngilizce)
- Bildirim ayarları
- Tema seçimi (açık/koyu mod)
- Gizlilik tercihleri (reklam kişiselleştirme, analitik)

### 2.4 Premium Abonelik Bilgileri

- Abonelik durumu (Ücretsiz/Premium)
- Satın alma geçmişi (Google Play Billing üzerinden)
- Premium özellik kullanımı
- Reklam izleme geçmişi ("Reklam İzleyerek Kazan" özelliği için)

---

## 3. Verilerin Kullanımı

Topladığımız veriler **yalnızca** aşağıdaki amaçlarla kullanılır:

### 3.1 Temel Uygulama İşlevleri

- Günlük kalori ve besin değeri hesaplamaları
- Hedeflere göre ilerleme takibi
- Grafik ve raporlar oluşturma
- Öğün önerileri ve yapay zeka destekli beslenme tavsiyeleri
- Sağlık uyarıları (alerji, tıbbi durum bazlı)

### 3.2 Kişiselleştirme

- En çok kullanılan yiyecekleri öncelik sırasına koyma
- Yapay zeka tabanlı yemek önerileri (AI Recommendation Engine)
- Kullanıcı alışkanlıklarına göre özelleştirme

### 3.3 Performans ve Güvenilirlik

- Uygulama hatalarını tespit etme ve düzeltme
- Firebase Performance Monitoring ile performans iyileştirme
- Çökme raporlarını analiz etme

### 3.4 Reklam ve Monetizasyon (Ücretsiz Kullanıcılar)

- Google AdMob reklamlarının gösterilmesi
- Reklam kişiselleştirme (izninizle)
- "Reklam İzleyerek Kazan" özelliği için reklam izleme takibi

---

## 4. Veri Saklama ve Güvenlik

### 4.1 Yerel Veri Saklama

**Tüm sağlık ve beslenme verileriniz CİHAZINIZDA YEREL OLARAK saklanır:**

- **SharedPreferences:** Kullanıcı tercihleri, ayarlar, yemek geçmişi
- **Flutter Secure Storage:** Hassas veriler (abonelik bilgileri, gizlilik tercihleri)
- **SQLite (sqflite):** Yemek kayıtları, kilo geçmişi, hedefler
- **Yerel JSON dosyaları:** Yiyecek veritabanı (assets/foods_database.json)

**ÖNEMLİ:** Verileriniz bizim sunucularımıza GÖNDERİLMEZ. Tüm veriler cihazınızda kalır.

### 4.2 Veri Güvenliği

Verilerinizi korumak için aşağıdaki güvenlik önlemlerini alıyoruz:

- **Şifreleme:** Flutter Secure Storage ile hassas verilerin şifrelenmesi
- **Encrypt Paketi (encrypt: ^5.0.3):** Ek şifreleme katmanı
- **Yerel Depolama:** Veriler internet üzerinden aktarılmaz
- **Güvenli API Kullanımı:** Google Play Billing ve AdMob güvenli API'leri

### 4.3 Veri Saklama Süresi

- Veriler **SİZİN** kontrolünüzdedir
- Uygulamayı sildiğinizde tüm yerel veriler otomatik olarak silinir
- "Tüm Verileri Temizle" özelliği ile istediğiniz zaman verileri silebilirsiniz
- Premium kullanıcılar "Veri Dışa Aktarma" özelliği ile verilerini CSV/PDF formatında alabilir

---

## 5. Üçüncü Taraf Servisler

MyNutrio, belirli işlevler için aşağıdaki üçüncü taraf servislerini kullanır:

### 5.1 Google AdMob (Reklam Servisi)

**Kullanım Amacı:** Ücretsiz kullanıcılara reklam gösterimi  
**Toplanan Veriler:** Cihaz tanımlayıcısı, reklam etkileşimleri, yaklaşık konum (ülke/şehir)  
**Gizlilik Politikası:** https://policies.google.com/privacy  
**Kontrol:** Ayarlar → Gizlilik Merkezi → "Kişiselleştirilmiş Reklamlar" seçeneği

### 5.2 Google Play In-App Billing

**Kullanım Amacı:** Premium abonelik yönetimi  
**Toplanan Veriler:** Satın alma geçmişi, abonelik durumu, ödeme bilgileri (Google tarafından yönetilir)  
**Gizlilik Politikası:** https://payments.google.com/payments/apis-secure/get_legal_document?ldo=0&ldt=privacynotice

### 5.3 Firebase Performance Monitoring

**Kullanım Amacı:** Uygulama performansını izleme ve iyileştirme  
**Toplanan Veriler:** Uygulama açılış süreleri, ekran yükleme süreleri, anonim kullanım metrikleri  
**Gizlilik Politikası:** https://firebase.google.com/support/privacy  
**Kontrol:** Ayarlar → Gizlilik Merkezi → "Analitik Verileri"

### 5.4 Pedometer (Adım Sayacı)

**Kullanım Amacı:** Günlük adım sayısı takibi  
**İzinler:** Fiziksel aktivite sensörlerine erişim (Android: ACTIVITY_RECOGNITION)  
**Veri:** Adım verileri yalnızca cihazda saklanır, paylaşılmaz

---

## 6. Veri Paylaşımı

### 6.1 VERİLERİNİZİ SATMAYIZ

MyNutrio, kişisel verilerinizi **ASLA** üçüncü taraflara satmaz, kiralamaz veya ticari amaçlarla paylaşmaz.

### 6.2 Anonim ve Toplu Veriler

- Uygulama performansını iyileştirmek için **anonim ve toplulaştırılmış** veriler kullanabiliriz
- Bu veriler KİŞİSEL KİMLİK BİLGİLERİNİZİ içermez
- Örnek: "Kullanıcıların %60'ı kahvaltı öğünü ekliyor" gibi istatistikler

### 6.3 Yasal Zorunluluklar

Aşağıdaki durumlarda verilerinizi paylaşmak zorunda kalabiliriz:

- Yasal bir mahkeme kararı veya resmi talep olması durumunda
- Dolandırıcılık veya güvenlik tehdidi tespit edilmesi durumunda
- Kullanım Şartlarımızın ihlal edilmesi durumunda

---

## 7. Kullanıcı Hakları (GDPR ve KVKK Uyumluluğu)

### 7.1 Erişim Hakkı

Uygulama içinde saklanan tüm verilerinize erişebilirsiniz:
- **Ayarlar → Gizlilik Merkezi → "Verilerime Eriş"**

### 7.2 Veri Taşınabilirliği

Premium kullanıcılar verilerini dışa aktarabilir:
- **Ayarlar → Veri Yönetimi → "Veri Dışa Aktar"**
- Desteklenen formatlar: **JSON, CSV, PDF**

### 7.3 Silme Hakkı (Right to Erasure)

Verilerinizi istediğiniz zaman silebilirsiniz:
- **Ayarlar → Gizlilik Merkezi → "Tüm Verileri Sil"**
- **Hesap Silme:** Ayarlar → "Hesabı Sil" (geri alınamaz)

### 7.4 İtiraz Hakkı

Veri işlemeye itiraz edebilirsiniz:
- Kişiselleştirilmiş reklamları kapatabilirsiniz
- Analitik veri toplamayı devre dışı bırakabilirsiniz

### 7.5 İletişim

Gizlilik haklarınızla ilgili talepleriniz için:
- **E-posta:** com.dayzen.nutrioapp üzerinden iletişime geçin
- **Yanıt Süresi:** 30 gün içinde

---

## 8. Çocukların Gizliliği

MyNutrio, **13 yaşın altındaki çocuklar** için tasarlanmamıştır. 13 yaşın altındaki kullanıcılardan bilerek veri toplamıyoruz. Eğer 13 yaşın altında bir çocuğa ait veri topladığımızı fark edersek, derhal sileriz.

**Ebeveynlere Not:** Eğer çocuğunuzun yaş sınırı altında uygulamamızı kullandığını düşünüyorsanız, lütfen bizimle iletişime geçin.

---

## 9. Uluslararası Veri Transferi

- Verileriniz **CİHAZINIZDA YEREL OLARAK** saklandığı için uluslararası veri transferi yoktur
- Firebase Performance Monitoring verileri Google'ın sunucularında (AB ve ABD) saklanabilir
- Google, GDPR uyumlu veri koruma anlaşmaları kullanır

---

## 10. Gizlilik Tercihlerinizi Yönetme

Uygulamadaki **Gizlilik Merkezi** üzerinden tüm tercihlerinizi kontrol edebilirsiniz:

### 10.1 Gizlilik Merkezi Özellikleri

**Ayarlar → Gizlilik Merkezi:**

- ✅ **Genel Gizlilik Onayı:** Uygulama kullanım onayı
- ✅ **Kişiselleştirilmiş Reklamlar:** AdMob reklam kişiselleştirme (açık/kapalı)
- ✅ **Analitik Verileri:** Firebase Performance Monitoring (açık/kapalı)
- ✅ **Verilerime Eriş:** Saklanan tüm verilerin özet görünümü
- ✅ **Veri Dışa Aktar:** JSON/CSV/PDF formatında veri indirme (Premium)
- ✅ **Tüm Verileri Sil:** Tüm yerel verileri kalıcı olarak sil

### 10.2 Bildirim Ayarları

**Ayarlar → Bildirimler:**
- Günlük öğün hatırlatıcıları
- Su içme hatırlatıcıları
- Premium ipuçları

---

## 11. Çerezler ve İzleme Teknolojileri

MyNutrio, **çerez veya web tracking** kullanmaz çünkü:
- Web tabanlı bir uygulama değildir
- Tarayıcı kullanmaz
- Tüm veriler yerel olarak saklanır

**Not:** Google AdMob, reklam gösterimi için kendi tracking teknolojilerini kullanabilir. Bu, Google'ın gizlilik politikasına tabidir.

---

## 12. Veri İhlali Bildirimi

Eğer verilerinizi etkileyen bir güvenlik ihlali meydana gelirse:

- **72 saat içinde** size bildirimde bulunuruz
- E-posta veya uygulama içi bildirim ile
- İhlalin kapsamı ve alınan önlemler açıklanır

**Ancak unutmayın:** Verileriniz cihazınızda yerel olarak saklandığı için merkezi bir veri ihlali riski çok düşüktür.

---

## 13. Politika Değişiklikleri

Bu Gizlilik Politikası zaman zaman güncellenebilir. Değişiklikler olduğunda:

- **"Son Güncelleme"** tarihi değiştirilir
- Önemli değişikliklerde uygulama içi bildirim gönderilir
- Güncel politika her zaman şu adreste erişilebilir:  
  **https://bayalkan.github.io/PRIVACY_POLICY_TR.html**

**Tavsiye:** Bu politikayı düzenli olarak kontrol edin.

---

## 14. İletişim Bilgileri

Gizlilik politikamız veya veri uygulamalarımız hakkında sorularınız varsa:

**Geliştirici:** Dayzen Studio  
**E-posta:** info@dayzenstudio.com  
**Web Sitesi:** https://bayalkan.github.io  
**Destek:** GitHub üzerinden issue açabilirsiniz

**Gizlilik Talepleri:**
- Veri erişimi talepleri
- Veri silme talepleri
- GDPR/KVKK hakları

---

## 15. Yasal Uyum

MyNutrio, aşağıdaki veri koruma yasalarına uygun olarak geliştirilmiştir:

- **GDPR (Avrupa Birliği Genel Veri Koruma Yönetmeliği)**
- **KVKK (Türkiye Kişisel Verilerin Korunması Kanunu)**
- **CCPA (California Consumer Privacy Act)**
- **Google Play Store Veri Güvenliği Gereksinimleri**

---

## 16. Özel Durumlar

### 16.1 Sağlık Verisi Sorumluluk Reddi

MyNutrio, **tıbbi tavsiye, teşhis veya tedavi amaçlı değildir**. Uygulama tarafından sağlanan tüm bilgiler yalnızca genel bilgilendirme amaçlıdır. Ciddi sağlık kararları için mutlaka bir sağlık uzmanına danışın.

### 16.2 Veri Doğruluğu

Uygulamaya girdiğiniz veriler (yiyecekler, porsiyonlar, hedefler) sizin sorumluluğunuzdadır. Hatalı veri girişinden MyNutrio sorumlu tutulamaz.

### 16.3 Üçüncü Taraf Bağlantılar

Uygulama, üçüncü taraf web sitelerine bağlantılar içerebilir. Bu sitelerin gizlilik uygulamalarından sorumlu değiliz. Bağlantılara tıklamadan önce ilgili sitenin gizlilik politikasını incelemenizi öneririz.

---

## 17. Özet (TL;DR - Hızlı Özet)

✅ **Verileriniz cihazınızda yerel olarak saklanır**  
✅ **Verilerinizi ASLA satmayız**  
✅ **İstediğiniz zaman verilerinizi silebilirsiniz**  
✅ **GDPR ve KVKK uyumlu**  
✅ **Reklam kişiselleştirmeyi kapatabilirsiniz**  
✅ **Premium kullanıcılar verilerini dışa aktarabilir**  
✅ **13 yaş altı çocuklar için uygun değil**  
✅ **Firebase Performance Monitoring (anonim)**  
✅ **Google AdMob reklamları (ücretsiz sürüm)**  
✅ **Gizlilik Merkezi ile tam kontrol**

---

**Son Güncelleme:** 21 Ekim 2025  
**Versiyon:** 1.0

Bu politika, MyNutrio 0.0.1+57 sürümü için geçerlidir.

**Teşekkürler!** 🥗💚
