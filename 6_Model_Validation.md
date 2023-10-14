# 6. Model Doğrulama

Model doğrulama (Model Validation), makine öğrenimi modellerinin performansını değerlendirmek için kullanılan bir dizi tekniktir. Bu teknikler, bir modelin gerçek dünya verileri üzerinde ne kadar iyi performans göstereceğini tahmin etmeye yardımcı olur.

## Temel İlkeler

- **Neden Model Doğrulama?** Bir modelin eğitim verilerine ne kadar iyi uyduğunu değil, aynı zamanda yeni verilerle nasıl performans göstereceğini de bilmek önemlidir.

## K-Fold Çapraz Doğrulama

- Veri seti K parçaya bölünür.
- K-1 parça eğitimde kullanılır, 1 parça test edilir.
- Bu işlem K defa tekrar edilir.
- Sonuçlar ortalamalanarak modelin performansı değerlendirilir.

## Holdout Doğrulama

- Veri seti rastgele iki gruba ayrılır: eğitim seti ve test seti.
- Model eğitim seti üzerinde eğitilir, test seti üzerinde değerlendirilir.

## Bootstrap Doğrulama

- Veri setinden rastgele örneklemler alınarak birden fazla eğitim seti oluşturulur.
- Her eğitim seti üzerinde model eğitilir ve performans değerlendirilir.

## Hiperparametre Ayarlama ile K-Fold Çapraz Doğrulama

- Modelin hiperparametrelerini belirlemek için K-Fold çapraz doğrulama kullanılır.
- Grid Search veya Random Search gibi tekniklerle en iyi hiperparametre kombinasyonu bulunur.

## Uygulama Alanları

- Model doğrulama, bir modelin gerçek dünya verileri üzerinde ne kadar iyi performans göstereceğini değerlendirmek için kullanılır.