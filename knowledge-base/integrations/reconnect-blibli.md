# Reconnect Blibli

API Blibli ada reset connection jika ada perubahan password, Expired API atau terhubung dengan sistem lain maka API Blibli jadi non aktif. Supaya API connection Blibli terhubung kemballi harap Anda mengaktifkan kembali API Forstok dan Blibli dari seller center Blibli dan Forstok.

Untuk reconnect marketplace ada 2 cara:\
1\. Manual reconnect dari menu integration - settings - reconnect

2\. Dari pop-up yang muncul pada dashboard Forstok

Berikut step by step reconnect 2 cara tersebut:

**A. Manual reconnect dari menu integration - settings - reconnect**

1 Pilih integrations - pilih settings pada channel yang akan reconnect API

![](<../../.gitbook/assets/image (441) (1).png>)

2\. Pilih update channel\


![](<../../.gitbook/assets/image (442) (1).png>)

3\. Input beberapa required berikut yang bisa di dapat dari seller center Blibli

MTA Username (Email): _Email log in seller center Anda_\
API Seller Key: _copy paste yang di dapat dari seller center_\
Merchant ID: _copy paste yang di dapat dari seller center_

![](<../../.gitbook/assets/WhatsApp Image 2022-02-15 at 16.49.11.jpeg>)

Untuk mendapatkan Email, API Seller Key dan Merchant ID:

* Log in terlebih dahulu ke seller center Blibli [https://seller.blibli.com/MTA/store-info/store-info](https://seller.blibli.com/MTA/store-info/store-info). Kita perlu set up API terlebih dahulu. Pada kanan atas pilih **Pengaturan Seller API**

![Pada Kata sandi API klik Buat . ](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48066775314/original/HUAtQ\_zL9xirsYbz-obm0lI-ncXyuq16Cw.png?1603734604)

* Untuk Kata sandi khusus silahkan diisi sesuai dengan yang ada di seller center.

![](<../../.gitbook/assets/WhatsApp Image 2022-02-15 at 16.09.22.jpeg>)

1. Kode toko = Merchant ID
2. Kata sandi API= Klik Buat Ulang/Regenerate, kemudian copy paste kata sandi API yang baru dari seller center Blibli ke Forstok
3. Pastikan Hubungkan API Klien sudah terhubung dengan ID API Klien FOrstok, yaitu:\
   mta-api-ptforstokteknologiindonesia-9ddf9

![](<../../.gitbook/assets/image (447) (1) (1).png>)

4\. Jika semua sudah di input, lalu pilih save. Harap info tim Forstok melalui ticketing atau WA Group jika sudah di reconnect.\


![](<../../.gitbook/assets/image (450) (1) (1).png>)

**B. Dari pop-up yang muncul pada dashboard Forstok**\
\
1\. Pastikan API Blibli masih tersambung dengan Forstok. Di seller center Blibli.\
Bisa di lihat dari Dropdown sebelah kanan atas - pilih seller API Manager

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48087352720/original/LbA4f7R-UMAA6T7Qs\_aWeJfhkgNvDWFzrA.png?1613468465)

{% hint style="info" %}
Pastikan anda klik regenerate/buat ulang API, kemudian copy paste dari seller center Blibli ke Forstok
{% endhint %}

2\. Klik Reconnect

![](<../../.gitbook/assets/image (298).png>)

3\. Input email dan password Blibli, lalu klik save. Setelah tidak ada pop up reconnect. Maka Blibli berjasil terconnect kembali.\


![](<../../.gitbook/assets/image (297).png>)

{% hint style="info" %}
Jika sudah di reconnect harap konfirmasi kembali tim Forstok terkait melalui Grup WhatsApp atau ticketing.
{% endhint %}
