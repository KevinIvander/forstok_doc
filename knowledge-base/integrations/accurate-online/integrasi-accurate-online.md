# Integrasi Accurate Online

{% embed url="https://drive.google.com/file/d/12-Vlk-8ReYRqrLi6rczrcWZ_BC7V1GEO/view?usp=drive_link" %}

<figure><img src="../../../.gitbook/assets/WhatsApp Image 2023-03-08 at 11.56.39.jpeg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}


**Existing User Accurate**

1. Integrasikan channel/marketplace ke forstok
2. Pastikan SKU di forstok tidak ada pending action (hal ini penting karena nanti ketika klik sync item, forstok akan mengirim seluruh data sku yang ada di forstok, termasuk SKU yang masih di pending actions);
3. Integrasikan accurate di forstok;
4. Mapping CoA dan WH Accurate di Forstok;
5. Klik Sync item forstok --> Accurate;
6. Klik Sync stock Accurate --> Forstok
7. Klik sync item forstok



**New User Accurate**

1. Integrasikan channel/marketplace ke forstok
2. Pastikan SKU di forstok tidak ada pending action (hal ini penting karena nanti ketika klik sync item, forstok akan mengirim seluruh data sku yang ada di forstok, termasuk SKU yang masih di pending actions);
3. Integrasikan accurate di forstok;
4. Mapping CoA dan WH Accurate di Forstok;
5. Klik Sync item forstok --> Accurate;
6. Penyesuaian Persediaan/Stok Opname di Accurate
7. Klik Sync stock Accurate --> Forstok
8. Klik sync item forstok
{% endhint %}

{% hint style="danger" %}
**Stock berkurang di accurate berdasarkan invoice, dengan demikian langsung memotong stok on hand/fisik. Begitu juga dengan di Forstok, kalau order RTS itu juga sudah memotong stok on hand.**

**Pastikan nama produk dan kode sku disamakan antara forstok dan accurate, kondisi nama produk sama dengan sku berbeda akan mengakibatkan error ketika auto create invoice di accurate**
{% endhint %}

1. **Add Integration > Choose “Accurate” > Click “Connect”**

[https://www.forstok.com/integrations](https://www.forstok.com/integrations)

![](<../../../.gitbook/assets/Screen Shot 2022-01-27 at 9.33.29 AM.png>)

2**. Login User & password Accurate**



{% hint style="info" %}
**Pastikan integrasi dilakukan dengan email owner/ akun utama, penggunaan email lain/nomor handphone akan mengakibatkan gagalnya proses integrasi**
{% endhint %}

![](<../../../.gitbook/assets/Screen Shot 2022-01-27 at 9.33.37 AM.png>)

3\. **Klik "Beri Akses"**

![](<../../../.gitbook/assets/Screen Shot 2022-01-27 at 9.33.43 AM.png>)

4\. **Select “Database “ > Click “Save”**

![](<../../../.gitbook/assets/image (449) (1) (1).png>)

{% hint style="warning" %}
1. data order yang di kirim ke accurate order setelah integrasi Accurate to forstok
2. Untuk ganti database harus integrasi ulang. Disconnect Accurate di Forstok
{% endhint %}
