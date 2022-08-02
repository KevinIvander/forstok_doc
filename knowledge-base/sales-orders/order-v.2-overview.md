# Order v.2 Overview (NEW)

## What's new&#x20;

1. **New Interface**: Tab order status, sorting, filter grouping, hide order fulfilled by channel, filter date.
2. **New status:** “Not shipped” menggantikan status “Printed”. Printed berubah jadi order flagging.
3. **2 Steps order Processing:** Open → Create Shipment (Not Shipped) → Mark as Ready to Ship
4. **Fulfill by channel Flag**: Tokocabang, FBL Lazada, FBB Blibli, SBS Shopee, FBJ JD.
5. **Warehouse User permission.:** User warehouse jakarta cuma bisa process order untuk warehouse Jakarta saja.&#x20;
6. **Delivery SLA time:** Deliveri limit waktu per marketplace
7. **WMS App**: Create picklist and package (Enterprise tiers only)

{% hint style="warning" %}
<mark style="color:orange;">**Order v1 masih bisa digunakan sampai 30 Juni 2022.**</mark>
{% endhint %}

### New Interface

Akses order v.2 melalui dropdown menu.

![](../../.gitbook/assets/Screenshot\_21.png)

### New Order Status

|   ORDER v.1 STATUS   |                                      ORDER v.2 STATUS                                      |
| :------------------: | :----------------------------------------------------------------------------------------: |
|  **Pending Payment** |                                     **Pending Payment**                                    |
|       **Open**       |                                          **Open**                                          |
|          N/A         | <p><strong>Not Picked / Picked</strong> (Optional) <br>(After action: Create Picklist)</p> |
|          N/A         |       <p><strong>Packed</strong> (Optional) </p><p>(After action: Create Package)</p>      |
|      **Printed**     |         <p><strong>Not Shipped</strong> </p><p>(After action: Create Shipment)</p>         |
|   **Ready to Ship**  |       <p><strong>Ready to Ship</strong> </p><p>(After action: Mark Ready to Ship)</p>      |
|      **Shipped**     |                                         **Shipped**                                        |
|     **Delivered**    |                                        **Delivered**                                       |
|     **Cancelled**    |                                        **Cancelled**                                       |

Order v.2 mempunyai 2 steps order processing sesuai seller center MP, di mana seller bisa menggunakan fitur “Create Shipment” di Forstok untuk Terima Order di toped, create package di Blibli, Lazada, zalora, zilingo&#x20;

Sehingga seller dapat print AWB tanpa trigger Ready to Ship ke channel/marketplace, sehingga paket dapat disiapkan terlebih dahulu sebelum dilakukan pemanggilan kurir (Ready to Ship)

### **Order Mapping per Marketplace**

&#x20;Berikut untuk melihat status order di Forstok dan di channel/marketplace

{% embed url="https://docs.google.com/spreadsheets/d/1N38sX9c57xPJ5o_2T8Qv8cr41tuHhO_L1I2T0QHjCiI/edit#gid=0" %}
[https://docs.google.com/spreadsheets/d/1N38sX9c57xPJ5o\_2T8Qv8cr41tuHhO\_L1I2T0QHjCiI/edit#gid=0](https://docs.google.com/spreadsheets/d/1N38sX9c57xPJ5o\_2T8Qv8cr41tuHhO\_L1I2T0QHjCiI/edit#gid=0)
{% endembed %}

### **2 steps order processing**

Order v.2 mempunyai 2 steps order processing sesuai seller center MP, di mana seller bisa menggunakan fitur “Create Shipment” di Forstok untuk Terima Order di toped, create package di Blibli, Lazada, zalora, zilingo.\
\
Namun untuk saat ini juga sudah ada fitur Create Shipment + Ready to Ship yang bisa digunakan seller untuk langsung memproses orderan sehinga bisa menampilkan AWB orderan tersebut.&#x20;

Sehingga seller dapat print AWB tanpa trigger Ready to Ship ke channel/marketplace, sehingga paket dapat disiapkan terlebih dahulu sebelum dilakukan pemanggilan kurir (Ready to Ship)

![](../../.gitbook/assets/Screenshot\_22.png)

### Tap to Ship: Not Shipped → Ready to Ship

Apabila sudah dilakukan Create Shipment, order akan berpindah ke tab ‘To Ship’. seller sudah bisa print shipping label dengan AWB untuk menyiapkan paket sebelum trigger Ready to Ship untuk pemanggilan kurir. Marketplace yg bisa print AWB tanpa RTS adalah Toped, Blibli, Lazada, JD

![](https://lh5.googleusercontent.com/FrEpEs-oMy6asKXJO5Ib4TQc4-T6NFU\_qd00yObYRs9VBLycD8VWcXmc6YxgQGh5lWP9uknyv2ir8LFsgDd4tGIi0ugzIXwkBdH\_RFxpgq1BICCkTm5XaAoVmtjRZxsDpJrIAvL6op\_9)

### Hide orders fulfilled by channels

Gunakan filter “hide orders fulfilled by channel” untuk membedakan orderan yang diproses oleh seller and yang diprocess oleh seperti Tokocabang, FBB by Blibli, FBL by Lazada, dsb., karena orderan tersebut bersifat view only (tidak bisa diproses).

![](https://lh5.googleusercontent.com/ax8mswDSud6lVgaEgO6vwCs\_jw9p6mGZHwQdDTHL5B0kALNdaaOf4XwPZnMewBRL5Uo-xrpndiNvWr4pWXbMB7p5JzhV8Dt9twp-JARU7mVmRxK1aQtFgDtOEstFQkgOPyU-sA)

### Search Filter

Klik ‘Forstok Order ID’ untuk memilih kategori pencarian berdasarkan: Forstok Order ID, Channel Order ID, Customer Name, Product SKU dan Product Name.

![](https://lh5.googleusercontent.com/kzg6hf8HDDnTWmAUPqJUkuwv7dffeWo5kXH-zh8Wb\_HioZ5WzJGKtHF57Df93UFecv0oiA2EELyV---ogE\_YCuUnR4onXc82xlDnWblxLPWbR-ajTfk9F3VugJ2eWacKmymp7Q)

### Filter Order by stores, warehouse, courier

Klik ‘Filter’ pada masing-masing tab status order (Pending, Open, To Ship, dst) untuk melakukan filter order berdasarkan Stores, Warehouses, couriers, Print status, picklist and package status.

Saat ini seller juga bisa menggunakan filter di tab yang berbeda apabila seller ingin menggunakan filter yang berbeda pada setiap tab sehingga untuk tab yang pertama dengan tab yang lainnya memiliki filter berbeda yang memudahkan ketika memproses orderan yang masuk.\


![](https://lh5.googleusercontent.com/72F3w5nl2R5AkwQKrMAyEgyKBCn8Iy5F5FnmmPaq-sGz6KAaNCM6rupiXCe\_A9dCnAr1y89AbH7y\_U5Arkp1BeSU3cpR2fmePhZFADRYQJ8fYi1y1xJ8onSSbLDWLfjv655Gsw)

### Sort Order

Klik ‘Sort by: Created Time (New First)’ untuk memilih urutan tampilan order berdasarkan: Created Time (New First), Created Time (Old First), Updated Time (New First) and Updated Time (Old First).

![](https://lh3.googleusercontent.com/0nOzpMwnANQHHlGZ\_vP-DkoTR4Ayj0BN7hKnZaRyUjPtJoiIio0-i1ksdC97leI\_HKK8wUjgwiy9ARRHLhUQzj\_SQ3aSc8ydk1ZtpA0Zrpank7\_7\_ILJVEmQtPfW3uFHe2wr6w)

### Bulk Actions

Klik box centang di samping ‘Bulk Select’ , atau klik box centang di baris order yang ingin anda proses dalam jumlah banyak, anda bisa melakukan: Create Pick List, Create Package, Mark as Ready to Ship, Print Shipping Label, Print pick list, Print pack list, Cancel sales.

![](https://lh3.googleusercontent.com/KoWu3XWsT5x7aIb8E8AgqC\_KHICPBEkmB4HCXZ1nra98xRD6vgbLtkitTc6ZhDr\_yIJ0faLa7R\_AHJKq9ou5cigQvDE6sqepZWRHisXCuvUApxQq-jmYQ9qA4wlvT9cQP3X8iA)

### Delivery SLA

Sisa waktu untuk di kirim sebelum di auto-cancelled oleh marketplace.

![](../../.gitbook/assets/Screenshot\_24.png)

### Jasa Kirim / Kurir

Apabila belum menyesuaikan dan melakukan pengaturan informasi jasa kirim di marketplace, maka ketika akan memproses order di Forstok akan tampil tanda (-) yang menandakan bahwa informasi kurir belum dilengkapi.

![](../../.gitbook/assets/Screenshot\_23.png)
