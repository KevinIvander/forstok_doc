---
description: Untuk menginput total stock yang ada saat ini (qty on hand)
---

# Upload Stock Adjustment Final Qty (xls)

### Video

![](<../../.gitbook/assets/stock adjustment.gif>)

1\. Pada menu Items, pilih tanda panah berikut dan Upload Stock Adjustment

![](<../../.gitbook/assets/image (316).png>)

2\. **** Pilih warehouse yang akan di update stocknya, kemudian Download Template.

![](<../../.gitbook/assets/upload stock adjustment\_choose warehouse.jpg>)

3\. File bisa di download pada Notifications, klik '**Download File**'

![](<../../.gitbook/assets/Download file stock adjustment (1).jpg>)

4\. Input stock yang akan di update pada kolom New Qty On Hand&#x20;

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

5\. Setelah penginputan stock pada New Qty On Hand, upload dan import file.

![](<../../.gitbook/assets/upload file stock adjustment final qty.jpg>)

6\.  Untuk melihat hasil update qty tsb klik icon Notifications - More Activity. Download pada **Summary File**

![](<../../.gitbook/assets/summary stock adjustment final qty xls.jpg>)



