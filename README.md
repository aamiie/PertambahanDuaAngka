
---
identitas
- Nama : Rahmi Hidayah
- NPM : 2210010376
- Kelas : 5B Nonreg Banjarmasin

Program Pertambahan Dua Angka

## Deskripsi Program
Program ini merupakan aplikasi sederhana berbasis GUI (Graphical User Interface) yang digunakan untuk menjumlahkan dua angka yang dimasukkan oleh pengguna. Program dibuat menggunakan Java Swing dan menyediakan fitur utama seperti menghitung hasil penjumlahan, menghapus input, dan keluar dari aplikasi.

---

## Fitur Utama
1. **Penjumlahan Dua Angka**  
   - Pengguna dapat memasukkan dua angka pada kolom input dan menghitung hasil penjumlahan dengan menekan tombol **Tambah**.
   
2. **Hapus Input**  
   - Tombol **Hapus** memungkinkan pengguna untuk mengosongkan semua input dan hasil perhitungan.

3. **Keluar dari Aplikasi**  
   - Tombol **Keluar** digunakan untuk menutup aplikasi.

4. **Informasi Footer**  
   - Panel footer menampilkan nama pembuat aplikasi.

---

## Komponen GUI
1. **JLabel**  
   - Label untuk menunjukkan deskripsi input/output, seperti "Angka 1", "Angka 2", dan "Hasil".

2. **JTextField**  
   - Tiga text field:
     - Dua untuk memasukkan angka.
     - Satu untuk menampilkan hasil penjumlahan.

3. **JButton**  
   - Tombol **Tambah** untuk menghitung hasil penjumlahan.
   - Tombol **Hapus** untuk mengosongkan input dan hasil.
   - Tombol **Keluar** untuk menutup aplikasi.

4. **JPanel**  
   - Panel untuk mengorganisasi tata letak elemen GUI.

---

## Cara Menjalankan Program
1. **Persyaratan:**
   - Pastikan Anda memiliki **Java Development Kit (JDK)** versi 8 atau lebih baru.

2. **Langkah-Langkah:**
   - Clone atau unduh file program.
   - Buka file `PertambahanDuaAngka.java` menggunakan IDE seperti NetBeans, Eclipse, atau IntelliJ IDEA.
   - Compile dan jalankan program.

3. **Penggunaan Aplikasi:**
   - Masukkan dua angka pada kolom input.
   - Klik tombol **Tambah** untuk melihat hasil penjumlahan.
   - Klik tombol **Hapus** untuk mengosongkan kolom input dan hasil.
   - Klik tombol **Keluar** untuk menutup aplikasi.

---

## Penjelasan Logika Program
1. **Penjumlahan**  
   - Ketika tombol **Tambah** ditekan, program membaca input dari dua text field, mengonversi nilai string menjadi integer, dan menghitung hasil penjumlahan.  
   - Hasil penjumlahan ditampilkan pada text field hasil.

2. **Hapus Input**  
   - Tombol **Hapus** akan mengosongkan semua text field dan mengembalikan fokus ke kolom input pertama.

3. **Keluar Aplikasi**  
   - Tombol **Keluar** memanggil fungsi `dispose()` untuk menutup jendela aplikasi.

---

## Contoh Penggunaan
1. **Input:**
   - Angka 1: `5`
   - Angka 2: `10`

2. **Output:**
   - Hasil: `15`

---

## Struktur Program
1. **GUI:**
   - Elemen GUI diatur menggunakan `javax.swing` untuk membuat form dan komponen seperti `JLabel`, `JTextField`, dan `JButton`.

2. **Event Handling:**
   - **Tombol Tambah:** Menggunakan event listener untuk membaca input, menghitung hasil, dan menampilkan output.
   - **Tombol Hapus:** Membersihkan semua text field.
   - **Tombol Keluar:** Menutup aplikasi.


---

## Lisensi
Program ini dirancang untuk tujuan pembelajaran. Anda bebas menggunakannya untuk proyek serupa atau memodifikasinya sesuai kebutuhan. 😊
 
