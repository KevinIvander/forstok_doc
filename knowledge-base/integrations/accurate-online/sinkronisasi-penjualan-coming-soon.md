# Sinkronisasi Penjualan (coming soon)



{% hint style="info" %}
Pastikan sebelum melakukan sinkronisasi penjualan; CoA, dan detail amount/rincian penjualan pada Accurate Settings telah di-mapping agar data order yang masuk ke Forstok dapat dikirimkan dengan sesuai ke Accurate
{% endhint %}

Data penjualan yang dikirimkan dari Marketplace --> Forstok, akan dikirimkan ke Accurate melalui fitur **Invoice**, panduan penggunaan fitur **Invoice**:

{% content-ref url="../../sales-invoices/invoice-overview.md" %}
[invoice-overview.md](../../sales-invoices/invoice-overview.md)
{% endcontent-ref %}

Berikut adalah alur sinkronisasi penjualan dari **Marketplace --> Forstok --> Accurate**:

1. Order masuk dari Marketplace --> Forstok, dan secara otomatis create invoice pada status order yang telah ditentukan:

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Invoice auto create pada status invoice 'Unpaid' di Forstok</p></figcaption></figure>

2. Auto create invoice di Forstok akan auto create sales invoice/faktur penjualan di Accurate:

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

3. Setelah invoice terbuat di Forstok dan di Accurate, **create payment receive** di Forstok untuk auto create sales receipt/penerimaan penjualan di Accurate dan akan mengupdate status sales invoice/faktur penjualan di Accurate menjadi **paid**.&#x20;
4. Berikut panduan create payment receive:

{% content-ref url="../../payment-receive/" %}
[payment-receive](../../payment-receive/)
{% endcontent-ref %}

<figure><img src="../../../.gitbook/assets/Screenshot 2023-02-02 123720.jpg" alt=""><figcaption><p>Detail amount ketika status order sudah Completed di Forstok</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Screenshot 2023-02-02 123945.jpg" alt=""><figcaption><p>Detail amount yang tertera di Accurate setelah dilakukan create payment receive di Forstok<br>(klik Invoice --> Informasi Diskon --> arahkan kursor dan scroll tabel Akun Diskon untuk melihat seluruh rincian amount yang dikirimkan dari Forstok ke Accurate untuk invoice tersebut)</p></figcaption></figure>

5. Setelah melakukan create payment receive, data amount yang tertera di Forstok, akan dikirimkan ke Accurate dan bisa dilihat rinciannya seperti gambar di atas.&#x20;
