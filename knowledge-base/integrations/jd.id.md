# JD.ID

![](../../.gitbook/assets/screen-shot-2021-05-31-at-1.13.24-pm.png)

{% hint style="warning" %}
**Penting!**  Sebelum integrasi, pastikan product yang sama di toko/ channel lain mempunyai Kode SKU yang sama. Setelah integration, product akan di import dan terlinking dengan product yang sama mengunakan Kode SKU.
{% endhint %}

## Cara Integrasi JD.ID \(Step-by-step\)

Sebelum integrasi ke JD.ID pastikan toko Anda sudah **Qualified Seller.** Karena JD.ID Open API khusus untuk seller yang sudah Qualified Seller. Jika masih Basic Seller harap mengupgrade Toko Anda atau mendaftar menjadi Qualified Seller.  
****Untuk mendaftar menjadi Qualified Seller bisa dilihat di link berikut:  
****[https://www.jd.id/blog/segera-update-toko-Anda-jadi-qualified-untuk-keuntungan-berlipat\_194.html](https://www.jd.id/blog/segera-update-toko-Anda-jadi-qualified-untuk-keuntungan-berlipat_194.html)  
  
****Setelah Toko Anda sudah terdaftar sebagai Qualified Seller, untuk JD.ID ini Anda harus request API Key terlebih dahulu langsung dari web yang diberikan tim JD.ID. Langkah awal untuk mendapatkan  API JD.ID:

1. Log in seller center JD.ID [https://seller.jd.id](https://seller.jd.id/) . Lalu log in ke toko Anda

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605700/original/0ywhTaNVG6TLxzV859tKmTj7ove2yZNH5g.png?1601870496)

2. Masuk ke link request API JD.ID [http://api.jd.id/](http://api.jd.id/)  
    Pilih Control Panel &gt; Pilih New App

![](../../.gitbook/assets/image%20%2824%29.png)

3. Isi data sesuai yang tertera, lalu Save.  
App name: Nama Toko\_Forstok  
Email: onboarding@forstok.com

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605691/original/KH2xDjdUe-MW3udbrPrNXTAgZWtEi00ong.png?1601870493)

4. Kembali ke Control Center, pilih ‘Manage’

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605693/original/EGLbpBGx85iGrKcCERmaX-oc0jszmLHjGA.png?1601870494)

5. Di Category pilih ‘Seller to JD’

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605694/original/pp5xaF35anUWnbXJnYxso_iNa_TteKV19A.png?1601870495)

6. Pada Not Apply pilih ‘ALL’ lalu SAVE

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605695/original/GsgSJEXOiQ7Reeyro1rcDd0r8Tn5UToYPA.png?1601870495)

7. Setelah request API maka statusnya masih ‘**Waiting Authorize**’. Ini Berarti menunggu pihak JD.ID untuk approval API yang kita request tadi. Estimated 3-5 hari kerja akan di approved oleh pihak JD.ID

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605697/original/zDqkIq9gPdGvxKgHMxHsgrhzP1YVX0_bjA.png?1601870495)

8. Jika API tersebut sudah di approved oleh pihak JD.ID, maka statusnya berubah menjadi ‘**Already Own**’. Dimana API Key bisa di lihat di kolom Key&Token ‘View’ maka muncul detail API Key JD.ID yang siap di integrasikan ke Forstok.

{% hint style="warning" %}
`Approval API bisa 2-7 hari kerja, jika lebih dari 7 hari masih belum approve harap hubungi pic Jd.ID bersangkutan.`
{% endhint %}

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605696/original/qLsll2nGXDmq0k67XmcHkoiJcT964fdikw.png?1601870495)

9. Kembali ke menu integrasi Forstok, silahkan copy paste API Key JD.ID yang sudah approved tadi ke kolom integrasi JD.ID . 

Untuk mendapatkan Shop ID JD.ID, masuk ke seller center JD.ID.   
Pilih My Shop --&gt;Shop Information   
Pada kolom Shop ID copy paste Shop ID tersebut ke kolom Integrasi Forstok.

![](../../.gitbook/assets/image%20%2812%29.png)

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605698/original/J5LeVB3t6eg92zGcfo-DpiG87E_SD238AA.png?1601870495)

  
10. Pada Product Catalog pilih Sync Products from JD.ID -  Lalu pilih Next. Maka JD.ID berhasil integrasi ke Forstok dan sedang proses import produk.

![](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/48062605699/original/-452dMB4bnP2DT9evo998HKgTK0waKdmfA.png?1601870495)



