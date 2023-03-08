# Sync Payout (Forstok -> Accurate)

Setelah sales invoice terbuat di Forstok dan di Accurate, lakukan **create payment receive** di Forstok untuk auto create sales receipt/penerimaan penjualan di Accurate dan kemudian mengupdate status sales invoice/faktur penjualan di Accurate menjadi **paid:**

{% hint style="info" %}
Berikut panduan create payment receive: [View Here](../../payment-receive/)
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption><p>Kami sarankan create payment receive dilakukan di status order 'Completed', hal ini agar nominal yang diupdate sudah fixed.</p></figcaption></figure>

1. Setelah melakukan create payment receive, sales invoice di accurate akan otomatis terupdate menjadi lunas, dan sales receipt akan auto create di accurate:

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Tampilan faktur penjualan/sales invoice setelah create payment receive dari Forstok</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (3).png" alt=""><figcaption><p>Auto-create Sales Receipt/Penerimaan Penjualan setelah create payment receive dari Forstok</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption><p>Detail amount yang tertera di Accurate setelah dilakukan create payment receive di Forstok<br>(klik Invoice di Accurate --> Informasi Diskon --> arahkan kursor dan scroll tabel Akun Diskon untuk melihat seluruh rincian amount yang dikirimkan dari Forstok ke Accurate untuk invoice tersebut)</p></figcaption></figure>

3. Setelah melakukan create payment receive, data amount yang tertera di Forstok, akan dikirimkan ke Accurate dan bisa dilihat rinciannya seperti gambar di atas.&#x20;
