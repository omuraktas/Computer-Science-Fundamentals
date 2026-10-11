# Algoritma ve Veri Yapıları Mantığı


## Data Structures (Veri Yapıları)
Verileri düzenli şekilde saklamak, yönetmek ve hızlı erişmek için kullanılır. 
Her veri yapısının kendine özgü avantajları vardır.
 Doğru veri yapısını seçmek, programın hızını ve bellek kullanımını etkiler.


## Big-O Notation (Büyük O Gösterimi)
Bir algoritmanın, veri miktarı arttıkça çalışma süresinin nasıl değiştiğini gösterir.
Algoritmaların verimliliğini karşılaştırmak için kullanılır.
    - O(1): Sabit zamanlı işlem.
    - O(n): Doğrusal çalışma, örneğin bir diziyi baştan sona taramak.


## Array (Dizi)
- Verileri sıralı şekilde saklar ve her elemana indeks (index) ile erişilmesini sağlar.
- İndeks üzerinden erişim genellikle (O(1)) zaman alır. Ancak araya eleman ekleme veya silme işlemleri diğer elemanların kaydırılmasını gerektirebilir.
## Linked List (Bağlı Liste)
 Her eleman (node), kendi verisini ve sonraki elemana ait bağlantıyı tutar.
 Eleman ekleme ve silme işlemleri, ilgili konum biliniyorsa kolay olabilir. 
 Ancak belirli bir elemana ulaşmak için listeyi sırayla dolaşmak gerekir.


## Stack (Yığın)
Son giren ilk çıkar (LIFO – Last In, First Out) mantığıyla çalışır. 
    - Eleman ekleme işlemine push
    - Eleman çıkarma işlemine pop denir.
    - Geri alma (undo), fonksiyon çağrıları 
    - Parantez kontrolü gibi işlemlerde kullanılır.


## Queue (Kuyruk)
İlk giren ilk çıkar (FIFO – First In, First Out) mantığıyla çalışır.
    - Eleman ekleme işlemine enqueue
    - Çıkarma işlemine dequeue denir. 
    - Yazıcı sıralaması, görev yönetimi ve isteklerin sırayla işlenmesinde kullanılır.


## HashMap (Hash Tablosu)
Verileri anahtar-değer (key-value) şeklinde saklar. 
Anahtar üzerinden arama, ekleme ve silme işlemleri ortalama olarak (O(1)) zamanda yapılabilir.
