### PYTHON İLE TAŞ KAĞIT MAKAS OYUNU
## Aygaz ile Python Bootcamp Projesi
# OYUN KURALLARI
* Taş - Kağıt - Makas oyunu bilgisayar ve oyuncu ile oynanılacaktır.
* Puanı 2 olan kazanır.
* Tur sonlarında oyuncuya tekrar oynayıp oynamayacağı sorulmuştur.
* Taş Makası KIRAR
* Makas Kağıdı KESER
* Kağıt Taşı KAPLAR

  
## Projede Kullanılanlar
* While Döngüsü
* If - else Yapısı
* Fonksiyonlar
* Google Colab ortamında geliştirilmiştir.
* Bilgisayar tahmini için random fonksiyonu kullanılmıştır.

Projede 2 farklı fonksiyon bulunmaktadır.
## def oyuncu_secimi(): fonksiyonu
Bu fonksiyonda oyuncunun seçimi yapılmaktadır. Oyuncu seçimi "taş" , "kağıt" yada "makas" seçmelidir.
Bu seçimler dışında bir seçim yapması durumunda hata vermekte ve oyuncuya yeni bir seçim yaptırmaktadır. 
Seçim işi ise while döngüsü kullanılarak yapılmıştır. Doğru seçim yapması sonucunda döngüden çıkmaktadır. 
Yanlış seçimde ise döngü içinde sürekli tahmin etmektedir.

## def tas_kagit_makas_MEHMET_CANTEMIR(): fonksiyonu
Bu fonksiyonda oyun başlangıcı ve bitişi bulunmaktadır.Bu fonksiyonda oyunu etkileyen çeşitli değişkenler bulunmaktadır.
- kullanici_puani : Oyuncunun kazandığı tur sayısını tutar.
- bilgisayar_puani : Bilgisayarın kazandığı tur sayısını tutar.
- tur : Tur sayısını tutar.
- oyun_devam_mi  : Oyun sonlarında kullanıcıya tekrar oynamak isteyip istemediği sorulur.Cevaba göre bu değişkene true veya false değeri atanır ve oyunun devam edilip edilmeyeceği belirlenir.



