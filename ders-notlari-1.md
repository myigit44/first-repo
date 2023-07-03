# COMPUTE

# EC2

Amazon Elastic Compute Cloud (Amazon EC2), bulutta güvenli, yeniden boyutlandırılabilen bilgi işlem kapasitesi sağlayan bir web hizmetidir. Geliştiriciler için web ölçeğindeki bulut bilişimi daha kolay hale getirmek için tasarlanmıştır.

Kısacası sanal makine hizmetidir.

# Lightsail

Amazon Lightsail, AWS üzerinde bir özel sanal sunucuya sahip olmanın ve yönetmenin en kolay yolu olarak tasarlanmıştır. Lightsail planları, düşük, öngörülebilir bir fiyatla projenize hızlı bir başlangıç yapmak için ihtiyacınız olan her şeyi (sanal makine, SSD tabanlı depolama, veri aktarımı, DNS yönetimi ve static IP) içerir.

Lightsail aslında önceki hosting firmaları gibi sanal makineleri, içlerinde belli ram,cpu,hdd,static ip gibi paketleri olan ve içlerinden işimize yarayıp direk sanal makine yaratabildiğimiz bir servistir.

# ECS - Elastic Container Service

Amazon ECS, Docker konteynerlerini destekleyen ve AWS'de konteyner uygulamalarını kolayca çalıştırmanıza ve ölçeklendirmenize izin veren yüksek oranda ölçeklenebilir, yüksek performanslı bir konteyner düzenleme hizmetidir. Amazon ECS, kendi konteyner düzenleme yazılımınızı kurmanız ve çalıştırmanız, bir sanal makine kümesini yönetmeniz ve ölçeklendirmeniz veya bu sanal makinelerdeki konteynerları programlamanız gereğini ortadan kaldırır.

ECS servisi de docker konteynerlarını production ortamında yönetmenizi sağlayan AWS servisidir. AWS'in konteyner orcestration servisi.

# EKS - Elastic Kubernetes Service

Kubernetes için Amazon Elastic Container Service (Amazon EKS), AWS'de Kubernetes kullanarak konteynerli uygulamaların dağıtımını, yönetilmesini ve ölçeklendirilmesini kolaylaştırır.

ECS'in Kubernetes üzerinde koşan çeşididir.

# AWS Lambda

AWS Lambda, sunucu yönetme zahmetine girmeden kod çalıştırmanıza izin verir. Yalnızca tükettiğiniz hesaplama zamanı için ödeme yaparsınız - kodunuz çalışmadığında ücret alınmaz. Lambda ile, hemen hemen her türlü uygulama veya arka uç hizmeti için kod çalıştırabilirsiniz. Sadece kodunuzu yükleyin ve Lambda, yüksek kullanılabilirlikle kodunuzu çalıştırmak ve ölçeklendirmek için gereken her şeyi halleder. Kodunuzu diğer AWS hizmetlerinden otomatik olarak tetiklemek veya doğrudan herhangi bir web veya mobil uygulamadan çağırmak için ayarlayabilirsiniz.

Kod çalıştırmak için sunucuya ihtiyaç duymadan (serverless) sadece yazdığın kodu yazıp sonucunu aldığın bir servistir.

# AWS Batch

AWS Batch, geliştiricilerin, bilim adamlarının ve mühendislerin AWS'de yüzbinlerce bilgisayar işlemlerini kolayca ve verimli bir şekilde çalıştırmasını sağlar. AWS Batch, sunulan toplu işlerin hacmine ve özel kaynak gereksinimlerine bağlı olarak hesaplama kaylaklarının (CPU veya bellek için optimize edilmiş sanal makineler) en uygun miktarını ve türünü dinamik olarak belirler.


Diyelim ki her ay sonu yazılımcıların yapması gereken rutin bir işlem var ve bu işlem için bir kaç makine ayağa kaldırılarak ilgili görevleri tamamlayıp daha sonra makineleri kapatıyor. Verilen görevi otomatize etmemize yarayan bir servistir. 

# AWS Elastic Beanstalk

