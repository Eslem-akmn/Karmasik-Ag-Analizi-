# Karmasik-Ag-Analizi-

20. Hesaplanan Tüm Metriklerin Yorumlanması
- Topluluk Yapısı (Modularity: 0.337): Ağın modülerlik skoru 0.3'ün üzerinde çıkmıştır. Bu durum, ağdaki düğümlerin rastgele dağılmadığını, aksine belirgin gruplar veya topluluklar oluşturduğunu gösterir. Ağ kendi içinde alt kümelere ayrılma eğilimindedir.

- Ağ Yoğunluğu (Density: 0.28): Ağın yoğunluğu yaklaşık %28 seviyesindedir. Bu, olası tüm bağlantıların sadece üçte birinden azının kurulduğunu gösterir. Ağ çok sıkışık değildir, daha gevşek ve genişlemeye müsait bir yapıdadır.

- Kümelenme (Average Clustering: 0.42): Yoğunluk düşük olmasına rağmen kümelenme katsayısı (0.42) görece yüksektir. Bu, "arkadaşımın arkadaşı benim de arkadaşımdır" ilkesinin ağda güçlü olduğunu, düğümlerin yerel seviyede birbirine sıkı bağlı üçgenler oluşturduğunu gösterir.
​
- İletişim Hızı (Diameter: 4): Ağın çapı 4'tür. En uzak iki düğüm bile birbirine sadece 4 adım mesafededir. Bu, ağın "Küçük Dünya" (Small World) özelliği taşıdığını ve bilginin ağ üzerinde çok hızlı yayılabileceğini gösterir.
​
21. En Kritik 5 'Köprü' Düğümü (Betweenness Centrality)
- Bu düğümler ağın farklı bölgeleri arasındaki bilgi akışını sağlayan "aracı" düğümlerdir. En yüksek skora sahip olanlar, ağın iletişim trafiğini kontrol eder.

​s03 (Skor: 0.340) - Ağın ana köprüsü, en kritik aracı.

​s04 (Skor: 0.196)

​s12 (Skor: 0.123)

​s06 (Skor: 0.100)

​s05 (Skor: 0.065)

22. En Kritik 5 'Lider' Düğümü (Degree Centrality)
- Bu düğümler ağda en çok bağlantıya sahip olan, en popüler ve görünürlüğü en yüksek "merkez" düğümlerdir.

​s03 (Derece Skoru: 0.56) - Hem köprü hem lider olmasıyla ağın en güçlü aktörüdür.

​s04 (Derece Skoru: 0.44)

​s01 (Derece Skoru: 0.31)

​s02 (Derece Skoru: 0.31)

​s05 (Derece Skoru: 0.31)

​
24. En Güçlü 3 Düğümün (s03, s04, s01) Ağdan Kaldırılması ve Değişim Yorumu
- ​Ağın en yüksek dereceye sahip 3 düğümü olan s03, s04 ve s01 ağdan çıkarıldığında şu değişimler gözlenmiştir:
​
- Yapısal Değişim: Bu üç düğüm ağın omurgasını oluşturmaktadır. Normalde bu tür merkezi düğümlerin çıkarılması ağı genellikle parçalar. Ancak bu veri setinde kalan düğümler ağı tek parça tutmayı başarmıştır. Ağ kopup parçalara ayrılmamıştır.

- İletişim Mesafesi: Ağ parçalanmasa da "yol" uzamıştır. Ağın çapı 4'ten 5'e yükselmiştir. En güçlü kısa yollar (shortcut) silindiği için, bilgi artık daha dolaylı yollardan gitmek zorunda kalmıştır.
​
- Genel Yorum: Ağ, en güçlü 3 liderini kaybetmesine rağmen kopmayarak yapısal bir direnç göstermiştir. Ancak iletişim verimliliği düşmüş ve mesafe uzamıştır.
