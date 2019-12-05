# Sanal Market Benzetimi
## Ödev Metni
Geliştirilecek bir sanal market yazılımı kapsamında, ürünlere ilişkin bilgiler kategori ağacında tutulacaktır. Her bir elemanı, Bilgisayar, Beyaz Eşya gibi kategorilerden biri olan ArrayList içerisinde ilgili kategorideki ürünleri tutan ağaçlar yer alacaktır. Ürünler, ürün adına göre, ilgili kategorideki ikili arama ağacı (binary search tree) veri yapısı üzerinde tutulacaktır. <br/>
Ağacın her düğümünde, Ürünün adı (örnek olarak Dizüstü Bilgisayar) ve ilgili ürün adındaki tüm marka ve modellerin listesi (ArrayList veya daha ileri bir veri yapısında) tutulmalıdır. Listenin her bir elemanında ürüne ilişkin bilgileri (Marka, Model, Miktarı, Maliyeti, Satış Fiyatı, Ürün Açıklaması) içerecektir. Bu gerçekleştirim, ikili arama ağacı tabanlı yapılacaktır. <br/>
Ürün açıklamalarında geçen kelimelere ilişkin listenin (sözcüğün) de, Hash Tablosu üzerinde oluşturulması gerekmektedir. Hash tablosunda her bir kelime için, bir dinamik dizi (ArrayList) tutulmalıdır. Örnek olarak, Ürün Açıklaması sahasında “USB” kelimesi geçen Ürünlerin referans (adres) listesi, Hash Tablosu’nun ilgili sahasında ArrayList olarak tutulmalıdır. Bu şekilde bir kullanıcı (müşteri), herhangi bir kelimenin geçtiği ürünlere daha hızlı erişebilecektir. İkili arama ağacını dolaşmadan doğrudan kelime ile ilgili ürünlerin bilgilerine ulaşabilecektir. <br/>
Verilen bir kategorideki, örnek olarak Bilgisayar kategorisindeki ürünler Satış Fiyatına göre ayrı bir Heap’te (Yığın) yani ağaç şeklindeki öncelik kuyruğunda küçükten büyüğe sıralı tutulacaktır. <br/>
# Yapılacak İşlemler
## 1.Verilerin hazırlanması:
Market.dat adlı dosyayı kendiniz hazırlayabilirsiniz. İlk bilgiler dosya yerine bellekten veya klavyeden de alınabilir (dosya kullanımı seçimlik). Kategoriler, Bilgisayar, Beyaz Eşya, Giyim, Kırtasiye_Ofis, YapıMarket, Bahçe, Tekstil, Yiyecek olarak düzenlenebilir. Diğer bilgileri de İnternet üzerinden Sanal marketlerden toplayabilirsiniz.
## 2.Verileri kullanarak Veri Yapılarının (Kategori tabanlı Binary Search Tree listesi, Hash Table ve Heap) belirtildiği şekilde oluşturulması:
Bu bilgilere göre 3. ve 4. adımlardaki işlemleri yapan programın yazılması
## 3.Market Personelinin Kullanacağı Modülün Geliştirilmesi:
Markete yeni isimde ve/veya kategoride ürün girişi <br/>
 Markete, yeni bir marka/modelde ürün girişi <br/>
 Adından Ürün arama ve silme <br/>
 Ürün bilgilerinde değişiklik (Kategori, Marka, Model, Miktar, Fiyat) <br/>
 Ayrıca şirketin toplam gelir, gider ve kârının hesaplanması istenmektedir (Kar = o ana kadar satışı yapılan ürünlerin tümü için [Satış Fiyatı – Maliyet] toplamı) 
## 4.Müşterilerin Kullanacağı Modülün Geliştirilmesi:
Adından Ürün bilgisi arama (tüm markalardaki modellerinin fiyatlarını listeleme) <br/>
 Belirli fiyatlar arasındaki tüm ürünlerin bulunup listelenmesi <br/>
 Belirtilen bir kategorideki tüm Ürünleri, ikili arama ağacındaki düzeyleri ile birlikte listeleme (Inorder, preorder, postorder). Ağacın derinliğini ve eleman sayısını yazdırma. <br/>
 Ürün Siparişi ve Alımı <br/>
 Verilen bir kelimenin geçtiği ürünlere Hash Tablosu üzerinden erişilerek listelenmesi <br/>
 Heap oluşturularak, kullanıcının vereceği kategorideki en ucuz N adet ürünün satın alınması. İkili arama ağacı ve Hash Tablosu üzerinde de gerekli güncellemelerin yapılması. <br/>
 Kategori ağaçlarını dengeleme. <br/>
 Müşterilerin üye olabilmesi (Sistem, birden çok müşteri için düzgün biçimde çalışabilmeli). <br/>
 Alışveriş listesi eklenmesi (Belirli bir müşterinin almış olduğu ürünlere ilişkin listenin tutulması). <br/>
 Müşterilerin ürünler hakkında yorum yazabilmesi. <br/>
