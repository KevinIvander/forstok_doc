# Sync Invoice (Forstok - Accurate)



{% hint style="info" %}
1. Pastikan sebelum melakukan sinkronisasi penjualan; CoA, dan detail amount/rincian penjualan pada Accurate Settings telah di-mapping agar data order yang masuk ke Forstok dapat dikirimkan dengan sesuai ke Accurate;
2. Pastikan SKU yang terdaftar di Forstok tidak ada yang empty, sku Empty dapat mengakibatkan proses auto create invoice di Accurate gagal, karena kode sku di accurate wajib terisi.
{% endhint %}

Data penjualan yang dikirimkan dari Marketplace --> Forstok, akan dikirimkan ke Accurate melalui fitur **Invoice**, panduan penggunaan fitur **Invoice**:

{% content-ref url="../../sales-invoices/invoice-overview.md" %}
[invoice-overview.md](../../sales-invoices/invoice-overview.md)
{% endcontent-ref %}

{% hint style="info" %}
Kami sarankan pengaturan invoice diatur _auto-create_ pada status order _**Ready to Ship**_** (RTS)**, hal ini dikarenakan:&#x20;

1. Sebelum RTS masih ada kemungkinan order di-cancel oleh customer;
2. _Detail amount_ yang ditampilkan di sales invoice/faktur penjualan di Accurate akan lebih mendekati detail _fixed_ yang dapat ditampilkan di status order _Completed_
3. Auto create invoice di Forstok akan auto create sales invoice di Accurate, dan akan langsung memotong stok di Accurate.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (2).png" alt=""><figcaption><p>Pengaturan auto create invoice pada status RTS di Forstok</p></figcaption></figure>

Berikut adalah alur sinkronisasi invoice dari **Marketplace --> Forstok --> Accurate**:

1. Order masuk dari Marketplace --> Forstok, dan secara otomatis create sales invoice/faktur penjualan pada status order yang telah ditentukan:
2. Auto create invoice di Forstok akan auto create sales invoice/faktur penjualan di Accurate:

<figure><img src="../../../.gitbook/assets/image (457).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Data pelanggan yang diinput di accurate adalah nama toko/integrasi di forstok.  &#x20;
{% endhint %}

Untuk step selanjutnya terdapat di Sync Payout: [View Here ](sync-payout-forstok-accurate.md)
