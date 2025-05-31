# 🚗 EnviroWatch: Araçlardan Çöp Atan Sürücülerin Tespiti

## 📌 Proje Özeti

**EnviroWatch**, MOBESE kameralarından alınan görüntüler üzerinde çalışarak, araçlardan çöp atan sürücüleri tespit eden yapay zeka destekli bir çevre denetim sistemidir. Sistem, çöp atma olayını tespit ettikten sonra ilgili aracın plakasını tanımlar, tarih ve saat bilgisiyle birlikte kaydeder ve raporlar.

## 🌟 Amaç

* Çevre kirliliğiyle mücadele
* Trafik kurallarının ihlallerini azaltma
* Yerel yönetimlerin denetim gücünü artırma
* Toplumsal çevre bilincini geliştirme

## 🧠 Kullanılan Teknolojiler

* **YOLOv11** – Nesne ve plaka tespiti için
* **Tesseract OCR** – Plaka üzerindeki yazıların okunması
* **OpenCV** – Görüntü işleme
* **PyTorch / TensorFlow** – Derin öğrenme
* **Pandas** – Excel raporlama
* **Python** – Tüm sistemin birleştirilmesi

## 🔍 Sistem Özellikleri

* Gerçek zamanlı araç ve çöp tespiti
* Plaka tanıma ve OCR işlemleri
* Etkin etiketleme ve veri artırma yöntemleri
* Yüksek doğruluk oranları:

  * Araç Tespiti: %95
  * Çöp Tespiti: %90
  * Ortalama Başarı: %92.5
* Excel tabanlı veri kaydı (plaka, tarih, saat, açıklama)

## 📁 Veri Hazırlığı

* Kaggle ve Roboflow üzerinden veri toplandı.
* CVAT ile video ve görseller etiketlendi.
* Etiket hataları (eksik, yanlış, etiketsiz) düzeltildi.
* Etiket koordinatları görselleştirilerek kontrol sağlandı.

## 📸 Çalışma Mantığı

1. MOBESE görüntüsünden çöp atan araç tespiti (YOLO)
2. Plaka bölgesi tespiti (YOLO)
3. OCR ile plaka okunması (Tesseract)
4. Sonuçların Excel dosyasına yazılması

## 📊 Örnek Çıktı

| Plaka    | Tarih      | Saat  | Açıklama               |
| -------- | ---------- | ----- | ---------------------- |
| 34ABC123 | 2025-05-31 | 14:32 | Çöp atma tespit edildi |

## 👥 Ekip

* **Cihat Erensoy**
* **Muhammet Cerrahoğlu**

## 📬 İletişim

- **Cihat Erensoy** - [LinkedIn](https://www.linkedin.com/in/cihat-erensoy-852935253/)
- **Muhammet Cerrahoglu** - [LinkedIn](https://www.linkedin.com/in/muhammet-cerrahoglu/)
