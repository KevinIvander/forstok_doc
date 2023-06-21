# Stock Adjustment via Interface (v1)

Adjust stock via interface bisa dilakukan dengan 3 cara: 1. Pada menu Inventory, +Inventory--> Create Stock Adjustment; dan 2. klik produk di menu Inventory --> Adjust stock

### **1. Bulk Stock Adjustment via Interface**

1\. Klik +Inventory --> Create Stock Adjustment

<figure><img src="../../.gitbook/assets/Screenshot 2023-06-06 093042.jpg" alt=""><figcaption></figcaption></figure>

2\. Stock adjustment via interface bisa dilakukan dengan:

* Final Qty : Input new qty on hand/ jumlah fisik yang ada di gudang setelah ada perubahan
* Adjust Qty (+) : Input qty change, jumlah penambahan stok
* Adjust Qty (-) : Input qty change, jumlah pengurangan stok
* Warehouse : pilih gudang yang akan di update (ini biasanya untuk multi warehouse. Jika hanya 1 gudang hanya Primary Warehouse)
* Date : Tanggal update stock
* Reference # : Nomor referensi. Boleh kosong atau di input

<figure><img src="../../.gitbook/assets/Screenshot 2023-06-06 093117.jpg" alt=""><figcaption></figcaption></figure>

3\. Klik Continue, anda akan dialihkan ke page baru untuk menginput stock adjustment.

4\. **Final Qty.** Input qty yang akan di update pada kolom New Qty on Hand. untuk reason boleh di pilih atau tidak (opsional), lalu save

![](<../../.gitbook/assets/image (345).png>)

* **Adjust Qty (+)**. Input Qty yang akan di tambahkan. Misal stock sebelumnya 20 dan ingin menambahkan 5. Cukup input 5 pada Qty Adjusted. Maka New Qty On Hand bertambah jadi 25

![](<../../.gitbook/assets/image (346).png>)

* **Adjust Qty (-)**.  Untuk mengurangi stock yang ada saat ini. Misal stock saat ini 20 ingin dikurangi 5. Maka input 5 pada Qty Adjusted. Maka New Qty On Hand berkurang jadi 15

![](<../../.gitbook/assets/image (347).png>)

5\. Jika ingin menambahkan sku lain untuk update stock. Pilih Select items

![](<../../.gitbook/assets/image (344).png>)

* Cari sku atau centang sku yang di update stock, lalu klik Add to List

![](<../../.gitbook/assets/image (343).png>)

6\. Klik Notifications - Summary untuk melihat hasil stock adjustment

![](<../../.gitbook/assets/summary stock adjustment interface.jpg>)

**7. Anda bisa melihat rincian hasil stock adjustment.**

![](<../../.gitbook/assets/stock adjustment interface html.jpg>)

### **2. Individual Stock Adjustment via Interface**

1. Klik item yang ingin dilakukan stock adjustment --> Adjust Stock

![](<../../.gitbook/assets/individual stock adjustment.png>)

2\. Pilih tipe stock adjustment, pilih warehouse, date, dan reference number apabila ada, klik Continue

![](<../../.gitbook/assets/Screenshot 2022-03-24 141143 (1).jpg>)

3\. Apabila Final qty, input jumlah fisik barang terbaru di kolom new qty on hand, untuk adjust qty (-) dan (=), input jumlah penyesuaian stok. Reason sifatnya opsional.

![](<../../.gitbook/assets/Screenshot 2022-03-24 141341.jpg>)

#### **3. Adjust stock by Scanning barcode**&#x20;

Sebelum memulai update stock menggunakan barcode, pastikan Anda sudah mengiput barcode item Anda. Jika belum berikut panduan untuk menginput barcode.

**How to connect Barcode Scanner**:  Konekan barcode scanner melalui USB / bluetooth ke computer atau table.&#x20;

{% content-ref url="../master-products/create-barcode-label.md" %}
[create-barcode-label.md](../master-products/create-barcode-label.md)
{% endcontent-ref %}

Berikut langkah-langkah untuk update stock menggunakan scan barcode.

1\. Scan barcode item yang akan di tambahkan stocknya

![](<../../.gitbook/assets/image (340).png>)

2\. Jika ingin input stock lebih bisa scan beberapa kali barcode tsb. Misal ingin update stock jadi 5 maka bisa scan 5 kali barcode tsb. Lalu save

![](<../../.gitbook/assets/image (342).png>)

