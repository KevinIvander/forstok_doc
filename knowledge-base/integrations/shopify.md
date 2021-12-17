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

**Contoh URL Link:** [onycha.myshopify.com](http://onycha.myshopify.com)\


![](<../../.gitbook/assets/image (421).png>)

3\. Scroll kebawah lalu klik **Install Unlisted App**\
****

![](https://lh3.googleusercontent.com/0LDmdUl52d8LHByTdcj4ER3QXDRcdFbe135EQ1n5TUsOHcM\_JMgPazOT0V-x9kk2kbZi-6BXXUbanpO03yNfg-P2XK9zEkvTSXG0wafEAzj0-AO0mzzMzNDpU9sJTdOdJ-6zhzoc) ![](../../.gitbook/assets/app.jpg)



4\. Pada Product Catalog pilih **Sync Product from Shopee** >**Next** \
****

![](https://lh5.googleusercontent.com/PfgpwCJAnMk9BP7JUoqCJZnucAuoEuTdV\_gh8kr5VizBrzJ3ovX2uQnn2bUq94V8KBh2LE3B4PfQjGElC2ZPdN0kn\_t0pJ8ukJYM4O-ww2Cz3i2XRRr4we8SaUC2v37cj1-GKjEh) ![](../../.gitbook/assets/inventory.jpg)



5\. Lalu pilih **Finish**\
****

![](https://lh6.googleusercontent.com/Lp1V2183urp-JGxes8UmLg1Pc\_5Xc5RxMXXt\_QBs8Cm3t2q6hGmXjSkeB8vGDIY8mhlO3OJR1a4yPHjjK3vB0CQXvCT2m-DlXN\_m-uQCK1ixC9z9Iuxf1UTaVEFdtjioQ8-n27Ee) ![](../../.gitbook/assets/finish.jpg)

## Mendaftarkan webhook

Setelah berhasil integrasi, harap daftarkan Webhook order dari seller center Shopify. _Webhook_ atau yang biasa disebut _callback_ adalah cara bagi suatu aplikasi untuk menyediakan aplikasi lain dengan informasi _real-time_. Jika sudah mendaftarkan webhook ini, maka jika terjadi order baru atau order update dari Shopify system akan dikirim ke Forstok application secara real-time.

1\. Log ke Shopify,  pilih **Settings** pada menu di sebelah kiri → lalu klik **Notifications**

![](https://lh4.googleusercontent.com/Itpx5JfT\_B1m6D9xwiASDge6R53LmylM\_q5hg5gE1kNFCNhECP1rZ-eBUFUTDjRoKeasQB5enm1NLZrHvMltzQ0PICkV\_OolFf-5oANE9-kYhEps89VKoPiqf41BGzlXeiOh\_1\_S) ![](../../.gitbook/assets/see.jpg) ![](../../.gitbook/assets/notif.jpg)

2\. Scroll kebawah lalu klik **create webhook**

![](https://lh5.googleusercontent.com/EzAl2S-BqUVGxI3Nx0pqu5sGSS6Bnef5gshDxLYejq5YNKYljFBABsd5X4E12g5K6A7JdC2ZtIpJ4vBYsxfh57Gmta7eimJH3XGTmANpPM9-nkPT8lhtxnDXx6bVFaK72DdE-1j0) ![](../../.gitbook/assets/wee.jpg)

3\. Pada Add a webhook input:\
**URL:** [**https://order.forstok.com/channels/shopify**\
****](https://orders.forstok.com/channels)**Webhook API version: pilih yang Latest**

Order/creation\
orders/fulfillment \
orders/payment \
orders/update \
order/cancellation

![](<../../.gitbook/assets/image (400).png>)

![](<../../.gitbook/assets/image (401).png>)

****
