# FAQ - Accurate Online

### Bagaimana proses / flow create sales return?

Saat ini untuk create sales return di order V2 belum di handle di Forstok dan juga di accurate. Sehingga untuk flownya AP - create sales return di Accurate Online, kemudian adjust stok di Accurate Online - Forstok.

### Berapa rate limit update stok per sku dari jurnal ke forstok dan accurate ke forstok?

* Saat ini belum ada rate limit nya, namun dari accurate setiap melakukan adjust stock akan mengirimkan webhook.
* Sedangkan untuk AOL setiap saat update stok, harus klik tombol pada awal integrasi AOL ke Forstok.
* Sedangkan untuk Jurnal setiap saat update stok , harus klik tombol sync dikarenakan ada delay sync. Disarankan sebaiknya di update di kedua platform (karena saat ini Jurnal belum menyediakan webhook).

### Jika pembuatan bundle di AOL / Virtual Bundling dengan skenario, Paket Hemat terdiri dari SKU A, B, C. Kondisinya Paket Hemat tersebut tidak memiliki stok di AOL, bagaimana implementasi di Forstok?

Jika ada skenario seperti ini, dimana terdapat order bundle di forstok dan mengirim ke Accurate, untuk proses / flownya adalah Forstok akan mengirimkan ke Accurate SKU Bundle dan SKU Detail Bundle nya.

{% hint style="info" %}
**Note :** Price anakan bundle tidak dikirim, namun price bundle dikirim.
{% endhint %}

<figure><img src="../../.gitbook/assets/acc bundle.png" alt=""><figcaption><p><mark style="color:blue;">*** Di Accurate sudah memiliki type product “Grup”, dan saat ini sedang di check skenario nya</mark></p></figcaption></figure>

### Apakah satu akun Forstok bisa ke multi akun Accurate?

Tidak bisa.

### Apakah multi akun Forstok bisa ke satu database Accurate?

Tidak bisa, melainkan harus 1 akun forstok - 1 akun database AOL.

{% hint style="info" %}
**Note : 1 akun Forstok - 1 akun AOL (Limitasi credential dari AOL waktu update token**
{% endhint %}

### Bagaimanakah flow cut off pada saat integrasi? Apakah mengikuti rules order dari MP ke Forstok?

Order hanya akan sync ke Forstok setelah di integrasi, tidak berlaku backdate (sebelum integrasi).

### Bagaimana rate limit Accurate Online yang terbaru?

Per tanggal 27 Maret 2023 saat ini rate limit untuk AOL sudah naik menjadi 8 request per detik dan 8 request paralel.



### Bagaimana proses retur di Accurate terkait integrasi dengan Forstok?

Proses retur saat ini tergantung dari settings auto create invoice di Forstok, cek panduan berikut: [Invoice Settings](../../knowledge-base/settings/invoice-settings.md). Hal ini dikarenakan proses create invoice di accurate berjalan ketika invoice created di Forstok. Apabila retur terjadi setelah barang keluar dari gudang (status ready to ship), proses retur tergantung dari apakah invoice sudah terbuat di forstok atau belum, apabila belum maka proses pengembalian stock/penambahan stok hanya perlu diilakukan di Forstok. Namun apabila sudah terbuat di Forstok, maka perlu dilakukan update status terhadap invoice menjadi status voided, ini agar invoice yang sudah terbuat di Accurate bisa terhapus ([Mark as Void](../../knowledge-base/sales-invoices/export-invoice-excel.md)).

Apabila terjadi partial retur, misal barang yang dikirimkan ada 2, namun yang diterima 1 dan 1 lagi dikembalikan, maka perlu dilakukan input manual di Accurate untuk disesuaikan kembali.

### Bagaimana apabila invoice tidak terbuat di Accurate?

Terdapat beberapa skenario yang dapat menyebabkan gagalnya proses terbuatnya invoice di accurate, apabila accurate sudah terintegrasi dan CoA serta WH sudah termapping, pada menu Invoice di Forstok, terdapat notifikasi untuk melihat _Summary_ dari invoice yang gagal terbuat di accurate:

<figure><img src="../../.gitbook/assets/Screenshot 2023-12-13 085931.jpg" alt=""><figcaption><p>Klik 'View Orders'</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2023-12-13 090029.jpg" alt=""><figcaption><p>Pada kolom 'Failed Reason' anda bisa melihat gagalnya proses pembuatan invoice di accurate karena apa, pada tombol Retry anda bisa melakukan request proses retry create invoice di accurate</p></figcaption></figure>
