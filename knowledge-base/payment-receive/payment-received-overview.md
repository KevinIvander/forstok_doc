# Payment Received Overview

{% hint style="info" %}
Untuk menggunakan fitur 'Payment Received', perlu mengaktifkan fitur faktur terlebih dahulu.[ ](../settings/invoice-settings.md)[Invoice Settings](../sales-invoices/invoice-settings.md)
{% endhint %}

{% hint style="info" %}
Fitur "Payment Received" hanya berfungsi untuk mencatat biaya-biaya. Proses penarikan dana tetap harus dilakukan langsung melalui platform marketplace



Untuk Channel yang sudah menyediakan API finance/ Payout, Amount akan terisi secara otomatis.&#x20;

* Shopee
* Tokopedia
* Bukalapak
* Lazada
* Tiktok
* Zalora
* Blibli (Coming Soon)
{% endhint %}

'Payment Received' atau 'Payout' pada Invoice Forstok adalah fitur pencatatan pembayaran di mana pihak yang berutang (Marketplace atau pelanggan) menyelesaikan jumlah yang tertera dalam faktur melalui API. Hal ini memungkinkan pengguna untuk menghindari pengunduhan file Excel dari Marketplace, mengeliminasi proses manual

Payment Received' untuk Invoice dari Marketplace dapat dilakukan ketika status pesanan sudah berubah menjadi 'Completed'. Status 'Completed' menandakan bahwa Marketplace telah melakukan pembayaran ke dompet penjual, sehingga Forstok dapat menarik jumlah yang diterima melalui API.

'Payment Received' dapat dilakukan pada H+1 pukul 00.00. Artinya, jika pesanan selesai pada pukul 14:00 hari ini, pembayaran dapat dikonfirmasi atau invoice dapat diubah menjadi status 'Paid' pada hari berikutnya setelah pukul 00:00.

**Biaya-biaya dari setiap Marketplace dapat bervariasi. Forstok telah melakukan pemetaan yang terperinci dalam tabel di bawah ini**

{% embed url="https://docs.google.com/spreadsheets/d/1QkLWBQNKZ-S9u54nEv0TaT4Hx7c0VY3yf6JEt37skGY/edit#gid=624816466" %}
