# Mustafa-aykac-linux-komutlari
<div align="center"><h1><strong>LİNUX NEDİR</strong></h1></div>
Başlarda Linus Torvalds, Scratch adıyla MIT tarafından geliştirilmiş birdil tabanı kullanarak yaratmıştır.
Linux bir operating sistemin kernelidir.  Yani aslında kendi başına bir iletim sistemi değildir. Linux etrafında şekilenen UI ve uygulamalar Linux’ü tam bir işlemi yapar. Buna nazaran Linux Kernel olduğu içinde farklı küçük değişiklikler yaparak yeni linuxlar oluşturup özel isimle piyasaya sürülebilir. Buna örnek olarak:
 Ubuntu, LinuxRedHat, Enterprise Linux, Linux Mint, Debian, Fedora, Arch Linux, Manjaro
Gibi farklı varyosyonlar ortaya çıkmıştır.
Linux özelleştirebilir ve açık kaynaklı olduğundan kaynaklı olduğundan serverlarda ve genel olarak pek çok alanda yazılım sektöründe kullanılmaktadır. Bunun sebebi Linuxun hızlı, ücretsiz olması ve güvenili olmasından kaynaklanır.

<h2><strong>1. Linux Shell Terminali Nedir ve Nasıl Kullanılır</strong></h2>
Linux Shell CMD'nin Linux için olanıdır. Linux Shell CMD'de olduğu gibi kullanıcıyı İşletim sistemindeki komut yönetimine bağlayarak uzun
sürebilecek işlemleri bir kaç harfle oluşan kısatlmalı cümlelelrden oluşur.Bu komutlar işletim sistemiyle kullanıcı arasındaki köprü görevi görür.Linux dağıtıcıları Guı ile gelir.(GUI bilgisayarlarda işletilen komutlar ve bunların çıktıları yerine simgeler, pencereler, düğmeler ve panellerin hepsine verilen addır.) Bu Guılar CLIya işlenir(CLI bilgisayarın işletim sistemiyle etkileşime geçtiği panele verilen addır.)girer.

| <div align="center">no</div> |	<div align="center">Komutlar</div>   | Açıklamalar
|------------------------------|-----------------------------------------|--------------------------------------------------------------------------------------------------------------| 
| <div align="center">1</dir>  |	<div align="center">pwd</div>	     | içinde bulunduğunuz dosyayı ekrana getirir                                  |
| <div align="center">2</dir>  |	<div align="center">touch</div>	     | touch dosya oluşturmaya yarar bu dosyalar txt veya farklı türde dosya olabilir.                                                                                            |
| <div align="center">3</dir>  |	<div align="center">ls</div>	     | Bir dizindeki dosya ve alt dosyaların listesini gösterir.                                                    |
| <div align="center">4</dir>  |	<div align="center">mkdir</div>	     | Yeni bir dizin oluşturur.                                                                                    |
| <div align="center">5</dir>  |	<div align="center">rmdir</div>      | Bir dizini kaldırır (içindeki dosyalarla birlikte kaldırmak için -r seçeneği kullanılır).                    |
| <div align="center">6</dir>  |	<div align="center">rm</div>	     | Dosya silme işlemini yapar.                                                                                  |
| <div align="center">7</dir>  |	<div align="center">man</div>	     |bir komudun nasıl kullanılacağı ve ayrıntısı hakkında bilgi alır. örnek                                       |
| <div align="center">8</dir>  |	<div align="center">mv</div>	     | Dosya ve dizinleri taşır veya yeniden adlandırır.                                                            |
| <div align="center">9</dir>  |	<div align="center">clear</div>	     | Terminal ekranını temizler.                                                                                  |
| <div align="center">10</dir> |	<div align="center">exit</div>	     | Terminal oturumundan çıkar.                                                                                  |
| <div align="center">11</dir> |	<div align="center">sudo</div>	     | bu komutu yapılacak bir işlemde kök ayrıcalıkları kullanmak ve görüntülemek istersek veya idari bir yapıyı yapılandırmak veya erişimi gerikirse kullana biliriz.                                                                                |
| <div align="center">12</dir> |	<div align="center">cat</div> | belirlenen iki dosya arasındaki karşılaştırma yapar veya birleştirir.                                                                                |
| <div align="center">13</dir> |	<div align="center">help</div>	     | Herhangi bir komudu yanlış yazma durumunda kullanıcay a kolaylık sağlar vehata ve kullanımları gösterir.                                                                 |                                                                          |
| <div align="center">14</dir> |	<div align="center">file</div>	     | Dosya türünü ve içeriğini gösterir. Ayrıca içeriği hakkında  da bilgi vermektedir                                                                                      |
| <div align="center">15</dir> |	<div align="center">printenv</div>	 | Ortam değişkenlerini gösterir.                                                                                |
| <div align="center">16</dir> |	<div align="center">echo -e "\033]0;Yeni Başlık\007"</div> | Terminal başlığını değiştirmek için kullanılır.                                        |
| <div align="center">17</dir> |	<div align="center">netstat</div>	 | Ağ bağlantılarını ve port durumunu gösterir.                                                                 |
| <div align="center">18</dir> |	<div align="center">shutdown</div>	 | Bilgisayarı kapatır veya yeniden başlatır.                                                                   |
| <div align="center">19</dir> |	<div align="center">find</div>	     | istenilen dosyaları bulmaya yarar.                                                                                    |                                                        
| <div align="center">20</dir> |	<div align="center">ps</div>	     | Çalışan işlemleri listeler.                                                                                  |
 
