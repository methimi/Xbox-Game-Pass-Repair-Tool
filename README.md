<div align="center">

# 🎮 Xbox Game Pass Repair Tool

### Xbox uygulaması ve PC Game Pass sorunlarını bulmaya ve gidermeye yardımcı olan bağımsız Windows aracı

🪟 Windows 10 / 11 &nbsp; • &nbsp; 🧰 Tarama ve onarım &nbsp; • &nbsp; ↩️ Geri alma desteği

<a href="https://github.com/methimi/Xbox-Game-Pass-Repair-Tool/releases/latest"><img src="https://img.shields.io/badge/Şimdi_İndirin-16a34a?style=for-the-badge&logo=github&logoColor=white" alt="Şimdi İndirin"></a>

**En güncel sürümü indirin, ZIP dosyasını bir klasöre çıkarın ve kullanmaya başlayın.**

</div>

> [!IMPORTANT]
> Bu proje Microsoft tarafından geliştirilmemiş, yayımlanmamış, desteklenmemiş veya onaylanmamıştır. Microsoft, Xbox ve Game Pass ile resmî ya da ticari bir bağlantısı yoktur.

## 👋 Bu uygulama ne işe yarar?

Xbox uygulaması açılmıyor, oyunlar indirilmiyor, Gaming Services hata veriyor veya Game Pass oyunları başlamıyorsa sorunun kaynağını bulmak zor olabilir.

Xbox Game Pass Repair Tool, ilgili Windows bileşenlerini tek tek kontrol eder, sonuçları anlaşılır bir dille gösterir ve güvenle uygulanabilecek çözümleri kullanıcı onayına sunar.

Uygulama özellikle şu alanlara bakar:

| | Kontrol edilen alan | Örnek sorunlar |
|---|---|---|
| 🎮 | Xbox ve Game Pass | Xbox uygulaması, Gaming Services ve oyun paketleri |
| 🛍️ | Microsoft Store | İndirme, lisans, uygulama kaydı ve Store servisleri |
| 🌐 | İnternet ve ağ | DNS, proxy, VPN etkisi, bağlantı ve Microsoft sunucularına erişim |
| 🕒 | Saat ve bölge | Yanlış saat, saat dilimi, bölge ve sertifika uyuşmazlıkları |
| 🧩 | Windows bileşenleri | Windows Update, BITS, AppX ve gerekli sistem servisleri |
| 💾 | Disk ve kullanıcı profili | Boş alan, oyun diski, klasör erişimi ve profil sorunları |
| 🖥️ | Oyun altyapısı | GPU sürücüsü, DirectX, Visual C++, .NET ve shader önbelleği |
| 🛡️ | Güvenlik ve anti-cheat | Secure Boot, Defender etkisi ve yaygın anti-cheat servisleri |

## ✨ Öne çıkan özellikler

- 🔍 Xbox ve Windows bileşenlerini kapsayan ayrıntılı genel tarama
- 🧠 Birbirine bağlı bulguları birlikte değerlendiren kök neden analizi
- ✅ Kesin sorunları, bilgi notlarını ve doğrulanamayan sonuçları birbirinden ayırma
- 🛠️ Uygun sorunlar için kullanıcı onaylı otomatik onarım
- 🔁 Onarım sonrasında yeniden kontrol
- ↩️ Desteklenen işlemler için geri alma ve onarım geçmişi
- 🧾 Her taramadan sonra ayrıntılı HTML raporu
- 🌐 Canlı Xbox servis durumu sayfası
- 🛑 Devam eden taramayı güvenli biçimde iptal edebilme
- 🇹🇷 Türkçe ve 🇬🇧 İngilizce arayüz

## 🚀 Nasıl kullanılır?

### 1. İndirin ve klasöre çıkarın

GitHub üzerindeki **Releases** bölümünden en güncel ZIP paketini indirin ve tamamını bir klasöre çıkarın.

> [!WARNING]
> Yalnızca EXE dosyasını başka yere taşımayın. `XboxGamePassRepairTool.exe` ile `ApplicationFiles` klasörü birlikte kalmalıdır.

### 2. Uygulamayı açın

`XboxGamePassRepairTool.exe` dosyasına çift tıklayın. Bazı kontroller ve onarımlar için Windows yönetici izni isteyebilir.

### 3. İsterseniz hata kodunu girin

Tarama başlamadan önce hata kodu sorulur. Bu alan isteğe bağlıdır; hata kodunuz yoksa boş bırakabilirsiniz. Girilen kod uygulanacak kontrolleri veya onarımları değiştirmez.

### 4. Genel taramayı başlatın

