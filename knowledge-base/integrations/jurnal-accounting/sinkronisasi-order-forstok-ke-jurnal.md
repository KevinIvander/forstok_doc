# Sinkronisasi Order (Forstok → Jurnal)

### **Order Mapping Forstok ke Jurnal**

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

### Faktur akan dibuat di Jurnal saat pesanan dikirim.&#x20;

Faktur di Jurnal akan dibuat dan ditandai sebagai dibayar secara otomatis. Pembayaran yang diterima akan dipetakan berdasarkan COA.



![](https://lh3.googleusercontent.com/iT39ykRJfb7eszqGdjIy01zf\_cWdcYUev7TnJXtVRaIvXxkq0lx0I1ujLFi4luMiAy1bY3he5zya8CsAZrDf5M36n0-G3\_vBlu1-1FCPskUe1oTNGvSXvfdiCRKKgu\_q2W\_Ms6GMEZo)

### Contoh Faktur Penjualan dari orderan Marketplace:

![](https://lh5.googleusercontent.com/xPzN1XXoK649YLGTyungNBa3LDkMMosU73XJ8QhNOjfhWnuduEy2YT3cY9LHxkKT1HTbVljqUT93-lBAtjnxYiufdasRV3yNTBXpj6IczEbhXLqnAzvTLqhNVv7C0FtXjE8mayAaO3k)
