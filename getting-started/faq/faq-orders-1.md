# FAQ - Orders

### Kenapa bisa terjadi Oversell?

Beberapa faktor yang menyebabkan oversell:

1. Stock limitation.\
   Kita sarankan menggunakan fitur priority channel. Fitur ini bertujuan agar SKU tersebut hanya di jual di satu _channel (marketplace)_ saja.\
   [https://docs.forstok.com/knowledge-base/inventory/priority-channel-store](https://docs.forstok.com/knowledge-base/inventory/priority-channel-store)
2. Delay order yang masuk.
3. Expired API token.

### **Kapan proses order (pesanan) memotong stok yang ada di Forstok?**

Proses order (pesanan) akan memotong stok apabila statusnya sudah menjadi _pending payment_ (pembayaran yang tertunda) dan akan masuk ke dalam  _reserved quantity_. Ada beberapa _marketplace_ yang menerapkan sistem _pending payment_ diantaranya adalah, Shopee, Lazada dan Blibli. Namun, untuk _marketplace_ yang tidak menerapkan sistem _pending payment_, maka akan otomatis memotong stok tersebut dari _quantity on hand_. Berikut kami lampirkan dokumentasi _mapping_ order di Forstok. [https://docs.google.com/spreadsheets/d/1N38sX9c57xPJ5o\_2T8Qv8cr41tuHhO\_L1I2T0QHjCiI/edit#gid=0](https://docs.google.com/spreadsheets/d/1N38sX9c57xPJ5o\_2T8Qv8cr41tuHhO\_L1I2T0QHjCiI/edit#gid=0)
