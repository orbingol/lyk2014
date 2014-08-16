## jQuery Örnekleri

Bu dizinde 3 örnek bulunmaktadır.

### Konsol örneği

Bu örnek için kullandığımız jQuery seçicileri ve fonksiyonları:

* `$("div#icerik div.sol-menu p").html();`
* `$("div#icerik div.sol-menu div[name='icmenu']").html();`

Döküman oldukça basit olduğundan bu seçiciler bir miktar gereksiz gibi görünse bile, karmaşık bir dökümanda bu şekilde kullanımlar olabilmektedir.

Alternatif kullanımlar:

```
var jq_nesnesi = $("div#icerik div.sol-menu p");
jq_nesnesi.html();
```

### Örnek 1

Bu örnek *beklendiği gibi çalışan* ve *beklendiği gibi çalışmayan* şeklinde iki aşamadan oluşmaktadır.

### Örnek 2

Bu örnek, ilk örneğin bir miktar farklılaştırılmış bir sürümüdür.
