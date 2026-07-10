<p style='border-left: solid; border-width:10px; border-color: #FFA500; background-color: #FFFACD; padding: 10px;'>
Bu öğrenme kaynağı 13 yaşın altındaki öğrenciler için önerilmemektedir. Kullanıcıları bu materyali sorumlu bir şekilde kullanmaya ve gerektiğinde güvendikleri bir yetişkinden rehberlik almaya teşvik ediyoruz.
</p>

## Ne yapacaksınız

![Çarpıcı mavi gözleri ve pembe burnu olan kabarık beyaz bir kedi, dekoratif metal bir kap içindeki saksı bitkisinin yanında, pencere pervazı ve kanepenin arkasına oturmuş. Pencere pervazı, çiçekli bir yastık, sarkıt yeşil bir bitki ve raflarla birlikte, sıcak ve samimi bir iç mekanın parçasıdır. Pencereden bir bina görünüyor. Görüntünün ön planında, zarif bir tarzda ve bazı süslemelerle yazılmış "EVİM Suzel GÜZEL Evim" metni bulunmaktadır.](images/prompt8.jpg)

Yapay zekâ ile görüntü oluşturmanın heyecan verici dünyasına hoş geldiniz!

Bu projedeki adımları takip ederek, yapay zekâ destekli bir görüntü oluşturucu kullanarak muhteşem görüntüler oluşturmayı öğreneceksiniz.

## --- collapse ---

## başlık: Daha fazla detay

Bu proje, basit fikirlerden yola çıkarak, çarpıcı görüntüler üretmek için kullanabileceğiniz ayrıntılı komutlar oluşturmanıza yardımcı olacaktır. Bu derste, belirli ayrıntıları nasıl ekleyeceğinizi; ortamları nasıl tanımlayacağınızı; temel unsurları nasıl dahil edeceğinizi; ve renkler, stiller ve kompozisyon hakkında nasıl düşüneceğinizi keşfedeceksiniz. Bu süreçte, komutlarınızı test edecek, ayarlamalar yapacak ve her değişikliğin görüntünüzü oluşturmanıza nasıl yardımcı olduğunu göreceksiniz.

\--- /collapse ---

### Nelere ihtiyacınız olacak

Bu proje için yapay zeka destekli bir görüntü oluşturma aracına ihtiyacınız olacak.

Çevrimiçi olarak kullanılabilen yapay zekâ görüntü oluşturucularını kullanmak için gereken minimum yaş sınırının altındaysanız veya Raspberry Pi bilgisayarınızda **kendi** yapay zekâ görüntü oluşturucunuzu barındırmayı tercih ediyorsanız, [buradaki talimatlarımızı izleyin](https://projects.raspberrypi.org/en/projects/ai-images-on-pi){:target="_blank"}.

### Ücretsiz Çevrimiçi Görüntü Oluşturucular

Kayıt gerektirmeyen ücretsiz bir resim oluşturucu [Craiyon](https://www.craiyon.com){:target="_blank"}'dur, ancak onu kullanmak için bulunduğunuz yargı bölgesinde [reşit olma yaşına](https://en.wikipedia.org/wiki/Age_of_majority){:target="_blank"} ulaşmış veya daha büyük olmalısınız ([daha fazla bilgi için şartlara bakın](https://www.craiyon.com/terms){:target="_blank"}).

Başka çevrimiçi araçlar da mevcuttur, ancak bunlar için geçerli bir e-posta adresiyle kayıt olmanız gerekir. Bazı örnekler şunlardır:

- [Adobe Firefly](https://firefly.adobe.com/){:target="_blank"} (Minimum yaş 13'tür ve eğer şartları kabul etmek için yasal yaşta değilseniz, bunu yapmak için bir ebeveyn/veli iznine ihtiyacınız vardır — [daha fazla bilgi için şartlara bakın](https://www.adobe.com/uk/legal/terms.html){:target="_blank"})
- [İdeogram](https://www.ideogram.ai){:target="_blank"} (Minimum yaş 13'tür ve eğer bulunduğunuz yargı bölgesinde reşitlik yaşının altındaysanız, bir ebeveyn/vasinin şartları sizin adınıza kabul etmesi gerekir — [daha fazla bilgi için şartlara bakın](https://ideogram.ai/legal/tos){:target="_blank"})
- [Kararlı Yayılım](https://stablediffusionweb.com/){:target="_blank"} ([şartlara bakın](https://stablediffusionweb.com/terms-and-conditions){:target="_blank"})

**Bu hizmetlerden birine hesap açarsanız, lütfen güvenlik politikalarına uymayı unutmayın.**

## --- collapse ---

## başlık: Neden daha büyük yaştaki öğrencilerin bu projeyi kullanmasını öneriyoruz?

Kişisel bilgilerinizi nasıl güvende tutabileceğinizi anlamak önemlidir. Raspberry Pi, verilerinizin ve gizliliğinizin korunması konusunda son derece titiz davranmaktadır; bu nedenle bu projeyi yalnızca 13 yaşından büyük kişilere öneriyoruz.

Muhtemelen birçok çevrimiçi hizmetin kullanıcıların en az 13 yaşında olmasını istediğini fark etmişsinizdir. Çünkü onlar sizin sağladığınız verileri işliyor ve saklıyorlar; bu veriler kişisel bilgileri de içerebilir. Bu hizmetler verilerinizi korumak için katı kurallara uysa da, internet üzerinden bilgi göndermek bazen daha az güvenli olabilir.

Ayrıca, üretken yapay zekânın bazen **doğru, adil veya uygun olmayan içerikler** üretebileceğini bilmek de önemlidir. Bu yapay zeka modelleri bazen "halüsinasyon görebilir" ve **doğru gibi görünen ancak doğru olmayan bilgiler üretebilir**. Dolayısıyla, yapay zekâ uygulamasının **çıktısını dikkatlice düşünmek ve iki kez kontrol etmek önemlidir**. Üretken yapay zekâ ile çalışırken, bilgileri kontrol ettiğinizden ve emin olmadığınız durumlarda güvenilir kaynaklara danıştığınızdan emin olun.

**Yapay zekâ tarafından oluşturulan içeriklere her zaman dikkatli ve düşünceli bir şekilde bakın.** Yardıma ihtiyacınız olursa, lütfen bir ebeveyninizden, vasinizden veya öğretmeninizden yardım isteyin.

Üretken yapay zekâ ile öğrenmenin ve yaratmanın keyfini çıkarın!

\--- /collapse ---
