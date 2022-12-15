# Naive-Bayes
Naive bayes makine öğrenmesinin bir alt sınıfıdır.Denetimli öğrenme başlığı altında yer alır . Bir probleme olasılıksal yaklaşı yapmamıza yardımcı olur. İsmini Naïve Bayes sınıflandırıcısı adını İngiliz matematikçi Thomas Bayes'ten (yak. 1701 - 7 Nisan 1761) almaktadır

![Bayes'_Theorem_MMB_01](https://user-images.githubusercontent.com/76650271/207851006-f7263974-3238-458b-bd90-be7be65b95a9.jpg)


# Bayes teoremi
Naive Bayes sınıflandırıcısı Bayes teoreminin bağımsızlık önermesiyle basitleştirilmiş halidir. Bayes teoremi aşağıdaki denklemle ifade edilir;![71d8066a406fb22ce08eec25dd04870779345cd3](https://user-images.githubusercontent.com/76650271/207850046-3b30be50-c592-413a-af9f-9ab659e760d0.svg)

P(A|B) ; B olayı gerçekleştiği durumda A olayının meydana gelme olasılığıdır (bakınız koşullu olasılık)

P(B|A) ; A olayı gerçekleştiği durumda B olayının meydana gelme olasılığıdır

P(A) ve P(B) ; A ve B olaylarının önsel olasılıklarıdır.

![1_pkpoXVmLeBGauIAppMSVYQ](https://user-images.githubusercontent.com/76650271/207851189-3eabc126-1dd3-4872-9d89-68cb356dd0b0.png)


# Naive Bayes’de kullanılan fonksiyonlar

Naive bayes, birkaç farklı çeşidi bulunmaktadır. Bunlar şunlardır:

Gaussian naive bayes: Bu çeşit, verilen bir olayın sürekli değişkenlerini (örneğin, yaş, kilo, boy gibi değişkenler) dikkate alarak sınıflandırma yapar.

Multinomial naive bayes: Bu çeşit, verilen bir olayın birbiriyle ilişkisi olmayan birden fazla değişkenini (örneğin, kelime sayısı, kelime tipi gibi değişkenler) dikkate alarak sınıflandırma yapar.

Bernoulli naive bayes: Bu çeşit, verilen bir olayın birbiriyle ilişkisi olmayan tek değişkenli (örneğin, e-posta içerisinde kelime sayısı gibi) değişkenlerini dikkate alarak sınıflandırma yapar.

Complement naive bayes: Bu çeşit, verilen bir olayın sınıflandırılması için diğer naive bayes çeşitlerinin tahminlerini dikkate alarak daha doğru tahminler yapmayı amaçlar.

Bu çeşitler, naive bayes yöntemini farklı veri tipleri için uyarlar ve bu sayede daha doğru tahminler yapmayı mümkün kılar.



# Kaynakça
Scikit-learn: https://scikit-learn.org/stable/modules/naive_bayes.html

 Gfg: https://www.geeksforgeeks.org/naive-bayes-classifiers/
 
Wikipedia: https://en.wikipedia.org/wiki/Naive_Bayes_classifier

Youtube:  https://www.youtube.com/watch?v=O2L2Uv9pdDA

