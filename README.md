# 🚚 DostKurye - Backend API

DostKurye, kurye, işletme sahibi ve admin panellerini kapsayan çok rollü bir teslimat platformudur.  
Bu repo, sistemin **Laravel tabanlı backend (API + Admin Blade)** tarafını içerir.

---

## 📌 Proje Özeti

DostKurye sistemi 3 ana rolden oluşur:

### 👤 Kurye
- Ana sayfada alınabilir siparişleri görür (konum, ödeme türü, ücret)  
- Aynı anda maksimum 4 sipariş alabilir  
- Siparişi teslim alır, yola çıkar ve teslim eder  
- Cüzdan ve tamamlanan siparişleri görüntüler  

### 🏪 İşletme Sahibi
- Sipariş oluşturur (konum, ödeme türü, fiyat)  
- Siparişlerini anlık takip eder  
- Atanan kuryeyi görür (ad, soyad, arama butonu)  
- Sipariş oluşturdukça bakiyeden düşer  

### 🛡️ Admin
- Tüm kullanıcıları yönetir  
- Kurye ve işletmelere bakiye/badge verir  
- Sistem ayarlarını kontrol eder  
- Tam yetkilidir  

---

## ⚙️ Teknoloji Altyapısı

- Backend: Laravel 11  
- Veritabanı: MySQL  
- API: RESTful  
- Admin Panel: Laravel Blade (ileride Next.js bağlanabilir)  
- Mobil: Flutter (ayrı repo)  

---

## 📂 Klasör Yapısı

app/ → İş mantığı, modeller, servisler  
routes/ → api.php, web.php  
database/ → migrations, seeders  
resources/ → admin blade, lang  
config/ → sistem ayarları  

---

## 🔐 Güvenlik

- Yetkisiz erişim engelleme  
- Spam ve kötüye kullanım koruması  
- API rate limit  
- Veri sızdırma önlemleri  

---

## 🚀 Kurulum

git clone https://github.com/Blntbv35/dostkurye-backend.git  
cd dostkurye-backend  
composer install  
cp .env.example .env  
php artisan key:generate  
php artisan migrate  
php artisan serve  

---

## 📅 Yol Haritası

- Auth sistemi  
- Rol sistemi (kurye / işletme / admin)  
- Sipariş altyapısı  
- Kurye eşleştirme  
- Cüzdan sistemi  
- Admin panel  

---

## 📄 Lisans

Bu proje DostKurye için özel geliştirilmiştir.