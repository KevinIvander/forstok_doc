---
description: Untuk menginput total stock yang ada saat ini (qty on hand)
---

# Upload Stock Adjustment Final Qty (xls)

### Video

![](<../../.gitbook/assets/stock adjustment.gif>)

1\. Pada menu Item Forstok pilih tanda panah berikut dan Upload Stock Adjustment

![](<../../.gitbook/assets/image (316).png>)

2\. **** Pilih warehouse yang akan di update stocknya

![](https://lh6.googleusercontent.com/BcVzu\_2Iqok9b5ggqUFbegSAkqeTJVki9v3kV7\_MtIwQnuRM5ljioeoC1pllGzVKPcFrEnNwj-pPLhxC9IRaGujOhhjhJT0bhIZMf-Z0SGW-m1aRvUJwCzlIktlDvArDuXtLwqPG)

3\. Pilih dan FInal Qty (xls), file bisa di download pada Notifications

![](<../../.gitbook/assets/image (315).png>)

4\. Input stock yang akan di update pada kolom New Qty On Hand&#x20;

Contoh 1\
\
SKU: KIZIBLOSSOM0445\
Current Qty On Hand: 1\
Current Qty Reserved: 0\
\
Ingin mengupdate Final Qty jadi 10. Maka stock yang akan di input pada kolom New Qty On Hand adalah 10. karena tidak ada reserved maka stock akan terupdate jadi 10 pada Qty On Hand

![](<../../.gitbook/assets/image (365).png>)

Contoh 2

SKU: NAYLAHAZELNUT0245\
Current Qty On Hand: 10\
Current Qty Reserved: 3 \
Maka available 7\
10 - 3 = 7\
\
Berarti ada 3 stock yang di reserved atau ada pending payment pada order.&#x20;

Harap update stock dengan sudah mengurangi Reserved, jika update stock kurang dari angka reserved stock, maka available akan minus (-). Stock minus Forstok akan export 0 atau kosong.\
\
Misal \
Currenty Qty on Hand: 10\
Current Qty Reserved: 3\
Ternyata pada New Qty On Hand update: 2\
Jadi 2- 3 = -1 \


![](<../../.gitbook/assets/image (366).png>)

{% hint style="warning" %}
* Patokan stock di Forstok yang akan di export ke channel yaitu status **Available**
* Saat melakukan update stock kolom tidak boleh di hapus. Baris boleh di hapus jika tujuannya hanya untuk update stock beberapa sku yang di pilih saja
* Jangan pernah merubah format kolom atau merubah file xls
* Jika ingin menjumlahkan dengan rumus vlookup harap dilakukan diluar format original file update stock Forstok. Atau pada update stock di New Qty On Hand tidak ada rumus. Karena akan failed saat export data ke channel
{% endhint %}

5\. Setelah penginputan stock pada New Qty On Hand, upload dan import file tsb

![](<../../.gitbook/assets/image (321).png>)

6\.  Untuk melihat hasil update qty tsb klik icon Notifications - More Activity. Download pada **Summary File**

![](<../../.gitbook/assets/image (318).png>)



