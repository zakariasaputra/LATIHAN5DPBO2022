# Design Pemrograman Berorientasi Objek
Repositori ini dibuat untuk memenuhi tugas latihan dari Mata Kuliah Desain Pemrograman Berorientasi Objek di Semester 4 pada Program Studi Ilmu Komputer Universitas Pendidikan Indonesia. Di dalamnya terdapat beberapa implementasi kelas dalam bahasa Python.
> Muhammad Zakaria Saputra; 2007993; Ilmu Komputer-C1-2020; Universitas Pendidikan Indoneisa

### Task Description
* Mengganti font dan ukuran teks
  * Klik elemen yang ingin diubah di JFrame hingga muncul menu Palette dan Properties-nya. Di Properties, cari menu "font", kemudian sesuaikan jenis dan ukuran font yang diinginkan.
* Mengubah nama variabel setiap komponen (misal komponen input NIM diberi nama variabel txtNim)
  * Klik kanan elemen yang akan diubah di JFrame, lalu pilih menu "Change Variable Name" dan ubahlah nama variabel sesuai kebutuhan.
* Menambahkan validasi ketika inputan tidak lengkap, seperti memunculkan pesan error menggunakan class JOptionPane
  * Cek apakah ada inputan data yang kosong atau tidak ada nilainya, dengan membandingkannya menggunakan `equals("")`. 
  * Jika ada inputan data yang kosong atau tidak ada nilainya, maka tampilkan pesan error.
* Menghapus data pada label inputan ketika sudah selesai add, update, delete, maupun ketika menekan tombol cancel
  * Menggunakan `setText("")` untuk setiap variabel di masing-masing kotak, ditambahkan setelah memindahkan teks ke dalam masing-masing variabel. 
* Mengupdate tabel setiap kali ada perubahan pada data hasil add, update dan delete
  * Menambahkan `[nama_variabel_tabel].setModel(setTable());` setelah data dimodifikasi di masing-masing method.

**Bonus**
* Menambahkan atribut inputan baru selain yang sudah ada pada form, namun tetap berkaitan dengan data mahasiswa. Pastikan penambahan ini ditampilkan juga di tabel
  * Di sini saya menambahkan atribut inputan "Kelas", berikut langkah-langkahnya :
   1.  Menambahkan label dan textfield untuk atribut kelas di desain JFrame.
   2.  Menambahkan atribut beserta Setter-Getter di class-nya (Mahasiswa.java).
   3.  Menambahkan data baru saat deklarasi `object[] column`, yakni "Kelas".
   4.  Menambahkan data baru di deklarasi `object[] row`. Pada kasus ini kelas merupakan data keempat, maka objek yang diisi berada pada indeks ke-3.
   5.  Pada method **insertData** dan **updateData**, ditambahkan variabel baru yang sesuai dan diisi dengan teks yang ada pada kotak.
   6.  Pada method **tableMouseClicked**, ditambahkan baris untuk kolom kelas.

### Tools
- [Apache Netbeans](https://netbeans.apache.org/)

### Results
1. Tampilan Awal</br>
![awal](https://github.com/zakariasaputra/LATIHAN5DPBO2022/blob/ba0142f2569fa339ddb25cfd4f4ab71e23854ab4/Screenshot%20Hasil/Tampilan%20Awal.png)</br>
2. Input Kosong</br>
![kosong](https://github.com/zakariasaputra/LATIHAN5DPBO2022/blob/ba0142f2569fa339ddb25cfd4f4ab71e23854ab4/Screenshot%20Hasil/Input%20Kosong.png)</br>
3. Add</br>
![add](https://github.com/zakariasaputra/LATIHAN5DPBO2022/blob/ba0142f2569fa339ddb25cfd4f4ab71e23854ab4/Screenshot%20Hasil/Add.png)</br>
4. Update</br>
![update](https://github.com/zakariasaputra/LATIHAN5DPBO2022/blob/ba0142f2569fa339ddb25cfd4f4ab71e23854ab4/Screenshot%20Hasil/Update.png)</br>
5. Delete</br>
![delete](https://github.com/zakariasaputra/LATIHAN5DPBO2022/blob/ba0142f2569fa339ddb25cfd4f4ab71e23854ab4/Screenshot%20Hasil/Delete.png)</br>
