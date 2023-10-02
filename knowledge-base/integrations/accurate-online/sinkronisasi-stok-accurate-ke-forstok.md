# Sinkronisasi stok (Accurate → Forstok)

{% hint style="danger" %}


Berikut adalah list data di Accurate Online yang akan mentrigger webhook update stok di Forstok:

1. Stock Awal pada Barang & Jasa
2. Pengiriman Pesanan
3. Faktur Penjualan
4. Retur Penjualan
5. Penerimaan Barang
6. Faktur Pembelian
7. Retur Pembelian
8. Pekerjaan Pesanan
9. Penyelesaian Pesanan
10. Penambahan Bahan Baku
11. Penyesuaian Persediaan
12. Pemindahan Barang
13. Hasil Stok Opname
14. Klaim Pemasok
15. Klaim Pelanggan
16. Pengambilan Bahan Baku Manufaktur
17. Penyelesaian Barang Jadi Manufaktur

\

{% endhint %}

{% hint style="info" %}
**Apabila Accurate terintegrasi dengan akun Forstok, maka penyesuaian stok/stock adjustment harus dilakukan dari Accurate, karena flow penyesuaian stok berjalan 1 arah (Accurate --> Forstok --> Marketplace)**
{% endhint %}

Terdapat **2 langkah** untuk melakukan Sync stok Accurate --> Forstok:

1. Lakukan **penyesuaian persediaan** dari Accurate;
2. Klik **Sync Stock** pada Accurate Integration Settings

{% hint style="info" %}
**Sebelum melakukan penyesuaian persediaan, pastikan penulisan nama dan sku di master data forstok sudah sama dengan di accurate, hal ini untuk mencegah terjadinya duplicate items ketika sync items dari Forstok --> Accurate**
{% endhint %}

## **Langkah pertama: Penyesuaian Persediaan**

1. Klik menu Inventory/Persediaan, kemudian pilih Item Adjustment / Penyesuaian Persediaan

<figure><img src="../../../.gitbook/assets/image (4) (2) (1).png" alt=""><figcaption></figcaption></figure>

2. Adjust Balance Qty (selalu adjust plus ke balance final qty)

<figure><img src="../../../.gitbook/assets/image (1) (1) (3) (1).png" alt=""><figcaption></figcaption></figure>

3. Check Item History in Accurate

<figure><img src="../../../.gitbook/assets/image (2) (2) (1) (2).png" alt=""><figcaption></figcaption></figure>

4. Pada Forstok di tab warehouse, update masuk ke Qty On Hand

<figure><img src="../../../.gitbook/assets/image (29) (1).png" alt=""><figcaption></figcaption></figure>

## **Langkah kedua**: klik tombol **Sync Stock**



{% hint style="info" %}
Klik tombol Sync Stock apabila terdapat transfer stok dari gudang A ke gudang B.
{% endhint %}

1. Klik menu Integrations - Accurate Settings

<figure><img src="../../../.gitbook/assets/image (3) (2) (1).png" alt=""><figcaption></figcaption></figure>

2. Klik Sync stock pada Integrations - Accurate Settings - Sync Stock

<figure><img src="../../../.gitbook/assets/Screenshot 2022-09-26 110305.jpg" alt=""><figcaption><p>Klik Sync Stock untuk menarik qty stock Accurate --> Forstok</p></figcaption></figure>

{% hint style="info" %}

{% endhint %}
