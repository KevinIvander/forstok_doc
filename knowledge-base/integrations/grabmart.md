# Grabmart

{% hint style="warning" %}
**!! Penting !!**

Sebelum mengaktifkan fitur sync item ON di Forstok, seller harus melakukan _add item_ terlebih dahulu di Forstok sesuai dengan data di Grabmart (jika sudah ada item di Grabmart).

Jika fitur sync item ON diaktifkan ketika item belum ditambahkan di Forstok, maka seluruh item yang ada di Grabmart akan hilang (karena di Forstok tidak ada item Grabmart).
{% endhint %}

![](<../../.gitbook/assets/Screen Shot 2022-03-08 at 12.37.32 PM.png>)

{% hint style="success" %}
**Fitur yang tersedia**

1. Add / Edit Listing produk dari Forstok → GrabMart.
2. Perbarui stok dari Forstok → GrabMart.
3. Mendapatkan pesanan baru dari GrabMart → Forstok. GrabMart order will be auto accept.&#x20;
{% endhint %}

{% hint style="danger" %}
**Batasan / API Limitation**

1. Tidak bisa import produk baru dari GrabMart. Harus add listing Forstok ke GrabMart terlebih dahulu untuk Linking Product
2. Tidak bisa manual confirm order. Driver pickup bisa diset secara manual ke PIC GrabMart langsung. &#x20;
{% endhint %}

## Steps

1. **Seller Request ke PIC Grabmart untuk add store ke Partner ID Forstok: 91f036fa-bf92-4deb-9d65-d4303d24a4b7**

![](<../../.gitbook/assets/image (443).png>)

2\. Setelah itu, nanti akan muncul Store id untuk Seller.

3\. Store id tersebut diberikan kepada tim Forstok untuk diproses.

4\. Tim Forstok akan menambahkan secara manual ke database.

5\. Channel Grabmart akan muncul di menu Integrations;

6\. Silahkan melakukan listing ke grabmart melalui Add Listing[Broken link](broken-reference "mention") atau Cross Listing[cross-listing-xls.md](../listing-products/cross-listing-xls.md "mention").

