# 📚 AKILLI KÜTÜPHANE SİSTEMİ  
🎓 *Nesneye Dayalı Programlama – Final Projesi*
---
Bu proje, **Java**, **Hibernate (ORM)** ve **SQLite** kullanılarak geliştirilmiş **konsol tabanlı bir Akıllı Kütüphane Otomasyon Sistemi**dir.  
Amaç; **nesneye dayalı programlama prensiplerini**, **veritabanı işlemlerini** ve **katmanlı mimariyi** gerçek bir senaryo üzerinde uygulamaktır.

---

## 🚀 Projenin Amacı

📌 Bu projede hedeflenenler:

- ✅ Nesneye Dayalı Programlama (OOP) mantığını **gerçek bir sistem** üzerinde uygulamak  
- ✅ **DAO (Data Access Object)** mimarisini öğrenmek  
- ✅ **Hibernate ORM** kullanarak veritabanı işlemlerini yönetmek  
- ✅ **SQLite** ile kalıcı veri saklamak  
- ✅ Kitap – Öğrenci – Ödünç alma süreçlerini yönetmek  

---

## 🧠 Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|---------|---------|
| ☕ Java | Ana programlama dili |
| 🧩 Hibernate | ORM (Object Relational Mapping) |
| 🗄 SQLite | Hafif ve taşınabilir veritabanı |
| 🧱 Maven | Proje ve bağımlılık yönetimi |
| 💻 Console | Kullanıcı arayüzü |

---

## 🏗 Proje Mimarisi (Katmanlı Yapı)

Proje **katmanlı mimari** kullanılarak geliştirilmiştir:


📦 AKILLI_KUTUPHANE  
┣ 📂 app    
┃ ┗ 📄 Main.java  
┣ 📂 dao  
┃ ┣ 📄 BookDao.java  
┃ ┣ 📄 StudentDao.java  
┃ ┗ 📄 LoanDao.java  
┣ 📂 entity  
┃ ┣ 📄 Book.java  
┃ ┣ 📄 Student.java  
┃ ┗ 📄 Loan.java  
┣ 📂 util  
┃ ┗ 📄 HibernateUtil.java  
┣ 📄 hibernate.cfg.xml  
┣ 📄 smartlibrary.db  
┗ 📄 pom.xml  


---

## 🧩 Katmanların Görevleri

### 📌 `entity` Paketi
🔹 Veritabanı tablolarını temsil eden **Java sınıfları** içerir.

- `Book` → Kitap bilgileri  
- `Student` → Öğrenci bilgileri  
- `Loan` → Ödünç alma kayıtları  

> 📎 Her entity sınıfı Hibernate anotasyonları ile işaretlenmiştir.

---

### 📌 `dao` Paketi
🔹 Veritabanı işlemlerinin yapıldığı katmandır.

- 📘 Kitap ekleme, silme, listeleme  
- 👨‍🎓 Öğrenci işlemleri  
- 🔄 Ödünç alma / iade işlemleri  

> DAO yapısı sayesinde **veritabanı bağımlılığı izole edilmiştir**.

---

### 📌 `util` Paketi
🔹 Hibernate bağlantısını yöneten yardımcı sınıflar içerir.

- `HibernateUtil`  
  - SessionFactory oluşturur  
  - Veritabanı bağlantısını yönetir  

---

### 📌 `app` Paketi
🔹 Programın **çalıştığı ana sınıf** burada bulunur.

- `Main.java`  
  - Menü sistemi  
  - Kullanıcıdan veri alma  
  - DAO sınıflarını çağırma  

---

## 🧪 Sistem Özellikleri

✨ Projede bulunan temel özellikler:

- 📖 Kitap ekleme / listeleme  
- 👨‍🎓 Öğrenci ekleme / listeleme  
- 🔄 Kitap ödünç alma  
- 📅 İade süreci takibi  
- 🗃 Veritabanı üzerinden kalıcı kayıt  

---

## ▶️ Projeyi Çalıştırma

### 1️⃣ Gerekli Araçlar
- Java JDK 8+
- Maven
- IntelliJ IDEA / Eclipse (önerilir)

---

2️⃣ Projeyi Klonla
```bash
git clone https://github.com/TimaYT/Nesneye-Dayal-Programlama-Final-Projesi.git
```
---
3️⃣ Maven Bağımlılıklarını Yükle
mvn clean install
```
---
4️⃣ Uygulamayı Çalıştır
Main.java dosyasını çalıştır
📌 Program konsol üzerinden menülü şekilde çalışacaktır.
```
---

🗄 Veritabanı Bilgisi
---

📂 Veritabanı: smartlibrary.db

🛠 SQLite kullanılmıştır

🔄 Hibernate otomatik tablo yönetimi yapar

🎯 Öğrenilen / Pekiştirilen Konular
---
✔️ Nesneye Dayalı Programlama  
✔️ DAO Design Pattern  
✔️ Hibernate ORM  
✔️ Veritabanı – Java entegrasyonu  
✔️ Katmanlı mimari  
✔️ Clean Code prensipleri  

🔮 Geliştirilebilir Özellikler
---
🚀 Gelecekte eklenebilecek geliştirmeler:

🖥 GUI (JavaFX / Swing)

🔐 Kullanıcı yetkilendirme sistemi

📊 Raporlama & istatistik ekranları

🌐 Web tabanlı sürüm

📅 Gecikme cezası hesaplama

👤 Geliştirici
---
👨‍💻 Yasin Balkan
🎓 Piri Reis Üniversitesi
📚 Bilgisayar Programcılığı
📌 Nesneye Dayalı Programlama – Final Projesi
