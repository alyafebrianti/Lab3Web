# Lab3Web

## Nama : Alya Febrianti
## Kelas : TI.24.A1
## NIM : 312410692
## Tugas Praktikum Lab3Web

## Praktikum Membuat List di HTML
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> HTML Lanjutan</title>
    </head>
    <body>
        <header>
            <h1>
                Membuat List
            </h1>
            <section id="order-list">
                <h2>
                    order-list
                </h2>
                <ol>
                    <li>Pemrograman web</li>
                    <li>Sistem Informasi</li>
                    <li>Basis Data</li>
                </ol>
            </section>
            <section id="unorder-list"> 
                <h2>unorder-list</h2>
                <ul type="square">
                    <li>Jaringan Komputer</li>
                    <li>Struktur Data</li>
                    <li>Algoritma &amp; Pemrograman</li>
                </ul>
            </section>
            <section id="unorder-list">
                <h2>Description List</h2>
                <dl>
                    <dt>Fakultas Teknik</dt>
                    <dd>Teknik Industri</dd>
                    <dd>Teknik Informatika</dd>
                    <dd>Teknik Lingkungan</dd>\
                    <dt>fakultas Ekonomi dan Bisnis</dt>
                    <dd>Akuntasi</dd>
                    <dd>Manajemen</dd>
                    <dd>Bisnis Digital</dd>
                </dl>
            </section>
        </header>
    </body>
</html>
```
## HASIL

<img width="1311" height="1134" alt="Screenshot 2025-10-06 120130" src="https://github.com/user-attachments/assets/ae282271-ae7d-449c-8f92-d13fa1c87ba8" />

## Penjelasan Praktikum Membuat List pada HTML

Dalam praktikum ini, dipelajari cara membuat tiga jenis daftar di HTML:

- Ordered List untuk daftar dengan urutan.

- Unordered List untuk daftar tanpa urutan.

- Description List untuk pasangan istilah dan deskripsi.

Dengan memahami ketiganya, kita dapat menampilkan informasi dalam format yang lebih terstruktur dan mudah dibaca

## Praktikum Membuat List dan Table di HTML

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> HTML Lanjutan </title>
    </head>
    <body>
        <header>
            <h1>Membuat Table</h1>
        </header>
        <table border="1" cellpadding="4" cellspacing="0">
            <thead>
                <tr>
                    <th>NO.</th>
                    <th>Fakultas</th>
                    <th>Pemrogram Studi</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1.</td>
                    <td rowspan="3">Teknik</td>
                    <td>Teknik Informatika</td>
                </tr>
                <tr>
                    <td>2.</td>
                    <td>Teknik Industri</td>
                </tr>
                <tr>
                    <td>3.</td>
                    <td>Teknik Lingkungan</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
```

## HASIL

<img width="974" height="435" alt="Screenshot 2025-10-06 120335" src="https://github.com/user-attachments/assets/27da3494-fcb1-4725-bcaf-54a13f903f88" />


## Penjelasan 

---

# 📘 Lab 3 – Membuat Tabel di HTML

## 🧩 Deskripsi

File **`Lab3_Table.html`** merupakan latihan untuk memahami dan menerapkan **tabel dalam HTML**.
Tujuan dari praktikum ini adalah agar mahasiswa mampu:

* Membuat tabel menggunakan elemen dasar HTML.
* Mengatur struktur tabel menggunakan **header**, **body**, dan **atribut pendukung** seperti `border`, `cellpadding`, `cellspacing`, dan `rowspan`.

## Penjelasan Elemen HTML

### 1. Elemen `<table>`

Digunakan untuk membuat tabel pada halaman web.
Atribut yang digunakan:

* **`border="1"`** → Menentukan ketebalan garis tabel.
* **`cellpadding="4"`** → Menambahkan jarak antara batas sel dan isi sel.
* **`cellspacing="0"`** → Menghilangkan jarak antar sel.

### 2. Elemen `<thead>` dan `<tbody>`

* **`<thead>`** berisi baris judul kolom (biasanya ditampilkan tebal).
* **`<tbody>`** berisi data utama dari tabel.

### 3. Elemen `<tr>`, `<th>`, dan `<td>`

* **`<tr>`** = *table row*, untuk membuat baris.
* **`<th>`** = *table header*, membuat sel judul tabel (biasanya tebal dan rata tengah).
* **`<td>`** = *table data*, isi data dalam tabel.

### 4. Atribut `rowspan`

Digunakan untuk **menggabungkan beberapa baris pada kolom yang sama**.
Contohnya:

```html
<td rowspan="3">Teknik</td>
```

Menandakan bahwa sel “Teknik” mencakup tiga baris di bawahnya.

---

## Hasil Tampilan Tabel

| No. | Fakultas | Program Studi      |
| :-: | :------- | :----------------- |
|  1. | Teknik   | Teknik Informatika |
|  2. |          | Teknik Industri    |
|  3. |          | Teknik Lingkungan  |

---

## Kesimpulan

Melalui latihan ini, dipelajari cara membuat tabel di HTML dengan:

