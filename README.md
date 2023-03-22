# 15 Günde PHP
15 gün boyunca PHP öğrenmek isteyenler için bir eğitim makalesi yazdım. Burada, temel düzeyden başlayarak, her gün farklı bir konu hakkında öğretici bir makale sunacağım.
# Gün 1: PHP Nedir ve Neden Kullanılır?

-   PHP'nin Tanımı ve Tarihçesi
-   PHP'nin Avantajları ve Dezavantajları
-   PHP ile Neler Yapılabilir?
-   İlk PHP Kodunuzu Yazın: "Hello World"

# Gün 2: PHP Kurulumu ve Ayarları

-   PHP'nin Kurulumu
-   PHP Sunucuları: Apache, Nginx vb.
-   PHP Ayarları ve Yapılandırması
-   İlk PHP Uygulamanızı Çalıştırın: "Merhaba Dünya"

# Gün 3: PHP Temel Sözdizimi ve Değişkenler

-   PHP Temel Sözdizimi
-   Değişkenler: Tanımlama, Atama, İsimlendirme
-   Veri Türleri: String, Sayı, Boolean, Dizi, Nesne
-   Değişken Tür Dönüşümleri

# Gün 4: PHP Operatörleri ve Kontrol Yapıları

-   Aritmetik Operatörler: Toplama, Çıkarma, Çarpma, Bölme
-   Atama Operatörleri: +=, -=, *=, /=
-   Karşılaştırma Operatörleri: ==, !=, >, <, >=, <=
-   Mantıksal Operatörler: AND, OR, NOT
-   Kontrol Yapıları: if-else, switch-case, for, while, do-while

# Gün 5: PHP Fonksiyonları

-   Fonksiyonların Tanımı ve Çağrılması
-   Fonksiyon Parametreleri ve Geri Dönüş Değerleri
-   Dahili Fonksiyonlar: strlen, substr, explode vb.
-   Kullanıcı Tanımlı Fonksiyonlar

# Gün 6: PHP Dizileri

-   Dizilerin Tanımı ve Oluşturulması
-   Dizilerin İndekslenmesi ve Değiştirilmesi
-   Dizi İşleme Fonksiyonları: count, array_push, array_pop, array_reverse vb.
-   Dizi Döngüleri: foreach, for, while

# Gün 7: PHP Dosya İşlemleri

-   Dosya İşlemlerine Giriş
-   Dosya Okuma: fopen, fread, fclose
-   Dosya Yazma: fopen, fwrite, fclose
-   Dosya Silme: unlink
-   Dosya Yönetimi Fonksiyonları: is_file, file_exists, rename vb.

# Gün 8: PHP Veritabanı İşlemleri

-   Veritabanına Giriş: MySQL, PostgreSQL vb.
-   Veritabanı Bağlantısı Oluşturma: mysqli_connect
-   Veritabanı Sorgulama: mysqli_query

# Gün 9: PHP Object-Oriented Programming (OOP)

-   OOP Nedir?
-   Sınıf ve Nesnelerin Tanımı
-   Özellikler (Properties) ve Metotlar (Methods)
-   Oluşturucu ve Yıkıcı Metotlar (Constructors and Destructors)
-   Kalıtım (Inheritance) ve İşaretçiler (Pointers)

# Gün 10: OOP İleri Konuları

-   Kapsülleme (Encapsulation) ve Erişim Belirteçleri (Access Modifiers)
-   Polimorfizm (Polymorphism) ve Arayüzler (Interfaces)
-   Soyut Sınıflar (Abstract Classes) ve Soyut Metotlar (Abstract Methods)
-   Olaylar (Events) ve Yönlendirme (Routing)
-   Örnek Uygulama: Bir Blog Sistemi

# Gün 11: PHP Web Uygulamaları

-   Web Uygulamalarına Giriş
-   HTML ve CSS ile PHP Entegrasyonu
-   Form Verilerinin Alınması: $_GET ve $_POST
-   Form Doğrulama ve Hataların İşlenmesi
-   Oturum Yönetimi: $_SESSION ve $_COOKIE

# Gün 12: PHP Framework'leri

-   Framework Nedir?
-   PHP Framework'leri: Laravel, CodeIgniter, Symfony vb.
-   MVC Modeli (Model-View-Controller) ve Yapılandırma
-   Yönlendirme ve İstek İşleme (Routing and Request Handling)
-   Örnek Uygulama: Bir E-Ticaret Sitesi

# Gün 13: PHP ve Diğer Web Teknolojileri

-   PHP ve JavaScript Entegrasyonu
-   AJAX ve jQuery ile Veri Yükleme
-   XML, JSON ve SOAP İşlemleri
-   RESTful API ve Web Servisleri
-   Örnek Uygulama: Bir Öğrenci Yönetim Sistemi

# Gün 14: PHP Güvenliği

-   Güvenli Kodlama Uygulamaları
-   XSS (Cross-Site Scripting) ve CSRF (Cross-Site Request Forgery)
-   SQL Enjeksiyonu ve Önleme Yöntemleri
-   Güvenli Oturum Yönetimi ve Şifreleme
-   Örnek Uygulama: Bir Şifre Yönetim Uygulaması

# Gün 15: PHP Performans ve Hata Ayıklama

-   PHP Performansı ve Ölçüm Yöntemleri
-   Kod Optimize Etme ve İyileştirme
-   Debugging Araçları: Xdebug, var_dump, error_reporting vb.
-   Hata Ayıklama ve Hata Yakalama Yöntemleri
-   Örnek Uygulama: Bir Performans Testi Aracı

Bu makale, PHP ile ilgili temel ve ileri düzey konuları kapsamakla birlikte, 15 günde tam bir uzman seviyesi eğitimi sağlamayabilir. Ancak, bu makale, başlangıç seviyesi programcılar için güçlü bir temel oluşturacaktır. Daha fazla kaynak ve örneklerle, PHP becerilerinizi daha da geliştirebilirsiniz.

# Gün 1: PHP Temelleri

## PHP Nedir?

PHP, Sunucu taraflı bir betik dili olarak kullanılan ve özellikle web geliştirme alanında popüler olan açık kaynaklı bir programlama dilidir. PHP, HTML ile birlikte kullanılabilir ve veritabanı işlemleri, form işlemleri, dosya işlemleri gibi birçok görevi yerine getirebilir.

## PHP Çalışma Mantığı

PHP, web sunucularında çalıştırılabilen bir betik dilidir. Web sunucusu, PHP kodlarını işleyerek HTML çıktısı üretir ve bu çıktı web tarayıcıları tarafından görüntülenebilir. PHP kodu, HTML kodu içinde yer alabilir veya bir dosyada saklanabilir.

## PHP Yorumlayıcıları

PHP kodları, web sunucusunda veya yerel bir bilgisayarda PHP yorumlayıcısı tarafından yorumlanır. PHP yorumlayıcıları, PHP kodlarını çalıştırabilen uygulamalardır. En popüler PHP yorumlayıcıları arasında Apache, Nginx, IIS, XAMPP ve WAMP bulunur.

## İlk PHP Uygulaması

Bir PHP uygulaması, .php uzantılı bir dosyada saklanabilir. Örneğin, hello.php adında bir dosya oluşturup içine aşağıdaki kodları yazabilirsiniz:
```php
<?php  echo  "Merhaba, Dünya!"; ?>
```

Bu kod, "Merhaba, Dünya!" metnini ekrana yazdıracaktır.

# Gün 2: PHP Değişkenleri ve Veri Türleri

## Değişkenler

Değişkenler, değerleri saklamak için kullanılan öğelerdir. PHP'de bir değişken, dolar işareti ($) ile başlar ve harf veya alt çizgi (_) ile devam eder. Örneğin:

```php
<?php
$name = "Serkan";
$age = 25;
?>
```

Bu örnekte, $name değişkeni "John" değerini, $age değişkeni ise 25 değerini saklar.

## Veri Türleri

PHP'de kullanabileceğiniz farklı veri türleri vardır. En yaygın veri türleri şunlardır:

-   String: Metin verileri için kullanılır. Örneğin: "Merhaba, Dünya!"
-   Integer: Tam sayılar için kullanılır. Örneğin: 25
-   Float: Ondalıklı sayılar için kullanılır. Örneğin: 3.14
-   Boolean: Doğru veya yanlış değerlerini saklar. Örneğin: true veya false
-   Array: Birden fazla değeri saklamak için kullanılır. Örneğin: array("elma", "armut", "portakal")
-   Object: Nesneleri temsil etmek için kullanılır. Örneğin: bir kullanıcı nesnesi
-   Null: Değersiz bir değişkeni ifade etmek için kullanılır. Örneğin: null

## Veri Türleri Dönüşümü
PHP, farklı veri türleri arasında dönüşüm yapabilmenizi sağlar. Örneğin, bir string değeri integer'a veya float'a dönüştürebilirsiniz. Bunun için, hedef veri türünün adını parantez içinde belirterek (int) veya (float) gibi bir ifade kullanmanız yeterlidir. Örneğin:
```php
<?php
$name = "Serkan";
$age = 25;
?>
```

