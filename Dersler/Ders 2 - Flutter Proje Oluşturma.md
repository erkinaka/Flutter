#1 - Proje Oluşturma

##Visual Studio Code:

  VS Code içerisine Fluuter eklentileri kurulduktan sonra CTRL+SHIFT+P tuşlarına bastığımızda karşımıza gelen komut plaetinden Flutter:New Project seçilir.

##Android Studio:

  Programın açılış sayfasında Fluuter Project seçildiğinde yeni proje oluşturulur.
  
##Komut Satırı:

  Flutter projelerini kout satırından da oluşturabiliriz. Özellikle flutter projeyi ilk oluşturduğumuzda iskelet bir proje yapısını internetten indirerek kurar. Eğer internet bağlantımız yoksa projemizi çevrimdışı (offline) olarak kurmamız gerektiğinde komut satırını kullanabiliriz.

  Bunun için kullanıdığımız program üzerindeki Terminal arayüzünden veya Windows’taki CMD veya Powershell üzerinden projeyi oluşturacağımız klasörün içerisine girip aşağıdaki komutu yazmamız yeterlidir.
'''  
flutter create my_app

flutter create –offline my_app   
(Bu komut internet bağlantımız olmadığında çevrimdışı proje oluşturur.)
'''

Projemizi çalıştırmak için ise proje klasörünün içindeyken “flutter run” komutu kullanılır.

