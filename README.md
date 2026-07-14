# GEO2R Sunitinib Gene Expression Analysis

Bu projede, renal kanser ksenograft modellerinde sunitinib uygulamasına bağlı gen ekspresyon değişimleri GEO2R kullanılarak incelenmiştir.

Çalışmanın amacı, vehicle kontrol grubu ile sunitinib uygulanan örnekleri karşılaştırmak, farklı ekspresyon davranışı gösteren genleri değerlendirmek ve GEO2R tarafından oluşturulan tanısal grafikleri yorumlamaktır.

## Veri Seti

- Veri tabanı: NCBI Gene Expression Omnibus
- Seri numarası: `GSE66346`
- Veri seti: `GDS5815`
- Organizma: `Homo sapiens`
- Çalışma konusu: Sunitinib uygulamasının renal kanser ksenograft tümörlerindeki gen ekspresyonuna etkisi

Analizde KURC1, KURC2 ve KURC3 renal kanser ksenograft modellerine ait vehicle ve sunitinib örnekleri karşılaştırılmıştır.

## Karşılaştırılan Gruplar

- Vehicle kontrol örnekleri
- Sunitinib uygulanan örnekler
- Sunitinib-duyarlı örnekler
- Sunitinib-dirençli örnekler

## İncelenen Genler

Çalışmada örnek olarak aşağıdaki genlerin ekspresyon düzeyleri değerlendirilmiştir:

- `OR4F17`
- `VPS13D`
- `DDI2`

Bu genlerin KURC1, KURC2 ve KURC3 modellerindeki ekspresyon değerleri ve örnek içi yüzdelik sıralamaları karşılaştırılmıştır.

## Kullanılan Yöntem ve Araçlar

- NCBI GEO veri tabanı
- GEO2R
- Diferansiyel gen ekspresyon analizi
- Grup karşılaştırması
- Gen ekspresyon profillerinin yorumlanması
- Veri görselleştirme ve tanısal grafik değerlendirmesi

## İncelenen Grafikler

- Volcano Plot
- Mean-Difference Plot
- UMAP
- Boxplot
- Expression Density Plot
- Moderated t-Statistic Q-Q Plot
- Mean-Variance Trend Plot

## Temel Bulgular

- Vehicle ve sunitinib grupları arasında bazı genlerde ekspresyon farklılıkları gözlemlenmiştir.
- OR4F17 geninde bazı sunitinib-dirençli örneklerde daha yüksek ekspresyon değerleri görülmüştür.
- VPS13D ve DDI2 genlerinin bazı dirençli örneklerde duyarlı örneklere göre daha yüksek ekspresyon gösterebildiği gözlemlenmiştir.
- UMAP grafiğinde bazı sunitinib örneklerinin vehicle örneklerinden ayrıştığı görülmüştür.
- Boxplot ve expression density grafiklerinde örneklerin genel ekspresyon dağılımlarının birbirine yakın olduğu görülmüştür.
- Sonuçlar, örnek sayısının sınırlı olması nedeniyle keşifsel nitelikte değerlendirilmiştir.

## Sonuç

Analiz sonucunda bazı genlerin vehicle ve sunitinib grupları arasında farklı ekspresyon davranışları gösterebildiği görülmüştür. OR4F17, VPS13D ve DDI2 genleri örnek genler olarak incelenmiştir.

Volcano plot, UMAP ve diğer tanısal grafikler, sunitinib uygulamasının bazı örneklerde gen ekspresyon profilleriyle ilişkili olabileceğini düşündürmektedir. Ancak örnek sayısının sınırlı olması nedeniyle bulgular kesin biyolojik sonuçlar olarak değil, keşifsel analiz sonuçları olarak değerlendirilmelidir.

## Proje Raporu

Analiz ayrıntılarını, gen ekspresyon grafiklerini ve yorumları aşağıdaki raporda inceleyebilirsiniz:

[Proje raporunu görüntüle](geo2r-sunitinib-gene-expression-analysis-report.pdf)

## Proje Hakkında

Bu çalışma, Biyoinformatiğe Giriş dersi kapsamında hazırlanmıştır. Projede açık erişimli bir gen ekspresyon veri seti kullanılarak biyolojik verilerin istatistiksel olarak değerlendirilmesi ve görselleştirilmesi amaçlanmıştır.

## Hazırlayan

**Ayşe Zehra Yılmaz**  
İstatistik Bölümü Mezunu
