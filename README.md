# Tasya Tiqa - Portofolio Digital

Website portofolio pribadi Tasya Tiqa dengan tampilan responsif, galeri karya, daftar proyek, pengalaman, pendidikan, dan informasi kontak.

## Demo

Tambahkan URL deployment di sini setelah situs dipublikasikan:

`https://username.github.io/nama-repository/`

## Fitur

- Landing page portofolio responsif
- Navbar hamburger untuk semua ukuran layar
- Section tentang saya, keahlian, proyek, galeri, pengalaman, pendidikan, dan kontak
- Galeri dengan aset lokal dari folder `galeri`
- Animasi scroll menggunakan AOS
- Ikon menggunakan Lucide
- Font DM Sans dan Playfair Display dari Google Fonts
- Tidak membutuhkan proses build atau backend

## Struktur Folder

```text
.
├── index.html
├── foto.jpeg
├── galeri/
│   ├── galeri1.jpeg
│   └── galeri2.jpeg
└── project/
    └── project1.jpg
```

## Menjalankan Secara Lokal

### Menggunakan XAMPP

1. Letakkan folder proyek di `C:\xampp\htdocs\tiqa`.
2. Jalankan Apache dari XAMPP Control Panel.
3. Buka alamat berikut di browser:

   `http://localhost/tiqa/`

### Menggunakan server lokal sederhana

Jika Python tersedia, jalankan dari folder proyek:

```bash
python -m http.server 8000
```

Kemudian buka:

`http://localhost:8000/`

Membuka `index.html` secara langsung juga dapat digunakan, tetapi server lokal lebih disarankan untuk meniru kondisi deployment.

## Deployment

### GitHub Pages

1. Buat repository baru di GitHub.
2. Upload `index.html`, `foto.jpeg`, folder `galeri`, dan folder `project`.
3. Buka **Settings > Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch utama dan folder `/ (root)`, lalu klik **Save**.
6. Tunggu proses deployment selesai, kemudian buka URL yang diberikan GitHub.

### Netlify

1. Login ke Netlify.
2. Pilih **Add new site > Import an existing project** untuk repository Git, atau gunakan drag-and-drop folder proyek.
3. Karena proyek ini statis, kosongkan perintah build.
4. Gunakan folder publik/root proyek sebagai publish directory.
5. Deploy situs.

### Vercel

1. Login ke Vercel dan pilih **Add New Project**.
2. Import repository proyek.
3. Pilih framework **Other** jika diminta.
4. Kosongkan build command dan output directory.
5. Klik **Deploy**.

## Checklist Sebelum Deploy

- Pastikan nama file dan huruf besar-kecil path aset sesuai.
- Pastikan semua gambar berada di dalam repository.
- Ganti `email@anda.com` dengan alamat email yang benar.
- Ganti tautan media sosial yang masih menggunakan `#`.
- Ganti tautan **Kode Sumber** dan proyek beta yang masih menggunakan `#`.
- Tambahkan file `project/project2.jpg` atau ubah referensinya jika proyek kedua belum memiliki gambar.
- Uji navbar hamburger, tautan galeri, dan gambar pada perangkat desktop serta mobile.
- Periksa URL proyek eksternal dan tautan Instagram sebelum publikasi.

## Teknologi

- HTML5
- CSS3
- JavaScript
- AOS.js
- Lucide Icons
- Google Fonts

## Lisensi

Proyek ini merupakan portofolio pribadi Tasya Tiqa. Hubungi pemilik proyek sebelum menggunakan aset visual atau kode untuk kebutuhan lain.
