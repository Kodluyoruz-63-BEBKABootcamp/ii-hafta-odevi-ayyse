# Yeni bir Github repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir? 

**MIT LICENCE** 

En yaygın kullanılan lisans türlerinden biridir. MIT tarafından yayınlandığı için adı da aynı şekilde MIT olarak geçer. Çok kullanışlıdır. Yazılıma ait kaynak kodu veya derlenmiş yazılımı değiştirebilir, yayabilir ve kullanabiliriz. Ticari olarak bile kullanımında herhangi bir sorun olmaz. MIT ile lisanslanmış bir yazılım gönül rahatlığı ile kullanılabilir. 

**APACHE LICENCE** 

Apache lisansının MIT’den bir farkı yok. Sadece yazılımı dağıtırken kullanılan Apache lisanslı ürünlerin lisanslarını da dağıtıma eklemek gerekiyor. 

**GNU GENERAL PUBLIC LICENCE** 

GNU lisansı da MIT gibi aynı şekilde size yazılımın kodlarına erişim konusunda herhangi bir kısıtlama getirmez. Fakat MIT lisansına göre kullanım açısından bazı kısıtlamalar getirir. Bu kısıtlamaların en önemlisi eğer yazılımında GNU lisansına sahip bir ürün kullandıysanız ve ürünü dağıtmaya başlarsanız sizin yazılımınız da GNU lisansına sahip olmalıdır. Yani yazılımın kendi geliştirdiğiniz kısımlarının da kaynak kodlarını paylaşmak zorundasınız. Dolayısı ile kaynak kodlarını paylaştığınız bir yazılımı ticari olarak satmak zor olacaktır. 

 

# Merge - Squash - Rebase arasındaki farklar nelerdir? 

- Merge ile yapılan birleştirmede yeni bir commit yaratacak ve yeni branchteki tüm history tarafını kaybetmeden birleştirme işlemini gerçekleştirir.  

- Rebase ile birleştirirken ise branchteki commitleri tek tek alıp istenilen branch üzerine ekler. Böylelikle tek bir history oluşturur ve istenmeyen history ortadan kalkar. 

- Squash ise geçmişte atılan commitleri yeniden düzenlemek, isimlendirmek veya birleştirmek için kullanılır.  


# Agile-Scrum-Kanban kavramlarını araştırınız 

- Agile yazılım geliştirme metodlarından biridir, değişime hızlı ve etkin bir şekilde uyum sağlama yeteneği ve kapasitesidir. 

- Scrum ve kanban agile yaklaşımlardan birer tanesidir.  

  - Scrum, projeyi küçük parçalara ayırarak yönetmeyi önerir. Bu sayede her parça tek tek incelenip gerekli değişiklikler yapılabilir. Bir parçada olan sorun daha kolay bulunabilir. Scrum’a göre proje yönetilirken müşteri ile daima iletişim halinde olunması gerekir. Scrum’un projeyi küçük parçalara ayırmasındaki en temel sebeplerden birisi, müşterilerin isteklerine göre projenin şekillendirilmesini kolaylaştırmaktır. 

  - Kanban, bir süreçten geçerken işi yönetmek için malzeme hareketlerinin kontrolü amacıyla kullanılan ve çizelgelerden oluşan görsel bir sistemdir. Kanban hem süreci (iş akışı) hem de o süreçten geçen gerçek işi görselleştirir. Kanban'ın amacı, sürecinizdeki aksaklıkları tanımlamak ve bunları düzeltmektir, böylece iş en uygun hızda veya verimde gerçekleşebilir. 

# Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız. 

> 20 kişiden fazla bir ekip veya birden fazla sürüm kullanımı için gitflow kullanımı faydalıdır ancak aksi durumda faydalı olmaz. 

# Gang of Four(GOF) araştırınız. 

> Gang of Four (GOF) olarak bilinen Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides, Design Patterns — Elements of Reusable Object-Oriented Software adında kitap yayınlamışlar ve ilk kez yazılım alanında tasarım kalıpları kavramını ortaya atmışlar. Tasarım kalıpları, yazılım geliştiricilerin yazılım geliştirme sırasında karşılaştıkları genel sorunların çözümüdür. Bu çözümler, uzun bir süre boyunca sayısız yazılım geliştirici tarafından deneme yanılma yoluyla elde edilmiştir. Daha sonra belli problemler için buldukları optimum çözümlere isimler vermişlerdir. GOF, kitaplarında da 23 adet Design Patterns’i konu almıştır. 

**Tasarım Kalıpları Çeşitleri** 

*Yazılım tasarım kalıpları genel olarak 3 ana başlıkta incelenir. Bunlar şunlardır:* 

1. Creational Patterns (Yaratımsal Kalıplar): Bu tasarım deseni nesneleri doğrudan new operatörü kullanarak oluşturmak yerine nesne oluşturma mantığını gizleyerek sınıflardan nesne oluşturmaya alternatif çözümler sunar. Bu program akışında hangi nesneye ihtiyaç varsa onu oluşturmada esneklik ve kolaylık sağlar. 

2. Structural Patterns (Yapısal Kalıplar): Bu tasarım deseni nesneler arasındaki ilişkinin yapısını düzenlemek için çözümler sunar. 

3. Behavioral Patterns (Davranışsal Kalıplar): Bu tasarım deseni çalışma zamanında nesneler arasındaki davranışlar için çözümler sunar. 

 

# Interface ve Abstract sınıflar arasındaki farklar nelerdir? 

- Abstract class constructor içerebilir, interface constructor içeremez. 

- Abstract class static üyeler içerebilir, interface içeremez. 

- Abstract class farklı tiplerde access modifier içerebilir, interface içeremez. Interface’te tanımlanan her metod deafult olarak public kabul edilir. 

- Abstract class’ta is-a ilişkisi, interface’te can-do ilişkisi vardır. 

- Bir sınıf sadece bir tane abstract class inherit edebilir ama birden fazla interface inherit edebilir. 

- Abstract sınıf metod, fields, constants vb. üyeleri içerebilir, interface yalnızca metod imzalarını içerebilir. 

- Türetilen sınıflar abstract sınıfı tamamen veya kısmi implement edebilir, interface’i tamamen implement etmek zorundadır. 

- Abstract class metod imzaları veya implementasyonları içerebilir, interface yalnızca metod imzalarını içerebilir. 

 

 

 
