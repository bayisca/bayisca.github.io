---
title: "Akademik Takip Sistemi (ATS) v1.4"
date: 2026-02-06T16:16:46+03:00
draft: false
tags: ["Python", "PyQt6", "Projelerim"]
---

Üniversite hayatınızı kolaylaştırmak için tasarlanmış; derslerinizi, devamsızlıklarınızı ve akademik başarınızı tek merkezden yönetmenizi sağlayan modern bir masaüstü uygulamasıdır.

## 🚀 v1.4 Yenilikleri ve Özellikler


*   📅 **Haftalık Ders Programı:** Görsel ve interaktif program arayüzü. Anlık saat çizgisi, bugün vurgusu ve çift tıklama ile hızlı düzenleme.
*   🚦 **Akıllı Devamsızlık Takibi:** Ders programı kartları üzerinde anlık devamsızlık gösterimi; zorunluluk muafiyeti desteği ve renk kodlu uyarı sistemi.
*   📊 **Akademik Analiz:** Anlık AGNO hesaplama, dönem ortalamaları ve grafik bazlı başarı takibi.
*   🗓️ **Sınav & Quiz Takvimi:** Sınav ve quiz tarihlerinin ders programına otomatik entegrasyonu; yaklaşan sınav kartları ve kalan gün sayacı.
*   🎯 **Hedef Harf & Final Hesaplayıcı:** Her ders için hedef not belirleyebilme ve gereken final notunu hesaplama.
*   🌓 **Dinamik Tema Motoru:** Tokyo Midnight (Karanlık) ve Aydınlık mod; tam uyumlu, göz yormayan tasarım.
*   📄 **Raporlama:** Dönem bazlı PDF transkript özeti oluşturma.
*   🎓 **Gazi OBSS Entegrasyonu:** OBSS üzerinden ders ve not bilgilerini otomatik olarak içe aktarma (Beta).
*   💾 **Veri Güvenliği:** Veriler `AppData` altında güvenli biçimde saklanır. Manuel yedekleme ve geri yükleme desteği.

# 🛠️ Teknolojiler
*   **Dil:** Python 3.x
*   **Arayüz:** PyQt6 (Modern & Responsive GUI)
*   **Raporlama:** PyQt6 QPrinter — PDF çıktısı
*   **Ağ:** `requests` kütüphanesi — OBSS oturum yönetimi
*   **Depolama:** JSON (AppData klasöründe yerel veritabanı)
## 📂 Proje Yapısı
Proje, kodun yönetilebilirliğini artırmak için modüler bir yapıda tasarlanmıştır:
```
Akademik-Takip-Sistemi/
├── main.py                  # Uygulamanın giriş noktası
├── backend/
│   ├── models.py            # Veri modelleri (Course, ScheduleEntry, SettingsManager)
│   ├── logic.py             # İş mantığı ve veri yönetimi (AcademicManager)
│   ├── report_manager.py    # PDF transkript oluşturma
│   └── obs_sync.py          # Gazi OBSS oturum ve veri çekme motoru
├── frontend/
│   ├── main_window.py       # Ana pencere ve sekme yönetimi
│   ├── schedule_view.py     # Haftalık ders programı görünümü
│   ├── stats_view.py        # Genel akademik durum ve istatistikler
│   ├── dialogs.py           # Tüm diyalog pencereleri (ders düzenleme, OBSS girişi vb.)
│   ├── components.py        # Yeniden kullanılabilir bileşenler (GradeChart, ToggleSwitch)
│   └── styles.py            # Tema renk paletleri ve QSS stilleri
└── assets/
    └── pencil_icon.ico      # Uygulama ikonu
```

## 🖼️ Ekran Görüntüleri

![ATS Projesi Ekran Görüntüsü](/images/ders-listesi.png)
![ATS Projesi Ekran Görüntüsü](/images/genel-durum.png)
![ATS Projesi Ekran Görüntüsü](/images/ders-programi.png)
![ATS Projesi Ekran Görüntüsü](/images/hakkinda.png)
![ATS Projesi Ekran Görüntüsü](/images/ders-ekle.png)

## 📥 Uygulamayı İndir

ATS v1.4 sürümünü bilgisayarınıza indirip anında kullanmaya başlamak için tıklayın:

[🚀 ATS'yi İndir](/Akademik%20Takip%20Sistemi.exe)

> [!TIP]
> **Windows Defender Notu:** Uygulama imzalanmamış bir .exe olduğu için Windows başlangıçta uyarı verebilir. "Ek Bilgi" -> "Yine de Çalıştır" diyerek güvenle başlatabilirsiniz.

## 👨‍💻 Geliştirici

* **Geliştirici:** İsmail Can Anlaş
* **Versiyon:** 1.4

## 📜 Versiyon Geçmişi
| Versiyon | Tarih | Yenilikler |
| :--- | :--- | :--- |
| **v1.4** | **17.04.2026** | **Ders Programı, Akıllı Devamsızlık ve Tema İyileştirmeleri** |
| v1.3 | 21.03.2026 | Genel performans ve sınav takip sistemi |
| v1.0 | 06.02.2026 | İlk kararlı sürüm yayını |
---
*Not: Bu proje eğitim ve kişisel kullanım amaçlı geliştirilmiştir.*

"Copyright © 2026 İsmail Can Anlaş. All rights reserved. No part of this software may be reproduced or distributed."