Noxia Logs Systems - Tanıtım ve Özellikler
🤔 Noxia Logs Systems Nedir?
Noxia Logs Systems, Roblox geliştiricileri için tasarlanmış profesyonel bir loglama ve izleme sistemidir. Oyundaki tüm önemli olayları, hataları ve performans metriklerini Discord üzerinden gerçek zamanlı olarak takip etmenizi sağlar.

🎯 Temel Amacı:
Oyununuzdaki her şeyi uzaktan monitor etmek - evden çıkmadan, telefonunuzdan bile oyununuzun durumunu takip edebilirsiniz!

✨ Başlıca Özellikler
1. 📱 Gerçek Zamanlı Discord Logları
💬 Sohbet mesajları

👥 Oyuncu giriş/çıkışları

⚠️ Sistem hataları

📊 Performans metrikleri

💾 Data işlemleri

2. 🚀 Kurulumu Çok Kolay
lua
-- Sadece 2 dosya!
ServerScriptService/
└── NoxiaLogs/
    ├── Config (Webhook URL'leri)
    └── MainScript (Otomatik çalışır)
3. ⚡ Sıfır Kod Gerektiren Otomatik Loglar
Hiç kod yazmadan çalışan sistem

Config'te Enabled = true yapman YETERLİ!

Otomatik giriş/çıkış takibi

Otomatik sohbet loglama

Otomatik hata yakalama

4. 🛠️ Geliştirici Dostu Manuel Kontrol
lua
-- İstediğiniz yerden log gönderin!
_G.NoxiaLogs_LogError("Market Hatası", "Stok yok", player)
_G.NoxiaLogs_LogData("Para Transferi", player, "1000 → 1500")
🛠️ Kurulum Nasıl Yapılır?
1. 📥 Dosyaları Studio'ya Aktarma
Kodları kopyala/yapıştır yaparak Studio'ya aktarın

2. 📁 Klasör Yapısını Oluşturma
text
ServerScriptService/
└── NoxiaLogs/
    ├── MainScript (Normal Script)
    └── Config (ModuleScript)
3. ⚙️ Script'leri Yapıştırma
MainScript içindeki kodu Normal Script'e yapıştır

Config içindeki kodu ModuleScript'e yapıştır

4. 🔧 Config Ayarlarını Yapılandırma
Config dosyasındaki webhook URL'lerini kendi Discord webhook'larınızla değiştirin

Diğer ayarları ihtiyacınıza göre düzenleyin

5. ✅ Sistemi Test Etme
Oyunu test modunda çalıştırın

Discord kanalınızda logların düştüğünü kontrol edin

🎯 Log Türleri ve İşlevleri
💬 Sohbet Logları
Tüm oyuncu sohbetlerini kaydeder

Küfür filtresi özelliği

Özel mesaj takibi

👥 Giriş-Çıkış Logları
Oyuncu giriş/çıkışlarını loglar

Yeni hesapları tespit eder (14 günden yeni)

Profil linkleri ile hızlı erişim

⚠️ Hata & Bug Logları
Script hatalarını yakalar

HTTP ve DataStore hatalarını takip eder

Rate limiting ile spam önleme

💾 Data Logları
Oyuncu data işlemlerini kaydeder

Hile tespiti (anormal para artışları)

Data kaybını önleme

📊 Performans Logları
Sunucu performansını monitor eder

FPS, Memory, CPU kullanımı takibi

Acil durum uyarıları

⚙️ Config Ayarları
Tüm ayarlar Config dosyasından yönetilir:

Webhook URL'leri: Discord kanallarınıza özel webhook'lar

Performans Ayarları: Kontrol aralıkları ve kritik eşikler

Filtreleme: Loglanacak/Loglanmayacak içerikler

Renk Ayarları: Discord embed renkleri

🆘 Destek ve Topluluk
Daha detaylı kurulum veya sorunlarınız için Discord sunucumuza katılın:

🔗 Discord Sunucusu: https://discord.gg/3ZPeMpEePP

📝 Lisans ve Katkı
Bu proje açık kaynaklıdır. Katkıda bulunmak veya geliştirmek için GitHub reposunu ziyaret edin.

text
📧 İletişim: Discord sunucumuz üzerinden
🐛 Hata Bildirimi: GitHub issues veya Discord
💡 Öneriler: Her zaman açığız!
Noxia Logs Systems - Oyununuzun gözü, kulağı ve beyni olur! 🛡️
