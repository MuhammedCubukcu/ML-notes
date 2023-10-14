# Overfitting ve Underfitting

Aşırı uyum (Overfitting), bir makine öğrenimi modelinin eğitim verilerine çok fazla uyum sağlayarak, yeni ve görünmemiş verilerle kötü performans göstermesi durumudur. Yetersiz uyum (Underfitting) ise modelin eğitim verilerine yeterince uyum sağlayamaması ve hata yapması durumudur.

## Temel İlkeler

- **Aşırı Uyum (Overfitting):** Model, eğitim verilerine aşırı uyum sağlar ve yeni verilerle kötü performans gösterir.

- **Yetersiz Uyum (Underfitting):** Model, eğitim verilerini yeterince öğrenemez ve hata yapar.

## Overfitting Neden Olur?

- Model çok karmaşık ise.
- Eğitim veri seti çok küçük ise.
- Model çok uzun süre eğitiliyorsa.

## Underfitting Neden Olur?

- Model çok basit ise.
- Eğitim veri seti çok büyük ise.
- Model çok az süre eğitiliyorsa.

## Çözüm Yolları

- **Aşırı Uyum (Overfitting):**
  - Daha fazla eğitim verisi topla.
  - Daha az karmaşık bir model seç.
  - Regularizasyon tekniklerini kullan.

- **Yetersiz Uyum (Underfitting):**
  - Daha fazla özellik ekleyerek modeli karmaşıklaştır.
  - Daha uzun süre eğit.

## Uygulama Alanları

- Aşırı uyum ve yetersiz uyum, modelin doğru şekilde eğitilip eğitilmediğini değerlendirmek için önemlidir.