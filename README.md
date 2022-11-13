# PragmaticProgrammer

- [Bölümler](#Bölümler)
    - [Bölüm 1](#Bölüm-1)
    - [Bölüm 2](#Bölüm-2)
    - [Bölüm 3](#Bölüm-3)
    - [Bölüm 4](#Bölüm-4)
    - [Bölüm 5](#Bölüm-5)
    - [Bölüm 6](#Bölüm-6)
    - [Bölüm 7](#Bölüm-7)

## Bölüm 1

* Pragmatik felsefenin en önemli noktası kariyer gelişimimizin öğrenmemizin, eğitimimizin vb. alanlarda sorumluluk almaktır.  Örneğin bir hata yaptığımızda ya da yanlış bilgi, yönlendirme yaptığımız zaman bunu üstlenmeliyiz. Projelerde hataların çıkması, testlerinin iyi yapılmaması vb. gibi sorunlarla elbette ki karşılaşacağız ancak bu sorunların çözüm aşamasında elimizden geldiğince çözmeye, projede durağanlık yaratmamaya çalışmalıyız. Bir sorunla karşılaştığımız zaman herhangi bir kişiyi, programı, yazılım dilini veya arkadaşlarımızı suçlamamamız gerekir, bu sayılanlardan herhangi birisinin oluşan sorunda rolü olabilir ancak bizim işimiz buna çözüm sunmak olmalı. İş birimine yapılan hata söylendiği zaman ise bunun workaround bir çözümü var mı veya söyleyeceğimiz sebep mantıklı mı değil mi öncesinde tartılıp düşünülmeli. Tarafımıza bir soru geldiğinde veya bir konu hakkında bilmiyorum değil de bunun yerine araştıracağım, bilgi sahibi olacağım bu konuda gibisinden cevaplar her iki taraf için de daha tatmin edici bir cevap olacaktır. 
* En önemli unsurlardan birisi ise takım arkadaşlarımız ile aramızdaki güvendir. Takım arkadaşlarımıza güvenerek veya onlara güven vererek çok daha işbirlikçi, yaratıcı veya işi huzurla yapabiliriz. 
* Kod tarafında gördüğümüz bozuk bir süreç, bozuk bir kod parçacığı veya iyileştirilebilir bir yer gördüğümüz zaman orayı düzeltmek için aksiyon almaktan kaçmamalıyız çünkü bozuk bir yapıdan herkes uzaklaşacaktır ve kimsenin içinden orayı düzeltmek gelmeyecektir, ihmal ettikçe o proje çürümeye devam edecektir ancak bu durumun üstesinden gelebildiğimiz göstermek için düzeltmeye yönelik aksiyonlar almamız gerekiyor.
* Bilgi portföyümüzü sürekli olarak güncel tutmamız gerekiyor, değişen teknolojiye ayak uydurmalıyız aksi taktirde sektörden uzaklaşma, bildiğin bilginin değersizleşmesi vb. durumlar ile karşılaşabiliriz. Portföyümüzü güncel tutmak için ise bunu bir alışkanlık haline getirmeliyiz, sürekli olarak küçük de olsa yeni bilgiler ile kendimizi beslemeliyiz. Portföyümüze yeni bir bilgi eklemeden önce okuduğumuz veya duyduklarımız hakkında eleştirel düşünmeliyiz ve bununla ilgili araştırma yaparak, soruşturarak doğru bilgiye ulaşmaya özen göstermeliyiz.
* Bir iletişim kurmak istediğimiz zaman karşı tarafın ihtiyaçlarını, ilgi alanlarını veya yeteneklerini bilerek iletişim kurmalıyız. İletişim kurarken hedef kitlemiz hakkındaki bilgilerimizi sürekli olarak güncel tutmalıyız. Karşı tarafa aktaracağımız konunun ihtiyaçlarını gidermesi gerekiyor, bu konuşma için de uygun zamanı bularak, karşı tarafın önceliklerine göre yapmalıyız. Konuyu aktarırken stilimizi hedef kitlesine göre belirlemeliyiz. Fikirlerimizi hedef kitlesine iletmek için stiline ve düzenine dikkat ederek iletmeliyiz. Bir üretim aşamasında karşı taraftan geri bildirim alarak ilerlemek daha iyi bir ürün çıkarmamıza yardımcı olacaktır. İletişim kurarken dinleyici olmamız gerekir, karşı tarafa sorular yönelterek onları da konuşmaya dahil etmemiz gerekir. Tarafımıza bir soru yöneldiğinde veya üzerimizde herhangi bir mail olduğu zaman onlara dönüş yapmamız gerekiyor aksi taktirde karşı taraf o konuyla ilgilenilmediğini veya konunun ortada kaldığını düşünecektir. Yapılan proje için belge tutarak ilerlemeliyiz yani bir dokümantasyon olursa sonrası için de işlerimizi kolaylaştıracaktır. 


## Bölüm 2

* Bir ürün onu kullanan insanlara uyum sağlayabiliyorsa bu iyi tasarlanmış demektir, örneğin iyi tasarlanmış bir ürün kullanıcının ihtiyaçlarına göre değişim yapılabilmelidir. Programdaki isimlendirmelerin iyi olması kodun okunmasını ve değiştirilmesini kolaylaştırır, yazdıklarımızın değiştirilebilir halde olmasına özen göstermeliyiz. Kod tarafında önemli yerlere not düştüğümüzde zaman geçse bile dönüp baktığımızda kolayca anlayabilmeliyiz. 
* DRY ilkesine uygun bir kodda bir yerde değişiklik yaptığımız zaman birden çok yere dokunmamalıyız ve farklı şekillerde olmamalıdır. Kod tarafındaki yorumlarımızda stabil kelimeler veya cümleler kullanmamalıyız, çünkü bunlar değiştiği zaman yorumu da güncellememiz gerekecektir. 
* Birinde yapılan değişiklik diğerini etkilemiyorsa bu iki şey ortogonaldir. İyi tasarlanmış bir sistemde, database kodları ve arayüz kodları ortogonal olacaktır, yani birbirlerini etkilemeyeceklerdir. Ortogonal olmayan sistemler daha komplekstir, kontrol etmesi ve değiştirilmesi daha zordur. Birbirinden bağımsız bileşenler yazdığımız zaman birini değiştirirken diğer yerlerde değişiklik yapmamıza gerek kalmadığı için bu yapıda birindeki hata diğerini etkilemeyecektir, hem geliştirme süresi azalacaktır hem de test süresi kısalacaktır. 
* Katmanlı yaklaşım, ortogonal sistemler tasarlamanın güçlü bir yoludur. Bu yaklaşım sayesinde kodu etkilemeden temeldeki uygulamaları değiştirebiliriz. 
* Her kod parçacığı yazıldığı zaman uygulamanın ortogonalliğini azaltma riski ile karşılaşırız. Ortogonalliği korumak için kodumuzu ayrı tutarak yani diğer modüllere bir şey göstermeyerek veya diğer modüllerin uygulamalarına dayanmayacak şekilde yazılması gerekiyor, grobel verilerden kaçmamız gerekiyor çünkü bu verileri paylaşan diğer bileşenlere bağlı oluyoruz, benzer işlevlerden kaçınmamız gerekiyor, tekrarlı bir kod kullanmamalıyız.
* Ortogonal olarak tasarlanmış ve uygulamış bir sitemin, sistem bileşenleri arasındaki etkileşimler sınırlandırılmış olduğundan sistem testinin çoğu bireysel modül düzeyinde gerçekleştirilebilir.   
* Ortogonallik DRY ilkesi ile yakından ilişkilidir, DRY ile bir sistemdeki tekrarı en aza indirgemeyi amaçlarken dikeylik ile sistem bileşenleri arasındaki karşılıklı bağımlılık azalır. Dikeylik ilkesini DRY ilkesi ile birleştirerek kullanım sağlarsak geliştirdiğimiz sistemlerin daha esnek, daha anlaşılır ve hata ayıklama, test etme ve bakımının daha kolay olduğunu göreceğiz. 
* Proje her an değişime ayak uydurabilecek şekilde yazılmalıdır ve ona göre tasarlanmalıdır. Örneğin MSSQL veritabanında MySQL veritabanına geçiş yapabilecek şekilde tasarlanmalıdır. 
* Daha öncesinde hiç olmayan bir projede çalışıyorsak bunun örneği olmadığı için aslında bir mermi benzetmesi ile karanlıkta bir hedefi vurmaya çalışıyoruz. Bu durum kullanıcılar için de aynı olacaktır ve ihtiyaçları belirsiz olacaktır ancak bunlar belli olduktan sonra hızlı bir şekilde geliştirme yapmayı amaçlamalıyız. 
* Prototip oluşturma yalnızca bir kaç soruyu cevaplamak için tasarlanmıştır, üretime giren uygulamalardan çok daha ucuz ve geliştirilmesi daha hızlıdır. Prototip ile risk taşıyan her şeyi tercih edebiliriz, daha önce denenmemiş veya mevcuttaki sistem için kritik olan herhangi bir şey için tercih edebiliriz. Prototipleme bir öğrenme deneyimidir, değeri üretilen kodda değil öğrenilen derstedir, asıl amacı budur. 
* Tahmin ederken kullanılan birimlerin yorumlanırken fark yaratacaktır bu yüzden zaman terimlerini doğru kullanmamız gerekmektedir. Örneğin aşağıdaki gibi;
* Duration      Quote estimate in
    1-15 days    days
    3-8 weeks    weeks
    8-30 weeks    months
    30+ weeks    think hard before giving an estimate 
* Yapılan tahminler soruna göre değişiklik göstermektedir, bu gibi durumlarda bunu daha önceden yaşayan kişilerden destek alarak sorunun daha hızlı çözüldüğünü gözlemleyebiliriz. Tahmin yapmadan önce ne sorulduğunu anlamamız ve etki alanını kavramamız gerekiyor. Tarafımızdan tahmin istendiğinde ise sana döneceğim şeklinde cevap verebiliriz :)

## Bölüm 3

* Pragmatik programcılar için temel şey bilgidir. Gereksinimlerimizi bilgi olarak toplarız ve bunları tasarımlarımızda, uygulamalarımızda, testlerimizde ve dökümanlarımızla ifade ederiz. Bilgiyi saklamanın en iyi biçimi ise düz yazıdır. İnsan tarafından okunabilen veri biçimleri diğer veri biçimlerine göre daha uzun ömürlü olacaktır. Veri dosyalarında alan ismi verirken herkesin anlayabileceği bir şekilde yaparsak bunu okunabilirliği daha yüksek olacaktır. Düz metin kullanımı tüm tarafların ortak bir standart kullanarak iletişim kurmasını sağlar. 
* GUI ortamları tasarımcıların amaçladığı yeteneklerle sınırlıdır. Avantajı da dezavantajı da ne görüyorsak onu almamızdır. 
* Bir yerde bir düzenleme yaparken kendimizi tekrar ettiğimizi fark ettiğimiz anda daha iyi bir yolu vardır diyerek bu düşünme alışkanlığını kazanmalıyız. 
* Yazdığımız projelerde sürüm kontrolü kullanmalıyız. Bir kaç dakika önce yaptığımız değişikliğe eğer ki destekliyorsa geri alma komutu ile gidebiliriz ancak bir hafta önceki değişikliğe sürüm kontrolü kullanmadan gidemeyiz. Sürüm kontrolleri kaynak kodumuzda ve dokümantasyonumuzdaki bütün değişiklikleri takip edecektir. Sürüm kontrolleri hatayı geri almaktan çok daha fazlasını yapacaktır, örneğin bu satısı kim yazdı, bu değişiklik ne zaman yapıldı, bu sürümde kaç satır kod değiştirdik vb. 
* Hata ayıklamanın sadece problemi çözmek olduğu gerçeğini benimsemeliyiz. Başkasının hatasını bulduğumuz zaman da suçlayıcı veya elle gösterici şeklinde değil bu sorunu nasıl çözebilirize odaklanmamız gerekiyor. Hatayı bulmaya başlamadan önce uyarılar olmadan temiz bir kod üstünde çalışmalıyız aksi taktirde bilgisayarın bizim yerimize bulabileceği bir sorunu bulmaya çalışırken zaman kaybedebiliriz. Herhangi bir sorunu çözmeye çalışırken ilgili tüm verileri toplamamız gerekli.  Tesadüfler tarafından yanıltılmak kolaydır ve tesadüflerin hatalarını ayıklayarak zaman kaybetmemeliyiz. Başlangıçta bize verilen bilgiden daha fazlasını toplamak için hatayı bildiren kullanıcı ile görüşmemiz gerekebilir. Sürümler arası kontrol ile de bakacağımız alanı daraltabiliriz. En son çalışan sürüm ile hata alan şu anki sürüm arasındaki kod farklılıkları ile soruna daha da yaklaşırız. Hatayı sözlü olarak başkasına aktarırken de soruna dair yeni bir kavrayış kazanabiliriz. 

## Bölüm 4

* Pragmatik programcılar kendileri de dahil kimsenin mükemmel kod yazmadığını bilerek kendi hatalarına karşı savunma oluştururlar. 
* Bir sözleşme haklarımızı ve sorumluluklarımız aynı zamanda karşı tarafın haklarını tanımlar. Taraflardan herhangi birinin sözleşmeye uymaması durumunda ortaya çıkacak sonuçlarla ilgili bir anlaşmadır. 
* Proje başlamadan önce neleri kabul edeceğimiz konusunda katı olmalıyız ve karşılığında da mümkün olduğunda az söz vermeliyiz. Kodu yazmadan önce, giriş etki alanının ne olduğunu, sınır koşullarının neler olduğunu ve rutinin ne vaat ettiği veya neyi sağlamayı vaat ettiğini basitçe sıralamalıyız. 
* Kod tarafında sorunlar olabilir, bir ağ hatası belki de listenin boş gelmesi vb. gibi kod tarafında sorunlar yaşanabilir, bu zamanlarda switch/case’in önemini anlıyoruz, imkansızın ne zaman gerçekleşeceğini görmek için kullanmalıyız. Sorunları mümkün olan en kısa sürede tespit etmenin faydalarından biri, kodun erken çökmesidir. Kodun, imkansız olan bir şeyin gerçekleştiğini gördüğümüzde program artık geçerli değildir, ölü bir program sakat bir programdan daha az zarar verir.
* Kendimizi bu asla olamaz dediğimiz noktada bununla ilgili kod tarafına bir kontrol eklememiz gerekir. Bunu yapmanın en kolay yolu iddialardır. Assertion’lar koda yük getirecektir ancak asla olmaması gereken şeyleri kontrol ettikleri için yalnızca kod tarafında hata olduğu zaman tetiklenirler. Kod test edilip gönderildikten sonra bunlara ihtiyaç duymazlar ancak testin küçük bir olasılığının dahi yapılması olası değildir. 
* Kod tarafında kaynak kullanımında, ne tür kaynak kullanıldığının önemi olmaksızın temel kalıp bir kaynağı kim tahsis ederse onu serbest bırakmaktan yükümlü olmalıdır. 
* Pragmatik programcılar kendimiz de dahil kimseye güvenmedikleri için kaynakları uygun şekilde bırakıp bırakmadığını kontrol den bir kod oluşturmanın iyi bir fikir olduğunu savunurlar. 
* Pragmatik programcıların kesin bir kuralı vardır, devam etmeden önce her zaman küçük ve kasıtlı adımlar atın, geri bildirimi kontrol edin ve ayarlayın.

## Bölüm 5

* Eşleştirme mantığı değişimi zorlaşırır çünkü paralel olarak değişmesi gereken şeyleri birbirine bağlayacaktır, bu da değişimi zorlayacaktır. Yazılım tasarlarken yazılımın esnek olmasını isteriz ki ilerideki değişiklik ihtiyaçlarını karşılayabilsin, esnek olmak için tek tek bileşenler mümkün olduğunca az bileşen ile birleştirilmelidir. 
* Kod tarafında çok fazla '.' bulundurmamaya çalışmalıyız, bir şeye eriştiğimiz zaman bunu ara değişkenlere atarak işlem yapmalıyız. Uygulamada herhangi bir şeyin değişeceğini düşünerek geliştirme yapılmalı. 
* Pubsub asenkron olayların işlenmesi için iyi bir teknolojidir. Uygulama çalışırken mevcut kodu değiştirmeden kodun eklenmesine ve değiştirilmesine imkan verir. Dezavantajı ise çok fazla pubsub kullanılırsa sistemde neler olup bittiği gözlemlenemeyeceğidir.
* Programları girdileri çıktılara dönüştüren bir şey olarak görmeye odaklanmalıyız.
* Kalıtım bir bağlaçtır, yalnızca alt sınıf ebeveyne, ebeveyninin ebeveynine ve benzerliklerine bağlı olmakla kalmaz aynı zamanda çocuğu kullanan kod da tüm atalara bağlanır. Çoklu kalıtımı doğru bir şekilde modellemek gerekiyor, bir araba bir tür araç olabilir aynı zamanda bir tür sigortalı öğe de olabilir. Inheritance kullanmak yerine aşağıdaki üç özelliği kullanabiliriz.
    -Interfaces and protocols
    -Delegation 
    -Mixins and traits
* Class yapısını kullanmak yerine protocolü tercih etme sebemimiz ise koddaki bağımlılığı azaltmayı amaçladığımız içindir.
* Kod, uygulama yayınlandıktan sonra değişebilecek değerlere dayandığında, bu değerleri uygulamanın dışında tutmalıyız. Uygulama farklı ortamlarda ve farklı müşterilerde çalıştığında, ortama ve müşteriye özel değerleri uygulamanın dışında tutmak gerekiyor. Bu şekilde yazdığımız uygulamayı paramedik bir yapıda yazmış oluyoruz ve bu şekilde kod çalıştığı yere uyum sağlayacaktır. Paramedik olarak ekleyeceğimiz şeyler genel olarak aşağıdaki gibidir:
    -Harici hizmetler için kimlik bilgileri
    -Kayıt seviyeleri ve hedefler
    -Uygulamanın kullandığı bağlantı noktası, IP adresi, makine ve küme adları
    -Ortama özel doğrulama parametreleri
    -Vergi oranları gibi harici olarak ayarlanan parametreler
    -Siteye özel biçimlendirme ayrıntıları
    -Lisans anahtarları
    Temel olarak ana kod dışındaki değiştirebileceğimiz şeyleri paramedik olarak tanımlamamız gerekiyor.

 ## Bölüm 6
 
 * Eşzamanlılık, iki veya daha fazla kod parçasının aynı anda çalışması demektir. Paralellik, aynı anda çalıştıkları zamandır. Paralelliği sahip olmak için iki şeyi aynı anda yapamn donanıma ihtiyaç duyulmaktadır. Bu bir CPU'daki birden çok çekirdek, bir bilgisayardaki birden fazla CPU veya birbirine bağlı birden çok bilgisayar olabilir. Zamanın bizim için önemli olan iki kısmı bulunmaktadır, bunlar da eşzamanlılık ve sıralamadır. 
 * Semafor, aynı anda yalnızca bir kişinin sahip olabileceği bir şeydir. Bir semafor oluşturabilir ve ardından başka bir kaynağa erişimi kontrol etmek için kullanabiliriz. Bu yaklaşımla ilgili bazı sorunlar mevcuttur, kodda semafor kullanma geleneğini herkesin kabul etmesi nedeniyle işe yarayacaktır ancak aksi bir durumda yine sorunlar yaşanacaktır. 
 * Eşzamanlı sorunların kaynağı olarak paylaşılan belleğe çok dikkat edilmelidir ancak asıl sorunlar, uygulama kodumuzun değişebilir kaynakları paylaştığı herhangi bir yerde orata çıkabilir. 
 * Bir aktör, kendi yerel durumuna bağımsız bir sanal işlemcidir. Her oyuncunun bir posta kutusu vardır ve oyuncu boştaysa ve posta kutusunda posta varsa mesajı işler, herhangi bir iş yok ise uyku moduna geçer.
 * Bir işlem, genellikle eşzamanlılığı kolaylaştırmak için işletim sistemi tarafından uygulanan daha genel amaçlı bir sanal işlemcidir. 
 * Aktör modelinde, paylaşılan bir durum olmadığı için eşzamanlılığı incelemek için herhangi bir kod yazmaya gerek yoktur, aktörler aldıkları işi zaten biliyor olacaklardır. 
 
## Bölüm 7
  
* Bir programcı deneyim kazandıkça bunlar beynin örtük bilgi katmanlarını oluşturur. Kod yazarken yeni bir şeye başlamışken korkuyorsak veya içgüdülerimiz bizi negatifliğe itiyorsa bu daha önceki deneyimlerimizden kaynaklanıyor olabilir. Böyle bir durumda ilk olarak yaptığımız şeyi durdurup kendimize zaman ve alan tanımalıyız. 
* Tesadüfen programlamadan kaçınmalıyız, şans ve tesadüfü başarılara güvenmemeliyiz. Bir kod yazıyoruz diyelim, bilerek ve güvenerek ilerlemiyoruz, bir şey yazıyoruz ve doğru çalıştığını görüyoruz ancak aylar sonra bu uygulama çökebilir çünkü burada tesadüf kod yazmış oluyoruz, bu şekilde ilerlememeliyiz. 
* Uygulama kazaları, kodun şu anda bu şekilde yazıldığıyla için olan şeylerdir. 
* Çalışan gibi görünen aslında sorun olan şeyleri düzeltmek için risk almalıyız, sebepleri ise aşağıdaki gibidir:
 - Gerçekten çalışmıyor olabilir, çalışıyor gibi görünüyor olabilir.
 - Güvenilen sınır koşulu sadece bir kaza olabilir. Farklı durumlarda farklı davranabilir.
 - Belgelenmemiş davranış, kitaplığın sonraki sürümü ile değişebilir.
 - Ek ve gereksiz belgelenmeler kodu yavaşlatır.
 - Ek çağrılar, yeni hataların ortaya çıkma riskini arttırır.
* Kasıtlı olarak programlama yapmalıyız. Aşağıdaki maddeleri bu konuda yardımcımız olacaktır:
 - Her zaman ne yaptığınızın farkında olun.
 - Kodu, daha genç bir programcıya açıklayabiliyor olmalıyız.
 - Karanlıkta kodlama yapmamalıyız, neyin ne işe yaradığını bilerek kodlama yapmalıyız.
 - Bu plan kafamızda veya bir kağıtta olsun, planlayarak ilerlemeliyiz.
 - Yalnızca güvenilir şeylere güvenmeliyiz. Bir şeyin güvenirliğinden emin değilsek olabilecek en kötü durumu düşünmeliyiz.
 - Varsayımlarımızı belgelemeliyiz, bu şekilde hem zihnimizde netleşecektir, hem de başkalarına iletmemizde yardımcı olacaktır. 
 - Sadece kodu test etmemeliyiz, aynı zamanda varsayımlarımızı da test etmeliyiz. 
 - Çabamıza öncelik vermeliyiz, önemli yönlere zaman ayırmalıyız.
 - Mevcut kodun gelecekteki kodu engellemesine izin vermemeliyiz. 
* Bir program geliştikçe, daha önceki kararları yeniden düşünmek ve kodun bölümlerini yeniden çalışmak gerekecektir, bu süreç tamamen doğaldır. 
* Bir şeyi öğrendiğimizde eskisine göre daha iyi yorum yapabiliriz. Kod artık tam olarak uymadığında veya herhangi bir şey bize yanlış geldiğinde vb. durumlarda değiştirmekte tereddüz etmemeliyiz. Aşağıdaki durumlarda değiştirme ihtiyacı duyabiliriz.
 - DRY ilkesinin ihlal edildiğini gördüğünüzde,
 - Ortogonal olmayan tasarımı daha ortogonal yapılabilecek bir şey gördüğmüzde,
 - Bir şeyler değişir ve sorun hakkındaki bilgimiz arttığında,
 - Sistem gerçek insanlar tarafından kullanıma başlandıkça, bazı özelliklerin artık düşünülenden daha önemli olduğunu ve olması gereken özelliklerin aslında olmadığında,
 - Performansı arttırmamız gerektiğinde.
* Yazdığımız kodun iyi olup olmadığını ancak bunu test ederek anlarız. Test etmek istediğimiz şeyi anladıysak test etmeliyiz, aksi taktirde testi doğru yapıp yapamadığımızı bilemeyiz. 
* Kod tarafında güvenliği sağlamak için birkaç temel ilke vardır:
 - Bir sistemin saldırı yüzey alanı, bir saldırganın veri girebileceği, veri çıkarabileceği ve bir hizmetin yürütülmesini başlatılabileceği tüm erişim noktalarının toplamıdır. Saldırının yüzey alanını küçültmeliyiz.
 - Elimizden geldiğince en az ayrıcalıktann en kısa süre yararlanmaktır. Örneğin en yüksek izin yetkisi olan 'Yöneticiyi' otomatik olarak almamalız. Bu yüksek seviyeye ihtiyaç duyulursa hızlı bir şekilde işlemimizi yapıp gerş bırakmalıyız. 
 - Uygulamadaki kullanıcıların ayarları en güvenli ayarlar olmaldırı.
 - Kişisel olarak tanımlanabilen bilgileri, finansal bilgileri, paraloları vb. bilgileri veritabanında veya baika bir yerde düz metin olarak tutulmamalı.
 - Bilgisayar sistemlerini güncellemek gerekiyor. 
* Kod tarafında bir şeyleri adlandırırken sürekli olarak ne demek istediğimizi açıklama yollarını ararsak kodumuzu daha iyi anlamamıza yardımcı olacaktır.
 

