# **Novel Corona Virus 2019 Dataset Analysis 🦠**

## **Proje Açıklaması 📊**

Bu projede, Kaggle üzerinde bulunan **Novel Corona Virus 2019 Dataset** veri seti kullanılarak COVID-19 verilerinin kapsamlı bir şekilde analizi yapılmıştır. Proje, dünya çapında görülen COVID-19 vakalarının, ölüm oranlarının ve iyileşen hasta sayılarının analizine odaklanmaktadır. Amaç, pandemi sürecine dair önemli çıkarımlar yaparak sağlık politikalarını geliştirmek, kaynak yönetimini iyileştirmek ve gelecekteki salgınlara karşı hazırlıklı olmak için stratejiler önerilmektedir. 

Veri seti, dünya genelindeki COVID-19 vaka sayıları, ölümler ve iyileşen hastalar gibi kritik verileri içermektedir. Bu veriler üzerinden salgının yayılma hızı, ölüm oranları, iyileşme oranları gibi sağlık göstergeleri analiz edilmiştir. Proje kapsamında, veri setinin ilk incelenmesi, eksik verilerin analizi ve veri temizleme işlemleri yapılmış; ardından keşifsel veri analizi (EDA) ile veri setindeki bölgeler arası farklar ve ilişkiler detaylandırılmıştır.

Proje, COVID-19'un sağlık sistemleri üzerindeki etkisini anlamamıza yardımcı olmakta ve gelecekteki salgınlara yönelik stratejilerin geliştirilmesine katkı sağlamaktadır.

---

## **Proje Adımları 🔍**

Proje, aşağıdaki adımlarla gerçekleştirilmiştir:

### 1. **Kütüphanelerin Yüklenmesi ve Veri Setinin İlk İncelemesi 📂**  
- Bu adımda, projede kullanılacak temel kütüphaneler yüklenmiş ve Kaggle'dan veri seti indirilmiştir. Verinin genel yapısını anlamak amacıyla ilk 5 satır incelenmiş, sütun türleri belirlenmiş ve veri setindeki eksiklikler tespit edilmiştir.

### 2. **Eksik Veri Oluşturmadan Önceki Veri Analizi 🔧**  
- Eksik verilerle çalışmadan önce, veri setinin mevcut yapısı derinlemesine incelenmiştir. Kategorik değişkenlerin dağılımları, sayısal sütunların histogramları ve her sütundaki benzersiz değerlerin sayısı analiz edilmiştir.

### 3. **Veri Setine Eksik Verilerin Eklenmesi 🧩**  
- Gerçek dünya verilerinde karşılaşılan eksik veri sorununu simüle etmek amacıyla veri setine %2 oranında eksik veri eklenmiştir. Bu işlem, eksik verilerin modelleme sürecine etkisini gözlemlememizi sağlamıştır.

### 4. **Keşifsel Veri Analizi (EDA) 🔎**  
- Veri setindeki sayısal ve kategorik değişkenlerin dağılımı incelenmiş, korelasyon analizi yapılmış ve eksik veri analizi gerçekleştirilmiştir. Verinin yapısı hakkında daha derinlemesine bilgiler edinilmiş ve önemli ilişkiler keşfedilmiştir.

### 5. **Eksik Verilerin Temizlenmesi 🧹**  
- Eksik veriler, sayısal sütunların ortalama değerleri ile doldurulmuş ve veri seti temizlenmiştir. Bu adım, eksik veri probleminin nasıl ele alındığını ve verinin güvenilirliğinin nasıl artırıldığını göstermektedir.

### 6. **İstatistiksel Analiz ve Görselleştirme 📈**  
- Bar grafikleri, çizgi grafikleri, scatter plot'lar ve histogramlar gibi görselleştirmelerle verinin analizi yapılmıştır. COVID-19’un küresel etkisi, günlük vaka artışları, ölüm oranları ve iyileşen hastaların durumu gibi metrikler detaylı olarak analiz edilmiştir.

