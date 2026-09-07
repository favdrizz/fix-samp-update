# FIX SAMP (ASI Plugin) - v1.0.9

SA-MP 0.3.DL-R1, 0.3.7 (R1-R5) ve open.mp sürümleri için geliştirilmiş nihai performans, uyumluluk ve kararlılık eklentisidir.

## 🚀 Eklenti Özellikleri ve Düzeltmeler

*   **Modern CPU & GPU Donanım Hızlandırma:**
    *   *Harici GPU Zorlama:* Yeni nesil çift ekran kartlı (Optimus / PowerXpress) laptop ve sistemlerde oyunun Intel dahili kart yerine güçlü harici ekran kartı (NVIDIA RTX / AMD Radeon) ile çalışmasını zorunlu kılan sürücü bayrakları eklendi.
    *   *D3D9 Donanım Hızlandırma (PureDevice):* Geometri ve köşe (vertex) hesaplamaları işlemciden alınıp ekran kartının shader çekirdeklerine devredildi.
    *   *Sıfır Gecikme & VSync Kilidi Kaldırma:* Direct3D `PresentationInterval` immediate moduna alınarak VSync ve kare gecikmeleri sıfırlandı; GPU'nun tam kapasite kare üretmesi sağlandı.
    *   *Çok Çekirdek & MMCSS Zamanlayıcı:* İşlemci önceliği ve Windows MMCSS ("Games") servisi etkinleştirildi.
*   **Kusursuz Araç Şasi ve Kasa Sallanma Fixi (Chassis Shake Fix):**
    *   Yüksek FPS'de araçların arka kısmının ("kıçının"), kasasının ve parçalarının titremesine/sallanmasına neden olan `CDoor::ProcessSwing` açısal hız, kuvvet ve sönümleme hesaplamaları delta-time ile eşitlendi; sallantı ve titreme tamamen yok edildi.
*   **Tam Sınırsız FPS Modu (Unlimited FPS):** GTA SA motorundaki 14 ms bekleme baytı, RenderWare kare sınırlayıcı ve SA-MP dahili Sleep/limiter kısıtlamaları tamamen kaldırıldı; `/fpslimit` aralık sınırı açıldı.
*   **Kusursuz Yüksek FPS Fiziği:** 
    *   *Suda Doğal Yüzme:* Suda hiçbir FPS kısıtlaması koyulmadan yüzme, dalma ve çıkma hızları delta-time ile eşitlendi; karakter batmaz ve tam hızda yüzer.
    *   *Araç Manevra Koruma:* Yüksek hızda sağ-sol manevralarında direksiyon dönme hızı (`WheelTurnSpeed`) ve viraj ataleti korunur, savrulma ve ani durma yaşanmaz.
*   **Çoklu Sürüm Girişi (Multi-Join):** SA-MP 0.3.DL istemcisiyle hiçbir dosya değiştirmeden doğrudan 0.3.7 sunucularına sorunsuz bağlanabilme (`/version`).
*   Sınırsız Pencere Modu (Borderless Windowed Mode)
*   Özel Harita Kasma Çözümü (Streaming Memory Limit)
*   Discord Rich Presence (RPC) - *Kullanıcı adı gizlidir*
*   Otomatik Güncelleme (Auto-Updater)
*   Hızlı Kapatma (Fast Quit)
*   Arayüz ve Textdraw Gizleyici (HUD Hider)
*   Bölgesel Ayar Çökmeleri Düzeltmesi (Locale Invariant Fix)
*   BASS.dll Ses Akışı Çift Çalma/Çökme Düzeltmesi (BASS Stream Fix)

## 📦 Kurulum

1. Deponun ana dizininde bulunan **`FIX SAMP.asi`** dosyasını indirin.
2. İndirdiğiniz dosyayı GTA San Andreas oyununuzun ana dizinine atın.

## 📅 Son Güncelleme
*   **Tarih:** 7 Eylül 2026
*   **Sürüm:** v1.0.9
