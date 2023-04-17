---
description: Optional.
---

# Checklist pre-Onboarding

**Apa itu Kode SKU?**

SKU _(Stock Keeping Unit)_ adalah kombinasi huruf atau angka yang dapat menjadi kode unik untuk identifikasi bagi setiap produck yang di jual di Marketplace. Kode SKU harus unik dan harus dibedakan sampai ke level varian.

![](https://lh3.googleusercontent.com/IBnNGMHW-l2yEIM0mtKbxohi\_\_9ozRp6moCgnv0gy0B7x-Ep5wozCBXt4-QOVWhSjpLzf-4wZ\_Ei78H65enCU8bjNjV0cruaQkoPSEWfAQishharrm-XBeJHND068Yu-fjW6z7tblK4)



**Mengapa Kode SKU penting?**

Forstok menggunakan kode SKU agar setiap pesanan yang masuk dari marketplace ke forstok agar memotong stok dengan sesuai dengan kode sku yang digunakan, dan untuk melakukan update stok di marketplace agar stok di forstok bisa sync dengan stok di marketplace.

{% hint style="danger" %}
Jika kode SKU belum disesuaikan di seluruh marketplace maka saat import produk ke Forstok, sistem forstok akan membuat kode sku secara otomatis yang berbeda walaupun masih item yang sama. Hal ini terjadi pada sku dengan status 'sku code is empty' dan 'sku code is duplicate'\
\
Contoh sku code is duplicate: produk Celana Merah ukuran XL dan ukuran L masih menggunakan kode sku yang sama (merah123), maka ketika produk diimport ke forstok, celana merah ukuran xl akan menggunakan sku merah123, dan celana merah ukuran L akan menggunakan sku merah123(x123abc)\
\
Contoh sku code is empty: produk kaos hitam ukuran L tidak memiliki kode sku di marketplace, ketika diimport ke forstok, sku akan otomatis terisi dari forstok (kaos0000)
{% endhint %}

**Praktik Terbaik untuk kode SKU**

1. Jadikan mereka unik - Buat kode SKU unik untuk setiap produk inventaris yang Anda jual dan jangan pernah menggunakan kembali kode SKU untuk produk yang tidak Anda jual lagi.
2. Tetap pendek - Kode SKU harus tidak lebih dari sekitar 30 karakter. Jika lebih dari itu mereka menjadi sulit dibaca dan juga mungkin tidak bekerja dengan beberapa sistem manajemen persediaan.&#x20;
3. Jangan pernah gunakan spasi atau karakter khusus - Tetap dengan karakter sederhana yang tidak akan membingungkan orang atau sistem perangkat lunak. Gunakan hanya tanda hubung atau titik sebagai pemisah, dan JANGAN PERNAH menggunakan spasi, garis miring (/ atau \\), “&”, “%”, “?”
4. Jangan hanya menggunakan judul produk - Tinggalkan deskripsi panjang untuk judul produk, bukan kode SKU.
5. Jangan pernah memulai kode SKU Anda dengan nol - Kecuali jika Anda ingin membuat pekerjaan Anda menjadi lebih berat, jangan mulai kode SKU Anda dengan 0. Excel dan perangkat lunak spreadsheet lainnya akan menghapus 0 dan mengacaukan semuanya. Jangan lakukan itu.

**Contoh Kode SKU jika sudah disamakan ke semua marketplace**

Di Shopee

![](<../../.gitbook/assets/image (106).png>)

Di Tokopedia

![](<../../.gitbook/assets/image (245).png>)

{% content-ref url="cara-penginputan-kode-sku-di-marketplace.md" %}
[cara-penginputan-kode-sku-di-marketplace.md](cara-penginputan-kode-sku-di-marketplace.md)
{% endcontent-ref %}