AWS Elastic Beanstalk, Apache, Nginx, Passenger ve IIS gibi bilinen sunucularda Java, .NEt, PHP, Node.js, Python, Ruby, Go ve Docker ile geliştirilen web uygulamarını ve servislerini dağıtmak ve ölçeklendirmek için kullanımı kolay bir hizmettir. Konuduzu kolayca yükleyebilir ve Elastic Beanstalk, kapasite sağlamasından, yük dengelemesinden, otomatik ölçeklemeden uygulama sağlığını izlemeye otomatik olarak gerçekleştirir. Aynı zamanda, uygulamanızı güçlendiren AWS kaynakları üzerinde tam kontrol sahibi olursunuz ve her zaman temel aynaklara erişebilirsiniz.

AWS'nin bir PAAS servisidir. Bu serverless'dan bir önceki aşamadır.  Kodunuzu yazıp, servisi ortaya çıkartıyorsunuz. 
Ama bu servisi bir sunucuya yükleme işlemini ve sunucu yönetme işini AWS hallediyor. Kısaca uygulamanızı çalıştırmanız için size bir platform sağlıyor. 

# STORAGE

# S3 - Simple Storage Service

Amazon S3 web siteleri ve mobil uygulamalar, kurumsal uygulamalar ve IoT sernsörler veya cihazlarından gelmesi farketmeksizin herhangi bir ortamdan gelen herhangi bir miktardaki veriyi depolamak ve almak için oluşturulmuş bir nesne deposudur. %99.99999999 dayanıklılık-sağlamlık sağlamak için tasarlanmıştır ve bulundukları sektörün pazar lideri firmaları tarafından kullanılan milyonlarca uygulama için veri depolar. S3, en sıkı regülasyon gereksinimlerini bile karşılayan kapsamlı güvenlik ve uyumluluk özellikleri sunar.

Obje tabanlı bir depolama hizmetidir.  * Blok tabanlı depolama alanları da vardır. 0 Byte'dan 5 TB'a kadar olan dosyaları S3'de tutabiliriz. 5TB sınırı tek bir dosyanın maksimum büyüklüğünü ifade eder. Buraya koyabileceğimiz dosya adet sınırı yoktur. 

# EFS - Elastic File System

EFS AWS bulut hizmetleri ve şirket içi kaynaklara kullanım için basir, ölçeklenebilir, elastik dosya depolama alanı sağlar. Kullanımı kolaydır ve dosya sistemlerini ve hızlı kolay bir şekilde oluşturmanızı ve yapılandırmanızı sağlayan basit bir arayüzü vardır. Amazon EFS, uygulamlara zarar vermeden, dosya ekletip kaldırırken otomatik olarak küçülüp daralırken, talep üzerine esnek bir şekidle ölçeklendirebilmek için üretilmiştir, böylece uygulamalarınız ihtiyaç duydukları anda ihtiyaç duydukları depolama alanına sahip olur. 

Örnek olarak, birden fazla sanal makineye yada kendi sunucu odandaki bir makineye bağlayabileceğin ve aynı anda birden fazla makinenin erişip okuma ve yazma işlemleri yapabileceği bir nevi esnek bir harddiskdir. 

# Amazon Glacier

Amazon Glacier, veri arşivleme ve uzun vadeli yedekleme için güvenli, dayanıklı ve son derece düşük maliyetli bir bulur depolama hizmetidir. %99.999999999 dayanıklılık sağlamak için tasarlanmıştır ve en sıkı yasal gerekliliklerin bile karşılanmasına yardımcı olabilecek kapsamlı güvenlik ve uyumluluk özellikleri sunar. 

S3'ün uzun vadeli saklanacak ve sık erişilmeyen dosyalar için olan çok ucuz versiyonu olarak düşünebiliriz. Örneğin ben sunucularımı düzenli olarak yedeklemek ve bu yedekleri 1 sene boyunca saklamak durumundayım. Bu yedeklerin içinden bir dosyaya belki 5 6 ay sonra erişmem gerekecek ve acil, hızlı erişmem gerekmiyor. Bu gibi durumlarda, uzun vadeli saklamam gereken ve hızlıca erişmem gerekmeyen verilerimi bu serviste çok ucuz bir şekilde saklayabilirim.

