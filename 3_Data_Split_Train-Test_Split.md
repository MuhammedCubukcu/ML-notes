# 3. Veri Bölme (Train-Test Split)
Veri setinin doğru bir şekilde bölünmesi, modelin gerçek dünya verileri üzerinde nasıl performans göstereceğini değerlendirmek için önemlidir.

## a. Kütüphane İçeri Aktarma:
```python
from sklearn.model_selection import train_test_split
```
## b. Veri Setini Ayırma:
Veri setini bağımlı değişken (y) ve bağımsız değişkenler (X) olarak ayırın. Genellikle bu, veri setindeki sütunları seçerek yapılır.

```python
X = veri[['Özellik1', 'Özellik2', 'Özellik3']]  # Bağımsız değişkenler
y = veri['Hedef']  # Bağımlı değişken
```

## c. Eğitim ve Test Setlerine Ayırma:
Veri setini eğitim ve test setlerine ayırın. test_size parametresi, test setinin oranını belirtir. Genellikle 0.2 veya 0.3 olarak belirlenir.
```python
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)
```

* X_train: Eğitim setinin bağımsız değişkenleri
* X_test: Test setinin bağımsız değişkenleri
* y_train: Eğitim setinin bağımlı değişkeni
* y_test: Test setinin bağımlı değişkeni

## d. Sonuçları Kontrol Etme:
Eğitim ve test setlerinin boyutlarını kontrol edin.
```python
print(f"Eğitim seti boyutu: {X_train.shape}")
print(f"Test seti boyutu: {X_test.shape}")
```

### e. Not:
* random_state parametresi, her seferinde aynı şekilde veri setini rastgele ayırmak için kullanılır. Bu, sonuçların tekrarlanabilirliği için önemlidir.

Bu adımlar, veri setini eğitim ve test setlerine ayırmak için temel bir yöntemi temsil eder. Bu, modelin eğitilmesi ve değerlendirilmesi için ayrılmış veri setlerinin kullanılmasını sağlar.