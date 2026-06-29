# FIX SAMP (ASI Plugin) - v1.0.0

SA-MP 0.3.DL-R1 ve 0.3.7 sürümleri için özel olarak geliştirilmiş, performans, kararlılık ve görsellik odaklı nihai eklenti (ASI Plugin) sürümüdür.

## 🚀 Eklenti Özellikleri ve Düzeltmeler

*   **Sınırsız Pencere Modu (Borderless Windowed Mode):**
    *   Yüksek FPS uyumlu sınırsız ekran modu.
    *   Çift ekranlar için tam uyumluluk ve kararlı Alt-Tab geçişleri.
    *   Ekran kartı ve D3D9 ayarlarını koruyarak çözünürlük, geniş ekran ve Kenar Yumuşatma (Anti-Aliasing) çökmelerini engeller.
*   **Özel Harita Drop & Kasma Çözümü (Streaming Memory Limit):**
    *   Sistem RAM kapasitesini otomatik tarayarak oyunun akış belleği limitini güvenli şekilde (512MB - 1.5GB) yükseltir.
    *   Sunucuya özel haritalar yüklenirken oluşan anlık drop, takılma ve "invisible textures" sorunlarını tamamen çözer.
*   **Discord Rich Presence (RPC):**
    *   Profilinizde gerçek zamanlı IP, Port, Kullanıcı Adı ve Sunucu İsmini gösterir.
    *   Sunucudaki **gerçek** aktif oyuncu sayısını ve maksimum oyuncu limitini (UDP Query ile) doğru şekilde yansıtır.
*   **Otomatik Güncelleme (Auto-Updater):**
    *   Siz oyundayken yeni bir güncelleme çıktığında eklentiyi arka planda asenkron olarak otomatik günceller.
*   **Hızlı Kapatma (Fast Quit):**
    *   `/q` veya `/quit` yazarak oyundan çıkarken yaşanan donma, askıda kalma ve siyah ekran gecikmelerini sıfıra indirerek oyunu anında kapatır.
*   **Yüksek FPS Şasi Sallanma Düzeltmesi (Chassis Shake Fix):**
    *   Yüksek FPS (100+) limitlerinde araçların şasilerinde oluşan titreme ve sallanma bug'ını düzeltir.
*   **Arayüz Gizleyici (HUD & TextDraw Hider):**
    *   F10 tuşuna basılı tutulduğunda veya F7 ile sohbet gizlendiğinde sunucu textdraw'larını titremeden temiz bir şekilde gizler.
*   **Bölgesel Ayar Çökmeleri Düzeltmesi (Locale Invariant Fix):**
    *   İşletim sistemindeki bölgesel ayarlar nedeniyle (ondalık sayı virgül/nokta uyuşmazlığı) oluşan dosya okuma çökmelerini engeller.

## 📦 Kurulum

1. Deponun ana dizininde bulunan **`FIX SAMP.asi`** dosyasını indirin.
2. İndirdiğiniz dosyayı GTA San Andreas oyununuzun ana dizinine atın. (Eğer ASI Loader yüklü değilse, oyuna girmeden önce bir ASI Loader kurun).
