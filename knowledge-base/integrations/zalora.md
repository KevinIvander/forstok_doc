# Zalora

![](../../.gitbook/assets/screen-shot-2021-05-31-at-1.13.01-pm.png)

{% hint style="warning" %}
**Penting!** &#x20;

* Pastikan toko Anda sudah aktif tidak dalam keadaaan Holiday Mode
* Sebelum integrasi, pasti kan product yang sama di toko/ channel lain mempunyai Kode SKU yang sama. Setelah integration, product akan di import dan terlinking dengan product yang sama mengunakan Kode SKU.
{% endhint %}



## Cara Integrasi Zalora (Step-by-step)

1\. Untuk Integrasi ke Zalora terlebih dahulu log in ke seller center Zalora di [https://sellercenter.zalora.co.id/](https://sellercenter.zalora.co.id/) untuk mendapatkan API Zalora.\
Pilih Settings > Integration Management

![](<../../.gitbook/assets/image (206).png>)

2\. Pada kolom API dan API Key copy paste API Zalora pada integrasi Zalora Forstok.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48083377573/original/obOk93Wne9EGacURGzoXJck-DfSGO6KsqA.png?1611654341)

3\. Pilih menu Integrations --> pilih Add Integrations

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062574882/original/BdIDq-WRz6e8oEZ9NQnU1Uj6VFDxR3Meuw.png?1601815709)

4\. Klik View/Connect untuk integrasikan Zalora

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48064002742/original/GLjyBNBUDWljjGbHVEwCWzmNmbbKPtaFXg.png?1602444620)

5\. Input Email log Zalora dan API Key Zalora yang sudah kita dapatkan pada point 2. Lalu klik Install Zalora

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48083378641/original/5cjmEKMS4fUzFy1kmzwReahG5x5SC3yZrg.png?1611654590)

6\. Pada Product Catalog pilih **Sync Product from Zalora --**>**Next --**> pilih **Finish**

![](<../../.gitbook/assets/image (374).png>)

7\. Maka Zalora berhasil integrasi ke Forstok dan sedang proses import produk.&#x20;

### Pendaftaran Webhook Order

Setelah mengintegrasikan zalora ke akun Forstok, lakukan pendaftaran webhook order melalui Seller Center Zalora dengan langkah berikut:

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

1. Pada SC Zalora, klik Pengaturan - Manajemen Integrasi - Add Webhook

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

2. Copy and Paste as Text url berikut:

https://order.forstok.com/channels/zalora/xxxx

{% hint style="info" %}
Untuk mendapatkan 4 angka terakhir (xxxx), yang merupakan account ID, silahkan menghubungi tim Forstok agar diberikan account id yang perlu didaftarkan
{% endhint %}

3. Centang keseluruhan boks centang pada menu Order, kemudian klik Submit.
