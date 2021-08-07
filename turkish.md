# Gizlilik ve Güvenlik Bilgileri
Botun çalışabilmesi için sunucular ve kullanıcılar hakkında bazı bilgileri saklıyoruz. Aşağıda, hangi bilgileri sakladığımızın ve neden saklandığının bir listesini bulabilirsiniz.

## Sakladığımız Veriler

- **Kullanıcı ID'leri:** Bunları, önerileri öneren kullanıcıya bağlamak için saklarız, böylece bot, öneriyi gönderen kullanıcıyı gösterebilir. Ayrıca, her sunucuda ve global olarak engellenen kullanıcıların bir listesini depolamak için kullanılırlar.
- **Kanal ID'leri:** Bunları, botun öneri-bekleme-inceleme mesajları, öneri mesajları, reddedilen öneri mesajları ve günlük mesajları gibi çeşitli mesajları nereye göndereceğini bilmesi için saklarız.
- **Rol ID'leri:** Bunları, sunucu yöneticilerinin bot üzerinde belirli izinlere sahip olan rolleri (personel, yönetici, engellenen roller vb.) ayarlamasına izin vermek için saklarız\
- **Sunucu ID'leri:** Bunları sunucu ayarlarını ve önerilerini kendi sunucularına bağlı tutmak için saklarız.
- **Webhook URL'leri:** Bunları, webhook aracılığıyla oturum açmanın çalıştığından emin olmak için saklarız - yalnızca bir URL saklanır; bu, günlük kaydı yapılandırıldığında bot tarafından oluşturulan webhook URL'sidir.
- **Sunucu Emote'ları:** Bir sunucu bir ifadeyi öneri akışında bir tepki ifadesi olarak yapılandırırsa, sunucu ifade adlarını/ID'lerini saklarız.
- **Gönderilen Öneriler/Yorumlar:** Botun her öneri hakkında veriye sahip olması için öneri ve yorum olarak gönderilen mesaj içeriğini saklarız.
- **Bağlılık URL'leri:** Ekleme özelliğini mümkün kılmak için önerilere eklenen dosyaların URL'lerini saklarız.
Analitik amaçlar için **kullanılan komutları ve botun eklendiği/çıkarıldığı sunucuları** kaydederiz.
Bot'a bağlı Trello tahtalarına ait bilgileri ve kart oluşturma ve bot aracılığıyla yapılan yorumlar gibi işlemleri bu tahtalarda saklarız.

## Verilere Neden İhtiyaç Duyarız & Verileri Nasıl Kullanırız?
Bu veriler, botun çalışmasını sağlamak için kullanılır. Yukarıdaki verileri saklamadan, Suggester'ın çalışması mümkün olmayacaktır. Topladığımız veriler yukarıda belirtilen amaçlar için kullanılır, başka bir şey değil. Sakladığımız bilgileri asla yetkisiz kullanıcılara vermeyeceğiz.
 
## Güvenlik
Tüm veriler ve bot hizmetleri, kimlik doğrulama ile korunur ve erişim, küçük bir kullanıcı grubuyla sınırlıdır (Yapımcılar ve bazı veriler için Suggester'ın Personel Ekibinin üyeleri). Sistemlerimizden birinde bir güvenlik sorunu bulduğunuzu düşünüyorsanız, herkese açık bir sohbette **hakkında konuşmayın**. Bir Yapımcıya (`Brightness#0001` veya `Ben!#0002`) bilgi verin, araştıralım.

## Diğer
Suggester Discord sunucusunu yönetmeye yardımcı olan botlar ayrıca bazı bilgileri depolar:\
**VoteBoat#1330**: Kullanıcı ID'niz ve her sitede sahip olduğunuz oy sayısı\
**i18n#1614**: Dizeler için çeviri olarak sağlanan içerik ve izin amacıyla kullanıcı ID'niz\
**Suggester Support#5646**: Bot'a gönderilen DM'ler, kullanıcı etiketiniz, sunucuya özel ad (varsa), hesap oluşturma tarihi ve hesap yaşı (sadece bota doğrudan mesaj göndererek/iletişim kurduğunuzda)

## Endişeler
Sakladığımız veriler veya botun işlevleri hakkında herhangi bir endişeniz varsa, lütfen Suggester'ın [destek sunucusu](https://suggester.js.org/support) aracılığıyla Suggester Personel Ekibinin bir üyesiyle iletişime geçin. Endişelerinizi gidermekten mutluyuz.

**Verilerinizin sistemlerimizden kaldırılmasını istiyorsanız, lütfen yukarıda listelenen yapımcılardan biriyle iletişime geçin, size oradan yardımcı olalım.**
