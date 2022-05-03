Veritabanımızdaki zombileri sahiplendirerek oyunumuzu çok oyunculu hale getirelim.
>Bunu yapmak için 2 yeni veri türüne ihtiyacımız olacak: mapping(eşleme) ve address(adres).
**Adresses(adresler)**
Ethereum blok zinciri, banka hesapları gibi düşünebileceğiniz hesaplardan oluşur. Bir hesabın bir Ether bakiyesi (Ethereum blok zincirinde kullanılan para birimi) vardır ve tıpkı banka hesabınızın diğer banka hesaplarına para transferi yapabilmesi gibi, diğer hesaplara Ether ödemeleri gönderip alabilirsiniz.

>Her hesabın bir banka hesap numarası gibi düşünebileceğiniz bir adresi vardır. Bu hesaba işaret eden benzersiz bir tanımlayıcıdır ve şöyle görünür:
`0x571743307078d0859A3f9C7476f898e0793b6b2A`


(Bu adres SelcukBlockchain ekibine aittir. SelcukBlockchain Ekibinden hoşlanıyorsanız, bize biraz Ether gönderebilirsiniz!😉 )

*Adreslerin küçük ayrıntılarına daha sonraki bir derste gireceğiz, ancak şimdilik bir adresin belirli bir kullanıcıya (veya akıllı bir kontrata) ait olduğunu anlamanız yeterlidir.*

Böylece zombilerimizin sahipliği için benzersiz bir kimlik olarak kullanabiliriz. Bir kullanıcı uygulamamızla etkileşim kurarak yeni zombiler oluşturduğunda, bu zombilerin sahipliğini, işlevi çağıran Ethereum adresine ayarlayacağız.
