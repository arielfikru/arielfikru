#### Use Case Login (FR1)
| Use Case          | Login                                                                                       |
|-------------------|---------------------------------------------------------------------------------------------|
| **Deskripsi**     | Memverifikasi username dan password untuk masuk ke sistem.                                   |
| **Aktor**         | Admin, User                                                                                  |
| **Kondisi Awal**  | User berada di halaman login.                                                                |
| **Kondisi Akhir** | User berhasil login sesuai dengan tingkat akses yang diberikan.                              |
| **Skenario**      | 1. User memasukkan username dan password.<br>2. Sistem memverifikasi username dan password.<br>3. Jika valid, user diarahkan ke dashboard. Jika tidak, tampilkan pesan error. |

| **Aksi Aktor**                                         | **Reaksi Sistem**                                                                     |
|--------------------------------------------------------|---------------------------------------------------------------------------------------|
| 1. User memasukkan username dan password               | 2. Sistem akan memverifikasi username dan password yang dimasukkan.                   |
|                                                        | - Jika invalid, user tidak akan bisa masuk ke sistem dan harus mengulang input.       |
|                                                        | - Jika valid, sistem akan menampilkan halaman sesuai dengan tingkat akses user.       |

#### Use Case Kelola Produk (FR3, FR4, FR5, FR6)
| Use Case          | Kelola Produk                                                                                       |
|-------------------|-----------------------------------------------------------------------------------------------------|
| **Deskripsi**     | Menambah, mengedit, menghapus, dan melihat data produk.                                              |
| **Aktor**         | Admin                                                                                                |
| **Kondisi Awal**  | Admin berada di halaman produk.                                                                     |
| **Kondisi Akhir** | Data produk berhasil dikelola di dalam sistem.                                                      |
| **Skenario**      | 1. Tambah Produk<br> - Admin masuk ke halaman tambah produk.<br> - Admin memasukkan detail produk (nama, harga, deskripsi, kategori, dll).<br> - Admin menekan tombol submit.<br> - Sistem memvalidasi dan merekam data ke dalam database.<br>2. Edit Produk<br> - Admin memilih produk yang akan diubah datanya.<br> - Admin mengubah detail produk.<br> - Admin menekan tombol submit.<br> - Sistem memvalidasi dan merekam data ke dalam database.<br>3. Hapus Produk<br> - Admin memilih produk yang akan dihapus.<br> - Admin menekan tombol hapus.<br> - Sistem menghapus data produk dari database.<br>4. Lihat Produk<br> - Admin membuka halaman produk.<br> - Sistem menampilkan daftar produk dalam bentuk tabel. |

| **Aksi Aktor**                                        | **Reaksi Sistem**                                                                     |
|-------------------------------------------------------|---------------------------------------------------------------------------------------|
| 1. Admin masuk ke halaman tambah produk.              | 2. Sistem menampilkan form tambah produk.                                             |
| 3. Admin memasukkan detail produk (nama, harga, deskripsi, kategori, dll), kemudian submit. | 4. Sistem akan memvalidasi dan merekam data ke dalam database.                        |
| 1. Admin memilih produk yang akan diubah datanya.     | 2. Sistem menampilkan form edit produk.                                               |
| 3. Admin mengubah detail produk, kemudian submit.     | 4. Sistem akan memvalidasi dan merekam data ke dalam database.                        |
| 1. Admin memilih produk yang akan dihapus.            | 2. Sistem menampilkan konfirmasi penghapusan.                                         |
| 3. Admin menekan tombol hapus.                        | 4. Sistem akan menghapus data produk dari database.                                   |
| 1. Admin membuka halaman produk.                      | 2. Sistem menampilkan daftar produk dalam bentuk tabel.                               |

#### Use Case Kelola Kategori (FR7, FR8, FR9, FR10)
| Use Case          | Kelola Kategori                                                                                     |
|-------------------|------------------------------------------------------------------------------------------------------|
| **Deskripsi**     | Menambah, mengedit, menghapus, dan melihat data kategori.                                            |
| **Aktor**         | Admin                                                                                                |
| **Kondisi Awal**  | Admin berada di halaman kategori.                                                                    |
| **Kondisi Akhir** | Data kategori berhasil dikelola di dalam sistem.                                                     |
| **Skenario**      | 1. Tambah Kategori<br> - Admin masuk ke halaman tambah kategori.<br> - Admin memasukkan detail kategori.<br> - Admin menekan tombol submit.<br> - Sistem memvalidasi dan merekam data ke dalam database.<br>2. Edit Kategori<br> - Admin memilih kategori yang akan diubah datanya.<br> - Admin mengubah detail kategori.<br> - Admin menekan tombol submit.<br> - Sistem memvalidasi dan merekam data ke dalam database.<br>3. Hapus Kategori<br> - Admin memilih kategori yang akan dihapus.<br> - Admin menekan tombol hapus.<br> - Sistem menghapus data kategori dari database.<br>4. Lihat Kategori<br> - Admin membuka halaman kategori.<br> - Sistem menampilkan daftar kategori dalam bentuk tabel. |

| **Aksi Aktor**                                       | **Reaksi Sistem**                                                                     |
|------------------------------------------------------|---------------------------------------------------------------------------------------|
| 1. Admin masuk ke halaman tambah kategori.           | 2. Sistem menampilkan form tambah kategori.                                           |
| 3. Admin memasukkan detail kategori, kemudian submit.| 4. Sistem akan memvalidasi dan merekam data ke dalam database.                        |
| 1. Admin memilih kategori yang akan diubah datanya.  | 2. Sistem menampilkan form edit kategori.                                             |
| 3. Admin mengubah detail kategori, kemudian submit.  | 4. Sistem akan memvalidasi dan merekam data ke dalam database.                        |
| 1. Admin memilih kategori yang akan dihapus.         | 2. Sistem menampilkan konfirmasi penghapusan.                                         |
| 3. Admin menekan tombol hapus.                       | 4. Sistem akan menghapus data kategori dari database.                                 |
| 1. Admin membuka halaman kategori.                   | 2. Sistem menampilkan daftar kategori dalam bentuk tabel.                             |

#### Use Case Kelola Profil (FR12)
| Use Case          | Kelola Profil                                                                                       |
|-------------------|-----------------------------------------------------------------------------------------------------|
| **Deskripsi**     | Melihat dan mengubah data profil pengguna.                                                          |
| **Aktor**         | Admin, User                                                                                         |
| **Kondisi Awal**  | Pengguna berada di halaman profil.                                                                  |
| **Kondisi Akhir** | Data profil berhasil diperbarui di dalam sistem.                                                    |
| **Skenario**      | 1. Pengguna melihat profil.<br>2. Pengguna mengubah data profil.<br>3. Pengguna menekan tombol submit.<br>4. Sistem memvalidasi dan merekam perubahan data ke dalam database. |

| **Aksi Aktor**                                       | **Reaksi Sistem**                                                                     |
|------------------------------------------------------|---------------------------------------------------------------------------------------|
| 1. Pengguna melihat profil.                          | 2. Sistem menampilkan form profil dengan data pengguna saat ini.                      |
| 3. Pengguna mengubah data profil, kemudian submit.   | 4. Sistem akan memvalidasi dan merekam perubahan data ke dalam database.              |

---
