# API Mantığı (REST & JSON Temelleri)

## API (Application Programming Interface)
API, farklı yazılımların birbiriyle iletişim kurmasını sağlayan arayüz. Örneğin, bir hava durumu uygulaması API aracılığıyla sunucudan hava durumu verilerini alabilir.


## HTTP Methods (GET – POST – PUT – DELETE)
Sunucuya hangi işlemin yapılacağını belirtir.
- GET: Veri okumak veya listelemek için,
- POST: Yeni veri oluşturmak için,
- PUT: Mevcut veriyi tamamen güncellemek için,
- DELETE: Veriyi silmek için kullanılır.

## JSON (JavaScript Object Notation)
Verilerin sistemler arasında taşınmasını sağlayan, okunabilir bir veri formatıdır. Veriler anahtar-değer (key-value) çiftleri şeklinde tutulur.

Örnek:

{
  "name": "Omur",
  "age": 21,
  "department": "Computer Engineering"
}


## Endpoint Tasarımı
Endpoint, API üzerinden belirli bir kaynağa erişmek için kullanılan URL yoludur. Örneğin "/students" öğrenci listesini, "/students/5" ise 5 numaralı öğrenciyi temsil edebilir.

REST yaklaşımında HTTP metotlarıyla kaynaklar üzerinde işlem yapılır. Örneğin "GET/students" öğrencileri listelerken "POST/students" yeni öğrenci oluşturur.