* Struktur `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, dan `<td>`.
* Penggunaan atribut `border`, `cellpadding`, `cellspacing`, dan `rowspan`.

Dengan memahami elemen-elemen tersebut, kita dapat menampilkan data dalam bentuk tabel yang **terstruktur dan mudah dibaca**.


## Praktikum Membuat List, Table, dan Form pada HTML

```html
<!DOCTYPE html> 
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat From</h1>
    </header>
    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea  id="alamat" name="alamat" cols="20" rows="3"></textarea>
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L">
                <label for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P">
                <label for="jk_p">Perempuan</label>
            </p>
            <p>
                <input type="submit" value="login">
            </p>
        </fieldset>
    </form>
    <style>
       form p > label {
            display: inline-block;
            width: 100px;
        }
        form input[type="text"], form textarea {
            border: 1px solid #197a43;
        }
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
        }
    </style>
</body>
</html>
```
## HASIL

<img width="2856" height="845" alt="Screenshot 2025-10-06 120525" src="https://github.com/user-attachments/assets/29056cc7-fdb2-4c22-8cfc-5d6433923c2a" />

## Penjelasan

# 🧾 Lab 3 – Membuat Form di HTML

## 📘 Deskripsi

File **`lab3_from.html`** digunakan untuk mempelajari cara membuat **formulir input data** di HTML. Form ini berfungsi untuk mengumpulkan data pelanggan seperti **nama, alamat, dan jenis kelamin**, kemudian mengirimkannya ke file `proses.php` menggunakan metode **POST**.

---

## 💡 Elemen yang Digunakan

* `<form>` : Membuat area formulir.
* `<fieldset>` dan `<legend>` : Mengelompokkan dan memberi judul pada form.
* `<input type="text">` : Input teks untuk nama.
* `<textarea>` : Kolom teks panjang untuk alamat.
* `<input type="radio">` : Pilihan jenis kelamin.
* `<input type="submit">` : Tombol untuk mengirim data.
* CSS digunakan untuk menata tampilan form agar lebih rapi dan berwarna.

---



## Tugas : Membuat Form Pendaftaran Mahasiswa

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        form p > label {
            display: inline-block;
            width: 120px;
        }
        form input[type="text"], form textarea, select {
            border: 1px solid #197a43;
            padding: 5px;
        }
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #145a32;
        }
    </style>
</head>
<body>
    <header>
        <h1>Form Pendaftaran</h1>
    </header>

    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Mahasiswa</legend>
            
            <!-- Input Nama -->
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama" required>
            </p>

            <!-- Dropdown (Select) -->
            <p>
                <label for="jurusan">Jurusan</label>
                <select id="jurusan" name="jurusan">
                    <option value="">-- Pilih Jurusan --</option>
                    <option value="ar">Arsitektur</option>
                    <option value="ts">Teknik Sipil</option>
                    <option value="ie">Teknik Industri</option>
                    <option value="ti">Teknik Informatika</option>
                    <option value="tl">Teknik Lingkungan</option>
                    <option value="tp">Teknologi Hasil Pertanian</option>
                    <option value="mm">Manajemen</option>
                    <option value="bd">Bisnis Digital</option>
                    <option value="kn">Kewirausahaan</option>
                    <option value="es">Ekonomi Syariah</option>
                    <option value="ai">Akutansi</option>
                    <option value="pgsd">Pendidikan Guru Sekolah Dasar</option>
                    <option value="pgpaud">Pendidikan Guru Pendidikan Anak Usia Dini</option>
                    <option value="bkpi">Bimbingan Dan Konseling Pendidikan Islam</option>
                    <option value="hm">Hukum</option>
                </select>
            </p>

            <!-- Listbox Multiple Selection -->
            <p>
                <label for="hobi">Hobi</label>
                <select id="hobi" name="hobi[]" multiple size="4">
                    <option value="membaca">Membaca</option>
                    <option value="olahraga">Olahraga</option>
                    <option value="musik">Musik</option>
                    <option value="gaming">Gaming</option>
                    <option value="traveling">Traveling</option>
                </select>
            </p>

            <!-- Tombol Submit -->
            <p>
                <input type="submit" value="Kirim Data">
            </p>
        </fieldset>
    </form>
</body>
</html>
```
## HASIL

<img width="950" height="319" alt="image" src="https://github.com/user-attachments/assets/c6f42348-1734-434d-9732-920bbaf4a9d7" />

## Penjelasan 

---

# 🧾 Lab 3 – Form Pendaftaran

## 📘 Deskripsi

File **`lab3_from_tugas.html`** berisi contoh **formulir pendaftaran mahasiswa** menggunakan elemen HTML dasar. Form ini digunakan untuk menginput data seperti **nama, jurusan, dan hobi**, lalu mengirimkannya ke file `proses.php` dengan metode **POST**.

---

## 💡 Elemen yang Digunakan

* `<form>` : Membuat area form.
* `<fieldset>` & `<legend>` : Mengelompokkan data mahasiswa.
* `<input type="text">` : Input nama.
* `<select>` : Dropdown pilihan jurusan.
* `<select multiple>` : Listbox untuk memilih beberapa hobi.
* `<input type="submit">` : Tombol untuk mengirim data.
* CSS digunakan untuk memperindah tampilan form.

---



