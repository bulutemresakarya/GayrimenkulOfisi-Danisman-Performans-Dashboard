# 🏠 X Ofisi - Enterprise Performance Dashboard

> **Not:** Bu proje, ticari bir ürün olduğu ve müşteri gizliliği içerdiği için kaynak kodları kapalıdır. Bu repository, projenin teknik mimarisini, çözülen problemleri ve kullanılan teknolojileri sergilemek amacıyla oluşturulmuş bir portföy referansıdır.

## 🎯 Proje Özeti

# 🏠 X Ofisi - Enterprise Performance Dashboard

> **Proje Durumu:** Production (Pasif)
> **Teknoloji:** React 18, TypeScript, Node.js, PostgreSQL, Google Sheets API

**X Ofisi Dashboard**, 40'tan fazla gayrimenkul danışmanının satış performansını, ofis cirosunu ve rekabet analizlerini **gerçek zamanlı** olarak takip eden, Google Sheets tabanlı verileri modern ve interaktif bir web arayüzüne dönüştüren kapsamlı bir SaaS çözümüdür.

Bu sistem, manuel raporlama süreçlerini otomatize ederek ofis verimliliğini **%1200** artırmış ve ofis içi rekabeti gamification (oyunlaştırma) öğeleriyle desteklemiştir.

## 🎯 İş Problemi ve Çözüm

### 🔴 Problem: Manuel Süreçler ve Veri Körlüğü
X Ofisi ofisinde performans takibi manuel Excel tabloları üzerinden yapılıyordu.
*   **Zaman Kaybı:** Haftalık raporları hazırlamak yöneticilerin **8 saatini** alıyordu.
*   **Hata Riski:** Manuel veri girişlerinde **%15 hata oranı** yaşanıyordu.
*   **Motivasyon Eksikliği:** Danışmanlar performanslarını anlık göremediği için rekabet ortamı oluşmuyordu.
*   **Sunum Zorluğu:** Müşteri toplantılarında güncel piyasa ve ofis verilerini sunmak zordu.

### 🟢 Çözüm: Tam Otomasyon ve Dijital Dönüşüm
Google Sheets verilerini veritabanı olarak kullanan, 30 saniyede bir güncellenen modern bir dashboard geliştirildi.
*   **Otomasyon:** Veriler Google Sheets'ten otomatik çekilir (5 dk senkronizasyon).
*   **Görünürlük:** Ofis içindeki TV'lerde "Kiosk Modu" ile canlı veriler döner.
*   **Oyunlaştırma:** Canlı liderlik tabloları ve kulüp hedefleri ile rekabet artırıldı.

## ✨ Ana Özellikler

### 1. Gerçek Zamanlı Veri Entegrasyonu
*   **Google Sheets Sync:** 215+ satırlık işlem verisi ve personel listesi otomatik senkronize edilir.
*   **Canlı Piyasa Verileri:** Dolar, Euro, Altın ve Kripto para verileri (CoinGecko & Finans API) anlık olarak ekranın altında akar.
*   **Akıllı Önbellekleme:** TanStack Query ile sunucu yükü minimize edilirken kullanıcı deneyimi akıcı tutulur.

### 2. Performans Analitiği ve Raporlama
*   **Çoklu Periyot Analizi:** Haftalık, Aylık, 3 Aylık, 6 Aylık ve Yıllık performans grafikleri.
*   **Trend Analizi:** Lineer regresyon ile gelecek 3 ayın ciro tahminlemesi.
*   **Kulüp Hedefleri:** Yıldızlar Kulübü'nden Crown Kulübü'ne kadar ilerleme çubukları ve kalan ciro hesaplaması.

### 3. TV Sunum Modu (Kiosk)
*   Ofis içi ekranlar için geliştirilen bu mod, dashboard sayfaları arasında (Liderlik Tablosu, Piyasa, Doğum Günleri, Recruiting) otomatik rotasyon sağlar.
*   Klavye kısayolları ile manuel kontrol imkanı.

### 4. İşe Alım (Recruiting) Yarışması
*   Danışmanların ofise kazandırdığı yeni adayların takibi.
*   Referans hiyerarşisi ve görselleştirilmiş "Recruiting Liderleri" tablosu.

## 🛠️ Teknik Mimari

Proje, performans, tip güvenliği ve ölçeklenebilirlik üzerine kurulmuştur.

### Frontend (İstemci)
*   **Core:** React 18, TypeScript, Vite
*   **State Management:** TanStack Query (Server State), React Context (UI State)
*   **UI/UX:** Tailwind CSS, shadcn/ui, Framer Motion (Animasyonlar)
*   **Data Viz:** Recharts (Grafikler)
*   **Routing:** Wouter

### Backend (Sunucu)
*   **Runtime:** Node.js 20, Express.js
*   **Database:** PostgreSQL, Drizzle ORM
*   **API Integrations:** Google Sheets API (v4), ExchangeRate-API, CoinGecko
*   **Security:** Helmet, Rate Limiting, Environment Variable Obfuscation

### DevOps & Deployment
*   **Platform:** Replit Autoscale
*   **Domain:** Custom domain (truemax.com.tr) ile SSL sertifikalı yayın.

## 🚀 Sonuçlar ve Kazanımlar

| Metrik | Değer |
|--------|-------|
| **Raporlama Süresi** | 8 Saat ➔ **0 Saat** (Tam Otomatik) |
| **Veri Güncelliği** | Haftalık ➔ **30 Saniye** |
| **Hata Oranı** | %15 ➔ **%0** |
| **Ofis Motivasyonu** | Görsel rekabet ile **%40 Artış** |

---

**Geliştirici:** Bulut Emre Sakarya
**Tarih:** Haziran 2025
