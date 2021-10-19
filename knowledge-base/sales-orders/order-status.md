# Order Status

{% hint style="warning" %}
## Forstok Order Status

**Pending Payment**:  Sales order yang belum dibayar oleh pembeli. Seller tidak bisa memproses orderanya. Setelah pembeli membayar, status order akan berubah jadi **Open** secara otomatis.

**Pending Courier: **Sales order (Shopee Only) yang couriernya belum ditentukan oleh Marketplace. Seller belum bisa memproses orderanya. Setelah marketplace menentukan courier nya, status order akan berubah menjadi **Open** secara otomatis.

**Open:** Sales order baru yang bisa di process. Next actions: Create picklist, Create package atau update order status ke "Mark as Ready to Ship" untuk ambil AWB informasi.&#x20;

**Picked**: Sales order yang produknya telah diambil dari rak didalam gudang. Next action: Create package

**Packed**: Sales orders yang produknya telah di packaging. &#x20;

**Ready to Ship: **Sales order yang sudah siap dikirim atau tunggu diambil oleh courier.&#x20;

**Ready to Print: **AWB/nomor resi sudah tersimpan pada Forstok. Shipping Label dapat diprint.

**Printed: ** Status akan berubah menjadi **Printed **jika shipping label sudah diprint.

**Shipped: **Status berubah menjadi **Shipped **secara otomatis jika** **paket telah diambil oleh courier. &#x20;

**Delivered: **Status berubah menjadi **Delivered **secara** **otomatis jika paket telah diterima oleh customer.

**Completed: **Status berubah menjadi **Completed **secara otomatis jika paket telah diterima oleh customer dan invoice sudah dibayar oleh Marketplace / customer.

**Cancelled: **Status berubah menjadi cancelled jika customer atau seller membatalkan order tersebut

**Returned: **Status berubah menjadi **Returned **jika seller sudah membuat Sales Return dan Confirm received item/konfirmasi barang sudah di terima digudang seller.
{% endhint %}

{% hint style="warning" %}
## Forstok Order Actions

**Mark as Paid: ** Mengganti status pembayaran order dari** **Pending Payment/Belum Dibayar ke Paid/Dibayar secara manual. Action ini hanya muncul khusus Webstore (Shopify, Magento, Woocommerce atau Custom Webstore) melalui pembayaran manual (Bank Transfer)

**Create Picklist**:  Membuat picklist dokumen berisikan daftar produk untuk diambil didalam warehouse untuk memenuhi pesanan. Setelah produk diambil, status order berubah menjadi Picked.

**Create Package: **Membuat package dokument berisikan daftar product untuk dikemas didalam satu order untuk memenuhi pesanan. Setelah produk dikemas, status order berubah menjadi Packed.&#x20;

**Mark as Ready to Ship:** Mengganti status order dari open/packed menjadi Ready to Ship/ Siap dikirim. Action ini sekaligus akan menarik data AWB/nomer resi dari courier yang teringrasi untuk bisa Print Shipping Label.

**Mark as Delivered**:  Mengganti status order dari Shipped / Sudah dikirim ke Delivered / Sudah Diterima** **oleh pembeli. Action ini hanya muncul khusus Webstore (Shopify, Magento, Woocommerce atau Custom Webstore) yang melalui courier manual/non integrated.

**Create Invoice: ** Membuat invoice document berisikan informasi nominal yang harus dibayarkan untuk order tersebut. Invoice yang sudah terbuat dapat dikonfirmasi pembayarannya, edit invoice, atau void/write off invoice tersebut.

**Cancel Order:**  Mengganti status order menjadi Cancelled dan melakukan cancel order pada marketplace juga.

**Create Sales Return:  **Membuat return document berisikan informasi pengembalian barang yang dilakukan oleh buyer. Return yang sudah terbuat dapat dikonfirmasi penerimaan barangnya, edit return, atau delete return. Saat konfirmasi return tersebut, user dapat memilih untuk restock barangnya atau tidak.
{% endhint %}

## Shopee&#x20;

