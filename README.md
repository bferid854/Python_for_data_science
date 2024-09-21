### English Version

**Title**: Rule-Based Classification for Estimating Potential Customer Revenue

**Description**: 
In this project, I calculated the potential revenue for future customers using rule-based classification. The dataset provided by a travel company includes various sales and customer information. Initially, I performed exploratory data analysis to understand the key characteristics of the data, such as unique values and averages for different cities and concepts. Following that, I categorized customers based on their booking lead time (EB Score) and examined the relationship between city, concept, and season with respect to the average price and frequency.

I then created new sales definitions (level-based sales) by combining different features (City, Concept, Season), which allowed for a more granular analysis of potential customer segments. The sales definitions were grouped into segments (A, B, C, D) using the `Price` variable, and each segment's characteristics were analyzed to identify their expected revenue.

Finally, I tested the model by predicting the potential revenue for a specific customer persona, 'ANTALYA_HERŞEY DAHIL_HIGH', which represented a customer from Antalya choosing an all-inclusive hotel during the high season.

---

### Turkish Version

**Başlık**: Kural Tabanlı Sınıflandırma ile Potansiyel Müşteri Getirisi Hesaplama

**Açıklama**: 
Bu projede, kural tabanlı sınıflandırma yöntemi kullanarak gelecekteki müşterilerin potansiyel getirilerini hesapladım. Gezinomi şirketinden alınan veri seti, çeşitli satış ve müşteri bilgilerini içermektedir. İlk olarak, veri setine keşifsel veri analizi uygulayarak şehir ve konseptlere göre eşsiz değerleri ve ortalamaları inceledim. Daha sonra, müşterileri rezervasyon süresine (EB Score) göre kategorize ederek şehir, konsept ve sezon kırılımında ortalama fiyat ve frekans ilişkilerini analiz ettim.

Farklı özellikleri (Şehir, Konsept, Sezon) birleştirerek yeni satış tanımları (level-based satışlar) oluşturup, potansiyel müşteri segmentleri üzerinde daha detaylı analiz yapmamı sağladım. Satış tanımlarını, `Price` değişkenine göre A, B, C ve D segmentlerine ayırdım ve her bir segmentin getiri beklentilerini analiz ettim.

Son olarak, belirli bir müşteri profili olan 'ANTALYA_HERŞEY DAHIL_HIGH' için potansiyel müşteri getirisi tahmini yaparak modelin performansını test ettim. Bu müşteri, Antalya’dan her şey dahil bir otele yoğun sezonda giden bir müşteriyi temsil ediyordu.
