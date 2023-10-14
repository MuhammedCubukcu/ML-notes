# 2. Veri Hazırlığı
Veri hazırlığı, makine öğrenimi projelerinde en önemli adımlardan biridir. Veri setinin temizlenmesi, düzenlenmesi ve modele uygun hale getirilmesi aşamalarını içerir.

## a. Eksik Verilerin İşlenmesi:
* Eksik veriler, veri setinde boş veya tanımsız değerlerdir. Bu durum, veri analizi ve model eğitimi için sorun oluşturabilir.

* Eksik verilerin işlenmesi için çeşitli yaklaşımlar vardır:
    * Eksik değerlerin silinmesi
    * Ortalama, medyan gibi istatistiksel değerlerle doldurma
    Eksik değerlerin tahmin edilmesi (örneğin, K-NN algoritmasıyla)
## b. Kategorik Değişkenlerin İşlenmesi:

* Kategorik değişkenler, sayısal olmayan değerlerdir (örneğin, renkler, kategoriler).

* Makine öğrenimi modelleri genellikle sayısal girdi bekler, bu nedenle kategorik değişkenler dönüştürülmelidir.

* One-Hot Encoding: Kategorik değişkenler, ikili (0, 1) değerlere dönüştürülür.

## c. Veri Standardizasyonu ve Normalizasyonu:
* Değişkenler arasındaki ölçek farklılıklarını düzelten bir işlemdir.

* Standartlaştırma: Verilerin ortalama değerini 0, standart sapmasını 1 yapar.

* Normalizasyon: Verileri belirli bir aralığa (genellikle 0 ile 1 arası) dönüştürür.

## d. Aykırı Değerlerin İşlenmesi:
* Aykırı değerler, diğer veri noktalarından önemli ölçüde farklı olan değerlerdir.

* Aykırı değerler, modele olumsuz etki edebilir. Bu nedenle, belirli bir eşik değerinin ötesinde olan değerler incelenmeli ve işlenmelidir.

## e. Veri Dönüşümleri: 
* Bazı veri dönüşümleri, modele daha iyi uyan veri yapılarına dönüştürme işlemleridir.

* Örnekler: Log dönüşümü, karekök dönüşümü.

## f. Özellik Mühendisliği:
* Mevcut veri setinin özelliklerini kullanarak yeni özelliklerin oluşturulmasıdır.

* Özellik mühendisliği, modelin daha iyi performans göstermesini sağlayabilir.

# g. Veri Görselleştirmesi:
* Veri setini görsel olarak analiz etmek, veri setindeki yapıları anlamak için önemlidir.

* Grafikler, histogramlar, kutu grafikleri gibi görsel araçlar kullanılır.

Bu notlar, veri hazırlığının temel adımlarını kapsamaktadır. Veri hazırlığı, bir makine öğrenimi projesinin başarılı olabilmesi için kritik bir öneme sahiptir. Bu adımları dikkatlice uygulamak, daha doğru ve güvenilir sonuçlara ulaşmanızı sağlar.