# AWS Storage Gateway

AWS Depolama Ağ Geçidi, kurum içi uygulamalarınızın AWS bulut depolama alanını sorunsuz bir şekilde kullanmasını sağlayan bir karma depolama hizmetidir. Servisi yedekleme ve arşivleme, felaket kurtarma, bulut veri işleme, depolama katmanları ve geçiş için kullanabiliriz. Servis, bant genişliği yönetimi, otomatik ağ esnekliği ve etkin verilerinize düşük gecikme süresi içinde kurum içi erişim için yüksek öneme sahip bir veri aktarım mekanizması içerir.

Çoğu firma hala bazı sunucularını local'de bazılarını ise bulutta tutuyorlar. Bu gibi senaryolarda yerelde tutulan sunucuları bir şekilde bulut kaynaklarına eriştirip, yedekleme yada felaketten kurtarma senaryoları gibi ihtiyaçlarda kullanıyorlar. Bu gibi senaryoların depolama ayağını bu servis sağlıyor. 

# DATABASE

# RDS - Relational Database Service (Aurora)

Amazon ilişkisel veritabanı hizmeti, buluttaki ilişkisel bir veritabanını kurmayı, çalıştırmayı ve ölçeklemeyi kolaylaştırır. Donanım sağlama, veritabanı kurulumu, yama ve yedeklemeler gibi zaman alıcı yönetim görevlerini otomatikleştirirken düşük maliyetli ve yeniden boyutlandırılabilir kapasite sağlar. Uygulamalarınıza odaklanmanızı sağlar, böylece onlara ihtiyaç duyduları hızlı performans, yüksek kullanılabilirlik, güvenlik ve uyumluluk sağlayabilirsiniz.

Kısacası Sql Server. 

# Amazon DynamoDB

Amazon DynamoDB, her ölçekte güvenilir performans sağlayan bir ilişkisel olmayan veritabanıdır. Tutarlı tek basamaklı milisaniyelik gecikme süresi sağlayan, yerleşik güvenlik, yedekleme ve geri yükleme ve bellek içi önbelleğe alma özelliği sunan çok bölgeli, çoklu yazma imkanı olan bir veritabanıdır.

İlişkisel olmayan, NoSql databse modelidir.

# Amazon ElastiCache

Amazon ElastiCache tamamen yönetilen Redis ve Memcached sunuyor. Yaygın açık kaynaklı uyumlu bellek içi veri depolarını sorunsuz bir şekilde dağıtın, çalıştırın ve ölçeklendirin. Yüksek veri hacmi ve düşük gecikmeli bellek içi veri depolarından veri alarak veri yoğunluklu uygulamalar oluşturun veya mevcut uygulamalarınızın performansını artırın. Amazon ElastiCache, Oyun, Reklam, Teknoloji, Finansal Hizmetler, Sağlık Hizmetleri ve Nesneler için popüler bir seçimdir. 

Hızlı belleklerle oluşturulan bir önbellek servisidir. Çok sık erişilen bir veriyi bu hızlı belleklere alıp her seferinde o veriyi nispeten yavaş veri tabanından çekmek yerine burdan sunmanı, dolayısıyla uygulamanı hızlandırmanı sağlar. 

# Amazon Neptune

Amazon Neptune, yüksek düzeyde bağlı veri kümeleriyle çalışan uygulamaları oluşturmayı ve çalıştırmayı kolaylaştıran hızlı, güvenilir, tam yönetimli bir grafik veritabanı hizmetidir. Amazon Neptune'ün temeli, milyarlarca ilişkiyi depolamak ve grafiği milisaniye gecikme süresiyle sorgulamak için optimize edilmiş, amaca uygun, yüksek performanslı bir grafik veritananı motorudur.

Veritabanı içerisindeki objelerin birbiri ile ilişkilerini 
verimli şekilde düzenleyen veritabanı türüne graph database denir. Neptune'de Amazon'un Graph Database hizmetidir.

