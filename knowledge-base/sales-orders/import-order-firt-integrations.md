# Import Order First Integrations

Saat pertama kita memulai integrasi marketplace ke Forstok, marketplace mempunyai limitasi saat list order yang bisa masuk melalui API. Jadi bukan pertama ada order di marketplace itu juga masuk ke Forstok.  
Misal mulai integrasi marketplace tanggal 5 Januari 2020, karena kentuan polling order yang masuk melalui API untuk pertama integrasi **2 hari yang lalu** maka orderan yg di tarik hanya dari tgl 3 Januari 2020. Karena limitasi API polling order yang disediakan oleh marketplace.

Berikut list Import Order First Connect to Forstok : 

| Channel | Time limitation \(Poling order created\) |
| :--- | :--- |
| Zalora | Setelah 30 hari yang lalu |
| Tokopedia | Setelah 2 hari yang lalu |
| Blibli | Setelah 30 hari yang lalu |
| Lazada | Setelah 4 jam yang lalu |
| JD.ID | Setelah 14 hari |
| Shopee | Setelah 2 jam yang lalu |
| Elevenia | Setelah 30 hari yang lalu |
| Woocommerce | Setelah 14 hari  |
| Shopify | Setelah 30 hari yang lalu |
| Magento | setelah 15 hari  |