Bu örnekte, $x değişkeni bir string değeri saklar. Ancak, (int) ifadesi kullanarak $x değerini integer'a dönüştürdük ve sonucu $y değişkenine atadık. Sonuç olarak, ekranda 25 değeri görüntülenecektir.

# Gün 3: PHP Koşullu İfadeler

## If-Else İfadeleri

PHP'de koşullu ifadeler, belirli bir koşulu yerine getirip getirmediğinizi kontrol etmenize olanak tanır. En temel koşullu ifade, if-else ifadesidir. Bu ifade, bir koşulu kontrol eder ve koşul doğruysa belirtilen kod bloğunu çalıştırır. Aksi takdirde, else bloğu çalıştırılır. Örneğin:

```php
<?php
$x = 10;
if ($x < 20) {
    echo "x, 20'den küçüktür.";
} else {
    echo "x, 20'den büyüktür veya eşittir.";
}
?>
```

Bu örnekte, $x değişkeni 10 değerini saklar. if-else ifadesi, $x değerinin 20'den küçük olup olmadığını kontrol eder. $x 20'den küçük olduğu için, ekranda "x, 20'den küçüktür." mesajı görüntülenecektir.

## Switch İfadeleri

Switch ifadesi, birden fazla koşulu kontrol etmenize olanak tanır. Bu ifade, belirli bir koşulu karşılayan ilk duruma atlar ve o durumun kod bloğunu çalıştırır. Örneğin:
```php
<?php
$day = "Pazar";
switch ($day) {
    case "Pazartesi":
        echo "Bugün Pazartesi.";
        break;
    case "Salı":
        echo "Bugün Salı.";
        break;
    case "Çarşamba":
        echo "Bugün Çarşamba.";
        break;
    case "Perşembe":
        echo "Bugün Perşembe.";
        break;
    case "Cuma":
        echo "Bugün Cuma.";
        break;
    case "Cumartesi":
        echo "Bugün Cumartesi.";
        break;
    case "Pazar":
        echo "Bugün Pazar.";
        break;
    default:
        echo "Geçersiz gün.";
}
?>
```
Bu örnekte, $day değişkeni "Pazar" değerini saklar. switch ifadesi, $day değerinin hangi koşulu karşıladığını kontrol eder ve "Pazar" durumunu karşılar. Sonuç olarak, ekranda "Bugün Pazar." mesajı görüntülenecektir. Eğer $day değeri case ifadeleri arasında bulunmuyorsa, default durumundaki kod bloğu çalıştırılır.
## Ternary İfadeleri

Ternary ifadesi, kısa bir if-else ifadesi olarak kullanılabilir. Bu ifade, belirli bir koşulu kontrol eder ve koşul doğruysa bir değer döndürür. Aksi takdirde, başka bir değer döndürür. Örneğin:
```php
<?php
$x = 10;
echo ($x < 20) ? "x, 20'den küçüktür." : "x, 20'den büyüktür veya eşittir.";
?>
```
Bu örnekte, $x değişkeni 10 değerini saklar. Ternary ifadesi, $x değerinin 20'den küçük olup olmadığını kontrol eder. $x 20'den küçük olduğu için, ekranda "x, 20'den küçüktür." mesajı görüntülenecektir.

# Gün 4: PHP Döngüler

## For Döngüsü

For döngüsü, belirli bir koşula kadar kod bloğunu yinelemek için kullanılır. Bu döngü, başlangıç değeri, koşul ve artış değeri gibi üç parametre alır. Örneğin:
```php
<?php
for ($x = 0; $x <= 10; $x++) {
    echo "Bu sayı: $x <br>";
}
?>
```
Bu örnekte, for döngüsü $x değişkeni için 0'dan başlayacak, 10'dan küçük veya eşit olana kadar çalışacak ve her yinelemede $x değerini bir artıracaktır. Sonuç olarak, ekranda 0'dan 10'a kadar olan sayılar görüntülenecektir.

## While Döngüsü

While döngüsü, belirli bir koşul doğru olduğu sürece kod bloğunu yinelemek için kullanılır. Bu döngü, sadece koşul parametresini alır. Örneğin:
```php
<?php
$x = 0;
while ($x <= 10) {
    echo "Bu sayı: $x <br>";
    $x++;
}
?>
```

Bu örnekte, while döngüsü $x değişkeninin 10'dan küçük veya eşit olup olmadığını kontrol eder. Her yinelemede $x değeri bir artırılır ve ekranda 0'dan 10'a kadar olan sayılar görüntülenir.

## Do-While Döngüsü

Do-while döngüsü, en az bir kez kod bloğunu çalıştırmak ve belirli bir koşul doğru olduğu sürece kod bloğunu yinelemek için kullanılır. Bu döngü, önce kod bloğunu çalıştırır ve sonra koşul parametresini kontrol eder. Örneğin:
```php
<?php
$x = 0;
do {
    echo "Sayı: $x <br>";
    $x++;
} while ($x <= 10);
?>
```
Bu örnekte, do-while döngüsü, $x değişkeninin 10'dan küçük veya eşit olup olmadığını kontrol eder. İlk yinelemede $x değeri 0 olduğu için, kod bloğu çalıştırılır ve ekranda "Sayı: 0" mesajı görüntülenir. Sonraki yinelemelerde, $x değeri artırılır ve koşul doğru olduğu sürece kod bloğu tekrar çalıştırılır. Sonuç olarak, ekranda 0'dan 10'a kadar olan sayılar görüntülenecektir.

# Gün 5: PHP Fonksiyonlar


Bugünkü makalede, PHP fonksiyonlarını ele alacağız. Fonksiyonlar, programlamada tekrarlanan işlemleri kolaylaştıran ve kodun daha düzenli olmasını sağlayan bir yapıdır. Fonksiyonlar, belirli bir görevi yerine getiren ve belirli bir değer döndüren birimlerdir. PHP'de, birçok hazır fonksiyon bulunurken, aynı zamanda kendi fonksiyonlarımızı da oluşturabiliriz.

## Fonksiyonların Tanımlanması

Bir fonksiyonu tanımlamak için `function` anahtar kelimesi kullanılır. Bir fonksiyonun adı, fonksiyonu çağırmak için kullanılan isimdir. Fonksiyon adı, değişken isimleriyle aynı kurallara tabidir. Adlar, harf veya alt çizgi (_) ile başlayabilir ve ardından harf, rakam veya alt çizgi (_) kullanılabilir.

Bir fonksiyonun içindeki işlemler, fonksiyonun adından sonra gelen parantez içinde belirtilir. Eğer fonksiyon herhangi bir değer döndürmüyorsa, parantez içinde herhangi bir değer belirtilmez.

Bir örnek fonksiyon tanımı şu şekildedir:
```php
function merhaba() {
    echo "Merhaba dünya!";
}
```
Bu fonksiyon, "Merhaba dünya!" metnini ekrana yazdıracaktır.

## Fonksiyonların Çağrılması

Bir fonksiyonu çağırmak için, fonksiyonun adı ve parantez kullanılır. Eğer fonksiyon herhangi bir değer döndürüyorsa, bu değer bir değişkene atanabilir veya doğrudan kullanılabilir.

Örnek olarak, yukarıda tanımladığımız `merhaba()` fonksiyonunu çağırmak için şu şekilde kullanabiliriz:
```php
merhaba(); // "Merhaba dünya!" metni ekrana yazdırılacak
```
## Parametreli Fonksiyonlar

Fonksiyonlar, parametrelerle birlikte de kullanılabilirler. Parametreler, fonksiyon içinde kullanılacak değerleri belirtir. Parametreler, fonksiyon adından sonra gelen parantez içinde belirtilir ve virgülle ayrılır.

Aşağıdaki örnekte, `merhaba()` fonksiyonu parametre olarak bir isim alacak şekilde tanımlanmıştır:
```php
function merhaba_isim($isim) {
    echo "Merhaba " . $isim . "!";
}
```
Bu fonksiyon, `isim` parametresine bağlı olarak, farklı isimlere hitap edebilir.

Fonksiyonu çağırmak için, `merhaba_isim()` fonksiyonu kullanarak, parametre olarak bir isim vermemiz gerekir:
```php
merhaba_isim("Serkan"); // "Merhaba Serkan!" metni ekrana yazdırılacak
```
## Fonksiyonlardan Değer Döndürme

Bir fonksiyon, bir değer döndürebilir. Değer, `return` anahtar kelimesi kullanılarak belirtilir. Fonksiyonun sonunda, `return` anahtar kelimesi kullanılarak döndürülecek değer belirtilir.

