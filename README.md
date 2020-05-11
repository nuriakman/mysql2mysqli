
# MySQL to MySQLi

## PHP MySQL'den MySQLi

Bu kod yardımı ile, mysql komutlarının, mysqli komutları ile çağrılması işlemi yapılır.

PHP 7 ile birlikte mysql_* kütüphanesinin kullanımı devre dışı bırakılmıştır.

Eğer, PHP 7 yüklü bir sunucuda mysql_* kütüphanesi komutları ile yazılmış bir projeniz varsa, bu proje yardımı ile kodunuzu sadece aşağıdaki satırları veritabanı bağlantısını tanımladığınız yerin başına yazarak kullanabileceksiniz.

### Kullanım Örneği

mysql_connect komutunun bulunduğu dosyanın başına şu kodu ekleyin:

```
if( !extension_loaded('mysql') ){
    require_once("mysql2i.class.php");
}
```

Kaynak Kod: https://www.phpclasses.org/package/9199-PHP-Replace-mysql-functions-using-the-mysqli-extension.html



## PHP MySQL to MySQLi

Replace mysql functions using the mysqli extension

This class can replace the mysql functions using the mysqli extension.

It provides equivalent functions that perform the same operations as the mysql extension when this is not available.

An auxiliary script is provided to provide global functions with the same names and parameters as mysql extension functions except that they call the class to use the mysqli extension.


### Usage Sample

Add this code at the top of file before use mysql_connect command:

```
if( !extension_loaded('mysql') ){
    require_once("mysql2i.class.php");
}
```

Original Source Code: https://www.phpclasses.org/package/9199-PHP-Replace-mysql-functions-using-the-mysqli-extension.html
