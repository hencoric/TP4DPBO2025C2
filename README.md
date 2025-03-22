# JANJI

Saya Marco Henrik Abineno dengan NIM 2301093 berjanji mengerjakan TP4 DPBO dengan keberkahan-Nya, maka saya tidak akan melakukan kecurangan sesuai yang telah di spesifikasikan, Aamiin

# DESAIN PROGRAM

Program ini adalah Aplikasi Manajemen Data Mahasiswa berbasis Java Swing, yang memungkinkan pengguna untuk menambahkan, memperbarui, dan menghapus data mahasiswa. Data mahasiswa mencakup:

1. NIM (Nomor Induk Mahasiswa)
2. Nama
3. Jenis Kelamin (Laki-laki/Perempuan)
4. Tingkat Pendidikan (S1, S2, D4)

## Komponen Utama:

### 1. Kelas Menu (GUI Utama)
a. Menggunakan JFrame sebagai window utama.  
b. Menggunakan JTable untuk menampilkan daftar mahasiswa.  
c. Memiliki beberapa input field: JTextField, JComboBox, dan JRadioButton untuk memasukkan data.  
  
Dilengkapi tombol:  
a. Add/Update untuk menambah atau memperbarui data.  
b. Delete untuk menghapus data.  
d. Cancel untuk mengosongkan input  
  
dan, Mengelola data dengan ArrayList.  
  
### 2. Kelas Mahasiswa (Model)
  
a. Menyimpan informasi mahasiswa.
b. Memiliki getter dan setter untuk mengakses dan mengubah data.

# ALUR PROGRAM

a. Saat Program Dijalankan
 - Aplikasi membuka window utama (Menu).
 - populateList() mengisi tabel dengan data mahasiswa awal.

b. Menambah Data Mahasiswa
 - Pengguna mengisi NIM, Nama, Jenis Kelamin, dan Tingkat Pendidikan.
 - Klik tombol Add.
 - Data disimpan ke dalam ArrayList<Mahasiswa>.
 - Tabel diperbarui untuk menampilkan data baru.
 - Formulir dikosongkan (clearForm()).
 - Muncul notifikasi sukses.
  
c. Memilih Data di Tabel
 - Pengguna mengklik baris dalam JTable.
 - Data dari tabel dimasukkan ke dalam input field.
 - Tombol Add berubah menjadi Update.
 - Tombol Delete ditampilkan.
  
d. Memperbarui Data Mahasiswa
 - Pengguna mengubah data yang telah dipilih.
 - Klik Update.
 - Data di ArrayList<Mahasiswa> diperbarui.
 - Tabel diperbarui.
 - Formulir dikosongkan.
 - Notifikasi sukses muncul.
  
e. Menghapus Data Mahasiswa
 - Pengguna memilih data di tabel.
 - Klik Delete.
 - Konfirmasi penghapusan muncul.
 - Jika memilih Yes, data dihapus dari ArrayList<Mahasiswa>.
 - Tabel diperbarui.
 - Formulir dikosongkan.

# DOKUMENTASI

### ADD

1. Input Data  
   ![image](https://github.com/user-attachments/assets/528f1f39-f1bf-4fbb-943c-19f90470577f)  

2. Tekan Tombol Add dan akan muncul pemberitahuan sukses dan formulir dikosongkan  
   ![image](https://github.com/user-attachments/assets/25a1f02d-dca3-40aa-975d-eaa331e845e7)  

### UPDATE 

1. Pilih data yang ingin di update dan ganti data yang sudah ada  
   ![image](https://github.com/user-attachments/assets/31662f92-2adb-4a28-80d4-95ea88a5a478)  
  
2. Tekan tombol update akan muncul pemberitahuan sukses dan formulir dikosongkan  
   ![image](https://github.com/user-attachments/assets/a82929ef-c645-4a2a-9412-ba45edb975e9)  

### DELETE

1. Pilih data yang ingin di hapus dan tekan delete  
   ![image](https://github.com/user-attachments/assets/5c24c79c-c91e-45d1-8f09-c6202735d1bc)  

2. Tekan Yes  
   ![image](https://github.com/user-attachments/assets/6ff7dd5a-a7d1-4823-8151-4f28e9002c8c)  

3. Akan Ada pemberitahuan sukses  
   ![image](https://github.com/user-attachments/assets/ec534a39-f896-49ee-ad3d-e28ad5a7324c)  
  
   

   

