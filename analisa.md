# SAMPLE SOAL
BERDASARKAN RANDOM SOAL DENGAN TEMA KASUS YANG TELAH DITENTUKAN YAITU LOGISTIK

Menu Interaktif: Fungsi ini menampilkan menu interaktif dengan pilihan untuk membuat pesanan baru, memperbarui status pesanan, mendapatkan informasi pesanan, atau keluar dari program.

Pilihan 1 - Create Order: Mengambil input dari pengguna untuk membuat pesanan baru dengan memanggil create_order dari logistics_service dan menampilkan ID pesanan yang baru dibuat.

Pilihan 2 - Update Order Status: Mengambil input dari pengguna untuk order_id dan status baru, memverifikasi validitas status, dan memperbarui status pesanan menggunakan update_status dari logistics_service.

Pilihan 3 - Get Order Information: Mengambil input dari pengguna untuk order_id, memanggil get_order dari logistics_service, dan menampilkan informasi pesanan jika ditemukan.

Pilihan 4 - Exit: Mengakhiri program dengan pesan perpisahan.

create_order Method: Method ini digunakan untuk membuat pesanan baru dengan parameter supplier_name, material_name, dan quantity. Setiap pesanan memiliki status awal 'Pending'. Metode ini mengembalikan ID pesanan yang baru dibuat.

update_status Method: Method ini digunakan untuk memperbarui status pesanan berdasarkan order_id yang diberikan. Jika order_id ditemukan dalam orders, status pesanan diperbarui sesuai dengan nilai status yang diberikan ('Processed' atau 'Shipped').

get_order Method: Method ini digunakan untuk mengembalikan informasi pesanan berdasarkan order_id. Jika order_id ditemukan dalam orders, metode ini mengembalikan kamus yang berisi informasi pesanan. Jika tidak ditemukan, metode ini mengembalikan None.

# Metode 5W + 1H
1. What (Apa):
Apa tujuan dari kode ini?
Kode ini bertujuan untuk menyediakan layanan logistik sederhana untuk mengelola pengadaan bahan baku. Ini mencakup pembuatan pesanan baru, pembaruan status pesanan, dan mendapatkan informasi pesanan.

2. Mengapa (Why)
Mengapa layanan logistik bahan baku dibuat?
Untuk mempermudah pengelolaan pengadaan bahan baku dari berbagai pemasok dengan memantau pesanan dan statusnya secara efisien.

3. Who (Siapa):
Siapa yang akan menggunakan layanan logistik ini?
Pengusaha atau perusahaan yang memerlukan pengelolaan pengadaan bahan baku, seperti produsen atau distributor.

4. When (Kapan):
Kapan layanan ini digunakan?
Layanan ini digunakan saat perusahaan membutuhkan pesanan bahan baku dari pemasok, dan ketika status pesanan perlu diperbarui atau informasi pesanan diperlukan.

5. Where (Dimana):
Dimana layanan ini dapat digunakan?
Layanan ini dapat digunakan di lingkungan perusahaan atau sistem informasi yang mengelola pengadaan bahan baku.

6. How (Bagaimana):
Bagaimana cara layanan ini bekerja?
Layanan ini bekerja dengan cara menyediakan fungsi untuk membuat pesanan baru, memperbarui status pesanan, dan mendapatkan informasi pesanan melalui antarmuka pengguna interaktif.