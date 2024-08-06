# california_Housing
Model Performansını Değerlendirme
Elde ettiğimiz kök ortalama kare hatası (RMSE) değerlerini karşılaştıralım:

Random Forest RMSE: 0.505
Linear Regression RMSE: 0.746
KNN RMSE: 0.658
Bu sonuçlara göre, Random Forest modeli en düşük RMSE değerine sahip olduğu için diğer modellerden daha iyi performans göstermektedir.

Sonuçları Raporlama
Proje sonuçlarını raporlayarak tamamlayacağız. Rapor aşağıdaki başlıkları içermelidir:

Problem Tanımı
Veri Keşfi ve Temizleme
Veri Ön İşleme
Modelleme
Model Performansını Değerlendirme
Sonuçlar ve Yorumlar
1. Problem Tanımı
Bu proje, California Housing veri setini kullanarak ev fiyatlarını tahmin etmeyi amaçlamaktadır. Hedef değişken PRICE olup, özellikler arasında medyan gelir (MedInc), ev yaşı (HouseAge), ortalama oda sayısı (AveRooms), ortalama yatak odası sayısı (AveBedrms), nüfus (Population), ortalama hane sayısı (AveOccup), enlem (Latitude) ve boylam (Longitude) yer almaktadır.

2. Veri Keşfi ve Temizleme
Veri setinde eksik veri bulunmamaktadır. Veri setinin özet istatistikleri ve görselleştirmeler, veri dağılımlarını ve özellikler arasındaki ilişkileri anlamamıza yardımcı olmuştur. Korelasyon matrisi, bazı özelliklerin hedef değişkenle güçlü korelasyona sahip olduğunu göstermiştir.

3. Veri Ön İşleme
Veri seti, hedef değişken PRICE ve özellikler olarak ayrılmış, ardından eğitim ve test setlerine bölünmüştür. Özellikler, modellerin daha iyi performans göstermesi için ölçeklendirilmiştir.

4. Modelleme
Üç farklı model eğitilmiştir:

Random Forest Regressor
Linear Regression
K-Nearest Neighbors (KNN) Regressor
5. Model Performansını Değerlendirme
Modeller, test seti üzerinde değerlendirilmiş ve aşağıdaki RMSE değerleri elde edilmiştir:

Random Forest: 0.505
Linear Regression: 0.746
KNN: 0.658
Random Forest modeli en düşük RMSE değerine sahip olup en iyi performansı göstermiştir.

6. Sonuçlar ve Yorumlar
Bu projede, California Housing veri seti kullanılarak ev fiyatlarını tahmin etmeye çalıştık. Üç farklı model eğitip değerlendirdik ve en iyi performansı Random Forest modelinin gösterdiğini gördük. Bu model, veri setindeki karmaşık ilişkileri daha iyi yakalayabilme kapasitesine sahip olduğu için en düşük hata oranına sahip olmuştur.
