# FAQ - Inventory

## Apa bedanya Qty on hand, Qty Reserved, Qty Available?

![](../../.gitbook/assets/qty-type-in-forstok.png)

### **Cara perhitungan quantity**  

Qty on Hand - Reserved Qty = Available Qty

* **Qty on Hand**: Jumlah item fisik di gudang
* **Qty Reserved:** Jumlah item ditahan yang belum diproses untuk suatu order
* **Qty Available:** Jumlah sisa item yang bisa dibeli.

{% hint style="danger" %}
Jika system anda hanya mempunyai satu tipe stok seperti di Shopify, Tokopedia, Shopee, POS system, Qty tersebut adalah **Qty available**. 

**Scenario:** Qty fisik digudang = **10**. Terjadi order qty **2 tetapi belum di proses**, secara system qty langsung berkurang jadi **8.** Apabila anda melakukan stock opnam digudang, secara qty fisik masih = **10.** Jika anda update stock menjadi **10** dan order yang belum di proces tadi dibatalkan oleh customer karena tidak jadi bayar atau berubah pikiran, maka **Order Qty 2** akan di balikan ke system secara otomatis. Qty baru anda menjadi **12** sedangkan qty fisik digudang = **10.**

Tapi ****jika anda mengunakan inventory system seperti Forstok, anda hanya perlu update ke Qty on Hand sesuai jumlah item fisik digudang. 
{% endhint %}







