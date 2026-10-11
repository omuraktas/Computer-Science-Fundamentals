
# Dosya Sistemleri ve Depolama Mantığı

## NTFS (New Technology File System)
Windows işletim sistemlerinde yaygın olarak kullanılan dosya sistemidir.
Dosyaların düzenlenmesini, erişim izinlerinin yönetilmesini ve büyük dosyaların saklandığı alandır.
Journaling özelliği sayesinde beklenmedik kapanmalardan sonra dosya sistemi tutarlılığının korunmasını sağlar.


## ext4 (Fourth Extended File System)
Linux işletim sistemlerinde yaygın olarak kullanılan dosya sistemidir.
Dosyaların düzenli şekilde saklanmasını sağlar ve journaling desteği sunar.
Performansı ve kararlılığı nedeniyle Linux bilgisayarlarda ve sunucularda tercih edilir.


## APFS (Apple File System)
Apple tarafından geliştirilen ve macOS, iOS gibi işletim sistemlerinde kullanılan dosya sistemidir.
Özellikle SSD'ler için optimize edilmiştir.
Şifreleme, snapshot ve dosya kopyalama işlemlerinde alan tasarrufu gibi özellikler sunar.


## Block Structure (Blok Yapısı)
Diskteki verilerin belirli büyüklükteki birimler halinde yönetilmesini sağlar.
Dosyalar, dosya sisteminin kullandığı bloklar veya kümeler (clusters) aracılığıyla saklanır.
Blok yapısı, verilerin düzenlenmesini ve gerektiğinde bulunmasını kolaylaştırır.


## HDD (Hard Disk Drive)
Verileri dönen manyetik diskler üzerinde saklayan mekanik depolama birimidir.
Verileri okumak ve yazmak için hareketli bir kafa kullanır.
Mekanik hareketler nedeniyle SSD'lere göre genellikle daha yavaştır ancak GB başına maliyeti daha düşüktür.


## SSD (Solid State Drive)
Verileri NAND flash bellek hücrelerinde saklayan elektronik depolama birimidir.
Hareketli mekanik parçaları bulunmadığından verilere hızlı erişim sağlar.
HDD'ye göre genellikle daha hızlı, sessiz ve darbelere karşı daha dayanıklıdır.
