#  Trafik Kazaları Veri Analizi (2012–2014)

Bu proje, Birleşik Krallık'ta 2012–2014 yılları arasında meydana gelen trafik kazalarına ait veriler kullanılarak yapılmış bir keşifsel veri analizi (EDA) çalışmasıdır.

##  Veri Kümesi

Veri dosyası: `accidents_2012_to_2014.csv`  
Toplam gözlem: ~464,000  
Veri kaynağı: [UK Department for Transport (DfT)]

##  Amaç

- Trafik kazalarının **zamansal**, **coğrafi**, **yol tipi**, **hava durumu** ve **ışık koşulları** gibi faktörlere göre dağılımını incelemek
- Kaza şiddetinin etkileyen değişkenlerle ilişkisini ortaya koymak
- Korelasyon analizleri ve görselleştirme ile veri üzerinden anlamlı sonuçlar çıkarmak

##  Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

##  Yapılan Analizler

- **Eksik veri analizi** ve gereksiz sütunların çıkarılması
- **Yol tipi**, **ışık koşulları**, **hava durumu**, **yaya geçidi durumu** gibi değişkenlere göre kaza dağılımı
- **Kaza saatine** ve **gününe** göre yoğunluk grafikleri
- **Kentsel-kırsal bölge farkı** ve kaza şiddeti karşılaştırması
- **Korelasyon matrisi** ile sayısal değişkenler arası ilişki analizi

##  Örnek Görselleştirmeler

- Saatlik kaza yoğunluğu (bar chart)
- Aylık kaza sayısı (zaman serisi)
- Kaza şiddeti dağılımı (boxplot ve oranlar)
- Korelasyon matrisi (heatmap)

##  Sonuçlar

- Kazalar en çok **iş giriş/çıkış saatlerinde** meydana gelmektedir.
- **Kırsal bölgelerde** ölümcül kazaların oranı daha yüksektir.
- **Aydınlatmanın yetersiz olduğu** yerlerde kazalar daha şiddetlidir.
- **Kaza şiddeti**, yaralı sayısı ile pozitif korelasyon göstermektedir.

##  Lisans

Bu proje eğitim ve analiz amaçlıdır. Veriler kamuya açık kaynaklardan alınmıştır.


