# FAQ - Accurate Online

### Bagaimana proses / flow create sales return?

Saat ini untuk create sales return di order V2 belum di handle di Forstok dan juga di accurate. Sehingga untuk flownya AP - create sales return di Accurate Online, kemudian adjust stok di Accurate Online - Forstok.

### Berapa rate limit update stok per sku dari jurnal ke forstok dan accurate ke forstok?

* Saat ini belum ada rate limit nya, namun dari accurate setiap melakukan adjust stock akan mengirimkan webhook.
* Sedangkan untuk AOL setiap saat update stok, harus klik tombol pada awal integrasi AOL ke Forstok.
* Sedangkan untuk Jurnal setiap saat update stok , harus klik tombol sync dikarenakan ada delay sync. Disarankan sebaiknya di update di kedua platform (karena saat ini Jurnal belum menyediakan webhook).

### Jika pembuatan bundle di AOL / Virtual Bundling dengan skenario, Paket Hemat terdiri dari SKU A, B, C. Kondisinya Paket Hemat tersebut tidak memiliki stok di AOL, bagaimana implementasi di Forstok?

Jika ada skenario seperti ini, dimana terdapat order bundle di forstok dan mengirim ke Accurate, untuk proses / flownya adalah Forstok akan mengirimkan ke Accurate SKU Bundle dan SKU Detail Bundle nya.

{% hint style="info" %}
**Note :** Price anakan bundle tidak dikirim, namun price bundle dikirim.
{% endhint %}

<figure><img src="../../.gitbook/assets/acc bundle.png" alt=""><figcaption><p><mark style="color:blue;">*** Di Accurate sudah memiliki type product “Grup”, dan saat ini sedang di check skenario nya</mark></p></figcaption></figure>

### Apakah satu akun Forstok bisa ke multi akun Accurate?

Tidak bisa.

### Apakah multi akun Forstok bisa ke satu database Accurate?

Tidak bisa, melainkan harus 1 akun forstok - 1 akun database AOL.

{% hint style="info" %}
**Note : 1 akun Forstok - 1 akun AOL (Limitasi credential dari AOL waktu update token**
{% endhint %}

### Bagaimanakah flow cut off pada saat integrasi? Apakah mengikuti rules order dari MP ke Forstok?

Order hanya akan sync ke Forstok setelah di integrasi, tidak berlaku backdate (sebelum integrasi).
