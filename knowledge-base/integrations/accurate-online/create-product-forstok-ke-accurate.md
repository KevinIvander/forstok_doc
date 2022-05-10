# Create Product (Forstok → Accurate)

1. Click setting “Accurate

<img src="../../../.gitbook/assets/Screen Shot 2022-01-27 at 1.06.34 PM.png" alt="" data-size="original">

2\. Click button “Sync Item (Forstok - Accurate)”

![](<../../../.gitbook/assets/image (443) (1) (1).png>)

### Product mapping&#x20;

| Forstok Master Product | Accurate Product    |
| ---------------------- | ------------------- |
| SKU Seller             | Item Code           |
| Name                   | -                   |
| Category               | -                   |
| Brand                  | -                   |
| Barcode                | UPC / Barcode       |
| Regular Price          | Default Sales Price |
| Cost Price             | Purchase Price      |
| Qty On Hand            | Balance Qty         |
| Weight                 | -                   |
| Height                 | -                   |
| Width                  | -                   |
| Length                 | -                   |
| VAT                    | VAT                 |

{% hint style="warning" %}
1. Forstok hanya create item ke Accurate yang sudah ada di forstok belum ada di Accurate
2. Di Accurate hanya single Variant. Utk multi-variant harus create/upload master product ke Forstok langsung
3. Forstok tidak kirim image to Accurate (Image tidak ada di API Accurate)
{% endhint %}
