# Sistem Informasi Supervisi Akademik Guru

Repository ini merupakan proyek tugas mata kuliah **Supervisi Pendidikan**. Proyek ini berupa website sederhana untuk membantu proses administrasi dan penilaian supervisi akademik guru.

## Identitas Pengembang

| Keterangan | Informasi |
|---|---|
| Nama | **Syamil Sayyafi** |
| Kelas | **5E** |
| Mata Kuliah | **Supervisi Pendidikan** |
| Nama Proyek | Sistem Informasi Supervisi Akademik Guru |

## Deskripsi Proyek

Sistem Informasi Supervisi Akademik Guru merupakan aplikasi berbasis web sederhana yang dirancang untuk membantu pencatatan data guru, pelaksanaan penilaian supervisi akademik, serta penyimpanan dan peninjauan hasil supervisi.

Aplikasi ini dibuat sebagai media penerapan dan pengembangan pemahaman mengenai supervisi pendidikan, khususnya dalam pemanfaatan teknologi untuk mendukung kegiatan supervisi akademik.

## Tujuan

- Memahami penerapan teknologi informasi dalam kegiatan supervisi pendidikan.
- Mempermudah pencatatan identitas guru yang disupervisi.
- Menyediakan contoh instrumen penilaian kegiatan pembelajaran.
- Membantu menghitung dan menampilkan hasil penilaian supervisi.
- Mendokumentasikan hasil supervisi secara sederhana.

## Fitur

1. **Dashboard** — menampilkan ringkasan jumlah guru, jumlah supervisi, nilai rata-rata, dan jumlah hasil dengan predikat Sangat Baik.
2. **Data Guru** — menambahkan, melihat, dan menghapus data guru.
3. **Penilaian Supervisi** — mengisi identitas supervisi dan memberikan skor pada indikator penilaian.
4. **Perhitungan Nilai Otomatis** — menghitung nilai akhir berdasarkan skor indikator.
5. **Hasil Supervisi** — melihat riwayat, rincian penilaian, catatan supervisor, dan menghapus hasil supervisi.
6. **Cetak Hasil** — mencetak halaman hasil supervisi melalui fitur cetak browser.

## Teknologi yang Digunakan

- **HTML5** — menyusun struktur halaman web.
- **CSS3** — mengatur tampilan dan tata letak.
- **JavaScript** — menjalankan navigasi, pengelolaan data, dan perhitungan nilai.
- **Local Storage** — menyimpan data pada browser yang digunakan.

Proyek ini dibuat dalam satu file HTML tanpa memerlukan framework atau database eksternal.

## Struktur Proyek

```text
supervisi-akademik-guru/
└── index.html
```

## Cara Menjalankan

1. Unduh atau clone repository ini ke komputer.
2. Buka folder proyek menggunakan Visual Studio Code.
3. Buka file `index.html`.
4. Jalankan file melalui browser, atau gunakan ekstensi **Live Server** di Visual Studio Code.
5. Website siap digunakan.

### Menjalankan dengan Git

```bash
git clone https://github.com/USERNAME/supervisi-akademik-guru.git
cd supervisi-akademik-guru
```

Ganti `USERNAME` dengan username GitHub pemilik repository.

## Alur Penggunaan

1. Buka halaman **Data Guru** dan masukkan identitas guru.
2. Buka halaman **Penilaian**.
3. Pilih guru yang akan disupervisi.
4. Isi nama supervisor dan tanggal supervisi.
5. Berikan skor pada seluruh indikator penilaian.
6. Periksa nilai akhir dan masukkan catatan supervisor jika diperlukan.
7. Simpan hasil supervisi.
8. Buka halaman **Hasil Supervisi** untuk melihat rincian atau mencetak hasil.

## Ketentuan Penilaian

Aplikasi menyediakan contoh 10 indikator penilaian dengan skala skor 1–4:

| Skor | Keterangan |
|---:|---|
| 1 | Kurang |
| 2 | Cukup |
| 3 | Baik |
| 4 | Sangat Baik |

Nilai akhir dihitung menggunakan rumus:

```text
Nilai Akhir = (Total Skor yang Diperoleh / Total Skor Maksimal) × 100
```

Predikat yang digunakan dalam aplikasi:

| Rentang Nilai | Predikat |
|---:|---|
| 90–100 | Sangat Baik |
| 80–89,99 | Baik |
| 70–79,99 | Cukup |
| Di bawah 70 | Perlu Pembinaan |

**Catatan:** Indikator, skala, dan rentang predikat pada aplikasi merupakan contoh untuk keperluan proyek. Dalam penggunaan nyata, semuanya perlu disesuaikan dengan instrumen dan ketentuan supervisi yang berlaku di institusi pendidikan.

## Keterbatasan

- Data disimpan secara lokal pada browser melalui Local Storage.
- Data tidak otomatis tersinkronisasi antarperangkat atau antarbrowser.
- Aplikasi belum menggunakan database dan sistem autentikasi pengguna.
- Fitur cetak menggunakan fasilitas cetak browser; hasil PDF dapat dipilih melalui pengaturan printer.
- Instrumen penilaian masih berupa contoh dan belum tentu mewakili instrumen resmi suatu sekolah atau lembaga pendidikan.

## Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan:

- Menambahkan identitas dan logo sekolah.
- Menambahkan fitur login untuk administrator dan supervisor.
- Menggunakan database agar data tersimpan secara terpusat.
- Menambahkan ekspor laporan ke PDF.
- Menambahkan tanda tangan supervisor dan kepala sekolah.
- Menyesuaikan instrumen dengan pedoman supervisi akademik yang digunakan lembaga.

## Penutup

Proyek ini disusun sebagai bagian dari tugas mata kuliah **Supervisi Pendidikan**. Diharapkan aplikasi sederhana ini dapat menjadi media pembelajaran dalam memahami proses supervisi akademik serta pemanfaatan teknologi informasi untuk mendukung administrasi pendidikan.

---

**Dibuat oleh:** Syamil Sayyafi  
**Kelas:** 5E  
**Mata Kuliah:** Supervisi Pendidikan
