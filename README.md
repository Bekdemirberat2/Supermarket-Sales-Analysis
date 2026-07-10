# Supermarket-Sales-Analysis
🏛️ Proje Özeti ve Makro Analiz Yaklaşımı
Bu proje, Amerika Birleşik Devletleri genelindeki bir süpermarket zincirinin ham satış verilerini kullanarak; ülkenin farklı coğrafi bölgelerindeki tüketim, lojistik ve sosyo-ekonomik dinamikleri deşifre etmek amacıyla gerçekleştirilmiştir. Analiz sürecinde veriler sadece ham rakamlar veya kod satırları olarak görülmemiş, veri setine bir iktisatçı ve stratejist gözüyle yaklaşılmıştır. Python ve veri analiz araçları, makroekonomik teorileri canlı bir pazar üzerinde test etmek için birer kaldıraç olarak kullanılmıştır.

Projenin teknik omurgasında ilk olarak veri temizleme ve yerlileştirme adımları uygulanmış, bölge adları analiz sürecini optimize etmek adına özelleştirilmiştir. Zaman serisi mühendisliği (Feature Engineering) yapılarak ham kargo tarihleri anlamlı aylık periyotlara dönüştürülmüş ve bu sayede pazardaki dönemsel dalgalanmalar ile tüketici sabrı görünür kılınmıştır. Analiz sürecinde; her bölgenin müşteri sayısı, toplam satış hacmi, kargo tercihleri ve veri setinde zaten hazır bulunan 3 ana kategori (Ofis Malzemeleri, Mobilya, Teknoloji) üzerinden tüketici davranışları ve standart sapma yapıları bütünsel olarak incelenmiştir.

🏙️ Kıyı Devlerinin Senkronizasyonu ve İstatistiki İstikrar: Doğu ve Batı Bölgeleri
Analiz sonuçlarında, Amerika'nın iki ucunu temsil eden Doğu ve Batı bölgelerinin; müşteri sayısı, toplam satış miktarı ve harcama iştahı bakımından ülkenin lokomotifi olan, doymak bilmez iki homojen dev pazar olduğu tescillenmiştir. İki bölge de ürün sepeti dağılımları ve harcama refleksleri bakımından adeta ikiz birer pazar gibi hareket etmektedir. İki bölgede de Ofis Malzemeleri toplam satış sayısında zirvede yer alırken, onları sırasıyla Mobilya ve Teknoloji kategorileri takip etmektedir. Batı bölgesi müşteri hacmi ve toplam satış sayısında Amerika'nın açık ara lider pazarı olarak öne çıkarken, Doğu bölgesi de her kategoride onu hemen arkasından takip ederek bu elit lige ortak olmaktadır.

Bu iki dev pazarın en dikkat çekici istatistiksel özelliği, devasa müşteri ve satış hacimlerine rağmen standart sapma değerlerinin diğer bölgelere kıyasla çok daha az dalgalanması ve stabil seyretmesidir. İktisadi açıdan bu durum, Doğu ve Batı kıyılarında pazarın tamamen doygunluğa ulaştığını, tüketici kitlesinin homojenleştiğini ve harcamaların belirli bir yüksek refah tabanına yayıldığını kanıtlamaktadır. Diğer bölgelerdeki sistemi sabote eden ani ve öngörülemeyen uç değer patlamaları bu kıyılarda pazarın genel dengesini bozamaz; çünkü düzenli kurumsal talep ve dengeli alım gücü, aylık fatura tutarlarını belirli bir istikrar bandında tutarak standart sapmayı baskılamaktadır.

Lojistik refleksler incelendiğinde de bu iki gelişmiş metropol pazarında tüketicilerin ezici bir çoğunlukla "Standart Sınıf" kargoyu seçtiği görülmüştür. Bu durum, yüksek alım gücüne sahip tüketicilerin bile acil olmayan normal ve sarf malzemeleri için fazladan lojistik maliyetine katlanmadığını, yani rasyonel tüketici kanunlarına pürüzsüzce uyduğunu kanıtlamaktadır. Bununla birlikte, bu iki bölgede "Aynı Gün" ve "Birinci Sınıf" gibi hızlı kargo harcamalarının toplam hacmi diğer bölgeleri katlamaktadır; çünkü buradaki elit kitle özellikle Teknoloji ve pahalı donanım siparişlerinde parayı basıp lojistiği ışık hızına çıkarma gücüne sahiptir.

