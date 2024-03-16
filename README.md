# LP5DPBO2K24C1
# janji bang
# saya muhamad irfan 2201897 berjanji mengerjakan LP5 dengan jujur, dan mengharap ridhonya maka dengan itu saya tidak melakukan kecuarngan seperti yang dispesifikasikan

 Desain Program

 Komponen Utama:
- JFrame: Menyediakan jendela utama aplikasi.
- JPanel: Digunakan untuk menampung elemen-elemen antarmuka pengguna.
- JLabel: Menampilkan teks statis.
- JTextField: Input teks untuk NIM, Nama, dan Email.
- JComboBox: Pilihan dropdown untuk jenis kelamin.
- JTable: Menampilkan data mahasiswa dalam bentuk tabel.
- JButton: Untuk menambah, mengubah, dan menghapus data.
- JScrollPane: Untuk menggulung tabel jika data melebihi ukuran tampilan.

 Kelas Utama:
- Menu: Kelas utama yang mengatur antarmuka pengguna dan logika program.
- Mahasiswa: Kelas untuk merepresentasikan objek Mahasiswa.

 Penjelasan Alur

1. Pengguna membuka aplikasi dan melihat daftar mahasiswa yang tersedia dalam tabel.
2. Pengguna dapat menambahkan data baru dengan mengisi formulir di bagian atas dan menekan tombol "Add".
3. Jika pengguna memilih salah satu baris di tabel, formulir akan diisi dengan data yang sesuai, dan tombol "Update" dan "Delete" akan muncul.
4. Pengguna dapat memperbarui data yang dipilih dengan mengubah nilai dalam formulir dan menekan tombol "Update".
5. Pengguna dapat menghapus data yang dipilih dengan menekan tombol "Delete".
6. Pengguna juga dapat membatalkan operasi dengan menekan tombol "Cancel", yang akan mengosongkan formulir.

 Dokumentasi

 Mahasiswa.java
Kelas Mahasiswa merepresentasikan entitas Mahasiswa dengan atribut NIM, Nama, Email, dan Jenis Kelamin.

Metode Utama:
- `getNim()`: Mengembalikan NIM mahasiswa.
- `getNama()`: Mengembalikan nama mahasiswa.
- `getEmail()`: Mengembalikan email mahasiswa.
- `getJenisKelamin()`: Mengembalikan jenis kelamin mahasiswa.
- `setNim(String nim)`: Mengatur NIM mahasiswa.
- `setNama(String nama)`: Mengatur nama mahasiswa.
- `setEmail(String email)`: Mengatur email mahasiswa.
- `setJenisKelamin(String jenisKelamin)`: Mengatur jenis kelamin mahasiswa.

 Menu.java
Kelas Menu merupakan kelas utama yang mengatur antarmuka pengguna dan logika program.

Metode Utama:
- `setTable()`: Mengatur model tabel dengan data mahasiswa.
- `insertData()`: Memasukkan data mahasiswa baru ke dalam daftar.
- `updateData()`: Memperbarui data mahasiswa yang ada.
- `deleteData()`: Menghapus data mahasiswa yang dipilih.
- `clearForm()`: Mengosongkan formulir input.
- `populateList()`: Mengisi daftar mahasiswa dengan data awal.


SS 
![Screenshot 2024-03-16 212854](https://github.com/mhmdirfn01/LP5DPBO2K24C1/assets/145920545/8eb45781-dac5-4f5b-8994-c806dde10841)
![Screenshot 2024-03-16 212859](https://github.com/mhmdirfn01/LP5DPBO2K24C1/assets/145920545/38d32df4-ce25-4f35-bf1f-90410e449854)
![Screenshot 2024-03-16 212920](https://github.com/mhmdirfn01/LP5DPBO2K24C1/assets/145920545/e05bf361-82fe-4054-b0ad-d6f5a9b388f0)
![Screenshot 2024-03-16 212925](https://github.com/mhmdirfn01/LP5DPBO2K24C1/assets/145920545/96133e1b-11a7-4250-9fca-f15843c8abae)

