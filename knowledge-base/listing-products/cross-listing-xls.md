# Cross Listing dari Master Product (xls)

Gunakan Cross Listing dari excel ini bertujuan untuk menambahkan banyak produk dari banyak category ke satu channel. Jika ingin manabahkan 1 produk ke banyak channel, guna kan [Cross Listing](add-listing.md) dari interface&#x20;

{% hint style="info" %}
Ada 2 cara untuk membuat Master product, Jika master product belum terupload di Forstok.

1. [Import Product dari salah satu channel (Marketplace atau website)](import-product-from-channels.md)
2. [Tambahkan master product](../master-products/add-master-product.md)
{% endhint %}



Berikut merupakan langkah-langkah yang bisa dilakukan untuk melakukan _cross listing_ :&#x20;

1\. Pastikan kondisi integrasi sudah **sync item on**. Lihat [migrate-to-forstok.md](../before-integrations/migrate-to-forstok.md "mention")

2\. Lakukan category mapping terlebih dahulu untuk mempermudah proses Cross Listing melalui Settings - Category. Lihat [category.md](../settings/category.md "mention")

3\. Pada halaman item, klik tombol +Item lalu pilih **cross listing**.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48084855913/original/-lj3XDsVRXGuTalXgcTGyPjRzbTZBM-y7A.png?1612291312)

4\. Pastikan category yang akan di listing pada channel tujuan sudah muncul setelah dilakukan Category Mapping sebelumnya.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48049647268/original/eq8O\_75YrevrzJ6HfwcTl8imdKWuu2Shkg.png?1594965940)

5\. Klik **submit** untuk mendapatkan excel cross listing.&#x20;

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062548537/original/YtrSsmawIeMJR3Bqc0PI4HSuDozOsCcPrQ.png?1601757059)

6\. Untuk mendownload file cross listing klik **activity** lalu download file cross listing pada **summary file dan dowonload brand list.**

![](<../../.gitbook/assets/image (169).png>)

7\. Setelah selesai di download, lengkapi data yang ada di csv. Untuk kolom Brand bisa di download dari Brand List. Untuk brand list harap copy paste kode dan nama brandnya.

![](<../../.gitbook/assets/image (92).png>)

{% hint style="info" %}
Berikut adalah contoh Template Cross Listing dalam bentuk xls:
{% endhint %}

{% embed url="https://docs.google.com/spreadsheets/d/1UsWM0ERtmTcv2bjXCu0Y-hq8gv6xe9EN/edit?ouid=108585903555648506286&rtpof=true&sd=true&usp=sharing" %}
Tab di bagian bawah dibagi berdasarkan kategori item di marketplace\
[https://docs.google.com/spreadsheets/d/1UsWM0ERtmTcv2bjXCu0Y-hq8gv6xe9EN/edit?usp=sharing\&ouid=108585903555648506286\&rtpof=true\&sd=true](https://docs.google.com/spreadsheets/d/1UsWM0ERtmTcv2bjXCu0Y-hq8gv6xe9EN/edit?usp=sharing\&ouid=108585903555648506286\&rtpof=true\&sd=true)
{% endembed %}

8\. Setelah dilengkapi, simpan file dengan cara Save, bukan Save as, nama file juga tidak dapat diubah karena bisa mengakibatkan gagal upload;

9\. Masuk ke halaman cross listing, pilih sales channel dan category nya, lalu pilih file csv/xls tersebut dan upload.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062548606/original/zHuIDDrUi8KofVxv9DoTN200SKwTdMqFug.png?1601757262)

10\. Setelah di upload dan berhasil maka untuk melihat original file dan summary file nya bisa dilihat di log activity.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062548715/original/iKBxQ4uj05i-bZEJA5REOMw\_t\_l3FpjSug.png?1601757322)

{% hint style="danger" %}
Untuk listing ke JD.ID dan Woocommerce belum bisa listing dari Forstok karena ada limitation listing API dari marketplace  harus di lakukan langsung dari seller center lalu import ke Forstok
{% endhint %}

{% hint style="info" %}
* Sebelum menggunakan cross listing, pastikan bahwa sudah ada **item master** nya terlebih dahulu di forstok dan **sudah terisi lengkap data master itemnya**.&#x20;
* Untuk seller center **zalora** di sarankan untuk menggunakan add single item atau edit item lalu menambahkan channel zalora, karna jika menggunakan cross listing maka image yang diupload akan mengikuti channel sebelumnya atau image yang ada di item master dan kemungkinan akan di reject oleh pihak zalora.&#x20;
* Untuk **cross listing ke POS** jika sku nya berupa angka secara keseluruhan maka skunya akan ada **tambahan @di sku depan** nya agar sku tersebut bisa terbaca oleh system. Misal sku 11245476 di sku master dan code nya berupa **@11245476,** sku tersebut tidak boleh di ganti pada saat asebelum di upload.&#x20;
* Untuk pengisian kolom harus **sesuai dengan format yang di template download**, tidak boleh mengubah kondisi yang ada pada template, misal : pada template kondisi nya adalah list dropdown lalu copy paste text hingga mengubah list drop down tersebut menjadi text biasa.
* Untuk pengisian **brand** bisa dengan cara download file brand setelah download template cross listing lalu cari nama brand nya, copy id dan nama brand nya lalu paste di kolom brand yang ada di halaman cross listing.
{% endhint %}

