# PA-Capstone

Judul Tema : Pengolahan Data Taman Kanak-kanak (TK)

Projek Akhir ini terdiri dari 4 Package, yaitu:
- Package 1 = Controller
- Package 2 = Model
- Package 3 = Database
- Package 4 = view

1) Package 1 Controller
a. ConstructorStaff
  - Pertama ialah syntax mendeklarasikan package yang digunakan dan mengimpor kelas-kelas yang diperlukan.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/39cc5762-8db1-40a3-b330-ef223fc67362)

  - constructorStaff adalah kelas yang digunakan untuk melakukan operasi terkait staff.
  - arraystaff adalah ArrayList yang digunakan untuk menyimpan data staf. Setiap data staff disimpan dalam bentuk array String.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/7cae1af9-5783-44e8-bae9-fe876eadbf33)

  - public boolean create(), adalah metode yang digunakan untuk menambahkan data staff ke database.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/19d27d9a-c3bb-4fd8-bda7-bd120d843f02)

  - openConnection() adalah metode yang digunakan untuk membuka koneksi ke database.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/4baaed39-d062-4bc8-a610-490a342a60b6)

  - public boolean updateStaff() adalah metode yang digunakan untuk mengupdate data staff, yang di update disini ialah bidang pekerjaan.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/1d9c43c4-72c0-4a46-9033-b2011fb69870)

  - Syntax ini menjalankan pernyataan SQL untuk mengupdate bidang pekerjaan staff berdasarkan ID staff yang di input.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/782e7ba1-9f12-4c28-a1b5-412da9f4afbe)

  - Public readStaff() adalah metode yang digunakan untuk membaca data staff dari tabel staff yang ada di database dan menyimpannya dalam ArrayList.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/ae31eb97-77ea-4be1-8c7c-90bd8fd26412)

  - Syntax ini mengeksekusi query SQL untuk mengambil data staf dari tabel staff dan menyimpannya dalam ArrayList.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/4bbea2f0-d5b9-405d-a259-4819eb02c29f)

  - Public boolean delete() adalah metode yang digunakan untuk menghapus data staff dari tabel staff yang ada di database berdasarkan ID staff yang di input.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/3d7f84dc-cf6c-4f2c-93c0-bfa2f721cfeb)

  - Syntax ini menjalankan pernyataan SQL untuk menghapus data staf berdasarkan ID staf yang di input.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/1f0244cc-559a-411b-87de-9ff6076a92ab)

  - Public boolean find() adalah metode yang digunakan untuk mencari data staff berdasarkan ID staff yang di input.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/309e6517-b6d1-4f58-b9ff-e5e909bc3051)

  - Syntax ini menjalankan query SQL untuk mencari dan mengambil data staff berdasarkan ID staff yang di input.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/9ee1b12e-c9d2-4504-ba77-532ec5816462)

b. Constructormurid
  - Petama ialah syntax mendeklarasikan package yang digunakan dan mengimpor kelas-kelas yang diperlukan.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/b3dd8518-e374-4406-a78e-bae250623419)

  - constructormurid adalah kelas yang digunakan untuk melakukan operasi terkait murid.
  - arrayMurid adalah ArrayList yang digunakan untuk menyimpan data murid. Setiap data murid disimpan dalam bentuk array String.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/451d2e13-7752-48fe-86dd-f97406757e32)

  - Public boolean create() adalah metode yang digunakan untuk menambahkan data murid ke database.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/934826d2-dafa-4d79-9733-7c5f6404befb)

  - openConnection() adalah metode yang digunakan untuk membuka koneksi ke database.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/71267e17-f34b-4ac0-9bc0-59b7228e33a6)

  - Public boolean updateMurid() adalah metode yang digunakan untuk mengupdate data murid, yang di update disini ialah alamat.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/2d71702b-de3a-42e2-aafa-3953c74f25b2)

  - Syntax ini menjalankan pernyataan SQL untuk mengupdate alamat murid berdasarkan ID murid yang di input.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/cd3b60b3-6841-4028-bab6-790850c67c86)

  - public boolean deleteMurid() adalah metode yang digunakan untuk menghapus data murid dari tabel murid berdasarkan ID murid yang diberikan.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/87695a87-bbf2-4b56-85f7-6530f053ff98)

  - Syntax ini menjalankan pernyataan SQL untuk menghapus data murid berdasarkan ID murid yang di input.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/a3daa012-b21d-4c27-871d-a952890a8e4d)

  - Public readMurid() adalah metode yang digunakan untuk membaca data murid dari tabel murid dan menyimpannya dalam arrayMurid.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/2e05020b-9ad6-4bc4-a851-7ca8f4516d5b)

  - Syntax ini menjalankan query SQL untuk mengambil data murid dari tabel murid. Syntax ini juga mengambil data murid dari hasil query dan menyimpannya dalam 
    bentuk array String.

    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/530bf3f0-94ee-4a13-af83-8979995df641)

  - public boolean find() adalah metode yang digunakan untuk mencari data murid berdasarkan ID yang diberikan.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/dac5e20a-e9c0-447d-a091-245c3f2fd156)

