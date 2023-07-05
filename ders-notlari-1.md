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

# AWS Autoscaling 

AWS AutoScaling, uygulamalarınızı izler ve mümkün olan en düşük maliyetle sabit, öngörülebilir bir performans sağlamak için otomatik olarak ayarlar. AWS Auto Scaling’I kulanarak, birkaç serviste birden fazla kaynak için uygulama ölçeklemesini dakikalar içinde kurmanız kolaydır. Amazon EC2 instances ve Spot instances, Amazon ECS görevleri, Amazon DynamoDB tabloları ve dizinleri ve Amazon Aurora Replicationlarını otomatik ölçeklendirmenizi sağlar. AWS Auto Scaling ölçeklemeyi, performansı, maliyetleri veya aralarındaki dengeyi optimize etmenizi sağlayan önerilerle işinizi kolaylaştırır. Amazon EC2 örneklerinizi dinamik olarak ölçeklendirmek için zaten Amazon EC2 Otomatik Ölçekleme kullanıyorsanız, şimdi AWS Auto ile birleştirebilirsiniz. AWS Otomtik Ölçekleme ile, uygulamalarınız her zaman doğru zamanda doğru kaynaklara sahip olur. 

Örnek olarak, dakikalar içinde yeni kaynaklar ekleyip, var olan kaynakları devreden çıkartabiliyor. Ve kullandığımız kadarını ödüyoruz. Misal uygulamamızın koştugu sunucu %80’den fazla CPU tüketiyorsa, bunun hemen yanına o an ki talebi karşılamak adına otomatik bir sunucu daha ekleyip talep azaldığında eklediği sunucuyu otomatik olarak silebilme işlemini Auto Scaling servisi yapıyor.

# AWS Config

AWS Config, AWS kaynaklarınızın konfigürasyonlarını denetlemenizi ve değerlendirmenizi sağlayan bir hizmettir. Config, AWS kaynak konfigürasyonlarınızı sürekli olarak izler ve kaydeder ve istenen konfigürasyonların değerlendirmesini otomatikleştimenizi sağlar. Config ile, yapılandırmalardaki değişiklikleri ve AWS kaynakları arasındaki ilişkileri, kaynakların geçmişiyle ilgili ayrıntılı raporları gözden geçirebilir ve dahili yönergelerinizde belirtilen yapılandırmalara karşı genel uyumunuzu belirleyebilirsiniz. Bu, denetim, güvenlik analizi, değişiklik yönetimi ve operasyonel sorun giderme işlemlerini basitleştirmenizi sağlar. 

Diyelim ki, 20 tane sanal makineniz var. Bu makinelerde de diskler ve network kartları bağlı vs. Yani ortamda oluşturulmuş bir sisteminiz var. Daha bunun gibi birçok serviste birçok hizmetiniz var. Hepsi bir arada bir system oluşturdunuz. Peki bu systemin o anki durumu, o anki bir resmini çekme şansınız olsa, daha sonra bunun üzerinde yapılan her değişikliği görme imkanınız olsa hoş olmaz mı? Buna hem değişiklik yönetimi için ihtiyacınız var hem de sorun çıktığında system konfigürasyonunda yapılan bir değişiklik mi bu sorunu tetikledi gibi cevap bulabilmek için ihtiyacınız var. Bir nevi CloudTrail ama bunun konfigürasyon için olanıdır. 



# AWS OpsWorks
AWS Opsworks, Chef ve Puppet’nın yönetilen örneklerini sağlayan bir yönetim hizmetidir. Chef ve Puppet sunucularınızın konfigürasyonlarını ayarlamanıza izin veren platformlardır. 

Altyapınızın kurulumunu, konfigürasyonlarını otomatize ederek hazırlamanızı sağlayan servistir.

