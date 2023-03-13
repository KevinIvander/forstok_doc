# Accurate Online

{% hint style="info" %}
**LIMITASI INTEGRASI FORSTOK - ACCURATE:**&#x20;

1. Sync stok tidak bisa realtime, hal ini dikarenakan proses create order dari mp -->forstok--> accurate membutuhkan waktu, sehingga akan ada kemungkinan posisi stok yang tidak sync antara forstok dan accurate;&#x20;
2. Kami sarankan stok antara offline dan online dipisah, stok offline diatur melalui accurate, stok online diatur melalui forstok;
3. Accurate memiliki rate limit/batasan untuk setiap proses berjalan dari forstok, hal ini bisa mengakibatkan stok tidak sync antara forstok dan accurate.
{% endhint %}

Accurate Online merupakan sistem akuntansi yang memudahkan Anda dalam mengelola laporan penjualan Anda. Dengan menghubungkan Accurate Online ke Forstok semua transaksi orderan online Anda bisa masuk ke applikasi accurate online Anda.&#x20;

* Integration Steps. [View here](integrasi-accurate-online.md)
* Accurate Settings - Mapping COA , gudang, pajak. [View here](accurate-settings-mapping-coa-gudang-pajak-dan-detail-amount.md)
* Create product: Forstok → Accurate. [View here](create-product-forstok-ke-accurate.md)
* Stock sync: Accurate → Forstok. [View here](sinkronisasi-stok-accurate-ke-forstok.md)
* Invoice sync: Forstok → Accurate. [View here](sync-invoice-forstok-accurate.md)
* Accurate FAQ. [View here](faq-accurate.md)
* Perubahan flow pelunasan Forstok --> Accurate. [View here](perubahan-flow-pelunasan-forstok-accurate.md)

<figure><img src="../../../.gitbook/assets/image (7) (2).png" alt=""><figcaption></figcaption></figure>

### **Invoice Mapping Forstok** → **Accurate Online**

| **Forstok**            | **Accurate**                                   |
| ---------------------- | ---------------------------------------------- |
| Unpaid                 | Unpaid                                         |
| Create Payment Receive | -                                              |
| Paid                   | <p>Paid<br>(Rincian biaya diupdate ke CoA)</p> |

