# 🏔️ Nexo Grower –  Distribution System

<div align="center">

**Uçtan uca üretim, dağıtım ve çoklu şube yönetim platformu**

![Status](https://img.shields.io/badge/status-geliştirme%20aşaması-yellow?style=flat-square)
![License](https://img.shields.io/badge/license-proprietary-red?style=flat-square)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20mobile%20%7C%20desktop-blue?style=flat-square)
![Made by](https://img.shields.io/badge/made%20by-ZeroDay%20Software-black?style=flat-square)

</div>

---

## 📌 Nedir?

Nexo Grower ( Distribution System), üretim tesisinden son tüketiciye kadar tüm süreçleri entegre eden **çok şubeli**, **merkezden yönetilen**, **gerçek zamanlı izlenebilir** bir dağıtım ve operasyon yönetim sistemidir.

### Temel Hedefler

- ✅ Ham maddeden son satışa **tam ürün izlenebilirliği**
- ✅ Merkezi denetim + şube bazlı **operasyonel esneklik**
- ✅ **Gerçek zamanlı** veri görünürlüğü ve karar destek mekanizmaları
- ✅ **Offline çalışabilme** yeteneği
- ✅ Mobil e-ticaret ve **akıllı teslimat** entegrasyonu

---

## 🗺️ Sistem Mimarisi

```
Ham Madde → Üretim → Kalite → Paketleme
                  ↓
         Şube Depoları  ↔  Şubeler Arası Transfer (Merkez Onaylı)
                  ↓
   POS / Mobil App / E-ticaret / Pazaryeri / Bayi
                  ↓
         Akıllı Yönlendirme (Smart Fulfillment)
                  ↓
       Müşteri Teslimatı + Bildirimler
                  ↕
   Merkez Dashboard + AI Optimizasyon + Raporlama
```

---

## ✨ Özellikler

### 📦 Ürün & Stok Yönetimi

SKU bazlı tam izlenebilirlik ile her ürünün yaşam döngüsü eksiksiz kayıt altına alınır:

```
Ham madde → Üretim (kesim/dikim/montaj) → Ara stok → Kalite kontrol
         → Fire kaydı → Paketleme → Şube girişi → Satış (POS / online / bayi)
```

> 💡 *"Bu ürün hangi hammaddeden, hangi tarihte, hangi personel tarafından, hangi şubede üretildi ve kime satıldı?"* sorusuna her zaman yanıt verilebilir.

---

### 🏢 Çoklu Şube & Merkez Yapısı

- +50 şube ölçeğine uygun tasarım
- Şubeler arası stok transferi (merkez onayı ile)
- Merkez gerçek zamanlı görünürlük:

| Görünürlük Alanı | Detay |
|---|---|
| 📊 Şube stokları | Anlık stok durumu |
| 🏭 Üretim adetleri | Günlük/haftalık üretim takibi |
| 💰 Satış & Kâr/Maliyet | Şube bazlı finansal görünüm |
| 👤 Personel performansı | Bireysel verimlilik metrikleri |
| 🔥 Fire oranları | Üretim kayıp analizi |

---

### 🔐 Rol Bazlı Erişim (RBAC)

| Rol | Yetki |
|---|---|
| **Şube Personeli** | Yalnızca kendi şubesinin verilerini görür |
| **Şube Yöneticisi** | Şube operasyonlarını yönetir |
| **Genel Merkez** | Tüm şubeleri görür, müdahale eder; fiyat/kampanya/üretim reçetelerini belirler |

---

### 🛒 Satış Kanalları

- 🖥️ Fiziksel POS
- 📱 E-ticaret & Mobil Uygulama
- 🏪 Pazaryerleri
- 🤝 Bayi Satışları

> Online ve mağaza stokları gerçek zamanlı senkronize edilir.

---

### 📡 Offline Çalışma Yeteneği

- POS ve şube sistemleri tamamen **offline** çalışır
- Bağlantı geldiğinde **otomatik senkronizasyon**
- Çakışmalar merkez kurallarıyla otomatik çözülür

---

### 🤖 Yapay Zeka Destekli Optimizasyon

- 📈 **Talep tahmini** – geçmiş veriye dayalı satış projeksiyonu
- 🔄 **Otomatik transfer önerileri** – şubeler arası dengeleme
- 🏭 **Üretim yeniden planlama** – anlık talep değişimlerine adaptasyon
- ♻️ **Fire optimizasyonu** – kayıp minimizasyonu

---

### 🚀 Smart Fulfillment – En Yakın Şubeden Teslim

Otomatik şube seçimi için kullanılan kriterler:

| Kriter | Açıklama |
|---|---|
| 📍 Coğrafi yakınlık | Müşteriye en yakın şube |
| 📦 Stok durumu | İlgili ürünün mevcut olduğu şube |
| ⚙️ Operasyonel kapasite | Şubenin anlık iş yükü |
| ⭐ Performans skoru | Geçmiş teslimat başarısı |

> Teslimat süresi ve kargo maliyeti otomatik olarak optimize edilir.

---

### 📱 Mobil E-Ticaret Entegrasyonu

- ⚡ Çift yönlü gerçek zamanlı senkronizasyon
- 🔔 Push notification, e-posta, SMS bildirimleri
- 📦 Sipariş → Paketleme → Kargo → Teslimat akışı
- 🗺️ Canlı takip ve ETA tahmini *(geliştirme aşaması)*

---

### 📊 Raporlama & Denetim

- Uçtan uca veri akış raporları
- Şube-merkez performans karşılaştırmaları
- Ürün yaşam döngüsü analizleri
- Append-only audit log *(7 yıl saklama)*
- Alarm & uyarı sistemi *(kritik stok, yüksek fire, offline şube vb.)*

---

### 🔒 Güvenlik & Kontrol

- JWT / OAuth2 API koruması
- Çoklu onay mekanizmaları *(yüksek riskli işlemler)*
- Merkez override yetkisi
- Fiyat ve maliyet kilitleri

---

## 🛠️ Teknoloji Yığını

| Katman | Teknoloji |
|---|---|
| **Backend** | .NET / Node.js / Python (Django/FastAPI) |
| **Frontend** | React / Vue.js |
| **Mobil** | React Native / Flutter |
| **Veritabanı** | PostgreSQL + TimescaleDB + Redis |
| **Mesajlaşma** | RabbitMQ / Kafka |
| **AI/ML** | Python (scikit-learn / TensorFlow / PyTorch) |
| **Bildirim** | Firebase Cloud Messaging + OneSignal |
| **Kargo** | API tabanlı (Yurtiçi, Aras, MNG vb.) |
| **Deployment** | Docker + Kubernetes |

---

## 🚀 Kurulum

> ⚠️ Proje şu an **kapalı geliştirme aşamasında**. Kurulum talimatları ve demo ortamı yakında eklenecek.

```bash
# Repo hazır olduğunda:
git clone https://github.com/berat-eth/Nexo Grower.git
cd Nexo Grower
docker-compose up -d
```

---

## 🤝 Katkıda Bulunma

Şu an kapalı geliştirme sürecindeyiz. İlerleyen dönemde açık kaynak bileşenler veya katkı rehberi yayınlanabilir.

---

## 📄 Lisans

© 2025–2026  / Berat Şimşek 
Tüm hakları saklıdır. *(Henüz açık kaynak lisansı belirlenmemiştir)*

---

## 📬 İletişim

<div align="center">

[![X (Twitter)](https://img.shields.io/badge/X-@zerodaysoftware-black?style=for-the-badge&logo=x)](https://x.com/berat.weth)

</div>

---

<div align="center">
<sub>Nexo Grower – Akıllı, izlenebilir ve kendini optimize eden bir operasyon platformu.</sub>
</div>
