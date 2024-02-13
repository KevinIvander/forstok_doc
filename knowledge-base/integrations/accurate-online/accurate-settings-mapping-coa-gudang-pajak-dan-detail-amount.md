# Accurate Settings - Mapping COA, gudang, pajak, dan detail amount

{% hint style="info" %}
Apabila setelah menyimpan mapping terdapat perubahan pada WH dan CoA di Accurate (**perubahan nama warehouse, penambahan warehouse, penghapusan warehouse utama, perubahan nama akun perkiraan**), pastikan dilakukan penyimpanan mapping kembali melalui Accurate Integration Settings, karena perubahan terhadap WH dan CoA di Accurate setelah sudah terintegrasi dengan Forstok akan mengakibatkan mappingan terlepas dan berdampak pada proses sinkronisasi stock serta sinkronisasi invoice.
{% endhint %}

1. **Click Setting Accurate**

![](<../../../.gitbook/assets/Screen Shot 2022-01-27 at 1.06.34 PM.png>)

\
2\. **Mapping to do list**

* Mapping COA : Pastikan sudah buat COA per store di Accurate. Hanya bisa mapping type COA Cash & Bank
* Mapping Warehouse : Hanya muncul warehouse yang sudah dibuat di Accurate

{% hint style="info" %}
**Pastikan penulisan COA dan Warehouse tidak dipisah oleh spasi, apabila terdiri dari 2 kata maka gunakan tanda pemisah seperti - atau \_ , atau bisa juga penulisan digabung.**&#x20;

**Contoh: Gudang-Marketplace, GudangMarketplace, WH-Tomang, Tokopedia\_Toko1,Shopee\_Toko1, dan seterusnya.**&#x20;
{% endhint %}

* Mapping Setting Tax ( On atau Off sesuai di Accurate )
* Mapping Shipping Price: other expense/ other income&#x20;

![](<../../../.gitbook/assets/image (446) (1).png>)

3\. Mapping detail amount/rincian penerimaan untuk masing-masing jenis penerimaan dari marketplace:

<figure><img src="../../../.gitbook/assets/Screenshot 2023-02-02 122541.jpg" alt=""><figcaption></figcaption></figure>



{% hint style="info" %}
Shipping fee mapping dan platform rebate mapping bisa dibuat pada akun Pendapatan Lainnya; Voucher seller, shipping fee difference, platform fulfillment fee, dan service fee mapping bisa dibuat di akun Beban lainnya di CoA accurate
{% endhint %}

4. **Click Save**

{% hint style="warning" %}
_Branch & Tax optional jika aktif di Accurate_
{% endhint %}
