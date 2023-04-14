---
description: Tentang Dashboard
---

# Dashboard

Berikut merupakan detail penjelasan untuk masing-masing section :&#x20;

**A. Menu Bar**

* **Forstok Dashboard :** tampilan depan Forstok yang terdapat bagian-bagian untuk melihat Pending Actions, Pending Orders, Sales Reports, dan Total Item.
* **Items Menu** : untuk mengelola item yang di edit seperti update stock, harga, sampai proses listing-listing produk.
* **Orders Menu** : untuk memproses orderan ready to ship, print shipping label, detail order dan lain-lain.
* **Customers Menu** : untuk melihat dan mendownload data customer.
* **Reports Menu** : untuk mengelola laporan yang bisa di filter berdasarkan category, kode sku, item dan lain-lain.
* **Promotion Menu**: untuk mengelola periode harga coret. Jadi harga core bisa di atur periodenya dari kapan dan sampai kapan.
* **Activity:** digunakan untuk mengetahui log aktifitas dan notifikasi.

<figure><img src="../../.gitbook/assets/Screenshot 2023-04-14 145336.jpg" alt=""><figcaption><p>Klik More Activity untuk detail activity</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2023-04-14 145612.jpg" alt=""><figcaption></figcaption></figure>

* **Integrations :** Untuk integrasikan channel yang akan connectkan ke Forstok dan untuk sync import item.
* **Settings:** Jika seller ingin mengganti password, menambahkan users and roles akun Forstok dan jika seller mengalami kendala bisa buka Help Center dan membuat ticketing pelaporan. Maka tim kami akan response dalam 1x24 jam.

**B. Forstok Dashboard**\
\
**1. Pending Action**\
setiap produk baru yang di import dari marketplace ke Forstok akan masuk terlebih dahulu ke Pending Action dimana perlu di confirm linking terlebih dahulu. Karena Forstok mapping menggunakan kode sku jadi Forstok akan infokan ke seller item mana saja yang kode skunya sudah sama atau masih ada yang belum rapih. Jika kode skunya sudah sama maka item tsb tinggal di confirm linking dan sudah bisa di edit-edit dari Forstok. Ada 4 category kode sku yang perlu perhatikan:

![](<../../.gitbook/assets/image (175).png>)

* SKU code is not matched: berkemungkinan ada 2 kondisi.\
  1\. Item tsb Kode sku yang beda di tiap marketplace atau di jual di satu marketplace saja\
  action: Langsung confirm\
  2\. Item tsb yang sama dijual di beberapa marketplace tapi salah penginputan kode sku.\
  action: Perlu di perbaiki di seller center marketplace.
* SKU Code is matched: Adalah kode SKU sudah linking dengan marketplace lain atau sudah sama.\
  action: Langsung confirm
* SKU code is empty: Adalah kode SKU masih kosong atau belum di isi dari seller center.\
  action: Kode sku di isi dari marketplace.
*   SKU code is duplicate: Adalah  kode SKU duplicate atau sama di seller center.

    Duplicate sku: Ada item yang kode skunya sama. Ada 2 kondisi: \
    1\. Duplicate produk yang sama: misal produk kamera 123 ada 2 buah di shopee tapi kode skunya sama: Action: Tinggal confirm replace di forstok \
    2\. Duplicate produk yang berbeda: misal kamera 123 dan kamera 345 di shopee kodenya sama percis. Action: Harus di perbaiki di seller center, yg ada di forstok di hapus lalu di sync/import ulang

2\.   **Order to Fulfill**\
Setelah proses integrasi Marketplace dilakukan, order yang masuk akan bisa dilihat di dashboard pada tab Order to Fulfill, kolom berdasarkan status order di Forstok.

<figure><img src="../../.gitbook/assets/Screenshot 2022-11-25 093234.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Catatan**: Marketplace yang tidak ada _**order to fulfill**_ tidak akan tampil di tab ini
{% endhint %}

3\.  **Sales Reports**\
Digunakan untuk melihat laporan dan mendownload data order sales. Yang bisa di filter berdasarkan channel dan periodenya bisa di custom.

{% hint style="info" %}
**Data Gross Sales Dashboard** = status order open, printed, ready\_to\_ship, shipped, delivered

**Data Gross Sales dari Export Sales Orders v2 dalam bentuk xls**  = status order not paid, open, printed, ready\_to\_ship, shipped, delivered, Cancelled
{% endhint %}

![](<../../.gitbook/assets/image (109).png>)

4\. **Total SKU's**\
Untuk mengetahui banyaknya item yang terdapat pada forstok sesuai dengan filter.

* All : Total sku per marketplace
* Live : Sku nya live atau ada stock
* QC Pending : Listing item dari Forstok masih proses QC/ approval dari marketplace. Berlaku untuk marketplace yang mempunyai approval produk. Seperti Blibli, Zalora, Lazada, JD.ID, Elevenia
* Inactive : Item yang di non-aktifkan biar tidak live di marketplace
* Pending Action: Ada pada dashboard Forstok paling atas, yaitu untuk mengetahui item mana saja yang belum di confirm linking
* Missing Image : Keterangan item mana saja yang gaga upload image. Actionnya harus di perbaiki imagenya dan upload ulang.
* Out of Stock : Item yang stocknya habis atau stock "0"

![](<../../.gitbook/assets/image (237).png>)
