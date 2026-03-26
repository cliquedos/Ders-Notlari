# Ağ Yönetimi ve Bilgi Güvenliği
---
## Ünite Bir
---

## 1. Ağ Tarihçesi ve Temel Kavramlar

### ARPANET ve Paket Anahtarlama
- **ARPANET (DARPA)**: ABD Savunma Bakanlığı tarafından askeri ve stratejik bilgi paylaşımı için geliştirildi. Paket anahtarlamanın ilk uygulamasıdır.
- **1969**: İlk paket anahtarlamalı bağlantı UCLA – Stanford arasında yapıldı. Günümüz internetinin temeli.
- **Paket anahtarlama**: Verinin küçük paketlere bölünüp ayrı ayrı iletilmesi; devre anahtarlamaya göre daha verimli.

### Protokol Kavramı
- **Protokol**: Bilgisayarlar arası haberleşmede mesaj biçimi, sırası, gönderim ve alım kurallarını tanımlayan kurallar dizisi.

### Önemli Tarihler
- **1970’ler**: TCP/IP mimarisi ortaya çıktı. Telnet, FTP geliştirildi.
- **1972**: Ethernet geliştirilmeye başlandı; e-posta ve “@” kullanımı.
- **1986**: ABD Ulusal Bilim Vakfı 56 Kbps ortak ağ altyapısı.
- **1989**: WWW (World Wide Web).

---

## 2. Ağ Çeşitleri

### Büyüklüklerine Göre Ağlar
| Tür | Açıklama |
|-----|----------|
| **PAN** | Kişisel cihazlar (akıllı telefon, tablet) arasında USB, Bluetooth ile bağlantı. |
| **LAN** | Yakın coğrafi konum; ev, okul, laboratuvar. İlk ağ çeşidi. |
| **MAN** | Şehir veya kampüs çapında; fiber optik, WiMAX; router kullanılır. |
| **WAN** | LAN ve MAN’ların birleşimi; **İnternet** en büyük WAN’dır. |
| **VPN** | Uzaktaki cihazı ağa sanal olarak bağlar. |

---

## 3. Ağ Topolojileri

| Topoloji | Özellikler |
|----------|------------|
| **Ortak Yol (BUS)** | Tek kablo, BNC konnektör, sonlandırıcı gerekli, merkez birim yok. Kurulumu en basit. |
| **Halka (Ring)** | Her cihaz kendi zaman diliminde veri gönderir. Tek cihaz arızası tüm ağı etkiler. |
| **Örgü (Mesh)** | Her düğüm birbirine bağlı; hatalı düğümler veri akışını engellemez. |
| **Ağaç (Tree)** | En az 3 seviye; merkez düğüme alt düğümler bağlı. |
| **Yıldız (Star)** | Merkezde switch (kablolu) veya access point (kablosuz). Günümüz LAN’larında en yaygın. |

---

## 4. Bağlantı Ortamları ve Ağ Cihazları

### Bağlantı Ortamları (Kablolu)
- **UTP Kablo**: Cat2 (4 Mbps) – Cat6a (10 Gbps); RJ45 konnektör; 100 m menzil.
- **Fiber Optik Kablo**: Işıkla veri iletimi; yüksek hız, uzun mesafe, yüksek maliyet.
- **Coaxial Kablo**: BNC konnektör; eski teknoloji.

### Bağlantı Ortamları (Kablosuz)
- **Wi-Fi (IEEE 802.11)**: 802.11a (5 GHz, 54 Mbps), 802.11b (2,4 GHz, 11 Mbps), 802.11g (2,4 GHz, 54 Mbps), 802.11n (300 Mbps).
- **GSM tabanlı**: GPRS, EDGE, 3G (28 Mbps), 4.5G (375 Mbps), 5G (4.7 Gbit/sn).
- **Kablosuz güvenlik**: WEP (zayıf), WPA, WPA2, WPS.

