# 🎥 Professional Kamera İzleme Sistemi

Uzaktan güvenli kamera izleme, cihazlar arası peer-to-peer bağlantı ve real-time video akışı sağlayan modern web uygulaması.

## ✨ Özellikler

### 🔐 Güvenlik
- SHA256 şifre hashleme
- 6 haneli erişim kodu
- Kullanıcı izin sistemi
- Oturum yönetimi

### 📹 Kamera Kontrolleri
- Gerçek zamanlı video akışı (1280x720 HD)
- Ses kaydı desteği
- Otomatik kayıt başlatma
- Video indirme özellikleri

### 🌐 Uzak İzleme
- PeerJS tabanlı P2P bağlantı
- Cihazlar arası doğrudan bağlantı
- Peer ID tabanlı bağlama sistemi
- Birden fazla bağlantı desteği

### 🎛️ Kontrol Paneli
- Modern gradyan arayüzü
- Responsive tasarım (Mobil + Desktop)
- Gerçek zamanlı durum göstergeleri
- Kolay kullanılabilir butonlar

### 💾 Kayıt Yönetimi
- WebM formatında video kayıtları
- Tarayıcı indirme desteği
- Otomatik zaman damgalı dosyalar
- Kayıt gönderme özellikleri

## 🚀 Başlangıç

### Demo Erişimi
```
Kullanıcı: demo
Şifre: demo123
Kod: 123456
```

### Admin Erişimi
```
Kullanıcı: admin
Şifre: admin2024
Kod: 999999
```

## 📋 Kullanım Adımları

1. **Giriş Yap** - Demo verilerinizi girerek sistem giriş ekranını geç
2. **Kamera Başlat** - "KAMERA BAŞLAT" butonuna tıkla ve izin ver
3. **Peer ID Kopyala** - Sağ panelden Peer ID'nı kopyala
4. **Uzak Cihaza Bağlan** - Başka bir cihazın Peer ID'sini gir ve "UZAK CİHAZA BAĞLAN" tıkla
5. **İzle ve Kaydet** - Video akışını izle ve otomatik kayıtları indir

## 🔧 Teknik Detaylar

### Kullanılan Kütüphaneler
- **PeerJS** - P2P video bağlantısı
- **CryptoJS** - Şifre hashleme
- **WebRTC** - Gerçek zamanlı medya

### Tarayıcı Desteği
- Chrome/Chromium 60+
- Firefox 60+
- Safari 11+
- Edge 79+

### Kamera İzinleri
- Video erişim
- Ses erişim
- Otomatik kayıt

## 📱 Responsive Tasarım

- **Desktop (1200px+)** - 2 sütunlu görünüm
- **Tablet (768px - 1199px)** - Duyarlı panel
- **Mobile (<768px)** - Tek sütun tam genişlik

## 🔗 PeerJS Sunucu

Şu an kullanılan sunucu:
```
peerjs-server.herokuapp.com
Port: 443 (Secure)
```

> **Not:** Production ortamında kendi PeerJS sunucunuzu kurmalısınız.

## 🛡️ Güvenlik Önerileri

1. Production'da backend kimlik doğrulama kullanın
2. HTTPS ile şifreli bağlantı kurun
3. Kendi PeerJS sunucusunu açın
4. Firewall kuralları yapılandırın
5. Düzenli şifre değişimi teşvik edin
6. Erişim loglarını tutun

## 📝 Yapılacak Geliştirmeler

- [ ] Backend API entegrasyonu
- [ ] Veritabanı kimlik doğrulama
- [ ] End-to-end şifreleme
- [ ] Kayıt gönderme protokolü
- [ ] WebRTC Data Channel
- [ ] Mobil uygulama
- [ ] Daha fazla çözünürlük seçeneği
- [ ] Screen sharing

## 🐛 Sorun Giderme

### Kamera Çalışmıyor?
- HTTPS kullanıyor musun?
- Tarayıcı izini verdi mi?
- Kamerası var mı?

### Bağlantı Başarısız?
- Peer ID doğru mu?
- Her iki cihazda kamera açık mı?
- İnternet bağlantısı var mı?

### Ses Gelmiyorsa?
- Mikrofon açık mı?
- Ses kapatılı mı?
- Kütüphaneler yüklendi mi?

## 📞 İletişim

Sorular ve öneriler için lütfen issue açın.

---

**Geliştirici:** yusapeker7-ux  
**Lisans:** MIT  
**Son Güncelleme:** 2026-06-06
