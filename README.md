# 20 STAR + 5 FORKDA PAYLAŞIYORUM!
# BEN DE BIRAZ SABIRSIZLANDIM VE PROJE HAKKINDA AZICIK BIR SPOILER GECEYIM DEDIM:

* Veritabanında 3 farklı veriyi bilgilendiriyor. Bunlar; `silinen rol/kanal`, `timeoutlu (<VeriYedeklemeSüresi> saatte güncellenen`, `komutla aldığınız kalıcı` verilerdir. Bu sistemi şu ana kadar hiçbir botçu ve botta görmedim, o yüzden şimdi biri çıkıp da bu altyapı/fikir bana ait diyip üzerimden prim kasmaya çalışmasın. Bu projeyi şu anda 19.02.2022 saat 11.22'de düzenliyorum. Projeyi ise 5 gün önce yani 14.02.2022 tarihinde yükledim.

# Veritabanımdaki 3 farklı veri ne işime yarayacak?

* Arkadaşlar belki kodlari inceliyorsunuzdur bilmiyorum ama ben baktığım zaman bazı/çoğu altyapıların tek bir veri tutucusu yani güncellenen veritabanı var, bir rol/kanal silindiğinde o veri güncellendikten sonra silinen rol/kanal da verilerden siliniyor. Sonra aptal botçu kurmaya çalıştığı zaman hazır altyapı elinde patlıyor ve adı patlağa çıkıyor. Bunu engellemek için 3 farklı veri tutucu koydurdum. Bu sistemi kendi yeni database botumda da çalıştırıyorum ama siktiğimin discord'unu saldığım için hiçbir sunucuda kullanmıyorum.

* Tüm verileri komut ile çekiyorsunuz. Ayrıca 3 farklı veri için veritabanı hızının yavaşlamaması adına isteğe bağlı olarak 3 farklı mongo URL yeri doldurmanızı istedim. Tabi ki bunu -ki botu paylaştığımda ayarlamalı olduğunu göreceksiniz- 3 farklı url true/false değeri şeklinde kendiniz düzenlersiniz.
* Ekstradan da **büyük sunuculara bot yapan hawli kodır arkadaşlarım için de dağıtıcı sistemi geliştirdim diledikleri kadar dağıtıcı koyabilirler.**

# Dağıtıcılar ne işime yarar, ne kadar işime yarar?

* Ben test sunucumda 20 kişiye 1 rolü 2 dağıtıcı + 1 database botuyla 1 saniyede verdim, şimdi sizin sunucunuzda 200 kişide kayıtsız olduğunu düşünelim. Bir avel geldi rolü sildi guard banladı vs. vs. sonra geldiniz bu rolü açacaksınız (eğer kurulumda silinen rol/kanalı oto açmayı false olarak ayarlarsanız komut ile açmak zorunda kalırsınız yoksa kendisi dağıtıcılarla oto açar) rolü açtıktan sonra 10 saniye dağıtması + 15/20 saniye de rate limitten 30 saniyede 200 kişiye rolü dağıtabilirsiniz. Piyasanın en iyi database olduğunu söylemiyorum emin olun daha iyileri vardır fakat şu ana kadar paylaşılan altyapılardan daha çalışabilir ve işlevli olduğunu düşünüyorum.

### NOT: Botta MIT lisansı bulunmaktadır. Bu botun dosyalarının benden habersiz paylaşılması/satılması durumunda gerekli işlemler yapılacaktır!
