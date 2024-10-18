Motoko ile Sayının Karesini Hesaplayan Akıllı Sözleşme
Bu örnekte, Motoko programlama dilinde yazılmış bir akıllı sözleşme (canister) bulunmaktadır. square adındaki aktör, bir sayının karesini hesaplamak için tasarlanmıştır. Kodda kullanılan ana bileşenler şunlardır:

Değişkenler: var ile tanımlanan square değişkeni, mutable (değiştirilebilir) bir değişkendir ve başlangıç değeri 0'dır. let ile tanımlanan değişkenler ise immutable (değiştirilemez) özelliğe sahiptir.

Asenkron İşlemler: async anahtar kelimesi, fonksiyonların arka planda çalışmasına olanak tanır, böylece ana akış duraksamaz.

Kare Hesaplama Fonksiyonu: hesaplama fonksiyonu, bir tamsayı alır ve eğer sayı 0 ise null döner. Aksi takdirde, sayının karesi hesaplanarak square değişkenine atanır ve bu değer döndürülür.

Temizleme Fonksiyonu: temizle fonksiyonu, square değişkenini sıfırlamak için kullanılır.

Bu akıllı sözleşme, kullanıcıların sayıların karelerini hızlı ve etkili bir şekilde hesaplamasını sağlar.