c. constructorKelas

d. InheritanceKhusus
Khusus ini ialah kepanjangan dari kelas khusus yang dimana merupakan subtype dari kelas.
  - Pertama ialah mendeklarasikan package dan mengimpor kelas yang terletak dalam package model. Kelas inheritanceKhusus akan 
    menggunakan kelas kelas sebagai dasar pewarisan.

    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/8c65548e-a1c5-48fd-a847-02da4a1e1bfb)

  - inheritanceKhusus adalah kelas yang dideklarasikan dan mendefinisikan pewarisan dengan menggunakan extends. Ini berarti kelas inheritanceKhusus 
    adalah subclass atau turunan dari _kelas_.

    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/1169cc35-6b60-44fa-9b26-3770700f4f06)

  - Atribut materiKhusus merupakan atribut tambahan yang ada hanya pada kelas inheritanceKhusus.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/a9b336a4-30a1-405a-a0d5-faacdf99cd50)

  - Metode getter dan setter untuk atribut materiKhusus. Metode getter getMateriKhusus digunakan untuk mengambil nilai dari atribut materiKhusus, sementara 
    metode setter setMateriKhusus digunakan untuk mengatur nilai atribut materiKhusus.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/b222c43a-8ad4-4019-9b98-36936053650f)

e. InheritanceRegular
Regular ini ialah kepanjangan dari kelas regular yang dimana merupakan subtype dari kelas.
  - Pertama ialah mendeklarasikan package dan mengimpor kelas kelas yang terletak dalam package model. Ini berarti inheritanceRegular akan menggunakan kelas 
    kelas sebagai dasar pewarisan.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/5439e6f2-0cff-4b61-8f4a-7b08a643a326)

  - inheritanceRegular adalah kelas yang dideklarasikan dan mendefinisikan pewarisan dengan menggunakan extends. Ini berarti kelas inheritanceRegular 
    adalah subclass (turunan) dari _kelas_.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/638a3e4f-46ba-472e-9b66-3d51eb3e1268)

  - Atribut metodePengajaran yang merupakan atribut tambahan yang ada hanya pada kelas inheritanceRegular.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/7778b9b3-647b-49f8-bbcf-9ff019fe6788)

2) Package Model
a. murid
  - Pertama ialah syntax mendefinisikan package yang berisi kelas murid dan mengimpor kelas database yang terletak dalam paket database.
    
  ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/54fe0fab-6d6f-4a87-b374-70f8344ab3f9)

  - murid adalah kelas yang menggextend kelas database.
    
  ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/f4c1b0a9-b969-411d-9299-e3d92fe04ebd)

  - Syntax ini mendefinisikan sejumlah atribut dalam kelas murid. Setiap atribut memiliki tipe data tertentu dan berikut adalah atribut-atribut 
    yang didefinisikan:
    1) idMurid: Atribut dengan tipe data String yang tampaknya akan digunakan untuk menyimpan ID murid.
    2) nama: Atribut dengan tipe data String yang menyimpan nama murid.
    3) tanggalLahir: Atribut dengan tipe data String yang menyimpan tanggal lahir murid.
    4) alamat: Atribut dengan tipe data String yang menyimpan alamat murid.
    5) namaOrangTua: Atribut dengan tipe data String yang menyimpan nama orang tua murid.
    6) nomorOrangTua: Atribut dengan tipe data String yang menyimpan nomor telepon orang tua murid.
    7) fkUsername: Atribut dengan tipe data String yang tampaknya akan digunakan untuk menyimpan kunci luar ke tabel pengguna (user).
    8) fkIdKelas: Atribut dengan tipe data String yang tampaknya akan digunakan untuk menyimpan kunci luar ke tabel kelas.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/55e8eb51-3a92-416b-b967-bc3c1c45d7e8)

  - Syntax ini mendefinisikan getter dan setter untuk atribut-atribut dalam kelas murid. Getter digunakan untuk mendapatkan nilai atribut, sedangkan setter 
    digunakan untuk mengatur nilai atribut.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/8e4ff98c-d79f-4a9f-a492-c85ac2a39623)

    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/fc999d19-94d9-4ad9-bb0e-6c3b7b85da42)


