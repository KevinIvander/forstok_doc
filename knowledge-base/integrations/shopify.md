# Shopify

![](../../.gitbook/assets/screen-shot-2021-05-31-at-1.16.24-pm.png)

{% hint style="info" %}
Untuk integrasi Shopify ada 2 point:\
1\. Integrasi Shopify ke Forstok\
2\. Mendaftarkan order webhook Shopify
{% endhint %}

## Integrasi

Pastikan Anda sudah Log In ke seller center Shopify atau akun Shopify

\
1.Buka Link berikut:\
[**https://www.forstok.com/dashboard/channels/integrations/shopify/setup**](https://www.forstok.com/dashboard/channels/integrations/shopify/setup)****\
****\
****2. Input URL Link myshopify

**Contoh URL Link:** [onycha.myshopify.com](http://onycha.myshopify.com/)\


![](<../../.gitbook/assets/image (421).png>)

3\. Scroll kebawah lalu klik **Install Unlisted App**

![](<../../.gitbook/assets/install unlisted app.jpg>)

4\. Pada Inventory pilih **Import Products from Shopify --> Next**&#x20;

![](<../../.gitbook/assets/Screenshot 2022-04-01 100048.jpg>)

5\. Apabila integrasi berhasil, muncul notifikasi di pojok kanan atas, klik **Finish** untuk kembali ke Dashboard

![](<../../.gitbook/assets/shopify success (1).jpg>)

{% hint style="info" %}
**PERLU DIKETAHUI:**

1. **Saat ini masih terdapat limitasi, di mana integrasi shopify hanya bisa dilakukan ke 1 warehouse shopify, yaitu warehouse utama/ warehouse default, apabila warehouse shopify ada lebih dari 1, mohon komunikasikan ke tim Forstok;**
2. **Infokan ke tim Forstok location id dari wh shopify melalui email onboarding@forstok.com setelah berhasil melakukan integrasi channel Shopify, location id bisa didapatkan dengan mengirimkan url saat membuka Settings - Location - klik lokasi warehouse yang mau di connect in ke forstok. Contoh: https://toko123.myshopify.com/admin/settings/locations/10236804;**
3. **Forstok hanya akan mengimport produk dengan status aktif dan **_**in stock**_**/ stok tersedia, apabila stok masih 0, lakukan penyesuaian terlebih dahulu agar item bisa terimport ke Forstok.**
{% endhint %}

## Mendaftarkan webhook

Setelah berhasil integrasi, harap daftarkan Webhook order dari seller center Shopify. _Webhook_ atau yang biasa disebut _callback_ adalah cara bagi suatu aplikasi untuk menyediakan aplikasi lain dengan informasi _real-time_. Jika sudah mendaftarkan webhook ini, maka jika terjadi order baru atau order update dari Shopify system akan dikirim ke Forstok application secara real-time.

1\. Log ke Shopify,  pilih **Settings** pada menu di sebelah kiri → lalu klik **Notifications**

![](<../../.gitbook/assets/settings webhook shopify.jpg>)

2\. Scroll kebawah lalu klik **create webhook**

![](<../../.gitbook/assets/create webhook shopify.jpg>)

3\. Pada Add a webhook input:\
**URL:** [**https://order.forstok.com/channels/shopify**](https://order.forstok.com/channels/shopify)****\
**Webhook API version: pilih yang Latest**

Order/creation\
orders/fulfillment \
orders/payment \
orders/update \
order/cancellation

![](<../../.gitbook/assets/image (400).png>)

![](<../../.gitbook/assets/image (401).png>)

****