# Amazon Redshift

Amazon Redshift hızlı ve ölçeklenebilir bir veri ambarı olup, veri ambarı ve veri gölündeki tüm verilerinizi analiz etmek için basit ve uygun maliyetlidir. Redshift, makine öğrenimi, büyük ölçüde paralel sorgu yürütme ve yüksek performanslı diskte sütunlu depolama kullanarak diğer veri ambarlarından on kat daha hızlı performans sunar.

Veri Ambarı : Bir veya daha fazla kaynaktan yapılandırılmış verileri bir araya getiren ve bu veriler üzerinde detaylı analizler yapabildiğimiz data saklama yapılarıdır. 

Yani bu veri ambarı çözümü ile sen bu verileri veri ambarı uygulamasına atıp bunun üstünde çeşitli sorgular çalıştırarak istediğin bazı önemli verileri elde edebiliyorsun. 

Raporlama işlemleri, yüksek boyutlu sorgular canlı bir ana veritabanını çok yoracağı ve sistemi yavaşlatacağı için veriler önce veri ambarına taşınır ve orada sorgular çalıştırılır. 

# NETWORKING & CONTENT DELİVERY

# VPC - Virtual Private Cloud

Amazon Sanal Özel Bulut, tanımladığınız bir sanal ağda AWS kaynaklarını çalıştırabileceğiniz AWS Cloud'un mantıksal olarak izole edilmiş bir bölümünü sağlar. Kendi IP adres aralığınızın seçilmesi, alt ağların oluşturulması ve rota tablolarının ve ağ geçitlerinin yapılandırılması dahil olmak üzere sanal ağ ortamınız üerinde tam denetime sahip olursunuz. Kaynaklara ve uygulamalara güvenli ve kolay erişim için VPC'inizde hem IPv4 hem de IPv6 kullanabilirsiniz.

VPC tamamen bize özel bir sanal ağdır. Bunun içerisinde; firewall, router, switch, vs gibi şeyler vardır. Alt ağlar yaratabilir, güvenliğini sağlayabiliriz. 


# Amazon Cloudfront

Amazon Cloudfront, düşük gecikme süresi ve yüksek aktarım hızları ile izleyicilere veri, video, uygulama ve API'leri güvenli bir şekilde ulaştıran bir global içerik dağıtım ağı(CDN) hizmetidir. Cloudfront, AWS küresel altyapısında doğrudan bağlı fiziksel konumların yanı sıra, uygulamarınız için kaynak olarak DDOS azaltma, Amazon S3, Elastic Load Balancing veya AWS Shield for Amazon EC2 gibi hizmetlerle entegre edilmiştir.

Amazonun CDN hizmetidir. 

# Amazon Route53

Amazon Route53, yüksek kullanılabilir ve ölçeklenebilirlik sunan bir bulut Alan Adı Sistemi(DNS) servisidir. Geliştiricilere ve işletmelere son kullanıcıların internet uygulamalarına yönlendirilmeleri için son derece güvenilir ve uygun maliyetli bir yol sunmak amacıyla tasarlanmıştır;www.example.com gibi isimleri 192.0.2.1 gibi bilgisayarların birbirleriyle bağlantı kurmak için kullandığı sayısal IP adreslerine çevirir. Amazon Route53, IPv4 ve IPv6 ile tamamen uyumludur. 

Amazon'un Dns hizmetidir. 

# API Gateway

Amazon API Gateway, geliştiricilerin herhangi bir ölçekte API oluşturmasını, yayınlamasını, sürdürmesini, izlemesini ve güvenliğini sağlamasını kolaylaştıran tamamen yönetilen bir hizmettir. AWS Yönetim Konsol'unda birkaç tıklamayla, Amazon Elastic Compute Cloud üzerinde çalışan iş yükleri, AWS Lambda üzerinde çalışan kod blokları veya herhangi bir web uygulaması gibi arka uç hizmetlerine erişmek için "ön kapı" olarak işlev gören bir API oluşturabilirsiniz.


# AWS Direct Connect

