# 📘 Praktikum 1 - CodeIgniter 4 (MVC)

## 👤 Data Mahasiswa

* Nama: **Naufal Rafi Haryanto**
* NIM: **312410118**
* Kelas: **I241A**

---

## 🎯 Tujuan Praktikum

Praktikum ini bertujuan untuk:

* Memahami konsep dasar framework
* Memahami arsitektur **MVC (Model-View-Controller)**
* Mengimplementasikan aplikasi web sederhana menggunakan **CodeIgniter 4**

---

## ⚙️ Tools yang Digunakan

* XAMPP
* Visual Studio Code
* CodeIgniter 4

---

## 📥 Langkah Instalasi

1. Download CodeIgniter 4 dari website resmi
2. Extract ke folder:

   ```
   C:\xampp\htdocs\lab11_ci\
   ```
3. Rename folder menjadi:

   ```
   ci4
   ```
4. Jalankan server:

   ```
   php spark serve
   ```
5. Akses di browser:

   ```
   http://localhost:8080
   ```

---

## 🧠 Konsep MVC

* **Model** → Mengelola data
* **View** → Menampilkan tampilan
* **Controller** → Mengatur alur program

---

## 📁 Struktur Folder

```
ci4/
├── app/
│   ├── Controllers/
│   │   └── Page.php
│   ├── Views/
│   │   ├── home.php
│   │   ├── about.php
│   │   ├── contact.php
│   │   ├── artikel.php
│   │   └── template/
│   │       ├── header.php
│   │       └── footer.php
├── public/
│   └── style.css
```

---

## 🔧 Routing

File: `app/Config/Routes.php`

```php
$routes->get('/', 'Page::home');
$routes->get('/about', 'Page::about');
$routes->get('/contact', 'Page::contact');
$routes->get('/artikel', 'Page::artikel');
```

---

## 🎮 Controller

Controller digunakan untuk mengatur logika aplikasi dan menghubungkan antara model dan view.

Contoh: `Page.php`

---

## 🎨 View & Template

View digunakan untuk menampilkan halaman:

* Home
* About
* Contact
* Artikel

Template:

* `header.php`
* `footer.php`

---

## 🌐 Hasil Tampilan

### 🏠 Home

(Tambahkan screenshot di sini)

### 👤 About

(Tambahkan screenshot di sini)

### 📞 Contact

(Tambahkan screenshot di sini)

### 📰 Artikel

(Tambahkan screenshot di sini)

---

## ⚠️ Kendala yang Dihadapi

* Error 404 karena kesalahan routing
* Kesalahan penggunaan path URL
* Struktur folder belum sesuai

---

## ✅ Solusi

* Menggunakan `php spark serve`
* Memastikan routing sudah benar
* Menyusun file sesuai struktur MVC

---

## 🏁 Kesimpulan

Dengan praktikum ini, mahasiswa dapat memahami konsep dasar MVC serta mampu membuat aplikasi web sederhana menggunakan CodeIgniter 4.

---
