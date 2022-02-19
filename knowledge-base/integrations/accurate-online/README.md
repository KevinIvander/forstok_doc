# Accurate Online

Accurate Online merupakan sistem akuntansi yang memudahkan Anda dalam mengelola laporan penjualan Anda. Dengan menghubungkan Accurate Online ke Forstok semua transaksi orderan online Anda bisa masuk ke applikasi accurate online Anda.&#x20;

* Integration Steps. [View here](integrasi-accurate-online.md)
* Accurate Settings - Mapping COA , gudang, pajak. [View here](accurate-settings-mapping-coa-gudang-dan-pajak.md)
* Create product: Forstok → Accurate. [View here](create-product-forstok-ke-accurate.md)
* Stock sync: Accurate → Forstok. [View here](sinkronisasi-stok-accurate-ke-forstok.md)
* Order sync: Forstok → Accurate. [View here](sinkronisasi-order-forstok-accurate.md)
* Accurate FAQ. [View here](faq-accurate.md)

### **Order Mapping Forstok** → **Accurate Online**

| **Forstok**     | **Accurate**                                                                                                                                                                                                  |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pending Payment | -                                                                                                                                                                                                             |
| Open            | Create Sales order di Accurate dan reserved stok.                                                                                                                                                             |
| Ready to Ship   | <p>Create Sales Invoice di Accurate status unpaid. </p><ul><li>Accurate SO akan otomatis updated jadi completed.</li><li>Reserved stock akan dilepas, On hand qty akan berkurang. </li></ul>                  |
| Shipped         | -                                                                                                                                                                                                             |
| Delivered       | Forstok akan update invoice di Accurate jadi paid.                                                                                                                                                            |
| Cancelled       | <p>Cancelled artinya paket belum keluar dari gudang / status sebelum Shipped dan delivered. Bisa dicancel oleh seller atau buyer.</p><p></p><p>SO and Invoice  akan di delete secara otomatis di Accurate</p> |
| Returned        | <p>Returned artinya paket sudah keluar dari gudang atau sdh di pickup oleh kurir. </p><p></p><p>Marketplace belum memprovide API return. Jadi harus create sales return di Accurate secara manual. </p>       |