AWS Direct Connect, tesisinizden AWS'ye özel bir ağ bağlantısı kurulmasını kolaylaştıran bir bulut servis çözümüdür. AWS Direct Connect'i kullanarak AWS ile veri merkeziniz, ana ofisiniz veya diğer lokasyonlardaki ortamınız arasında, çoğu durumda ağ bant genişliği verimliliğini artırıp maliyetleri azaltan ve İnternet tabanlı bağlantılardan daha tutarlı bir ağ deneyimi sağlayabilen özel bağlantı kurabilirsiniz.

Bu hizmet sayesinde kendi firma lokasyonunuzdan AWS veri merkezine direkt dedike bir ağ hattı çekme imkanına kavuşuyoruz. 

# MİGRATİON
 
# AWS Migration Hub

AWS Migration Hub, AWS ve AWS iş ortakları tarafından sunulan migration çözümleride süreci izlemek için tek bir konum sağlar. Migration Hub'ı kullanmak, ihtiyaçlarınıza en iyi uyan AWS ve iş ortağı geçiş araçlarını seçmenizi sağlar. Migration Hub ayrıca, hangi araçların taşınmak için kullanıldığına bakılmaksızın, bireysel uuygulamalar için önemli göstergeler sağlayarak migration sürecindeki ilerlemeyi görmenize imkan tanır.

Aslında migration için gerekli araçlara bir arayüz sağlayan servistir. Bu servis sayesinde diğer uygulamalar ile yapılan işin sürecini ve sonucunu takip edebiliyoruz.

# AWS Application Discovery Service

AWS Application Discovery Service, müşterilerinin şirket içi veri merkezleri hakkında bilgi toplayarak geçiş projelerini planlamalarına yardımcı olur. Veri merkezi geçişlerini planlama, genellikle birbirine bağlı olan binlerce iş yükü içerebilir. Sunucu kullanım verileri ve bağımlılık haritalaması, migration sürecinin ilk önemli adımlarıdır. AWS Application Discovery Service, iş yüklerinizi daha iyi anlamanıza yardımcı olmak için sunucularınızdan yapılandırma, kullanım ve davranış verilerini toplar ve sunar.

Local'de bulunan sunucular ve uygulamarın buluta taşınmasın da yardımcı oluyor. Bu uygulamalar ve sunucular ile ilgili tüm detayları, birbirleriyle olan bağlantılarını anlamanıza yardımcı olup, bu bilgiler ile taşıma planınızı oluşturmanızda yardımcı oluyor. 

# AWS Database Migration Service

AWS Veritabanı Taşıma Hizmeti, veritabanlarını hızlı ve güvenli bir şekilde AWS'ye taşımanıza yardımcı olur. Kaynak veritabanı, geçiş sırasında çalışmaya devam eder ve veritabanına bağlı uygulamalarda kesinti süresini en aza indiriri. AWS Veritabanı Taşıma Hizmeti, en popüler ticari ve açık kaynak veritabanlarıyla uyumludur. Servis, Oracle'dan Oracle'a gibi homojen geçişleri desteklediği gibi aynı zamanda Oracle'dan Amazon Aurora'ya veya Microsoft SQL Server'dan MySQL'e gibi heterojen geçişleri de destekler.

Bu servis veritabanınızı Amazonun veritabanı hizmetine aktarmanıza yarar.

# AWS Server Migration Service

AWS Sunucu Taşıma Hizmeti (SMS), binlerce şirket içi iş yükünü AWS'ye taşımayı kolaylaştıran ve hızlandıran aracı olmayan bir hizmettir. AWS SMS, çalışan sunucularınızı kesintisiz olarak taşıma işlemlerini otomatikleştirmenizi, programlamanızı ve izlemenizi sağlayarak büyük ölçekli sunucu geçişlerini ölçeklendirmenizi kolaylaştırır.

# AWS Snowball