Tarama sırasında sonuçlar sırayla ekrana gelir. Tarama devam ederken başka sayfalara geçiş kilitlenir. İsterseniz işlemi güvenli biçimde iptal edebilirsiniz.

### 5. Sonuçları inceleyin

Bulunan sorunlar otomatik onarılabilenler ve sizin yapmanız gerekenler olarak ayrılır. Onarım başlamadan önce hangi işlemlerin uygulanacağını görebilirsiniz.

### 6. Onarımı onaylayın

Uygulama izniniz olmadan önerilen onarımları başlatmaz. İşlem bittikten sonra mümkün olan kontroller yeniden çalıştırılır ve sorunun gerçekten düzelip düzelmediği doğrulanır.

## 🚦 Sonuçlar ne anlama geliyor?

| Gösterim | Anlamı |
|---|---|
| ✅ Başarılı | Kontrol edilen alan sağlıklı görünüyor. |
| ⚠️ Sorun bulundu | Güvenilir bir sorun tespit edildi. |
| ℹ️ Bilgi | Arıza olmayan fakat bilmeniz gereken bir durum var. |
| ❓ Belirsiz | Uygulama bu alanı kesin olarak doğrulayamadı. Bu sonuç “bozuk” demek değildir. |

Onarım sonuçları da dört şekilde gösterilir:

| Sonuç | Açıklama |
|---|---|
| ✅ Başarılı | İşlem tamamlandı ve mümkünse yeniden doğrulandı. |
| 🟠 Kısmi | İşlemin bir bölümü tamamlandı veya sonuç tam doğrulanamadı. |
| ⏳ Bekliyor | Yeniden başlatma, Store kurulumu ya da kullanıcı işlemi gerekiyor. |
| ❌ Başarısız | Onarım uygulanamadı veya sorun devam ediyor. |

## 🛠️ Neleri onarabilir?

Bulguya göre aşağıdakilerden bazılarını önerebilir:

- Windows saat ve saat dilimi servislerini düzeltme
- DNS önbelleğini temizleme
- Kullanıcının onayıyla proxy katmanlarını sıfırlama
- Windows Update, BITS ve Xbox servislerini yeniden yapılandırma
- Microsoft Store önbelleğini yenileme
- Xbox uygulaması ve Gaming Services kayıtlarını onarma
- Eksik uygulamalar için resmî Microsoft Store sayfasını açma
- DirectX shader önbelleğini güvenli sınırlar içinde temizleme
- Gerekli durumlarda Windows sistem dosyası onarımını çalıştırma

Her sorun otomatik olarak düzeltilemez. Hesap, abonelik, ödeme, yaş kısıtlaması, Microsoft tarafındaki servis kesintileri ve bazı kurum politikaları kullanıcı veya sistem yöneticisi müdahalesi gerektirebilir.

## ↩️ Onarım geçmişi ve geri alma

Uygulama son onarım oturumunu **Onarım Geçmişi** sayfasında saklar.

- Tam desteklenen ayarlar eski hâline getirilebilir.
- Bazı paket ve önbellek işlemleri yalnızca kısmen geri alınabilir.
- Store üzerinden tamamlanan kurulumlar veya Windows’un yaptığı sistem değişiklikleri her zaman geri alınamaz.
- Geri alma seçeneği yalnızca gerçekten kullanılabilir bir kayıt varsa gösterilir.

Geri alma işlemi yapılırsa o onarıma ait memnuniyet anketi kaldırılır.

## 🔄 Yeniden başlatma

Bazı Windows servisleri ve paket değişiklikleri ancak bilgisayar yeniden başladıktan sonra tamamlanır. Uygulama gerekli veya önerilen yeniden başlatma durumlarını ayrıca bildirir; bilgisayarı izniniz olmadan yeniden başlatmaz.

## 🔐 Gizlilik ve veri paylaşımı

> [!CAUTION]
> Bu sürüm, tarama başladığında ve tamamlandığında geliştiriciye Telegram üzerinden otomatik bildirim gönderir.

Gönderilebilecek bilgiler:

- Rastgele oluşturulan destek kimliği ve tarama kimliği
- Girildiyse hata kodu; girilmediyse kod girilmediği bilgisi
- Tarama sonuçları ve ayrıntılı HTML raporu
- Windows sürümü, donanım modeli, işlemci, bellek, ekran kartı ve sürücü bilgileri
- Disklerin genel kapasite ve boş alan bilgileri
- Ağ bağdaştırıcısı, güvenlik özellikleri ve Xbox paket sürümleri
- Kullanıcının “çözüldü” veya “çözülmedi” geri bildirimi
- “Çözülmedi” seçilirse kullanıcının kendi yazdığı açıklama

