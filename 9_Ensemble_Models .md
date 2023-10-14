# 9. Ensemble Modeller

Ensemble modelleri, birden fazla temel modelin kombinasyonuyla daha güçlü bir model oluşturmayı amaçlayan bir makine öğrenimi tekniğidir. Bu, farklı modellerin bir araya getirilmesiyle genellikle daha iyi performans elde etmek için kullanılır.

## Temel İlkeler

- **Neden Ensemble Modelleri?** Farklı modellerin birleştirilmesi, tek başına kullanılan modellere göre daha iyi sonuçlar elde etme potansiyeline sahiptir.

## Ensemble Modellerinin Türleri

1. **Bagging (Bootstrap Aggregating):** Aynı algoritmanın farklı örneklemeleriyle farklı modeller oluşturur. Örneğin, Random Forest algoritması.

2. **Boosting:** Zayıf modelleri bir araya getirerek güçlü bir model oluşturur. Örneğin, AdaBoost, Gradient Boosting.

3. **Voting:** Farklı modellerin tahminlerini birleştirerek en yaygın sınıfı seçer. Örneğin, Hard Voting, Soft Voting.

4. **Stacking:** Farklı modellerin tahminlerini girdi olarak kullanarak bir meta-model oluşturur.

## Ensemble Modellerinin Avantajları

- Daha iyi genelleme yeteneği.
- Daha yüksek performans.
- Daha az aşırı uyum eğilimi.

## Uygulama Alanları

- Sınıflandırma ve regresyon problemlerinde yaygın olarak kullanılır.