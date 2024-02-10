# Payment Received Overview

{% hint style="info" %}
Untuk menggunakan fitur 'Payment Received', perlu mengaktifkan fitur faktur terlebih dahulu.[ ](../settings/invoice-settings.md)[Invoice Settings](../sales-invoices/invoice-settings.md)
{% endhint %}

{% hint style="info" %}
Fitur "Payment Received" hanya berfungsi untuk mencatat biaya-biaya. Proses penarikan dana tetap harus dilakukan langsung melalui platform marketplace.&#x20;



Keuntungan dari menggunakan fitur **Payment Receive Forstok**:

1. _Cost Structure_ yang berbeda dari setiap marketplace disamakan di fitur Payment Receive, sehingga memudahkan proses rekonsiliasi;
2. _Flow_ rekonsiliasi lebih sederhana karena data sudah tersedia via API;
3. _**Detail amount**_ yang terinput pada payment receive sudah akurat, karena otomatis terisi sesuai dengan nominal yang masuk pada saldo/dompet penjual;
4. Pengecekan ulang terhadap data tersedia di 1 platform, tanpa perlu menarik data secara manual satu per satu dari marketplace, cukup mengunduh file xls payment receive dari Forstok;
5. Dengan melakukan create _Payment Receive_ dari Forstok, fitur _Reporting - Financial Transactions_ bisa digunakan: [Financial Transactions](../reports/financial-reports.md)



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

Forstok akan menjadwalkan penarikan data pembayaran setiap hari pada pukul 00:00. Hal ini memungkinkan 'Payment Received' dilakukan pada H+1 pukul 00:00. Dengan kata lain, jika pesanan selesai pada pukul 14:00 hari ini, pembayaran dapat dikonfirmasi atau invoice dapat diubah menjadi status 'Paid' pada hari berikutnya setelah pukul 00:00.&#x20;



{% hint style="info" %}
**Payment Received memiliki 2 jenis tanggal Payment Date**:

1. Payment Date berdasarkan "Channel Payment Date" atau uang yang masuk ke dompet penjual. Ini adalah pengaturan default.
2. Payment Date berdasarkan tanggal saat pengguna melakukan "Payment received" di forstok invoice.

Opsi Auto Paid dapat diaktifkan jika menggunakan pengaturan "Channel Payment Date". Dengan demikian, pengguna tidak perlu secara manual melakukan "Payment received" di faktur forstok. Pembayaran otomatis akan dipicu H+1 setelah pesanan selesai / uang masuk ke dompet penjual.



Pengaturan ini dapat ditemukan di [Invoice Settings](https://app.forstok.com/dashboard/settings/invoices)

Berikut adalah panduan pembuatan Payment Received: [View Here](./)
{% endhint %}



**Biaya-biaya dari setiap Marketplace dapat bervariasi. Forstok telah melakukan pemetaan yang terperinci dalam tabel di bawah ini**

{% embed url="https://docs.google.com/spreadsheets/d/1QkLWBQNKZ-S9u54nEv0TaT4Hx7c0VY3yf6JEt37skGY/edit#gid=624816466" %}
