# Shopify (new integration)

![](../../.gitbook/assets/screen-shot-2021-05-31-at-1.16.24-pm.png)

{% hint style="info" %}
Untuk integrasi Shopify ada 2 point:\
1\. Mendapatkan API Key, API Access Token di Seller Center Shopify\
2\. Integrasi Shopify ke Forstok
{% endhint %}

## Integrasi

Log In ke seller center Shopify atau akun Shopify

1. Klik **Settings**

<figure><img src="../../.gitbook/assets/1s.jpg" alt=""><figcaption></figcaption></figure>

2. Apps and sales channels --> Develop apps

<figure><img src="../../.gitbook/assets/2s.jpg" alt=""><figcaption></figcaption></figure>

3. Allow custom app development

<figure><img src="../../.gitbook/assets/3s.jpg" alt=""><figcaption></figcaption></figure>

4. Klik **Allow custom app development** kembali

<figure><img src="../../.gitbook/assets/4s.jpg" alt=""><figcaption></figcaption></figure>

5. Create an app

<figure><img src="../../.gitbook/assets/5s.jpg" alt=""><figcaption></figcaption></figure>

6. Isi **App name** --> **Create app**

<figure><img src="../../.gitbook/assets/6s.jpg" alt=""><figcaption></figcaption></figure>

7. Pada menu App development, klik **API Credentials** --> **Configure Admin API scopes**

<figure><img src="../../.gitbook/assets/7s.jpg" alt=""><figcaption></figcaption></figure>

8. Centang seluruh jenis akses

<figure><img src="../../.gitbook/assets/85s.jpg" alt=""><figcaption></figcaption></figure>

9. Klik **Save**

<figure><img src="../../.gitbook/assets/8s.jpg" alt=""><figcaption></figcaption></figure>

10. Klik tab **API** credentials -->**Install app**

<figure><img src="../../.gitbook/assets/9s.jpg" alt=""><figcaption></figcaption></figure>

11. Klik **Install**

<figure><img src="../../.gitbook/assets/10s.jpg" alt=""><figcaption></figcaption></figure>

12. Pada tab **API Credentials**, klik **Reveal token once**, copy API access token dan API key, simpan untuk digunakan pada proses integrasi Shopify di Forstok

<figure><img src="../../.gitbook/assets/11s.jpg" alt=""><figcaption></figcaption></figure>

## Integrasi Shopify di Forstok

1. Login ke Forstok
2. Klik Integration - Add Integrations&#x20;
3. Input **API Key**, **Admin API Access Token**, dan domain web

{% hint style="info" %}
**PERLU DIKETAHUI:**

1. **Saat ini masih terdapat limitasi, di mana integrasi shopify hanya bisa dilakukan ke 1 warehouse shopify, yaitu warehouse utama/ warehouse default, apabila warehouse shopify ada lebih dari 1, mohon komunikasikan ke tim Forstok;**
2. **Infokan ke tim Forstok location id dari wh shopify melalui email onboarding@forstok.com setelah berhasil melakukan integrasi channel Shopify, location id bisa didapatkan dengan mengirimkan url saat membuka Settings - Location - klik lokasi warehouse yang mau di connect in ke forstok. Contoh: https://toko123.myshopify.com/admin/settings/locations/10236804;**
3. **Forstok hanya akan mengimport produk dengan status aktif dan **_**in stock**_**/ stok tersedia, apabila stok masih 0, lakukan penyesuaian terlebih dahulu agar item bisa terimport ke Forstok.**
{% endhint %}