| Forstok Status      | Shopee Status                                 | Actions in Forstok                                                                                                               |
| ------------------- | --------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | Belum bayar                                   | -                                                                                                                                |
| **Pending Courier** | -                                             | -                                                                                                                                |
| **Open**            | <p>Perlu Dikirim / </p><p>Perlu diprocess</p> | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                                             | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                                             | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | <p>Perlu Dikirim / </p><p>Telah diprocess</p> | -                                                                                                                                |
| **Ready to Print**  | -                                             | Print Shipping Label                                                                                                             |
| **Printed**         | -                                             | -                                                                                                                                |
| **Shipped**         | Dikirim                                       | -                                                                                                                                |
| **Delivered**       | -                                             | Create Sales Return                                                                                                              |
| **Completed**       | Selesai                                       | -                                                                                                                                |
| **Cancelled**       | Pembatalan                                    | -                                                                                                                                |
| **Returned**        | Pengembalian                                  | -                                                                                                                                |

## Tokopedia

| Forstok Status      | Tokopedia Status | Action in Forstok                                                                                                                 |
| ------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | -                | -                                                                                                                                 |
| **Pending Courier** | -                | -                                                                                                                                 |
| **Open**            | Pesanan Baru     | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order </p> |
| **Picked**          | -                | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order </p>                                  |
| **Packed**          | -                | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order </p>                                                       |
| **Ready to Ship**   | Siap dikirim     | -                                                                                                                                 |
| **Ready to Print**  | -                | Print Shipping Label                                                                                                              |
| **Printed**         | -                | -                                                                                                                                 |
| **Shipped**         | Dalam pengiriman | -                                                                                                                                 |
| **Delivered**       | Pesanan Selesai  | Create Sales Return                                                                                                               |
| **Cancelled**       | Dibatalkan       | -                                                                                                                                 |
| **Returned**        | -                | -                                                                                                                                 |

## Lazada

| Forstok Status      | Lazada Status            | Action in Forstok                                                                                                                |
| ------------------- | ------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | Belum bayar              | -                                                                                                                                |
| **Pending Courier** | -                        | -                                                                                                                                |
| **Open**            | Untuk Dikemas            | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                        | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                        | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Atur Pengiriman          | -                                                                                                                                |
| **Ready to Print**  | -                        | Print Shipping Label                                                                                                             |
| **Printed**         | -                        | -                                                                                                                                |
| **Shipped**         | Dalam Pengiriman         | -                                                                                                                                |
| **Delivered**       | Diterima                 | Create Sales Return                                                                                                              |
| **Cancelled**       | Dibatalkan               | -                                                                                                                                |
| **Returned**        | Pengembalian Barang/Dana | -                                                                                                                                |

## Blibli

| Forstok Status      | Lazada Status | Action in Forstok                                                                                                                |
| ------------------- | ------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | -             | -                                                                                                                                |
| **Pending Courier** | -             | -                                                                                                                                |
| **Open**            | Baru          | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -             | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | Dalam Proses  | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Dalam Proses  | -                                                                                                                                |
| **Ready to Print**  | -             | Print Shipping Label                                                                                                             |
| **Printed**         | -             | -                                                                                                                                |
| **Shipped**         | Dalam Proses  | -                                                                                                                                |
| **Delivered**       | Delivered     | Create Sales Return                                                                                                              |
| **Cancelled**       | Batal         | -                                                                                                                                |
| **Returned**        | -             | -                                                                                                                                |

## JD.ID

| Forstok Status      | Lazada Status                                      | Action in Forstok                                                                                                                |
| ------------------- | -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | -                                                  | -                                                                                                                                |
| **Pending Courier** | -                                                  | -                                                                                                                                |
| **Open**            | Awaiting Shipment                                  | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                                                  | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                                                  | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Ready Shipment                                     | -                                                                                                                                |
| **Ready to Print**  | -                                                  | Print Shipping Label                                                                                                             |
| **Printed**         | -                                                  | -                                                                                                                                |
| **Shipped**         | Awaiting Acceptance                                | -                                                                                                                                |
| **Delivered**       | Completed                                          | Create Sales Return                                                                                                              |
| **Cancelled**       | Canceled                                           | -                                                                                                                                |
| **Returned**        | <p>Awaiting Refuse Confirmation</p><p>Rejected</p> | -                                                                                                                                |

