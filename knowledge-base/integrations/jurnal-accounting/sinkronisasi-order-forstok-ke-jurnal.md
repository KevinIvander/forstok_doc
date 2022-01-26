# Sinkronisasi Order (Forstok ke Jurnal)

### **Order Mapping Forstok ke Jurnal**

| **Forstok**     | **Jurnal**                                    |
| --------------- | --------------------------------------------- |
| Pending Payment | -                                             |
| Open            | -                                             |
| Printed         | -                                             |
| Ready to Ship   | Create Invoice di Jurnal                      |
| Shipped         | -                                             |
| Delivered       | Update invoice di jurnal jadi paid            |
| Cancelled       | Invoice akan cancel secara otomatis di Jurnal |
| Return          | Invoice akan cancel secara otomatis di Jurnal |

### Faktur akan dibuat di Jurnal saat pesanan dikirim.&#x20;

Faktur di Jurnal akan dibuat dan ditandai sebagai dibayar secara otomatis. Pembayaran yang diterima akan dipetakan berdasarkan COA.



![](https://lh3.googleusercontent.com/iT39ykRJfb7eszqGdjIy01zf\_cWdcYUev7TnJXtVRaIvXxkq0lx0I1ujLFi4luMiAy1bY3he5zya8CsAZrDf5M36n0-G3\_vBlu1-1FCPskUe1oTNGvSXvfdiCRKKgu\_q2W\_Ms6GMEZo)

Contoh Faktur Penjualan dari orderan Marketplace:

![](https://lh5.googleusercontent.com/xPzN1XXoK649YLGTyungNBa3LDkMMosU73XJ8QhNOjfhWnuduEy2YT3cY9LHxkKT1HTbVljqUT93-lBAtjnxYiufdasRV3yNTBXpj6IczEbhXLqnAzvTLqhNVv7C0FtXjE8mayAaO3k)
