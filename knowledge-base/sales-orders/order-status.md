# Order Status

{% hint style="info" %}
**Pending Payment**:  Sales order yang belum dibayar oleh pembeli. Seller tidak bisa memproses orderanya. Setelah pembeli membayar, status order akan berubah jadi **Open** secara otomatis.

**Pending Courier:** Sales order \(Shopee Only\) yang couriernya belum ditentukan oleh Marketplace. Seller belum bisa memproses orderanya. Setelah marketplace menentukan courier nya, status order akan berubah menjadi **Open** secara otomatis.

**Open:** Sales order baru yang bisa di process. Next actions: Create picklist document , Create packages document. atau update order status ke "Mark as Ready to Ship" untuk ambil AWB informasi. 

**Picked \(optional\)**: Sales orders yang telah di pickup produknya. Next action: Create package document

**Packed**: Sales orders yang telah di packaging. Beberapa Marketplace 

**Ready to Ship:**

**Ready to Print:**

**Printed:**

**Shipped:**

**Delivered:**

**Completed:**

**Cancelled:**

**Returned:**
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

## Shopee 

<table>
  <thead>
    <tr>
      <th style="text-align:left">Forstok Status</th>
      <th style="text-align:left">Shopee Status</th>
      <th style="text-align:left">Shipping Label</th>
      <th style="text-align:left">Actions in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Belum bayar</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Mark as Paid (Webstore only)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">
        <p>Perlu Dikirim /</p>
        <p>Perlu diprocess</p>
      </td>
      <td style="text-align:left"></td>
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
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
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
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
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
      <td style="text-align:left">Ready to Print</td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dikirim</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Mark as Delivered (Manual AWB only)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Completed</b>
      </td>
      <td style="text-align:left">Selesai</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Pembatalan</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Pengembalian</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
  </tbody>
</table>

## 

