# FAQ - Inventory

### Apa bedanya Qty on hand, Qty Reserved, Qty Available?

![](../../.gitbook/assets/qty-type-in-forstok.png)

**Cara perhitungan quantity** &#x20;

Qty on Hand - Reserved Qty = Available Qty

* **Qty on Hand**: Jumlah item fisik di gudang yang siap dijual. (Tidak termasuk stok yang rusak)
* **Qty Reserved:** Jumlah item ditahan yang belum diproses untuk suatu order. Status Pending payment (belum dibayar) atau open (perlu di proses).
* **Qty Available:** Jumlah sisa item yang bisa dibeli di Marketplace/ webstore. (Dihitung oleh sistem secara otomatis)&#x20;

{% hint style="danger" %}
Jika system anda hanya mempunyai satu tipe stok seperti di Shopify, Tokopedia, Shopee, POS system, Qty tersebut adalah **Qty available**.&#x20;

**Scenario:** Qty fisik digudang = **10**. Terjadi order **Qty 2 tetapi belum di proses**, secara system qty langsung berkurang **Qty 8.** Apabila anda melakukan stock opnam digudang, secara Qty fisik digudang masih = **10.** Jika anda update stock menjadi  **Qty** **10** dan order yang belum di proces tadi dibatalkan oleh customer karena tidak jadi bayar atau berubah pikiran, maka **Order Qty 2** akan di balikan ke system secara otomatis. Qty baru anda yang dapat dibeli menjadi **12** sedangkan qty fisik digudang hanya ada **10.** Ini dapat menyebabkan overselling.&#x20;

Tapi **** jika anda mengunakan inventory system seperti Forstok, anda hanya perlu **update ke Qty on Hand sesuai jumlah item fisik digudang. Jadi Qty on Hand = 10, Qty reserved 2, Qty available 8. Jika order dibatalkan, Qty on hand 10, Qt reserved 0, Qty available 10.** Scenario diatas tidak akan terjadi.&#x20;
{% endhint %}

### Template Update stock di Forstok. Final Qty or Delta Qty

#### Template update stock using Final Qty

![Template update stock using Qty Final](<../../.gitbook/assets/qty-update-final (1).png>)

#### Template update stock using Qty Changed (+/-)

![Template update stock using Qty Changed](../../.gitbook/assets/qty-update-delta.png)

{% file src="../../.gitbook/assets/sample-template-update-stock-forstok.xlsx" %}
Sample Template update stock Forstok
{% endfile %}

### **Apakah bisa set up harga coret dari Forstok?**

Untuk shopee, tokopedia dan JD.ID harga coretnya sementara hanya bisa dilakukan setupnya melalui _marketplace_ sedangkan untuk _marketplace_ lain sudah bisa melakukan harga coret langsung di dashboard Forstok melalui fitur Promotion.

![Fitur Promosi harga coret di dashboard Forstok](<../../.gitbook/assets/WhatsApp Image 2022-03-15 at 11.47.57.jpeg>)

### Apa yang harus dilakukan jika ada perubahan nama produk/sku dll?

Apabila ada perubahan nama/sku/detail variant/struktur variant(penambahan/pengurangan variant) ketika sudah terhubung dengan Forstok, perlu dilakukan remove listing kemudian import ulang kembali agar nama/sku/detail variant/struktur variant ter update di Forstok.

### **Bagaimana jika sudah upload produk namun gagal?**

Apabila gagal melakukan upload produk/listing pada umumnya dikarenakan untuk exportnya masih Off. Ketika ingin melakukan listing pastikan hal-hal berikut:

Stock tersedia (untuk yg baru pertama menggunakan Forstok mulai menggunakan Forstok harap melalakunan update stock perdana via Forstok) Export item sudah aktif

Note: Jika listing produk saat kondisi export Off, maka akan ada gagal export listing ke Marketplace. Jadi: export di On kan - lalu klik edit utk sku yg gagal listing tadi - lalu tambahkan beberapa deskripsi misal titik atau koma disalah satu field lalu Save (ini bertujuan untuk mentrigger kembali listingan yg gagal tadi dan bisa ke export).

### Apakah nama produk dan harga akan berpengaruh ke stok?

Perbedaan harga dan perbedaan nama produk tidak akan berpengaruh dengan stok karena untuk saat ini Forstok melakukan pemetaan (mapping) berdasarkan kode SKU pada setiap item/produk.

