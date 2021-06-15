# Order Status

{% hint style="info" %}
**Pending Payment**:  Sales order yang belum dibayar oleh pembeli. Seller tidak bisa memproses orderanya. Setelah pembeli membayar, status order akan berubah jadi **Open** secara otomatis.

**Pending Courier:** Sales order \(Shopee Only\) yang couriernya belum ditentukan oleh Marketplace. Seller belum bisa memproses orderanya. Setelah marketplace menentukan courier nya, status order akan berubah menjadi **Open** secara otomatis.

**Open:** Sales order baru yang bisa di process. Next actions: Create picklist document , Create packages document. atau update order status ke "Mark as Ready to Ship" untuk ambil AWB informasi. 

**Picked \(optional\)**: Sales orders yang telah di pickup produknya. Next action: Create package document

**Packed**:

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
      <th style="text-align:left">Action in Forstok</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Pending payment</b>
      </td>
      <td style="text-align:left">Belum bayar</td>
      <td style="text-align:left">Mark as Paid (Webstore only)</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Pending Courier</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Open</b>
      </td>
      <td style="text-align:left">Perlu dikirim</td>
      <td style="text-align:left">
        <p>Create Picklist (Optional)</p>
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Picked</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
        <p>Create Package</p>
        <p>Mark as Ready to Ship</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Packed</b>
      </td>
      <td style="text-align:left">Perlu diprocess</td>
      <td style="text-align:left">Mark as Ready to Ship</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Ship</b>
      </td>
      <td style="text-align:left">Telah diprocess</td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Ready to Print</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Print Shipping Label</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Printed</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Shipped</b>
      </td>
      <td style="text-align:left">Dikirim</td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Delivered</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Create Sales Return</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Completed</b>
      </td>
      <td style="text-align:left">Selesai</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Cancelled</b>
      </td>
      <td style="text-align:left">Pembatalan</td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Returned</b>
      </td>
      <td style="text-align:left">Pengembalian</td>
      <td style="text-align:left">&lt;b&gt;&lt;/b&gt;</td>
    </tr>
  </tbody>
</table>

## Tokopedia

| Forstok Status | Tokopedia Status | Action in Forstok |
| :--- | :--- | :--- |
| **Pending payment** |  |  |
| **Pending Courier** |  | \*\*\*\* |
| **Open** | Pesanan Baru | Create Picklist |
| **Picked** |  | Create Package |
| **Packed** |  | Mark Ready to Ship |
| **Ready to Ship** | Siap dikirim | \*\*\*\* |
| **Ready to Print** |  | Print Shipping Label |
| **Printed** |  |  |
| **Shipped** | Dalam pengiriman | \*\*\*\* |
| **Delivered** | Pesanan Selesai | Create Sales Return |
| **Cancelled** |  | \*\*\*\* |
| **Returned** |  | \*\*\*\* |

## Lazada

| Forstok Status | Lazada Status | Action in Forstok |
| :--- | :--- | :--- |
| **Pending payment** | Belum bayar |  |
| **Pending Courier** |  | \*\*\*\* |
| **Open** | Perlu dikirim | Create Picklist |
| **Picked** |  | Create Package |
| **Packed** | Perlu diprocess | Mark Ready to Ship |
| **Ready to Ship** | Telah diprocess | \*\*\*\* |
| **Ready to Print** |  | Print Shipping Label |
| **Printed** |  |  |
| **Shipped** |  | \*\*\*\* |
| **Delivered** |  | Create Sales Return |
| **Cancelled** |  | \*\*\*\* |
| **Returned** |  | \*\*\*\* |