Aşağıdaki örnekte, `topla()` fonksiyonu iki sayının toplamını döndürecek şekilde tanımlanmıştır:
```php
function topla($sayi1, $sayi2) {
    return $sayi1 + $sayi2;
}
```
Bu fonksiyon, iki sayının toplamını döndürecektir. Fonksiyonu çağırmak için, `echo` veya `print` gibi bir fonksiyon kullanabiliriz:
```php
echo topla(3, 4); // 7
```
## Fonksiyonların Varsayılan Değerleri

Bir fonksiyonun parametreleri, varsayılan değerlerle belirtilebilir. Bu sayede, fonksiyon çağrılırken bu parametrelere değer verilmediği zaman, fonksiyon bu varsayılan değerleri kullanacaktır.

Aşağıdaki örnekte, `merhaba_isim()` fonksiyonu, isim parametresinin varsayılan değerini "dünya" olarak belirtilmiştir:
```php
function merhaba_isim($isim = "dünya") {
    echo "Merhaba " . $isim . "!";
}
```
Eğer bu fonksiyon çağrılırken bir isim belirtilmezse, fonksiyon varsayılan değer olan "dünya"yı kullanacaktır
```php
merhaba_isim(); // "Merhaba dünya!" metni ekrana yazdırılacak
```
Eğer bir isim belirtilirse, fonksiyon bu ismi kullanacaktır:
```php
merhaba_isim("Serkan"); // "Merhaba Serkan!" metni ekrana yazdırılacak
```
## Fonksiyonların Kapsamı

Bir fonksiyonun değişkenleri, fonksiyonun kapsamı içinde tanımlanır. Bu değişkenler, fonksiyonun dışında kullanılamazlar. Eğer bir değişken, fonksiyonun içinde tanımlanmamışsa, bu değişken fonksiyonun dışında kullanılabilir.

Aşağıdaki örnekte, `topla()` fonksiyonu, iki sayının toplamını hesaplar ve sonucu geri döndürür. Bu fonksiyonda, `$sonuc` değişkeni, sadece fonksiyonun içinde tanımlanmıştır ve fonksiyon dışında kullanılmaz.
```php
function topla($sayi1, $sayi2) {
    $sonuc = $sayi1 + $sayi2;
    return $sonuc;
}
```
Eğer `$sonuc` değişkeni fonksiyonun dışında kullanılmak istenirse, fonksiyonun sonunda `return` anahtar kelimesi kullanılarak döndürülmelidir:
```php
function topla($sayi1, $sayi2) {
    $sonuc = $sayi1 + $sayi2;
    return $sonuc;
}

$sonuc = topla(3, 4);
echo $sonuc; // 7

```
Burada, `$sonuc` değişkeni fonksiyon içinde tanımlanmış, hesaplanmış ve `return` anahtar kelimesi ile döndürülmüştür. Döndürülen bu değer, `$sonuc` değişkenine atanarak fonksiyon dışında kullanılabilir hale getirilmiştir.

# Gün 6: PHP Diziler

Diziler, belirli bir türdeki verileri tutmak için kullanılan veri yapılarıdır. Diziler, tek bir değişken içinde çok sayıda değer saklamak için kullanılabilir. PHP'de, diziler iki türde olabilir: indisli diziler ve ilişkisel diziler.

## İndisli Diziler

İndisli diziler, her öğenin bir indis numarası ile belirtildiği dizilerdir. İndis numaraları sıfırdan başlar ve her öğenin farklı bir indis numarası vardır. İndisli diziler, "array()" fonksiyonu veya kısa sözdizimi ile oluşturulabilir. Örneğin:
```php
<?php
$numbers = array(1, 2, 3, 4, 5);
echo "Dizinin üçüncü elemanı: " . $numbers[2];
?>
```
Bu örnekte, $numbers dizisi "array()" fonksiyonu ile oluşturulmuştur. Dizi içindeki öğelere erişmek için, öğenin indis numarasını kullanarak diziye erişilir. Sonuç olarak, ekranda "The third element of the array is: 3" mesajı görüntülenecektir.

## İlişkisel Diziler

İlişkisel diziler, öğelerin anahtar-değer çiftleri olarak saklandığı dizilerdir. İlişkisel diziler, "array()" fonksiyonu veya kısa sözdizimi ile oluşturulabilir. Anahtarlar, diziye eklenen öğelerin isimleri olarak kullanılır ve değerler, anahtarlarla eşleştirilir. Örneğin:
```php
<?php
$person = array(
    "name" => "Serkan",
    "age" => 25,
    "city" => "Kocaeli"
);
echo "Kişinin adı: " . $person["name"];
?>
```
Bu örnekte, $person dizisi, "name", "age" ve "city" anahtarlarına sahip öğelerle oluşturulur. Öğelere erişmek için, öğenin anahtarını kullanarak diziye erişilir. Sonuç olarak, ekranda "The person's name is: John" mesajı görüntülenecektir.

## Dizi Fonksiyonları

PHP'de, diziler için birçok faydalı fonksiyon bulunmaktadır. Bazı yaygın kullanılan dizi fonksiyonları şunlardır:

-   count() - Dizideki öğe sayısını döndürür.
-   sort() - Diziyi küçükten büyüğe sıralar.
-   rsort() - Diziyi büyükten küçüğe sıralar.
-   array_push() - Dizinin sonuna bir veya daha fazla öğe ekler.
-   array_pop() - Dizinin sonundan bir öğe çıkarır.

Örneğin, "count()" fonksiyonu ile bir dizinin eleman sayısı bulunabilir:
```php
<?php
$numbers = array(1, 2, 3, 4, 5);
$count = count($numbers);
echo "Dizideki eleman sayısı: " . $count;
?>
```
Bu örnekte, "count()" fonksiyonu, $numbers dizisindeki öğe sayısını döndürür. Sonuç olarak, ekranda "The number of elements in the array is: 5" mesajı görüntülenecektir.
### sort()

Diziyi sıralar. Örneğin:
```php
<?php
$numbers = array(5, 4, 3, 2, 1);
sort($numbers);
echo "Sıralanmış dizi: ";
foreach ($numbers as $num) {
    echo $num . " ";
}
?>
```
Bu örnekte, "sort()" fonksiyonu, $numbers dizisindeki öğeleri sıralar. Dizideki öğeler artan sıraya göre sıralanır. Sonuç olarak, ekranda "The sorted array is: 1 2 3 4 5" mesajı görüntülenecektir.

### array_push()

Diziye bir veya daha fazla öğe ekler. Örneğin:
```php
<?php
$fruits = array("elma", "portakal");
array_push($fruits, "muz", "armut");
echo "Güncellenmiş dizi: ";
foreach ($fruits as $fruit) {
    echo $fruit . " ";
}
?>
```
Bu örnekte, "array_push()" fonksiyonu, $fruits dizisine "banana" ve "pear" öğelerini ekler. Sonuç olarak, ekranda "The updated array is: apple orange banana pear" mesajı görüntülenecektir.

## Özet  
Bugünkü makalede, PHP  dizileri  hakkında  temel  bilgileri öğrendik. Diziler, birden çok  değeri  saklamak  ve  işlemek  için  kullanışlı bir  veri  yapısıdır. Dizilerin  tanımlanması, elemanlarına  erişimi, elemanlarını değiştirme, döngülerle  işleme  ve  fonksiyonlarla  işleme  konularını ele  aldık. İlerideki  makalelerde, dizilerin  daha  gelişmiş konularını ele  alacağız.

# Gün 7: Dosya İşlemleri
PHP'de dosya işlemleri için kullanabileceğimiz bazı fonksiyonlar vardır. Bu fonksiyonlar dosya okuma, yazma, silme, taşıma vb. işlemleri gerçekleştirmemize yardımcı olur.

### Dosya Oluşturma ve Yazma

PHP'de dosya oluşturmak ve yazmak için `fopen()` ve `fwrite()` fonksiyonlarını kullanabiliriz. `fopen()` fonksiyonu belirtilen dosyayı açar ve dosya işaretçisini döndürür. Bu işaretçi, dosyadaki konumumuzu tutar. `fwrite()` fonksiyonu ise, belirtilen dosyaya yazmak için kullanılır.
```php
<?php
$dosya = fopen("test.txt", "w");
fwrite($dosya, "Merhaba Dünya!");
fclose($dosya);
?>
```
Yukarıdaki kod, "test.txt" adlı bir dosya oluşturacak ve içine "Merhaba Dünya!" yazacaktır.

### Dosya Okuma

PHP'de dosya okumak için `fread()` fonksiyonunu kullanabiliriz. Bu fonksiyon, belirtilen dosyadan belirli bir sayıda bayt okur.
```php
<?php
$dosya = fopen("test.txt", "r");
$icerik = fread($dosya, filesize("test.txt"));
fclose($dosya);
echo $icerik;
?>
```
### Dosya Silme İşlemleri

