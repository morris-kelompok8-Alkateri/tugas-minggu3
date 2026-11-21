Aplikasi konsol sederhana untuk membantu mahasiswa mencatat kebiasaan kesehatan
selama sesi aplikasi berjalan. Aplikasi dibuat dengan Python dan tidak
membutuhkan paket tambahan.

## Tujuan

Tujuan pembuatan aplikasi ini adalah menyediakan sarana sederhana bagi
mahasiswa untuk lebih memperhatikan kebiasaan sehari-hari yang berhubungan
dengan kesehatan, seperti aktivitas fisik, konsumsi air, dan durasi tidur.
Aplikasi ini juga memberikan tips kesehatan umum dan ringkasan dari catatan
yang dimasukkan pengguna.

Aplikasi ini bersifat edukatif, bukan alat diagnosis atau pengganti saran
tenaga kesehatan. Data hanya disimpan sementara di memori dan akan hilang
ketika aplikasi ditutup.

## Fitur

1. Login sesi menggunakan NIM, nama, dan program studi.
2. Mencatat jenis serta durasi aktivitas fisik.
3. Mencatat jumlah konsumsi air.
4. Mencatat durasi tidur terakhir.
5. Melihat tips kesehatan untuk mahasiswa.
6. Mengakses menu CKG untuk mencatat rencana janji puskesmas, permintaan
   konsultasi rujukan, menghitung IMT, mengisi survei kesehatan, melihat status,
   dan membaca informasi CKG.
7. Melihat ringkasan catatan dan logout.

Menu CKG hanya menyimpan rencana dan permintaan secara lokal selama aplikasi
berjalan. Aplikasi tidak menghubungi puskesmas dan tidak membuat janji atau
rujukan resmi. Hubungi fasilitas kesehatan secara langsung; keputusan rujukan
berada pada tenaga kesehatan.

Program studi yang tersedia:

- D3 Teknik Informatika
- D4 1A Teknik Informatika
- D4 1B Teknik Informatika

Pilihan puskesmas pada menu CKG:

- Puskesmas Sariwangi
- Puskesmas Bandung
- Puskesmas Cimahi

## Struktur file

- `main.py` — titik masuk program dan alur login.
- `data.py` — pilihan program studi, validasi input, dan data sesi.
- `kesehatan.py` — menu, pencatatan kesehatan, tips, dan ringkasan.
- `ckg.py` — submenu CKG, pencatatan rencana janji dan permintaan konsultasi,
  kalkulator IMT, serta survei kesehatan.

## Cara menjalankan

Pastikan Python 3 sudah terpasang, kemudian jalankan dari folder aplikasi:

```bash
python main.py
```

## Anggota kelompok

1. Brian Januarsa
2. Muhammad Fikry Auladi Insani
3. Intan Cahya Putri
4. Muhammad Idzhar Arsalan
5. AL-AKBARI (yang akun shafamecca6-beep)
6. Dary Darwisy Ramdhani
7. Muhammad Hasfi A P

==================
TERIMAKASIH BANYAK
==================
