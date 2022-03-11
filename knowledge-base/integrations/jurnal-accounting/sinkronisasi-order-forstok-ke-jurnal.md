# Sinkronisasi Order (Forstok → Jurnal)

### **Order Status Mapping**&#x20;

| **Forstok**     | **Jurnal**                                                                                                                                                                                           |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pending Payment | <p>Create invoice status unpaid di Jurnal untuk potong stok. </p><p></p><p><em>Ini untuk orderan MP yang mempunyai status order pending payment seperti Shopee, Tokopedia, Lazada, etc</em></p>      |
| Open            | Create Invoice di Jurnal                                                                                                                                                                             |
| Printed         | -                                                                                                                                                                                                    |
| Ready to Ship   | -                                                                                                                                                                                                    |
| Shipped         | -                                                                                                                                                                                                    |
| Delivered       | Update invoice di jurnal jadi paid                                                                                                                                                                   |
| Cancelled       | <p>Cancelled artinya paket belum keluar dari gudang / status sebelum Shipped dan delivered. Bisa dicancel oleh seller atau buyer.</p><p></p><p>Invoice akan di delete secara otomatis di Jurnal</p>  |
| Return          | <p>Returned artinya paket sudah keluar dari gudang atau sdh di pickup oleh kurir. </p><p></p><p>Marketplace belum memprovide API return. Jadi harus create sales return di Jurnal secara manual.</p> |

### **Order fields Mapping**

| **Forstok Order**    | **Jurnal Invoice/ Faktur** |
| -------------------- | -------------------------- |
| Channel / Store      | Nama pelanggan             |
| Channel / Store      | Tag                        |
| Marketplace Order ID | No. referensi pelanggan    |

### Faktur akan dibuat di Jurnal .&#x20;

Faktur di Jurnal akan dibuat dan ditandai sebagai dibayar secara otomatis. Pembayaran yang diterima akan dipetakan berdasarkan COA.

{% hint style="warning" %}
Nama pelanggan di Jurnal akan menggunakan Channel/Store name. contoh Tokopedia - Mybabystore. Sesuai nama toko di Forstok
{% endhint %}

![](<../../../.gitbook/assets/Screen Shot 2022-03-10 at 1.19.56 PM (1).png>)

### Faktur penjualan dari orderan Marketplace:

![](<../../../.gitbook/assets/Screen Shot 2022-03-11 at 10.56.30 AM.png>)
