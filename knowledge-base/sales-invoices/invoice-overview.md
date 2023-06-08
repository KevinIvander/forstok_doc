# Invoice Overview

{% embed url="https://www.youtube.com/watch?v=g8W_pSFs2NA" %}
Invoice Video
{% endembed %}

Forstok Invoice adalah dokumen yang diterbitkan oleh penjual untuk kepentingan pencatatan pembayaran/payout dari penjualan baik di marketplace maupun di luar marketplace.



**Fungsi Forstok invoice:**&#x20;

* Dapat dicetak bersamaan dengan shipping document / AWB untuk surat bukti keluar gudang.&#x20;
* Tidak perlu dicetak untuk dikirimkan ke pembeli di Marketplace waktu packing produk. Jika pembeli marketplace membutuhkan invoice, mereka bisa mencentak langsung dari order history.&#x20;



**Status Forstok invoice:**&#x20;

* Unpaid - belum di bayarkan atau menunggu pembayaran
* Overdue - belum dibayar tapi jatuh tempo
* Paid - sudah dibayar mengunakan Payment Received
* Void - Otomatis dibatalkan jika sales order status menjadi batal
* Write off - faktur yang menjadi tidak tertagih.&#x20;

{% hint style="info" %}
Forstok Invoice **bukan** merupakan invoice yang dilampirkan oleh Penjual untuk dikirimkan ke Pembeli sebagai bukti pembayaran.&#x20;

Invoice di Forstok merupakan fitur yang digunakan untuk mendapatkan rincian nominal dari penjualan yang masuk ke dompet penjual di marketplace.&#x20;

Nominal yang dimaksud tidak bisa didapatkan dari data penjualan, karena informasi seperti _Platform Fee, Platform Fulfillment Fee, Platform Rebate_; baru tersedia setelah transaksi selesai dan pendapatan dari penjualan masuk ke saldo penjual di marketplace.
{% endhint %}



<figure><img src="../../.gitbook/assets/poo (1).png" alt=""><figcaption></figcaption></figure>

_**Cara mengaktifkan invoice**_

_Sales Invoice_ dapat dibuat secara otomatis berdasarkan Status pada Sales Orders. Untuk mengatur _Trigger_ tersebut, dapat diakses melalui menu “Setting -> Invoice”. Selain mengatur _Trigger_ untuk membuat Invoice secara Otomatis, Anda juga dapat mengatur _Due Date_, _Customer Note_, dan _Terms & Conditions_ pada halaman Setting tersebut.

<figure><img src="../../.gitbook/assets/nmn (2).png" alt=""><figcaption></figcaption></figure>

**Note:**

* Saat ini _Invoice_ hanya dapat dibuat secara Otomatis berdasarkan Status Sales Orders
* Jika Anda memilih “Create Invoice Automatically”, maka artinya _Invoice_ tersebut tidak akan dibuat (Off)
* Pengertian Status Sales Order untuk _Trigger Invoice_ adalah sebagai berikut:
  * _Open_ = SO Status “Open”
  * _Printed_ = SO Status “Not Shipped”
  * _Ready to Ship_ = SO Status “Ready to Ship”
  * _Shipped_ = SO Status “Shipped ”
  * _Delivered_ = SO Status “Delivered ”

Setelah _Invoice_ terbuat secara otomatis berdasarkan Status pada Sales Order yang telah Anda pilih sebelumnya, saat ada Order baru, akan terbuat secara otomatis _Invoice_ dengan status _Unpaid_ yang berkaitan dengan Order tersebut. Anda dapat melihat List dari _Invoice_ pada menu Orders -> Invoices.

<figure><img src="../../.gitbook/assets/vb (1).png" alt=""><figcaption></figcaption></figure>

Untuk dapat melihat detail dari _Invoice_ tersebut, Anda dapat klik pada Invoice ID dan akan langsung diarahkan pada halaman _Invoice Detail_.

<figure><img src="../../.gitbook/assets/jk (1).png" alt=""><figcaption></figcaption></figure>
