<div align="center">
   <h1>Final Project Fullstack Web dan Android C14</h1>
</div>

<div>
<p>
    Final project ini ditujukan untuk mengasah kemampuan
    pengembangan, dan mengaplikasikan pengetahuan yang telah
    dipelajari secara keseluruhan mulai dari chapter 0 - 8.
</p>

**Tema** : E-Flight Ticket Platform (Benchmark dari Garuda Indonesia)
<br>

**Nama Aplikasi** : Lef.id (Let's Flight Indonesia)
<br>

**Deskripsi** : Platform ini merupakan tempat beli dan booking tiket penerbangan secara online, baik one way (sekali penerbangan)
dan round trip (pulang pergi). Platform ini membuka dan menyediakan berbagai jenis penerbangan domestik dan
mancanegara. Flow / alur platform dibebaskan berdasarkan kreasi tim final project.
Terdapat dua peran User yaitu berperan sebagai admin dan login sebagai buyer. Buyer dapat mengirimkan dan
menerima bukti hasil transaksi melalui platform ini.
<br>

**Requirement & Submit Idea Android** 
<br>

- Design : Human Interface Guidelines Android
- Design Pattern : MVVM
- Component : Custom
- Testing : Unit testing
- Output : Package Aplikasi (.apk atau .aab)

***MVP***
|     MVP (Minimum Viable Product)    |     Status   |
| :--------- |:--------    |
| Registrasi (email & password) | ***Completed*** |
| Login dan logout | ***Completed*** |
| Implementasi in app notification (notif lonceng) | ***Completed*** |
| Profile detail (foto, no. Hp, alamat tinggal) | ***Completed*** |
| Transaksi history (sebagai buyer) | ***Completed*** |

***Role Buyer***
|     Requirement    |     Status   |
| :--------- |:--------    |
| Dua kategori pemberangkatan: One-Way dan Round Trip (pulang-pergi) | ***Completed*** |
| Tujuan pemberangkatan (From dan To) | ***Completed*** |
| Waktu pemberangkatan, dan waktu pulang (jika memilih round trip) | ***Completed*** |
| Listing airport (Nama airport, kode negara, dan lokasi) | ***Completed*** |
| Wishlist user di data lokal |  ***Completed*** |

***Role Admin***
|     Requirement    |     Status   |
| :--------- |:--------    |
| Admin punya page sendiri (List customer yang booking, membeli tiket, jadwal pemberangkatan, histori pembayaran) | ***Completed*** |
| Admin bisa CRUD item listing (gambar, deskripsi, harga lokasi) | ***Completed*** |
| Item dibuat 2 kategori: pulang pergi, satu arah | ***Completed*** |

***Tambahkan fitur dengan ketentuan dan flow berikut:***
|     Requirement    |     Status   |
| :--------- |:--------    |
| Menerapkan architecture pattern MVVM. | ***Completed*** |
| Dapat mengimplementasikan offline first (menyimpan data) agar dapat menampilkan data sementara ketika device sedang offline. | ***Completed*** |
| Menggunakan Room untuk menyimpan data ke local database. | ***Completed*** |
| Menerapkan data store / shared preferences untuk penyimpanan key-value. | ***Completed*** |
| Menerapkan coroutine/rxjava untuk background process. | ***Completed*** |
| Menambahkan testing minimal satu test case. | ***Completed*** |
| Menerapkan Dependency Injection Dagger/Koin. | ***Completed*** |
| Menggunakan API yang disediakan oleh anggota dari student Back End. | ***Completed*** |
| Menggunakan Retrofit | ***Completed*** |
| Menggunakan salah satu fitur Firebase contoh crashlytics | ***Completed*** |

***Additional Feature***
|     Requirement    |     Status   |   Keterangan   |
| :--------- |:--------    |:--------    |
| Menggunakan fitur push notification | ***Completed*** | Push Notif ketika User berhasil melakukan booking dan pembayaran |
| Fitur biometric untuk login (UI dibebaskan) | ***Not Completed*** |  |
| Menggunakan fitur kamera | ***Completed*** | User dapat mengganti Foto Profile melalui kamera |
| Menggunakan navigation component | ***Completed*** | Semua perpindahan fragment menggunakan navigation component |
| Motion | ***Completed*** | Motion layout pada dashboard admin |
| Swipe Touch |  ***Completed*** | Buyer dapat melakukan delete pada wishlist dengan swipe ke kanan |
| Swipe Touch |  ***Completed*** | Admin dapat melakukan delete pada item tiket, airport, airplane, company, dan transaksi dengan swipe ke kanan |
| Alert Dialog |  ***Completed*** | Alert Dialog muncul ketika user melakukan swipe untuk menghapus item |
| Filter Transaksi |   ***Completed*** | Buyer dan Admin dapat melakukan filter success, pending, dan canceled pada transaksi |
| FilterResults |  ***Completed*** | Buyer dapat melakukan search kota/kode airport dengan mengetik pada editText saat melakukan pencarian tiket |
| Cancel Transaksi |  ***Completed*** | Setelah berhasil melakukan booking, buyer dapat lanjut melakukan pembayaran ataupun cancel |

<br>

</div>