PHP'de dosya silme işlemi yapmak için unlink() fonksiyonu kullanılır.
```php
<?php
if(unlink("dosya.txt")) {
  echo "Dosya silindi.";
} else {
  echo "Dosya silinemedi.";
}
?>
```
### Dosya Taşıma İşlemleri

PHP'de dosya taşıma işlemi yapmak için rename() fonksiyonu kullanılır.
```php
<?php
if(rename("eski_dosya.txt", "yeni_dosya.txt")) {
  echo "Dosya taşındı.";
} else {
  echo "Dosya taşınamadı.";
}
?>
```
Bu örnekler, PHP'de dosya işlemleri yapmanız için gerekli olan temel fonksiyonları göstermektedir. Bu fonksiyonları kullanarak, dosya işlemlerini kolayca yapabilirsiniz.


# Gün 8: PHP Veritabanı İşlemleri
PHP ile veritabanı işlemleri yapmak için PDO (PHP Data Objects) veya mysqli (MySQL Improved) gibi bir veritabanı sürücüsü kullanabilirsiniz. Bu sürücüler, MySQL, PostgreSQL, SQLite vb. gibi farklı veritabanı yöneticileriyle etkileşim kurmanıza olanak tanır. İşte bazı örnekler:

### PDO Kullanarak Veritabanına Bağlanma
```php
<?php
$host = 'localhost';
$dbname = 'my_database';
$username = 'my_username';
$password = 'my_password';

try {
  $conn = new PDO("mysql:host=$host;dbname=$dbname", $username, $password);
  echo "Veritabanına başarıyla bağlandı!";
} catch(PDOException $e) {
  echo "Bağlantı hatası: " . $e->getMessage();
}

?>
```
### mysqli Kullanarak Veritabanına Bağlanma
```php
<?php
$host = 'localhost';
$dbname = 'my_database';
$username = 'my_username';
$password = 'my_password';

$conn = mysqli_connect($host, $username, $password, $dbname);

if(!$conn) {
  die("Bağlantı hatası: " . mysqli_connect_error());
}

echo "Veritabanına başarıyla bağlandı!";

?>
```
### PDO Kullanarak Veri Ekleme
```php
<?php
$stmt = $conn->prepare("INSERT INTO users (name, email) VALUES (:name, :email)");
$stmt->bindParam(':name', $name);
$stmt->bindParam(':email', $email);

$name = 'John Doe';
$email = 'john.doe@example.com';

$stmt->execute();

echo "Veri başarıyla eklendi!";

?>
```
### mysqli Kullanarak Veri Ekleme
```php
<?php
$sql = "INSERT INTO users (name, email) VALUES ('$name', '$email')";

if(mysqli_query($conn, $sql)) {
  echo "Veri başarıyla eklendi!";
} else {
  echo "Veri eklenirken hata oluştu: " . mysqli_error($conn);
}

?>
```
### PDO Kullanarak Veri Seçme
```php
<?php
$stmt = $conn->prepare("SELECT * FROM users WHERE id=:id");
$stmt->bindParam(':id', $id);
$id = 1;
$stmt->execute();

$result = $stmt->fetch(PDO::FETCH_ASSOC);

echo "Kullanıcı Adı: " . $result['name'] . "<br>";
echo "E-posta Adresi: " . $result['email'];

?>
```
### mysqli Kullanarak Veri Seçme
```php
<?php
$sql = "SELECT * FROM users WHERE id=1";
$result = mysqli_query($conn, $sql);

if(mysqli_num_rows($result) > 0) {
  $row = mysqli_fetch_assoc($result);
  echo "Kullanıcı Adı: " . $row['name'] . "<br>";
  echo "E-posta Adresi: " . $row['email'];
} else {
  echo "Veri bulunamadı.";
}

?>
```
Bu örnekler, PDO ve mysqli kullanarak PHP'de veritabanı işlemlerini yapmak için gerekli olan temel işlemleri göstermektedir. Bu sürücülerin sağladığı diğer işlevleri de kullanarak, veritabanı işlemlerini daha da geliştirebilirsiniz.

# Gün 9: PHP Object-Oriented Programming (OOP)
PHP'de Nesne Yönelimli Programlama (OOP), sınıflar ve nesneler kullanarak programlama yapmanızı sağlar. Sınıflar, bir nesnenin özelliklerini (ör. değişkenler) ve davranışlarını (ör. yöntemler) tanımlar. Nesneler, bir sınıftan türetilen örneklerdir. Bu, bir sınıfın özelliklerini ve davranışlarını kullanarak özelleştirilmiş nesneler oluşturmanıza olanak tanır. İşte birkaç örnek:

### Bir Sınıf Tanımlama

```php
class Person {
  public $name;
  public $age;

  function __construct($name, $age) {
    $this->name = $name;
    $this->age = $age;
  }

  function getDetails() {
    return "Adı: " . $this->name . "<br>Yaşı: " . $this->age;
  }
}

?>
```
Bu örnekte, "Person" adında bir sınıf tanımladık. Bu sınıf, "name" ve "age" adında iki özellik içerir ve "getDetails" adında bir yönteme sahiptir. Ayrıca, sınıfın kurucu yöntemi "__construct" tanımlanmıştır.

### Bir Nesne Oluşturma
```php
<?php
$person = new Person("John Doe", 30);
?>
```
Bu örnekte, "Person" sınıfından bir nesne oluşturduk ve "John Doe" adında bir kişiyi ve 30 yaşını temsil etti.

### Nesne Özelliklerine Erişim
```php
<?php
echo $person->name;
echo $person->age;
?>
```
Bu örnekte, "Person" nesnesinin "name" ve "age" özelliklerine erişiyoruz.

### Nesne Yöntemlerini Kullanma
```php
<?php
echo $person->getDetails();
?>
```
Bu örnekte, "Person" nesnesinin "getDetails" yöntemini kullanarak kişi ayrıntılarını getiriyoruz.

### Kalıtım (Inheritance)
```php
<?php
class Student extends Person {
  public $studentID;

  function __construct($name, $age, $studentID) {
    parent::__construct($name, $age);
    $this->studentID = $studentID;
  }

  function getDetails() {
    return parent::getDetails() . "<br>Öğrenci Numarası: " . $this->studentID;
  }
}

$student = new Student("Serkan", 25, "12345");
echo $student->getDetails();

?>
```

Bu örnekte, "Student" sınıfı, "Person" sınıfından kalıtım alır. Bu, "Student" sınıfının "name" ve "age" özelliklerini "Person" sınıfından almasını sağlar. Ayrıca, "studentID" adında başka bir özellik ve "getDetails" yönteminde bir değişiklik yaparak öğrenci numarasını da dahil eder.

Bu örnekler, PHP'de nesne yönelimli programlama (OOP) konseptlerini gösterir. Bu örnekler, sınıflar ve nesneler oluşturma, özelliklere ve yöntemlere erişim, kurucu yöntemler, kalıtım ve yöntem geçersiz kılma gibi temel OOP konularını kapsamaktadır.

### Soyut Sınıflar (Abstract Classes)
```php
<?php
abstract class Animal {
  public $name;

  public function __construct($name) {
    $this->name = $name;
  }

  abstract public function makeSound();
}

class Dog extends Animal {
  public function makeSound() {
    echo "Hav! Hav!";
  }
}

$dog = new Dog("Fido");
echo $dog->name . " says ";
$dog->makeSound();

?>
```
Bu örnekte, "Animal" adında bir soyut sınıf tanımladık. Bu sınıfın bir özelliği ("name") ve soyut bir yöntemi ("makeSound") var. "makeSound" yöntemi, alt sınıflar tarafından geçersiz kılınmak zorundadır.

"Dog" adlı bir sınıf tanımladık ve "Animal" sınıfından kalıtım aldık. Bu sınıf, "makeSound" yöntemini geçersiz kılınarak köpeklerin havlaması için bir metin yazdırır.

### Arabirimler (Interfaces)
```php
<?php
interface Animal {
  public function makeSound();
}

class Dog implements Animal {
  public function makeSound() {
    echo "Hav! Hav!";
  }
}

$dog = new Dog();
$dog->makeSound();

?>
```
Bu örnekte, "Animal" adında bir arabirim tanımladık. Bu arabirim, "makeSound" adında bir yöntem içerir.

"Dog" adlı bir sınıf tanımladık ve "Animal" arabirimini uygulayarak "makeSound" yöntemini geçersiz kılar.

Bu örnekler, PHP'de nesne yönelimli programlama konularını gösterir. Bu konular, büyük ölçüde uygulama ve tasarım tercihlerine bağlı olarak farklı şekillerde kullanılabilir. OOP, özellikle büyük projelerde, daha iyi bir kod organizasyonu, daha kolay bakım ve daha fazla esneklik sağlayabilir.

### Kapsülleme (Encapsulation)
Kapsülleme, OOP'nin temel prensiplerinden biridir ve sınıfın içindeki verilerin ve işlevlerin korunmasına izin verir. Bu, sınıfın dışındaki kodun doğrudan sınıfın özelliklerine ve yöntemlerine erişememesi anlamına gelir.

