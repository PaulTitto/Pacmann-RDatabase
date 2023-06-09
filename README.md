# Used Cars-Management-System
[All about Design Database Used Cars ](https://medium.com/@tittoft/practical-sql-designing-and-creating-a-relational-database-used-cars-bd644a1aba44)

# Database Specification:
* Purpose
* Business Rules
* Design Requirements
* Design Decisions
* ERD diagram


## Purpose
membangun relational database untuk sebuah website yang menawarkan penjualan mobil bekas. Gambaran umum tentang project ini adalah siapa saja dapat menawarkan produknya (mobil bekas) dalam bentuk iklan dan calon pembeli dapat melakukan pencarian berdasarkan beberapa kategori.


## Business Rules

* Setiap user aplikasi dapat menawarkan lebih dari satu produk mobil bekasnya.
* Sebelum menjual produk mobil, user harus melengkapi data dirinya terlebih dahulu, seperti nama, kontak, dan domisili lokasi.
* User menawarkan produknya melalui iklan yang akan ditampilkan oleh website.
* Iklan ini berisikan judul, detail informasi produk yang ditawarkan, serta kontak penjual.
* Beberapa informasi yang harus ditulis dalam iklan adalah sebagai berikut
 > - merek mobil: Toyota, Daihatsu, Honda, dll
 > - Model: Toyota Camry, Toyota Corolla Altis, Toyota Vios,Toyota Camry Hybrid, dll
 > - Jenis body mobil: MPV, SUV, Van, Sedan, Hatchback, dll
 > - Tipe mobil: manual atau automatic
 > - Tahun pembuatan mobil: 2005, 2010, 2011, 2020
Deskripsi lain, seperti warna, jarak yang telah ditempuh, dsb, boleh ditambahkan sesuai
kebutuhan.
* Setiap user bisa mencari mobil yg ditawarkan berdasarkan lokasi user penjual, merk mobil, dan jenis body mobil.
* Jika calon pembeli tertarik terhadap sebuah mobil, ia dapat menawar (bid) harga produk jika penjual mengizinkan fitur tawar.
* Transaksi pembelian dilakukan di luar aplikasi sehingga tidak dalam scope project

## Design Requirements:
* Mission Statement
* Creating Table
* Determine Table Relationships
* Determain Business Rules
* Implementing a Relational Database


## ER Diagram:

![](https://github.com/PaulTitto/Pacmann-RDatabase/blob/main/ERD/ERD.png)
