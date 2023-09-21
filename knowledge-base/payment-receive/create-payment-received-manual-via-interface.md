# Create Payment Received (API via Interface)

### Single Payment Received (Interface)

<figure><img src="../../.gitbook/assets/Payment Received - select.png" alt=""><figcaption><p>Click "Payment Received</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Payment Received Single.png" alt=""><figcaption><p>Single Payment Received</p></figcaption></figure>

### Bulk Payment Received (Interface)



Fitur ini berguna untuk Anda dapat melihat rincian pengurangan maupun penambahan dari Order tersebut langsung secara otomatis terisi Amountnya yang didapatkan dari masing-masing _Channel/Marketplace_. Untuk menggunakan fitur ini, pastikan Anda sudah menyalakan _Invoice_, karena pembayaran yang terima akan berelasi dengan _Invoice_.

Adapun penjelasan dari masing-masing field di atas sebagai berikut:

* _Sub Total_: Jumlah dari penjumlahan Item
* _Voucher Amount_: Voucher yang dibuat oleh Seller
* _Service Fee_: Biaya Layanan, Biaya Platform, Komisi, Biaya Admin, Biaya Program, dll
* _Platform Rebate_: Cashback dari Marketplace/Channel
* _Shipping Difference_: Pengurangan selisih pengiriman berdasarkan berat sebenarnya.
* _Total_: Sub Total - Voucher Amount - Service Fee + Platform Rebate + Shipping (if non-cashless)
* _Balance Due_: Outstanding invoice amount



**Note:**

* Saat ini _Payment Receive via API_ baru tersedia untuk _marketplace_ **Shopee, Tokopedia, Bukalapak, Lazada, Tiktok** kedepannya akan ditambahkan _channel-channel_ lainnya yang memungkinkan dan apabila menyediakan API tersebut **(Blibli dan Zalora)**.
* _Balance Due_ akan secara otomatis menjadi **“0”** setelah Anda melakukan _Payment Receive_ dan Save data tersebut.
* Shipping Cashless tidak termasuk ke dalam hitungan karena akan dibayarkan secara otomatis oleh _Channel/Marketplace_ ke masing-masing jasa kirim (Anda tidak menerima uang atas _Shipping Cashless_ tersebut).
* Saat Anda melakukan _Payment Receive_, _Amount_ yang ada pada Invoice Detail akan ter-_replace_ secara otomatis mengikuti _Amount_ yang diterima dari API/Input dari Anda.
* Apabila sistem gagal dalam pengambilan _Amount_ dari API, akan secara otomatis menampilkan Form yang dapat Anda isi secara manual.

Setelah membuat Payment Receive, anda bisa melihat [**Activity Log**](../dashboard/introduction-to-dashboard.md) atau [**Payment Received List**](payment-received-list.md) untuk mengetahui Payment Receive yang sudah berhasil.