Kapsülleme, sınıfın özelliklerini özel olarak işaretleyerek ve yöntemlere get ve set yöntemleri ekleyerek sağlanabilir. Bu yöntemler, sınıfın dışındaki kodun özelliklere erişmesine izin verirken, veri doğruluğunu kontrol etmek ve sınıfın iç yapısını korumak için kullanılabilir.
```php
<?php
class Person {
  private $name;
  private $age;

  public function setName($name) {
    $this->name = $name;
  }

  public function getName() {
    return $this->name;
  }

  public function setAge($age) {
    if ($age < 0) {
      throw new Exception("Yaş pozitif bir sayı olmalıdır");
    }
    $this->age = $age;
  }

  public function getAge() {
    return $this->age;
  }
}

$person = new Person();
$person->setName("Serkan");
$person->setAge(30);

echo $person->getName() . " ben" . $person->getAge() . " yaşındayım.";

?>
```
Bu örnekte, "Person" adında bir sınıf tanımladık ve "name" ve "age" adında özel özellikler içerir.

"name" ve "age" özelliklerine erişim, "setName", "getName", "setAge" ve "getAge" adında dört yöntem aracılığıyla yapılır. "setName" ve "setAge" yöntemleri, veri doğruluğunu kontrol etmek için kullanılır ve "getAge" ve "getName" yöntemleri, özelliklere erişim sağlar.

## PHP Polimorfizm (Polymorphism) ve Arayüzler (Interfaces)

PHP'de Polimorfizm ve Arayüzler, nesne yönelimli programlama konseptleri arasında yer almaktadır. Polimorfizm, aynı isimde farklı davranışlar sergileyen nesnelerin kullanılabilmesine olanak tanırken, Arayüzler, bir sınıfın belirli bir davranış kümesine sahip olduğunu belirtir.

### Polimorfizm

Polimorfizm, farklı nesnelerin aynı metodları kullanarak farklı davranışlar sergilemesini ifade eder. Bu, farklı sınıfların aynı yöntem isimlerini kullanarak farklı işlevler yerine getirmeleri anlamına gelir.

```php
interface Shape {
   public function area();
}

class Square implements Shape {
   private $side;

   public function __construct($side) {
      $this->side = $side;
   }

   public function area() {
      return $this->side * $this->side;
   }
}

class Circle implements Shape {
   private $radius;

   public function __construct($radius) {
      $this->radius = $radius;
   }

   public function area() {
      return $this->radius * $this->radius * pi();
   }
}

$square = new Square(5);
$circle = new Circle(3);

echo "Kare Alan: " . $square->area() . "<br>";
echo "Daire Alanı: " . $circle->area();

?>
```

### İsim Uzayları (Namespaces)
```php
<?php
namespace Animals;

class Dog {
  public function bark() {
    echo "Hav! Hav!";
  }
}

namespace Birds;

class Parrot {
  public function speak() {
    echo "Polly kraker istiyor!";
  }
}

?>
```

Bu örnekte, "Animals" ve "Birds" adında iki farklı isim uzayı tanımladık. Her isim uzayı, aynı sınıf adına sahip sınıflar içerebilir, ancak her isim uzayı, sınıflarının adını benzersiz bir şekilde belirtir.

Bu örnekte "Dog" adlı bir sınıf, "Animals" isim uzayında ve "Parrot" adlı bir sınıf "Birds" isim uzayında tanımlanmıştır.

### Magic Yöntemler (Magic Methods)
```php
<?php
class Person {
  private $name;

  public function __construct($name) {
    $this->name = $name;
  }

  public function __toString() {
    return $this->name;
  }
}

$person = new Person("John");
echo $person; // "John" yazdırır

?>
```
Bu örnekte, "Person" adında bir sınıf tanımladık ve "name" adında özel bir özellik tanımladık. Ayrıca, "__toString" adında bir "magic method" (sihirli yöntem) tanımladık. Bu yöntem, nesne dizesine dönüştürüldüğünde çağrılır ve burada sadece "name" özelliği döndürülür.
### Oluşturucu Yöntemler (Constructor Methods)
```php
<?php
class Person {
  public $name;

  public function __construct($name) {
    $this->name = $name;
  }

  public function sayHello() {
    echo "Selam, benim adım: " . $this->name . "!";
  }
}

$person = new Person("Serkan");
$person->sayHello();

?>
```
Bu örnekte, "Person" adlı bir sınıf tanımladık ve "name" adında bir özelliği ("John" adlı bir kişinin adı) var.

"Sözde yapıcı" yöntemi olan "__construct" yöntemini tanımladık. Bu yöntem, sınıfın bir nesnesi oluşturulduğunda otomatik olarak çağrılır ve özellikleri ayarlamak için kullanılabilir.

"sayHello" adında bir yöntem tanımladık. Bu yöntem, "name" özelliğini kullanarak bir "Merhaba" mesajı oluşturur ve yazdırır.

### Yöntem Geçersiz Kılma (Method Overriding)
```php
class Animal {
  public function makeSound() {
    echo "Unknown sound";
  }
}

class Dog extends Animal {
  public function makeSound() {
    echo "Hav! Hav!";
  }
}

$animal = new Animal();
$animal->makeSound();

$dog = new Dog();
$dog->makeSound();

?>
```
Bu örnekte, "Animal" adında bir sınıf tanımladık ve "makeSound" adında bir yöntemi var.

"Dog" adlı bir sınıf tanımladık ve "Animal" sınıfından kalıtım aldık. "makeSound" yöntemini geçersiz kılarak köpeklerin havlaması için bir metin yazdırır.

"Animal" sınıfından bir nesne ve "Dog" sınıfından bir nesne oluşturduk ve her biri kendi "makeSound" yöntemini çağırdı.

### Final Anahtar Kelimesi (Final Keyword)
`final` anahtar kelimesi, sınıf veya sınıf üyelerinin (metodlar ve özellikler) alt sınıflar tarafından değiştirilemez olduğunu belirtmek için kullanılır. Bu, sınıfın başka bir sınıf tarafından genişletilemeyeceği ve sınıf üyelerinin değiştirilemeyeceği anlamına gelir.

### `final` Sınıflar

`final` anahtar kelimesi, bir sınıfın başka bir sınıf tarafından genişletilemeyeceği anlamına gelir. Bu, `final` olarak belirlenmiş bir sınıfın alt sınıfları olamayacağı anlamına gelir. Aşağıdaki örnek, `final` anahtar kelimesi ile işaretlenmiş bir sınıfı göstermektedir:
```php
<?php
final class FinalClass {
    // sınıf kodları
}
?>
```
Bu sınıfı başka bir sınıf tarafından genişletmeye çalışırsanız, bir hata mesajı alırsınız:
```php
<?php
class ChildClass extends FinalClass {
    // hata mesajı: Cannot extend final class FinalClass
}
?>
```
### Özetle

`Final` anahtar kelimesi, bir sınıfın veya öğenin değiştirilemez olduğunu belirtmek için kullanılır. Bu kısıtlama, bir sınıfın veya öğenin alt sınıflar tarafından değiştirilemeyeceği anlamına gelir. Bu, bir uygulamanın belirli bir sınıfın veya öğenin davranışını garanti altına almasına yardımcı olur.

# Gün 11: PHP Web Uygulamaları
PHP, web uygulamaları geliştirmek için popüler bir seçimdir. PHP, sunucu tarafında çalıştığından, web uygulamaları için ideal bir dildir. PHP, HTML, CSS ve JavaScript gibi diğer web teknolojileriyle kolayca birleştirilebilir.

### PHP Web Uygulamaları Örnekleri

#### Form İşleme

Web uygulamaları, kullanıcıların verileri sunucuya göndermesi için formlar kullanır. Bu formlar, kullanıcının girdiği verileri PHP tarafında işlemek için kullanılır. Örneğin, bir kullanıcının bir ad, soyad ve e-posta adresi girmesini isteyen bir form oluşturabiliriz. Bu verileri sunucuya gönderdikten sonra, PHP tarafında bu verileri alabilir, doğrulayabilir ve bir veri tabanına kaydedebiliriz.
```php
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
  // Form verilerini al
  $name = $_POST["name"];
  $surname = $_POST["surname"];
  $email = $_POST["email"];

  // Form verilerini işle
  // ...

  // Veritabanına kaydet
  // ...
}
?>

<form method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>">
  Ad: <input type="text" name="name"><br>
  Soyad: <input type="text" name="surname"><br>
  E-posta: <input type="text" name="email"><br>
  <input type="submit" value="Gönder">
</form>

?>
```
#### Oturum Yönetimi

Web uygulamaları, kullanıcının kimliğini doğrulamak ve oturum açıkken kullanıcının oturum bilgilerini saklamak için oturum yönetimi kullanır. PHP, bu işlevselliği kolayca sağlar. Örneğin, bir kullanıcının oturum açmasını isteyen bir uygulama oluşturabiliriz.

