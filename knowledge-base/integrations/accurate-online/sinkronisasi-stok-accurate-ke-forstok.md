# Sinkronisasi stok (Accurate → Forstok)

{% hint style="info" %}
**Apabila Accurate terintegrasi dengan akun Forstok, maka penyesuaian stok/stock adjustment harus dilakukan dari Accurate, karena flow penyesuaian stok berjalan 1 arah (Accurate --> Forstok --> Marketplace)**
{% endhint %}

Terdapat 2 cara untuk melakukan penyesuaian stok Accurate --> Forstok:

1. Klik Sync stock pada Integrations - Accurate Settings - Sync Stock

<figure><img src="../../../.gitbook/assets/Screenshot 2022-09-26 110100.jpg" alt=""><figcaption><p>Integrations - Accurate Settings</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Screenshot 2022-09-26 110305.jpg" alt=""><figcaption><p>Klik Sync Stock untuk menarik qty stock Accurate --> Forstok</p></figcaption></figure>

2\. Lakukan penyesuaian stok/stok opname dari Accurate, setiap perubahan stok yang berhasil dilakukan akan dikirim ke Forstok.

{% hint style="info" %}
**Sebelum melakukan penyesuaian stok/stok opname, pastikan penulisan nama dan sku di master data forstok sudah sama dengan di accurate, hal ini untuk mencegah terjadinya duplicate items ketika sync items dari Forstok --> Accurate**
{% endhint %}

Penyesuaian stok pada Accurate dapat dilakukan dengan 2 cara:&#x20;

1\. Satu per satu melalui fitur **Penyesuaian Persediaan**;&#x20;

2\. Secara bulk/masif melalui fitur **Stok Opname**

## **Penyesuaian Persediaan**

1. Klik menu Inventory/Persediaan, kemudian pilih Item Adjustment / Penyesuaian Persediaan

![](<../../../.gitbook/assets/Screenshot 2022-05-31 120909.jpg>)

2\. Adjust Balance Qty (selalu adjust plus ke balance final qty)

![](<../../../.gitbook/assets/image (448).png>)

3\. Check Item History in Accurate

![](<../../../.gitbook/assets/image (450).png>)

4\. Pada Forstok di tab warehouse, update masuk ke Qty On Hand

![](<../../../.gitbook/assets/image (449) (1).png>)
