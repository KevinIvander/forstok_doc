# Accurate Online

Accurate Online merupakan sistem akuntansi yang memudahkan Anda dalam mengelola laporan penjualan Anda. Dengan menghubungkan Accurate Online ke Forstok semua transaksi orderan online Anda bisa masuk ke applikasi accurate online Anda.&#x20;

### **Order Mapping Forstok** → **Accurate Online**

| **Forstok**     | **Accurate**                                                                                                 |
| --------------- | ------------------------------------------------------------------------------------------------------------ |
| Pending Payment | -                                                                                                            |
| Open            | Create Sales order di Accurate untuk reserved stok.                                                          |
| Ready to Ship   | Create Sales Invoice di Accurate status unpaid. Accurate SO akan otomatis updated jadi completed.            |
| Shipped         | -                                                                                                            |
| Delivered       | Forstok akan update invoice di Accurate jadi paid. Reserved stock akan dilepas, On hand qty akan berkurang.  |
| Cancelled       | SO and Invoice  akan di delete secara otomatis di Accurate                                                   |
| Return          | Invoice harus di delete secara manual di Accurate                                                            |



