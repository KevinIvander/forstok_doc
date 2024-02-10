# Sync Payment Received (Forstok → Accurate)

Setelah sales invoice terbuat di Forstok dan di Accurate, lakukan **create payment receive** di Forstok untuk auto create sales receipt/penerimaan penjualan di Accurate dan kemudian mengupdate status sales invoice/faktur penjualan di Accurate menjadi **paid:**

{% hint style="info" %}
**Payment Received memiliki 2 jenis tanggal Payment Date**:

1. Payment Date berdasarkan "Channel Payment Date" atau uang yang masuk ke dompet penjual. Ini adalah pengaturan default.
2. Payment Date berdasarkan tanggal saat pengguna melakukan "Payment received" di forstok invoice.

Opsi Auto Paid dapat diaktifkan jika menggunakan pengaturan "Channel Payment Date". Dengan demikian, pengguna tidak perlu secara manual melakukan "Payment received" di faktur forstok. Pembayaran otomatis akan dipicu H+1 setelah pesanan selesai / uang masuk ke dompet penjual.



Pengaturan ini dapat ditemukan di [Invoice Settings](https://app.forstok.com/dashboard/settings/invoices)

Berikut adalah panduan pembuatan Payment Received: [View Here](../../payment-receive/)
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (6) (1) (2).png" alt=""><figcaption><p>Kami sarankan create payment receive dilakukan di status order 'Completed', hal ini agar nominal yang diupdate sudah fixed.</p></figcaption></figure>

1. Setelah melakukan create payment receive, sales invoice di accurate akan otomatis terupdate menjadi lunas, dan sales receipt akan auto create di accurate:

<figure><img src="../../../.gitbook/assets/image (1) (6) (1).png" alt=""><figcaption><p>Tampilan faktur penjualan/sales invoice setelah create payment receive dari Forstok</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (3) (1) (2).png" alt=""><figcaption><p>Auto-create Sales Receipt/Penerimaan Penjualan setelah create payment receive dari Forstok</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1) (6).png" alt=""><figcaption><p>Detail amount yang tertera di Accurate setelah dilakukan create payment receive di Forstok<br>(klik Invoice di Accurate --> Informasi Diskon --> arahkan kursor dan scroll tabel Akun Diskon untuk melihat seluruh rincian amount yang dikirimkan dari Forstok ke Accurate untuk invoice tersebut)</p></figcaption></figure>

3. Setelah melakukan create payment receive, data amount yang tertera di Forstok, akan dikirimkan ke Accurate dan bisa dilihat rinciannya seperti gambar di atas.&#x20;



{% hint style="info" %}
Setelah dilakukan payment received dari Forstok, tanggal yang diinput pada 'Payment Date' di Accurate adalah _channel payment date_ atau tanggal pembayaran dari marketplace ke seller (tanggal pesanan selesai)&#x20;


{% endhint %}

<figure><img src="../../../.gitbook/assets/image (458).png" alt=""><figcaption></figcaption></figure>