🚜 Fiyat/Performans Omurgası ve Esnaf İstikrari: Merkez Bölgesi
Merkez bölgesi; kıyı metropollerinin çılgın, yüksek hacimli ve uçlarda yaşayan harcama modellerine kıyasla, kendi yağında kavrulan, ne yaptığını bilen, tam bir esnaf ve orta sınıf ticari omurgasını temsil etmektedir. Müşteri sayısı ve toplam satış miktarı kıyılara göre daha geride gelse de, kendi içinde son derece dengeli bir havuz oluşturmaktadır. Kategorik dağılımda Ofis Malzemeleri yine liderliği korurken, Mobilya ve Teknoloji sipariş adetleri son derece sakin bir şekilde aşağı inmektedir. Merkez bölgesinin satış genelindeki o sinsi 9 aylık istikrarının sırrı ve düşük, stabil standart sapma değerleri de bu analizle deşifre edilmiştir: Bölge pazarı, fiyatı ve dalgalanması düşük olan standart Ofis Malzemeleri tüketimiyle ayakta kalmakta, faturalarda ani sıçramalar yaratmayarak bütçesini sinsi bir istikrar içinde yönetmektedir.

Bölgenin bu dengeli cüzdan stratejisi ve öngörülebilir standart sapma yapısı, lojistik tercihlerinde de kendini açıkça belli etmektedir. Merkez bölgesindeki tüketiciler, hızlı kargoların getirdiği fuzuli maliyetlerden agresif bir şekilde kaçınırken, işlerini tamamen şansa bırakıp Standart Sınıfın esnek süresine de yayılmak istememektedir. Bunun yerine, tam bir fiyat-performans (F/P) canavarı gibi hareket ederek hem bütçeyi koruyan hem de teslimat gününü garanti altına alan "İkinci Sınıf" kargo türüne ciddi bir ağırlık vermişlerdir. Bu durum, Merkez halkının rasyonel ve hesaplı alışveriş karakterinin en net lojistik kanıtıdır.

⚖️ Uçurumlar ve Sinsi Outlier Bombaları: Güney Bölgesi
Projenin istatistiksel ve sosyo-ekonomik olarak en çarpıcı bombası, Güney bölgesinin analiz edilmesiyle patlamıştır. Güney genelinde müşteri sayısı ve toplam satış miktarı yerlerde sürünmekte; Ofis Malzemeleri, Mobilya ve Teknoloji kategorilerinin tamamında talep diğer bölgelerin fersah fersah gerisinde kalarak oldukça cılız bir pazar tablosu çizmektedir. Toplam sipariş frekansı ve hacmi bu kadar cılız, pazar yapısı bu kadar durgun olan bir bölgede, standart sapmanın ortalamayı katlayarak havaya uçması ilk başta büyük bir matematiksel çelişki olarak görünmüştür. Ancak verinin iliği söküldüğünde, bu deli saçması dalgalanmanın ve arşa çıkan standart sapmanın arkasındaki o acımasız "Gelir Adaletsizliği" modeli bilgisayar başından çırılçıplak yakalanmıştır.

İstatistiksel olarak standart sapmanın bu kadar yüksek olması, Güney pazarında orta sınıfın neredeyse yok denecek kadar az olduğunu ve toplumun iki uç kutba bölündüğünü matematiksel olarak ispatlar. Doğu ve Batı'nın o stabil ve az dalgalı yapısının aksine, Güney'de geniş ve bütçesiz halk kitlesi sadece hayatta kalacak kadar ucuz sarf malzemesi tüketip mecburen en ucuz Standart Kargonun günlerce gelmesini beklemektedir (bu da tabandaki cılız yoğunluğu yaratmaktadır). Madalyonun diğer yüzünde ise, araya giren sinsi ve ultra zengin bir azınlık, nadiren de olsa tek kalemde devasa lüks harcamalar yapmaktadır. Bu elit azınlığın, Güney gibi altyapısı zayıf bir bölgede bile paraya acımadan "Birinci Sınıf" hızlı kargoyu seçmesi ve az sayıdaki lüks Teknoloji/Mobilya kategorisinden devasa ciro patlamaları yaratması, standart sapmayı havaya uçuran o meşhur "outlier" (uç değer) gerçeğinin ta kendisidir.