Uygulama kişisel dosyaların içeriğini, parolaları veya tarayıcı geçmişini raporlamak amacıyla toplamaz. Donanım seri numaraları, IP adresleri ve MAC adresleri sistem envanterine eklenmez. Bununla birlikte rapor ayrıntılı teknik sistem bilgisi içerir; uygulamayı kullanmadan önce bu paylaşımı kabul ettiğinizden emin olun.

## 🛡️ Güvenlik yaklaşımı

- Tarama sırasında sistem ayarları değiştirilmez.
- Onarım işlemleri başlamadan önce kullanıcı onayı istenir.
- Tek bir belirti, yeterli kanıt yoksa kesin arıza kabul edilmez.
- Okunamayan kontroller başarılı sayılmaz; “belirsiz” olarak ayrılır.
- Yüksek etkili işlemler ayrıca belirtilir.
- Korunan Windows veritabanları ve kritik oyun depolama kayıtları otomatik silinmez.
- Windows 10 üzerinde bazı yüksek etkili paket onarımları güvenlik amacıyla sınırlandırılır.

> [!TIP]
> Onarım öncesinde açık oyunları ve uygulamaları kapatın. Önemli çalışmalarınızı kaydedin ve mümkünse bir Windows geri yükleme noktası oluşturun.

## 💻 Sistem gereksinimleri

- 🪟 Windows 11 veya Windows 10 22H2
- 🌐 İnternet bağlantısı
- 🧩 Microsoft Edge WebView2 Runtime
- 👤 Bazı işlemler için yönetici yetkisi

Diğer işletim sistemleri desteklenmez. Kurum tarafından yönetilen bilgisayarlarda bazı eksik bileşenler veya kısıtlamalar bilinçli olarak uygulanmış olabilir; bu tür sistemlerde otomatik onarım yerine sistem yöneticinize danışın.

## ❓ Sık sorulan sorular

<details>
<summary><strong>Uygulama Microsoft’un resmî aracı mı?</strong></summary>

Hayır. Bu bağımsız bir üçüncü taraf projesidir ve Microsoft tarafından desteklenmez veya onaylanmaz.

</details>

<details>
<summary><strong>Tarama bilgisayarımda değişiklik yapar mı?</strong></summary>

Genel tarama yalnızca mevcut durumu kontrol eder. Değişiklik yapabilecek onarımlar ayrı bir pencerede gösterilir ve kullanıcı onayı olmadan başlatılmaz.

</details>

<details>
<summary><strong>Neden yönetici izni istiyor?</strong></summary>

Windows servislerini, sistem günlüklerini ve uygulama paketlerini doğru şekilde kontrol edebilmek; onaylanan sistem onarımlarını uygulayabilmek için yönetici yetkisi gerekebilir.

</details>

<details>
<summary><strong>“Belirsiz” sonucu bir hata mı?</strong></summary>

Hayır. Bu, kontrolün kesin bir sonuca ulaşamadığını gösterir. Kurum politikası, Windows sürümü, kapalı bir günlük veya geçici erişim sorunu buna neden olabilir.

</details>

<details>
<summary><strong>Onarım başarılı görünüyorsa sorun kesin çözülmüş müdür?</strong></summary>

Uygulama mümkün olduğunda onarım sonrasında aynı alanı yeniden kontrol eder. Ancak Store kurulumu, yeniden başlatma veya hesap işlemi gerekiyorsa sonuç “bekliyor” ya da “kısmi” kalabilir.

</details>

<details>
<summary><strong>Yalnızca EXE dosyasını kopyalayabilir miyim?</strong></summary>

Hayır. `ApplicationFiles` klasörü uygulamanın gerekli parçalarını içerir. EXE ve bu klasör birlikte taşınmalıdır.

</details>

## ⚠️ Sorumluluk reddi

Bu yazılım geliştirme aşamasındadır ve herhangi bir garanti verilmeden sunulur. Windows servisleri, ağ ayarları ve uygulama paketlerinde değişiklik yapabilen onarımlar içerir. Ekrandaki açıklamaları okuyun, anlamadığınız yüksek etkili işlemleri uygulamayın ve önemli verilerinizi yedekleyin.

Microsoft, Windows, Xbox, Xbox Game Pass ve Microsoft Store adları ve markaları ilgili hak sahiplerine aittir. Bu adların kullanımı yalnızca aracın uyumluluk alanını açıklamak içindir.

---

<div align="center">

🎮 **Sorunu bul • Güvenli seçeneği değerlendir • Sonucu doğrula**

</div>