b. staff
  - Pertama ialah syntax mendefinisikan paket (package) yang berisi kelas staff dan mengimpor kelas database yang terletak dalam paket database.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/6a665f15-f63d-4e5b-8eaa-541156bfc223)

  - staff adalah kelas yang didefinisikan dan menggextend kelas database.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/8145fedd-6c03-4842-a3ec-7a89847f5022)

  - Syntax ini mendefinisikan sejumlah atribut (variabel anggota) dalam kelas staff. Setiap atribut memiliki tipe data tertentu dan berikut adalah atribut- 
     atribut yang didefinisikan:
    1) idStaff: Atribut dengan tipe data String yang tampaknya akan digunakan untuk menyimpan ID staff.
    2) nama: Atribut dengan tipe data String yang menyimpan nama staff.
    3) alamat: Atribut dengan tipe data String yang menyimpan alamat staff.
    4) nomorTelepon: Atribut dengan tipe data String yang menyimpan nomor telepon staff.
    5) bidangPekerjaan: Atribut dengan tipe data String yang menyimpan bidang pekerjaan staff.
       
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/1ca8a03d-d430-4702-9978-1259f28dc3c8)

  - Syntax ini mendefinisikan getter dan setter untuk atribut-atribut dalam kelas staff. Getter digunakan untuk mendapatkan nilai atribut, sedangkan setter 
    digunakan untuk mengatur nilai atribut.
    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/d0326eab-adaf-4c4a-b40d-02af1a85b530)

    
    ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/c0e4372a-5062-4497-a05a-723097fcd9a8)


c. kelas

3) Package database
- Pertama ialah syntax untuk mendefinisikan package yang berisi kelas database. Kemudian, kelas database import dari pustaka Java SQL 
  (java.sql.*), yang berisi kelas-kelas untuk berinteraksi dengan database.
  
  ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/b46eb440-a8a9-475d-a038-8bdd40766be0)

- Syntax ini mendefinisikan beberapa variabel konstan (final) yang digunakan untuk mengkonfigurasi koneksi database. Variabel-variabel ini mencakup:
  1) dbhost: Menyimpan nama host atau alamat database MySQL (dalam hal ini, "localhost" mengindikasikan bahwa database berjalan di komputer lokal).
  2) dbname: Menyimpan nama database yang akan digunakan (dalam hal ini, "final").
  3) username: Menyimpan nama pengguna (username) yang akan digunakan untuk mengakses database (dalam hal ini, "root").
  4) password: Menyimpan kata sandi yang sesuai dengan pengguna (dalam hal ini, kata sandi kosong, yang tidak aman dan hanya digunakan untuk keperluan 
     pengembangan).
     
  ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/2b0c5e4f-42e3-4390-881a-7a799539e862)

- Syntax ini mendefinisikan beberapa atribut (variabel anggota) yang akan digunakan untuk mengelola koneksi database dan eksekusi pernyataan SQL. Atribut-atribut 
  ini mencakup:
  1) connection: Objek Connection yang digunakan untuk mengelola koneksi ke database.
  2) statement: Objek Statement yang digunakan untuk mengeksekusi pernyataan SQL biasa.
  3) preparedStatement: Objek PreparedStatement yang digunakan untuk mengeksekusi pernyataan SQL dengan parameter.
  4) resultSet: Objek ResultSet yang digunakan untuk menyimpan hasil dari pernyataan SQL yang menghasilkan data (seperti SELECT).
     
  ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/e05b5d04-991f-4166-90c9-0901eb572533)

