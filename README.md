<div align="center">

# ⚡ CODUM Social Tools for X (Twitter)
### %100 Şifresiz, Güvenli ve Açık Kaynaklı X (Twitter) Temizlik ve Otomasyon Asistanı

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-4.9_%E2%98%85-brightgreen?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/codum-social-tools/idcnaigkclmjnnnaojjoebkgmbeenfam)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Security: 100% Client-Side](https://img.shields.io/badge/Security-%25100_Yerel_DOM-success)](https://codum.tr)
[![Platform](https://img.shields.io/badge/Platform-X_(Twitter)-000000?logo=x&logoColor=white)](https://x.com)

**Hesap şifrenizi paylaşmadan, pahalı X API ücretlerine katlanmadan ve aşırı istek sınırlarına (rate-limit) takılmadan profilinizi tertemiz yapın.**

[Canlı Demo & Web Sitesi](https://codum.tr) • [Chrome'a Ekle](https://chromewebstore.google.com/detail/codum-social-tools/idcnaigkclmjnnnaojjoebkgmbeenfam) • [Özellikler](#-özellikler) • [Güvenlik Mimarisi](#-güvenlik-mimarisi)

</div>

---

## 📌 Neden CODUM Social Tools?

Çoğu sosyal medya temizleme aracı:
* ❌ Twitter hesap şifrenizi veya hassas oturum çerezlerinizi (cookie) üçüncü parti sunuculara göndermenizi ister.
* ❌ X'in fahiş API fiyatlandırması yüzünden sizden aylık yüksek abonelik ücretleri talep eder.
* ❌ Sabit ve agresif silme yaparak hesabınızı hız sınırına (rate-limit) veya geçici hız sınırlarına (rate-limit) sokar.

**CODUM**, tamamen farklı bir mimariyle çalışır:
* ✅ **Sıfır Şifre:** Bilgileriniz tarayıcınızdan asla çıkmaz; doğrudan açık olan X oturumunuzun sayfa arayüzünü (DOM) kullanır.
* ✅ **API Bağımsız:** X'in resmi API'sini kullanmadığı için zamlardan, kısıtlamalardan etkilenmez.
* ✅ **İnsansı Ritim (Human-Delay Simulation):** Doğal bekleme süreleri ve akıllı limitlerle hesap limitlerine saygılı, kontrollü bir akış sunar.

---

## 🚀 Özellikler

### 1. 🗑️ Toplu Tweet & Yanıt Silme (Bulk Delete Tweets)
* Tek tıkla binlerce eski tweet ve yanıtı silin.
* **Tarih Filtresi:** Belirli bir tarihten öncesini veya sonrasını temizleyin.
* **Kelime & Etkileşim Filtresi:** İstemediğiniz anahtar kelimeleri veya düşük etkileşimli tweetleri hedefleyin.

### 2. 🔁 Retweet (RT) Geri Alma
* Profilinizi dolduran eski retweet ve alıntıları orijinal gönderilerinize dokunmadan tek hamlede geri alın.

### 3. 👥 Geri Takip Etmeyenleri Bulma & Çıkarma (Unfollow)
* Sizi takip etmeyen hesapları listeleyin, istediklerinizi güvenle takipten çıkarın.
* Beyaz liste (Whitelist) desteğiyle önemli kişileri koruyun.

### 4. 📥 1080p X Video İndirme
* Akışta gördüğünüz videoları harici sitelere gitmeden tek tıkla orijinal kalitede indirin.

---

## 🔒 Güvenlik Mimarisi

```
[ Kullanıcı Tarayıcısı ]
         │
         ├── (1) X.com üzerinde açık oturumunuz kullanılır
         ├── (2) İşlemler yerel DOM üzerinden simüle edilir (Sıfır API / Sıfır Şifre)
         └── (3) Verileriniz KESİNLİKLE hiçbir harici sunucuya iletilmez
```

---

## 📦 Kurulum

### Seçenek 1: Chrome Web Mağazası (Önerilen)
Doğrudan [Chrome Web Mağazası](https://chromewebstore.google.com/detail/codum-social-tools/idcnaigkclmjnnnaojjoebkgmbeenfam) üzerinden tek tıkla tarayıcınıza yükleyin.

### Seçenek 2: Manuel Geliştirici Modu (Unpacked)
1. Bu repoyu klonlayın veya zip olarak indirin:
   ```bash
   git clone https://github.com/codumtr/social-tools.git
   ```
2. Chrome'da `chrome://extensions/` adresine gidin.
3. Sağ üstten **Geliştirici Modu**'nu (Developer Mode) açın.
4. **Paketlenmemiş Öğe Yükle** butonuna basarak klasörü seçin.

---

## 📄 Lisans
Bu proje [MIT Lisansı](LICENSE) altında açık kaynak olarak sunulmaktadır.