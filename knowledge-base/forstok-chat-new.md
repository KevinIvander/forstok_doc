---
description: >-
  Fitur Forstok Chat merupakan fitur yang dapat menerima dan membalas chat yang
  masuk dari beberapa marketplace yang saat ini sudah terintegrasi di Forstok.
---

# Forstok Chat (NEW)

### Tampilan Utama (Dashboard)

Forstok chat dapat langsung diakses melalui dashboard setelah seller login melalui akun Forstok.

<figure><img src="../.gitbook/assets/Screenshot_36.png" alt=""><figcaption></figcaption></figure>

### Tampilan Forstok Chat

Saat ini marketplace yang sudah dapat terintegrasi dengan Forstok Chat adalah Shopee dan Tokopedia.&#x20;

Bagian sebelah kiri akan disesuaikan dengan jumlah marketplace (Shopee dan Tokopedia) yang sudah berhasil terintegrasi di Forstok.

<figure><img src="../.gitbook/assets/Screenshot_37.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Batasan / Limitasi:**&#x20;

* User harus melakukan activation.
* Shopee harus login terlebih dahulu karna App di API Shopeenya berbeda dgn ERP untuk versi chat saat ini.
* Tokopedia saat ini  tidak dapat mengirim produk (Karena dari MP nya tidak menyediakan).
* Shopee tidak dapat melihat informasi produk jika customer mengirimkan chat melalui Item Detail yang ada MP, namun akan tampil jika mengirimkan dari List Produk yang di chat.
* Tokopedia memiliki rate limit, sehingga chat akan masuk ke antrian di Forstok.



**Fitur yang akan di develop:**&#x20;

* Sorting list message (Pesan terbaru akan tampil paling atas by default).
* Handle link (Clickable).
* Enter to send message, Shift + Enter to new line.
* Send image (Tokopedia & Shopee).
* Manual sync chat (Button sync untuk mendapatkan chat sebelumnya).
* Order list (Setiap chatroom akan mempunyai list order yang berbeda-beda jika customer tersebut sudah mempunyai order sebelumnya).
* Setiap chat akan mempunyai status (Mine, Served, Unserved, Resolved).
* Mark as Resolved.
{% endhint %}
