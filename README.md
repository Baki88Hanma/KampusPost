# KampusPost – Mobil Uygulama Projesi

Bu proje React Native kullanılarak geliştirilmiş basit bir giriş (Login), kayıt (Register) ve içerik listeleme (Home) uygulamasıdır.

---

## 📁 Proje Klasör Yapısı (Güncel Ekran Görüntüsü)

![Proje Yapısı](./readme_assets/project_structure.png)

---

## 📱 Uygulama Akışı Ekran Görüntüleri

### 🔹 Login → Register → Home Akışı

![Login](./readme_assets/login.png)
![Register](./readme_assets/register.png)
![Home](./readme_assets/home.png)

---

## 📝 Ekranlar

### 1️⃣ Login Screen
- Email input
- Password input
- “Giriş Yap” butonu
- “Kayıt Ol” butonu

### 2️⃣ Register Screen
- İsim
- Email
- Şifre
- Şifre tekrar
- Şifre eşleşmezse **Alert** verilir

### 3️⃣ Home Screen
- JSONPlaceholder API’den post verileri çekilir
- FlatList ile listelenir

---

## ▶️ Projeyi Çalıştırma Adımları

```sh
npm install
npx react-native start
npx react-native run-android
