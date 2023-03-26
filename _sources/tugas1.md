### Nama : Qoid Rif'at

### NIM : 210411100160



> Daftar aplikasi yang dibutuhkan adalah sebagai berikut:

1.  Postgresql
2.  Xammp
3.  Power Bi
4.  Membuat akun di elephantsql.com

> Langkah-langkah untuk mengumpulkan data dari beberapa sumber database

### 1. Database menggunakan server cloud di postgres 

> **Langkah pertama** membuat intance pada akun elephantsql.com yang diberi nama pendatab yang akan digunakan untuk server cloud.
>
> ![pendata1](C:\Users\USER\Downloads\pendata1.png)
>
> 
>
> **Langkah kedua** Menghubungkan server dari elephantsql.com ke postgress dengan cara :

1.  klik kanan pada server \> klik menu registrasi \> klik server

> ![pendata2](C:\Users\USER\Downloads\pendata2.png)

2.  memberi nama server

> ![pendata3](C:\Users\USER\Downloads\pendata3.png)

3. mengisi bagian connection sesuai dengan server pada intance Pendata B akun elephantsql.com 	

   ​	a. host name/address diisi dengan server 

   ​	b. maintenance database dan username diisi dengan user & default database 

   ​	c. password diisi dengan password yang tertera pada detail intance elephant

   ​	d. kemudian klik tombol save, maka server pendatab berhasil dibuat

   ![pendata4](C:\Users\USER\Downloads\pendata4.png)

> 
>
> **Langkah Ketiga** membuat table data iris 
>
> - [ ] membuka database berdasarkan nama user & default database dari intance akun elepant yaitu dpoemens
>
> ![pendata5](C:\Users\USER\Downloads\pendata5.png)
>
> - [ ] klik kanan pada menu table dan pilih menu Query Tool
>
>   ![pendata6](C:\Users\USER\Downloads\pendata6.png)
>
> - [ ] pada bagian query tuliskan query create table dari data yang ingin dimasukan
>
>
> ![pendata7](C:\Users\USER\Downloads\pendata7.png)
>
> - [ ] kemudian run code tersebut dan refresh pada menu table \> klik kanan \> klik refresh untuk memunculkan table iris
>
>   ![pendata8](C:\Users\USER\Downloads\pendata8.png)



### 2. Database menggunakan localhost di postgress

> **Langkah pertama** membuat server bernama localpendatab, kemudian untuk connectionnya di isi di isi seperti dibawah ini dengan menyertakan password dari postgres
>
> ![pendata10](C:\Users\USER\Downloads\pendata10.png)
>
> **Langkah selanjutnya** membuat table data iris

1. membuat database terlebih dahulu bernama databaseiris

   ![pendata11](C:\Users\USER\Downloads\pendata11.png)

2. membuat table iris dengan cara yang sama dengen pembuatan table iris server cloud

3. pembuatan server local postgres yang berisi table iris telah berhasil dibuat



### 3. Power BI

- [ ] **Data iris yang terdapat pada database localhost**

> **Langkah pertama** export table iris menjadi ﬁle csv
>
> ![pendata12](C:\Users\USER\Downloads\pendata12.png)
>
> **Langkah kedua** bukalah aplikasi power bi, lalu masukan file csv tadi dengan cara klik get data kemudian klik text/csv
>
> ![pendata13](C:\Users\USER\Downloads\pendata13.png)
>
> **Langkah ketiga,** jika sudah berhasil memasukan data csv maka klik load
>
> ![pendata14](C:\Users\USER\Downloads\pendata14.png)
>
> **Langkah keempat,** jika sudah di load maka pada bagian kanan layar terdapat data iris yang harus di centang kemudian pilih menu bagan Clustered column chart untuk menampilkan data yang sudah di load tadi \> selesai
>
> ![pendata15](C:\Users\USER\Downloads\pendata15.png)

- [ ] **Data iris yang terdapat pada database cloud postgres**

> **Langkah pertama,** klik menu getdata \> klik more \> cari postgress database \> klik postgress database \> klik connect
>
> ![pendata16](C:\Users\USER\Downloads\pendata16.png)
>
> **Langkah kedua,** memasukan nama server sesuai dengan yang terdapat di elephantsql.com yaitu mel.db.elephantsql.com dan nama databasenya disesuaikan dengan posgress \> klik ok
>
> ![pendata17](C:\Users\USER\Downloads\pendata17.png)
>
> kemudian mengisi user name dan password yang terdapat pada akun elephantsql.com \> klik connect
>
> ![pendata18](C:\Users\USER\Downloads\pendata18.png)
>
> kemudian langkah-langkah selanjutnya sama dengan cara sebelumnya \> setelah berhasil connect \> load \> selesai

- [ ] **Data iris yang terdapat pada database MYSQL**

> **Langkah pertama,** klik menu getdata \> klik more \> cari MYSQL database \> klik MYSQL database \> klik connect
>
> ![pendata22](C:\Users\USER\Downloads\pendata22.png)
>
> kemudian mengisi nama server dengan localhost diikuti dengan port mysql pada XAMPP dan database sesuai dengan nama database yang terdapat di phpmyadmin
>
> ![pendata23](C:\Users\USER\Downloads\pendata23.png)
>
> jika sudah tertampil seperti di bawah ini maka klik load
>
> ![pendata24](C:\Users\USER\Downloads\pendata24.png)
>
> jika sudah tertampil di power BI maka pilihlah tampilan visual nya sebagai table maka terlihat seperti di bawah ini \> selesai
>
> ![pendata25](C:\Users\USER\Downloads\pendata25.png)

### 4. Data iris csv ke PHPMYadmin

> **Langkah pertama,** menyalakan apache dan sql di XAMPP
>
> ![pendata19](C:\Users\USER\Downloads\pendata19.png)
>
> **Langkah kedua** membuka phpmyadmin \> membuat database baru bernama pendatairis
>
> **Langkah ketiga** mengimport csv ke PHPmyadmin
>
> ![pendata20](C:\Users\USER\Downloads\pendata20.png)
>
> jika data tertampil seperti dibawah ini maka telah berhasil.
>
> ![pendata21](C:\Users\USER\Downloads\pendata21.png)