## Zalora

| Forstok Status      | Lazada Status                         | Action in Forstok                                                                                                                |
| ------------------- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | Pending                               | -                                                                                                                                |
| **Pending Courier** | -                                     | -                                                                                                                                |
| **Open**            | Pending                               | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                                     | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                                     | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Ready to Ship                         | -                                                                                                                                |
| **Ready to Print**  | -                                     | Print Shipping Label                                                                                                             |
| **Printed**         | -                                     | -                                                                                                                                |
| **Shipped**         | Shipped                               | -                                                                                                                                |
| **Delivered**       | Completed                             | Create Sales Return                                                                                                              |
| **Cancelled**       | <p>Canceled</p><p>Delivery Failed</p> | -                                                                                                                                |
| **Returned**        | Returned                              | -                                                                                                                                |

## Bukalapak

| Forstok Status      | Lazada Status     | Action in Forstok                                                                                                                |
| ------------------- | ----------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | -                 | -                                                                                                                                |
| **Pending Courier** | -                 | -                                                                                                                                |
| **Open**            | Dibayar           | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                 | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | Diproses          | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Diproses          | -                                                                                                                                |
| **Ready to Print**  | -                 | Print Shipping Label                                                                                                             |
| **Printed**         | -                 | -                                                                                                                                |
| **Shipped**         | Dikirim           | -                                                                                                                                |
| **Delivered**       | Selesai           | Create Sales Return                                                                                                              |
| **Cancelled**       | Respon Pembatalan | -                                                                                                                                |
| **Returned**        | Dikembalikan      | -                                                                                                                                |

## Zilingo

| Forstok Status      | Lazada Status                                                                      | Action in Forstok                                                                                                                |
| ------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | -                                                                                  | -                                                                                                                                |
| **Pending Courier** | -                                                                                  | -                                                                                                                                |
| **Open**            | Menunggu Konfirmasi                                                                | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                                                                                  | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                                                                                  | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | <p>Menunggu Permintaan Pengambilan</p><p>Pengambilan Pesanan Sudah Dijadwalkan</p> | -                                                                                                                                |
| **Ready to Print**  | -                                                                                  | Print Shipping Label                                                                                                             |
| **Printed**         | -                                                                                  | -                                                                                                                                |
| **Shipped**         | Sedang Transit                                                                     | -                                                                                                                                |
| **Delivered**       | Telah Diterima                                                                     | Create Sales Return                                                                                                              |
| **Cancelled**       | <p>Dibatalkan Oleh Penjual</p><p>Dibatalkan Oleh Pembeli</p>                       | -                                                                                                                                |
| **Returned**        | Canceled by Buyer (Package Returned)                                               | -                                                                                                                                |

## Elevenia

| Forstok Status      | Lazada Status                       | Action in Forstok                                                                                                                |
| ------------------- | ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | Belum Dibayar                       | -                                                                                                                                |
| **Pending Courier** | -                                   | -                                                                                                                                |
| **Open**            | Pesanan Baru                        | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                                   | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                                   | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Perlu Dikirim                       | -                                                                                                                                |
| **Ready to Print**  | -                                   | Print Shipping Label                                                                                                             |
| **Printed**         | -                                   | -                                                                                                                                |
| **Shipped**         | Dalam Pengiriman                    | -                                                                                                                                |
| **Delivered**       | <p>Diterima</p><p>Terkonfirmasi</p> | Create Sales Return                                                                                                              |
| **Cancelled**       | Pembatalan                          | -                                                                                                                                |
| **Returned**        | <p>Pengembalian</p><p>Penukaran</p> | -                                                                                                                                |

## TheFthing

