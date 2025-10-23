# 🎬 Firebase Video Upload & Player

![Header Image](https://img.icons8.com/color/96/video.png)

Bu proje, kullanıcıların videolarını **PHP** ile **Firebase Realtime Database** üzerine yüklemesini sağlar ve tarayıcı üzerinden parçalı olarak oynatılabilen bir video player sunar.  

Videolar **1 MB veya istenilen boyutta parçalara** bölünür, Base64 olarak Firebase’e kaydedilir ve tarayıcıda Blob üzerinden oynatılır. Sunucuda **hiçbir video kalmaz**, tüm yükleme doğrudan Firebase’e yapılır.

---

## 🚀 Özellikler

- 🔹 **Hatalı yükleme önleme:** Videolar parçalanarak yüklenir, büyük dosyalar için ideal  
- 🔹 **Firebase Realtime Database:** Basit, güvenli ve sunucusuz veri yönetimi  
- 🔹 **HTML5 Video Player:** Parçalı videolar otomatik birleştirilir ve oynatılır  
- 🔹 **URL-Safe Video Adları:** Özel karakterler veya boşluklar otomatik düzeltilir  
- 🔹 **Sunucu yükü sıfır:** Videolar hiçbir zaman sunucuda depolanmaz  
- 🔹 **Responsive:** Masaüstü ve mobil tarayıcılar ile uyumlu  

---

## 📂 Firebase Yapısı

Videolar Firebase’e şu şekilde kaydedilir:

