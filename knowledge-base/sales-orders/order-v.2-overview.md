# Order v.2 Overview (NEW)

## What's new&#x20;

1. **New Interface**: Tab order status, sorting, filter grouping, hide order fulfilled by channel, filter date.
2. **New status:** “Not shipped” menggantikan status “Printed”. Printed berubah jadi order flagging.
3. **2 Steps order Processing:** Open → Create Shipment (Not Shipped) → Mark as Ready to Ship
4. **Fulfill by channel Flag**: Tokocabang, FBL Lazada, FBB Blibli, SBS Shopee, FBJ JD.
5. **Warehouse User permission.:** User warehouse jakarta cuma bisa process order untuk warehouse Jakarta saja.&#x20;
6. **Delivery SLA time:** Deliveri limit waktu per marketplace
7. **WMS App**: Create picklist and package (Enterprise tiers only)

{% hint style="success" %}
Order v1 masih bisa digunakan
{% endhint %}

### New Interface

Access order v.2 melalui dropdown menu.

![](https://lh3.googleusercontent.com/rFSK2lyVGlUo-KxDyTTOZf9-jaz51fxmV-I-e4MDJ1a0Wjh7nRu6wM3NBIUBbE5Pv9Sy4ciWSjiF0oJkvCPcV5q-DenSqoTZZOt3tNeh1akYO8UxRi2aWrY6HyDf8iKjlCKYklJK5Cai)

### New Order Status

|    ORDER V1 STATUS    |                        ORDER V2 STATUS                        |
| :-------------------: | :-----------------------------------------------------------: |
|  **** Pending Payment |                      **** Pending Payment                     |
|          Open         |                              Open                             |
|          N/A          |                      Not PIcked / Picked                      |
|          N/A          |                             Packed                            |
|        Printed        | <p>To Ship / Not Shipped </p><p>(Action: Create Shipment)</p> |
|     Ready to Ship     |                    To Ship / Ready to Ship                    |
|        Shipped        |                            Shipped                            |
|       Delivered       |                           Delivered                           |
|       Cancelled       |                           Cancelled                           |

### **2 steps order processing**

Order v.2 mempunyai 2 steps order processing sesuai sellercenter MP dimana seller bisa menggunakan fitur “Create Shipment” di Forstok untuk Terima Order di toped, create package di Blibli, Lazada, zalora, zilingo&#x20;

Sehingga seller dapat print AWB tanpa trigger Ready to Ship ke channel/marketplace, sehingga paket dapat disiapkan terlebih dahulu sebelum dilakukan pemanggilan kurir (Ready to Ship)

![](https://lh6.googleusercontent.com/gT5CcK\_HafXsuQJR1EfXCqw9Vddre-ep\_9mxZLn3GyJjrVSIOhwXaRV-SKOnX3tLDJDhQwdWBV00Rur2m5yAFXyf4DBG8OGdS2LPaHOtjFBlugpLC68xRhrJAG9zm4ogPbWuOsfRpR60)