👥 Bölgesel Kişisel Ekonomik Refah Değerlendirmesi
Veri setindeki tüketim alışkanlıkları ve lojistik tercihler, Amerika genelindeki bireylerin kişisel ekonomik refahları ve alım güçleri hakkında çok net bir toplumsal harita sunmaktadır:

Doğu ve Batı (Yüksek ve Eşit Refah): Bu iki bölgede yaşayan insanların kişisel ekonomik refahı sadece yüksek değil, aynı zamanda toplumun geneline homojen bir şekilde yayılmıştır. Bireyler hem temel ihtiyaçlarını rahatça karşılayabilmekte hem de teknoloji ve mobilya gibi yüksek bütçeli lüks tüketim mallarına kişisel bütçelerinden ciddi pay ayırabilmektedir. Kargo tercihlerindeki esneklik, bu bölgelerdeki insanların günlük hayatta finansal bir sıkışmışlık yaşamadıklarını ve acil durumlarda parayı ikinci plana iterek "hız ve konfor" satın alabildiklerini göstermektedir.

Merkez (Temkinli ve İstikrarlı Orta Sınıf): Merkez bölgesindeki bireysel refah, uç noktalardan uzak, dengeli bir orta sınıf yaşam standardına işaret etmektedir. İnsanların alım gücü hayatta kalma sınırının çok üzerinde olsa da, kıyılardaki gibi agresif bir tüketim çılgınlığına dönüşmemektedir. Bireyler harcamalarında son derece rasyonel, planlı ve temkinlidir. Lojistikte bile fiyat/performans kovalamaları, bu bölgedeki insanların kişisel bütçelerini kuruşu kuruşuna hesaplayan, geleceğe yönelik ekonomik kaygıları veya tasarruf eğilimleri daha yüksek olan öngörülebilir bir kitle olduğunu kanıtlamaktadır.

Güney (Kutupsal Refah ve Gelir Uçurumu): Kişisel refah seviyesinin en sorunlu ve dengesiz olduğu yer açık ara Güney bölgesidir. Burada ortalama bir vatandaşın alım gücü ve kişisel refahı diğer bölgelerin fersah fersah gerisindedir; halkın ezici çoğunluğu sadece en temel sarf malzemelerini tüketebilen ve bütçe yetersizliğinden dolayı en yavaş lojistik hizmete mahkum olan düşük gelir grubundadır. Ancak aynı coğrafyada, bu geniş kitleyle tamamen zıt kutupta yaşayan, lojistikte paraya acımayan ve tek kalemde devasa lüks harcamalar yapabilen ultra yüksek refah sahibi sinsi bir azınlık bulunmaktadır. Güney, kişisel ekonomik refahın tabana yayılamadığı, sınıfsal uçurumun en derin hissedildiği bölgedir.

#Projeyi İndirmek İçin:

Bash

#1. Projeyi Klonlayın
Öncelikle bu depoyu yerel makinenize çekin:

git clone https://github.com/Bekdemirberat2/Supermarket-Sales-Analysis
cd Supermarket-Sales-Analysis

#2. Sanal Ortam Oluşturun ve Aktif Edin (Tavsiye Edilen)
Projelerin kütüphane bağımlılıklarının temiz kalması için bir sanal ortam oluşturun:

Bash

Windows için:
python -m venv venv
venv\Scripts\activate

macOS / Linux için:
python3 -m venv venv
source venv/bin/activate

#3. Gerekli Kütüphaneleri Yükleyin

Projede analiz, veri manipülasyonu ve görselleştirme için kullanılan tüm bağımlılıkları tek tıkla kurun:

Bash
pip install -r requirements.txt

#4. Jupyter Notebook'u Başlatın

Her şey hazır olduğunda analiz dosyasını açmak için yerel sunucuyu tetikleyin:

Bash
jupyter notebook
Açılan tarayıcı ekranından proje dosyanıza (.ipynb) tıklayarak tüm kod bloklarını sırasıyla (Shift + Enter) çalıştırabilir, makroekonomik analizlerin ve grafiklerin üretim sürecini canlı olarak gözlemleyebilirsiniz.


