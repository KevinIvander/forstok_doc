# WMS overview

Forstok WMS adalah suatu applikasi gudang management yang bisa membantu tim gudang melakukan validasi product mengunakan barcode scanner pada waktu picking dan packing barang.&#x20;

![](<../../.gitbook/assets/Screen Shot 2022-03-22 at 4.42.12 PM (1).png>)

{% hint style="success" %}
**Benefit Forstok WMS flow**

1. Paperless. Tidak perlu print picklist and packlist kertas. Hanya mengunakan Forstok Shipping label sebagai acuan picking dan packing.
2. Bisa mengunakan 2 step produk validasi dari picker dan packer untuk mengurangi kesalahan.&#x20;
3. Built-in barcode scanner, dan tetap bisa mengunakan external bluetooth barcode scanner untuk memvalidasi produk.
4. Native app iOS dan Android. [Download app](download-wms-app.md)
{% endhint %}

{% hint style="success" %}
**Forstok picking and packing flow**

1. &#x20;Update orders status menjadi "Not Shipped or Ready to Ship".&#x20;
2. Print Forstok shipping label AWB
3. Picker buka WMS App, pilih picklist, create picklist, scan order ID di Forstok shipping label dan mulai picking dengan mengunakan barcode untuk validasi produk. [Lihat](picklist.md)
4. Masukan produk dan shipping label kedalam box dan pindahkan kebagian packer.&#x20;
5. Packer buka WMS app, pilih package, scan order ID di Forstok shipping label dan  validasi produk yang ada didalam box. [lihat](package.md)
6. Jika semua sudah cocok, tutup box and tempel shipping label.
{% endhint %}

### Features:

&#x20;**Manage outbound activities**

* Create Picklist
* Create Package

**Barcode Scanner**

* Build-in barcode scanner
* Connect to external bluetooth scanner

**Manage inbound activities (Coming Soon)**

* Create inbound
* Return management

**Stocktake (Coming Soon)**

* Stock take
* Register new barcode