- Syntax ini mendefinisikan metode openConnection(), yang digunakan untuk membuka koneksi ke database. Metode ini bekerja dengan cara:
- Menggunakan DriverManager untuk mendapatkan koneksi ke database MySQL menggunakan parameter yang telah didefinisikan sebelumnya seperti host, nama database, 
  username, dan password.
- Jika koneksi berhasil, pesan "Mysql successfully connected" akan ditampilkan di konsol.
- Jika ada kesalahan koneksi, metode displayErrors(ex) akan dipanggil untuk menampilkan pesan kesalahan.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/289fcc7f-5453-4d38-aeae-175471e01df7)


![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/618127cc-3c5d-49b3-8a92-c61807ad5e98)


- Syntax ini mendefinisikan metode closeConnection(), yang digunakan untuk menutup koneksi ke database dan melepaskan sumber daya. Metode ini bekerja dengan cara:
- Memeriksa apakah objek resultSet, statement, preparedStatement, dan connection sudah ada (tidak null).
- Jika ada, metode close() dipanggil untuk menutup masing-masing objek.
- Kemudian, objek-objek tersebut diatur menjadi null untuk melepaskan sumber daya.
- Jika ada kesalahan saat menutup objek, metode displayErrors(ex) dipanggil untuk menampilkan pesan kesalahan.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/d018e3b5-383a-4eac-95ab-602019cd31b0)

- Syntax ini mendefinisikan metode displayErrors(ex) yang digunakan untuk menampilkan pesan kesalahan terkait dengan SQL. Metode ini menerima objek SQLException 
  sebagai argumen dan mencetak informasi kesalahan, seperti pesan kesalahan, kode SQLState, dan kode VendorError, ke konsol.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/532c4599-1411-43ed-ba3d-651fa70f8687)

4) Package View
a. admin
 - Kedua variabel ini digunakan untuk mengambil username dan password yang dimasukkan oleh admin melalui User Interface (UI). usernameLogin dan     
   passwordLogin adalah elemen UI yang digunakan untuk memasukkan informasi login. Username diambil sebagai string dari elemen teks, sedangkan password diambil 
   sebagai string dari elemen password (yang konsepnya lebih aman daripada tipe data String biasa).
   
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/c8429392-cad4-4d7b-86c0-e897c187d8da)

- Syntax ini mendefinisikan pernyataan SQL yang akan digunakan untuk mengambil data dari tabel "admin" berdasarkan username dan password yang sesuai.
- Variabel conn digunakan untuk menyimpan koneksi database yang telah dibuka sebelumnya.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/3e4c3075-e941-44d6-b872-290e6e7ad85c)

- Syntax ini berada dalam try dan digunakan untuk menjalankan pernyataan SQL ke database. Selanjutnya membuat PreparedStatement (ps) dari koneksi database dan 
  menyusun menggunakan pernyataan SQL yang telah di definisikan sebelumnya. Kemudian mengisi nilai parameter pertama (?) dengan username dan parameter kedua 
  dengan password yang sudah diambil dari UI. Setelah itu, mengeksekusi pernyataan SQL dengan executeQuery(), yang menghasilkan objek ResultSet (rs) yang berisi 
  hasil dari pernyataan SQL.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/db3e2236-6101-4b50-8a28-536d2697b8af)

- Syntax ini memeriksa hasil dari pernyataan SQL yang dijalankan. Jika rs.next() mengembalikan true, ini berarti ada data di dalam tabel "admin" berdasarkan 
  username dan password yang dimasukkan.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/361271a9-79c6-478d-8c3d-838aa02a9f9d)

- catch menangani penanganan kesalahan yang mungkin terjadi selama eksekusi pernyataan SQL. Jika terjadi kesalahan akan muncul pesan kesalahan yaitu "Data 
  failed!"
- finally digunakan untuk memastikan bahwa koneksi database ditutup.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/d894050a-b4da-4cca-a886-1384a75fa77e)