Snowball, büyük miktarda veriyi AWS bulutuna ve dışına aktarmak için tasarlanmış cihazları kullanan, petabyte ölçekli bir veri taşıma çözümüdür. Snowball kullanmak, yüksek ağ maliyetlerini, uzun aktarım süreleri ve güvenlik endişeleri dahil olmak üzere büyük ölçekli veri transferleri ile ilgili ortak zorlukları çözmenize yardımcı olmaktadır. Müşteriler bugün analitik verileri, genomik verileri, video kitaplıklarını, görüntü depolarını, yedekleri, teyp değiştirme veya uygulama taşıma projelerini taşımak için Snowball kullanıyor.

Küçük bir valiz büyüklüğünde bir cihazdır. AWS'den bu siparişi başlatarak sipariş ediyorsunuz, AWS size bu cihazı gönderiyor. İçinde ufak bir bilgisayarı olan bir disk kutusudur. AWS'ye aktarmak istediğiniz tüm verileri bu cihaza aktarıp AWS'e geri gönderiyorsunuz. İçerisindeki herşey şifrelenmiş durumda oluyor. AWS içindeki tüm veriyi şifrelenmiş şekilde istediğiniz servise yüklüyor, böylelikle tüm datanızı buluta taşımış oluyorsunuz. 


# MANAGEMENT TOOLS

# CloudWatch 

Amazon CloudWatch, geliştiriciler, sistem operatörleri ve BT yöneticileri için geliştirilmiş bir izleme ve yönetim hizmetidir. CloudWatch, uygulamalarınızdan ve sistem kaynaklarınızdan işlem yapılabilir bilgiler sağlar, sistem çapında performans değişikliklerini anlar ve bunlara yanıt verir, kaynak kullanımını optimize eder ve operasyonel sağlığın birleşik bir görünümünü sunar.

Yani bir nevi monitoring işlevini yapar. Örneğin, sunucunun işlemcisi %80'i aştığında ve 5 dakika boyunca boyle devam ederse sunucu işlemcisini arttır veya ekstra bir sunucu kur gibi ayarlamalar yapılabilir.

# CloudTrail

AWS CloudTrail, AWS hesabınızın yönetişim, uyumluluk, operasyonel denetim ve risk denetimini sağlayan bir hizmettir. CloudTrail ile AWS altyapınızı kaydedebilir, sürekli izleyebilir ve koruyabilirsiniz. CloudTrail AWS Yönetim Konsolu, AWS SDK, komut satırı araçları ve diğer AWS hizmetleri de dahil olmak üzere AWS hesap etkinliğinizin etkinlik geçmişini sağlar. Bu olay geçmişi, güvenlik analizi, kaynak değişikliği izleme ve sorun giderme işlemlerini basitleştirir.

Örneğin AWS yönetiminde bulunan 40 farklı çalışanımız ve bunlara ait hesaplar var. Ve bu kişiler sanal makine vs kurup silme işlemleri yapabiliyor. Eğer bu servisi aktif edersek, kim ne zaman sunucu açtı veya sildi gibi işlemleri görüntüleyebileceğiz.

# CloudFormation

AWS CloudFormation, bulut ortamınızdaki tüm altyapı kaynakları için ortak bir dil sağlar. CloudFormation, tüm coğrafyalarda ve hesaplarda otomatik ve güvenli bir şekilde modellemek ve devreye almak için basit bir metin dosyası kullanmanıza izin verir. Bu dosya bulut ortamınız için tek bir gerçek kaynak olarak hizmet vermektedir.

Örneğin, benim bir uygulamam var, bunu oluşturmak için 4 backend sunucu, 2 frontend sunucu, 2 de database sunucu kuruyorum. Sonra bunlardaki yük dağıtımını sağlamak adına loadbalancer servisi ile haşır neşir oluyorum. Bunun yanında buradaki dosyaları saklamak adına S3 servisinde bir şeyler oluşturuyorum. Bunların izlenmesi için CloudWatch ayarları yapıyorum. Buna benzer bir çok işlem yapıyorum. Ve bu işlemlerin tümünü bir sefer değil de haftada 5-10 defa yapmam gerekiyorsa bu yaptığım tüm işlemleri otomatize etmemize yarayan servis CloudFormation'dur.