<h2><strong>2. Linux Terminal Komutları Ve Uygulamaları</strong></h2>

### **1.pwd**

Ek bilgilendirme:<br> Bu komudu sadece o an aktif olarak gösterir.

![Ekran görüntüsü 2024-11-15 133035](https://github.com/user-attachments/assets/9da07a5b-3abc-490c-9918-5aa14ec7782d)

### **2.touch**

Ek bilgilendirme:<br> BU komut genel itabiriyle windowstaki echo komuduyla karşılığa sahiptir.

![Ekran görüntüsü 2024-11-15 133532](https://github.com/user-attachments/assets/3e4367ad-6efd-4961-b7d6-031e0c7b4d0f)

### **3.ls**

Ek bilgilendirme:<br> Bu komut için bilgilendirme yukarıda tabloda verilmiştir fakat ek olarak bazı parametrelere sahiptir.<br>
1.ls -l: parametresi,dosyaların ayrıntılı bilgilerini göstermede işe yarar.<br>
2.ls -lh: dosya boyularını insanların okuyabileceği boyutlara indirger.<br>
3.ls -R: Bu parametre geçerli dizindeki ve alt dizindeki tüm dosyaları liztememizi sağlar.

![Ekran görüntüsü 2024-11-15 133305](https://github.com/user-attachments/assets/966dc28a-811e-4f2b-9452-aa763a7e1d3f)

### **4.mkdir**

Ek bilgilendirme:<br> Bu uygulama resmi mkdir,rmdir ve find komutlatının uygulama resimleri paylaşmaktadır tek bir uygualamda 3 komut kombine edlerek
uygualmaya sokulmuştur.

![Ekran görüntüsü 2024-11-15 133335](https://github.com/user-attachments/assets/0b5b9973-e6af-41b3-a9e8-a5c305d903ae)

### **5.rmdir**

Ek bilgilendirme:<br> Bu uygulama resmi mkdir,rmdir ve find komutlatının uygulama resimleri paylaşmaktadır tek bir uygualamda 3 komut kombine edlerek
uygualmaya sokulmuştur.

![Ekran görüntüsü 2024-11-15 133347](https://github.com/user-attachments/assets/8dca0ad8-9750-48e7-81eb-8d257e014588)

### **6.rm**

ek bilgilendirme:<br>Bu komutta yularıda belirtildiği gibi silme işlemi yapar fakat brada dikkat edilmesi gereken buradaki dosyalar çöp kutusuna atılmadan direk kalıcı şekilde silme işlemi uygular.<br>
Bazı parametrelere sahiptir:<br>
1.-r ve -f: kombinasyonu kullanılması takdirde kurtarılması çok zordur özel part yazlımlar gerekebilir.<br>
2.rm -rf/ : Bu komutunun, kök dizin ve tüm sistem dosyalarını siler. Bu komut çok tehlikelidir ve sistemin çökmesine yol açabilir.

![Ekran görüntüsü 2024-11-15 134116](https://github.com/user-attachments/assets/66f1782d-0339-48dd-89e6-bb979d96895e)

### **7.man touch**

Ek bilgilendirme:<br> Bir örnek olarak mn komudunu touch komuduyla birleştirerek burada touch komudunun kullanımı konusunda detayları görülmektedir.

![Ekran görüntüsü 2024-11-15 204134](https://github.com/user-attachments/assets/b37d240e-e84b-46ae-8737-f41f759eb66d)

### **8.mv**

Ek bilgilendirme:<br> Yukarıda gerekli bilgilendirmesi yapılan komut farklı parametreler sahiptir.<br>
parametreler:
1.-f: var olan dosyanın üzerine yazılmasına neden olur
2.-i: taşıma işleminde onay almaya yarar.
3.-v: Taşıma hakkında ayrıntılı bilgi verir.

![Ekran görüntüsü 2024-11-15 203910](https://github.com/user-attachments/assets/ab8ab6f4-3863-4486-ba1e-2a23551ed304)

### **9.clear**

Ek bilgilendirme:<br> Burada uygulama aynı ekranda önce ve sonra olarak görüntülenmiştir.

![Ekran görüntüsü 2024-11-15 133204](https://github.com/user-attachments/assets/4d6c72ae-a02d-465c-af71-bb07e2319d4b)

![Ekran görüntüsü 2024-11-15 133243](https://github.com/user-attachments/assets/8c829f1c-cd8b-4b70-8642-2c96a637521b)

### **10.exit**

Ek bilgilendirme:<br> Burada uygulama aynı ekranda önce ve sonra olarak görüntülenmiştir.

![Ekran görüntüsü 2024-11-15 135630](https://github.com/user-attachments/assets/5d575c44-861c-4158-be02-347bedbba08d)

![Ekran görüntüsü 2024-11-15 135721](https://github.com/user-attachments/assets/35a3968e-df82-477e-aeea-56e1bf864b3f)

### **11.sudo**

Ek bilgilendirme:<br> Superuser do yani Sudo bu komud aslında dostaki yönetici olarak çalıştırma mantığında ilerler ayrıca bu komut kullanıcıların yönetici 
hakkına sahip olmasını sağlar tabi kullanıcıyı belirli bir çerçevede tutarak belirli yetkilerlle bu işi yürütür.

![Ekran görüntüsü 2024-11-15 135835](https://github.com/user-attachments/assets/e2406785-a363-4a8a-b1b9-5aefc69dbe59)

### **12.cat**

Ek bilgilendirme:<br>Concatenate kelimesinden türeyen bir komuttur yukarıda belirtildiği gibi karşılaştırma veya birleştirme işlemlerinde kullanılır.

![Ekran görüntüsü 2024-11-15 141310](https://github.com/user-attachments/assets/be398cb4-72c6-49ea-8752-ca22e1a28d28)

### **13.help**

Ek bilgilendirme:<br>Bu komudun bilgilendirmesi basti ve yukarıda verilmiştir fakat bu komut bir kaç farklı parametlerndirmeye sahiptir ve bu sayede komudu özelliştirme mümkündür.<br>
1.help komut_adı: Bu parametreyle girilen 2. komut hakkında komut yardımı ister.
2.help cd: Belirtilen komut hakkında yardım mesajı gösterir.

![Ekran görüntüsü 2024-11-15 134818](https://github.com/user-attachments/assets/b0da5905-1854-4931-baf4-7b7ad707bdd2)

### **14.file**

Ek bilgilendirme:<br> yukarıya ek olrak aynı zamanda file komudu bağımsız olrak dosyanın gerçek türünü belirlemekte kullanılır.(txt,ımage ve dahası)
Kullanım zamanı:<br> Yazılan dosyanın hangi formatta olduğu bilinmediği zamanda,sistem veya binary dosyalar hakkında bilgi toplamak için.

![Ekran görüntüsü 2024-11-15 205401](https://github.com/user-attachments/assets/a9629be8-dbad-4757-b8e0-5ff47b62cbd3)

### **15.printenv**

Ek bilgilendirme:<br> Çevre değişkenliği dışıdna sistem dosylarını doğrulamada,hata ayıklamayla hangi çevresel değişkenleri mevcut olduğunu göremeye 
yarar ayrıca yapılandırmayla beraber belirli uygulamalar için ortam değişikliğini ayarlayarak kontrol eder.

![Ekran görüntüsü 2024-11-15 133521](https://github.com/user-attachments/assets/1e600e23-c1fa-453c-8fdf-f0cce1a1b370)

### **16.echo -e "\033;Yeni Başlık\007**

Ek bilgilendirme:<br> Yeni başlık oluşturma komudu dos komutlarına nazaran yeni kullanıcılar için biraz karmaşık ve anlam ifade etmeyebilir ama aslında
bu komudu parçalayarak aslındaki yapıya bir göz atılmalıdır.<br>
Komudun yapısı:<br>
1.\033: Escape karakterdir bu karakter terminalde özel kontrol dizileri başlatır.<br>
2.]0; :Terminalde başlığı ayarlama dizisini belirtir.<br>
2.1 [0] başlık çubuğunu ifade eder.<br>
3.Yeni başlık: aslında burası opsiyoneldir burası başlık ne olması isternire yazı yazılır.<br>
4.\007: en önemli karakterdir ve terminalde değişiklik işlemini tamamlanmasını sağlar.<br>
Kullanım Zamanı: Birden fazla teminal penceresinin açıldığı durumlarda<br> başlılara bölerek kolayca ayırımını yapmak için kullanılır.<br>

![Ekran görüntüsü 2024-11-15 211909](https://github.com/user-attachments/assets/708fbaad-4b1f-4ca2-87a7-05934305f3d7)


### **17.netstat**

Kullanım Zamanı:<br> Ağ bağlantılarını izlemek,sorunlu portları kontrol etmek ve ağ trfiğinde analiz yapmak için kullanılır. Ek bilgi olarakda
ağ uzmanları Linux kullanırken bu komut ağ uzmanları için çok kullanışlı bir araç haline gelmiştir.

![Ekran görüntüsü 2024-11-15 133440](https://github.com/user-attachments/assets/66c63e4b-1019-4f48-bb50-37e5327339a8)

### **18.shutdown**

Ek bilgilendirme:<br> Shutdown komutu aslında basit ve temel bir komuttur fakat parametleri vardır buda shut down komudunu fakrlı şekillerde kullanmaya olanak sağlar.<br>
Bu parametrelere örnek olarak:<br>
1.now: Bu parametre işlemi hemen başlatır.<br>
2.-h: Bu parametre ile tımer ayarlanır ve tımer süreis bittiği zaman bilgisayar kendini kapatır.<br>
3.-c: Bu parametre başlatılmış kapatma işlemini iptal eder.
ayrıca bu komutla dosyalar düzgün kapatılarak çıkış kapatma işlemi yapılır.

![Ekran görüntüsü 2024-11-15 135024](https://github.com/user-attachments/assets/677f22fb-0bd8-479b-8e1f-29b0f066947b)

### **19.find**

Ek bilgilendirme:<br> Bu uygulama resmi mkdir,rmdir ve find komutlatının uygulama resimleri paylaşmaktadır tek bir uygualamda 3 komut kombine edlerek
uygualmaya sokulmuştur.

![Ekran görüntüsü 2024-11-15 133347](https://github.com/user-attachments/assets/6583a265-3514-489e-b483-a75d743e180d)

### **20.ps**

Ek bilgilendirme:<br>Processes status kısaltmasıdır ve yukarıdaki bilgilendirmeye ek olrak hangi kaynakları kullandığını ve fazlasını görüntülemede kullanılır.

![Ekran görüntüsü 2024-11-15 133409](https://github.com/user-attachments/assets/22f03fa2-92d8-4f08-984c-7e1144115e97)




