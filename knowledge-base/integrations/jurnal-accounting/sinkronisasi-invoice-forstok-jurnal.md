# Sinkronisasi Invoice (Forstok → Jurnal)

<figure><img src="../../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### **Field Mapping**

| **Forstok Invoice**  | **Jurnal Invoice/ Faktur** |
| -------------------- | -------------------------- |
| Channel / Store      | Nama pelanggan             |
| Channel / Store      | Tag                        |
| Marketplace Order ID | No. referensi pelanggan    |

### Faktur akan dibuat di Jurnal .&#x20;

Faktur di Jurnal akan dibuat dan ditandai sebagai dibayar secara otomatis berdasarkan status invoice di Forstok. Pembayaran yang diterima akan dipetakan berdasarkan COA.

{% hint style="warning" %}
Nama pelanggan di Jurnal akan menggunakan Channel/Store name. contoh Tokopedia - Mybabystore. Sesuai nama toko di Forstok
{% endhint %}

![](<../../../.gitbook/assets/Screen Shot 2022-03-10 at 1.19.56 PM (1).png>)

### Faktur penjualan dari orderan Marketplace:

![](<../../../.gitbook/assets/Screen Shot 2022-03-11 at 10.56.30 AM.png>)

<figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption><p>Invoice di Jurnal dengan detail payment received Forstok</p></figcaption></figure>
