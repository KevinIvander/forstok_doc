# Sinkronisasi stok (Accurate → Forstok)

{% hint style="info" %}
**Apabila Accurate terintegrasi dengan akun Forstok, maka penyesuaian stok/stock adjustment harus dilakukan dari Accurate, karena flow penyesuaian stok berjalan 1 arah (Accurate --> Forstok --> Marketplace)**
{% endhint %}

Terdapat 2 cara untuk melakukan penyesuaian stok Accurate --> Forstok:

1. Klik Sync stock pada Integrations - Accurate Settings - Sync Stock

<figure><img src="../../../.gitbook/assets/Screenshot 2022-09-26 110100.jpg" alt=""><figcaption><p>Integrations - Accurate Settings</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Screenshot 2022-09-26 110305.jpg" alt=""><figcaption><p>Klik Sync Stock untuk menarik qty stock Accurate --> Forstok</p></figcaption></figure>

2\. Lakukan penyesuaian stok/stok opname dari Accurate, setiap perubahan stok yang berhasil dilakukan akan dikirim ke Forstok.

{% hint style="info" %}
**Sebelum melakukan penyesuaian stok/stok opname, pastikan penulisan nama dan sku di master data forstok sudah sama dengan di accurate, hal ini untuk mencegah terjadinya duplicate items ketika sync items dari Forstok --> Accurate**
{% endhint %}

Penyesuaian stok pada Accurate dapat dilakukan dengan 2 cara:&#x20;

1\. Satu per satu melalui fitur **Penyesuaian Persediaan**;&#x20;

2\. Secara bulk/masif melalui fitur **Stok Opname**

## **Penyesuaian Persediaan**

1. Klik menu Inventory/Persediaan, kemudian pilih Item Adjustment / Penyesuaian Persediaan

![](<../../../.gitbook/assets/Screenshot 2022-05-31 120909.jpg>)

2\. Adjust Balance Qty (selalu adjust plus ke balance final qty)

![](<../../../.gitbook/assets/image (448).png>)

3\. Check Item History in Accurate

![](<../../../.gitbook/assets/image (450).png>)

4\. Pada Forstok di tab warehouse, update masuk ke Qty On Hand

![](<../../../.gitbook/assets/image (449) (1).png>)

## **Stok Opname**

{% hint style="info" %}
Pastikan anda melakukan stok opname di luar jam operasional pemrosesan pemesanan, karena memulai perintah stok opname akan mengunci sistem stok untuk kategori barang yang anda sedang lakukan stok opname.
{% endhint %}

1. Klik menu Perintah Stok Opname

![](<../../../.gitbook/assets/Screenshot 2022-06-06 144915.jpg>)

2\. Isi mandatory fields/baris yang wajib diisi (terdapat tanda '**\***'), kemudian klik Save.&#x20;

![](<../../../.gitbook/assets/Screenshot 2022-06-06 145809.jpg>)

3\. Klik Menu Persediaan --> Barang dan Jasa

![](<../../../.gitbook/assets/Screenshot 2022-06-06 151804.jpg>)

4\. Klik menu di pojok kiri atas

![](<../../../.gitbook/assets/Screenshot 2022-06-06 151850.jpg>)

5\. Klik Ekspor Data --> Ekspor ke Excel, kemudian buka file daftar barang.&#x20;

![](<../../../.gitbook/assets/Screenshot 2022-06-06 152150.jpg>)

6\. Pada menu Persediaan, klik Hasil Stok Opname

![](<../../../.gitbook/assets/Screenshot 2022-06-06 152723.jpg>)

7\. Klik tombol cari pada baris Perintah Opname, pilih Perintah Opname yang sudah dibuat.

![](<../../../.gitbook/assets/Screenshot 2022-06-06 152900.jpg>)

8\. Klik Impor dari excel

![](<../../../.gitbook/assets/Screenshot 2022-06-06 152940.jpg>)

9\. Download template stok opname dengan klik bagian yang dimerahkan.

![](<../../../.gitbook/assets/Screenshot 2022-06-06 153003.jpg>)

10\. Isi kolom Nama Barang, Kode, dan Unit berdasarkan daftar barang yang sebelumnya sudah diunduh.

![](<../../../.gitbook/assets/Screenshot 2022-06-06 153313.jpg>)

11\. Setelah selesai mengisi daftar barang yang akan dilakukan stok opname, simpan file, kembali lagi ke menu upload excel stok opname. Kemudian klik Save.&#x20;

![](<../../../.gitbook/assets/Screenshot 2022-06-06 153028.jpg>)
