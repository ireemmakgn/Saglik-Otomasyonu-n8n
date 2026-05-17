# 🏥 n8n ile Akıllı Sağlık Risk Analiz Otomasyonu

Bu proje, Google Sheets ve Google Gemini yapay zeka modelini n8n otomasyon altyapısı kullanarak birleştiren bir Sağlık Bilişimi projesidir.

## 🚀 Projenin Çalışma Mantığı
1. **Google Sheets Trigger:** Tabloya yeni bir hasta kaydı (Ad, Yaş, Şeker Değeri, Şikayet) girildiğinde otomasyon otomatik olarak tetiklenir.
2. **Data Split & Loop:** Eklenen veriler hız limitlerine takılmamak adına tek tek döngüye sokulur.
3. **Google Gemini AI:** Hasta verileri yapay zekaya gönderilerek otomatik bir tıbbi risk analizi raporu hazırlanır.
4. **Google Sheets Update:** Üretilen risk analizi raporu, ilgili hastanın satırındaki boş sütuna otomatik olarak geri yazılır.

## 🛠️ Kullanılan Teknolojiler
* **n8n** (Workflow Automation)
* **Google Gemini API** (Yapay Zeka Analizi)
* **Google Sheets** (Veritabanı / Dashboard Girdisi)
