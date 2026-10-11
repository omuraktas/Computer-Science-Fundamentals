# Yazılım Mimarisi Temelleri

## Monolith vs Microservice
- Monolith, uygulamanın tüm bileşenlerinin tek bir uygulama içinde çalıştığı mimaridir. Geliştirmesi ve dağıtımı başlangıçta daha kolaydır.

- Microservice: Uygulama, sipariş, ödeme ve ürün yönetimi gibi bağımsız servislere ayrılır. Her servis ayrı geliştirilebilir ve dağıtılabilir. Bir serviste oluşan hata, doğru tasarlanmış bir sistemde diğer servislerin ve tüm uygulamanın çökmesini önlemeye yardımcı olur.

Örnek: Trendyol'da ödeme servisinde sorun yaşanması, ürün listeleme servisinin de mutlaka çökmesi anlamına gelmez.

## MVC – MVVM
Yazılım bileşenlerini düzenlemek için kullanılan mimari desenlerdir. MVC, Model–View–Controller; MVVM ise Model–View–ViewModel yapısını kullanır.


## State Management (Durum Yönetimi)
Uygulamanın o anki verilerini ve durumunu yönetme işlemidir. 
Örneğin, kullanıcının giriş yapıp yapmadığı, sepetteki ürünler veya ekranda seçilen tema uygulamanın durumudur.


## Layered Architecture (Katmanlı Mimari)
Uygulamayı görevlerine göre farklı katmanlara ayırır.
- Controller: Gelen istekleri karşılar ve yanıtları yönetir.
- Service: İş kurallarını ve uygulama mantığını yürütür.
- Repository: Veritabanından veri okuma ve yazma işlemlerini yönetir.
Bu yapı, kodun daha düzenli, test edilebilir ve bakımı kolay olmasını sağlar.
