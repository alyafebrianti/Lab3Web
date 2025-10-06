# Lab3Web

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

<img width="1311" height="1134" alt="Screenshot 2025-10-06 120130" src="https://github.com/user-attachments/assets/ae282271-ae7d-449c-8f92-d13fa1c87ba8" />




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

<img width="974" height="435" alt="Screenshot 2025-10-06 120335" src="https://github.com/user-attachments/assets/27da3494-fcb1-4725-bcaf-54a13f903f88" />



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

<img width="2856" height="845" alt="Screenshot 2025-10-06 120525" src="https://github.com/user-attachments/assets/29056cc7-fdb2-4c22-8cfc-5d6433923c2a" />
