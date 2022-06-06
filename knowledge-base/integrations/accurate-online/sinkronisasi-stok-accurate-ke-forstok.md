# Sinkronisasi stok (Accurate → Forstok)

{% hint style="info" %}
**Apabila Accurate terintegrasi dengan akun Forstok, maka penyesuaian stok/stock adjustment harus dilakukan dari Accurate, karena flow penyesuaian stok berjalan 1 arah (Accurate --> Forstok --> Marketplace)**
{% endhint %}

Penyesuaian stok dapat dilakukan dengan 2 cara: 1. Satu per satu melalui fitur penyesuaian persediaan; 2. Secara bulk/masif melalui fitur Stok Opname

**Penyesuaian Persediaan**

1. Klik menu Inventory/Persediaan, kemudian pilih Item Adjustment / Penyesuaian Persediaan

![](<../../../.gitbook/assets/Screenshot 2022-05-31 120909.jpg>)

2\. Adjust Balance Qty (selalu adjust plus ke balance final qty)

![](<../../../.gitbook/assets/image (448).png>)

3\. Check Item History in Accurate

![](<../../../.gitbook/assets/image (450).png>)

4\. Pada Forstok di tab warehouse, update masuk ke Qty On Hand

![](<../../../.gitbook/assets/image (449) (1).png>)

**Stok Opname**

{% hint style="info" %}
Pastikan anda melakukan stok opname di luar jam operasional pemrosesan pemesanan, karena memulai perintah stok opname akan mengunci sistem stok untuk kategori barang yang anda sedang lakukan stok opname.
{% endhint %}

1. Klik menu Perintah Stok Opname

![](<../../../.gitbook/assets/Screenshot 2022-06-06 144915.jpg>)

2\. Isi mandatory fields/baris yang wajib diisi.&#x20;
