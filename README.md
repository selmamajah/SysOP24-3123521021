![alt text](https://github.com/selmamajah/SysOP24-3123521021/blob/main/Selma%20Diagram%20pertemuan%202.drawio%20(1).png?raw=true)

Berikut Penjelasan dari Diagram yang saya buat:

**POST (Power On Self Test):**
- Selama tahap POST, komputer melakukan pemeriksaan mandiri terhadap perangkat kerasnya.
- POST memastikan bahwa komponen seperti RAM, CPU, kartu grafis, dan perangkat penyimpanan berfungsi dengan baik.
- Jika ada masalah dengan perangkat keras, POST biasanya memberikan kode kesalahan atau bunyi bip yang mengindikasikan masalah tersebut.

**Bootloader:**
- Bootloader adalah program kecil yang berada pada sektor awal dari hard drive atau media penyimpanan lainnya.
- Tugas bootloader adalah mencari dan memuat sistem operasi yang akan dijalankan.
- Beberapa bootloader populer termasuk GRUB (Grand Unified Bootloader) untuk Linux dan NTLDR (New Technology Loader) atau BOOTMGR (Boot Manager) untuk Windows.

**Sistem Operasi:**
- Sistem operasi (SO) adalah perangkat lunak inti yang mengelola sumber daya perangkat keras dan menyediakan antarmuka antara pengguna dan komputer.
- Setelah dimuat ke dalam memori utama (RAM), sistem operasi mengambil kendali dan memulai eksekusi program.
- Sistem operasi bertanggung jawab atas manajemen memori, file, proses, dan perangkat.

**Desktop:**
- Desktop adalah antarmuka grafis pengguna pada sistem operasi, memberikan lingkungan visual tempat pengguna dapat berinteraksi dengan komputer.
- Pada desktop, pengguna dapat melihat ikon, memulai program, membuka file, dan melakukan berbagai tugas lainnya.
- Pengaturan desktop, seperti latar belakang dan tata letak ikon, dapat disesuaikan sesuai preferensi pengguna.

Semua langkah ini membentuk suatu proses yang kompleks namun terstruktur saat komputer menyala dan bersiap untuk digunakan. Dengan pemahaman yang lebih mendalam tentang setiap tahap, pengguna dapat memahami bagaimana komputer mereka beroperasi dan mengidentifikasi potensi masalah jika terjadi gangguan pada salah satu tahapan proses booting.

Booting adalah proses dimana sebuah komputer atau perangkat lunak komputer diaktifkan dan memuat sistem operasi atau perangkat lunak lainnya ke dalam memori. Ada beberapa jenis booting yang umum digunakan, termasuk:

1. **Cold Boot (Boot Dingin):**
   - Cold boot terjadi ketika komputer atau perangkat dinyalakan setelah sebelumnya dimatikan sepenuhnya.
   - Pada cold boot, semua perangkat keras dan perangkat lunak sistem diinisialisasi kembali.

2. **Warm Boot (Boot Hangat):**
   - Warm boot terjadi ketika komputer di-restart tanpa dimatikan sepenuhnya.
   - Pada warm boot, beberapa komponen sistem mungkin tetap dalam keadaan aktif, dan tidak seperti cold boot, proses inisialisasi penuh tidak terjadi.

3. **Remote Booting:**
   - Remote booting melibatkan booting dari sumber yang tidak berada di perangkat fisik yang sama.
   - Contohnya adalah booting melalui jaringan (network boot), di mana sistem operasi dimuat dari server jaringan ke komputer klien.

4. **Network Boot (Boot Jaringan):**
   - Booting melalui jaringan memungkinkan sebuah komputer untuk memuat sistem operasi atau perangkat lunak lainnya dari server jaringan, tanpa menggunakan media penyimpanan lokal.

5. **Dual Boot:**
   - Dual boot memungkinkan pengguna untuk menginstal dan menjalankan dua sistem operasi yang berbeda pada satu komputer.
   - Pada saat booting, pengguna dapat memilih sistem operasi mana yang ingin digunakan.

6. **Multi-Boot:**
   - Multi-boot mirip dengan dual boot, tetapi melibatkan lebih dari dua sistem operasi yang dapat dipilih pada saat booting.

7. **Live Boot:**
   - Live boot memungkinkan pengguna untuk menjalankan sistem operasi langsung dari media penyimpanan tanpa menginstalnya pada hard drive.
   - Umumnya digunakan untuk uji coba atau pemulihan sistem.

8. **Fast Boot:**
   - Fast boot adalah fitur yang dirancang untuk mempercepat proses booting dengan meminimalkan waktu inisialisasi perangkat keras.

Setiap jenis booting memiliki tujuan dan kegunaannya sendiri tergantung pada kebutuhan pengguna atau konfigurasi sistem yang diinginkan.

MENGINDENTIFIKASI LAPTOP MELALUI APLIKASI CPU-Z

Spesifikasi CPU

![alt text](https://github.com/selmamajah/SysOP24-3123521021/blob/main/Spesifikasi%20CPU%20Selma%20Humayra.PNG?raw=true)

CPU: Tab ini menunjukkan informasi tentang prosesor, seperti nama, kode nama, kecepatan clock, jumlah inti, dan teknologi yang digunakan.

*Section Processor*

Name: Intel Core I5 6300U

Menampilkan nama dari processor yang digunakan pada laptop atau komputer.

Code Name: Skylake-U/Y

Menampilkan Code dari processor yang dipakai komputer atau laptop.

Max TDP:  15.0 Watt

Menyatakan power consumption, Artinya laptop atau komputer ini membutuhkan daya 15.0 Watt saat bekerja.

Package : Socket 1356 FCBGA

Menampilkan bahwa jenis socket pada processor laptop ini adalah Socket 1356 FCBGA.

Technology : 14 nm

Menampilkan Seberapa besar komponen yang digunakan.

Core VID : 0.641 V

Menampilkan tegangan listrik yang digunakan sekitar 0.641 Volt.

Spesification : Itel Core i5-6300U CPU @ 2.40 Ghz

Menampilkan Spesifikasi dari komputer atau laptop yang dipakai.

Family: 6

Menampikan generasi keberapa processor yang di gunakan.

Ext Family : 6

Menampilkan total family (keluarga) processor yang ada dalam komputer atau laptop.

Intruction : MMX, SSE, SSE2, SSE3, SSSE3, SSE4.2, EM64T, VT-X, AES, AVX, AVX2, FMA3, TSX

Menampilkan instruksi yang didukung dalam processor yang dipakai.

A. MMX : berhubungan dengan Integrasi VGA (yang mangatur tentang visual berupa gambar, grafik, dll). 
B. SSE : jenis – jenis instruksi algoritma atau perhitungan yang dapat dipahami processor. 
C. EM64T : teknologi yang meningkatkan platform server dan stasiun kerja dengan keterlayakan alamat 64 bit dan instruksi terkait. 
D. VT-x : dapat mengizinkan komputer untuk membuat mesin virtual. 

E. TSX:TSX menyediakan dukungan untuk transaksi memori, yang memungkinkan beberapa operasi memori untuk dijalankan sebagai satu kesatuan transaksi atomik. Ini dapat meningkatkan kinerja aplikasi yang menggunakan operasi memori bersamaan pada tingkat tinggi.

Section Clocks (Core #0)
Core Speed : 798.63 MHz

Mengetahui kecepatan satu core satuan dalam melakukan suatu perintah.

Multiplier: x 8.0 (4.0 - 30.0)

Mengatur lebar jalur transfer yang tersedia. Pengkali. Apabila processor banyak melakukan proses pada computer, maka multiplier meningkat. Sedangkan apabila processor sedikit melakukan proses pada computer, maka multiplier menurun dalam keadaan stabil.

Bus Speed: 99.83 MHz

Menampilkan kecepatan transfer data dan instruksi atau kecepatan BUS. Jumlah alur yang mampu dilaksanakan oleh sebuah pemproses dalam masa second. Satuan waktu ini diukur dalam unit juta arahan second yang disebut juga sebagai megahertz (MHz) atau juta kitaran second.

Cache

Cache memory adalah memory berukuran kecil berkecepatan tinggi yang berfungsi untuk menyimpan sementara instruksi dan/atau data (informasi) yang diperlukan oleh prosesor.

L1 Data: 2 x 32 KBytes 8-way
L1 inst.: 2 x 32 Kbytes 8-way
Level 2 : 2x 256 KBytes 4-way
Level 3: 3 Mbytes 12-way

keterangan:

- L1 : Trensfer data ke prosesor paling cepat karena letaknya paling dekat dengan prosesor.

- L2 : Transfer data ke proseror lebih lambat dari L1 karena posisinya lebih jauh dari prosesor.

- L3 : Transfer datanya paling lambat kerena jauh dari prosesor.








