---
description: Halaman khusus untuk menampilkan Qty per SKU, Warehouse dan Status
---

# Inventory Qty V2

Pada halaman ini dapat melakukan "Create Stock Adjustment" :&#x20;

* **Final Qty** adalah untuk merubah Qty sebelumnya&#x20;
* **Inbound Qty** adalah untuk menambahkan Qty sebelumnya&#x20;
* **Outbond Qty** adalah untuk mengurangi Qty sebelumnya

Informasi Tab ( Grouping ) :&#x20;

* **All**  Menampilkan status keseluruhan Qty ( In Stock, Out Of Stock, On Promotions, Oversell )
* **In Stock**  Menampilkan status Qty "Available to sell"  lebih besar dari 0&#x20;
* **Out of Stock** Menampilkan status Qty "Available to sell" sama dengan 0
* **On Promotions** Menampilkan status Qty "Reserved Promotions"&#x20;
* **Oversell** Menampilkan status Qty "Available to sell" lebih kecil dari 0 ( Minus )&#x20;

Informasi Kolom :&#x20;

* **Item Name** adalah nama produk beserta variant&#x20;
* **Master SKU** adalah Kode SKU produk atau variant&#x20;
* **Warehouse** adalah nama warehouse ( tanpa kode warehouse )&#x20;
* **On Hand Total** adalah Qty keseluruhan dari "Reserved Orders, Reserved Promotions, Available to sell"&#x20;
* **Reserved Order** adalah Qty berdasarkan jumlah order yang masuk ke Forstok pada status "Pending Payment, Pending Courier, Open, Ready to Ship"
* **Reserved Promotions** adalah Qty berdasarkan jumlah "Stock Allocation" yang dibuat oleh user pada fitur "[Create Stock Allocation](https://www.forstok.com/dashboard/bulk\_edit?type=stock\_allocation)"&#x20;
* **Available to Sell** adalah Qty yang di export ke channel&#x20;

<div align="center">

<figure><img src="../../.gitbook/assets/inventory qty.png" alt=""><figcaption></figcaption></figure>

</div>

