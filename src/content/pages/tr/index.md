---
title: "Android Açık Kalsın"
lang: tr
description: "Android'in herkesin üzerinde uygulama geliştirebileceği özgür ve açık bir platform olmasını savunuyoruz."

# localizable sections for the footer text
contact_header: "İletişim"
contact_email: "E-posta"
site_problems_header: "Sorunlar"
site_report_issues: "Site sorunlarını bildirin"
site_disclaimer: "**Yasal uyarı:** Bu site, topluluk tarafından yürütülen ve kâr amacı gütmeyen bir girişimdir. Yalnızca bilgilendirme ve eğitim amaçlıdır."
site_privacy: "**Gizlilik:** Bu site çerez kullanmaz, kullanıcıları takip etmez ve kayıt tutmaz."
site_copyright: "**Telif hakkı:** Yok. Bu çalışma şununla işaretlenmiştir:"

open_letter_cta: "Android Geliştirici Doğrulama programına karşı açık mektubumuzu okuyun"
open_letter_header: "Açık Mektup"
open_letter_description: "Android'in özgür ve açık bir platform olarak kalmasını savunan açık mektup."
---

Google, Ağustos 2025'te 2027'den itibaren Android platformu için uygulama
geliştirmenin, önce Google'a merkezi olarak kayıt olmadan artık mümkün
olmayacağını [duyurdu](https://developer.android.com/developer-verification).
Bu kayıt şunları gerektirecek:

- Google'a ücret ödemek
{:.li-list .li-money}
- Google'ın Şartlar ve Koşullarını kabul etmek
{:.li-list .li-terms}
- Resmî kimlik belgesi sunmak
{:.li-list .li-id}
- Geliştiricinin özel imzalama anahtarına sahip olduğunu gösteren kanıtı yüklemek
{:.li-list .li-signing}
- Mevcut ve gelecekteki tüm uygulama kimliklerini listelemek
{:.li-list .li-appids}

## Bu, haklarınız için ne anlama geliyor

➤ **Tüketici** olarak siz, Android cihazınızı Google'ın bunun açık bir bilgisayar platformu olduğu ve üzerinde istediğiniz yazılımı çalıştırabileceğiniz sözüne güvenerek satın aldınız. Oysa Google 2027'den itibaren, rızanız olmadan işletim sisteminize bu hakkı geri dönülmez biçimde ortadan kaldıran bir güncelleme gönderecek ve hangi yazılıma güvenmenize izin verileceği konusunda sizi kendi takdirine mahkûm edecek.

➤ **Geliştirici** olarak siz, bir uygulama geliştirip önce Google'ın onayını almadan arkadaşlarınızla, ailenizle ve topluluğunuzla doğrudan paylaşamayacaksınız. Android'in vaadi ve kendisini iPhone'dan ayırmak için kullandığı pazarlama avantajı her zaman "açık" olmasıydı. Ancak Google, Android ekosistemi üzerinde yeterince denetim kurduğunu ve düzenleyicileri de yeterince etkisi altına aldığını düşünüyor olmalı ki bu ilkeyi artık pervasızca ve hiçbir yaptırımla karşılaşmadan bir kenara atabiliyor.

➤ **Devlet** olarak siz, vatandaşlarınızın haklarını ve kendi dijital egemenliğinizi, otoriter rejimlerin hoşlarına gitmeyen tamamen yasal uygulamaları kaldırma yönündeki yargı dışı taleplerine uymuş bir geçmişe sahip bir şirkete devrediyorsunuz. İşletmelerinizin ve kamu kurumlarınızın işleyişi için kritik olan yazılımlar, uzaktaki ve hesap vermeyen bir şirketin şeffaf olmayan keyfine kalacak.

<div class="callout-warning">

### Güncelleme: Google "gelişmiş akışı" açıkladı ve bu bir çözüm değil

19 Mart 2026'da Google, kilitleme yürürlüğe girdikten sonra "ileri düzey kullanıcıların" doğrulanmamış geliştiricilerin uygulamalarını yükleyebilmesi için tasarlanan "gelişmiş akış" mekanizmasının [ayrıntılarını yayımladı](https://android-developers.googleblog.com/2026/03/android-developer-verification.html). Süreç şöyle işliyor:

1. _Telefon hakkında_ bölümündeki yazılım derleme numarasına **yedi kez** dokunarak [Geliştirici Modunu](https://www.android.com/intl/en_uk/articles/enable-android-developer-settings/) açın
1. Ayarlar > Sistem bölümünde Geliştirici Seçenekleri'ni açın ve "Doğrulanmamış paketlere izin ver" seçeneğine kadar aşağı kaydırın.
1. Anahtarı açın ve baskı altında olmadığınızı onaylamanızı isteyen korkutucu uyarı ekranını yanıtlayın
1. Cihazınızın kilit açma PIN'ini veya şifresini girin
1. Cihazınızı yeniden başlatın
1. **24 saat bekleyin**
1. Güvenlik bekleme süresi dolunca _doğrulanmamış paketler_ menüsüne geri dönün
1. Ek korkutucu uyarı ekranlarını geçip "Geçici olarak izin ver" (yedi gün) ya da "Süresiz izin ver" seçeneğini seçin.
1. Bir sonraki korkutucu uyarı ekranında riskleri anladığınızı onaylayın.
1. Artık paket yükleyicide "Yine de yükle" seçeneğine dokunarak doğrulanmamış paketleri cihaza yükleyebilirsiniz.

Bu akışın tamamı Android işletim sistemi üzerinden değil, Google Play Hizmetleri üzerinden sunuluyor. Yani Google bunu işletim sistemi güncellemesine ve kullanıcı onayına gerek kalmadan istediği an değiştirebilir, kısıtlayabilir ya da tamamen kaldırabilir.

Tutumumuz değişmedi: Kilitleme 2027'de yürürlüğe girdiğinde kayıtlı olmayan geliştiricilerin **tüm** uygulamaları **engellenecek**.

</div>


## Nasıl yardımcı olabilirsiniz {#help}

### Geliştiriciler: Direnin ve reddedin {#developers}

Bir uygulama geliştiricisiyseniz erken erişim programına _**kayıt olmayın**_, kimlik doğrulaması yapmayın ve Android Developer Console davetlerini kabul etmeyin. Gelen davetlere endişelerinizi ve itirazlarınızı sıralayan (kibar) bir yanıt verin.

—— _Bu ele geçirme planı ancak geliştiricilerin boyun eğip teslim olmasıyla başarıya ulaşabilir._ ——

Diğer uygulama geliştiricilerini ve kuruluşları programa kaydolmaktan vazgeçirin. Mesajı yaymak için topluluk forumlarını, sosyal medyayı ve blog yazılarını kullanın. Uygulamanızın kullanıcılarını bilgilendirmek için kodunuza [FreeDroidWarn kütüphanesini](https://github.com/woheller69/FreeDroidWarn) ekleyin. Bir web siteniz varsa sayfanızın en üstüne [geri sayım banner'ını eklemeyi](/banner) düşünün.

Vicdan sahibi bir Google çalışanı ya da yükleniciyseniz ve program hakkında planlanan teknik ayrıntılar veya programın diğer gerekçeleri gibi ek bilgilere sahipseniz, lütfen _iş için kullanmadığınız_ bir cihazdan ve _Gmail olmayan_ bir hesaptan [tips@keepandroidopen.org](mailto:tips@keepandroidopen.org) adresine yazın. Bilgileriniz kesinlikle gizli tutulacaktır.

### Herkes: Sesinizi duyurun {#everyone}

- Android cihazlarınıza [F-Droid kurun](https://f-droid.org). Alternatif uygulama mağazalarını kullanan insan sayısı arttıkça onları devre dışı bırakmak da o kadar zorlaşır.
- Google'ın [Android geliştirici doğrulama gereksinimleri anketi](https://docs.google.com/forms/d/e/1FAIpQLSfN3UQeNspQsZCO2ITkdzMxv81rJDEGGjO-UIDDY28Rz_GEVA/viewform?pli=1) aracılığıyla görüşlerinizi doğrudan Google'a iletin.
- Sosyal medyada ve blog yazılarınızda sesinizi duyurun ve <https://keepandroidopen.org> adresine bağlantı verin.
- Sahte gündemle mücadele edin: Topluluk forumlarında ve sosyal medyada bu politikayı destekleyen şüpheli paylaşımlarla (“Ama aslında…”) karşılaştığınızda onlara itiraz edin ve çekinmeyin.
- [Bu sayfayı düzenleyerek](https://github.com/keepandroidopen/keepandroidopen.github.io/blob/main/src/content/pages/tr/index.md) daha fazla faydalı bilgi ekleyin ve projeye destek olun.
- [change.org kampanyasını imzalayın](https://www.change.org/p/stop-google-from-limiting-apk-file-usage/)

### Web sitesi sahipleri: Desteğinizi gösterin {#webmasters}

Tek bir `<script>` etiketiyle [geri sayım banner'ını sitenize ekleyin](/banner). Bağımlılığı yoktur, 20 dilde yerleşik çevirisi vardır ve tamamen özelleştirilebilir.
