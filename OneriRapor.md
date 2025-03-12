# 📌 Öneri Raporu
## 1. Proje Konusu
Bu proje, Arduino tabanlı bir otonom robotun, HC-SR04 ultrasonik sensör kullanarak önündeki engelleri algılayıp kaçınmasını sağlamak amacıyla geliştirilmiştir. Robot, çevresindeki nesneleri tespit eder, uygun bir yön belirler ve çarpışmaları önleyerek ilerler.

## 2. Proje Hedefleri
Projenin temel hedefleri şunlardır:
 Engelleri tespit eden ve yön değiştiren otonom bir robot geliştirmek.
 Ultrasonik mesafe sensörü kullanarak nesneleri algılama algoritması oluşturmak.
 Arduino ve motor sürücü devresi ile DC motorları kontrol etmek.
 Robotun otonom hareket kabiliyetini artırarak belirlenen alan içinde engellerden kaçmasını sağlamak.
 Açık kaynak bir proje olarak GitHub’da paylaşmak.

## Başarı Kriterleri:

Robotun engelleri %95 doğrulukla algılaması.
Engel algıladığında en az %90 oranında doğru manevra yapması.
Kesintisiz en az 20 dakika çalışabilmesi.

## 3. Tahmini Zaman Çizelgesi
Görev	Tahmini Süre
Malzeme temini ve hazırlık	2 gün
Devre bağlantılarının yapılması	1 gün
Arduino kodlarının yazılması	2 gün
Sensör testleri ve hata ayıklama	2 gün
Robotun gövde montajı	1 gün
Yazılım optimizasyonu	2 gün
Nihai testler ve raporlama	2 gün
✅ Toplam Süre: 12 Gün

## 4. Kaynak Planlaması
Ekip:
Proje Yöneticisi: [Adınız]
Elektronik Uzmanı: [Ekip Üyesi 1]
Yazılım Geliştirici: [Ekip Üyesi 2]
Gerekli Malzemeler ve Maliyetler:
Malzeme	Birim Fiyat (₺)	Adet	Toplam (₺)
Arduino Uno	500	1	500
HC-SR04 Ultrasonik Sensör	100	1	100
L298N Motor Sürücü	150	1	150
DC Motorlar ve Tekerlek Seti	400	2	800
6'lı AA Pil Yuvası ve Piller	200	1	200
Şasi (Robot Gövdesi)	350	1	350
Jumper Kabloları	50	1 Set	50
Toplam Tahmini Maliyet:	2.150₺		2.150₺

## Kullanılacak Yazılımlar:
 Arduino IDE (Kod yazımı ve yükleme)
 Proteus veya Tinkercad (Simülasyon testleri)
 Fritzing veya EasyEDA (Devre tasarımı)

## 5. Risk Analizi
Potansiyel Risk	Çözüm Önerisi
Sensörlerin hatalı ölçüm yapması	Sensörlerin hizalanmasını kontrol etmek, kod optimizasyonu yapmak.
Motorların senkronize çalışmaması	PWM sinyalleriyle hız kontrolü sağlamak.
Pil ömrünün kısa olması	Li-Po pil kullanmak veya enerji verimliliğini artırmak.
Robotun manevra hataları yapması	Sensör menzilini artırmak ve daha iyi algoritmalar geliştirmek.
## 6. Ticari Potansiyel
Otonom engelden kaçan robotlar, ticari olarak birçok alanda kullanılabilir:
📌 Eğitim → Arduino ve robotik eğitimi için temel proje olarak kullanılabilir.
📌 Endüstriyel Uygulamalar → Otonom lojistik robotları, engelleri algılayarak depolarda kullanılabilir.
📌 Ev Otomasyonu → Akıllı süpürgeler ve otonom temizlik robotları gibi ürünlerde temel teknoloji olarak uygulanabilir.
📌 Askeri ve Araştırma Alanları → Keşif ve gözlem robotlarında engellerden kaçınma algoritması kullanılabilir.
