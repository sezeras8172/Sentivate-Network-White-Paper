
# SENTIVATE WHITEPAPER

![Logo](https://sentivate.com/wp-content/uploads/brizy/3443/assets/images/iW=269&iH=274&oX=0&oY=0&cW=269&cH=274/SNTVTbig.png)

##### BAŞLIK: SENTIVATE- Evrensel Web
#####  ÖZET
Sentivate, günümüz web teknolojisinin yerini almak için geliştirilmiş, uygulanabilir ve gerçekçi bir alternatiftir. Sentivate ağı, merkezi veya merkezi olmayan ağların (centralized/decentralized) herhangi birinin sunabileceklerinin ötesine geçmek için dizayn edilmiş, merkezi odaklı fakat merkezi olmayan bileşenlerle geliştirilmiş karma bir ağdır. Sentivate; bant genişliği, geçerliliğini yitirmiş protokoller, arızalı DNS, hesap verebilirlik eksikliği, sertifika eksikliği, tepkili güvenlik, alan adı kuralları ve web kategorizasyonu gibi sorunlara doğrudan odaklanmaktadır.

##### ODAK
Bu dökümanda, VIAT’a hizmet edecek temel ağ ve bileşenleri, hApps (hibrit uygulamalar) ve Sentivate evrensel web'i için gerekli çekirdek ağ tasarımı irdelenmiştir. VIAT için ayrıca bir whitepaper yayınlanacaktır. Tüm bu teknolojiler, Sentivate’in günümüz internet mimarisinin yerini alacak evrilmiş bir hali olmasının ötesinde, devrim yaratmasını sağlamaya odaklanmıştır.

## GİRİŞ
##### WWW (DÜNYA ÇAPINDA AĞ) DURUMU

Günümüzde, yıkık dökük, iflas etmek üzere olan, birbirlerine bağlı iletişim araçlarının küresel ölçekte kullanılmaya devam edildiğini görmekteyiz. İnsanlığın talepleri Dünya Çapında Ağ’ın karşılayamayacağı derecede her geçen gün katlanarak artmaktadır. İnsanlık, gelişime, değişime ve güneş sisteminin ötesine geçme girişimine devam ettikçe, bağımlı olduğumuz teknolojide devrim yaratmak bir zorunluluk haline gelmiştir.

Dünya Çapında Ağ’ın şu anki yetersiz durumu kabul edilemezdir. Eğer mevcut sorunlar yama yapılarak çözülmeye devam ederse, internet hep kusurlu olarak kalacaktır. İnsanlığın giderek artan talepleri, Dünya Çapında Ağ’ın varolan durumu tarafından asla karşılanmayacaktır. Bu sebeple mevcut sorunlara devrimsel bir bakış açısıyla yaklaşmaya başlamalıyız. Çözüm; artırılmış güvenlik, hız, verimlilik, hesap verebilirlik, güvenilirlik, kimlik, kapasite ve dayanıklılık ile çağdaş sistemlerin, tarayıcıların, haberleşme yöntemlerinin, protokollerin ve platformların tamamen değiştirilmesidir. Yeni bilgi çağına sağlıklı bir geçiş yapabilmek için, sahip olduğumuz teknolojiyi tümüyle değiştirmek zorundayız.

###### BANT GENİŞLİĞİ SORUNU
[Bant genişliği sınırlıdır, varolan ağlar büyüyen ihtiyaçlarımız için yetersizdir.](https://www.scientificamerican.com/article/the-bandwidth-bottleneck-that-is-throttling-the-internet/) Bu sorunu çözmek için mevcut bileşenlerin yerini alacak modern devrimci teknolojiye ihtiyacımız vardır. Bunu yapmadığımız taktirde, hız şeridi ve verilerin önceliklendirilmesi tek seçeneğimizdir. İnternet servis sağlayıcılarının, tüm internet iletişimine eşit şekilde davranmayacağı ve kullanıcı, içerik, web sitesi, platform, uygulama, ekipman türü veya iletişim yöntemine göre ayrım yapma veya farklı ücret alma korkusu, interneti eğirmek için tek umudumuz olacaktır. IoT (Nesnelerin İnterneti)'nin kaçınılmaz yükselişi, kişi başına düşen cihaz sayısındaki artış, ev başına daha fazla cihaz, kendi kendine sürüş yapan araçlar, araç sigortası mantıksal analizi ve yeni gelişmekte olan ülkeler çevrimiçi olmaya başladıkça, sahip olmadığımız bant genişliğini emecektir.

###### BEL BAĞLADIĞIMIZ WEB KENDİNİ YEMEKTE
HTTP ve DNS uzun zaman önce, modern taleplerin artacağı düşünülmeksizin inşa edildi. Giderek daha fazla bant genişliği emiliyor, HTTP, uzun ölçeklenebilirlik sorunlarını göstermeye devam ediyor ve DNS güvenilir veya ölçeklenebilir değildir. Eğer web'in yarısı DoS-ing'e özgü DNS sunucularından kapatılabiliyorsa, bariz bir mimari problem olduğu aşikardır. HTTP para akışı için mevcut araçtır. Tüm dijital ekonomi HTTP üzerinden taşınır. HTTP veya DNS’e yavaşlama, çok daha yavaş bir küresel ekonomi demektir. DNS ve HTTP doğal olarak bozulmakta, ölçeklenebilirliği zayıf, korkunç derecede yavaş, modern özelliklerden yoksun, bant genişliğini tüketmekte, tüketicilere ve işletmelere milyarlara mal olmaktadır. Bu sorunu çözemezsek, ekonomiye büyük bir darbe ile karşı karşıya kalacağız. Tüm bunları göz önünde bulundurduğumuzda, yakın gelecekte yavaş ağların küresel bir krize yol açacağı açıktır.

1.  [_1.Satışlarda bir saniyelik gecikme Amazon’a 1.6 milyar dolara mal olabilir.](https://www.fastcompany.com/1825005/how-one-second-could-cost-amazon-16-billion-sales_)
2.  [_2.	“10 yil önce Amazon, her 100ms'lik gecikmenin satislarda % 1'e mal oldugunu keşfetti”_](https://www.gigaspaces.com/blog/amazon-found-every-100ms-of-latency-cost-them-1-in-sales/)
3.  [_“10 yil sonrasının nasıl olacağına dair bir çalışma, web sitesinin yüklenme süresindeki her 100 milisaniyelik bir gecikmenin dönüşüm oranlarini %7 oraninda etkileyebileceğini -bu da satislarda önemli bir düşüştür- Amazon'un saniye ve milisaniye cinsinden gecikmeden bahsetmesinden itibaren %6’dır. Bu durum, e-ticaret başarısı için kullanıcı deneyimlerinin kritik önemde olması sebebiyle, internet perakende satıcıları için işlerin hiç kolay olmadığını göstermektedir. 
”_](https://www.akamai.com/us/en/about/news/press/2017-press/akamai-releases-spring-2017-state-of-online-retail-performance-report.jsp)

###### KİŞİSELLEŞTİRİLMİŞ WEB OLMAYAN ARIZA AKA WEB 3.0
Küresel ekonominin yüksek performanslı ve ucuz bir ağ gerektirdiğini biliyoruz. Eğer sadece merkezi olmayan bir ağ, modern ağın yerini alırsa, o zaman bant genişliği krizini hızlandıracak ve bizi bir distopya ağına götürecekti. Web 3.0 terimi sihirli bir dünya, devrimci bir fikir veya bir çözüm değildir; Bu bir nakit çekimi. Nanosaniye cinsinden gerçekleşen işlemler, küresel ekonominin ağ üzerinden doğrulanması ve yayılması için blok süre boyunca saniyeler veya dakikalar beklemek için zamanı yok. Web için bir değiştirme, tüketiciler için daha yavaş ve daha pahalı olmamalıdır. Web 3.0 daha pahalıya mal oluyor ve hepsi zincir halinde gibi şeyler arkasına saklanmaktan hoşlanıyor ve bir uygulamayı başlatmanın maliyeti çok az. Gerçek şu ki, ödediğiniz paranın karşılığını alıyorsunuz. Web 3.0, hizmetler yerine kullanıcılara maliyeti düşürür ve bu da daha düşük bir hizmetle sonuçlanır. Diğer bir yaygın argüman, kullanıcıların verilerini kontrol etmelerine izin vermektir. Bu sorun değil, homomorfik şifrelemeye merhaba deyin. Bu konuyu sadece topolojiden ele almak yerine, web'in her alanında yenilik yapmalı ve web servislerimizden daha fazlasını istemeliyiz. İnternetin topoloji problemi, eski teknoloji problemine kıyasla çok azdır. Bu Web 3.0 projeleri aslında web'i değiştirmeye özen gösteriyorsa, asıl konulara odaklanırlardı. **Her iki topolojinin de kullanım durumları var, ancak birlikte kontrol edilmeyen ve gittikçe büyüyen bir sorunun çözümü.**

## EVRENSEL WEB KRİSTOGRAFİ ([SODYUM-YERLİ](https://github.com/sodium-friends/sodium-native))

-  Anahtar İmzalar
    -   Tek parça imzası: Ed25519
    -   Çok parçalı imza: Ed25519ph
-  Paket Şifreleme
	- Ek Verilerle Doğrulanmış Şifreleme
    - Bir mesajı bir mesajla ve gizli tutmak için şifrelemeyle şifreler.
    - Bir kimlik doğrulama etiketi hesaplar. Bu etiket, iletinin yanı sıra isteğe bağlı, gizli olmayan (şifrelenmemiş) verilerin de tahrif edilmediğinden emin olmak için kullanılır.
    - Şifreleme: XChaCha20 akış şifresi
    - Authentication : Poly1305 MAC

- Anahtar değişimi - Paylaşılan Oturum Gizli Anahtarları
    - BLAKE2B-512
        - AK BLAKE2 bir şifreleme karma işlevidir **MD5, SHA-1, SHA-2 ve SHA-3'ten daha hızlı**, en azından en son standart SHA-3 kadar güvenli
        - NEON etkin ARM'ler dahil 64 bit platformlar için optimize edilmiştir ve 1 ile 64 bayt arasında her boyutta özetler üretir
    - X25519- Geçici Anahtar Çifti
        - Gönderenin gizli anahtarını ve alıcının genel anahtarını kullanarak gönderenle alıcı arasında paylaşılan bir sırrı hesaplar (veya tersi)

## Hibrit ağ
![Sentivate Hibrit ağ](https://github.com/sentivate/Sentivate-Network-White-Paper/blob/master/images/turkish_1.jpg)

## PROTOKOL

### Evrensel Veri Akışı Protokolü
###### Veri Aktarım Protokolü 

UDSP, UDP tabanlı düşük gecikmeli, gerçek zamanlı, iki yönlü, şifreli ve güvenilir bir Veri Aktarım Protokolüdür.

##### Sorun
Giriş bölümünde bahsedildiği gibi: Kullanıcının talepleri değişti ve internetin gereksinimleri arttı. Bu değişiklikler, HTTP'yi büyük bir tıkanıklık haline getirir. HTTP standardının kendisi ve TCP'nin ikisi de büyük sorunlardır. Çok büyük miktarda veriyi bir uç noktadan diğerine taşıyan büyük veri merkezleri, eski Internet mimarisiyle ilişkili gecikme ve maliyet sorunlarına sahiptir. HTTP, kullanıcılar düşük verim, sınırlı bant genişliği, düşük ağ bağlantısı veya gerçek zamanlıya yakın bir yanıt gerektirdiğinde, sorunludur.

##### Çözüm
Evrensel Web'in yapımındaki ilk adım, HTTP'yi tamamen UDSP ile değiştirmek. UDSP, UDP tabanlı düşük gecikmeli, gerçek zamanlı, çift yönlü, şifreli ve güvenilir bir Veri Aktarım Protokolüdür. Universal Web'de, tüm iletişim, akış veya herhangi bir veri türünün aktarılması UDSP'yi kullanır. Evrensel Web'de bir siteyi ziyaret ederken UDSP, HTTP yerine kullanılan protokoldür. Özel UDSP istemci ve sunucu modülleri, Sentivate Ağındaki bir web sitesini ziyaret etmek veya barındırmak için gereklidir. UDSP, Sentivate Ağının kuruluşu ve can damarıdır.

UDSP, bağlantı düzeyinde veya ilgili taraflar arasında kararlaştırılan istek başına esasına göre dinamik güvenilirliğe sahiptir. UDSP şifrelemeyi zorlar, bu da tüm UDSP bağlantılarının varsayılan olarak şifrelenmiş olduğu, istisnalar olmadığı anlamına gelir. UDSP IPv6, Multiplexing ve Multihoming'i destekler. UDSP, bağlantı kurmak için kriptografik tuş takımlarına ve XChaCha20'ye güveniyor.

UDSP, gerçek zamanlı web ve Dispersed Computing'e öncelik veriyor. Bağlantılar iki yönlü akışlar ve daha az konuşkan olduklarından, bu ağın daha az tıkanmasına neden olur ve bağlantının geçerliliği için düşük gecikme sağlar. UDSP, HTTP'den çok daha az konuşkandır ve kendi güvenilirlik standartlarını ayarlamak için programlı olarak ayarlanabilir. Bu, UDSP'yi yüksek verimlilik, düşük gecikme süresi ve yüksek güvenilirliğin gerekli olduğu yerlerde çok kullanışlı bir protokol haline getirir. UDSP'nin programatik olarak dinamik olması nedeniyle, oldukça değişken ve ya da bozulmuş ağ bağlantısı durumlarında etkilidir.

UDSP, paketlerin içinde, sağlayıcıların ve çözücülerin VIAT kazanmasını sağlayan isteğe bağlı bulmacalara sahiptir. Yapbozlar değişkenlik gösterebilir ve bu nedenle yapbozlar Dinamik Çalışma Kanıtıdır. Bulmacalar kapsüllenebilir veya bulmacayı çözmek için gerekli olan verilere işaret edebilir. Bu işlevsellik, VIAT için bir sonraki beyaz makalede açıklanacaktır. Yapbozlar ayrıca tıkanıklık kontrolü ve DDOS saldırılarından gelebilecek olası zararları sınırlamanın bir yolu olarak da işlev görür. Sentivate, çeşitli bulmaca türlerinin paketlere sokulmasıyla tipik bir DDOS saldırısını kar haline getirir. Bir müşteri sunulan bulmacayı çözdüğünde, müşteri ve alan adı Viat ile ağ tarafından hesaba katılır. Bir sunucu DDOS saldırısı altındaysa, sunucu etki alanı için ödül bölünmesini dinamik olarak% 100'e kadar değiştirebilir. Bu, saldırganların daha fazla maddi zarara uğramasını ve kazanacak çok az şey olmasını sağlar. Bulmacalar, her iki tarafın da iyi niyetle davranmaya teşvik edilmesini sağlar.

![CLIENT CONNECTION](https://github.com/sentivate/Sentivate-Network-White-Paper/blob/master/images/turkish_2.jpg)

## UNIVERSAL DOMAIN SİSTEMİ

### DOMAIN BELGELERİMİZ
###### YÖNLENDİRME VE KRİPOGRAFİ PARAMETRELER

Etki alanı sertifikaları, yönlendirme, şifreleme ve bir ana bilgisayar adıyla ilişkili ek ayrıntılar sağlar. Etki alanı sertifikaları 3 veya daha fazla anahtar çifti tarafından imzalanır: Ephemeral, Master ve yetkili bir Domain Registrar. Başarılı bir el sıkışma oluşturmak için, etki alanı sertifikası ve geçerli bir imza gerekir.

Etki alanının geçici sertifikası, müşterilere dağıttığı her bulmaca için fon depolayan bir cüzdan görevi de görür. Mayınlı Viat'ın bir kısmı geçici sertifika cüzdan adresine gönderilir.

### DOMAIN REGISTRAR
###### YÜKLEME & İMZA ALAN BELGELERİMİZ

Etki Alanı Kayıt Şirketi (DR), bir etki alanı kaydetmek ve bir etki alanının genel sertifikasını yönetmek için kullanılır. DR, ana bilgisayar adıyla ilişkilendirilmiş ortak sertifikaları doğrular ve imzalar. DR, sertifikayı dağıtım için sertifikayı depolayan Etki Alanı Bilgi Sistemine iletir.


### DOMAIN BİLGİ SİSTEMİ
###### QUERY DOMAIN ROUTING VE KRİPTOGRAFİ

Etki Alanı Bilgi Sistemi (DIS), insan tarafından okunabilen ana bilgisayar adlarından bir etki alanı sertifikası biçimindeki etki alanına özgü bilgileri döndürür. DIS, etki alanının şifreleme ayrıntılarını ve yönlendirme bilgilerini içeren sertifikasını döndürür. Ana bilgisayar adları şifreleme, yönlendirme bilgileriyle birlikte dahil edildiğinde, 0-RTT, müşteriden önce alanı ziyaret etmesine gerek kalmadan mümkündür. Bu, TLS 1.3'e kıyasla benzersiz bir avantajdır, çünkü 0-RTT varsayılan olarak TLS 1.3'te olduğu gibi siteyi daha önce ziyaret etmiş olmak zorundadır. Müşteriler bir web sitesine bağlanmadan önce, önce DIS'i insan tarafından okunabilen bir ana bilgisayar adıyla sorgulamalıdırlar. DIS, müşterilere etki alanı sertifikalarına en hızlı şekilde erişmelerini sağlamak için merkezi sunucular ve merkezi olmayan bir ağa sahiptir.

DİS, kötü niyetli sertifika ile ilgili saldırılara karşı başka bir savunma katmanı olarak hareket eder. DIS'den bir servise gitmek üzere bilgi istemek için geçersiz sertifikalar kullanıldığında, DIS sadece bir cevap döndürmeyi reddeder.

Etki alanı sertifikaları sağlayan merkezi olmayan düğümlerin hizmetleri aracılığıyla Viat kazanma şansı var. Bu işlevsellik Viat teknik incelemesiyle derinlemesine ele alınacak.

![DIS](https://github.com/sentivate/Sentivate-Network-White-Paper/blob/master/images/turkish_3.jpg)

### DOMAINS
###### İNSAN OKUMA HOSTNAMLARI

Sentivate’deki alanlar tam uzantı adlarına sahiptir ve ticari marka varlıkları için tek tam adlar içerebilir. Etki alanı kuralları ve düzenlemeleri web'i düzenlemek, yeni şirketler için etki alanı adları serbest bırakmak, ticari markaları korumak, kötü amaçlı faaliyetleri sınırlandırmak ve uzantıları daha açıklayıcı hale getirmek için tasarlanmıştır.

Örneğin, bir Amazon yalnızca Sentivate tarayıcısına Amazon yazarak gidebilir. Etki alanı kuralları, Sentivate ağında daha katıdır. Etki alanı ele geçirme işlemine tamamen izin verilmiyor, bunun bir kullanımı var ya da politikasını kaybediyor. Etki alanı içeriği veya hizmeti, etki alanı uzantısıyla alakalı olmalıdır. Örneğin, Amazon'un mağazasının "Amazon.store" adlı mağaza etki alanı uzantısını kullanması gerekir. Bazı etki alanları için kısa devre alanı uzantıları vardır. Örneğin, Amazon’un şirket web sitesinde, Amazon. Bitcoin, Ethereum ve Litecoin kripto para birimleridir ve bunlara adanmış siteler kripto para birimi uzantısını kullanmalıdır. Ancak, bitcoin ile ilgili bir haber sitesi .news veya .blog uzantısını kullanmalıdır. Rasgele ve veya rasgele içeriğe sahip olabilecek herhangi bir etki alanı .abstract uzantısını kullanmalıdır.

## UNIVERSAL KİMLİK SİSTEMİ

### KİMLİK BELGELERİMİZ
###### EPHEMERAL VE MASTER ANAHTAR ÇİFTLER

Kimlik sertifikaları (IC), sizi ağda temsil eden ve bir Kimlik Tescil Görevlisi tarafından imzalanan şifreleme ayrıntılarını sağlayan belgelerdir. Bir kimlik sertifikasının iki şifreleme anahtarı çifti vardır: Master ve Ephemeral. Özel olarak geçici sertifikaları imzalamak için bir ana anahtar çifti kullanılır ve çekirdek tanımlayıcı anahtar çiftidir. Geçici anahtar çiftleri, sahibinin takdirine bağlı olarak değiştirilebilir. Kimlik sertifikaları, ağdaki istemcileri şifreleyerek doğrular ve yetkilendirir.

Geçici Sertifikalar (EC), Ana Sertifikaya bir alt sertifikadır. EC'ler, kullanıcı tanımlı servislere erişmek için kullanılan profiller gibi davranır. Örneğin, cüzdan sertifikası, bankacılık sertifikası, genel web tarama sertifikası veya her servis için. Ancak, tüm hizmetler için tek bir geçici sertifika kullanmayı seçebilirsiniz. EC'ler, menşe ile ev sahibi arasında iki yönlü bir UDSP bağlantısı kuran anahtar değişim işlemi için kullanılır.

Kullanıcılar, hemen sertifika alabilirler, kimlik sertifikalarıyla bir öğeye kaydolabilir, giriş yapabilir ve satın alabilirler. Sunucular, başarılı bir UDSP anlaşması oluşturmak için bağlantı sırasında müşteri sertifikası isterler.

Kimlik sertifikaları, belirli sertifikalarla ilişkili olarak iyi ve kötü davranışları genel olarak kaydedebilen merkezi olmayan bir itibar sisteminin temelini oluşturur. Bilinen kötü oyuncuların ağı daha da güvenli hale getiren bir hizmete erişmelerini engellemek için bir bal küpü kullanılabilir.

Kimlik sertifikaları gerçek dünya kimlikleri ve varlıkları ile ilişkilendirilebilir. Sentivate'i seçimlerde güvenli, özel ve doğrulanabilir oylamalar için ideal bir platform haline getirmek. Mağazalar ve şirketler, kullanıcıların Viat ile doğrudan ödeme yapmasına veya bağış yapmasına izin veren IC'leri doğrulamış olabilir.

### KİMLİK KAYIT (KİMLİK REGISTRAR)
###### DEĞERLENDİRME VE İMZA

Kimlik Tescil Görevlisi (IR) sertifikaları imzalayan ve ağ için ilk koruma katmanı olan bir hizmettir. IR, hatalı sertifikaları filtreleyerek, Sybil saldırılarını ve zorlayıcı oyuncuları durdurarak ağı koruyor. Kimlik Tescili, hizmetlerin bağlantı girişimlerini etkin bir şekilde reddetmelerine izin veren kötü amaçlı sertifikaların imzalanmamasını sağlar. Sahte imzalar DIS tarafından reddedilebilir ve bu nedenle bir hizmeti potansiyel olarak koruyabilir ve elden önce bazı kaynaklarını koruyabilir.

Merkezi olmayan bir ağ ve asiklik bir blok zinciri, imzalanmak üzere yeni gönderilen sertifikaların doğrulanmasına yardımcı olmak için kullanılacaktır. Sertifikalı ağ tarafından başarıyla onaylanırsa, IR sertifikayı imzalar. Daha sonra, servisler ve DIS tarafından başarıyla kullanılabilir. İlk el sıkışma sırasında, ilk paket bir UDSP akışı oluşturmak için gereken sertifikaları içerir. İmzalar başarıyla doğrulanırsa, el sıkışma işleminin geri kalanı devam eder, aksi halde başarısız olur.

Aktif sertifikalar sürekli güncellenecek ve imzalanacaktır. Bir sertifika yeniden imzalandığında, sertifikanın önceki imzasından bu yana geçen süreyi gösteren sertifikaya başka bir alan eklenir. Bu, belirli sertifikalar için ek bir güven katmanı ile hizmet sunar.

## GELİŞİM 

### hApps
###### HİBRİD EVRENSEL WEB UYGULAMALARI

Hibrit uygulamalar kendi kendini oluşturuyor ve tek sayfalı uygulamalar yayınlıyor. Hibrit uygulamalar reaktif, dinamik ve modüler gelişim metodolojileri kullanılarak oluşturulmuştur. hApps, en yüksek ölçeklenebilirlik potansiyelini sağlayan merkezi ve merkezi olmayan ağların tüm avantajlarına sahiptir.

hApps’ın varlıkları kendi dosyalarında bulunur ve müşteriye ihtiyaç duyulduğunda aktarılır. hApp'ler, akış boyunca yürürken kendisini inşa eden bir köprü gibi, zaman içerisinde izlenir ve kurulur. Yalnızca bir ilk sayfa yükleme gerçekleşir ve ardından Sayfalar, Tek sayfa uygulamalarına benzer şekilde gerektiğinde dinamik olarak oluşturulur. Sadece müşteri tam olarak ihtiyaç duyduğunda kaynak alınacak ve teslim edilecek.

Sentivate’in bileşenleri, oldukça modüler varlık akışı sağlar. Örneğin, bileşenler, paylaşılan varlıkların yalnızca bir kez indirilmesini ve yinelenen kodun hiçbir zaman kablo üzerinden gönderilmemesini sağlayan aynı CSS veya HTML varlıklarını paylaşabilir. Bu metodoloji ile sunucu yükleri ve bant genişliği önemli ölçüde azaldı, çünkü şu anda müşteri tam olarak ihtiyaç duyulanı çekiyor.

Hybrid Apps, hedef servise ek olarak varlıklar için bir merkeziyetçi olmayan P2P CDN'si kullanabilir. Hibrit İçerik Dağıtım Ağı'nı kullanmak, hibrit uygulamaların yüksek kullanılabilirliğe, ölçeklenebilirliğe ve daha fazla bant genişliğine sahip olduğu anlamına gelir.

hApps, ilk bağlantı anlaşması sırasında istemcileri otomatik olarak doğrular, doğrular ve yetkilendirir. hApps arka uçları, istemcileri genel anahtarlarıyla veya tam sertifikalarıyla saklayabilir ve başvuruda bulunabilir. Bütün İnternet için outh olarak düşünün. Hizmetlerin artık parolaları toplama, saklama veya şifreleme konusunda endişelenmesine gerek yok. Müşteriler bir düğmeye tıklayarak veya hızlıca servise bağlayarak otomatik olarak giriş yapabilirler. Kullanıcıların artık tuş takımlarını kullanmak daha güvenli ve kullanımı daha kolay olduğu için karmaşık şifreler hatırlamak veya oluşturmak zorunda değiller. Servisler bir kullanıcı adınızın olmasını gerektirmiyorsa, tanımlayıcı adınız olarak genel anahtarınıza güvenebilirler. Bu, bazı hizmetler için kullanıcıların kayıt işlemi sırasında bir kullanıcı adı ve parola oluşturmak zorunda olmadıkları anlamına gelir.

## VIAT

### DOĞAL KRİPTOKÜRRİ
Viat, Sentivate Ağındaki yerel şifreleme para birimidir. Viat'ın melez bir blok zinciri var. Viat’ın çekirdek sistemleri merkezileşmemiş odaklanmış ancak merkezi bileşenler (Sentivate’in Web’inin tersi) tarafından geliştirilmiştir. Viat hızlı, güvenli ve mevcut en düşük işlem ücretlerinden bazılarına sahip olacak şekilde tasarlanmıştır. Viat’ın merkezi bölümleri anlık işlemleri gerçekleştirebilir, cüzdan güvenliği sağlayabilir ve merkezsiz ağ ağır yük altındayken ağ tıkanıklığını azaltabilir. Ancak, bu merkezi özellikler yalnızca kullanıcıların kendi yollarını oluşturmasına izin vermek için tercih edilir.

### MADEN
Viat'ın iki şekilde mayınlanabilecek dinamik bir çalışma kanıtı var. Doğrudan madencilik, Viat teknik raporunda açıklanacak olan ana yöntemdir ve ikinci yöntem ise UDSP'de paket bulmacaların kullanılmasıdır. Paket yapbozlar, Universal Web’e göz atarken Viat’ın pasif madenciliğine izin veriyor. Ancak, varsayılan olarak etkin değildir. Paket bulmacaları etkinleştiren durumlar şunlardır: bağlantı anlaşması, bağlantı canlılığı kontrolü, DDoS koruması, tıkanıklık kontrolü ve / veya servis, kendi nedenleriyle etkinleştirmeyi seçer. Paket bulmacaları etkinleştirmek hizmete kalmıştır. Bu, arka planda sürekli madenciliğe gerek kalmamasını ve madencilik sürecine gerçek bir amaç verilmesini sağlar. Aksi takdirde, kaynakları emmek ve pil ömründe yemek her zaman açık olacaktır.

### INTEROPERABILITY 
Kimlik ve Etki Alanı sertifikaları ayrıca Viat cüzdan anahtarları olarak da kullanılır. Bu, kullanıcıların bir bağlantı anlaşması sırasında yalnızca bir servise anında giriş yapmasını sağlamakla kalmaz, aynı zamanda servislerden, ipucu sitelerinden ve / veya geri ödemeli müşterilerden mal satın almanın bir yolunu sağlar. Viat, Evrensel Web'in tam işlevselliğinin ayrılmaz bir parçası olup, resmin yalnızca bir kısmı yoktur.