AWS Service Catalog
AWS Hizmet Kataloğu, kuruluşarın AWS’de kullanım için onaylanmış BT Hizmetleri kataloglarını oluşturup yönetimlerine olanak tanır. Bu BT Hizmetleri, sanal makine görüntüleri, sunucular, yazılımlar ve veritabanlarından çok katmanlı uygulama mimarilerini tamamlamak için kullanılabilecek diğer servislere kadar her şeyi içerebilir. AWS Servis Kataloğu, BT servislerini konuşlandırmanıza ve uyumluluk gereksinimlerinize ulaşmanıza yardımcı olur.

Örneğin, şirket çalışanlarım AWS kaynaklarını kullanabilsinler ama sadece benim izin verdiğim servis ve hizmetlerden yararlanabilrsinler gibi bir ayarlama yapmak isterseniz onu bu servisle halledebiliyoruz. Çalışanlarınızın kullanabileceği hizmetlerin olduğu bir katalog yaratarak bunun içinden kolayca seçim yapmalarına imkan tanıyorsunuz.

# AWS System Manager
AWS System Manager, AWS’de altyapınızın görünürlüğünü ve kontrolünü sağlar. Systems Manager, birleşik bir kullanıcı arayüzü sağlar, böylece birden fazla AWS hizmetinden operasyonel verileri görüntüleyebilir ve AWS kaynaklarınızdaki operasyonel görevleri otomatikleştirmenizi sağlar. Systems Manager ile, Amazon EC2 örnekleri, Amazon S3 bucketları, Amazon RDS örnekleri gibi kaynakları, izleme ve sorun giderme için uygulama verilerine ve kaynak gruplarınızla harekete geçirebilirsiniz.

Bir çok sunucunuzu bir araya toplayıp tek bir ekrandan hepsine birden işletim sistemi güncellemesi geçmek gibi işlemleri bu servisle halledebiliyoruz. 






# AWS Trusted Advisor

Trusted Advisor ortamınızı optimize ederek maliyetleri azaltmanıza, performansı artırmanıza ve güvenliği artırmanıza yardımcı olacak çevrimiçi bir kaynak. Trusted Advisor, AWS’in tavsiye edilen alışkanlıklarını takip ederek kaynaklarınızı ayarlamanıza yardımcı olacak gerçek zamanlı rehberlik sağlar.

 Olması gereken ve tavsiye edilen yol (Best Practice) 
Sisteminizi tarayıp, AWS’in belirlediği best practice kriterlerine göre tavsiyelerde bulunur.

# AWS Managed Services

Tüm altyapı yönetimini outsource etmen için kullanabileceğin güvenilir ve sertifikalı partnerlere bu Managed Services üzerinden ulaşabileceğimiz bir sekmedir.

# SECURİTY

# AWS IAM - Identity and Access Management

AWS IAM, AWS servislerine ve kaynaklarına erişimi güvenli bir şekilde yönetmenizi sağlar. IAM'yi kullanarak AWS kullanıcılarını ve gruplarını oluşturabilir ve yönetebilir ve AWS kaynaklarına erişmelerine izin vermek ve bunları reddetmek için izinleri kullanabilirsiniz.

AWS'in kalbi olan bir yönetim sistemidir. AWS'ye giriş yapan hesaplar ve grupların yetkilendirmelerini bu servis ile yapılandırabiliyoruz.

# Amazon Cognito

Amazon Cognito, kullanıcı yaratma, oturum açma ve web-mobil uygulamalarınıza erişim sağlama işini hızlı ve kolay bir şekilde yönetmenizi sağlar. Amazon Cognito, milyonlarca kullanıcıya ölçeklendiriyor ve Facebook, Google ve Amazon gibi sosyal kimlik sağlayıcılarıyla ve SAML 2.0 üzerinden kurumsal kimlik sağlayıcılarıyla oturum açmayı destekliyor.

AWS üzerinde çalışan bir mobil uygulama yazdığımızı düşünelim. Uygulamalarda kullanıcı bilgileri ile kayıt olmayı, facebook, gmail gibi hesaplarla kayıt olmayı sağlayan bir servistir.