b. createKelas 
 - Syntax ini membuat objek constructorKelas yang merupakan kelas yang digunakan untuk mengelola data kelas.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/9e49fe5d-4496-416e-be59-8d2b8fe2862d)

 - Syntax ini untuk mengambil teks dari elemen UI dengan nama num dan mengonversinya menjadi integer.
   
   ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/eb22f5f2-ed17-4b74-8215-b21f40982ab5)

 - Syntax ini untuk mengambil teks dari elemen UI dengan nama capacity dan mengonversinya menjadi integer.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/a4d0617b-eece-4383-8a7d-b4894e9e62a1)

 - Syntax ini untuk mengisi properti objek ck dengan nilai-nilai yang diambil dari elemen UI.
    1) ck.namaKelas diisi dengan teks dari elemen UI dengan nama name.
    2) ck.jumlahMurid diisi dengan nilai kpInt yang telah diambil sebelumnya.
    3) ck.kapasitas diisi dengan nilai jmlhInt yang telah diambil sebelumnya.
    4) ck.metodePengajaran diisi dengan teks dari elemen UI dengan nama study.
       
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/c01364ee-4bfe-4ae5-a710-e7d205e925f4)

 - Syntax ini memanggil metode create() pada objek ck. Metode create() ini untuk menyimpan data kelas ke dalam database.
   Jika metode create() berhasil, maka pesan yang tertampil "Data Successfully Saved!".
   Jika metode create() gagal, maka pesan yang tertampil "Data Failed".
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/9b4fdc68-aa83-4399-87fa-261f55fbe2e5)

 - Baris ini digunakan untuk mengosongkan textbox atau field input yang digunakan untuk mengisi data.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/7bcf33d7-11a2-4b2f-9f81-801d5f822d99)

c. createMurid
 - Syntax ini untuk membuat objek constructormurid yang merupakan kelas yang digunakan untuk mengelola data murid.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/aa270f42-59d8-4810-9e97-d5047dbb70ca)

 - Syntax ini mengambil teks dari elemen UI dengan nama nameMurid, DOBMurid, alamatMurid, parentsMurid, phoneMurid, adminStaff, idClass.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/4d5b64bc-c9fd-42e0-9957-b5e6c74fc536)

 - Syntax ini memanggil metode create() pada objek cm. Metode create() ini untuk menyimpan data murid ke dalam database.
   Jika metode create() berhasil, maka pesan yang tertampil "Data Successfully Saved!".
   Jika metode create() gagal, maka pesan yang tertampil "Data Failed".

 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/9ed075a0-d175-4ddc-8019-0f41f650696e)

 - Syntax ini digunakan untuk mengosongkan textbox atau field input yang digunakan untuk mengisi data.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/a8aa9964-0e34-400e-ab6e-7e9462d96661)

d. createStaff
 - Syntax ini untuk membuat objek constructorStaff yang merupakan kelas yang digunakan untuk mengelola data staff.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/e91ad784-0d92-4e2b-8764-337606273119)

 - Syntax ini mengambil teks dari elemen UI dengan nama name, address, phone, occation.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/2efab9c0-e044-470d-a2d8-9e1eaa414c66)

 - Syntax ini memanggil metode create() pada objek st. Metode create() ini untuk menyimpan data staf ke dalam database.
   Jika metode create() berhasil, maka pesan yang tertampil "Data Successfully Saved!".
   Jika metode create() gagal, maka pesan yang tertampil "Data Failed".

 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/b2c0020d-4b98-4c76-b531-3c20e64f2c56)

 - Syntax ini digunakan untuk mengosongkan textbox atau field input yang digunakan untuk mengisi data.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/265ece73-c59d-440d-9a93-2ce13b8f448c)

e. deleteKelas 
 - Syntax ini membuat objek constructorKelas. Ini adalah objek yang digunakan untuk mengelola data kelas, seperti mencari dan menghapusnya dari database.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/a1c929a0-e79b-422c-8ceb-1bb3096289c0)

 - Syntax ini mengambil teks yang dimasukkan oleh admin melalui elemen UI dengan nama idclass. Ini akan digunakan sebagai ID kelas yang akan dihapus.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/e05b1c60-c511-4665-959f-8aafec75617e)

 - Syntax ini memanggil metode find(idKelas) pada objek ck. Metode find ini untuk mencari data kelas dengan ID yang sesuai di dalam database.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/da4c1adc-61df-4ed2-940a-937522a227f1)

 - Syntax ini memanggil metode deleteKelas(idKelas) pada objek ck. Metode ini untuk menghapus data kelas dari database berdasarkan ID kelas yang diberikan. 
   Jika metode create() berhasil, maka pesan yang tertampil "Data Successfully Saved!".
   Jika metode create() gagal, maka pesan yang tertampil "Data Failed".
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/adcfc965-19b9-42eb-916d-52302914d8d1)

 - Syntax ini digunakan untuk mengosongkan textbox atau field input yang digunakan untuk mengisi data.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/43a0df4a-07a3-4cf6-9a33-5bbd72521e75)

