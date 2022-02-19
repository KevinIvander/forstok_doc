# Sinkronisasi Order (Forstok → Accurate)

### **Order Mapping Forstok** → **Accurate Online**

| **Forstok**     | **Accurate**                                                                                                                                                                                            |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pending Payment | -                                                                                                                                                                                                       |
| Open            | Create Sales order di Accurate dan reserved stok.                                                                                                                                                       |
| Ready to Ship   | <p>Create Sales Invoice di Accurate status unpaid. </p><ul><li>Accurate SO akan otomatis updated jadi completed.</li><li>Reserved stock akan dilepas, On hand qty akan berkurang. </li></ul>            |
| Shipped         | -                                                                                                                                                                                                       |
| Delivered       | Forstok akan update invoice di Accurate jadi paid.                                                                                                                                                      |
| Cancelled       | SO and Invoice  akan di delete secara otomatis di Accurate                                                                                                                                              |
| Returned        | <p>Returned artinya paket sudah keluar dari gudang atau sdh di pickup oleh kurir. </p><p></p><p>Marketplace belum memprovide API return. Jadi harus create sales return di Accurate secara manual. </p> |

Accurate Invoice

