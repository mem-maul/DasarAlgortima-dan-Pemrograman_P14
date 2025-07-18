Program sederhana berbasis teks (command-line) untuk membantu mengelola dan melacak stok barang di toko minuman skala kecil. Aplikasi ini dibuat dengan Python dan dirancang agar mudah digunakan oleh siapa saja, bahkan tanpa latar belakang teknis.

Fitur Utama
🔎 Melihat Stok: Menampilkan seluruh daftar minuman beserta jumlah stoknya saat ini dalam format tabel yang rapi.

➕ Menambah Barang: Menambahkan jenis minuman baru ke dalam daftar inventori.

🔄 Memperbarui Stok: Mencatat penjualan (mengurangi stok) atau penambahan stok baru dengan mudah.

❌ Menghapus Barang: Menghapus data minuman yang sudah tidak dijual lagi.

💾 Penyimpanan Otomatis: Semua perubahan secara otomatis disimpan ke dalam file inventory.json, sehingga data tidak hilang saat program ditutup.

Cara Menjalankan Program
Ikuti langkah-langkah berikut untuk menjalankan aplikasi di komputer Anda.

Prasyarat: Pastikan Anda sudah menginstall Python di komputer Anda.

Simpan File: Simpan kode program dengan nama manajemen_inventori.py.

Buka Terminal:

Windows: Buka Command Prompt atau PowerShell.

macOS/Linux: Buka aplikasi Terminal.

Jalankan Perintah: Arahkan terminal ke folder tempat Anda menyimpan file, lalu ketik perintah berikut dan tekan Enter:

Bash

python manajemen_inventori.py
Aplikasi akan berjalan dan menampilkan menu utama.

Panduan Penggunaan Menu
Saat program berjalan, Anda akan melihat menu utama. Cukup ketik angka pilihan Anda, lalu tekan Enter.

===== Sistem Manajemen Inventori Toko Minuman =====
1. Lihat Semua Stok Barang
2. Tambah Barang Baru
3. Perbarui Stok Barang (Jual/Tambah)
4. Hapus Barang
5. Keluar
Pilih menu (1-5):
1. Melihat Stok Barang 🧐
Gunakan pilihan ini untuk melihat daftar lengkap semua minuman dan jumlah stoknya.

➡️ Cara Pakai: Ketik 1 lalu tekan Enter.

--- STOK BARANG SAAT INI ---
Nama Barang          | Stok
-------------------------------
Aqua 600ml           | 60
Coca-Cola 250ml      | 45
...                  | ...
----------------------------
2. Menambah Barang Baru ➕
Gunakan pilihan ini untuk menambahkan jenis minuman baru ke dalam daftar inventori Anda.

➡️ Cara Pakai: Ketik 2 lalu ikuti petunjuk di layar.

Pilih menu (1-5): 2
Masukkan nama barang baru: Le Minerale 600ml
Masukkan jumlah stok awal untuk 'Le Minerale 600ml': 48
Berhasil! 'Le Minerale 600ml' dengan stok 48 telah ditambahkan.
3. Memperbarui Stok Barang (Jual/Tambah) 🔄
Menu ini adalah yang paling penting untuk operasional harian, yaitu mencatat penjualan atau penambahan stok.

➡️ Cara Pakai: Ketik 3 dan ikuti petunjuk.

💡 Tips Penting:

Untuk mencatat penjualan, gunakan angka negatif. Contoh: -5 jika terjual 5 botol.

Untuk mencatat stok baru, gunakan angka positif. Contoh: 24 jika datang stok baru 24 botol.

Contoh Penjualan:

Pilih menu (1-5): 3
Masukkan nama barang yang akan diperbarui: Coca-Cola 250ml
Stok 'Coca-Cola 250ml' saat ini: 45
Masukkan perubahan stok (contoh: -5 untuk terjual 5, 10 untuk menambah 10): -10
Stok 'Coca-Cola 250ml' berhasil diperbarui menjadi 35.
4. Menghapus Barang ❌
Gunakan pilihan ini untuk menghapus data minuman dari daftar secara permanen.

➡️ Cara Pakai: Ketik 4 dan berikan konfirmasi.

Pilih menu (1-5): 4
Masukkan nama barang yang akan dihapus: Jus Jambu
Apakah Anda yakin ingin menghapus 'Jus Jambu'? (y/n): y
'Jus Jambu' telah dihapus dari inventori.
5. Keluar dan Simpan 👋
Ini adalah cara yang benar untuk menutup program agar semua perubahan tersimpan dengan aman.

➡️ Cara Pakai: Ketik 5 lalu tekan Enter.

Pilih menu (1-5): 5
Terima kasih! Data inventori telah disimpan.
Catatan Penting
File inventory.json: File ini adalah "buku catatan" digital program. File ini dibuat secara otomatis dan berisi semua data stok Anda. JANGAN HAPUS file ini kecuali Anda ingin memulai dari awal.

Menutup Program: Selalu gunakan pilihan menu Nomor 5 untuk keluar. Ini memastikan semua pekerjaan Anda tersimpan dengan baik.
