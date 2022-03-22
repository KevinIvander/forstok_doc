# Order Status

{% hint style="warning" %}
## Forstok Order Status

**Pending Payment**:  Sales order yang belum dibayar oleh pembeli. Seller tidak bisa memproses orderanya. Setelah pembeli membayar, status order akan berubah jadi **Open** secara otomatis.

**Pending Courier:** Sales order (Shopee Only) yang couriernya belum ditentukan oleh Marketplace. Seller belum bisa memproses orderanya. Setelah marketplace menentukan courier nya, status order akan berubah menjadi **Open** secara otomatis.

**Open:** Sales order baru yang bisa di process. Next actions: Create picklist, Create package atau update order status ke "Mark as Ready to Ship" untuk ambil AWB informasi.&#x20;

**To Ship / Not Shipped:**  Order yang sudah di Create Shipment/ terima ordernya.

**To Ship / Ready to Ship:** Order yang sudah siap dikirim atau tunggu diambil oleh courier.&#x20;

**Picked**: Sales order yang produknya telah diambil dari rak didalam gudang. Next action: Create package

**Packed**: Sales orders yang produknya telah di packaging. &#x20;

**Ready to Print:** AWB/nomor resi sudah tersimpan pada Forstok. Shipping Label dapat diprint.

**Printed:** Status akan berubah menjadi **Printed** jika shipping label sudah diprint.

**Shipped:** Status berubah menjadi **Shipped** secara otomatis jika **** paket telah diambil oleh courier. &#x20;

**Delivered:** Status berubah menjadi **Delivered** secara **** otomatis jika paket telah diterima oleh customer.

**Completed:** Status berubah menjadi **Completed** secara otomatis jika paket telah diterima oleh customer dan invoice sudah dibayar oleh Marketplace / customer.

**Cancelled:** Status berubah menjadi cancelled jika customer atau seller membatalkan order tersebut

**Returned:** Status berubah menjadi **Returned** jika seller sudah membuat Sales Return dan Confirm received item/konfirmasi barang sudah di terima digudang seller.
{% endhint %}

{% hint style="warning" %}
## Forstok Order Actions

**Mark as Paid:** Mengganti status pembayaran order dari **** Pending Payment/Belum Dibayar ke Paid/Dibayar secara manual. Action ini hanya muncul khusus Webstore (Shopify, Magento, Woocommerce atau Custom Webstore) melalui pembayaran manual (Bank Transfer)

**Create Picklist**:  Membuat picklist dokumen berisikan daftar produk untuk diambil didalam warehouse untuk memenuhi pesanan. Setelah produk diambil, status order berubah menjadi Picked.

**Create Package:** Membuat package dokument berisikan daftar product untuk dikemas didalam satu order untuk memenuhi pesanan. Setelah produk dikemas, status order berubah menjadi Packed.&#x20;

**Mark as Ready to Ship:** Mengganti status order dari open/packed menjadi Ready to Ship/ Siap dikirim. Action ini sekaligus akan menarik data AWB/nomer resi dari courier yang teringrasi untuk bisa Print Shipping Label.

**Mark as Delivered**:  Mengganti status order dari Shipped / Sudah dikirim ke Delivered / Sudah Diterima **** oleh pembeli. Action ini hanya muncul khusus Webstore (Shopify, Magento, Woocommerce atau Custom Webstore) yang melalui courier manual/non integrated.

**Create Invoice:** Membuat invoice document berisikan informasi nominal yang harus dibayarkan untuk order tersebut. Invoice yang sudah terbuat dapat dikonfirmasi pembayarannya, edit invoice, atau void/write off invoice tersebut.

**Cancel Order:**  Mengganti status order menjadi Cancelled dan melakukan cancel order pada marketplace juga.

**Create Sales Return:**  Membuat return document berisikan informasi pengembalian barang yang dilakukan oleh buyer. Return yang sudah terbuat dapat dikonfirmasi penerimaan barangnya, edit return, atau delete return. Saat konfirmasi return tersebut, user dapat memilih untuk restock barangnya atau tidak.
{% endhint %}

## Order status Mapping

[https://docs.google.com/spreadsheets/d/1N38sX9c57xPJ5o\_2T8Qv8cr41tuHhO\_L1I2T0QHjCiI/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1N38sX9c57xPJ5o\_2T8Qv8cr41tuHhO\_L1I2T0QHjCiI/edit?usp=sharing)
