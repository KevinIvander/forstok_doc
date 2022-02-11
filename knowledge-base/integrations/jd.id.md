# JD.ID

![](../../.gitbook/assets/screen-shot-2021-05-31-at-1.13.24-pm.png)

{% hint style="warning" %}
**Penting!**  Sebelum integrasi, pastikan product yang sama di toko/ channel lain mempunyai Kode SKU yang sama. Setelah integration, product akan di import dan terlinking dengan product yang sama mengunakan Kode SKU.
{% endhint %}

## Cara Integrasi JD.ID (Step-by-step)

Sebelum integrasi ke JD.ID pastikan toko Anda sudah **Qualified Seller.** Karena JD.ID Open API khusus untuk seller yang sudah Qualified Seller. Jika masih Basic Seller harap mengupgrade Toko Anda atau mendaftar menjadi Qualified Seller.\
****Untuk mendaftar menjadi Qualified Seller bisa dilihat di link berikut:\
****[https://www.jd.id/blog/segera-update-toko-Anda-jadi-qualified-untuk-keuntungan-berlipat\_194.html](https://www.jd.id/blog/segera-update-toko-Anda-jadi-qualified-untuk-keuntungan-berlipat\_194.html)

{% hint style="warning" %}
1. Log in ke akun JD.ID seller [https://seller.jd.id/](https://seller.jd.id)
2. Log in ke dev console jd.id [https://open-console.jd.id/](https://open-console.jd.id)

Untuk URL Callback menggunakan link berikut : [https://www.forstok.com/dashboard/channels/integrations/jd/setup](https://www.forstok.com/dashboard/channels/integrations/jd/setup)

Video panduan: [https://www.loom.com/share/5440127537684caa9b37aaeb34f9df0e](https://www.loom.com/share/5440127537684caa9b37aaeb34f9df0e)
{% endhint %}



1 Log in ke ke seller center JD.ID [https://seller.jd.id/](https://seller.jd.id) input email dan password Anda.\


![](https://lh3.googleusercontent.com/TFHNnpmnWhw9Ro8bal4tcPv1SHuyjq0\_md8TyHja88PNNuOYNKgxobL2l02Aoa-k9kU25TSTlhf0lJqigsliVr6citzXJ70EuRV8-kXfAF1vox6i\_m3B5dH6mdQAWflqT-mUlIUM) ![](../../.gitbook/assets/1.jpeg)

2\. Log in ke dev console JD.ID menggunakan akses seller center tadi (ini untuk mendapatkan API JD.ID)\


![](https://lh4.googleusercontent.com/OBjmmL034kjAtVQM7CVIWzg0y36O023OZW5M8dAB-nhqiabmmbM3oEXZxZ0cDN3rGYsjrWLHCLPm-89nOOAz12C14\_OV-rOPF9ogyflpvfB\_1FLdc8T\_yxRtWqyD6Yijvkco6Hrc) ![](../../.gitbook/assets/2.jpeg)

3\. Centang input data JD.ID sesuai data yang Anda daftarkan saat Buka Toko, setelah semua terisi lalu pilih Register\


![](https://lh5.googleusercontent.com/Vppkehpv1pV2x3dwRK08aMUNEpWpr4nBdWN3-npgml226BMXa569aMIbxyo8Mnckrz03shggSg0081PRNkttTIeOnKPXKiFi6M86e7kWHLps2B0Dsrue59UX2hgMAsMB13GE42nK) ![](../../.gitbook/assets/3.jpeg)

4\. Pilih create App\


![](../../.gitbook/assets/5.jpeg)

5\. Pada seller to JD.ID buka dropdown

![](https://lh6.googleusercontent.com/-bi4J4u6ZKrJLkszwIIUW5wk0Z8\_iLcWAIyq873UaKqw6wXsgfSFVjZYWc5hiNVx6C1CGrxU0kYBl3FtqQoFk5wUrWhXWQX3eZzxQlxg3Jyh631fz9QLkScj0VP0qdaKQitn0v7k) ![](../../.gitbook/assets/6.jpeg)

6\. Pada normal standard API pilih Create App\


![](https://lh5.googleusercontent.com/M7uaep58Wdz8r2X9DPuqImMxLN0lXsdgEmLc0\_2\_q\_Nq1MyPM\_mJQAayQCzIMNaf\_rXE7FjIIAn\_OFBaX5drccKWNT-1Pf-OsyCdHY4g-W0TB8JcFnHsC8LsOCngXnzprARG0ND2) ![](../../.gitbook/assets/7.jpeg)

7\. Create App pada App Name input Nama Toko Anda di JD.ID

![](<../../.gitbook/assets/image (410).png>)

8\. Pilih publish App

![](https://lh5.googleusercontent.com/fqLjdYHqZmeYdB7-sKbcTQuHO9as1wGY\_7LRvPLkydR-U57oVkYu6PJeRHfNUkXQGb8cIXlm7MtI6agDNJLCTq\_w7Xa\_0UZo3n1drCv\_kBq1x0lLiVQFx60q6hV9JOtKzvHmcO1P) ![](../../.gitbook/assets/8.jpeg)

9\. Pilih App Management\
****

![](https://lh5.googleusercontent.com/HcNoUyJRo3o3ssZtMuf6f7GDWW90gsaOACj34TM256ue43fY4cInRXOX-s9yPd6gHATcR1qbfeG0ohLw85DXxQI0NtvVhK4H6hiCTZywFjZcBHJTZRfOTVfJSdrpjhZgXOdI0e2D) ![](../../.gitbook/assets/9.jpeg)

10\. PIlih App Setting\
Input URL Callback pada \*Callback URL:

[https://www.forstok.com/dashboard/channels/integrations/jd/setup](https://www.forstok.com/dashboard/channels/integrations/jd/setup)

![](https://lh6.googleusercontent.com/IRbJz2M4R5EK7swczSHEq47EUJfUVphx9vpX4TRYS9rs979t8Xag75zrg2cjMdDcTi6kHCA6LndFRayv0SHDXM4Tnt2SyrZQAoZD7WlJzccT5GbmMxIt2P48n983dzsd7XpzSjNj) ![](../../.gitbook/assets/10.jpeg)

11\. Masuk ke akun Forstok Anda, kita mulai integrasikan API JD.ID ke Forstok.\
Pilih integration pada kanan atas, lalu pilih Add Integration. Lalu pilih JD.ID

![](https://lh3.googleusercontent.com/eU0sSGleiF7yTRexdL6G9iU61iVoi874rOHvxivBIHIx432gwjsLKI2uFf5g\_GAiHADEhAyq9Cw3HIes2WJu1YoMzADr9d-WAqRWZxX5NnYwhH3ySN3eyL9rw0xdIgW0zDTNMNM1) ![](../../.gitbook/assets/11.jpeg)

![](<../../.gitbook/assets/image (409).png>)

12\. Input Shop ID, API Key, API Secret yang di dapat dari dev console JD.ID tadi.



Shop ID (dari seller center JD.ID [https://seller.jd.id/](https://seller.jd.id))

![](https://lh6.googleusercontent.com/iZcFGi4Tm6WbNOURHe1L1TtUkacZKp08P4DiBalDxbgy5Q8YZCD-7D7WvLeGjBj5s7ntS-QuSICFkC\_TLoj83VH3D7VXNIwt3D2eQTW69pTuoC1oyLRpwpf8KvzMIQsNXOv9yyY1) ![](../../.gitbook/assets/14.jpeg)

API Key dan API Secret (dari dev console https://open-console.jd.id/)

![](https://lh3.googleusercontent.com/loXZ2V1Gtj76\_hgmAP31MDDiyg6pggzFrKIvhpzMSQOKtBCZhMvcgt9-ChJ-kbkG6\_9cIL9fe\_C4sCRq5sKCecD058QAE0rGfSeDwOylyMp-B2DbunEnKILxzF6ETCWQO\_wLu8aH) ![](../../.gitbook/assets/13.jpeg)

13\. Sudah di pinput semua, klik install

![](../../.gitbook/assets/15.jpeg)

\


14\. Klik Log in\


![](https://lh6.googleusercontent.com/XmWcuZJqA9FrCQU70mQ-KGHWKENpVA50Bigl2hXu5KlAeDn\_IVI9YAf3\_uViQ\_BTTucYqjylvugXf0fuHEKRgaseXZ6YKx4iLIwJ5HE46C0eOy3jxdmgavDpqh3dzkGtSsEe\_Wb0) ![](<../../.gitbook/assets/155 (1).jpeg>)

15\. Pilih Next\
****

![](https://lh6.googleusercontent.com/AeMzspQrycnmZEQCYkCdN3Cjs6HGZevJe3HWSo-Bg3\_x\_w0xtPsXla74jHBeUiB6Ue6Ch0eLM-0RC67IG7T5AB7EE9g\_DwR1HxnHP3GwPrNSISQSiKxukehK5PaNGHNtFiMwCJsd) ![](<../../.gitbook/assets/16 (1).jpeg>)

16\. Klik Finish, Pop up sebelah kanan atas, menginformasikan jika sedang proses import item JD.ID\
****\
****

![](../../.gitbook/assets/19.jpeg)

17\. JD.ID berhasil di integrasikan\
Note:saat awal di integrasikan sync Export masih Off, harap aktifkan/On terlebih dahulu jika JD.ID mulai update stock, listing, update harga dari Forstok\
****

![](https://lh3.googleusercontent.com/u8SknBniwzULnESwMyEQ\_2xlgw\_mk3L2PQszAl13sLTBE1RZFiFfbDQMwzT2aIfEZxodOnkfpdoiHoxrs3NnqiyCNcBXx2EJrmpYDu1zb8TcfrcIrJLsoOmQ9yhZaSyEg40\_DtJu) ![](<../../.gitbook/assets/17 (1).jpeg>)
