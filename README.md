# Pratik - Dosyadan Sayıları Okuma ve Toplama

Soru: Aşağıda verilen bir metin dosyasındaki (.txt) tüm sayıları okuyan ve bu sayıların toplamını döndüren ve ekrana yazdıran bir Java programı yazınız. Dosyada sadece satır başına bir tam sayı bulunacaktır.


Dosya içeriği :

* 5
* 10
* 20
* 12
* 33

Programınızın çıktısı 80 olmalıdır.

İpucu 1: Java'da bir dosyadan veri okumak için `BufferedReader` sınıfını veya Java 7 ve üzeri için `java.nio.file` paketini kullanabilirsiniz. `BufferedReader`'ı `FileReader` ile birlikte kullanarak bir dosyayı satır satır okuyabilirsiniz.


İpucu 2: Dosyadan okunan her satır bir `String` olacaktır. Bu `String`'i bir tam sayıya dönüştürmek için `Integer.parseInt` metodunu kullanabilirsiniz.


İpucu 3: Her bir satırdaki sayıyı bir toplam değişkenine ekleyin. Bu değişken, döngü boyunca her bir sayıyı ekler ve sonuçta tüm sayıların toplamını elde edersiniz.


İpucu 4: Dosya okuma işlemleri her zaman `IOException` hatası fırlatabilir. Bu yüzden, dosya okuma kodunuzu `try-catch` bloğu içerisine almayı unutmayın.

