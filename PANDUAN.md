# GeoFoto Gizi — Kamera Lapangan (Versi 1)

Kamera berbasis web dengan cap otomatis berisi jam, tanggal, hari, alamat, koordinat GPS,
kegiatan, tempat, nama petugas/dosen, instansi, catatan, logo, dan kode foto.
Tidak perlu login atau server. Semua pengaturan tersimpan di HP masing-masing.

## Pasang di GitHub (±5 menit)
1. Login akun GitHub **jurusan-gizi** → New repository → nama `geofoto` → Public → Create.
2. Klik "uploading an existing file", unggah: `index.html`, `manifest.json`, `sw.js`, dan folder `icons`
   (seret folder icons sekaligus). Klik Commit.
3. Settings → Pages → Branch: main / (root) → Save.
4. Link aplikasi: **https://jurusan-gizi.github.io/geofoto/**

## Cara pakai (untuk dibagikan ke pengguna)
1. Buka link di **Chrome** (Android) atau **Safari** (iPhone). Izinkan Kamera & Lokasi.
2. Pertama kali: isi **Nama** dan **Instansi** (⚙️). Logo instansi opsional.
3. Ketuk baris **📋 kegiatan** di atas → pilih/isi kegiatan, tempat, catatan.
4. Tunggu label **GPS ±… m** berwarna hijau, lalu tekan tombol bulat untuk memotret.
5. Foto langsung tersimpan di folder **Download** dan muncul di **Galeri**.
   iPhone: setelah memotret tekan **Bagikan → Simpan Gambar**.
6. Supaya terasa seperti aplikasi: menu Chrome ⋮ → **Tambahkan ke layar utama** / **Instal aplikasi**.

## Letak keterangan (⚙️ Pengaturan)
- **Bingkai di bawah foto** (bawaan): foto tetap utuh, keterangan ada di panel hijau tua di bawahnya. Wajah dan aktivitas tidak tertutup. Saat membidik, layar kamera tetap bersih.
- **Di atas foto**: model Timemark. Ukuran teks bisa diatur Kecil / Sedang / Besar.

## Blitz (tombol ⚡ di kanan atas)
Ketuk berulang untuk berganti mode:
- **⚡** mati
- **⚡A** menyala saat memotret
- **🔦** selalu menyala, khusus kamera belakang (berguna untuk memotret di ruangan gelap)

Kamera depan memakai **layar putih terang** sebagai lampu. Di iPhone, browser tidak mengizinkan akses lampu
kamera, jadi yang dipakai juga layar putih.

## Catatan
- Tanpa sinyal internet: kamera, jam, dan koordinat tetap jalan. Alamat tidak muncul
  (butuh internet), jadi yang tercetak hanya koordinat.
- Lokasi GPS juga ditanam di data foto (EXIF), sehingga foto bisa tampil di peta Galeri / Google Photos.
- Kode foto dibuat dari waktu, koordinat, nama, dan kegiatan. Fungsinya sebagai penanda unik
  tiap foto, bukan jaminan anti-edit.
- Alamat diambil dari OpenStreetMap (gratis). Nama desa/kecamatan kadang kurang tepat di daerah
  terpencil. Gunakan kolom **Tempat** untuk menuliskan nama lokasi yang benar.
- Etika: minta izin sebelum memotret ibu, balita, dan warga; foto sasaran tidak untuk media sosial.
