# Laporan-setup-ubuntu
### Soal Nomor 1
- Laporan proses instalasi sistem operasi linux

## Pendahuluan
Pada praktikum ini, kami melakukan instalasi sistem operasi Ubuntu di VirtualBox untuk memahami dasar-dasar penggunaan virtualisasi dan pengaturan sistem operasi Linux.

## Alat dan Bahan
- VirtualBox
- ISO file Ubuntu Versi 24.04
- PC/Laptop

## Langkah-Langkah Instalasi
### 1. Membuat Virtual Machine Baru di VirtualBox
Buka VirtualBox dan klik "New" pada icon diatas lalu Next.

![Proses pembuatan virtual machine ubuntu](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20190742.png)

### 2. Memasukkan File ISO
Klik "ISO Image" dan Cari File ISO UBUNTU Yang sudah Didownload dan Tekan Next.

![menambahkan file iso ke Virtual Machine](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20190820%20-%20Copy%20-%20Copy.png)

### 3. Membuat Username, Password, dan Nama Host
Untuk Langkah Ini Kita Bebas Memasukkan Yang Kita Mau, Kalau Sudah Selesai Tekan next.

![membuat username, password. dan Host name](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191013%20-%20Copy.png)

### 4. Mengatur Seberapa Banyak RAM dan CPU Yang Akan Digunakan
Pada langkah kali ini, Ada pilihan untuk mengatur seberapa banyak RAM dan CPU yang akan digunakan. Biasanya pada RAM menggunakan 4GB (4096 MB) dan CPU kisaran 1-5, disini saya mengatur jumlah RAM dan CPU yang digunakan pada Virtual Machine ini pada 4GB (4096 MB) dan 4 GPU Lalu Tekan Next.

![mengatur seberapa banyak memori dan cpu yang akan digunakan](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191230%20-%20Copy.png)

### 5. Menetapkamn Virtual Base Memori
Selanjutnya adalah menetapkan Virtual Base Memori pada Virtual Machine Linux, disini saya menetapkan memori yang akan dialokasikan ke Virtual Machine sebanyak 20 GB 
(20480 MB) dan Tekan Next.

![menetapkan virtua base memori](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191259.png)

### 6. Menunggu Proses Instalasi UBUNTU Versi 24.04
Proses kali ini hanya menunggu instalasi UBUNTU pada VirtualBox.

![menunggu proses instalasi ubuntu versi 24.04](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191358.png)

![menunggu proses instalasi ubuntu versi 24.04](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191926.png)

### 7. Proses Mengatur Bahasa, Tata Letak(Layout) Keyboard, dan Menyetel Zona Waktu Yang Digunakan

- Mengatur Bahasa Yang Akan Digunakan

Pada proses instalasi ini, bisa bebas memilih bahasa yang akan digunakan lalu next.

![bahasa yang digunakan](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191614.png)

- Mengatur Layout Keyboard Yang Akan Digunakan

Masih pada proses instalasi, kita bebas memilih layout keyboard yang akan digunakan (Saya memakai layout English US), lalu tekan next.

![memilih layout](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191637.png)

- Membuat Nama, Username, dan Password

Kemudian masih pada proses instalasi, disini akan disuruh membuat Nama, Username, dan Password untuk masuk pada Sistem Operasi Linux nantinya. Klik Next

![pembuatan Nama, Username, dan Password untuk Linux](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191855.png)

- Menyetel Zona Waktu Yang Digunakan

Proses kali ini setting zona waktu yang akan digunakan. Klik Next

![Zona Waktu yang digunakan](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20191907.png)

### 8. Masukkan Password Yang baru Saja Dibuat
Sebelum masuk ke Tampilan UBUNTU Linux pada VirtualBox, user harus memasukkan password yang sudah dibuat pada proses instalasi sebelumnya.

![login akun yang baru saja dibuat](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20193418.png)

### 9. Tampilan Linux UBUNTU Versi 24.04
Berikut adalah tampilan Linux UBUNTU Versi 24.04 yang berhasil diinstal

![Linux UBUNTU 24.04](Screenshot%20Tugas%20linux/Screenshot%202024-08-29%20193628.png)



### Soal Nomor 2

Karena “/” adalah root filesystem yang menyimpan semua file sistem dan direktori penting, pemilihan opsi Mount Point ini memastikan bahwa sistem tahu di mana menyimpan data dan konfigurasi sistem.


### Soal Nomor 3

*ext4* adalah sistem berkas default di banyak distribusi Linux modern, menawarkan dukungan untuk ukuran file hingga 16 TB dan partisi hingga 1 EB. Fitur-fiturnya termasuk jurnal, cek konsistensi, dan efisiensi penyimpanan.

*ext3* adalah versi sebelumnya dari ext4, mendukung ukuran file hingga 2 TB dan partisi hingga 32 TB. Fitur utamanya adalah jurnal yang membantu pemulihan data setelah crash.

*swap* adalah partisi atau file di Linux yang digunakan sebagai memori virtual untuk memperluas kapasitas RAM dengan menyimpan data yang tidak aktif, membantu manajemen memori saat RAM fisik penuh.

*NTFS* adalah sistem berkas default untuk Windows NT dan versi terbaru, mendukung ukuran file besar, fitur keamanan file, dan kompresi data. Di Linux, NTFS memerlukan driver tambahan untuk akses baca-tulis.

*FAT32* adalah sistem berkas yang lebih tua, umum pada media penyimpanan portabel, mendukung ukuran file hingga 4 GB dan partisi hingga 2 TB. Kelemahannya adalah tidak mendukung fitur seperti izin file atau enkripsi.

*Btrfs* adalah sistem berkas modern untuk Linux dengan fitur canggih seperti snapshot, kompresi, dan pengelolaan ruang efisien. Meskipun menawarkan banyak fitur, Btrfs masih dalam pengembangan aktif dan lebih kompleks dibandingkan ext4.
