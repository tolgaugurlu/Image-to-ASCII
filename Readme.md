# Fotoğrafı ASCII Koduna Çevirerek Çizme

Bu bir Python programıdır ve resim dosyalarını ASCII sanatına dönüştürür. Programı çalıştırmadan önce, bilgisayarınızda `Python`, `pip` ve `Pillow`'un en son sürümünün yüklü olduğundan emin olun. Ayrıca, dönüştürülecek resmi `'test1.jpg'` olarak bu dizine kaydedin.

### Hatalar

Yüksek ihtimalle ilk başta çalıştırmaya çalıştığınız dizin içerisinde `test1.jpg` adında bir görüntü olmayacak, bu yüzden dizin içerisine atmak istediğiniz resmi `'test1.jpg'`adı ile kopyalarsanız kodlar sorunsuz çalışacaktır.

`in_convert_pixel` hatası alırsanız. Bu hata, `convert_pixel_to_character` fonksiyonunda bir pikselin RGB değerlerini çözümlemeye çalışırken oluşan bir hatadan kaynaklanması demektir. Pikselin beklenen 3 değerden daha fazla veya daha az değere sahip olduğu anlamına gelir. Bu hata genellikle, resim dosyasının boyutlarının yanlış olduğu veya resim dosyasının bozuk olduğu durumlarda oluşur. Bu hatayı çözmek için, resim dosyasının boyutlarını kontrol edin ve yüksek çözünürlükte resim koymamaya çalışın.

### Nasıl Çalışır?

Programı çalıştırmak için, Visual Studio Code benzeri bir IDE kullanıyorsanız. Kullandığınız Vscode ekranında `terminal`'i açın ve ardından `python3 ascii_art.py` komutunu çalıştırın. Direkt olarak bulunduğunuz dizinin içerisine bir `image.txt` oluşacaktır. Masaüstüne bu dosyayı kopyalayarak ASCII kodundan oluşmuş olan görselinizin boyutunu küçültüp nasıl göründüğüne bakabilirsiniz.