# AWS Secrets Manager

AWS Secrets Manager, uygulamalarınıza, hizmetlerine ve BT kaynaklarınıza erişmek için gereken anahtarları korumanıza yardımcı olur. Hizmet, yaşam döngüsü boyunca veritabanı kimlik bilgilerini, API anahtarlarını ve diğer anahtarları kolayca döndürmenizi, yönetmenizi ve almanızı sağlar. Kullanıcılar ve uygulamalar, Secrets Manager API'lerine yapılan bir çağrıyla anahtarlara erişebilir ve bu da bu anahtarları uygulama içinde düz metin halinde saklayarak hassas bilgileri sabitleme ihtiyacını ortadan kaldırır.

Şifreler ve şifre benzeri anahtarların güvenliğini sağlamak için kullanılır. 

# Amazon GuardDuty

Amazon GuardDuty, AWS hesaplarınızı ve iş yüklerinizi korumanıza yardımcı olmak için kötü amaçlı veya yetkisiz davranışları sürekli olarak izleyen bir tehdit algılama hizmetidir. Olağan dışı API çağrıları veya olası hesap uzlaşmalarını belirten potansiyel olarak yetkisiz dağıtımlar gibi etkinlikleri izler. GuardDuty ayrıca, potansiyel olarak tehlike altındaki örnekleri veya saldırganların keşiflerini de tespit eder.

AWS kaynaklarınızı sürekli izleyerek olağan dışı ve tanımlı güvenlik ihlallerini size bildiren servistir. 

# Amazon Inspector

Amazon Inspector, AWS'de konuşlandırılan uygulamaların güvenliğini ve uyumluluğunu geliştirmeye yardımcı olan otomatik bir güvenlik değerlendirme hizmetidir. Amazon Inspector, güvenlik açıklarını veya en iyi uygulamalardan sapmaları otomatik olarak değerlendirir. Bir değerlendirmeyi yaptıktan sonra, Amazon Inspector, şiddet düzeyine göre önceliklendirilen ayrıntılı güvenlik bulguları listesi üretir. Bu bulgular, doğrudan veya Amazon Inspector konsolu veya API aracılığıyla sunulan ayrıntılı değerlendirme raporlarının bir parçası olarak incelenebilir.

Türkçe anlamı müfettiştir. AWS'de barındırdığımız uygulamaların taranmasını ve olası güvenlik açıklarını tespit etme imkanı sağlayan servistir.

# Amazon Macie

Amazon Macie, AWS'de hassas verileri otomatik olarak bulmak, sınıflandırmak ve korumak için makine öğrenimini kullanan bir güvenlik hizmetidir. Amazon Macie, kişisel olarak tanımlanabilir bilgiler (PII) veya fikri mülkiyet gibi hassas verileri tanır ve size bu verilere nasıl erişildiğini veya taşındığını görünürlük sağlayan gösterge panoları ve uyarılar sağlar. Tam yönetilen hizmet, anomaliler için veri erişim etkinliğini sürekli olarak izler ve yetkisiz erişim veya istenmeyen veri sızıntıları riskini algıladığında ayrıntılı uyarılar üretir.

Macie ile S3 servisinde herhangi bir hassas veri atılıp atılmadığını gözlemlemenizi sağlar. Sürekli S3'ü tarar ve örneğin kredi kartı bilgisinin şifrelenmemiş  bir şekilde bu serviste saklanıp saklanmadığını size bildirir.

# AWS Single Sign-On 

AWS Single Sign ON(SSO) çoklu AWS hesaplarına SSO erişimini merkezi olarak yönetmeyi kolaylaştıran bir bulut SSO hizmetidir. Kullanıcıların mevcut kurumsal kimlik bilgileriyle bir kullanıcı portalında oturum açmalarını ve atanmış tüm hesap ve uygulamalarına tek bir yerden erişmelerini sağlar. AWS SSO ile, AWS Kuruluşlarında merkezi olarak tüm hesaplarınıza SSO erişimini ve kullanıcı izinlerini kolayca yönetebilirsiniz.

