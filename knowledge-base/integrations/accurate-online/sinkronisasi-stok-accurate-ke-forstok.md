# Sinkronisasi stok (Accurate → Forstok)

{% hint style="info" %}
**Apabila Accurate terintegrasi dengan akun Forstok, maka penyesuaian stok/stock adjustment harus dilakukan dari Accurate, karena flow penyesuaian stok berjalan 1 arah (Accurate --> Forstok --> Marketplace)**
{% endhint %}

Terdapat **2 langkah** untuk melakukan Sync stok Accurate --> Forstok:

1. Lakukan **penyesuaian persediaan** dari Accurate;
2. Klik **Sync Stock** pada Accurate Integration Settings

{% hint style="info" %}
**Sebelum melakukan penyesuaian persediaan, pastikan penulisan nama dan sku di master data forstok sudah sama dengan di accurate, hal ini untuk mencegah terjadinya duplicate items ketika sync items dari Forstok --> Accurate**
{% endhint %}

## **Langkah pertama: Penyesuaian Persediaan**

1. Klik menu Inventory/Persediaan, kemudian pilih Item Adjustment / Penyesuaian Persediaan

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

2. Adjust Balance Qty (selalu adjust plus ke balance final qty)

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

3. Check Item History in Accurate

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

4. Pada Forstok di tab warehouse, update masuk ke Qty On Hand

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

## **Langkah kedua**: klik tombol **Sync Stock**

1. Klik menu Integrations - Accurate Settings

<figure><img src="../../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

2. Klik Sync stock pada Integrations - Accurate Settings - Sync Stock

<figure><img src="../../../.gitbook/assets/Screenshot 2022-09-26 110305.jpg" alt=""><figcaption><p>Klik Sync Stock untuk menarik qty stock Accurate --> Forstok</p></figcaption></figure>
