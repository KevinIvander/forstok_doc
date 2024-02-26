# Upload Stock Adjustment Final Qty (xls)

{% hint style="info" %}
Sebelum melakukan penyesuaian stok, pastikan sudah sync  item on all marketplace agar bisa terupdate ke all marketplace
{% endhint %}

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Kolom qty per skunya yang tidak diisi akan dikecualikan dari proses update stock</p></figcaption></figure>

Untuk menginput total stock yang ada saat ini (qty on hand)

1\. Klik menu Inventory - Import/Export - Upload Stock Adjustment\
\


<figure><img src="../../.gitbook/assets/Screenshot 2023-11-15 140951.jpg" alt=""><figcaption></figcaption></figure>

3\.  Pilih warehouse yang akan di update stocknya, kemudian klik Download 1 kali saja.

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-15 141223.jpg" alt=""><figcaption></figcaption></figure>

4\. Setelah diklik, akan muncul notifikasi bahwa proses download in progress

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-15 142855.jpg" alt=""><figcaption></figcaption></figure>

5\. File bisa didownload pada menu Activity, klik Download File

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-15 142929.jpg" alt=""><figcaption></figcaption></figure>

6. Buka File dan isi file dengan contoh sebagai berikut:

Contoh 1\
\
SKU: 1AAASD0014\
Current Qty On Hand: 70\
\
Ada penambahan stok/inbound barang 5 item. Sehingga jumlah fisik barang menjadi 75. Maka yang diinput pada kolom New Qty On Hand adalah 75.&#x20;

![](<../../.gitbook/assets/final qty update xls.jpg>)

Contoh 2

SKU: 1AAASD0017\
Current Qty On Hand: 71\


Terdapat barang rusak sejumlah 2 item, maka input new Qty on Hand menjadi 69

![](<../../.gitbook/assets/update qty on hand final qty.jpg>)

{% hint style="warning" %}
* Patokan stock di Forstok yang akan di export ke channel yaitu status **Available**
* Saat melakukan update stock kolom tidak boleh di hapus. Baris boleh di hapus jika tujuannya hanya untuk update stock beberapa sku yang di pilih saja
* Jangan pernah merubah format kolom atau merubah file xls
* Jika ingin menjumlahkan dengan rumus vlookup harap dilakukan diluar format original file update stock Forstok. Atau pada update stock di New Qty On Hand tidak ada rumus. Karena akan failed saat export data ke channel
{% endhint %}

6\. Setelah penginputan stock pada New Qty On Hand, save file xls, pada menu Inventory, klik Import/Export, klik browse, pilih file xls yang sudah diisi - Import

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-15 143434.jpg" alt=""><figcaption></figcaption></figure>

7\.  Untuk melihat hasil update qty tsb klik icon Notifications - More Activity. Download pada **Summary File**

![](<../../.gitbook/assets/summary stock adjustment final qty xls.jpg>)



