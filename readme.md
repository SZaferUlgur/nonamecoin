# 🪙 CoinAI: Yapay Zeka Destekli Kripto Analiz & Takip Ekosistemi

![Golang](https://img.shields.io/badge/Go-Backend-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-AI_Engine-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-Mobile-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React](https://img.shields.io/badge/React-Web-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux Toolkit](https://img.shields.io/badge/Redux-State_Management-593D88?style=for-the-badge&logo=redux&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-Database-003545?style=for-the-badge&logo=mariadb&logoColor=white)

## 📖 Proje Hakkında

Bu proje, standart bir borsa takip uygulamasının ötesine geçerek, **Python tabanlı Yapay Zeka ve Algoritmik Hesaplama Motoru** ile güçlendirilmiş hibrit bir finans platformudur.

Sistem, anlık piyasa verilerini toplar, **özel geliştirilmiş matematiksel formüllerle** işler ve kullanıcıya hem web hem de mobil ortamda "Al/Sat" sinyalleri, piyasa yorumları ve trend analizleri sunar.

## 🏗️ Mimari ve Teknoloji Yığını

Proje, her biri kendi sorumluluk alanında uzmanlaşmış 3 ana katmandan oluşan bir mikroservis/modüler yapıya sahiptir.

### 1. 🧠 Intelligence Engine (Yapay Zeka & Analiz)
Sistemin beyni olan bu katman, karmaşık hesaplamaları ve doğal dil işlemeyi (NLP) üstlenir.
* **Dil:** Python
* **Özellikler:**
    * **AI Robot:** Piyasa verilerine dayalı otomatik metin tabanlı yorum ve analiz üretimi.
    * **Özel Formüller:** Standart indikatörlerin dışında, proje için özel geliştirilmiş algoritmalar ile risk ve fırsat hesaplamaları.
    * **Veri İşleme:** Büyük veri setlerinin analizi ve veritabanına işlenmesi.

### 2. ⚡ Core API (Backend & Yönetim)
Yüksek performans ve düşük gecikme süresi (low-latency) gerektiren API isteklerini karşılar.
* **Dil:** Golang (Go)
* **Framework:** Fiber v2
* **Veritabanı:** MariaDB
* **İletişim:** REST API & gRPC (Servisler arası iletişim)
* **Rolü:** Mobil ve Web istemcileri ile Python analiz motoru arasındaki köprüyü kurar, kullanıcı yetkilendirmesini (JWT) ve veri akışını yönetir.

### 3. 📱 Frontend & Mobile (Kullanıcı Arayüzü)
Kullanıcı deneyimini en üst düzeye çıkaran, platform bağımsız (Cross-platform) istemci uygulamaları.
* **Mobil:** React Native (iOS & Android)
* **Web:** ReactJS
* **Dil:** **Full JavaScript** (TypeScript kullanılmamıştır, saf JS tercih edilmiştir).
* **State Management:** **Redux Toolkit (RTK) & Slices.**
    * Veri akışı ve durum yönetimi, hem web hem mobil tarafta tutarlı bir mimari (Slice yapısı) ile kurgulanmıştır.

---

## 🌟 Öne Çıkan Özellikler

### 🤖 AI Destekli Piyasa Yorumları
Sadece grafikler değil; Python botu anlık verileri yorumlayarak kullanıcının anlayacağı dilde günlük analiz raporları sunar.

### 🧮 Özel Algoritmik Formüller
Hazır kütüphaneler yerine, projenin dinamiğine uygun olarak geliştirilmiş matematiksel modeller ile coinlerin potansiyel hareketleri önceden hesaplanır.

### 📲 Tam Entegre Mobil Deneyim
React Native ile geliştirilen mobil uygulama, web paneli ile %100 senkronize çalışır. Bildirimler ve portföy takibi cepten yönetilir.

### 🔄 Optimize Edilmiş State Yönetimi (RTK)
Redux Toolkit'in modern "Slice" mimarisi kullanılarak, karmaşık borsa verileri (Order book, Trade history) performanstan ödün vermeden yönetilir.

---

### Backend (Go & Python)
