---
title: "Akademik Takip Sistemi (ATS) v3.2"
date: 2026-02-06T16:16:46+03:00
draft: false
tags: ["Python", "PyQt6", "Projelerim"]
---

# Açıklama

Akademik Takip Sistemi (ATS), üniversite öğrencilerinin ders notlarını, ortalamalarını ve akademik başarılarını takip etmelerini sağlayan modern ve kullanıcı dostu bir masaüstü uygulamasıdır. Python ve PyQt6 kullanılarak geliştirilmiştir.

## 🚀 Özellikler

* **Ders Yönetimi:** Derslerinizi dönem, kredi, not ve tür (Alan/Havuz) bilgileriyle ekleyin, düzenleyin veya silin.
* **Gelişmiş Filtreleme:** Dersleri döneme veya harf notuna göre anlık olarak filtreleyerek görüntüleyin.
* **AGNO ve İstatistikler:**
    * Genel Ağırlıklı Not Ortalaması (AGNO/GNO) hesaplama.
    * Toplam kredi takibi.
    * Dönem bazlı ortalama ve başarı grafiği.
* **Sınav Takibi:** Yaklaşan sınavlarınızı ve kalan gün sayısını "Genel Durum" ekranında takip edin.
* **Veri Yönetimi:**
    * Verileri JSON formatında otomatik kaydetme.
    * Yedekleme (Dışa Aktar) ve Geri Yükleme (İçe Aktar) seçenekleri.
    * **PDF Çıktısı:** Transkript benzeri akademik durum raporu oluşturma.
* **Modern Arayüz:**
    * **Tokyo Midnight** temalı karanlık mod.
    * Açık/Koyu tema desteği.
    * Responsive ve estetik tasarım.

## 🛠️ Teknolojiler

Bu proje aşağıdaki teknolojiler kullanılarak geliştirilmiştir:

* **Dil:** Python 3.x
* **Arayüz:** PyQt6 (Modern GUI Framework)
* **Veri Saklama:** JSON (Yerel depolama)

## 📂 Proje Yapısı

Proje, kodun yönetilebilirliğini artırmak için modüler bir yapıda tasarlanmıştır:

* `main.py`: Uygulamanın giriş noktası.
* `backend/`: Veri yönetimi ve iş mantığı.
* `frontend/`: Kullanıcı arayüzü dosyaları.
* `assets/`: İkonlar ve görsel kaynaklar.
* `data/`: Kullanıcı verilerinin saklandığı dizin.

## 🖼️ Ekran Görüntüleri

![ATS Projesi Ekran Görüntüsü](/images/ders-listesi.png)
![ATS Projesi Ekran Görüntüsü](/images/genel-durum.png)
![ATS Projesi Ekran Görüntüsü](/images/hakkinda.png)
![ATS Projesi Ekran Görüntüsü](/images/ders-ekle.png)

## 📥 Uygulamayı İndir

ATS v3.2 sürümünü bilgisayarınıza indirip anında kullanmaya başlamak için tıklayın:

[🚀 ATS v3.2'yi İndir (Windows .exe)](/ats-guncel.exe)

*Not: Kurulum gerektirmez, indirip çift tıklamanız yeterlidir. Windows Defender yazısına aldanmayın yine de çalıştıra basın*

## 👨‍💻 Geliştirici

* **Geliştirici:** İsmail Can Anlaş
* **Versiyon:** 3.2

---
*Not: Bu proje eğitim ve kişisel kullanım amaçlı geliştirilmiştir.*