### Ağ Cihazları
- **Tekrarlayıcı (Repeater)**: Fiziksel katmanda çalışır; sinyali güçlendirerek mesafeyi artırır. Çok arayüzlü olanına **Hub** denir.
- **Yönlendirici (Router)**: Ağ katmanında çalışır; IP adresine göre paketleri yönlendirir.
- **Anahtar (Switch)**: Veri bağlantı katmanında çalışır; MAC adresine göre çerçeveleri yönlendirir.

---

## 5. Ağ Katmanları ve Protokoller

### TCP/IP Modeli Katmanları
1. **Uygulama Katmanı** – HTTP, SMTP, POP3, FTP, DNS
2. **Taşıma Katmanı** – TCP, UDP
3. **Ağ Katmanı** – IPv4, IPv6, ARP, yönlendirme
4. **Ağ Erişim Katmanı** – MAC, fiziksel ortam

### Uygulama Katmanı Protokolleri
- **HTTP/HTTPS**: Web sayfaları; HTTPS güvenli sürümdür.
- **FTP**: Dosya transferi; TCP kullanır, güvenli ve eksiksiz teslim.
- **SMTP**: E-posta gönderme.
- **POP3 / IMAP**: E-posta alma.
- **DNS**: Alan adını IP adresine çevirir.

### Taşıma Katmanı (TCP ve UDP Karşılaştırması)
| Özellik | TCP | UDP |
|---------|-----|-----|
| Bağlantı | Bağlantı tabanlı (3 yollu el sıkışma) | Bağlantısız |
| Güvenilirlik | Var (onay, yeniden iletim) | Yok |
| Sıralı Gönderim | Var | Yok |
| Akış/Tıkanıklık Kontrolü | Var | Yok |
| Çoklu Alıcıya Gönderim | Yok | Var |
| Başlık Boyutu | 20-60 Bayt | 8 Bayt |
| Kullanım Alanı | Web, e-posta, FTP | Ses/video, DNS sorguları |

### Ağ Katmanı
- **IPv4**: 32 bit, 4 blok (örn. 193.140.129.130). NAT ile yerel ağlarda sanal IP kullanımı.
- **IPv6**: 128 bit, 8 blok (16’lık tabanda). IPv4 adres sıkıntısını çözmek için geliştirildi.
- **ARP**: IP adresinden MAC adresini bulmak için kullanılır.
- **Yönlendirici (Router)**: IP adresine göre yönlendirme yapar.

### Veri Bağlantı Katmanı
- **MAC adresi**: 48 bit, her ağ kartına özel, benzersiz.
- **Hata yakalama yöntemleri**: Checksum, Parity Checking, CRC-32 (en yaygın).
- **MAC protokolü**: Veri hattını kimin kullanacağına karar verir; çarpışma (collision) durumunda yeniden gönderme.
- **Çerçeveleme (Framing)**: Verinin başını ve sonunu belirleme.

### Fiziksel Katman
- Donanım katmanı; kablolu ve kablosuz veri yollarını oluşturur.
- Sayısal verileri voltaj (kablolu) veya dalga (kablosuz) olarak kodlar.

---

## 6. Ağ Yönetimi ve SNMP

### Ağ Yönetim Çeşitleri (ISO 5 Kategori)
| Yönetim Türü | Görevi |
|--------------|--------|
| **Performans Yönetimi** | Ağ verimliliğini, çıkış gücünü ölçme, analiz etme, raporlama. |
| **Hata Yönetimi** | Arızaları kaydetme, raporlama, aksiyon alma. |
| **Yapılandırma Yönetimi** | Cihazların durumu ve yapılandırmaları hakkında bilgi sahibi olma. |
| **Hesaplama Yönetimi** | Ağ kaynaklarının nasıl kullanıldığını izleme (ör. kota yönetimi). |
| **Güvenlik Yönetimi** | Yetkisiz girişleri engelleme, zararlı yazılımları pasifleştirme. |

