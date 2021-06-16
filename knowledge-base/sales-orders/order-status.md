# Order Status

{% hint style="warning" %}
## Forstok Order Status

**Pending Payment**:  Sales order yang belum dibayar oleh pembeli. Seller tidak bisa memproses orderanya. Setelah pembeli membayar, status order akan berubah jadi **Open** secara otomatis.

**Pending Courier:** Sales order \(Shopee Only\) yang couriernya belum ditentukan oleh Marketplace. Seller belum bisa memproses orderanya. Setelah marketplace menentukan courier nya, status order akan berubah menjadi **Open** secara otomatis.

**Open:** Sales order baru yang bisa di process. Next actions: Create picklist, Create package atau update order status ke "Mark as Ready to Ship" untuk ambil AWB informasi. 

**Picked**: Sales order yang produknya telah diambil dari rak didalam gudang. Next action: Create package

**Packed**: Sales orders yang produknya telah di packaging.  

**Ready to Ship:** Sales order yang sudah siap dikirim atau tunggu diambil oleh courier. 

**Ready to Print:** AWB/nomor resi sudah tersimpan pada Forstok. Shipping Label dapat diprint.

**Printed:**  Status akan berubah menjadi **Printed** jika shipping label sudah diprint.

**Shipped:** Status berubah menjadi **Shipped** secara otomatis jika ****paket telah diambil oleh courier.  

**Delivered:** Status berubah menjadi **Delivered** secara ****otomatis jika paket telah diterima oleh customer.

**Completed:** Status berubah menjadi **Completed** secara otomatis jika paket telah diterima oleh customer dan invoice sudah dibayar oleh Marketplace / customer.

**Cancelled:** Status berubah menjadi cancelled jika customer atau seller membatalkan order tersebut

**Returned:** Status berubah menjadi **Returned** jika seller sudah membuat Sales Return dan Confirm received item/konfirmasi barang sudah di terima digudang seller.
{% endhint %}

{% hint style="warning" %}
## Forstok Order Actions

**Mark as Paid:**  Mengganti status pembayaran order dari ****Pending Payment/Belum Dibayar ke Paid/Dibayar secara manual. Action ini hanya muncul khusus Webstore \(Shopify, Magento, Woocommerce atau Custom Webstore\) melalui pembayaran manual \(Bank Transfer\)

**Create Picklist**:  Membuat picklist dokumen berisikan daftar produk untuk diambil didalam warehouse untuk memenuhi pesanan. Setelah produk diambil, status order berubah menjadi Picked.

**Create Package:** Membuat package dokument berisikan daftar product untuk dikemas didalam satu order untuk memenuhi pesanan. Setelah produk dikemas, status order berubah menjadi Packed. 

**Mark as Ready to Ship:** Mengganti status order dari open/packed menjadi Ready to Ship/ Siap dikirim. Action ini sekaligus akan menarik data AWB/nomer resi dari courier yang teringrasi untuk bisa Print Shipping Label.

**Mark as Delivered**:  Mengganti status order dari Shipped / Sudah dikirim ke Delivered / Sudah Diterima ****oleh pembeli. Action ini hanya muncul khusus Webstore \(Shopify, Magento, Woocommerce atau Custom Webstore\) yang melalui courier manual/non integrated.

**Create Invoice:**  Membuat invoice document berisikan informasi nominal yang harus dibayarkan untuk order tersebut. Invoice yang sudah terbuat dapat dikonfirmasi pembayarannya, edit invoice, atau void/write off invoice tersebut.

**Cancel Order:**  Mengganti status order menjadi Cancelled dan melakukan cancel order pada marketplace juga.

**Create Sales Return:**  Membuat return document berisikan informasi pengembalian barang yang dilakukan oleh buyer. Return yang sudah terbuat dapat dikonfirmasi penerimaan barangnya, edit return, atau delete return. Saat konfirmasi return tersebut, user dapat memilih untuk restock barangnya atau tidak.
{% endhint %}

## Shopee 

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Shopee Status</th>
      <th style="text-align:left">Actions in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Belum bayar</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">
        <p>Perlu Dikirim /</p>
        <p>Perlu diprocess</p>
      </td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">
        <p>Perlu Dikirim /</p>
        <p>Telah diprocess</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dikirim</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Completed</b>
      </td>
      <td style="text-align:left">Selesai</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Pembatalan</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Pengembalian</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Tokopedia

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Tokopedia Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Pesanan Baru</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Siap dikirim</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dalam pengiriman</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Pesanan Selesai</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Dibatalkan</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Lazada

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Belum bayar</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Untuk Dikemas</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Atur Pengiriman</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dalam Pengiriman</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Diterima</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Dibatalkan</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Pengembalian Barang/Dana</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Blibli

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Baru</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">Dalam Proses</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Dalam Proses</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dalam Proses</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Delivered</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Batal</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## JD.ID

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Awaiting Shipment</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Ready Shipment</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Awaiting Acceptance</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Completed</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Canceled</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">
        <p>Awaiting Refuse Confirmation</p>
        <p>Rejected</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Zalora

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Pending</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Pending</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Ready to Ship</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Shipped</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Completed</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">
        <p>Canceled</p>
        <p>Delivery Failed</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Returned</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Bukalapak

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Dibayar</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">Diproses</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Diproses</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dikirim</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Selesai</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Respon Pembatalan</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Dikembalikan</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Zilingo

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Menunggu Konfirmasi</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">
        <p>Menunggu Permintaan Pengambilan</p>
        <p>Pengambilan Pesanan Sudah Dijadwalkan</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Sedang Transit</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Telah Diterima</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">
        <p>Dibatalkan Oleh Penjual</p>
        <p>Dibatalkan Oleh Pembeli</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Canceled by Buyer (Package Returned)</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Elevenia

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Belum Dibayar</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Pesanan Baru</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Perlu Dikirim</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dalam Pengiriman</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">
        <p>Diterima</p>
        <p>Terkonfirmasi</p>
      </td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Pembatalan</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">
        <p>Pengembalian</p>
        <p>Penukaran</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## TheFthing

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Belum bayar</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Perlu dikirim</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">Perlu diprocess</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Telah diprocess</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## GrabMart

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Submitted</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">Perlu diprocess</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">
        <p>Driver Allocated</p>
        <p>Driver Arrived</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Collected</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Delivered</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">
        <p>Cancelled</p>
        <p>Failed</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>

## Shopify

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Unpaid</td>
      <td style="text-align:left">Mark as Paid (For Bank Transfer)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Open</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">
        <p>Fulfilled</p>
        <p>Closed</p>
      </td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Woocommerce

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Pembayaran Tertunda</td>
      <td style="text-align:left">Mark as Paid (For Bank Transfer)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Diproses</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Diproses</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">Selesai</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">
        <p>Cancel Request</p>
        <p>Dibatalkan</p>
      </td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Dana Dikembalikan</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

## Magento

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Lazada Status</th>
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Mark as Paid (For Bank Transfer)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Baru</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel Order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">Dalam proces</td>
      <td style="text-align:left">
        <p>Mark as Ready to Ship</p>
        <p>Create Sales Invoice</p>
        <p>Cancel order</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Telah diprocess</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">-</td>
    </tr>
  </tbody>
</table>

