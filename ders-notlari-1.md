#CloudWatch 

Amazon CloudWatch, geliştiriciler, sistem operatörleri ve BT yöneticileri için geliştirilmiş bir izleme ve yönetim hizmetidir. CloudWatch, uygulamalarınızdan ve sistem kaynaklarınızdan işlem yapılabilir bilgiler sağlar, sistem çapında performans değişikliklerini anlar ve bunlara yanıt verir, kaynak kullanımını optimize eder ve operasyonel sağlığın birleşik bir görünümünü sunar.

Yani bir nevi monitoring işlevini yapar. Örneğin, sunucunun işlemcisi %80'i aştığında ve 5 dakika boyunca boyle devam ederse sunucu işlemcisini arttır veya ekstra bir sunucu kur gibi ayarlamalar yapılabilir.

#CloudTrail

AWS CloudTrail, AWS hesabınızın yönetişim, uyumluluk, operasyonel denetim ve risk denetimini sağlayan bir hizmettir. CloudTrail ile AWS altyapınızı kaydedebilir, sürekli izleyebilir ve koruyabilirsiniz. CloudTrail AWS Yönetim Konsolu, AWS SDK, komut satırı araçları ve diğer AWS hizmetleri de dahil olmak üzere AWS hesap etkinliğinizin etkinlik geçmişini sağlar. Bu olay geçmişi, güvenlik analizi, kaynak değişikliği izleme ve sorun giderme işlemlerini basitleştirir.

Örneğin AWS yönetiminde bulunan 40 farklı çalışanımız ve bunlara ait hesaplar var. Ve bu kişiler sanal makine vs kurup silme işlemleri yapabiliyor. Eğer bu servisi aktif edersek, kim ne zaman sunucu açtı veya sildi gibi işlemleri görüntüleyebileceğiz.

#CloudFormation

AWS CloudFormation, bulut ortamınızdaki tüm altyapı kaynakları için ortak bir dil sağlar. CloudFormation, tüm coğrafyalarda ve hesaplarda otomatik ve güvenli bir şekilde modellemek ve devreye almak için basit bir metin dosyası kullanmanıza izin verir. Bu dosya bulut ortamınız için tek bir gerçek kaynak olarak hizmet vermektedir.

Örneğin, benim bir uygulamam var, bunu oluşturmak için 4 backend sunucu, 2 frontend sunucu, 2 de database sunucu kuruyorum. Sonra bunlardaki yük dağıtımını sağlamak adına loadbalancer servisi ile haşır neşir oluyorum. Bunun yanında buradaki dosyaları saklamak adına S3 servisinde bir şeyler oluşturuyorum. Bunların izlenmesi için CloudWatch ayarları yapıyorum. Buna benzer bir çok işlem yapıyorum. Ve bu işlemlerin tümünü bir sefer değil de haftada 5-10 defa yapmam gerekiyorsa bu yaptığım tüm işlemleri otomatize etmemize yarayan servis CloudFormation'dur.