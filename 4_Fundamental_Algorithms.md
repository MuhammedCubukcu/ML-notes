# 4. Temel Algoritmalar
# A. Regresyon
Regresyon, istatistik ve makine öğrenimi alanlarında kullanılan bir tekniktir. Bu teknik, bir veya birden fazla bağımsız değişkenin, bir bağımlı değişken üzerindeki etkilerini analiz etmek veya tahmin etmek için kullanılır.

### Regresyonun Temel İlkeleri
* Bağımlı Değişken (Y): Tahmin edilmek istenen değişken. Örneğin, ev fiyatları.

* Bağımsız Değişkenler (X): Tahminde kullanılan değişkenler. Örneğin, evin büyüklüğü, oda sayısı, konumu, vb.

* İlk Model: En basit haliyle, regresyon bir doğru veya eğri kullanarak bağımlı değişkenin bağımsız değişkenlere nasıl bağlı olduğunu ifade eder.

### En Küçük Kareler Yöntemi
* Regresyon analizinde, hedef, gözlemlenen değerlerle modelin tahmin ettiği değerler arasındaki hata karelerinin toplamını en aza indirecek şekilde ayarlanır.

###  Lineer Regresyon
* En basit regresyon modelidir. Bağımlı değişken ile bağımsız değişken arasındaki ilişki doğrusal bir modelle ifade edilir.

### Çoklu Regresyon
* Birden fazla bağımsız değişkenin kullanıldığı bir regresyon modelidir.

### Lojistik Regresyon
* Sınıflandırma problemlerinde kullanılır. Sonuç, bir sınıfa ait olma olasılığı olarak ifade edilir.

### Regresyonun Uygulama Alanları
* Ekonomi: Gelir tahminleri, tüketici davranışları.

* Tıp: Hastalık riski tahmini, tedavi etkinliği.

* Finans: Hisse senedi fiyat tahminleri, risk analizi.

### Regresyonun Değerlendirilmesi
* MSE (Mean Squared Error): Tahmin edilen değerler ile gerçek değerler arasındaki karelerin ortalaması.

* R² (R-Kare): Bağımsız değişkenlerin bağımlı değişkeni ne kadar açıkladığını ölçer.

# B. Sınıflandırma

Sınıflandırma, bir veri noktasını belirli bir kategoriye atamak için kullanılan bir makine öğrenimi tekniğidir. Bu, genellikle bir veri noktasının hangi sınıfa ait olduğunu belirlemek amacıyla kullanılır.

### Temel İlkeler

- **Bağımlı Değişken (Y):** Belirli bir kategoriye ait olup olmadığını belirlemek istediğimiz değişken. Örneğin, bir e-postanın spam olup olmadığını belirlemek.

- **Bağımsız Değişkenler (X):** Bu veri noktasının sınıflandırılmasında kullanılan özellikler. Örneğin, e-postanın metni, gönderenin adresi, vb.

### Lojistik Regresyon

- Sınıflandırma problemlerinde yaygın olarak kullanılır. Sonuç, bir sınıfa ait olma olasılığı olarak ifade edilir.

### Karar Ağaçları

- Sınıflandırma işlemini bir dizi karar kuralıyla gerçekleştirir. Her bir kararın sonucunda belirli bir sınıfa atanır.

### Destek Vektör Makineleri (SVM)

- Veri noktalarını farklı sınıflara ayırmak için bir hiper düzlem oluşturur.

### K-En Yakın Komşu (K-Nearest Neighbors - KNN)

- Bir veri noktasını sınıflandırmak için en yakın k komşusunu kullanır.

###  Naive Bayes

- İstatistiksel bir sınıflandırma tekniğidir. Her özelliğin sınıf olasılıklarını bağımsız olarak etkilediğini varsayar.

### Değerlendirme Metrikleri

- **Doğruluk (Accuracy):** Doğru sınıflandırılan veri noktalarının oranı.

- **Hassasiyet (Precision):** Pozitif olarak tahmin edilenlerin ne kadarının doğru olduğu.

- **Duyarlılık (Recall):** Gerçek pozitiflerin ne kadarının tespit edildiği.

- **F1 Skoru:** Hassasiyet ve duyarlılığın harmonik ortalaması.

### Uygulama Alanları

- Spam filtreleme, tıbbi teşhis, duygu analizi gibi birçok alanın



# C. Kümeleme

Kümeleme (Clustering), veri noktalarını benzerlikleri temelinde gruplara ayıran bir makine öğrenimi tekniğidir. Bu, veri setindeki doğal yapıyı keşfetmek için kullanılır.

### Temel İlkeler

- **Küme (Cluster):** Benzerlik ölçütlerine göre bir araya getirilen veri noktaları grubu.

- **Hedef:** Her bir kümenin içindeki veri noktaları birbirine benzer, farklı kümlerdeki veri noktaları ise birbirinden farklı olmalıdır.

### K-Means Kümeleme

- Veri noktalarını belirli bir sayıda küme (K) içerisine ayırır.
- Her veri noktasını en yakın küme merkezine atar.

### Hiyerarşik Kümeleme

- Veri noktalarını hiyerarşik yapıda kümelere ayırır.
- Bu yöntem alt küme oluşturma işlemini adım adım gerçekleştirir.

### DBSCAN (Yoğunluk Tabanlı Kümeleme)

- Veri noktalarını yoğunluklarına göre kümelere ayırır.
- Düşük yoğunluklu bölgeleri ayırt eder.

### Agglomerative Clustering

- Hiyerarşik kümeleme yöntemlerinden biridir.
- Veri noktalarını birleştirerek küme oluşturur.

### K-Medoids

- K-Means'e benzer, ancak küme merkezleri veri noktalarından seçilir.

### Değerlendirme Metrikleri

- **Silhouette Skoru:** Bir veri noktasının kendi kümesine olan benzerliği ile en yakın olmayan kümenin veri noktalarına olan benzerliği arasındaki farkı ölçer.

### Uygulama Alanları

- Pazarlama segmentasyonu, görüntü işleme, biyoinformatik gibi birçok alanda kullanılır.



