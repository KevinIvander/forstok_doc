# Pesanan penjualan ke Faktur \(Chart of Accounting Mapping\)

Catatan: Chart of Account di Jurnal diperlukan untuk menandai faktur sebagai lunas

a. Buat COA di Jurnal

Login ke Jurnal dulu. Buat Chart of Account \(COA\) per marketplaces 

[https://my.jurnal.id/registers/new](https://my.jurnal.id/registers/new)

![](https://lh5.googleusercontent.com/hUPNhprIKNLncRXSsH35wEv_bZw5n1ge6t-Hi8PUe7KbuaYabh-BYWoVzgOtNjtszCea_w21_7NbsmcJwndmjbAhyK24VSG-CFxuHhznxBu47iGWKpb-aNrxjATz_HKF8ddBzn7amW4)

b. Mappingkan COA di Forstok

Login ke Forstok dulu. Memetakan COA Jurnal ke setiap sales channel di Forstok.  

[https://www.forstok.com/jurnal-settings](https://app.forstok.com/dashboard/channels/settings/1018/edit)

![](https://lh5.googleusercontent.com/dYzy6xRSoWJmP5Px-6uGJAHK9JbTbNyp14igBkmIuL_OJOriruRJh9dN0hFYnJTw57M57d0ZL8hZW0Ysw9ft7pg53juNY8MMhVPXYsIfmmyz4LZ8I4LAz1D-z4YziSeDOsclvsknfCU)

c. Faktur akan dibuat di Jurnal saat pesanan dikirim. 

Faktur di Jurnal akan dibuat dan ditandai sebagai dibayar secara otomatis. Pembayaran yang diterima akan dipetakan berdasarkan COA.

![](https://lh3.googleusercontent.com/iT39ykRJfb7eszqGdjIy01zf_cWdcYUev7TnJXtVRaIvXxkq0lx0I1ujLFi4luMiAy1bY3he5zya8CsAZrDf5M36n0-G3_vBlu1-1FCPskUe1oTNGvSXvfdiCRKKgu_q2W_Ms6GMEZo)

Contoh Faktur Penjualan dari orderan Marketplace:

![](https://lh5.googleusercontent.com/xPzN1XXoK649YLGTyungNBa3LDkMMosU73XJ8QhNOjfhWnuduEy2YT3cY9LHxkKT1HTbVljqUT93-lBAtjnxYiufdasRV3yNTBXpj6IczEbhXLqnAzvTLqhNVv7C0FtXjE8mayAaO3k)



**Status orderan yang akan masuk ke Jurnal**

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Forstok</b>
      </th>
      <th style="text-align:left">Jurnal</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Pending Payment</td>
      <td style="text-align:left">
        <p>Tidak masuk ke Jurnal. Karena</p>
        <p>buyer pasti sudah bayar atau tidak</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Open</td>
      <td style="text-align:left">Open</td>
    </tr>
    <tr>
      <td style="text-align:left">Printed</td>
      <td style="text-align:left">Open</td>
    </tr>
    <tr>
      <td style="text-align:left">Ready to Ship</td>
      <td style="text-align:left">Paid</td>
    </tr>
    <tr>
      <td style="text-align:left">Shipped</td>
      <td style="text-align:left">Paid</td>
    </tr>
    <tr>
      <td style="text-align:left">Delivered</td>
      <td style="text-align:left">Paid</td>
    </tr>
  </tbody>
</table>

