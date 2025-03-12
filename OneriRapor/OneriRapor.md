
# Öneri Raporu
## 1. Proje Konusu
Bu proje, Arduino tabanlı bir otonom robotun, HC-SR04 ultrasonik sensör kullanarak önündeki engelleri algılayıp kaçınmasını sağlamak amacıyla geliştirilmiştir. Robot, çevresindeki nesneleri tespit eder, uygun bir yön belirler ve çarpışmaları önleyerek ilerler.

## 2. Proje Hedefleri

Projenin temel hedefleri şunlardır:

- Engelleri tespit eden ve yön değiştiren otonom bir robot geliştirmek.
- Ultrasonik mesafe sensörü kullanarak nesneleri algılama algoritması oluşturmak.
- Arduino ve motor sürücü devresi ile DC motorları kontrol etmek.
- Robotun otonom hareket kabiliyetini artırarak belirlenen alan içinde engellerden kaçmasını sağlamak.
- Açık kaynak bir proje olarak GitHub’da paylaşmak.

## Başarı Kriterleri:

- Robotun engelleri %95 doğrulukla algılaması.
- Engel algıladığında en az %90 oranında doğru manevra yapması.
- Kesintisiz en az 20 dakika çalışabilmesi.

## 3. Tahmini Zaman Çizelgesi

| *Görev*                                        | *Tahmini Süre*  |
|--------------------------------------------------|-------------------|
| *Proje Planlaması ve Araştırma*                | 1 hafta           |
| *Arduino ve Sensörlerin Kurulumu*              | 1 hafta           |
| *Yazılım Geliştirme ve Engel Algılama Algoritması* | 2 hafta           |
| *Donanım Montajı ve Testler*                   | 2 hafta           |
| *Yazılım ve Donanım Entegrasyonu*              | 2 hafta           |
| *Test ve Hata Ayıklama*                        | 1 hafta           |
| *Son Testler ve Optimizasyon*                  | 1 hafta           |
| *Proje Sonuçları ve Rapor Hazırlama*           | 1 hafta           |
| *Toplam Süre*                                  | 9 hafta           |

## 4. Kaynak Planlaması
## Gerekli Malzemeler ve Maliyetler

| Malzeme                        | Birim Fiyat (₺) | Adet  | 
|--------------------------------|---------------|------|
| Arduino Uno                    | 500           | 1    | 
| HC-SR04 Ultrasonik Sensör      | 100           | 1    | 
| L298N Motor Sürücü             | 150           | 1    | 
| DC Motorlar ve Tekerlek Seti   | 400           | 2    | 
| 6'lı AA Pil Yuvası ve Piller   | 200           | 1    |
| Şasi (Robot Gövdesi)           | 350           | 1    | 
| Jumper Kabloları               | 50            | 1 Set |
| **Toplam Tahmini Maliyet:**    | **1.750₺**   |      | 

## Kullanılacak Yazılımlar:

- Arduino IDE (Kod yazımı ve yükleme)
- Proteus veya Tinkercad (Simülasyon testleri)
- Fritzing veya EasyEDA (Devre tasarımı)


## Risk Analizi

| Potansiyel Risk                     | Çözüm Önerisi |
|--------------------------------------|---------------|
| Sensörlerin hatalı ölçüm yapması     | Sensörlerin hizalanmasını kontrol etmek, kod optimizasyonu yapmak. |
| Motorların senkronize çalışmaması    | PWM sinyalleriyle hız kontrolü sağlamak. |
| Pil ömrünün kısa olması              | Li-Po pil kullanmak veya enerji verimliliğini artırmak. |
| Robotun manevra hataları yapması     | Sensör menzilini artırmak ve daha iyi algoritmalar geliştirmek. |

## 6. Ticari Potansiyel

Otonom engelden kaçan robotlar, ticari olarak birçok alanda kullanılabilir:

- 📌 **Eğitim** → Arduino ve robotik eğitimi için temel proje olarak kullanılabilir.  
- 📌 **Endüstriyel Uygulamalar** → Otonom lojistik robotları, engelleri algılayarak depolarda kullanılabilir.  
- 📌 **Ev Otomasyonu** → Akıllı süpürgeler ve otonom temizlik robotları gibi ürünlerde temel teknoloji olarak uygulanabilir.  
- 📌 **Askeri ve Araştırma Alanları** → Keşif ve gözlem robotlarında engellerden kaçınma algoritması kullanılabilir.

 ## 7. Proje Ekibi ve Görev Dağılımı   

### Busenur Yıldız 
- Sensör ve motorların Arduino'ya bağlantısını yapma
- Arduino kodlarını yazma 
- Devre şemasını oluşturma ve test etme  
- Enerji yönetimi ve pil bağlantılarını sağlama

### Aybüke Eraydın  
- Arduino kodlarını yazma  
- Motor sürücü ve kontrol mekanizmalarını kodlama 

### Sevgi Nur Öksüz 
- Sensörlerden gelen verileri işleme
- Arduino kodlarını yazma 
- Kabloların düzenli yerleştirilmesini sağlama  

### Onur Kerem 
- Robotun hareketlerini test etme
- Arduino kodlarını yazma 
- Engelleri algılama hassasiyetini ayarlama  
- Hata tespiti ve optimizasyon önerileri geliştirme
