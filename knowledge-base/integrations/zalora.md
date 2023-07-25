# Zalora

![](../../.gitbook/assets/screen-shot-2021-05-31-at-1.13.01-pm.png)

{% hint style="warning" %}
**Penting!** &#x20;

* Pastikan toko Anda sudah aktif tidak dalam keadaaan Holiday Mode
* Sebelum integrasi, pasti kan product yang sama di toko/ channel lain mempunyai Kode SKU yang sama. Setelah integration, product akan di import dan terlinking dengan product yang sama mengunakan Kode SKU.
{% endhint %}



## Cara Integrasi Zalora (Step-by-step)

1\.  Login ke seller center > ke page [https://sellercenter.zalora.co.id/oauth/apps](https://sellercenter.zalora.co.id/oauth/apps)

<figure><img src="../../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

2\. Klik "Add Application" > Input data dibawah ini:

**Application Name** : Forstok.com

**Authorization redirect URL** : [https://www.forstok.com/dashboard/channels/integrations/zalora/setup](https://www.forstok.com/dashboard/channels/integrations/zalora/setup)

Website URL : [https://app.forstok.com/](https://app.forstok.com/)\
\
Kemudian klik Save.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

3\. Hasil Data di bawah ini diinput di Forstok

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2023-06-30 145532.jpg" alt=""><figcaption></figcaption></figure>

### Pendaftaran Webhook Order

Setelah mengintegrasikan zalora ke akun Forstok, lakukan pendaftaran webhook order melalui Seller Center Zalora dengan langkah berikut:

<figure><img src="../../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

1. Pada SC Zalora, klik Pengaturan - Manajemen Integrasi - Add Webhook

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

2. Copy and Paste as Text url berikut:

https://order.forstok.com/channels/zalora/xxxx

{% hint style="info" %}
xxxx merupakan kombinasi angka yang merupakan account id, yang akan ada setelah Zalora terintegrasi, acc id bisa didapatkan dengan cara membuka Integration - Zalora Settings, kemudian pada URL dari halaman tersebut akan terdapat 4/5 angka yang merupakan account ID yang dibutuhkan.

Contoh: [https://www.forstok.com/dashboard/channels/settings/12345/edit](https://www.forstok.com/dashboard/channels/settings/12322/edit)\
Maka account id adalah 12345
{% endhint %}

3. Centang keseluruhan boks centang pada menu Order, kemudian klik Submit.