```php
<?php
session_start();

if ($_SERVER["REQUEST_METHOD"] == "POST") {
  // Kullanıcı adı ve şifreyi al
  $username = $_POST["username"];
  $password = $_POST["password"];

  // Kullanıcı adı ve şifre doğruysa oturum başlat
  if ($username == "admin" && $password == "1234") {
    $_SESSION["username"] = $username;
    header("Location: home.php");
    exit;
  } else {
    $error = "Kullanıcı adı veya şifre hatalı.";
  }
}
?>

<form method="post" action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]);?>">
  Kullanıcı Adı: <input type="text" name="username"><br>
  Şifre: <input type="password" name="password"><br>
  <input type="submit" value="Giriş">
</form>

?>
```
####  HTML ve CSS ile PHP Entegrasyonu

Web uygulamaları, genellikle veritabanlarıyla etkileşim halindedir. PHP, MySQL ve diğer veritabanlarıyla kolayca etk


```php
<!DOCTYPE html>
<html>
<head>
	<title>PHP ile Entegrasyon</title>
</head>
<body>

	<h1>Merhaba, <?php echo "Dünya"; ?>!</h1>

	<?php
		$yil = date("Y");
		$ay = date("m");
		$gun = date("d");
		$saat = date("H");
		$dakika = date("i");
		$saniye = date("s");
		echo "<p>Tarih: $gun/$ay/$yil Saat: $saat:$dakika:$saniye</p>";
	?>

</body>
</html>

?>
```
Yukarıdaki örnekte, `<?php ?>` etiketleri arasında PHP kodu yer alır. Bu kodlar, HTML kodunun içinde doğrudan kullanılabilir. Örneğin, yukarıdaki örnekte, `Merhaba, <?php echo "Dünya"; ?>!` satırında, `echo` fonksiyonu kullanılarak "Dünya" yazısı HTML içinde görüntülenir.

CSS kodu ve PHP kodu içeren bir örnek aşağıda verilmiştir:


```php
<?php
$name = "Serkan";
$age = 25;
?>
```



```php
<?php
<!DOCTYPE html>
<html>
<head>
	<title>PHP ile Entegrasyon</title>
	<style>
		<?php
			$renk = "blue";
			echo "body { background-color: $renk; }";
		?>
	</style>
</head>
<body>

	<h1>Merhaba, <?php echo "Dünya"; ?>!</h1>

	<?php
		$yil = date("Y");
		$ay = date("m");
		$gun = date("d");
		$saat = date("H");
		$dakika = date("i");
		$saniye = date("s");
		echo "<p>Tarih: $gun/$ay/$yil Saat: $saat:$dakika:$saniye</p>";
	?>

</body>
</html>

?>
```
Yukarıdaki örnekte, PHP kodu, `<style>` etiketleri arasında yer alır. Bu kodlar, CSS kodunun içinde doğrudan kullanılabilir. Örneğin, yukarıdaki örnekte, `$renk` değişkeni PHP kodu kullanılarak belirlenir ve `body` elementinin `background-color` özelliği belirlenir.

PHP, HTML ve CSS ile birlikte kullanıldığında, web siteleri dinamik hale gelebilir ve daha fazla işlevsellik sağlayabilir. Ancak, güvenliği sağlamak ve doğru çalışmayı sağlamak için en iyi uygulamaları kullanmak önemlidir.

### Form Doğrulama ve Hataların İşlenmesi
Web uygulamalarında, kullanıcıların girdiği verilerin doğruluğunu kontrol etmek ve hataların işlenmesi, güvenli ve kullanılabilir bir uygulama oluşturmak için önemlidir. PHP, form verilerinin doğruluğunu kontrol etmek ve hataları işlemek için birçok fonksiyon ve yöntem sağlar.

### Form Doğrulama

Form doğrulama, kullanıcıların girdiği verilerin doğruluğunu kontrol etmek için kullanılır. Bu işlem, verilerin uygun biçimde doldurulmasını sağlar ve hatalı girişlerin yapılmasını önler.

Form doğrulama için, PHP'de `filter_var()` fonksiyonu kullanılabilir. Bu fonksiyon, bir değerin belirli bir filtreden geçip geçmediğini kontrol eder. Örneğin, `FILTER_VALIDATE_EMAIL` filtresi, bir e-posta adresinin doğruluğunu kontrol eder.
```php
<?php
$email = $_POST["email"];

if (!filter_var($email, FILTER_VALIDATE_EMAIL)) {
    echo "Geçersiz e-posta adresi";
}

?>
```
Yukarıdaki örnekte, `$_POST` değişkeni ile gönderilen `email` verisi `filter_var()` fonksiyonu ile kontrol edilir ve eğer geçersizse bir hata mesajı gösterilir.

###  Oturum Yönetimi: $_SESSION ve $_COOKIE
PHP'de oturum yönetimi, kullanıcının siteye giriş yaptığında kullanıcı bilgilerini ve diğer verileri saklamak için kullanılır. Oturum yönetimi, PHP'de $_SESSION ve $_COOKIE değişkenleri kullanılarak gerçekleştirilir.

$_SESSION değişkeni, oturum bilgilerini saklamak için kullanılır. Oturum başlatıldığında, $_SESSION değişkeni boş bir dizi olarak oluşturulur ve oturum sırasında değiştirilebilir.

Örneğin, bir kullanıcının giriş yaptığı bir uygulama düşünelim. Kullanıcının giriş yaptığında, kullanıcı adı $_SESSION değişkenine kaydedilebilir ve diğer sayfalarda kullanılabilir. Örneğin:

```php
<?php
session_start(); // Oturum başlatma
$_SESSION["kullanici_adi"] = "serkanyalcin";
?>
```
Bu örnekte, oturum başlatılır ve $_SESSION değişkeni, "kullanici_adi" anahtarına sahip bir dizi olarak oluşturulur. Kullanıcı adı, diziye kaydedilir.

$_COOKIE değişkeni, tarayıcıda saklanan çerezlerle çalışır. Bir çerez, bir web sitesi tarafından tarayıcıya gönderilen küçük bir dosyadır ve tarayıcı tarafından saklanır. Çerezler, oturum bilgileri, kullanıcı tercihleri vb. gibi verileri depolamak için kullanılabilir.

Örneğin, bir kullanıcının tercihlerini saklamak için $_COOKIE kullanılabilir:

```php
<?php
setcookie("kullanici_tercihleri", "ornek_tercihler", time() + (86400 * 30), "/");
?>
```
Bu örnekte, "kullanici_tercihleri" adında bir çerez oluşturulur ve "ornek_tercihler" olarak ayarlanır. Çerez, tarayıcıda 30 gün boyunca saklanacak şekilde ayarlanır.

Özetle, $_SESSION ve $_COOKIE değişkenleri, PHP'de oturum yönetimi için kullanılır. $_SESSION değişkeni, sunucuda saklanan oturum bilgileri için kullanılırken, $_COOKIE değişkeni, tarayıcıda saklanan çerezlerle çalışır. Bu yöntemler, kullanıcıların siteye giriş yaparken ve diğer verileri saklamak istediklerinde kullanışlıdır.

Örneğin, bir oturum açma işlemi gerçekleştirirken, kullanıcının giriş yaptığı bilgileri $_SESSION değişkenine kaydedebiliriz. Daha sonra, kullanıcı diğer sayfalarda gezinirken, bu oturum bilgileri $_SESSION değişkeninde saklanır ve istediğimiz zaman kullanılabilir.

```php
<?php
session_start(); // Oturum başlatma
$_SESSION["kullanici_id"] = $kullanici_id;
?>
```
Bu örnekte, oturum başlatılır ve kullanıcının kimliği ve adı $_SESSION değişkenine kaydedilir. Bu bilgiler, kullanıcının giriş yaptığı sürece oturum boyunca saklanacaktır.

Öte yandan, çerezler $_COOKIE değişkeni kullanılarak oluşturulur ve saklanır. Örneğin, bir kullanıcının siteye son ziyaretinde seçtiği dil seçeneğini saklamak istediğimizi varsayalım. Bu bilgi bir çerezde saklanabilir ve kullanıcının sonraki ziyaretlerinde dil seçeneği otomatik olarak seçilebilir.

```php
<?php
$dil = "tr"; // varsayılan dil
if (isset($_COOKIE["dil"])) {
    $dil = $_COOKIE["dil"];
} else {
    setcookie("dil", $dil, time() + (86400 * 30), "/");
}
?>
```
Bu örnekte, "dil" adında bir çerez oluşturulur ve varsayılan olarak "tr" olarak ayarlanır. Kullanıcı daha önce bir dil seçtiyse, çerezden bu seçim alınır. Eğer bir dil seçimi yoksa, varsayılan dil çerezde kaydedilir.

