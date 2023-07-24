# Create Payment Received - (Manual via Excel)

{% hint style="info" %}
Payment receive dilakukan untuk memperbarui status pembayaran dari invoice yang sudah terbuat dan melengkapi rincian nominal/_detail amount_ untuk data invoice yang masih belum tersedia via API, untuk penarikan dana di **marketplace** dilakukan secara langsung di **Seller Center**.
{% endhint %}

Keuntungan dari menggunakan fitur **Payment Receive Forstok**:

1. _Cost Structure_ yang berbeda dari setiap marketplace disamakan di fitur Payment Receive, sehingga memudahkan proses rekonsiliasi;
2. _Flow_ rekonsiliasi lebih sederhana karena data sudah tersedia via API;
3. _**Detail amount**_ yang terinput pada payment receive sudah akurat, karena otomatis terisi sesuai dengan nominal yang masuk pada saldo/dompet penjual;
4. Pengecekan ulang terhadap data tersedia di 1 platform, tanpa perlu menarik data secara manual satu per satu dari marketplace, cukup mengunduh file xls payment receive dari Forstok;
5. Dengan melakukan create _Payment Receive_ dari Forstok, fitur _Reporting - Financial Transactions_ bisa digunakan: [Financial Transactions](../../reports/financial-reports.md)

Bulk payment receive melalui '_**+Payment Receive**_', berikut adalah langkahnya:

<figure><img src="../../../.gitbook/assets/Screenshot 2023-02-06 153516.jpg" alt=""><figcaption></figcaption></figure>

1. Klik '_+Payment Receive_';

<figure><img src="../../../.gitbook/assets/Screenshot 2023-02-06 153641.jpg" alt=""><figcaption></figcaption></figure>

2. Tentukan range date dari invoice yang akan dilakukan create payment receive, pilih store yang akan digenerate via xls, kemudian generate excel

<figure><img src="../../../.gitbook/assets/image (5) (3).png" alt=""><figcaption><p>Catatan: Pop up notification akan muncul apabila create payment receive untuk store yang dipilih sudah tersedia via API.</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Screenshot 2023-02-06 154848.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
1. Penyeragaman _cost structure_ mempermudah proses rekonsiliasi, hal ini dikarenakan marketplace memiliki istillah yang berbeda-beda untuk setiap _cost structure_.&#x20;
2. Payment receive yang masih harus dilakukan manual juga lebih mudah untuk dilakukan, lengkapi kolom (P) sampai kolom (T), setelah file xls diunggah, status invoice akan ter-_update_ menjadi _paid_.
{% endhint %}

3. Review kembali setiap invoice yang akan diproses menjadi Paid dengan cara mengisi kolom detail amount secara manual apabila create payment receive belum tersedia via API

Berikut sample channel payout summary: [https://docs.google.com/spreadsheets/d/1QkLWBQNKZ-S9u54nEv0TaT4Hx7c0VY3yf6JEt37skGY/edit#gid=0](https://docs.google.com/spreadsheets/d/1QkLWBQNKZ-S9u54nEv0TaT4Hx7c0VY3yf6JEt37skGY/edit#gid=0)

<figure><img src="../../../.gitbook/assets/Screenshot 2023-02-06 155110.jpg" alt=""><figcaption></figcaption></figure>

3. Apabila detail amount sudah sesuai: Save file --> Drag & Drop file/browse untuk mengupload file --> Mark as Paid
4. Setelah file xls diunggah, invoice yang sudah terisi _detail amount_nya akan terupdate dari **Unpaid** menjadi **Paid**

<figure><img src="../../../.gitbook/assets/Screenshot 2023-04-11 133541.jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Note:**

* Perubahan pada detail amount hanya akan terupdate pada order dengan status '**Delivered**' dan '**Completed**'
* Channel **Shopee** dan **Tokopedia** harus **Completed** dahulu untuk mendapatkan amount yang benar-benar Fixed.
* Untuk invoice dengan status Paid tetap akan masuk di xls, namun tidak akan mengalami perubahan
{% endhint %}

Setelah membuat Payment Receive, anda bisa melihat [**Activity Log**](../../dashboard/introduction-to-dashboard.md) atau [**Payment Received List**](../payment-received-list.md) untuk mengetahui Payment Receive yang sudah berhasil.
