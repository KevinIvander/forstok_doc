# Invoice List

<figure><img src="../../.gitbook/assets/hj (1).png" alt=""><figcaption></figcaption></figure>

Pada halaman _Invoice_, Anda dapat melihat seluruh _Invoice_ yang telah terbuat secara otomatis. Anda dapat dengan mudah melakukan filter berdasarkan status _Invoice_ tersebut menggunakan tab-tab yang ada (Seperti halaman Sales Order). Terdapat kolom-kolom dengan penjelasan sebagai berikut:

* Store = Nama store dengan logo Channel yang berelasi dengan Invoice tersebut
* Invoice ID = ID dari Invoice tersebut
* Status = Status pada Invoice tersebut, seperti:
  * Unpaid = Belum terbayarkan
  * Overdue = Telah melewati batas pembayaran
  * Paid = Invoice telah terbayarkan
  * Voided = Invoice dianggap batal
  * Written Off = Invoice dianggap lunas
* Amount = Amount dari Invoice tersebut berdasarkan Sales Order
* Outstanding = Amount dari Invoice yang belum terbayarkan
* Order Ref = ID Sales Order yang berelasi dengan Invoice tersebut
* Updated At = Tanggal dan waktu Invoice tersebut terbarukan
* Actions = Actions yang dapat Anda lakukan terhadap Invoice tersebut:
  * Payment Receive = Mendapatkan Fixed Amount untuk melakukan update terhadap Amount yang ada pada Invoice tersebut menggunakan API atau Manual Input
  * Mark as Void = Membuat Invoice tersebut menjadi batal
  * Mark as Written Off = Membuat Invoice tersebut dianggap lunas
  * Print Invoice = Melakukan Print terhadap Invoice tersebut.

Di Invoice list Anda juga dapat melakukan pencarian menggunakan Invoice ID, Sales Order ID, Channel Order ID, dan Customer Name (Yang tidak termasking). Selain itu, Anda juga dapat melakukan Filter berdasarkan Store yang Anda miliki beserta Filter berdasarkan Warehouse. Serta, Anda dapat melakukan sorting berdasarkan urutan terbaru dan terlama.
