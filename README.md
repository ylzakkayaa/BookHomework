# PragmaticProgrammer

- [Bölümler](#Bölümler)
    - [Chapter 1](#Chapter-1)
    - [Chapter 2](#Chapter-2)
    - [Chapter 3](#Chapter-3)
    - [Chapter 4](#Chapter-4)

##Chapter 1

* Pragmatik felsefenin en önemli noktası kariyer gelişimimizin öğrenmemizin, eğitimimizin vb. alanlarda sorumluluk almaktır.  Örneğin bir hata yaptığımızda ya da yanlış bilgi, yönlendirme yaptığımız zaman bunu üstlenmeliyiz. Projelerde hataların çıkması, testlerinin iyi yapılmaması vb. gibi sorunlarla elbette ki karşılaşacağız ancak bu sorunların çözüm aşamasında elimizden geldiğince çözmeye, projede durağanlık yaratmamaya çalışmalıyız. Bir sorunla karşılaştığımız zaman herhangi bir kişiyi, programı, yazılım dilini veya arkadaşlarımızı suçlamamamız gerekir, bu sayılanlardan herhangi birisinin oluşan sorunda rolü olabilir ancak bizim işimiz buna çözüm sunmak olmalı. İş birimine yapılan hata söylendiği zaman ise bunun workaround bir çözümü var mı veya söyleyeceğimiz sebep mantıklı mı değil mi öncesinde tartılıp düşünülmeli. Tarafımıza bir soru geldiğinde veya bir konu hakkında bilmiyorum değil de bunun yerine araştıracağım, bilgi sahibi olacağım bu konuda gibisinden cevaplar her iki taraf için de daha tatmin edici bir cevap olacaktır. 
* En önemli unsurlardan birisi ise takım arkadaşlarımız ile aramızdaki güvendir. Takım arkadaşlarımıza güvenerek veya onlara güven vererek çok daha işbirlikçi, yaratıcı veya işi huzurla yapabiliriz. 
* Kod tarafında gördüğümüz bozuk bir süreç, bozuk bir kod parçacığı veya iyileştirilebilir bir yer gördüğümüz zaman orayı düzeltmek için aksiyon almaktan kaçmamalıyız çünkü bozuk bir yapıdan herkes uzaklaşacaktır ve kimsenin içinden orayı düzeltmek gelmeyecektir, ihmal ettikçe o proje çürümeye devam edecektir ancak bu durumun üstesinden gelebildiğimiz göstermek için düzeltmeye yönelik aksiyonlar almamız gerekiyor.
* Bilgi portföyümüzü sürekli olarak güncel tutmamız gerekiyor, değişen teknolojiye ayak uydurmalıyız aksi taktirde sektörden uzaklaşma, bildiğin bilginin değersizleşmesi vb. durumlar ile karşılaşabiliriz. Portföyümüzü güncel tutmak için ise bunu bir alışkanlık haline getirmeliyiz, sürekli olarak küçük de olsa yeni bilgiler ile kendimizi beslemeliyiz. Portföyümüze yeni bir bilgi eklemeden önce okuduğumuz veya duyduklarımız hakkında eleştirel düşünmeliyiz ve bununla ilgili araştırma yaparak, soruşturarak doğru bilgiye ulaşmaya özen göstermeliyiz.
* Bir iletişim kurmak istediğimiz zaman karşı tarafın ihtiyaçlarını, ilgi alanlarını veya yeteneklerini bilerek iletişim kurmalıyız. İletişim kurarken hedef kitlemiz hakkındaki bilgilerimizi sürekli olarak güncel tutmalıyız. Karşı tarafa aktaracağımız konunun ihtiyaçlarını gidermesi gerekiyor, bu konuşma için de uygun zamanı bularak, karşı tarafın önceliklerine göre yapmalıyız. Konuyu aktarırken stilimizi hedef kitlesine göre belirlemeliyiz. Fikirlerimizi hedef kitlesine iletmek için stiline ve düzenine dikkat ederek iletmeliyiz. Bir üretim aşamasında karşı taraftan geri bildirim alarak ilerlemek daha iyi bir ürün çıkarmamıza yardımcı olacaktır. İletişim kurarken dinleyici olmamız gerekir, karşı tarafa sorular yönelterek onları da konuşmaya dahil etmemiz gerekir. Tarafımıza bir soru yöneldiğinde veya üzerimizde herhangi bir mail olduğu zaman onlara dönüş yapmamız gerekiyor aksi taktirde karşı taraf o konuyla ilgilenilmediğini veya konunun ortada kaldığını düşünecektir. Yapılan proje için belge tutarak ilerlemeliyiz yani bir dokümantasyon olursa sonrası için de işlerimizi kolaylaştıracaktır. 


##Chapter 2

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

##Chapter 3

* Pragmatik programcılar için temel şey bilgidir. Gereksinimlerimizi bilgi olarak toplarız ve bunları tasarımlarımızda, uygulamalarımızda, testlerimizde ve dökümanlarımızla ifade ederiz. Bilgiyi saklamanın en iyi biçimi ise düz yazıdır. İnsan tarafından okunabilen veri biçimleri diğer veri biçimlerine göre daha uzun ömürlü olacaktır. Veri dosyalarında alan ismi verirken herkesin anlayabileceği bir şekilde yaparsak bunu okunabilirliği daha yüksek olacaktır. Düz metin kullanımı tüm tarafların ortak bir standart kullanarak iletişim kurmasını sağlar. 
* GUI ortamları tasarımcıların amaçladığı yeteneklerle sınırlıdır. Avantajı da dezavantajı da ne görüyorsak onu almamızdır. 
* Bir yerde bir düzenleme yaparken kendimizi tekrar ettiğimizi fark ettiğimiz anda daha iyi bir yolu vardır diyerek bu düşünme alışkanlığını kazanmalıyız. 
* Yazdığımız projelerde sürüm kontrolü kullanmalıyız. Bir kaç dakika önce yaptığımız değişikliğe eğer ki destekliyorsa geri alma komutu ile gidebiliriz ancak bir hafta önceki değişikliğe sürüm kontrolü kullanmadan gidemeyiz. Sürüm kontrolleri kaynak kodumuzda ve dokümantasyonumuzdaki bütün değişiklikleri takip edecektir. Sürüm kontrolleri hatayı geri almaktan çok daha fazlasını yapacaktır, örneğin bu satısı kim yazdı, bu değişiklik ne zaman yapıldı, bu sürümde kaç satır kod değiştirdik vb. 
* Hata ayıklamanın sadece problemi çözmek olduğu gerçeğini benimsemeliyiz. Başkasının hatasını bulduğumuz zaman da suçlayıcı veya elle gösterici şeklinde değil bu sorunu nasıl çözebilirize odaklanmamız gerekiyor. Hatayı bulmaya başlamadan önce uyarılar olmadan temiz bir kod üstünde çalışmalıyız aksi taktirde bilgisayarın bizim yerimize bulabileceği bir sorunu bulmaya çalışırken zaman kaybedebiliriz. Herhangi bir sorunu çözmeye çalışırken ilgili tüm verileri toplamamız gerekli.  Tesadüfler tarafından yanıltılmak kolaydır ve tesadüflerin hatalarını ayıklayarak zaman kaybetmemeliyiz. Başlangıçta bize verilen bilgiden daha fazlasını toplamak için hatayı bildiren kullanıcı ile görüşmemiz gerekebilir. Sürümler arası kontrol ile de bakacağımız alanı daraltabiliriz. En son çalışan sürüm ile hata alan şu anki sürüm arasındaki kod farklılıkları ile soruna daha da yaklaşırız. Hatayı sözlü olarak başkasına aktarırken de soruna dair yeni bir kavrayış kazanabiliriz. 

##Chapter 4

* Pragmatik programcılar kendileri de dahil kimsenin mükemmel kod yazmadığını bilerek kendi hatalarına karşı savunma oluştururlar. 
* Bir sözleşme haklarımızı ve sorumluluklarımız aynı zamanda karşı tarafın haklarını tanımlar. Taraflardan herhangi birinin sözleşmeye uymaması durumunda ortaya çıkacak sonuçlarla ilgili bir anlaşmadır. 
* Proje başlamadan önce neleri kabul edeceğimiz konusunda katı olmalıyız ve karşılığında da mümkün olduğunda az söz vermeliyiz. Kodu yazmadan önce, giriş etki alanının ne olduğunu, sınır koşullarının neler olduğunu ve rutinin ne vaat ettiği veya neyi sağlamayı vaat ettiğini basitçe sıralamalıyız. 
* Kod tarafında sorunlar olabilir, bir ağ hatası belki de listenin boş gelmesi vb. gibi kod tarafında sorunlar yaşanabilir, bu zamanlarda switch/case’in önemini anlıyoruz, imkansızın ne zaman gerçekleşeceğini görmek için kullanmalıyız. Sorunları mümkün olan en kısa sürede tespit etmenin faydalarından biri, kodun erken çökmesidir. Kodun, imkansız olan bir şeyin gerçekleştiğini gördüğümüzde program artık geçerli değildir, ölü bir program sakat bir programdan daha az zarar verir.
* Kendimizi bu asla olamaz dediğimiz noktada bununla ilgili kod tarafına bir kontrol eklememiz gerekir. Bunu yapmanın en kolay yolu iddialardır. Assertion’lar koda yük getirecektir ancak asla olmaması gereken şeyleri kontrol ettikleri için yalnızca kod tarafında hata olduğu zaman tetiklenirler. Kod test edilip gönderildikten sonra bunlara ihtiyaç duymazlar ancak testin küçük bir olasılığının dahi yapılması olası değildir. 
* Kod tarafında kaynak kullanımında, ne tür kaynak kullanıldığının önemi olmaksızın temel kalıp bir kaynağı kim tahsis ederse onu serbest bırakmaktan yükümlü olmalıdır. 
* Pragmatik programcılar kendimiz de dahil kimseye güvenmedikleri için kaynakları uygun şekilde bırakıp bırakmadığını kontrol den bir kod oluşturmanın iyi bir fikir olduğunu savunurlar. 
* Pragmatik programcıların kesin bir kuralı vardır, devam etmeden önce her zaman küçük ve kasıtlı adımlar atın, geri bildirimi kontrol edin ve ayarlayın.

