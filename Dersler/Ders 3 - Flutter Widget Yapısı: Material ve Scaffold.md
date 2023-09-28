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
  

  İşte Flutter burada devreye girmektedir. Flutter geliştiricilere Mobil Uygulamlarda standart haline gelmiş temel öğeleri ekrana getirip özelleştirme noktasında büyük kolaylık sunuyor. Flutter Material ve Cupertino 