### 7. **Sonuçlar ve Öneriler 📝**  
- Analizlerin sonuçları doğrultusunda sağlık politikaları ve kaynak yönetimi için öneriler geliştirilmiştir. Ayrıca, gelecekteki salgınlar için kullanılabilecek makine öğrenimi modelleri önerilmiştir.

---

## **Kullanılan Kütüphaneler 🛠️**

Projede, aşağıdaki Python kütüphaneleri kullanılmıştır:

- **pandas**: Veri işleme ve analiz için kullanılmıştır. Veri setinin yüklenmesi, filtrelenmesi ve manipülasyonu bu kütüphane ile yapılmıştır.
- **numpy**: Matematiksel işlemler ve veri manipülasyonu için kullanılmıştır. Eksik veri ekleme ve veri dönüşümleri numpy ile gerçekleştirilmiştir.
- **seaborn**: İleri düzey veri görselleştirme için kullanılmıştır. Grafiklerin görsel kalitesini arttırarak veri analizi süreçlerini daha anlaşılır hale getirmiştir.
- **matplotlib**: Grafik çizimleri için kullanılmıştır. Hem istatistiksel hem de keşifsel analizler için çizilen tüm görseller matplotlib ile oluşturulmuştur.

---

## **Sonuçlar ve Öneriler 📊**

### **Veri Setinin Potansiyel Kullanımı ve Problemi Tanımlama 🏥**

COVID-19 vaka sayılarındaki artışları analiz etmek, sağlık bakanlıkları ve hastane yöneticileri için kritik öneme sahiptir. Bu verilerle, sağlık hizmetlerinin ne kadar yoğun olduğunu, mevcut kaynakların nasıl yönetilmesi gerektiğini ve gelecekteki kaynak ihtiyaçlarını tahmin etmek mümkündür. Örneğin:

- **Sağlık Bakanlıkları**: Verileri kullanarak vaka artış hızlarını takip edebilir ve sağlık politikalarını buna göre oluşturabilir.
- **Hastane Yöneticileri**: Vaka sayısındaki artışı izleyerek yatak kapasitesini planlayabilir ve kaynak ihtiyaçlarını tahmin edebilir.

### **Makine Öğrenimi Modelleri Önerileri 🤖**

Bu projede, COVID-19 vaka sayılarının gelecekteki artışını tahmin etmek için birkaç makine öğrenimi modeli önerilmektedir:

1. **Zaman Serisi Analizi (ARIMA)**  
   - **Neden ARIMA?** Vaka sayılarındaki zaman bazlı değişimleri analiz etmek için uygundur. Gelecekteki vaka artış oranlarını tahmin etmek amacıyla kullanılabilir.

2. **Regresyon Modelleri (Linear Regression, Random Forest Regressor)**  
   - **Neden Regresyon Modelleri?** Vaka sayısı, ölüm oranı ve iyileşen oranı gibi değişkenlerin arasındaki ilişkileri tahmin etmek için güçlü bir yöntemdir.

3. **Derin Öğrenme Yöntemleri (LSTM - Long Short-Term Memory)**  
   - **Neden LSTM?** Zaman serisi veri analizi için çok güçlü bir derin öğrenme modelidir. Uzun dönemli bağımlılıkları öğrenebilir ve vaka artış trendlerini daha doğru tahmin edebilir.

### **Projenin Gelecekteki Kullanımı 🔮**

Bu analizlerin, sağlık sektöründe ve hükümet politikalarında kullanılabilecek büyük bir potansiyeli bulunmaktadır. Özellikle, ARIMA veya LSTM modelleri ile vaka artışlarını tahmin ederek bölgelerdeki sağlık hizmetleri planlanabilir. Ayrıca, regresyon modelleri ile risk altındaki bölgeler belirlenebilir ve bu sayede müdahale stratejileri geliştirilebilir.

