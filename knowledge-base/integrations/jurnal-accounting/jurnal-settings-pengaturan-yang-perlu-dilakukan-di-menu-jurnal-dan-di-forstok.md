# Jurnal Settings - Pengaturan yang perlu dilakukan di menu Jurnal

Catatan: Chart of Account di Jurnal diperlukan untuk menandai faktur sebagai lunas

### 1. Buat COA di Jurnal

Login ke Jurnal terlebih dulu. Buat Chart of Account (COA) per marketplaces.&#x20;

[https://my.jurnal.id/registers/new](https://my.jurnal.id/registers/new)\


<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

![](<../../../.gitbook/assets/Screenshot\_1 (2).png>)

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption><p>Buatkan akun Pendapatan Lainnya untuk komponen biaya Platform Rebate dan Shipping Fee</p></figcaption></figure>

### Buat CoA sesuai dengan mappingan komponen biaya di fitur Invoice Forstok:

Voucher Seller, Shipping Difference (Cashless), Platform Fulfillment Fee, Service Fee dibuatkan masing-masing akun di Jurnal

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### 2. Create New Product di Jurnal untuk Platform Rebate dan Shipping Fee&#x20;

**Product Name:**

1. Platform Rebate (SKU : platformrebate)
2. Shipping Fee (SKU : shippingfee)&#x20;

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
( 2 detail payment receive ini tidak masuk ke detail Jurnal, akan masuk sebagai produk baru )
{% endhint %}

### 3. Mappingkan COA di Forstok

Login ke Forstok dulu. Memetakan COA Jurnal ke setiap sales channel di Forstok. &#x20;

[https://www.forstok.com/jurnal-settings](https://app.forstok.com/dashboard/channels/settings/1018/edit)\


![](../../../.gitbook/assets/Screenshot\_2.png)

{% hint style="info" %}
**Pastikan penulisan nama dan kode warehouse (wajib diisi) tidak menggunakan spasi, gunakan - atau  **_**apabila terdiri dari dua kata. Contoh: Gudang\_Cengkareng, WH-001.**_
{% endhint %}

### 4. Mappingkan Gudang di Forstok dan Jurnal

Apabila terdapat lebih dari 1 (satu) gudang di Jurnal, pastikan warehouse code di Jurnal sudah terisi agar stok dapat ter-update ke warehouse yang sesuai di Forstok. Stok akan otomatis ter-update di Primary Warehouse Forstok apabila warehouse code tidak diisi.

Untuk melihat warehouse code di Jurnal:&#x20;

1. klik **Produk** --> **Gudang**, warehouse code bisa dilihat di setiap gudang.

![](<../../../.gitbook/assets/wh code jurnal.jpg>)

2\. Untuk edit warehouse code, klik '**Ubah Gudang**'

![](<../../../.gitbook/assets/ubah gudang\_jurnal.png>)

3\. Masukkan warehouse code pada baris '**Kode**', kemudian klik '**Update Gudang**'

![](<../../../.gitbook/assets/wh code ubah\_jurnal.jpg>)

### 5. Aktifkan fitur Multipemotongan di Jurnal

<figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>