f. deleteMurid
 - Syntax ini membuat objek constructormurid. Ini adalah objek yang digunakan untuk mengelola data kelas, seperti mencari dan menghapusnya dari database.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/0ac4a434-fd93-4e6a-b645-2a20ec5d13cd)

 - Syntax ini mengambil teks yang dimasukkan oleh pengguna melalui elemen UI dengan nama deleteId. Nilai ini digunakan sebagai ID murid yang akan dihapus.
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/535c62fb-23e6-44ea-8919-8091afb3a37e)

 - Syntax ini memanggil metode find (idMurid) pada objek mm. Metode find ini untuk mencari data murid dengan ID yang sesuai di dalam database. Ini mungkin akan 
   mengisi properti-properti objek mm dengan data murid yang sesuai jika ditemukan.

 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/8c012dd8-c02a-417e-99c0-4901e52418a6)

 - Syntax metode find selesai dijalankan, syntax ini memanggil metode deleteMurid() pada objek mm. Metode ini mungkin bertanggung jawab untuk menghapus data murid dari database berdasarkan ID murid yang 
   diberikan.
   Jika metode deleteMurid() berhasil, maka pesan yang tertampil "Data Successfully Saved!".
   Jika metode deleteMurid() gagal, maka pesan yang tertampil "Data Failed".
   
 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/486714a6-ce96-4579-bcc7-b5b9b65ed48f)

 - Syntax ini digunakan untuk mengosongkan textbox atau field input yang digunakan untuk mengisi data.

 ![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/581c446c-60e5-4f97-baa6-7d18bb2cd583)

g. deleteStaff
 - Syntax ini membuat objek constructorStaff. Ini adalah objek yang digunakan untuk mengelola data kelas, seperti mencari dan menghapusnya dari database.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/67b8fe44-0972-4d4e-9038-785bebfb0272)

- Syntax ini mengambil teks yang dimasukkan oleh pengguna melalui elemen UI yang mungkin memiliki nama "deleteStaff". Nilai teks ini kemudian disimpan dalam variabel deleteId. Ini kemungkinan adalah ID staf yang akan dihapus.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/5f027d9d-14f1-4d9a-974f-67edf0ef57cf)

- Syntax ini memanggil metode "find" pada objek "st" dengan argumen "deleteId". Metode "find" mungkin bertanggung jawab untuk mencari data staf dalam database yang sesuai dengan ID yang diberikan. Jika data ditemukan, properti objek "st" mungkin akan diisi dengan data staff yang sesuai.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/6f7f9a84-1a36-4852-b660-eb2ab8f75281)

- Ini adalah awal dari struktur pengkondisian. Kode ini memeriksa apakah metode delete pada objek st berhasil dieksekusi.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/24c3c4c2-f570-489c-9a8b-2fc24cc8f975)

- Jika metode delete berhasil (mungkin mengembalikan true), maka JOptionPane digunakan untuk menampilkan pesan "Data Successfully Delete!" kepada pengguna. Selain itu, elemen UI "deleteStaff" juga dikosongkan dengan mengeset teksnya menjadi string kosong.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/94a1accb-2c5c-4ac9-a124-80d37e6383d0)

- Ini adalah blok yang akan dieksekusi jika metode delete mengembalikan false. Dalam konteks ini, blok ini akan dijalankan jika penghapusan data staf gagal. Jika penghapusan gagal, maka pesan "Data Failed" akan ditampilkan kepada pengguna menggunakan JOptionPane.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/96f51284-d36b-49c2-a0e0-71be9ce013bd)

