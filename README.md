Global Education Analysis (2018–2020)

Bu proje, farklı ülkelerin 2018–2020 yılları arasındaki okuryazarlık oranı, eğitim süresi, eğitim harcamaları ve nüfus verileri üzerinden kapsamlı bir Exploratory Data Analysis (EDA) çalışması sunar.
Amaç; ülkelerin eğitim göstergeleri arasındaki ilişkileri incelemek, trendleri ortaya çıkarmak ve veri içindeki örüntüleri görselleştirerek yorumlamaktır.

📂 İçerik

Bu projede aşağıdaki analiz adımları gerçekleştirilmiştir:

✔ Veri Yükleme ve İnceleme

Veri yapısı incelendi (info(), head(), shape())

Eksik değer kontrolü yapıldı

Sütun veri tipleri gözden geçirildi

✔ Tanımlayıcı İstatistikler

describe() kullanılarak temel istatistik özetleri çıkarıldı:

Ortalama

Medyan

Minimum–Maksimum

Standart sapma

Çeyrek değerleri

✔ Ülke Bazlı İnceleme

Benzersiz ülke sayısı

Ülkelere göre temel istatistik karşılaştırmaları

✔ Veri Görselleştirme

Projedeki grafikler:

• Zaman Serisi (Line Plot)

Ülkelerin yıllara göre:

Okuryazarlık oranı

Ortalama eğitim yılı

Eğitim harcaması
trend grafikleri oluşturuldu.

• Dağılım Grafiği (Scatter Plot)

Nüfus ↔ Eğitim Harcaması ilişkisi incelendi

Ülke bazlı renk ayrımı yapıldı

• Korelasyon Matrisi

Sadece sayısal değişkenler kullanılarak heatmap oluşturuldu.

• Pair Plot

Sayısal değişkenler arasındaki ilişkiler toplu olarak incelendi.

🧪 Kullanılan Kütüphaneler

pandas

numpy

matplotlib

seaborn

📁 Dosya Yapısı
global-education-analysis/
│
├── education_eda.ipynb   → Tüm analiz adımları burada
├── education.csv         → Veri seti (isteğe bağlı eklenebilir)
└── README.md             → Proje açıklaması

📌 Sonuçlar

Bu çalışma kapsamında:

Eğitim göstergeleri arasındaki ilişkiler görselleştirildi

Ülkelerin yıllara göre eğitim trendleri karşılaştırıldı

Eğitim harcaması ve nüfus arasındaki etkileşim incelendi

Okuryazarlık ve eğitim süresine dair anlamlı örüntüler ortaya çıkarıldı

Proje, temel EDA tekniklerini gerçek bir veri seti üzerinde uygulayarak analitik bakış açısını güçlendirmeyi amaçlamaktadır.

🚀 Gelecek Geliştirmeler

Daha fazla yıl ve ülke eklenebilir

Makine öğrenmesiyle eğitim harcaması tahmini yapılabilir

Mevcut grafiklere interaktif dashboard eklenebilir