### Ağ Yönetim Altyapısı (SNMP)
- **Yönetici Öğe (Manager)**: Ağ merkezinde çalışan, ağ bilgilerini sağlayan yazılım.
- **Yönetilen Cihaz (Agent)**: Ağa bağlı donanım ve üzerindeki uygulama (bilgisayar, switch, router).
- **Yönetim Bilgi Üssü (MIB)**: Reddedilen IP’ler, çarpışma hataları, DNS sürümleri, yönlendirme haritaları gibi bilgilerin toplandığı veri tabanı.
- **Yönetim Protokolü (SNMP)**: Yönetici öge ile yönetilen cihaz arasında köprü; ortak dil sağlar.
- **SMI (Structure of Management Information)**: Veri tipleri, nesne modeli, yazım kuralları; veri biçimini tanımlar.

### SNMP Bileşenleri
1. **Araç Uygulama (Agent)** – Cihaz üzerinde SNMP hizmetini çalıştırır.
2. **Yönetici Uygulama (Manager)** – Araç uygulamadan bilgileri alır, yöneticiye sunar, değişiklik isteklerini iletir.
3. **Ağ Yönetim Sistemi (NMS)** – Yönetici birimde çalışan, tüm cihazların izlenmesini ve yönetimini sağlayan sistem.

---

## 7. Kriptografi ve Bilgi Güvenliği (Ara Sınavlarda Çıkan Konular)

### Temel Tanımlar
- **Kriptografi**: Kullanıcılar arasında güvenli iletişim için algoritma ve protokolleri tasarlayan bilim dalı.
- **Simetrik Şifreleme**: Aynı anahtar şifreleme ve deşifreleme için kullanılır. Hızlıdır. Örnek: DES, 3DES, AES, IDEA.
- **Asimetrik Şifreleme (Açık Anahtar)**: Açık anahtar şifreleme, gizli anahtar deşifreleme için kullanılır. Örnek: RSA, ElGamal, Diffie-Hellman.

### Simetrik Şifreleme Algoritmaları
- **DES (Data Encryption Standard)**: 64 bit blok, 56 bit anahtar. Uzun yıllar kullanılmış, üzerinde en çok araştırma yapılan algoritma.
- **AES (Advanced Encryption Standard)**: Günümüzde yaygın; farklı anahtar boyutları (128, 192, 256 bit). İşlem katmanları: Bayt yer değiştirme, satır kaydırma, sütun karıştırma (son tur hariç), anahtar ekleme.
- **Blok Şifreleme**: Veriyi eşit uzunlukta bloklara ayırır. Modlar: ECB, CBC, CFB, OFB.
- **Sezar Şifreleme**: Harflerin belirli sayıda ötelenmesiyle yapılan en eski yöntem.
- **Affine Şifreleme**: Sezar’ın genelleştirilmiş hali; Türk alfabesi (29 harf) için anahtar uzayı 812’dir.

### Asimetrik Şifreleme (RSA)
- **RSA**: Büyük sayıları asal çarpanlarına ayırmanın zorluğuna dayanır.
- **Formüller**:
  - n = p × q
  - φ(n) = (p-1)(q-1)
- **Kullanım Amaçları**: İnkâr edilemezlik, kimlik doğrulama, oturum anahtarı paylaşımı, güvenli veri saklama.

### Dijital İmza ve Özet Fonksiyonları
- **Dijital İmza**: Benzersiz olmalı, imzalanan metne bağımlı olmalı, doğrulama kolay, taklit edilmesi zor olmalıdır.
- **Özet Fonksiyonları (Hash)**: Mesaj bütünlüğü kontrolü, dijital imza oluşturma, parola saklama, dosya bütünlüğü doğrulama.

### Güvenlik Servisleri
- **Gizlilik**: Verinin yetkisiz kişilerce okunmasını engelleme.
- **Mesaj Bütünlüğü**: Verinin değiştirilmesini engelleme.
- **Erişim Kontrolü**: Yetkisiz erişimi engelleme.
- **Kimlik Doğrulama**: Kullanıcının kimliğini doğrulama.
- **Fiziksel Güvenlik**: Donanımı, çevresel faktörleri ve doğal afetleri koruma.

---
