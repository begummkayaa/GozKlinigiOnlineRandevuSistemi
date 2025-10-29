# 👁️ Göz Kliniği Online Randevu Sistemi

Göz kliniği için geliştirilmiş web tabanlı online randevu sistemi. Hastaların ve doktorların hesap oluşturmasına, profil yönetimine ve kolayca randevu almasına olanak tanır.

---

## 🚀 Projenin Özellikleri

Bu proje, hasta ve doktor etkileşimini dijitalleştiren kapsamlı bir randevu yönetimi çözümü sunar.

* **🔐 Güvenli Kimlik Doğrulama:**
    * Kullanıcıların (hasta ve doktor) web uygulaması üzerinden güvenli bir şekilde hesap oluşturup giriş yapabilmesi sağlandı.
* **🔑 Şifre Yönetimi:**
    * Şifresini unutan kullanıcılar, sisteme kayıtlı e-posta adresi aracılığıyla şifrelerini sıfırlayabilmektedir.
* **👤 Profil Yönetimi:**
    * Kullanıcılar, kendi profillerini görüntüleyip temel bilgilerini güncelleyebilmektedir.
* **📅 Online Randevu Modülü:**
    * Kullanıcıların (hasta), uzmanlara ait uygun gün ve saatleri seçerek kolayca randevu alması sağlanmıştır.
* **ℹ️ Klinik Bilgi Sayfası:**
    * Ana sayfada klinik hakkında bilgi, iletişim bilgileri ve uzman doktor listesi yer almaktadır.

## 🛠️ Kullanılan Teknolojiler

### ⚙️ Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**

**Ek Araçlar:** CORS, Nodemailer, Crypto, Node-fetch

---

### 🎨 Frontend
- **React**
- **Axios**
- **Framer Motion**
- **FontAwesome**, **Lucide React**
- **Date-fns**

---

### 🧪 Test ve Geliştirme Araçları
- **Jest**
- **React Testing Library**
- **Webpack**, **Babel**
- **ESLint**
- **npm**

---

### 📦 Mimari ve Yapı
- **MVC Deseni**
- **Bileşen Tabanlı Mimari (React)**
- **RESTful API**

---

### 🔒 Güvenlik ve Servisler
- **Gmail SMTP** (E-posta servisi)
- **E-posta doğrulama & şifre sıfırlama**
- **CORS koruması**
- **Sunucu taraflı girdi doğrulama**

---

### 💻 Geliştirme Ortamı
- **Create React App**
- **Yerel Geliştirme Sunucusu:** Express (port 3000)
- **React Geliştirme Sunucusu:** React (port 3001)

### 📁 Proje Yapısı

Proje, bir monorepo benzeri yapıda randevu-frontend ve randevu-backend olmak üzere iki ana klasöre ayrılmıştır.

```bash
📁 GozKlinigiOnlineRandevuSistemi/
│
├── 💻 randevu-backend/              # 🧠 Sunucu tarafı (Node.js & Express)
│   ├── index.js                     # Ana sunucu dosyası
│   ├── models/                      # MongoDB modelleri
│   ├── package.json
│   └── package-lock.json
│
├── 🌐 randevu-frontend/             # 🎨 İstemci tarafı (React)
│   ├── public/                      # Statik dosyalar (görseller, videolar, favicon vb.)
│   ├── src/                         # React kaynak dosyaları (componentler, stiller, sayfalar)
│   ├── package.json
│   └── package-lock.json
│
└── 🧾 README.md                     # 📖 Genel proje açıklaması
```

## 🖥️ Kurulum ve Çalıştırma

1.  📥 Bu depoyu klonlayın: `git clone https://github.com/kullaniciadiniz/GozKlinigiOnlineRandevuSistemi.git`
2.  🔧 Veritabanı bağlantı ayarlarını (`appsettings.json`) yapılandırın.
3.  ▶️ Package Manager Console üzerinden `Update-Database` komutunu çalıştırın.
4.  🎉 Projeyi başlatın.