| Forstok Status      | Lazada Status   | Action in Forstok                                                                                                                |
| ------------------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | Belum bayar     | -                                                                                                                                |
| **Pending Courier** | -               | -                                                                                                                                |
| **Open**            | Perlu dikirim   | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -               | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | Perlu diprocess | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Telah diprocess | -                                                                                                                                |
| **Ready to Print**  | -               | Print Shipping Label                                                                                                             |
| **Printed**         | -               | -                                                                                                                                |
| **Shipped**         | -               | -                                                                                                                                |
| **Delivered**       | -               | Create Sales Return                                                                                                              |
| **Cancelled**       | -               | -                                                                                                                                |
| **Returned**        | -               | -                                                                                                                                |

## GrabMart

| Forstok Status      | Lazada Status                                | Action in Forstok                                                                                                                |
| ------------------- | -------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | -                                            | -                                                                                                                                |
| **Pending Courier** | -                                            | -                                                                                                                                |
| **Open**            | Submitted                                    | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                                            | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | Perlu diprocess                              | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | <p>Driver Allocated</p><p>Driver Arrived</p> | -                                                                                                                                |
| **Ready to Print**  | -                                            | Print Shipping Label                                                                                                             |
| **Printed**         | -                                            | -                                                                                                                                |
| **Shipped**         | Collected                                    | -                                                                                                                                |
| **Delivered**       | Delivered                                    | Create Sales Return                                                                                                              |
| **Cancelled**       | <p>Cancelled</p><p>Failed</p>                | -                                                                                                                                |
| **Returned**        | -                                            |                                                                                                                                  |

## Shopify

| Forstok Status      | Lazada Status                 | Action in Forstok                                                                                                                |
| ------------------- | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | Unpaid                        | Mark as Paid (For Bank Transfer)                                                                                                 |
| **Pending Courier** | -                             | -                                                                                                                                |
| **Open**            | Open                          | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                             | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                             | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | -                             | -                                                                                                                                |
| **Ready to Print**  | -                             | Print Shipping Label                                                                                                             |
| **Printed**         | -                             | -                                                                                                                                |
| **Shipped**         | -                             | -                                                                                                                                |
| **Delivered**       | <p>Fulfilled</p><p>Closed</p> | Create Sales Return                                                                                                              |
| **Cancelled**       | -                             | -                                                                                                                                |
| **Returned**        | -                             | -                                                                                                                                |

## Woocommerce

| Forstok Status      | Lazada Status                          | Action in Forstok                                                                                                                |
| ------------------- | -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | Pembayaran Tertunda                    | Mark as Paid (For Bank Transfer)                                                                                                 |
| **Pending Courier** | -                                      | -                                                                                                                                |
| **Open**            | Diproses                               | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -                                      | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | -                                      | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Diproses                               | -                                                                                                                                |
| **Ready to Print**  | -                                      | Print Shipping Label                                                                                                             |
| **Printed**         | -                                      | -                                                                                                                                |
| **Shipped**         | -                                      | -                                                                                                                                |
| **Delivered**       | Selesai                                | Create Sales Return                                                                                                              |
| **Cancelled**       | <p>Cancel Request</p><p>Dibatalkan</p> | -                                                                                                                                |
| **Returned**        | Dana Dikembalikan                      | -                                                                                                                                |

## Magento

| Forstok Status      | Lazada Status   | Action in Forstok                                                                                                                |
| ------------------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Pending payment** | -               | Mark as Paid (For Bank Transfer)                                                                                                 |
| **Pending Courier** | -               | -                                                                                                                                |
| **Open**            | Baru            | <p>Create Picklist (Optional)</p><p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel Order</p> |
| **Picked**          | -               | <p>Create Package</p><p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                  |
| **Packed**          | Dalam proces    | <p>Mark as Ready to Ship</p><p>Create Sales Invoice</p><p>Cancel order</p>                                                       |
| **Ready to Ship**   | Telah diprocess | -                                                                                                                                |
| **Ready to Print**  | -               | Print Shipping Label                                                                                                             |
| **Printed**         | -               | -                                                                                                                                |
| **Shipped**         | -               | -                                                                                                                                |
| **Delivered**       | -               | Create Sales Return                                                                                                              |
| **Cancelled**       | -               | -                                                                                                                                |
| **Returned**        | -               | -                                                                                                                                |
