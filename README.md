# SEOMS Security Kullanım Kılavuzu

**Sürüm:** 1.1  
**Hedef kullanıcılar:** Süper Yönetici, Şirket Sahibi, Tedarikçi ve Amir
**Uygulama:** SEOMS Security

Bu kılavuz; uygulamada oturum açma, şirket kapsamını seçme, tedarikçi ve personel havuzlarını yönetme, etkinlik yürütme, personel talebi oluşturma ve yoklama alma adımlarını açıklar. Bu sürümde ekran görüntüsü yoktur.

## İçindekiler

1. [Hesap rolleri](#1-hesap-rolleri)
2. [Giriş ve çalışma şirketini seçme](#2-giriş-ve-çalışma-şirketini-seçme)
3. [Gösterge panelini okuma](#3-gösterge-panelini-okuma)
4. [Şirket ve hesap yönetimi](#4-şirket-ve-hesap-yönetimi)
5. [Tedarikçileri yönetme](#5-tedarikçileri-yönetme)
6. [Personel havuzunu yönetme](#6-personel-havuzunu-yönetme)
7. [Etkinlik ve atamaları yönetme](#7-etkinlik-ve-atamaları-yönetme)
8. [Personel talebi ve tedarikçi yanıtı](#8-personel-talebi-ve-tedarikçi-yanıtı)
9. [Yoklama ve QR akışı](#9-yoklama-ve-qr-akışı)
10. [Bildirimler, ödemeler ve denetim kayıtları](#10-bildirimler-ödemeler-ve-denetim-kayıtları)
11. [Güvenli işlem ve sorun giderme](#11-güvenli-işlem-ve-sorun-giderme)

## 1. Hesap rolleri

| Rol | Neler yapabilir? |
| --- | --- |
| **Süper Yönetici** | Şirket ve hesap yönetimi yapar, çalışma şirketini seçer veya tüm şirketler görünümünü kullanır, operasyonları denetler. |
| **Şirket Sahibi** | Kendisine atanmış şirket(ler) içinde tedarikçi, personel, etkinlik, talep, atama ve yoklama işlemlerini yürütür. |
| **Tedarikçi** | Yalnızca kendi tedarikçi personelini ve kendisine atanmış etkinlik/talepleri görür; personel önerisi gönderir. Etkinlik oluşturamaz veya etkinlik bilgilerini düzenleyemez. |
| **Amir** | T.C. Kimlik No ve ayrı şifreyle giriş yapar; yalnızca yetki verilen etkinlik ve bölgelerdeki onaylı personeli kendi bölgelerine yerleştirir. |

Menüde görünen seçenekler, oturum açan hesabın rolüne ve seçili şirket kapsamına göre değişir. Erişim sınırları sunucuda da uygulanır.

## 2. Giriş ve çalışma şirketini seçme

1. Uygulamanın size verilen adresini açın.
2. Yönetici tarafından verilen kullanıcı adı/e-posta ve parolayla giriş yapın.
3. Birden çok şirkete erişiminiz varsa üst bölümdeki hesap/şirket seçicisinden çalışacağınız şirketi seçin.
4. Ekrandaki şirket adı ve rol bilgisini kontrol edin. İşlem yapmadan önce doğru şirketin seçili olduğundan emin olun.
5. İşiniz bittiğinde hesap menüsünden güvenli biçimde çıkış yapın.

Şirket Sahibi yalnızca hesabına atanmış şirketlere geçebilir. Tedarikçi hesabı ise bağlı olduğu kendi şirket ve tedarikçi kapsamıyla sınırlıdır.

Giriş sayfasındaki **Amir olarak giriş yapın** bağlantısı Amir oturumunu açar. Amir kullanıcı adı personelin T.C. Kimlik No bilgisidir; T.C. Kimlik No tek başına giriş için yeterli değildir. Şirket yöneticisi tarafından oluşturulan ayrı bir parola gerekir. Uygulama şu anda ek parola uzunluğu kuralı uygulamaz.

## 3. Gösterge panelini okuma

Gösterge paneli, seçili şirkete göre özetleri ve yaklaşan etkinlikleri gösterir:

- **Toplam personel, Güvenlik ve ÖGG:** Şirket kapsamındaki personel dağılımı.
- **Tedarikçiler:** Şirkete bağlı tedarikçi sayısı ve ilgili dağılım.
- **Şirket dağılımı ve Tedarikçi dağılımı:** Tedarikçi hesabı dışında, görünen kapsamdaki personel ve etkinlik özetleri.
- **Yaklaşan Etkinlikler:** Planlı etkinliklerin tarih, şirket ve tedarikçi bilgisi.
- **Atama Açıkları:** Etkinlik ihtiyacı ile onaylanmış personel arasındaki farkı izleme.

Kartlar kullanıcının yetkisine göre farklılaşabilir. Gösterge panelindeki sayılar operasyonel özettir; ayrıntı için ilgili menü sayfasını açın.

## 4. Şirket ve hesap yönetimi

Şirket ve genel kullanıcı hesabı yönetimi **Süper Yönetici** yetkisi gerektirir. Şirket Sahibi kendi şirket operasyonlarını ve Amir giriş hesaplarını yönetebilir; şirket sahibi veya tedarikçi rollerini oluşturamaz. Tedarikçi hesabı yalnızca bir tedarikçi kaydına bağlı olarak tanımlanır.

### Şirket ekleme

1. **Şirketler** menüsünü açın ve **Şirket ekle** seçeneğini kullanın.
2. Şirket adı, kodu ve istenen diğer şirket bilgilerini girin.
3. **Kaydet** seçeneğine basın.
4. Şirket listesinden yeni kaydı bulun, ayrıntılarını açın ve doğru şirket olduğunu kontrol edin.
5. Operasyonlara başlamak için şirketi çalışma alanı olarak seçin.

Şirketi devre dışı bırakmak veriyi tutar ancak kullanıcıların operasyonel erişimini etkiler. Şirketi kalıcı silmek ilişkili operasyon kayıtlarını etkileyebilir; kalıcı silme onayındaki etki özetini dikkatle inceleyin.

### Şirket sahibi hesabı oluşturma

1. Üst menüden **Hesaplar** bölümünü açın.
2. **Hesap oluştur** düğmesine basın. Bu ekran şirket sahibi hesabı oluşturur; tedarikçi giriş hesabı oluşturmak için tedarikçi formu kullanılır.
3. Ad, soyad, kullanıcı adı, e-posta, isteğe bağlı telefon ve ilk şifre alanlarını doldurun.
4. **Hesabı oluştur** seçeneğine basın. Yeni şirket sahibi hesabı henüz bir şirkete bağlı değilse giriş yapamaz; hesap listesinde şirket bağlantısı bekliyor olarak görünür.
5. Hesabı bir şirkete bağlama adımlarını uygulayıp erişimi etkinleştirin.
6. İlk şifreyi hesap sahibine güvenli bir kanaldan iletin; kılavuza, ekran görüntüsüne veya ortak bir belgeye yazmayın.

### Şirket sahibi hesabına şirket erişimi verme

İki yoldan birini kullanabilirsiniz:

- **Hesaplar → Şirket erişimleri:** Hesap satırında şirket sahibi erişimlerini yönetin.
- **Şirketler → ilgili şirket → Şirket erişimlerini yönet:** Bu şirkete erişecek mevcut şirket sahibi hesabını seçin.

Her iki akışta da:

1. Hesabı veya şirketi arayıp doğru kaydı seçin.
2. Eklenecek şirketi gözden geçirme adımında doğrulayın.
3. Onay ekranında hesap adı ve şirket adını kontrol edin.
4. **Erişim ver** ile işlemi onaylayın.
5. Kullanıcıya hesabından çıkıp tekrar girmesini ve doğru şirketi seçmesini bildirin.

Erişim, kullanıcı hesabından ayrı bir şirket üyeliğidir. Erişimi kaldırmak kullanıcı hesabını silmez. Son şirket erişimi kaldırılırsa hesap otomatik olarak pasifleştirilir.

### Hesapları bulma, düzenleme ve güvenliğini yönetme

**Hesaplar** listesindeki arama alanını kullanıcı adı, ad, e-posta, şirket veya tedarikçiyle kullanabilirsiniz. Hesap satırındaki işlemler:

- **Ayrıntılar:** Hesap rolünü, etkinlik durumunu ve şirket/tedarikçi bağlantılarını kontrol edin.
- **Düzenle:** Ad, soyad, kullanıcı adı, e-posta, telefon ve etkin/pasif durumunu güncelleyin. Kaydetmeden önce değişiklik özeti açılır; bilgileri kontrol edip açıkça onaylayın. Rol ve şirket/tedarikçi bağlantısı bu formdan değiştirilmez.
- **Şifreyi değiştir:** Yeni şifreyi belirleyin ve doğrulama alanlarına aynı değeri girin. Şifreyi gösteren veya yeniden görüntüleyen bir ekran yoktur; kullanıcıya güvenli şekilde iletin.
- **Şirket erişimleri:** Şirket sahibi hesaplarının erişimlerini ayrı olarak ekleyip kaldırın.
- **Hesabı sil:** Giriş hesabını kalıcı olarak siler; erişim kaldırma ile aynı işlem değildir. Onay ekranındaki sonucu incelemeden devam etmeyin.

İşlem sonrası hesap türünü ve bağlı olduğu şirket/tedarikçi bilgisini tekrar kontrol edin. Süper Yönetici hesabı normal hesap silme akışıyla silinemez.

### Amir giriş hesabı oluşturma ve yönetme

Şirket Sahibi kendi erişimindeki şirketlerde, Süper Yönetici ise seçili şirket çalışma alanında Amir hesabı yönetebilir:

1. Doğru şirket çalışma alanını seçin ve **Amirler** menüsünü açın.
2. Yalnızca o şirketteki aktif personel listelenir. Amir olacak kişiyi seçin.
3. İlk şifreyi belirleyin ve tekrar girerek doğrulayın. Şifre boş bırakılamaz; ek uzunluk kuralı yoktur.
4. **Amir hesabı oluştur** seçeneğine basın. Kullanıcı adı personelin T.C. Kimlik No bilgisidir; ayrıca e-posta adresi istenmez.
5. İlk şifreyi amire güvenli bir kanaldan iletin. Sistem parolayı e-posta ile göndermez veya sonradan göstermez.
6. Hesap listesinden gerektiğinde parolayı yenileyin ya da hesabı devre dışı bırakın. Bu işlemler denetim kayıtlarına yazılır.

Amirler giriş sayfasındaki **Amir olarak giriş yapın** bağlantısını kullanır. T.C. Kimlik No tek başına giriş bilgisi değildir; ayrı parola gerekir. Girişten sonra yalnızca kendilerine yetki verilen etkinlikleri ve etkinliğe özel bölgeleri görürler.

## 5. Tedarikçileri yönetme

Şirket Sahibi, yalnızca aktif şirketine bağlı tedarikçileri yönetir. Süper Yönetici şirket seçimine göre tedarikçi kapsamını görüntüler.

### Tedarikçi ekleme

1. **Tedarikçiler** menüsünü açın.
2. **Tedarikçi Ekle** düğmesini seçin.
3. Tedarikçi adı, iletişim e-postası ve telefon gibi bilgileri girin; şirket sahibi hesabında şirket aktif çalışma alanından alınır.
4. Tedarikçi giriş hesabını aynı akışta oluşturmak için kullanıcı adı, hesap e-postası ve ilk şifreyi girin.
5. Daha önce **Hesaplar** bölümünde hazırlanmış, tedarikçiye bağlanmamış bekleyen hesap varsa onu arayıp seçin. Bekleyen hesabı seçtiğinizde yeni hesap alanlarını boş bırakın.
6. **Tedarikçiyi Kaydet** düğmesine basın.
7. Tedarikçi listesinde tedarikçi adını ve bağlı giriş hesabını doğrulayın. Yeni tedarikçi kullanıcısına ilk şifreyi güvenli biçimde iletin.

### Tedarikçiyi bulma veya güncelleme

- Arama alanında tedarikçi adı, şirket, e-posta veya hesap bilgisiyle arayın.
- **Ayrıntılar** ile ilişkili hesapları ve kayıt bilgilerini kontrol edin.
- **Düzenle** ile gerekli alanları güncelleyin; varsa kaydetme öncesi özet penceresini inceleyin.
- Tedarikçinin hesabı ayrı bir kullanıcı girişi olsa da bu düzenleme akışında tedarikçi adı ve hesap bağlantısını birlikte görebilirsiniz. Şifre değiştirilmeyecekse şifre alanını boş bırakın.
- Tedarikçi silme işlemi bağlı personel, hesap, talepler ve atamalar gibi verileri etkileyebilir. Silme onay ekranındaki etki özetini dikkatle incelemeden onaylamayın.

## 6. Personel havuzunu yönetme

Personel havuzu şirket personelini ve şirkete bağlı tedarikçilerin personelini tek ekranda ilişki bilgisiyle gösterir. Ayrı bir personel numarası alanı yoktur.

### Personel ekleme

1. **Personeller** menüsünü açın.
2. **Personel Ekle** düğmesine basın.
3. T.C. kimlik numarası, ad ve soyadı girin. Personel türünü **Güvenlik** veya **ÖGG** olarak seçin; doğum tarihi, cinsiyet ve iletişim alanlarını gerekiyorsa doldurun.
4. ÖGG personelinde **ÖGG Kimlik Kartı No** zorunludur. Yelek numarası personel kaydında tutulmaz; etkinlik atamasında, o etkinlikte verilen yelek için girilir.
5. Banka ve IBAN ödeme çıktısı için kullanılabilir. Kayıt doğrudan şirkete ait olacaksa şirket personeli olarak bırakın. Tedarikçi personeliyse doğru tedarikçiyi seçin.
6. **Kaydet** düğmesine basın ve yeni kaydın listede doğru bağlılıkla göründüğünü kontrol edin.

Tedarikçi hesabı yalnızca kendi personel kayıtlarını yönetebilir. Personel kayıtları giriş hesabı değildir.

### Personeli bulma, düzenleme ve durumunu yönetme

- Ad, soyad, T.C. kimlik numarası veya ÖGG kart numarasıyla arama yapın.
- Personel türü, durum ve bağlılık filtrelerini seçip **Filtrele** düğmesine basın.
- Filtrelerden vazgeçmek için **Filtreleri Temizle** seçeneğini kullanın.
- İlgili satırda **Düzenle** seçeneğini kullanın. Kaydetmeden önce şirket/tedarikçi, personel türü ve güncellenen bilgileri kontrol edin.
- Çalışmayan personeli kaldırmak için mümkünse durumunu pasif veya arşivlenmiş yapın; bu, geçmiş atama kayıtlarının izlenebilirliğini korur.
- Ataması bulunan personel kaydı doğrudan silinemeyebilir. Önce etkinlik atamalarını ve geçmişi kontrol edin. Etkinlikten atamayı kaldırmak personel havuzundaki kişiyi silmez.

### Arama, filtreleme ve dışa aktarma

- Arama ve filtreleme birlikte kullanılabilir; filtreleri uyguladıktan sonra sonuç listesini kontrol edin.
- Excel'e aktarma, mevcut arama ve filtre kapsamını kullanabilir. Dışarı aktarmadan önce şirket ve tedarikçi kapsamını doğrulayın.
- İndirilen dosyada kimlik ve iletişim bilgileri bulunabileceğinden dosyayı güvenli saklayın ve yalnızca yetkili kişilerle paylaşın.

### Excel ile içe aktarma

1. **Excel'den İçe Aktar** ekranını açıp şablonu indirin.
2. Şablondaki sütunları koruyun; her satıra bir personel girin.
3. Şirket/tedarikçi havuzunu ve varsayılan personel türünü seçin.
4. Dosyayı yükleyip doğrulama önizlemesini kontrol edin.
5. Hatalı veya yinelenen satırları düzelttikten sonra aynı dosyayı yeniden seçerek aktarımı onaylayın.

Doğum tarihi isteğe bağlıdır. Yelek numarası etkinliğe atanmış personelin atama satırında elle girilir; başındaki sıfırlar korunur. Personel türü ÖGG ise ÖGG kimlik kartı numarası zorunludur; Güvenlik personeli için bu alanı boş bırakın.

Dosya en fazla 5 MB ve 5.000 satır olabilir. Aynı T.C. kimlik numarası ikinci kez içe aktarılmaz. Gerçek kişisel verileri demo ortamında veya onaysız paylaşım kanallarında kullanmayın.

## 7. Etkinlik ve atamaları yönetme

### Etkinlik oluşturma

1. **Etkinlikler** menüsünden **Etkinlik Oluştur** seçeneğini açın.
2. Etkinlik adı, şirket, konum, açıklama ve etkinlik gününü doldurun. Etkinlik bölgelerini her satıra bir ad yazarak ekleyin; bölgeler yalnızca o etkinliğe kaydedilir. Etkinliklerde saat aralığı tutulmaz.
3. Gerekiyorsa hizmet verecek tedarikçileri arayıp seçin. Şirket sahibi için şirket kapsamı sabittir; tedarikçiler etkinlik oluşturamaz.
4. Seçtiğiniz her tedarikçinin altında görünen **Asıl kişi üst sınırı** ve **Yedek kişi üst sınırı** alanlarını isteğe göre doldurun. Boş alan sınırsız, 0 ise yeni personel sunumuna kapalı kontenjan anlamına gelir.
5. **Personel gereksinimleri** bölümünde Güvenlik ve ÖGG türleri için gereken kişi sayılarını girin.
6. Etkinlik hazırsa **Planla ve kaydet**, daha sonra tamamlanacaksa **Taslak olarak kaydet** düğmesini seçin.
7. Planlanmış/taslak sekmesinde yeni kaydı açıp şirketi, etkinlik gününü, tedarikçileri ve kişi ihtiyacını doğrulayın.

Planlananlar ve Taslaklar ayrı sekmelerde bulunur. Tamamlanan, ertelenen ve iptal edilen kayıtlar arşiv alanında görüntülenir.

### Etkinliği güncelleme ve durumunu takip etme

1. **Planlananlar** veya **Taslaklar** sekmesinde etkinliği bulun.
2. Satırın işlem menüsünden **Önizle** veya **Düzenle** seçeneğini açın. Taslak bir etkinliği düzenleyip **Planlamaya al** ile yayımlayabilirsiniz.
3. Tarih, personel ihtiyacı veya tedarikçi değişikliğini kaydetmeden önce gözden geçirin.
4. İhtiyaca göre etkinlik menüsündeki **Ertele**, **İptal et** veya **Tamamla** akışını kullanın. Erteleme/iptal gerekçesini girin. Tamamlama sırasında gelir ve yoklama/atama kontrolleri istenir.
5. Sonuçlanan kayıtları **Etkinlik arşivi** içindeki Tamamlanan, Ertelenen veya İptal edilen sekmelerinden bulun.

Tamamlanan etkinlikler finansal kayıt ve geçmiş operasyon oluşturur; tamamlandıktan sonra atama ve temel etkinlik alanları değiştirilemez. Güvenlik ve ÖGG günlük ücretleri yalnızca “Geldi” işaretli personel için hesaplanır. Amir günlük ücreti, etkinlikte en az bir bölgeye yetkilendirilmiş her Amir için bir kez hesaplanır. Kalıcı silme işlemi geçmiş verileri etkileyebilir; mümkünse silme yerine doğru durum akışını kullanın.

### Personel atama

Atamalar ekranı sekmelerden oluşur: **İçerik** (ihtiyaç ve katılım özeti), **Tedarikçi Listesi**, **Tüm Personel Listesi** (şirket yetkilisi), **Kayıt Listesi** ve kilitli olmayan etkinliklerde **Amir Listesi**.

1. İlgili etkinlik satırında **Atamalar** seçeneğini açın.
2. **Tüm Personel Listesi** sekmesinde personeli tek tek eklemek için **Tekli personel ekle**, çoklu seçim için **Toplu personel ekle** düğmesini seçin.
3. T.C. kimlik numarası, ad, soyad veya tedarikçiyle arayın; tedarikçi filtresini kullanın.
4. Tekli atamada etkinlik görev türünü kontrol edin. ÖGG personeli bu etkinlikte Güvenlik olarak görevlendirilebilir; Güvenlik personeli ÖGG yapılamaz. Toplu atamada **Seçilen Personelleri İncele** adımında türü kişi bazında belirleyin.
5. Toplu atamada uygun personelleri işaretleyin. Görünenleri topluca seçerken seçili kişi sayısını ve listeyi mutlaka kontrol edin.
6. **Seçilen Personelleri İncele** adımında etkinliği, personelleri ve notları gözden geçirin.
7. Son onayı verdikten sonra atama tablosunda onay durumunu ve onaylı/toplam ihtiyaç sayaçlarını doğrulayın.

### Tedarikçi asıl/yedek kontenjanı

Kontenjanları etkinlik oluştururken veya etkinliği düzenlerken, tedarikçi seçiminin altındaki alanlardan belirleyebilirsiniz. Atama ekranında geniş bir ayar paneli yerine **Tedarikçi kontenjanları** düğmesini kullanın:

1. Düğme, her tedarikçinin asıl/yedek kullanımını ve sınırını gösteren pencereyi açar.
2. İlgili tedarikçinin yanındaki kalem düğmesine basarak yalnızca o tedarikçinin sınırlarını düzenleyin.
3. Yeni değerleri kaydedin. Etkinlik oluşturma/düzenleme ekranında da aynı sınırları daha sonra değiştirebilirsiniz.
4. Kullanım sayacı bekleyen ve onaylanmış kayıtları gösterir. Asıl personel sunumları asıl sınırdan, devamsızlık için oluşturulan tedarikçi yedek talepleri ve yedek atamalar yedek sınırından düşer.

Alanı boş bırakmak o tür için sınır olmadığı anlamına gelir; sıfır girilirse yeni sunum/talep engellenir. Sınır mevcut kullanımdan düşük kaydedilirse kullanım gösterilir ve yeni sunumlar/onaylar kullanım sınır içine inene kadar engellenir. Tamamlanmış, ertelenmiş ve iptal edilmiş etkinliklerde kontenjan düzenlenemez.

### Amirleri etkinlik bölgelerine yetkilendirme

Şirket Sahibi, kendi şirketindeki; Süper Yönetici ise seçili şirket kapsamındaki etkinliklerde Amir bölge yetkilerini yönetebilir:

1. Atamalar ekranında **Amir bölge yetkileri** seçeneğini açın.
2. Her Amir için yalnızca o etkinliğe ait bölgeleri işaretleyin. Seçim kaydedildiğinde o Amir'in aynı etkinlikteki önceki bölge yetkileri bu seçimle değiştirilir; tüm seçimleri kaldırmak erişimi geri alır.
3. Etkinlikte bölge yoksa önce etkinliği düzenleyerek bölge adlarını ekleyin. Yalnızca aktif personel kaydına bağlı ve aktif Amir hesapları listelenir.
4. Yetki verilen Amir giriş yaptığında sadece yetkili etkinliklerini/bölgelerini görür; yeni personel ekleyemez ve izni olmayan bölgeyi açamaz.

Amir etkinlik ekranında yalnızca etkinliğe onaylanmış personellerden bölgeye yerleştirilmemiş olanları veya kendi bölgelerinde bulunanları görür. Listede olmayan bekleyen/ret edilmiş atamalar ve başka Amirlerin yetkili olduğu bölgelerdeki personel bu ekrandan değiştirilemez. Amir sadece kendi yetkili bölgelerinden birini seçebilir veya uygun personeli bölge atanmamış duruma alabilir. Şirket yetkilileri de atama tablosunda güncel bölgeyi görür.

### Atamaları ve bekleyen önerileri yönetme

- Atama listesindeki **Onay Bekleyen** sayacını açarak tedarikçi önerilerini inceleyin. Doğru personeli seçip tek tek veya toplu onaylayın; reddedilen öneri atanmış personel olmaz.
- Atama satırındaki **Etkinlik görev türü** alanı, personelin bu etkinlikte Güvenlik mi ÖGG mü sayılacağını belirler. ÖGG personeli Güvenlik olarak değiştirilebilir; Güvenlik personeli ÖGG olarak görevlendirilemez.
- Yoklama sırasında etkinlik görev türünü yeniden kontrol edip düzeltebilirsiniz. Etkinlik raporları, tür bazlı ihtiyaç ve gider hesapları ile ödeme tutarı etkinlikteki görev türünü kullanır. Etkinlikte ÖGG olarak görev yapan personele telsiz verilemez.
- Atama satırından yoklamayı, gerektiğinde yedek personel işlemini ve izin verilen diğer durum güncellemelerini yapın.
- Atama satırından personeli etkinlikten çıkarmak ilgili atama kaydını etkiler; personel havuzunu silmez.
- **Kayıt Listesi** sekmesindeki Excel grubu üç dosya üretir. **MMS Excel'e Aktar** firma, maç ve tarih başlığıyla Amir ve ÖGG satırlarını yazar; poliçe no, il ve telefon boş kalır. **Emniyet Listesi** kimlik, ad, ÖGG kartı, yelek ve görev yeri sütunlarını doldurur; ÖGG bitiş tarihi boştur. **Tüm Liste Excel'e Aktar** etkinlik adı ve tarihiyle aynı Amir/ÖGG kapsamını yazar. Dosyalar onaylı ve onay bekleyen atamaları içerir; tedarikçisi geri çeken kayıtlar dışarıda kalır.
- **Tüm Personel Listesi** sekmesinde **Excel Yükle**, çalışma kitabındaki T.C. kimlik numaralarından mevcut personeli etkinliğe ekler. Yeni personel kaydı oluşturmaz. **Excel'e Aktar** aynı Amir/ÖGG listesini indirir.
- **Kayıt Listesi**ndeki **Görev** filtresi Amir, ÖGG ve Güvenlik kayıtlarını ayırır. **Telsizleri Yönet** verilen telsizleri ve teslimleri izler. ÖGG olarak görev yapan personele telsiz verilemez.
- Tedarikçi personel önerisi gönderdiğinde öneri onay bekler; şirket yetkilisi onaylamadan etkinliğe kesin atama yapılmaz.
- Uygun olmayan, pasif, aynı takvim gününde başka etkinliğe atanmış veya farklı şirket/tedarikçi kapsamındaki kayıtlar reddedilebilir. İhtiyaç sayısı aşılırsa uygulama uyarı gösterir.
- Tamamlanmış, iptal edilmiş veya ertelenmiş etkinliklerde atama işlemleri kısıtlanır.

## 8. Personel talebi ve tedarikçi yanıtı

Talep akışı şirket ve tedarikçi hesapları arasında personel ihtiyacını, yanıtları ve öneri onaylarını takip eder.

### Şirket yetkilisi: talep oluşturma

1. **Talepler** menüsünü açın ve **Talep Oluştur** düğmesini seçin.
2. Aktif şirketinizin tedarikçisini ve o tedarikçiye atanmış etkinliği seçin.
3. Tarih, konum, Güvenlik/ÖGG sayısı ve açıklamayı girin.
4. Talep özetini kontrol edip gönderin.
5. Tedarikçi yanıtını ve personel önerilerini aynı talep ekranından takip edin.

Tamamlanmış, ertelenmiş veya iptal edilmiş etkinlikler yeni talep oluşturma seçeneklerinde yer almaz.

### Tedarikçi: yanıt ve personel önerisi

1. **Talepler** ekranında kendi tedarikçinize gelen talebi açın.
2. Talebi kabul edin veya reddedin.
3. Kabul edilen talep için yalnızca kendi aktif ve uygun personelinizden, istenen tür ve kalan sayı sınırları içinde seçim yapın.
4. Personel önerisini gönderin. Öneri şirket yetkilisinin onayına gider; gönderilmesi personeli etkinliğe otomatik olarak atamaz.

### Şirket yetkilisi: önerileri inceleme

1. Talepteki bekleyen personel önerilerini açın.
2. Her öneride personelin kimliğini, personel türünü ve tedarikçi bağlantısını kontrol edin.
3. Önerileri tek tek veya seçili kayıtları topluca onaylayın.
4. Onaylanan personelin etkinlik atama listesine eklendiğini doğrulayın.

Talep, istenen personel önerileri onaylanıp etkinliğe atandığında tamamlanabilir. Bir talebi iptal etmek, bekleyen önerileri ve talep üzerinden oluşturulan atamaları etkileyebilir; onaydan önce ekrandaki bilgileri okuyun.

## 9. Yoklama ve QR akışı

### Manuel yoklama

1. Etkinlikte **Atamalar** ekranının **Kayıt Listesi** sekmesini açın.
2. **Geldi** kaydı verilecek personel ÖGG ise hangi görev türüyle geldiğini (**ÖGG** veya **Güvenlik**) seçin. Güvenlik personeli ÖGG olarak seçilemez.
3. **Durum seçin** alanından **Geldi** veya **Gelmedi** durumunu seçin.
4. **Katılımı Kaydet** düğmesine basın.
5. Yoklama durumunun ve görev türünün tabloda güncellendiğini doğrulayın.

Gelmeyen personel aktif atama sayısından çıkar. Gerekirse aynı türde ve uygunluk koşullarını sağlayan bir yedek personel atanabilir.

Etkinlik önizlemesinde ve atama/yoklama sayfasında **Etkinlik katılım takibi** özeti bulunur. Görevlendirilen personel, gelenler, gelmeyenler ve yoklaması henüz girilmemiş personeller tedarikçi ve şirket personeli bazında; Güvenlik ve ÖGG kırılımıyla gösterilir. Onay bekleyen atamalar ayrı sayılır. Özet, açık sayfalarda yaklaşık iki saniyede bir yenilenerek başka kullanıcıların kaydettiği yoklama değişikliklerini de yansıtır. Tedarikçi hesapları yalnızca kendi personelinin özetini görür.

### Personel QR portalı

Personel, kendisine bildirilen `/qr-create/` adresini telefonundan veya bilgisayarından açar:

1. T.C. kimlik numarasını girip **Güvenli Şekilde Devam Et** düğmesine basar.
2. İstenen telefon bilgisini personel kaydındaki numarayla eşleştirir.
3. Etkinlik gününde uygun etkinliği seçip katılım QR kodunu oluşturur ve kodu yoklama yetkilisine gösterir. QR yoklama etkinliğin takvim günü boyunca kullanılabilir.

Portal SMS göndermez; telefon bilgisinin kayıtla eşleşmesi SMS doğrulaması değildir. Ekran görüntüsünde kişisel bilgi veya üretilmiş QR kodu paylaşmayın.

### Yetkiliyle QR yoklaması

1. Etkinlikte **Atamalar → Kayıt Listesi → QR Yoklama** penceresini açın. Etkinlik tamamlanmış, ertelenmiş veya iptal edilmişse düğme **QR Yoklama kapalı** olarak görünür.
2. Yoklama modunu kontrol edin. Gerekiyorsa **Yönetici onaylı** veya **Otomatik** modunu seçip **Modu Kaydet** düğmesine basın.
3. Kamerayı seçin, **Kamerayı Başlat** düğmesine basın ve personelin güncel QR kodunu kameraya tutun.
4. ÖGG kayıtlı personelde etkinlik görev türünü (**ÖGG** veya **Güvenlik**) seçin. Yönetici onaylı modda tarama sonucunu ayrıca onaylayın; otomatik modda geçerli tarama yoklamayı kaydeder.
5. Sonucun doğru etkinlik ve personel için kaydedildiğini kontrol edin. Yeni bir kod okutmak için **Yeni QR Okut** seçeneğini kullanın.

QR kodu kısa süreli ve tek kullanımlıktır. Kamera erişimi için HTTPS veya yerel geliştirmede `localhost` kullanın. QR kodunu başkasına göndermeyin; daha önce okutulmuş veya süresi geçmiş kod yerine personelden yeni kod üretmesini isteyin.

### Barkod okuyucuyla Kayıt Sistemi

Etkinlik yöneticisi, barkod okuyucuyu bilgisayara klavye gibi bağlayıp personel T.C. kimlik numarasını hızlıca kaydedebilir:

1. **Atamalar → Kayıt Listesi** ekranını açıp **Kayıt Sistemi** düğmesine basın. Düğme, etkinlik kilitli değilse etkinlik gününden bağımsız görünür.
2. Barkod okuyucuyu T.C. kimlik kartına, ÖGG kimlik kartına veya ehliyet barkoduna tutun. 11 rakam tamamlanınca kayıt otomatik gönderilir; okuyucu Enter gönderiyorsa beklemeden işlenir.
3. Personel ÖGG ise etkinlikte **ÖGG** mü yoksa **Güvenlik** olarak mı geldiğini seçin. Seçim kaydı otomatik tamamlar.
4. Personelin ataması **Onay Bekliyor** durumundaysa barkod penceresinde personel/tedarikçi bilgisini kontrol edin. **Onayla ve geldi kaydet** seçimi atamayı onaylar ve katılımı birlikte kaydeder; **Atamayı reddet** seçimi öneriyi reddeder ve katılım kaydetmez. ÖGG personelinde önce etkinlik görev türünü seçin.
5. Başarılı sonuçta personelin adını, etkinlik görev türünü ve tedarikçisini kontrol edin. Mevcut onaylı atama **Geldi** olur; henüz atanmamış uygun personel etkinliğe eklenir ve **Geldi** işaretlenir. Arka arkaya okutulan kayıtlar pencerede liste halinde görünür.
6. Aynı barkod ikinci kez okutulursa sistem mevcut katılımın daha önce kaydedildiğini bildirir. Reddedilmiş/iptal edilmiş atamalar veya daha önce **Gelmedi** kaydedilen kişiler otomatik olarak yeniden etkinleştirilmez; ekrandaki durum ve yönlendirmeyi izleyin. Başka etkinliğin şirketinde kayıtlı, pasif veya bulunamayan personel kaydedilmez.

Kayıt Sistemi şirket yetkilisi/Süper Yönetici hesabıyla kullanılabilir; tamamlanmış, ertelenmiş veya iptal edilmiş etkinliklerde kullanılamaz. Personelin QR üretmesi yine yalnızca etkinlik gününde geçerlidir. Tedarikçi kontenjanı dolu olsa bile fiziksel olarak gelen personelin katılımı kaydedilir; bu durum kontenjan kullanımını aşabilir ve şirket yetkilisinin incelemesine sunulur. Onay bekleyen atama, penceredeki **Onayla ve geldi kaydet** ile onaylanıp katılımı kaydedilir. Daha önce **Gelmedi** olarak işaretlenmiş kişiler için yedek atama akışını kullanın. Barkod numarası yeni personel kaydı oluşturmaz.

## 10. Bildirimler, ödemeler ve denetim kayıtları

### Bildirimler

- Üst menüdeki zil, okunmamış bildirim sayısını gösterir.
- Bildirimler; yeni personel talepleri, talep yanıtları, tedarikçi personel sunumları ve atama onayları için oluşturulabilir.
- Zile veya **Bildirimler** sayfasına girerek kaydı açın; bağlantı varsa ilgili talep/etkinliğe yönlendirilirsiniz.
- Bildirimleri okundu işaretleme veya silme işlemini yalnızca doğru şirket/tedarikçi kapsamındayken yapın.

### Ödemeler

**Ödemeler** ekranı tamamlanmış etkinliklere dayalı ödeme dökümlerini gösterir. Güvenlik ve ÖGG için hesaplama kaydedilmiş katılım ve etkinlik gününe; Amir için etkinlikte bölge yetkisi bulunmasına ve Amir günlük ücretine bağlıdır. Aynı personel Amir olarak yetkilendirilmişse ödeme listesinde Amir ücreti tek satır olarak uygulanır. **Tüm Liste Excel'e Aktar** çıktısı **Ad, Soyad, IBAN, Ücret ve Tedarikçi** sütunlarını içerir; şirket personelinde Tedarikçi hücresi boş kalır. IBAN bilgisi olan katılımcı yoksa dosya oluşturulmaz. Dosyayı indirmeden önce etkinliği ve personel kapsamını kontrol edin; IBAN ve ödeme dosyalarını güvenli kanallarda saklayıp paylaşın.

### Denetim kayıtları

Yetkili yöneticiler **Denetim Kayıtları** ekranından kritik işlemleri inceleyebilir. Kayıtlar işlemi yapan hesabı, zamanı, nesneyi ve hassas olmayan ilgili ayrıntıları içerir. Bu ekranı personel veya ödeme verilerini dışarı aktarmak için kullanmayın.

## 11. Güvenli işlem ve sorun giderme

### Kaydetme veya filtreleme beklediğiniz gibi çalışmıyor

- Filtre alanlarını seçtikten sonra **Filtrele/Uygula** düğmesine basın.
- Beklenen şirketin üst bölümde seçili olduğunu doğrulayın.
- Tedarikçi hesaplarında yalnızca kendi kapsamınızdaki kayıtların görünmesi normaldir.
- Kaydetme onay penceresi açıldıysa bilgileri kontrol edip açıkça onaylayın; vazgeçmek için **Vazgeç/Geri dön** seçin.

### Kayıt listede görünmüyor

- Arama metnini ve filtreleri temizleyin.
- Durum sekmesini (Planlananlar/Taslaklar/Arşiv) kontrol edin.
- Şirket sahibi hesabında doğru şirketin seçili olduğundan emin olun.
- Tedarikçi hesabında kayıt şirket tarafından size atanmış olmalıdır.

### Kamera açılamıyor veya QR okunmuyor

- Siteyi HTTPS ya da `localhost` üzerinden açın ve tarayıcı kamera iznini verin.
- QR'ın güncel, doğru etkinliğe ait ve süresi geçmemiş olduğunu doğrulayın.
- Her QR tek kullanımlıdır; daha önce okutulduysa personelden yeni QR üretmesini isteyin.
- Kamera iznini açamıyorsanız manuel yoklama akışını kullanın.

### Silme veya değiştirme işlemi

- Silme işlemlerinde etki özeti ve onay penceresini okuyun.
- Personel ataması bulunan personeli doğrudan silemeyebilirsiniz; pasife alma/arşiv seçeneklerini değerlendirin.
- Emin değilseniz onayı iptal edin ve yöneticinizle doğrulayın.
- Şifre, T.C. kimlik numarası, IBAN, QR kodu veya oturum bilgilerini ekran görüntüsüyle paylaşmayın.

---

Bu kılavuz son kullanıcı iş akışlarını açıklar. Ekranların adları ve izinler dağıtım ayarlarına, hesaba ve seçili şirkete göre farklılık gösterebilir. Sistem yöneticinizin verdiği şirket içi prosedürler ve veri koruma kuralları önceliklidir.