h. menu1
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/122219678/a26ba2e9-7d44-4b01-9bee-854af492496b)

- "private void staffbuttonActionPerformed(java.awt.event.ActionEvent evt) {":
Ini adalah deklarasi dari method staffbuttonActionPerformed yang mengambil satu parameter dari tipe data ActionEvent yang disebut evt. Method ini merupakan event handler yang dipanggil ketika suatu aksi (seperti mengklik tombol) terjadi.

- "menustaff mn = new menustaff();"
  Di dalam method ini, sebuah objek baru dari kelas menustaff dibuat menggunakan konstruktor tanpa parameter. Objek ini diinisialisasi dan disimpan dalam variabel lokal mn.

- "mn.setVisible(true);" :
  Method setVisible(true) dipanggil pada objek mn. Ini berarti mengatur properti objek mn sehingga menjadi terlihat (visible) di antarmuka pengguna. Dalam konteks GUI Java, ini biasanya digunakan untuk menampilkan jendela atau frame pada layar.

- "this.dispose();" :
  adalah sebuah method dari kelas Window yang menghancurkan window (jendela) saat ini. Dalam konteks ini, this.dispose() digunakan untuk menghapus jendela tempat tombol ini berada dari layar setelah jendela menustaff ditampilkan. Ini umumnya digunakan untuk membersihkan sumber daya dan membebaskan memori yang digunakan oleh jendela yang tidak lagi diperlukan.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/127498258/408bb890-470e-4f8d-8ea1-4538c3208cb3)

- "private void studentbuttonActionPerformed(java.awt.event.ActionEvent evt) {" :
  Ini adalah deklarasi dari sebuah metode (fungsi) bernama studentbuttonActionPerformed. Metode ini dipanggil ketika suatu event terjadi pada tombol (button) yang memiliki aksi (action) "studentbutton". Parameter java.awt.event.ActionEvent evt menyatakan bahwa metode ini menerima objek bertipe ActionEvent sebagai parameter.

- "menuMurid mn = new menuMurid();" :
  Membuat objek baru dari kelas menuMurid dan menetapkannya ke variabel mn. Ini adalah langkah untuk membuat instance dari antarmuka pengguna (UI) yang akan ditampilkan.

- "mn.setVisible(true);"
  Mengatur objek menuMurid yang telah dibuat agar terlihat (visible) di layar. Dengan mengatur nilai true, antarmuka pengguna akan ditampilkan.

- "this.dispose();" :
  Menutup antarmuka pengguna saat ini (yang merupakan instance dari kelas yang memiliki metode studentbuttonActionPerformed). Metode dispose() digunakan untuk membebaskan sumber daya yang digunakan oleh antarmuka pengguna, sehingga antarmuka pengguna dapat ditutup dengan benar.
  
![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/127498258/4d6881f2-56d6-4a45-a86d-8f5f82188dbb)

- "private void classbuttonActionPerformed(java.awt.event.ActionEvent evt) {" :
  Ini adalah deklarasi dari sebuah metode (fungsi) bernama classbuttonActionPerformed. Metode ini dipanggil ketika suatu event terjadi pada tombol (button) yang memiliki aksi (action) "classbutton". Parameter java.awt.event.ActionEvent evt menyatakan bahwa metode ini menerima objek bertipe ActionEvent sebagai parameter.

- "menuKelas mc = new menuKelas();" :
  Membuat objek baru dari kelas menuKelas dan menetapkannya ke variabel mc. Ini adalah langkah untuk membuat instance dari antarmuka pengguna (UI) yang akan ditampilkan.

- "mc.setVisible(true);":
  Mengatur objek menuKelas yang telah dibuat agar terlihat (visible) di layar. Dengan mengatur nilai true, antarmuka pengguna akan ditampilkan.

- "this.dispose();":
  Menutup antarmuka pengguna saat ini (yang merupakan instance dari kelas yang memiliki metode classbuttonActionPerformed). Metode dispose() digunakan untuk membebaskan sumber daya yang digunakan oleh antarmuka pengguna, sehingga antarmuka pengguna dapat ditutup dengan benar.

![image](https://github.com/PA-Capstone-25/PA-Capstone/assets/127498258/626d7fe7-ccf2-4898-bc6a-c9358e80d258)

- 
