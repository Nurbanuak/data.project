# Obesity Prediction Project

Bu proje, obeziteye etki eden faktörleri inceleyen ve obezite durumunu tahminlemek için bir makine öğrenimi modeli geliştiren bir çalışmadır.

## Veri Seti

Bu projede kullanılan veri seti "Obesity dataset.csv" adlı bir CSV dosyasından okunmuştur. Veri seti, obezite ile ilgili çeşitli özellikleri içermektedir.

## Kullanılan Özellikler

Proje, obezite durumunu tahminlemek için aşağıdaki özellikleri kullanmaktadır:

- Cinsiyet (Gender): Bir katılımcı erkekse 1, kadınsa 0'dır.

- Yaş (Age): Bir katılımcının yaşı, yıl cinsindendir.

- Ailede Şişmanlık Hikayesi (family_history_with_overweight): Bir katılımcının ailesinde şişmanlık hikayesi varsa 1, yoksa 0'dır.

- Yüksek Kalorili Yiyecek Tüketimi (FAVC): Bir katılımcı sık sık yüksek kalorili yiyecek tüketiyorsa 1, değilse 0'dır.

- Sebze Tüketimi (FCVC): Bir katılımcı genellikle yemeklerinde sebze tüketiyorsa 1, değilse 0'dır.

- Günlük Ana Öğün Sayısı (NCP): Bir katılımcının günlük ana öğün sayısı. 0, 1-2 öğün; 1, 3 öğün; 2, 3'ten fazla öğün.

- Öğünler Arası Yiyecek Tüketimi (CAEC): Bir katılımcının öğünler arasında yemek tüketim miktarı, 0 ile 3 arasında bir ölçekte ifade edilir.

- Sigara İçme Durumu (SMOKE): Bir katılımcı sigara içiyorsa 1, içmiyorsa 0'dır.

- Su Tüketimi (CH2O): Bir katılımcının su içme miktarı, 0 ile 2 arasında bir ölçekte ifade edilir.

- Kalori Takibi (SCC): Bir katılımcı kalori alımını takip ediyorsa 1, etmiyorsa 0'dır.

- Fiziksel Aktivite Düzeyi (FAF): Bir katılımcının fiziksel aktivite düzeyi, 0 ile 3 arasında bir ölçekte ifade edilir.

- Ekran Başında Geçirilen Zaman (TUE): Bir katılımcının ekran başında geçirdiği zaman, 0 ile 2 arasında bir ölçekte ifade edilir.

- Alkol Tüketimi Sıklığı (CALC): Bir katılımcının alkol tüketme sıklığı, 0 ile 3 arasında bir ölçekte ifade edilir.

- Ulaşım Araçları (Automobile, Bike, Motorbike, Public_Transportation, Walking): Bir katılımcının ana ulaşım aracını belirtir. Ana ulaşım aracı 1 olarak belirtilir, diğer araçlar 0 olarak belirtilir.

- Obezite Durumu (NObeyesdad): Bir katılımcı obezse 1, değilse 0'dır.

## Kullanılan Python Kodu

Python programlama dili kullanılarak, veri seti üzerinde çeşitli makine öğrenimi algoritmaları uygulanmıştır. Ana kod dosyası "obesity_prediction.py" adını taşımaktadır.

## Kullanım

Projenin çalıştırılması için aşağıdaki adımları takip edebilirsiniz:

1. Veri setini "Obesity dataset.csv" olarak sağlayın.
2. Ana kod dosyasını çalıştırarak makine öğrenimi modelini eğitin ve sonuçları gözlemleyin.

## Gereksinimler

Projenin çalışması için aşağıdaki Python kütüphanelerine ihtiyaç vardır:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn