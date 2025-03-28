# To-Do Uygulaması

Bu proje, kullanıcıların görevlerini (todo) takip etmelerini sağlayan basit bir uygulamadır. Hem frontend (React) hem de backend (Node.js ve Express) içerir. Uygulama, görevleri ekleme, düzenleme, silme ve listeleme gibi temel işlevleri sunmaktadır.

## Teknolojiler

- **Frontend:** React, Bootsrap
- **Backend:** Node.js, Express, Sequelize, Dotenv
- **Veritabanı:** MySQL
- **API İletişimi:** Axios (Frontend - Backend)

## Özellikler

- Görevleri listeleme
- Yeni görev ekleme
- Görevleri düzenleme
- Görevleri silme
- Görevlerin tamamlanma durumunu güncelleme

## Kurulum

### Projeyi Çekme

GitHub reposunu bilgisayarınıza klonlayın:

```bash
git clone https://github.com/kullaniciadi/proje-adi.git
```

Backend ve Frontend farklı terminallerde çalıştırılmalıdır.

**Backend Kurulumu**
```bash
cd server
npm install
npm start
```

**Frontend Kurulumu**
```bash
cd client
npm install
npm start
```

**Database**
.env dosyasının içindekikleri kendi veritabanınıza göre düzenlemeniz gerekmektedir.
