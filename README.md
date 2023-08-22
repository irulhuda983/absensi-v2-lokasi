## Cara Konfigurasi Aplikasi Absensi V.2

- Buat Folder dengan nama (absensi) di C:\xampp\htdocs\absensi.v2-location
- Lalu Extrak dalam folder tersebut.
- Buat Database dangan nama (absensi) dan import database absensi_foto.sql pada folder (Database).
- Setelah Berhasil Inport Silahkan Setting Url

  - Buka Databasenya (absensi_v2_lokasi) -> lalu pilih tabel site :
  - Silahkan ubah fiel(site_url)nya sesuakan dengan alamat web kalian.

  - Example :
  - Localhost : http://localhost/absensi.v2-location
  - Online : https://domain.com

- Setting Koneksi Database

  - Buka Folder sw-library -> lalu buka file config.php
  <p>$DB_HOST 	= "localhost";</p>
  <p>$DB_USER = "root";</p>
  <p>$DB_PASSWD  	= "";</p>
  <p>$DB_NAME = "absensi_v2_lokasi";</p>
  <p>Sesuaikan koneksi database kalian, jika di localhost tidak perlu menambah password dan user, <br>Jika kalian hosting silahkan sesuaikan dengan username, nama database, dan password hosting kalian</p>

- Setting Konfirgurasi Google

  - Buka Folder sw-library - > lalu buka file google-config.php
  <p>$client_id = ''; </p>
  <p>$client_secret = ''; </p>
  <p>Silahkan sesuaikan Cliend ID dan Client Secret Google Anda bisa langsung buat melalui link di bawah ini https://console.cloud.google.com/apis/dashboard?hl=ID</p>

- Password Admin (alamatweb/sw-admin) dihalaman url web untuk masuk ke halaman admin

```bash
Username : Widodo
Password : admin123
```

## DEMO LOCALHOST

## USER

```bash
url : http://localhost/absensi
Email : swidodo.com@gmail.com
Pass : user12345
```

## ADMIN

```bash
url : http://localhost/absensi/sw-admin
User : Widodo
Pass : admin123
```