### **Apakah ada limitasi untuk edit produk di dashboard Forstok?**

Limitasi deskripsi karakter kalau untuk marketplace Shopee  5000 karakter. Sedangkan kalau untuk Tokopedia, dibagian nama produk / nama items tidak boleh lebih dari 70 karakter.

![Tampilan edit product Forstok.](<../../.gitbook/assets/tampilan edit item.png>)

Apabila muncul tampilan seperti ini untuk image tokopedianya silahkan upload ulang jika menemukan message seperti ini dengan ketentuan sebagai berikut:

1. Edit item.
2. Hapus image yang lama item tokopedia tersebut pada menu edit item.
3. Upload kembali resolusi yang disarankan 800x800 pixel, sedangkan untuk ukurannya maksimal 2MB.
4. Merubah deskripsi items.
5. Simpan _(sav_e) dan kami sarankan untuk merubah image tokopedia dengan cara upload baru saat add listing jika masternya dari Shopee.

### **Bagaimana caranya untuk mengecek SKU mana yang belum masuk ke Forstok?**

Sebenarnya saat ini Forstok belum memiliki fitur ataupun filter untuk mengetahui list SKU yang belum masuk ke Forstok. Namun dapat kita ketahui dengan menggunakan 2 opsi berikut ini:

1. _Cross Listing_

Melalui fitur _cross listing_ dapat memilih channel tujuan yang ingin kita lihat list SKU apa saja yg belum ada di channel tujuan tersebut. Selanjutnya akan tampil nominal angkanya. Kemudian untuk melihat dari angka tersebut, harus melakukan _mapping destination_ _category_ terlebih dahulu, lalu submit. Setelah itu kita bisa melihat di list excel SKU tersebut yang belum terlisting di channel tersebut.

![Tampilan cross listing.](<../../.gitbook/assets/cross listing.png>)

_2. Upload price adjustment_

![Tampilan upload price adjustment.](<../../.gitbook/assets/upload price adjustment.png>)

Pada tampilan berikut ini akan terihat bahwa ada filter by harga. Jika kolomnya ada harga, berarti di marketplace tersebut ada SKUnya. Jika terdapat kolom kosong, berarti di marketplace tsb itemnya/SKUnya tidak ada.

![Tampilan pada kolom excel.](../../.gitbook/assets/excel.png)

### **Apakah untuk pengaturan **_**price adjustment**_** dapat menggunakan waktu? Misalnya ketika ingin **_**update**_** harga di awal tahun 2023 Januari, apakah bisa diatur dibulan Desember 2022?**

Jika ingin melakukan pengaturan _price adjustment_ dengan menggunakan waktu bisa melalui menu _upload price adjustment_ via excel dan _menu adjust price_ via dashboard forstok. Berikut tampilannya.

![Tampilan menu upload price adjustment via excel](<../../.gitbook/assets/price 1.png>)

![Tampilan menu adjust price via dashboard Forstok.](<../../.gitbook/assets/price 2.png>)

### Apakah ada perbedaan jika ingin merubah harga melalui dashboard dengan melalui template excel?

Jika ingin melakukan perubahan harga dengan menggunakan _User Interface_ (dashboard) maka bisa dipilih menu _adjust price_ dan akan diarahkan untuk mengisi beberapa kolom yang bersifat _mandatory_ (wajib) diisi.

Sedangkan jika ingin melakukan perubahan harga dengan menggunakan template excel bisa langsung mengisi harga final (akhir) di kolom excel yang telah disediakan.

![Tampilan adjust price melalui user interface (dashboard) Forstok.](../../.gitbook/assets/zz.png)

### Bagaimana caranya update price tiktok?

Untuk update price tiktok untuk saat ini memang belum dapat dilakukan dan sudah kami sampaikan di broadcast tiktok berikut informasi lengkap nya : [https://docs.forstok.com/knowledge-base/integrations/tiktok](https://docs.forstok.com/knowledge-base/integrations/tiktok)

![Tiktok Integrations](../../.gitbook/assets/sH72BAn8MlH7MHsDat\_sc0YdvcIfNylUVA.png)

Untuk update price tiktok saat ini hanya bisa dilakukan di seller center langsung. Tiktok saat ini hanya mendukung: import item, update stok, import order.