Bu örnekler, oturum yönetimi için $_SESSION ve $_COOKIE değişkenlerinin nasıl kullanılabileceğini göstermektedir. Bu değişkenler, kullanıcıların oturum bilgilerini ve diğer verileri saklamak için çok kullanışlıdır. Ancak, güvenlik konusunda dikkatli olmak önemlidir.

# Gün 12: PHP Framework'leri
PHP Framework'leri, PHP ile web uygulamaları geliştirmek için kullanılan bir dizi kütüphane ve araç setidir. Framework'ler, birçok farklı görevi otomatikleştirir ve kolaylaştırır, böylece geliştiriciler uygulama kodlarına odaklanabilirler. Bu, web uygulamalarının daha hızlı, daha verimli ve daha güvenli bir şekilde geliştirilmesine olanak tanır.

İşte en popüler PHP Framework'lerinden bazıları:

## 1. Laravel

Laravel, açık kaynaklı bir PHP web uygulama framework'üdür ve MVC (Model-View-Controller) tasarım desenini kullanır. Laravel, kullanıcı kimlik doğrulaması, veritabanı yönetimi, hata işleme ve birçok diğer özellik sağlar. Laravel, özellikle RESTful API'lerin geliştirilmesi için popülerdir.

## 2. CodeIgniter

CodeIgniter, açık kaynaklı bir PHP web uygulama framework'üdür ve MVC tasarım desenini kullanır. CodeIgniter, küçük ve orta ölçekli web uygulamaları için tasarlanmıştır. Kodu basit ve anlaşılırdır, böylece yeni başlayanlar tarafından kolayca öğrenilebilir.

## 3. Symfony

Symfony, açık kaynaklı bir PHP framework'üdür ve PHP 7.1 ve üstü sürümlerini destekler. Symfony, MVC tasarım desenini kullanır ve esnek bir mimariye sahiptir. Symfony, web uygulamalarının yanı sıra, web hizmetleri ve mikro hizmetlerin geliştirilmesinde de kullanılabilir.

## 4. CakePHP

CakePHP, PHP dilindeki en eski Framework'lerden biridir ve MVC yapısına dayalıdır. Özellikle büyük ölçekli web uygulamaları için uygundur. CakePHP, basit bir öğrenme eğrisine sahip olmasının yanı sıra, birçok hazır bileşen içerir.

## 5. Zend Framework

Zend Framework, hızlı ve güvenli web uygulamaları geliştirmek için kullanılan bir PHP Framework'üdür. MVC yapısına dayalıdır ve birçok hazır bileşen içerir. Zend Framework, özellikle büyük ölçekli web uygulamaları için uygundur ve basit bir öğrenme eğrisine sahiptir.

Bu PHP Framework'leri, birçok farklı web uygulaması geliştirme senaryosuna uygunluk gösterirler. Laravel ve Symfony, büyük ölçekli web uygulamaları için uygunken, CodeIgniter ve CakePHP, küçük ve orta ölçekli web uygulamaları için daha uygun olabilir. Zend Framework ise, özellikle hızlı ve güvenli web uygulamaları geliştirmek için kullanılabilir.

## 6. Yii Framework

Yii Framework, hızlı ve güvenli web uygulamaları geliştirmek için kullanılan bir PHP Framework'üdür. MVC yapısına dayalıdır ve birçok hazır bileşen içerir. Özellikle büyük ölçekli web uygulamaları için uygundur. Yii Framework, birçok özellik sunar, örneğin Gii code generator, Active Record, i18n desteği ve authentication/authorization sistemi gibi. Ayrıca, performansıyla da dikkat çeker.

Yii Framework, özellikle büyük ölçekli web uygulamaları geliştirmek isteyenler için tercih edilebilir. İleri düzey özellikleri, kolay öğrenme eğrisi ve performansı ile öne çıkar.

# Gün 13: PHP ve Diğer Web Teknolojileri
PHP, web geliştirme için oldukça popüler bir dildir. Web teknolojileri arasında HTML, CSS, JavaScript, MySQL gibi diğer teknolojileri kullanarak etkileşimli ve dinamik web sayfaları oluşturmak için kullanılır. PHP'nin özellikleri arasında kolay öğrenme eğrisi, büyük topluluğu ve birçok hazır çözüm içeren birçok popüler framework yer alır.

## PHP ve JavaScript Entegrasyonu

PHP ve JavaScript, birbirinden farklı ama birbirini tamamlayan teknolojilerdir. PHP, sunucu tarafında çalışan bir dildir ve genellikle veritabanlarından veri alma, verileri işleme ve web sayfaları oluşturma için kullanılır. JavaScript ise, web tarayıcılarında çalışan bir dildir ve kullanıcı etkileşimleri, animasyonlar ve diğer görsel öğeler gibi işlevleri kontrol etmek için kullanılır.

PHP ve JavaScript arasındaki entegrasyon, web sayfalarının daha etkileşimli ve dinamik hale getirilmesine yardımcı olur. Bu entegrasyon, PHP tarafından oluşturulan verilerin JavaScript tarafından işlenmesi veya tam tersi, JavaScript tarafından oluşturulan verilerin PHP tarafından işlenmesi için kullanılır.

## AJAX ve jQuery ile Veri Yükleme

AJAX, Asenkron JavaScript ve XML anlamına gelir. Bu teknoloji, web sayfalarının daha etkileşimli hale getirilmesi için kullanılır. AJAX, sayfanın yenilenmesine gerek kalmadan verilerin gönderilmesine ve alınmasına olanak sağlar.

jQuery, JavaScript kütüphanelerinden biridir ve web geliştiricilerine AJAX ile veri yükleme, HTML/DOM işlemleri, animasyonlar, olay işleme ve diğer birçok işlev için bir dizi kolay kullanımlı araç sağlar.

AJAX ve jQuery, web geliştiricilerin veri yükleme işlemlerini kolaylaştırır ve web sayfalarının daha hızlı, daha etkileşimli ve daha duyarlı hale getirilmesine yardımcı olur.

## XML, JSON ve SOAP İşlemleri

XML ve JSON, web servislerinde sıklıkla kullanılan iki veri formatıdır. XML, genellikle verilerin yapısını açıklayan ve belirli bir kurallar kümesine göre yapılandırılan metin tabanlı bir formattır. JSON ise, kolayca okunabilir, hafif ve web uygulamaları için ideal olan bir veri formatıdır.

SOAP, Simple Object Access Protocol'ün kısaltmasıdır ve web servisleri için kullanılan bir protokoldür. SOAP, web uygulamalarının birbiriyle iletişim kurmasına olanak tanır. SOAP, XML tabanlı bir protokoldür ve web uyglamaları arasında veri alışverişi yapmak için kullanılır. Web servislerindeki veri alışverişi için genellikle XML veya JSON kullanılır.

## RESTful API ve Web Servisleri

RESTful API, Representational State Transfer anlamına gelir ve modern web uygulamaları için popüler bir web servisi arayüzüdür. RESTful API'ler, web uygulamaları arasında veri alışverişinin yapılmasına olanak sağlar. Bu API'ler, genellikle JSON veya XML formatında veri döndürürler ve birçok programlama dili tarafından desteklenirler.

Web servisleri, farklı platformlar arasında veri paylaşımına olanak tanıyan bir teknolojidir. Web servisleri, önceden belirlenmiş bir protokol ve veri formatı kullanarak veri alışverişi yaparlar. Bu sayede, farklı programlama dillerinde yazılmış uygulamalar arasında veri alışverişi yapmak mümkün hale gelir. Web servisleri genellikle SOAP veya RESTful API gibi teknolojiler kullanılarak geliştirilir.

# Gün 14: PHP Güvenliği
PHP, web uygulamaları için oldukça popüler bir programlama dilidir. Ancak, PHP uygulamaları da potansiyel olarak saldırılara açık olabilirler. Bu nedenle, güvenli bir PHP kodu yazmak son derece önemlidir.

### Güvenli Kodlama Uygulamaları

PHP kodunun güvenliği, kodun doğru şekilde yazılmasından başlar. Güvenli kodlama uygulamaları, kodun güvenliğini sağlamak için kullanılacak teknikler ve prosedürlerdir. Bu uygulamalar, kodun doğru şekilde yazılmasını, hata ayıklama, test ve güncelleme işlemlerinin yapılmasını ve güvenliği arttırmak için gerekli düzeltmelerin yapılmasını kapsar.

PHP uygulamaları için güvenli kodlama uygulamaları, güvenli kodlama standartlarına uyulmasını sağlayarak, uygulamaların güvenliğini artırır. Güvenli kodlama uygulamaları şunları içerebilir:

