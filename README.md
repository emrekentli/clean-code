Bir kod takımındaki herkes tarafından kolayca anlaşılabiliyorsa temizdir.Temiz kod sadece yazan kişi tarafından değil, aynı zamanda diğer geliştiriciler tarafından da geliştirilebilir. Temiz bir kod yazıldığında, anlaşılabilirliğin yanı sıra okunabilirlik, değiştirilebilirlik ve geliştirilebilirlik de artar.
_____________________________________
## Genel Kurallar
1. Standartlara uyun.
2. Basit tutun; karmaşıklığı mümkün olduğunca azaltın.
3. İzci Kuralı: Bulduğunuzdan daha temiz bırakın.
4. Herhangi bir sorunda her zaman kök nedeni arayın.

## Tasarım Kuralları
1. Yapılandırılabilir verileri yüksek seviyelerde tutun.
2. If/else veya switch/case yerine polimorfizmi tercih edin.
3. Çoklu iş parçacığı kodlarını ayırın.
4. Aşırı yapılandırılabilirliği önleyin.
5. Bağımlılık enjeksiyonu kullanın.
6. Demeter Yasasına uyun.

## Anlaşılabilirlik İpuçları
1. Tutarlı olun.
2. Açıklayıcı değişken isimleri kullanın.
3. Sınır koşullarını kapsülleyin.
4. Nesne türlerini, ilkel türler yerine tercih edin.
5. Mantıksal bağımlılıktan kaçının.
6. Negatif koşullardan sakının.

## İsim Kuralları
1. Açıklayıcı ve net isimler seçin.
2. Anlamlı ayrımlar yapın.
3. Telaffuzu kolay isimler kullanın.
4. Aramada kolay bulunabilecek isimler seçin.
5. Sihirli sayıları adlandırılmış sabitlerle değiştirin.
6. İsimlendirmelerden kaçının; değişkenlere önek eklemeyin.

## Fonksiyon Kuralları
1. Küçük ve tek işlevli fonksiyonlar yazın.
2. Açıklayıcı isimler kullanın.
3. Daha az argüman tercih edin.
4. Yan etki içermeyen fonksiyonlar yazın.
5. Bayrak argümanlarından kaçının.

## Yorum Satırı Kuralları
1. Kodunuzu mümkünse açıklamaya çalışın.
2. Gereksiz yorumlar eklemeyin.
3. Kapanış için yorum satırları eklemeyin.
4. Kodu yorum satırında tutmayın; gereksiz kodları silin.
5. Yorumları niyetinizi açıklamak için kullanın.

## Kaynak Kodu Yapısı
1. Kavramları dikey olarak ayırın.
2. İlgili kodları dikey yoğun bir şekilde düzenleyin.
3. Değişkenleri kullanıldıkları yere yakın tanımlayın.
4. Bağımlı fonksiyonları birbirine yakın tutun.
5. Benzer fonksiyonları bir araya getirin.
6. Fonksiyonları aşağı yönde yerleştirin.
7. Kod satırlarını kısa tutun.
8. Yatay hizalama yapmayın.
9. İlgili şeyleri boşluk kullanarak birbirine yakın, zayıf ilişkili olanları ayırarak düzenleyin.
10. Girintilere müdahale etmeyin.

## Nesneler ve Veri Yapıları
1. Kodun iç yapısını gizleyin.
2. Veri yapılarını tercih edin.
3. Hibrid yapılardan kaçının.
4. Küçük ve tek işlevli tutun.
5. Az sayıda örnek değişkeni kullanın.
6. Temel sınıfların türetilenler hakkında bilgi sahibi olmamasına özen gösterin.
7. Bir davranışı seçmek için bir fonksiyona kod geçirmek yerine, birçok sade ve tek işlevli fonksiyona sahip olun.
8. Statik metotları, statik olmayanlara tercih edin.

## Testler
1. Her testte bir assert bulunmalı.
2. Okunabilir ve anlaşılır olmalı.
3. Hızlı çalışmalı.
4. Bağımsız olmalı.
5. Tekrarlanabilir olmalı.

## Kötü Kokan Kod (Code Smells)
Bazen yazılım geliştirme süreçlerindeki çeşitli nedenlerle kod, "kötü kokan kod" haline gelebilir. Bu durumlar için yaygın olarak kullanılan terim "kod kokuları" veya "code smells"dir. Bu kötü kokuların ortaya çıkmasına neden olan temel durumları şu şekilde sıralayabiliriz:
1. **Rigidity (Sertlik):** Yazılımı değiştirmek zordur; küçük bir değişiklik, bir dizi ardışık değişikliği tetikler.
2. **Fragility (Kırılganlık):** Yazılım, tek bir değişiklikle birçok yerde bozulur.
3. **Immobility (Hareketsizlik):** Kodun parçalarını diğer projelerde yeniden kullanmak risklidir ve yüksek çaba gerektirir.
4. **Needless Complexity (Gereksiz Karmaşıklık):** Gereksiz karmaşıklık bulunur.
5. **Needless Repetition (Gereksiz Tekrar):** Gereksiz tekrarlar vardır.
6. **Opacity (Saydamlık):** Kodu anlamak zordur.