# AWS Certificate Manager

AWS Sertifika Yöneticisi, AWS hizmetleri ve dahili bağlı kaynaklarınızla kullanım için genel vve özel Güvenli Yuva Katmanı / Aktarım Katmanı Güvenliği (SSL/TLS) sertifikalarını kolayca sağlamanıza, yönetmenize ve dağıtmanıza olanak sağlayan bir hizmettir. SSL/TLS sertifikaları, ağ iletişimini güvenceye almak ve internet ğzerşnden web sitelerinin kimliğini ve özel ağlardaki kaynakları oluşturmak için kullanılır. AWS Sertifika Yöneticisi, SSL/TLS sertifikalarının satın alınması, yüklenmesi ve yenilenmesi için zaman alıcı manuel süreci kaldırır.

AWS'im sertifika sağlayıcısıdır. 

# AWS CloudHSM - Hardware Security Module

AWS CloudHSM, AWS Cloud üzerinde kendi şifreleme anahtarlarınızı kolayca oluşturmanızı ve kullanmanızı sağlayan bulut tabanlı bir donanım güvenlik modülüdür. CloudHSM ile FIPS 140-2 Seviye 3 onaylı HSM'leri kullanarak kendi şifreleme anahtarlarını yönetebilirsiniz.

AWS dünyasına yolladığımız verileri bizden başka kimse göremesin dersek, burdaki yöntem verileri şifrelemek olacak. Bu yöntem için en kurumsal ve güvenli olanını kullanmak isterseniz  donanımsal bir HSM modülü kullanmanız gerekecek. 

# AWS Directory Service

AWS Microsoft AD olarak bilinen Microsoft Active Directory için AWS Dizin Hizmeti, dizin gerekliliğindeki iş yükleriniz ve AWS kaynaklarınızın AWS Bulutunda yönetilen Active Directory'yi kullanmasına olanak tanır. AWS Microsoft AD, Microsoft Active Directory'ye dayanmaktadır ve varolan Active Directory'nizdeki erileri bulutta senkronize etmenizi veya çoğaltmanızı gerektirmez. Standart Active Directory yönetim araçlarını kullanabilir ve Grup ilkesi ve tek oturum açma (SSO) gibi yerleşik Active Directory özelliklerinden yararlanabilirsiniz. AWS Microsoft AD ile Amazon EC2 ve Amazon RDS SQL sunucularınızı kolayca dizine katılabilir ve AWS Entreprise IT uygulamalarını Active Directory kullanıcıları ve grupları ile kullanabilirsiniz.

 Bulutta kendi Active Directory hizmetimizi kullanmayı sağlıyor. 

 # AWS WAF - Web Application Firewall

 AWS WAF, web uygulamalarınızı yaygın olarak kullanılan ve güvenliği tehlikeye sokup veya aşırı kaynak tüketen web saldırılarına karşı koruyan bir web uygulamasıdır. AWS WAF, kişiselleştirilebilir web güvenlik kurallarını iletmek için kontrol sağlar. SQL injection veya cross site scripting gibi genel saldırı kalıplarını engellemk ve uygulamanız için özel tasarlanmış kurallar oluşturmak için AWS WAF kullanabilirsiniz. 

 WAF ve Shield iki ayrı servistir. Ama içiçeler. WAF kullandığımız zaman Shield'in standart hizmetini de kullanmış oluyoruz. WAF AWS'de bulunan uygulamalarımızı SQL injection gibi temel saldırılara karşı koruyor. Shield ise ddos saldırılarına karşı koruma altına alan ddos engelleme hizmetidir. 

 # AWS Artifact

 AWS Artifact sizin için önemli olan uyumlulukla ilgili bilgiler için merkez kaynaktır. AWS'nin güvenlik ve uyumluluk raporlarına isteğe bağlı erişim sağlar.

 