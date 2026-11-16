# Deskio School

Modern, hafif ve yüksek performanslı okul laboratuvarı ve sınıf yönetim sistemi.

---

## 🚀 İndirme & Sürümler (v1.0.0)

En son kararlı sürüm dosyalarını doğrudan [Releases](https://github.com/Deskio-School/deskio-app/releases/latest) sayfasından edinebilirsiniz:

| Dosya | Açıklama |
| :--- | :--- |
| **[Deskio-Teacher-Console.exe](https://github.com/Deskio-School/deskio-app/releases/latest/download/Deskio-Teacher-Console.exe)** | Öğretmen Kontrol Konsolu (Taşınabilir / Kurulumsuz) |
| **[Deskio-Student.exe](https://github.com/Deskio-School/deskio-app/releases/latest/download/Deskio-Student.exe)** | Öğrenci İstemcisi & Arka Plan Ajanı |
| **[Deploy-DeskioStudent.ps1](https://github.com/Deskio-School/deskio-app/releases/latest/download/Deploy-DeskioStudent.ps1)** | Okul / Laboratuvar için tek tıkla sessiz kurulum scripti |
| **[Install-DeskioService.bat](https://github.com/Deskio-School/deskio-app/releases/latest/download/Install-DeskioService.bat)** | Windows SYSTEM bekçi servisi kurucu |

---

## ⚡ Temel Yetenekler

* **Canlı Ekran İzleme:** Düşük gecikmeyle tüm sınıf ekranlarını aynı anda izleyin ve büyütün.
* **Sınıf Güvenliği & Kilit:** Tek tıkla tüm ekranları kilitleyin, karartın veya sesleri susturun. Kilit sırasında Görev Yöneticisi ve kaçış tuşları engellenir.
* **NetSupport v15 Etkileşim Araçları:**
  * 📡 **Ekran Yayını:** Öğretmen ekranını tam ekran ve gecikmesiz tüm sınıfa yansıtın.
  * 🌐 **Birlikte Gezin (Co-Browse):** Sınıf tarayıcılarını eşzamanlı tek bir web adresine yönlendirin.
  * ⚡ **Hızlı Soru & Anket:** Çoktan seçmeli anlık quiz gönderin, sonuçları grafik olarak toplayın.
  * 🔔 **Buzzer (Zil Turu):** Söz hakkı yarışması başlatın; ilk basan öğrenciyi salise hassasiyetiyle belirleyin.
  * 🎯 **Şans Çarkı:** Sınıf listesinden adil ve rastgele öğrenci seçici.
  * 📁 **Dosya Fırlat:** Öğrencilerin masaüstüne anında dosya gönderin ve ödevleri toplayın.
  * ❤️ **Öğrenci İyi Hali:** Ders anlama ve dikkat seviyesini tek dokunuşla ölçün.
* **Akıllı Süreç Bekçisi:** Sınav ve ders modunda oyunları (`Roblox`, `Minecraft`, `Discord` vb.) arka planda otomatik kapatır.
* **Yerel Ağ Hibrit Güncelleme:** Güncellemeleri öğretmen 1 kez indirir; 30 öğrenciye internet kotası harcamadan yerel gigabit ağdan saniyeler içinde dağıtır.
* **Deep Freeze & MEB Koruması:** Dondurulmuş sistemlerde kalıcı çalışır; MEB güvenlik duvarlarına takılmaz.

---

## 🛠️ Hızlı Kurulum

### 1. Öğretmen Bilgisayarı
* `Deskio-Teacher-Console.exe` dosyasını çalıştırın. Kurulum gerektirmez, doğrudan açılır.

### 2. Öğrenci Bilgisayarları (Toplu Dağıtım)
Laboratuvardaki öğrenci bilgisayarlarına USB veya ağ paylaşımı üzerinden tek tıkla kurmak için PowerShell'i yönetici olarak açın:
```powershell
powershell -ExecutionPolicy Bypass -File .\Deploy-DeskioStudent.ps1 -LabId "LAB-1A"
```
Bu script güvenlik duvarı izinlerini otomatik tanımlar, Defender dışlamasını ekler ve arka plan servisini başlatır.

---

## 📋 Sistem Gereksinimleri
* **İşletim Sistemi:** Windows 10 / Windows 11 (64-bit)
* **Ağ:** Yerel Alan Ağı (LAN / Wi-Fi) — İnternet bağlantısı zorunlu değildir.

---

© 2026 Deskio School. Tüm hakları saklıdır.
