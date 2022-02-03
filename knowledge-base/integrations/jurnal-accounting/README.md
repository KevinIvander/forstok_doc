# Jurnal Accounting

Jurnal merupakan sistem akuntansi yang memudahkan Anda dalam mengelola laporan penjualan Anda. Dengan menghubungkan Jurnal ke Forstok semua transaksi orderan Online Anda bisa masuk ke Software Jurnal Anda. Sehingga Anda dapat mengelola laporan keuangan Offline dan Online jadi lebih mudah dan efisien.\


{% hint style="danger" %}
<mark style="color:red;">Untuk integrasi ke Jurnal pastikan akun Jurnal yang connect ke Forstok adalah owner account bukan sub account.</mark>
{% endhint %}

\
Integration Steps. [View here](integrasi-jurnal.md)

1. Jurnal Settings - Mapping COA and gudang. [View here](pesanan-penjualan-ke-faktur-chart-of-accounting-mapping.md)
2. How to import product from Jurnal to Forstok. [View here](pedoman-penggunaan-jurnal-di-forstok.md)
3. Stock adjustment and sync from Jurnal to Forstok. [View here](sinkronisasi-stok-jurnal-ke-forstok.md)
4. Order sync from Forstok to Jurnal. [View here](sinkronisasi-order-forstok-ke-jurnal.md)
5. Jurnal FAQ. [View here](faq-jurnal.md)

![Jurnal x Forstok API Flow](../../../.gitbook/assets/screen-shot-2021-08-27-at-10.50.08-am.png)

### **Order Mapping Forstok ke Jurnal**

| **Forstok**     | **Jurnal**                                                                                                                                                                                      |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pending Payment | <p>Create invoice status unpaid di Jurnal untuk potong stok. </p><p></p><p><em>Ini untuk orderan MP yang mempunyai status order pending payment seperti Shopee, Tokopedia, Lazada, etc</em></p> |
| Open            | Create invoice status unpaid di Jurnal untuk potong stok.                                                                                                                                       |
| Printed         | -                                                                                                                                                                                               |
| Ready to Ship   | -                                                                                                                                                                                               |
| Shipped         | -                                                                                                                                                                                               |
| Delivered       | Update invoice jadi Paid di jurnal                                                                                                                                                              |
| Cancelled       | Invoice akan di delete secara otomatis di Jurnal                                                                                                                                                |
| Returned        | Marketplace belum memprovide API return. Jadi harus create sales return di Accurate secara manual.                                                                                              |



Untuk integrasi ke Jurnal ada 2 kebutuhan yaitu:\
1\. Transaksi order masuk ke Jurnal\
2\. Upate stock via Jurnal dan import product master via Jurnal ke Forstok