-   Güvenli bir veri tabanı bağlantısı sağlamak için PDO kullanmak
-   Veri girişlerini temizlemek için filtreleme işlevlerini kullanmak
-   Veri girişlerini doğrulamak için doğrulama işlevlerini kullanmak
-   SQL sorgularını hazırlamak için hazır işlevleri kullanmak
-   Şifreleme işlemleri için PHP'nin dahili şifreleme işlevlerini kullanmak
-   Kullanıcı girişleri gibi verilerin güvenli bir şekilde işlenmesi
-   Veritabanı sorgularının doğru şekilde yapılandırılması ve filtrelenmesi
-   Güvenli oturum yönetimi için oturum verilerinin doğru şekilde saklanması
-   PHP güncellemelerinin düzenli olarak yapılması

### XSS (Cross-Site Scripting) ve CSRF (Cross-Site Request Forgery)

XSS, Cross-Site Scripting anlamına gelir ve web uygulamalarının güvenliği için önemli bir tehdit oluşturur. XSS, web uygulamalarına kötü niyetli kodların enjekte edilmesi ile gerçekleşir. Bu kodlar, kullanıcıların tarayıcılarında çalıştırılabilir ve kullanıcıların gizli bilgilerini ele geçirme ya da zararlı işlemler gerçekleştirme amacıyla kullanılabilir.

CSRF, Cross-Site Request Forgery anlamına gelir ve bir kullanıcının tarayıcısı üzerinden, kötü niyetli bir web sitesi tarafından, bir başka web sitesindeki işlemleri gerçekleştirmesi için zorlanmasıdır. Bu işlemler, kullanıcının izni olmadan gerçekleştirilebilir ve örneğin, para transferi ya da hesap silme gibi ciddi sonuçlar doğurabilir.

### SQL Enjeksiyonu ve Önleme Yöntemleri

SQL enjeksiyonu, web uygulamalarına saldırmak için yaygın olarak kullanılan bir yöntemdir. SQL enjeksiyonu, web uygulamalarının güvenlik duvarlarını aşarak, veritabanı sorgularına kötü niyetli kodların enjekte edilmesi ile gerçekleşir. Bu kodlar, veritabanından bilgi çalmaya ya da veritabanındaki verileri değiştirmeye yöneliktir.

SQL enjeksiyonu önleme yöntemleri arasında, veritabanı sorgularının doğru şekilde yapılandırılması ve filtrelenmesi yer alır. Bu yöntemler, SQL enjeksiyonu saldırılarına karşı etkili bir koruma sağlayabilir.

## Güvenli Oturum Yönetimi ve Şifreleme

Güvenli oturum yönetimi, kullanıcıların oturum açma bilgilerinin korunmasını sağlar. Bu nedenle, oturum açma bilgileri (kullanıcı adı, şifre vb.) şifrelenmeli ve güvenli bir şekilde saklanmalıdır. Ayrıca, oturum süresi ve oturum verilerinin doğrulanması gibi önlemler alınmalıdır.

## Örnek Uygulama: Bir Şifre Yönetim Uygulaması

Bir şifre yönetim uygulaması, kullanıcıların farklı hesaplarının şifrelerini güvenli bir şekilde saklamasını sağlar. Bu tür bir uygulama, güvenli oturum yönetimi, şifreleme ve doğru veri doğrulama tekniklerini kullanarak güvenli bir şekilde girdi verilerini doğrulamalıdır. Ayrıca, SQL enjeksiyonu ve XSS gibi saldırılara karşı önlem alınmalıdır. Aşağıda, bir şifre yönetim uygulaması için alınabilecek güvenlik önlemlerinin bir özeti verilmiştir:
-   Kullanıcı şifreleri şifrelenerek depolanmalıdır. Bu, şifrelerin depolanırken çalınmasını veya görüntülenmesini engeller.
-   Kullanıcılar için güçlü şifreler zorunlu olmalıdır. Bu, saldırganların kolayca tahmin edebilecekleri zayıf şifrelerin kullanılmasını engeller.
-   Kullanıcıların girdi verileri doğrulanmalıdır. Bu, saldırganların kullanıcıların hesaplarına erişmelerine izin veren kötü amaçlı girdileri enjekte etmelerini engeller.
-   Güvenli oturum yönetimi kullanılmalıdır. Bu, kullanıcıların oturum açma bilgilerinin korunmasını sağlar.
-   XSS ve CSRF gibi saldırılara karşı önlem alınmalıdır. Bu, saldırganların web uygulamasına kötü amaçlı kodları enjekte etmelerine veya istemci taraflı işlemleri gerçekleştirmelerine izin vermez.

PHP, performans açısından oldukça hızlı bir dil olsa da, kodunuzda yapılan hatalar veya yanlış kullanımlar, uygulamanızın performansını olumsuz yönde etkileyebilir. Bu nedenle, performansı ölçmek ve iyileştirmek önemlidir.

Performans ölçümü yapmak için, kodunuzu belirli bir süre içinde çalıştıran ölçüm araçları kullanabilirsiniz. Bu araçlar, kodunuzun çalışma süresi, bellek kullanımı ve diğer performans ölçümlerini yapar ve sonuçları size raporlar. Örneğin, Xdebug, PHP'nin bir hata ayıklama aracıdır ve kodunuzu çalıştırırken performansı izleyebilmenize olanak tanır.

## Kod Optimize Etme ve İyileştirme

Performansı artırmak için, kodunuzu optimize etmeniz ve iyileştirmeniz gerekir. Örneğin, döngülerinizi, koşullu ifadelerinizi ve sorgularınızı daha verimli hale getirebilirsiniz.

Bunun yanı sıra, PHP'nin önbellekleme özelliğini kullanabilirsiniz. Önbellekleme, kodunuzun tekrar tekrar çalıştırılması gereken bölümlerinin önbelleğe alınmasını sağlar. Bu sayede, tekrarlanan işlemler daha hızlı gerçekleştirilir.

## Debugging Araçları: Xdebug, var_dump, error_reporting vb.

Debugging, kodunuzdaki hataları bulmak ve düzeltmek için kullanılan bir yöntemdir. PHP'de debugging yapmak için birçok araç vardır. Xdebug, PHP'nin bir hata ayıklama aracıdır ve kodunuzu çalıştırırken hataları yakalamanıza olanak tanır. var_dump() fonksiyonu, değişkenlerin içeriğini gösterir ve hata ayıklama sürecinde kullanılabilir. error_reporting() fonksiyonu, PHP hatalarının hangi düzeyde raporlanacağını belirlemenize olanak tanır.

## Hata Ayıklama ve Hata Yakalama Yöntemleri

PHP'de hata ayıklama ve hata yakalama işlemleri için birçok yöntem vardır. try-catch blokları, kodunuzdaki belirli hataların yönetilmesine olanak tanır. PHP'nin error_log() fonksiyonu, hataları bir dosyaya veya veritabanına kaydetmenizi sağlar. Ayrıca, PHP'nin hata raporlama özelliği sayesinde, hataların nedenlerini ve hangi satırda oluştuğunu öğrenebilirsiniz.

## Debugging Araçları

### Xdebug

Xdebug, PHP uygulamalarını hata ayıklama ve performans ölçümü yapmak için kullanılan bir araçtır. Xdebug, PHP sürümüne bağlı olarak farklı yollarla kurulabilir. Xdebug'ın temel özellikleri arasında:

-   Kodun çalışması durdurulduğunda otomatik olarak hata ayıklama moduna geçer
-   Kodun herhangi bir noktasında kesme noktaları eklemek mümkündür
-   Çalışma sırasında değişken değerlerini görüntülemek için kullanılabilir
-   Kodun yavaş çalıştığı noktaları tespit etmek için kullanılabilir

Xdebug'ın yararlı özellikleri, geliştiricilerin hata ayıklama yapmasını kolaylaştırır ve uygulamaların daha iyi performans göstermesine yardımcı olabilir.

### Kod Optimize Etme ve İyileştirme

PHP'de performansı iyileştirmenin bir yolu, kodu optimize etmek ve daha verimli hale getirmektir. Bunun için aşağıdaki teknikleri kullanabilirsiniz:

-   Doğru veri yapısını kullanın: Veri yapılarının seçimi performansı önemli ölçüde etkileyebilir. Örneğin, bir dizi kullanmak yerine, daha hızlı ve daha verimli bir veri yapısı olan bir sözlük kullanmayı düşünebilirsiniz.
    
-   Loops ve döngülerden kaçının: Döngüler, özellikle iç içe döngüler, performansı önemli ölçüde azaltabilir. Bunun yerine, array_map (), array_walk (), array_filter () gibi PHP işlevlerini kullanmayı düşünebilirsiniz.
    
-   Sorgu sayısını azaltın: Sorgu sayısını azaltmak, veritabanı performansını önemli ölçüde artırabilir. Bunun için, verileri tek bir sorgu ile getirmeyi ve ardından bu verileri PHP'de işlemeyi düşünebilirsiniz.
    
-   Kodunuzu önbelleğe alın: PHP, kodunuzu önbelleğe alarak daha hızlı çalışmasını sağlayabilir. Bu, özellikle büyük bir proje veya sık kullanılan bir işlev için geçerlidir.
