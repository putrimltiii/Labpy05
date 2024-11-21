# Labpy05
# Tugas Praktikum
# Nama: Putri Melati Ramadhaniati (312410194)

Soal Tugas Praktikum

Buat program sederhana yang akan menampilkan daftar nilai
mahasiswa, dengan ketentuan:

• Program dibuat dengan menggunakan Dictionary

• Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data,
Tampilkan Data, Cari Data)

• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
uts: 35%, uas: 35%)

• Buat flowchart dan penjelasan programnya

![Program 1](https://github.com/user-attachments/assets/c0df0677-5cc5-4932-be23-38aaf56e1de9)
![Program 2](https://github.com/user-attachments/assets/faa6ff8b-9c86-4088-b9cc-2fc979c77ae0)
![Program 3](https://github.com/user-attachments/assets/09129ba9-0970-4132-a0ad-1e924150c96d)
![Program 4](https://github.com/user-attachments/assets/ae58c9d6-38aa-4225-a515-a76552c407d5)
![Program 5](https://github.com/user-attachments/assets/584de1ab-cf94-4ab7-b517-930bdcf29994)

# Penjelasan Program

1. **Membuat dictionary untuk menyimpan data mahasiswa**:
   
   - Program ini menggunakan dictionary `dataMahasiswa` untuk menyimpan data nilai mahasiswa.
     
   - Dictionary ini akan menyimpan nama mahasiswa sebagai key, dan nilai-nilai lainnya (tugas, UTS, UAS, nilai akhir) sebagai value.

2. **Fungsi tambah_data()**:
   
   - Fungsi ini digunakan untuk menambahkan data mahasiswa baru ke dalam dictionary `dataMahasiswa`.
     
   - Pengguna akan diminta untuk memasukkan nama, NIM, nilai tugas, UTS, dan UAS.
     
   - Program akan menghitung nilai akhir berdasarkan bobot yang diberikan (tugas 30%, UTS 35%, UAS 35%).
     
   - Data mahasiswa baru kemudian disimpan ke dalam dictionary `dataMahasiswa`.

4. **Fungsi tampilkan_data()**:
   
   - Fungsi ini digunakan untuk menampilkan semua data mahasiswa yang tersimpan di dalam dictionary `dataMahasiswa`.
     
   - Data akan ditampilkan dalam format tabel yang rapi, dengan nomor urut, nama, nilai tugas, UTS, UAS, dan nilai akhir.
     
   - Jika dictionary `dataMahasiswa` masih kosong, maka program akan menampilkan pesan "Data masih kosong!".

5. **Fungsi ubah_data()**:
   
   - Fungsi ini digunakan untuk mengubah data mahasiswa yang sudah tersimpan di dalam dictionary `dataMahasiswa`.
     
   - Pengguna akan diminta untuk memasukkan nama mahasiswa yang ingin diubah.
     
   - Jika nama mahasiswa ditemukan di dalam dictionary, pengguna akan diminta memasukkan nilai tugas, UTS, dan UAS yang baru.
     
   - Program akan menghitung kembali nilai akhir berdasarkan bobot yang diberikan, dan menyimpan perubahan data ke dalam dictionary `dataMahasiswa`.
     
   - Jika nama mahasiswa tidak ditemukan di dalam dictionary, maka program akan menampilkan pesan "Data tidak ditemukan!".

6. **Fungsi hapus_data()**:
   
   - Fungsi ini digunakan untuk menghapus data mahasiswa yang sudah tersimpan di dalam dictionary `dataMahasiswa`.
     
   - Pengguna akan diminta untuk memasukkan nama mahasiswa yang ingin dihapus.
     
   - Jika nama mahasiswa ditemukan di dalam dictionary, maka data mahasiswa tersebut akan dihapus.
     
   - Jika nama mahasiswa tidak ditemukan di dalam dictionary, maka program akan menampilkan pesan "Data tidak ditemukan!".

7. **Fungsi cari_data()**:
   
   - Fungsi ini digunakan untuk mencari data mahasiswa yang sudah tersimpan di dalam dictionary `dataMahasiswa`.
     
   - Pengguna akan diminta untuk memasukkan nama mahasiswa yang ingin dicari.
     
   - Jika nama mahasiswa ditemukan di dalam dictionary, maka program akan menampilkan detail data mahasiswa tersebut (nama, nilai tugas, UTS, UAS, dan nilai akhir).
     
   - Jika nama mahasiswa tidak ditemukan di dalam dictionary, maka program akan menampilkan pesan "Data tidak ditemukan!".

8. **Program Utama**:
   
   - Program utama akan menampilkan menu utama yang terdiri dari 5 pilihan:
     
     1. Tambah Data
        
     2. Tampilkan Data
        
     3. Ubah Data
        
     4. Hapus Data
        
     5. Cari Data
         
   - Pengguna dapat memilih salah satu menu dengan memasukkan nomor (1-5).
     
   - Jika pengguna memilih menu 0 (Keluar), maka program akan berhenti.
     
   - Jika pengguna memilih nomor yang tidak valid, maka program akan menampilkan pesan "Pilihan menu tidak valid!".

Secara keseluruhan, program ini berfungsi untuk mengelola data nilai mahasiswa, mulai dari menambahkan, menampilkan, mengubah, menghapus, dan mencari data mahasiswa. Program ini memanfaatkan dictionary untuk menyimpan data, dan beberapa fungsi untuk melakukan operasi-operasi tersebut.

# Hasil Run(Output)

# **Tambahkan Data**

![Tambah Data](https://github.com/user-attachments/assets/28a555c1-201e-4db3-a3b4-35e3ac46eefe)

# **Tampilkan Data**

![Tampilkan Data](https://github.com/user-attachments/assets/9992318a-c7f3-47dc-aeea-5b35233a60b6)

# **Ubah Data**

![Ubah Data](https://github.com/user-attachments/assets/bf6b2c35-9d86-4b34-824c-50a49419f5a3)

# **Hapus Data**

![Hapus Data](https://github.com/user-attachments/assets/c64656c5-8e40-46d9-b35c-7fff4c04cee5)

# **Cari Data**

![Cari Data](https://github.com/user-attachments/assets/1c2bf9dc-1d3c-4cc7-a8d7-9d1154feecc8)

# **Keluar**

![Keluar](https://github.com/user-attachments/assets/39d71fe8-47a3-4657-8b66-6c18eac09053)
