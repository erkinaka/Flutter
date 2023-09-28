  Bu sayfada bulunduğunuza göre Flutter'ın ne olduğunu veya en azından ne amaçla kulanıldığını bildiğiniz düşünerek hemen programın kurulumlarını sizlere anlattık. Ama şimdi bilmeyenler ve yeni başlayanlar için Flutter ile ilgili bir ka temel konuya değinelim.

  Flutter, Google tarafından oluşturulan ve Mayıs 2017'de piyasaya sürülen ücretsiz ve açık kaynaklı bir Mobil UI Framework’üdür (çerçevesidir). Birkaç kelimeyle söylemek gerekirse, yalnızca tek bir kod tabanıyla yerel bir mobil uygulama oluşturmanıza olanak tanır. Bu, iki farklı uygulama (iOS ve Android için) oluşturmak için bir programlama dili ve bir kod tabanı kullanabileceğiniz anlamına gelir.

# Flutter iki önemli bölümden oluşur:

## 1-	SDK (Yazılım Geliştirme Kiti): 
  Uygulamalarınızı geliştirmenize yardımcı olacak araçlardan oluşan bir koleksiyon. Bu, kodunuzu yerel makine koduna (iOS ve Android kodu) derlemeye yönelik araçları içerir.
## 2-	Framework (widget'lara dayalı Kullanıcı Arayüzü Kitaplığı): 
  Kendi ihtiyaçlarınıza göre kişiselleştirebileceğiniz, yeniden kullanılabilir kullanıcı arayüzü öğelerinden (düğmeler, metin girişleri, kaydırıcılar vb.) oluşan bir koleksiyon.

# Flutter Ekran Tasarımı
  Flutter’da ekran tasarımları, widget ismi verilen yapılar ile kurulur. Widget’lar ekranda kullanılan nesnelere ait sınıflardır. Ekran tasarımı yapılırken widget’lar bir hiyerarşi ve ilişki içerisinde ekrana yerleştirilir. Biz buna widget tree ( widget ağacı ) deriz.

Widget ve ekran tasarım örneklerini aşağıdaki linklerden inceleyebilirsiniz.

https://docs.flutter.dev/ui/widgets

https://gallery.flutter.dev/#/

  Bootsrapt ile web sayfaları geliştirirken geliştiricilere, temel web sayfası arayüz tasarımlarında standart haline gelen ve temel kullanıcı alışkanlığı olan sayfalar için nasıl hazır tasarım araçları sunuyorsa Flutter'da arayüz tasarımlarında bu kullanım kolaylalığını Widget'lar ile sunuyor. 

  Web sayfası arayüz tasarımlarında, header, container, footer yapısı standart haline gelmiştir. Yaygın olarak kullanılan bu standartlar müşteri ve internet kullanıcıları için de kullanım alışkanlıkları kazandırmıştır. Mesela bir web sayfasını açtığımızda sayfanın üstünde banner bölümünde sayfa başlığı ve logo öğelerini görmeyi umarız. Banner altında sayfada gezinmek için bir menü ihtiyacı duyarız. Yine sayfanın en altında firma iletişim bilgileri, kullanıcı sözleşmeleri ve telif hakları gibi bilgiler yer alır. 

  Kullanıcılar bir web sayfasında gezinirken yukarıda anlattığımız alışkanlıklar doğrultusunda hareket eder. Aynı bu durum mobil uygulamalar için de geçerlidir.

![Screenshot](images/Resim15.png)
![Screenshot](images/Resim16.png)
  

  İşte Flutter burada devreye girmektedir. Flutter geliştiricilere Mobil Uygulamlarda standart haline gelmiş temel öğeleri ekrana getirip özelleştirme noktasında büyük kolaylık sunuyor. Flutter Material ve Cupertino widget sınıfları ile kullanıcılar hazır tema ve tasarım ilkelerine sahip widget'ları kullanmasını sağlar.

  Scafold widget'ı ile kullanıcılara bir iskelet yapısı sunar ve böylece kullanıcılar, istediği widget'ı ekranın istediği yerinde gösterebilir.


# Flutter main.dart dosyası

Flutter backend kısımda dart programlama dilini kullanır. Dart nesne yönelimli bir dildir. Flutter projeleri çalışmak için bir başlangıç dosyasına ve main methoduna ihtiyaç duyar. Eğer aksi belirtilmemişse Flutter projelerinin başlangıç dosyaı proje kök dizini içinde yer alan *lib* klasörünün içindeki main.dart dosyasıdır.

Flutter projesi çalıştırıldığında main.dart içerisindeki main metodu çalıştırılır.

````
void main() {
  runApp(const MyApp());
}

//Veya 

void main() =>  runApp(const MyApp());
````

main metdonunun içersinde projemizde oluşturacağımız uygulamamıza ait ana sınıf ismi ile birlikte runApp komutu ile çağrılıp çalıştırılır. Yukaridaki örnekte projemizimizin MyApp isimli ana sınıfı çağrılmıştır. Bu ana sınıf bir widget'tan türeyen başka bir widget sınıfıdır. MyApp ismi değiştirilerek kullanıcının istediği herhangi bir isim verilebilir.

MyApp sınıfı Flutter'da iki temel sınıftan birini miras alabilir. Bunlar StatelessWidget ve StatefulWidget widgetlardır. Bu widgetların temel açıklamalarına yer verilmek ile birlikte daha sonra ayrıntısı ile anlatılacaktır.

## StatelessWidget: Bu widgetlar i
  


