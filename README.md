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

## İlk PHP Programı

Bir PHP programı, .php uzantılı bir dosyada saklanabilir. Örneğin, hello.php adında bir dosya oluşturup içine aşağıdaki kodları yazabilirsiniz:
```php
<?php  echo  "Hello, World!"; ?>
```

Bu kod, "Hello, World!" metnini ekrana yazdıracaktır.

# Gün 2: PHP Değişkenleri ve Veri Türleri

## Değişkenler

Değişkenler, değerleri saklamak için kullanılan öğelerdir. PHP'de bir değişken, dolar işareti ($) ile başlar ve harf veya alt çizgi (_) ile devam eder. Örneğin:

```php
<?php
$name = "John";
$age = 25;
?>
```

Bu örnekte, $name değişkeni "John" değerini, $age değişkeni ise 25 değerini saklar.

## Veri Türleri

PHP'de kullanabileceğiniz farklı veri türleri vardır. En yaygın veri türleri şunlardır:

-   String: Metin verileri için kullanılır. Örneğin: "Hello, World!"
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
$name = "John";
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

# Gün 4: PHP Döngüleri

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
    echo "The number is: $x <br>";
    $x++;
} while ($x <= 10);
?>
```
Bu örnekte, do-while döngüsü, $x değişkeninin 10'dan küçük veya eşit olup olmadığını kontrol eder. İlk yinelemede $x değeri 0 olduğu için, kod bloğu çalıştırılır ve ekranda "The number is: 0" mesajı görüntülenir. Sonraki yinelemelerde, $x değeri artırılır ve koşul doğru olduğu sürece kod bloğu tekrar çalıştırılır. Sonuç olarak, ekranda 0'dan 10'a kadar olan sayılar görüntülenecektir.

# Gün 5: PHP Fonksiyonları

Fonksiyonlar, belirli bir işlevi yerine getirmek için kullanılan kod bloklarıdır. Fonksiyonlar, kodun yeniden kullanılabilirliğini artırır ve programlama işini daha modüler hale getirir. Bir fonksiyon oluşturmak için, "function" anahtar kelimesi kullanılır. Örneğin:
```php
<?php
function addNumbers($a, $b) {
    $sum = $a + $b;
    return $sum;
}
echo "5 ve 10'un toplamı: " . addNumbers(5, 10);
?>
```
Bu örnekte, addNumbers() fonksiyonu, $a ve $b parametrelerini alır ve bu parametreleri toplar. Daha sonra, toplam değer "return" ifadesi ile geri döndürülür. Fonksiyon çağrısı, "echo" ifadesi ile yapılır ve sonuç ekrana yazdırılır. Sonuç olarak, ekranda "The sum of 5 and 10 is: 15" mesajı görüntülenecektir.

## Değişken Alan Fonksiyonlar

Değişken alan fonksiyonlar, fonksiyonlara değişken sayıda parametre geçmek için kullanılır. Bu fonksiyonlar, "func_num_args()", "func_get_arg()" ve "func_get_args()" fonksiyonları kullanılarak çalışır. Örneğin:
```php
<?php
function addNumbers() {
    $sum = 0;
    $numArgs = func_num_args();
    for ($i = 0; $i < $numArgs; $i++) {
        $sum += func_get_arg($i);
    }
    return $sum;
}
echo "1, 2, 3, 4 ve 5'in toplamı: " . addNumbers(1, 2, 3, 4, 5);
?>
```
Bu örnekte, addNumbers() fonksiyonu değişken sayıda parametre alır. Fonksiyon içinde, "func_num_args()" fonksiyonu ile kaç adetarametre geçirildiği kontrol edilir. Daha sonra, "func_get_arg()" fonksiyonu ile her parametrenin değeri alınarak toplama işlemi yapılır. Fonksiyon çağrısı yine "echo" ifadesi ile yapılır ve sonuç ekrana yazdırılır. Sonuç olarak, ekranda "The sum of 1, 2, 3, 4 and 5 is: 15" mesajı görüntülenecektir.

## Fonksiyonlarda Referans Değişkenleri

Fonksiyonlar, değerleri geri döndürmenin yanı sıra, referans değişkenlerini de döndürebilirler. Referans değişkenleri, fonksiyonun işlediği değişkenin kendisini kullanarak değişiklik yapar. Örneğin:
```php
<?php
function addOne(&$num) {
    $num++;
}

$x = 5;
addOne($x);
echo "X'in değeri: $x";
?>
```
Bu örnekte, addOne() fonksiyonu, $num değişkenini alır ve değerini bir artırır. Fonksiyon, "&" işareti ile referans parametresi alır. Fonksiyon çağrısı, $x değişkeni ile yapılır ve addOne() fonksiyonu, $x değişkeninin değerini bir artırır. Sonuç olarak, ekranda "The value of x is: 6" mesajı görüntülenecektir.

# Gün 6: PHP Diziler

Diziler, belirli bir türdeki verileri tutmak için kullanılan veri yapılarıdır. Diziler, tek bir değişken içinde çok sayıda değer saklamak için kullanılabilir. PHP'de, diziler iki türde olabilir: indisli diziler ve ilişkisel diziler.

## İndisli Diziler

İndisli diziler, her öğenin bir indis numarası ile belirtildiği dizilerdir. İndis numaraları sıfırdan başlar ve her öğenin farklı bir indis numarası vardır. İndisli diziler, "array()" fonksiyonu veya kısa sözdizimi ile oluşturulabilir. Örneğin:
```php
<?php
$numbers = array(1, 2, 3, 4, 5);
echo "The third element of the array is: " . $numbers[2];
?>
```
Bu örnekte, $numbers dizisi "array()" fonksiyonu ile oluşturulmuştur. Dizi içindeki öğelere erişmek için, öğenin indis numarasını kullanarak diziye erişilir. Sonuç olarak, ekranda "The third element of the array is: 3" mesajı görüntülenecektir.

## İlişkisel Diziler

İlişkisel diziler, öğelerin anahtar-değer çiftleri olarak saklandığı dizilerdir. İlişkisel diziler, "array()" fonksiyonu veya kısa sözdizimi ile oluşturulabilir. Anahtarlar, diziye eklenen öğelerin isimleri olarak kullanılır ve değerler, anahtarlarla eşleştirilir. Örneğin:
```php
<?php
$person = array(
    "name" => "John",
    "age" => 30,
    "city" => "New York"
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

# Gün 7: PHP Fonksiyonları

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
