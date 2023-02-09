# Payment Receive

Terdapat 3 cara untuk **Create Payment Receive**:\
\
1\. “_Payment Receive via API_” dan “_Payment Receive via Manual_”

<figure><img src="../../.gitbook/assets/image (1) (4).png" alt=""><figcaption></figcaption></figure>

\
2\. Bulk payment receive melalui '_**+Payment Receive**_', berikut adalah langkahnya:

<figure><img src="../../.gitbook/assets/Screenshot 2023-02-06 153516.jpg" alt=""><figcaption></figcaption></figure>

1. Klik '_+Payment Receive_';

<figure><img src="../../.gitbook/assets/Screenshot 2023-02-06 153641.jpg" alt=""><figcaption></figcaption></figure>

2. Tentukan range date dari invoice yang akan dilakukan create payment receive, pilih store yang akan digenerate via xls, kemudian generate excel

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption><p>Catatan: Pop up notification akan muncul apabila create payment receive untuk store yang dipilih sudah tersedia via API.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2023-02-06 154848.jpg" alt=""><figcaption></figcaption></figure>

3. Review kembali setiap invoice yang akan diproses menjadi Paid dengan cara mengisi kolom detail amount secara manual apabila create payment receive belum tersedia via API

Berikut sample channel payout summary: [https://docs.google.com/spreadsheets/d/1QkLWBQNKZ-S9u54nEv0TaT4Hx7c0VY3yf6JEt37skGY/edit#gid=0](https://docs.google.com/spreadsheets/d/1QkLWBQNKZ-S9u54nEv0TaT4Hx7c0VY3yf6JEt37skGY/edit#gid=0)

<figure><img src="../../.gitbook/assets/Screenshot 2023-02-06 155110.jpg" alt=""><figcaption></figcaption></figure>

3. Apabila detail amount sudah sesuai: Save file --> Drag & Drop file/browse untuk mengupload file --> Mark as Paid

**Note:**

* Untuk dapat melakukan Payment Receive, pastikan order tersebut sudah “Delivered” atau “Completed”. Karena di API, amount dapat berubah-berubah.
* Channel **Shopee** dan **Tokopedia** harus **Completed** dahulu untuk mendapatkan amount yang benar-benar Fixed.
