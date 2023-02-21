# FAQ - Accurate Online

### Bagaimana proses / flow create sales return?

Saat ini untuk create sales return di order V2 belum di handle di Forstok dan juga di accurate. Sehingga untuk flownya AP - create sales return di Accurate Online, kemudian adjust stok di Accurate Online - Forstok.

### Berapa rate limit update stok per sku dari jurnal ke forstok dan accurate ke forstok?

* Saat ini rate limit disesuaikan dengan jurnal dan accurate, namun dari accurate setiap melakukan adjust stock akan mengirimkan webhook.
* Sedangkan kalau untuk AOL setiap melakukan update stok, harus klik tombol pada awal.
* Jurnal setiap saat update stok, harus klik button sync karena ada sync delay, Dan sebaiknya di update di kedua platform karena jurnal untuk saat ini belum menyediakan webhook.
