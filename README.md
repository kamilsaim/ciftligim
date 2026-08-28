<div align="center">
  <img src="logo.png" alt="Çiftliğim logo" width="140" />

  # Çiftliğim

  Hayvancılık işletmenizi tek ekrandan yönetin: hayvanlar, ahırlar ve finans kayıtları.

  [![Canlı Demo](https://img.shields.io/badge/canlı%20demo-kamilsaim.github.io%2Fciftligim-0F6E56?style=flat-square)](https://kamilsaim.github.io/ciftligim/)
  ![Sürüm](https://img.shields.io/badge/sürüm-v1.2.0-1D9E75?style=flat-square)
  ![PWA](https://img.shields.io/badge/PWA-destekli-0a2e1f?style=flat-square)
  ![Firebase](https://img.shields.io/badge/Firebase-Auth%20%2B%20Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
</div>

---

## Hakkında

**Çiftliğim**, küçük ve orta ölçekli hayvancılık işletmeleri için geliştirilmiş, tek sayfalık (single-page) bir web uygulamasıdır. Firebase üzerinde çalışır; doğrudan tarayıcıdan, bir Progressive Web App (PWA) olarak ana ekrana eklenerek veya bir WebView sarmalayıcı (native iOS/Android uygulaması) üzerinden kullanılabilir.

👉 **[Canlı demoyu deneyin](https://kamilsaim.github.io/ciftligim/)**

## Özellikler

| | |
|---|---|
| 🐄 **Hayvan Yönetimi** | Tekli veya **toplu hayvan ekleme**, küpe/isim takibi, ırk, ağırlık, gebelik durumu |
| 🏠 **Ahır Yönetimi** | Ahır ekleme/düzenleme, kapasite takibi ve hayvanların ahırlara dağılımı |
| 💰 **Finans Takibi** | Gelir/gider kayıtları, toplu hayvan satışı, ödenen/kalan tutar takibi |
| 🔔 **Akıllı Hatırlatmalar** | Yaklaşan doğumlar, dolan ahırlar, eksik bilgiler için otomatik uyarılar |
| 🔐 **Google ile Giriş** | Firebase Authentication üzerinden güvenli oturum açma |
| 📱 **Mobil Uyumlu** | PWA desteği, ana ekrana ekleme ve responsive arayüz |
| ⬇️ **Yedekleme** | Tüm verileri JSON olarak indirme ve geri yükleme |

## Kullanılan Teknolojiler

- Vanilla JavaScript — framework'süz, bağımlılıksız, tek dosya
- Firebase (Authentication + Firestore)
- Progressive Web App (PWA) — inline service worker ile çevrimdışı destek ve otomatik güncelleme

## Çalıştırma

`index.html` dosyasını herhangi bir statik dosya sunucusuyla (veya doğrudan tarayıcıda) açmanız yeterlidir — derleme/kurulum adımı gerekmez.

```bash
# örnek: basit bir statik sunucu ile
npx serve .
```

---

<div align="center">
  <sub>Çiftliğim · Hayra vesile olsun 🤲</sub>
</div>
