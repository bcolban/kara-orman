# KARA ORMAN

Büyük kızıl dolunayın altında, sisli bir ormanda yakın dövüş ve zombi hayatta kalma oyunu. Windows için, tek başına veya en fazla üç oyuncuyla oynanır.

## İndir ve aç

**[Windows sürümünü indir](https://github.com/bcolban/kara-orman/releases/latest/download/KaraOrman-Windows.zip)**

**Releases → en son sürüm → KaraOrman-Windows.zip** dosyasını indir. ZIP'e sağ tıklayıp **Tümünü ayıkla** seç; çıkan klasörde **KARA_ORMAN.exe** dosyasını aç. Godot ve Mixamo kurman gerekmez. EXE ile **KARA_ORMAN.pck** aynı klasörde kalsın.

Oyun doğrudan motorun özgün dijital imzalı EXE dosyasından açılır; CMD başlatıcısı kullanılmaz. Windows yine uyarı gösterebilir. Pakette kısa açma anlatımı **1_ONCE_BUNU_OKU.txt** dosyasındadır. Başkalarına bütün ZIP'i veya bu indirme bağlantısını gönder; kendi bilgisayarının kısayolu ya da yalnız EXE dosyası yeterli değildir.

İki oyuncu da aynı sürümü kullanmalı. Oyun tarayıcı içinde çalışmaz.

Açılıştaki ana menüde büyük **OYNA** düğmesine bas. İlk oyunda hikâye ve zorunlu eğitime girer; eğitim yarım kaldıysa kayıtlı adımdan sürer. Eğitim tamamlandıysa OYNA doğrudan ormanı açar. Oda düğmeleri eğitim bitince açılır.

## Birlikte oyna

- **Aynı Wi-Fi:** biriniz **ODA KUR** desin. Diğeri oda sahibinin oyun ekranında görünen yerel IP adresini yazıp **ODAYA KATIL** desin.
- **Farklı evler:** iki bilgisayarda [Tailscale](https://tailscale.com/download/windows) kurulu ve bağlı olsun. Oda sahibi kendi bilgisayarı için cihaz paylaşımı davetini göndersin; diğeri kabul etsin. Oyunda oda sahibinin Tailscale `100.x.x.x` adresine bağlanın. [Resmî cihaz paylaşımı adımları](https://tailscale.com/docs/features/sharing).

Oda sahibinin oyunu açık olmalı. Windows güvenlik duvarı oyunun UDP 24567 portuna erişime izin vermeli. Tailscale kurulumunu iki bilgisayarda bir kez tamamlamanız gerekir. Ayrıntılı Türkçe anlatım paketteki **BIRLIKTE_OYNA.txt** dosyasında.

Grup oyununda **Enter** ile takım sohbetini açıp mesajını gönder; **Esc** ile kapat. **T'ye basılı tutarak konuş**, bırakınca mikrofon yayını durur. Konuşan kahraman sağ altta görünür. Ayarlardan mikrofonunu ve sohbet sesini seçebilir, sesli sohbeti kapatabilirsin. Ses ve mesajlar oyun bağlantısını kullanır; ayrı bir hesap gerekmez.

## Oyunda

Hikâyeden sonra **20 adımlık zorunlu temel eğitim** var. Yürüme, koşma, iki zıplama, engel aşma, kamera, kombo, savunma, kaçınma, güçlü vuruş ve üç kahramanın dövüş biçimleri gerçek uygulamayla öğretilir. Her bilgisayarda bir kez tamamlanır; yarım kalırsa son adımdan sürer. Finalde **üç kahraman, dokuz normal/mutant zombi türü ve üç boss**, toplam 15 karakter yan yana dans eder. Ardından tek oyunculu ve oda seçenekleri açılır.

Paladin, Maria ve Ely; 50 / 100 / 150 zombili üç zorluk; boss savaşları; aynı ağ ve Tailscale üzerinden eşli oyun. Bölümdeki bütün zombiler ve boss yenilince takım kazanır.

Zafer veya yenilgiden **10 saniye sonra ana menüye otomatik dönülür**; sonuç ekranında geri sayım görünür. Eşli oyunda herkes aynı bölüm sonucuyla döner. Bir kahraman ölürken takım arkadaşları yaşıyorsa oyun ve izleme sürer; yenilgi süresi tüm takım düştüğünde başlar.

Nişangâhın merkezi yakındaki düşmanın gövdesindeyken yapılan vuruş o hedefe isabet eder. Yakın dövüş menzili zombilerde **2,5 m**, bosslarda **3,5 m**. İlk iki saldırı **35**, güçlü saldırı **55** hasar verir. Her oyuncu kendi nişangâhıyla hedef seçer.

Ayarlarda **önizlemeli 10 nişangâh** arasından seçim yapılır; eski tek kırmızı nokta kaldırılmıştır. **Hitbox'ları göster** yalnızca **5 metre içindeki ve görüşü açık** isabet alanlarını gösterir; ağaç, kaya ve duvar arkasındakileri gizler. Başarılı vuruşta isabet işareti, **35 / 55 hasar** ve düşmanın kalan canı görünür. Eşli oyunda isabeti oda sahibi doğrular, işaret yalnızca vuran oyuncuya gösterilir. Tercihler bilgisayarda kaydedilir.

Maria'nın modeli, kılıcın oluşturduğu toplam sınırlar yerine gövdesinin merkeziyle hizalanır; isabet alanı artık gövdesinden yana kaymaz.

Dalgalı arazi ve doğal açıklıklara sahip ormanda 900 ağaç, ayrıntılı yaprak kümeleri, yosunlu kaya yüzeyleri ve 42 devrik ağaç bulunur. Sınırların ötesinde kaya dokulu dağ sırtları ve 2400 uzak ağaçla manzara devam eder. Kızıl dolunayın kraterleri gerçek 2K Ay yüzeyinden çizilir.

Yere yakın otlar kıvrımlı, eğreltiotu yaprakları yuvarlatılmış geometri kullanır. Bitki kümeleri yamaçların eğimine oturur; köklerin havada kalması azaltılmıştır.

WASD hareket · Shift koş · Space zıpla · E kaçın · Sol tık basılı kombo · Sağ tık basılı savunma · V kamera · H kontrolleri göster/gizle · Esc ayarlar.

**F11** ile tam ekran ve pencere modu arasında geçiş yapabilirsin. Menü, hikâye, temel eğitim ve oyun sırasında çalışır.

Sol alttaki kontrol açıklamaları H veya aynı köşedeki düğmeyle açılıp kapatılır. Tercih bu bilgisayarda hatırlanır; can ve bölüm bilgileri görünür kalır.

Bu depo oynanabilir Windows sürümlerini dağıtmak içindir. Motor ve kullanılan kaynakların lisans bildirimleri indirme paketinde yer alır.
