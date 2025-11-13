# Erwan Majid 06

# Soal 1

Tambahkan nama panggilan Anda pada title app sebagai identitas hasil
pekerjaan Anda

![json](IMG/2.png)

# Soal 2

cobalah akses di browser URI tersebut dengan lengkap seperti ini. Jika menampilkan data JSON, maka Anda telah berhasi

![json](IMG/1.png)

# Soal 3

Jelaskan maksud kode langkah 5 tersebut terkait substring dan catchError!

-substring : Untuk mencegah tampilan teks terlalu panjang di layar saat menampilkan hasil dari API.
Karena hasil Google Books API biasanya sangat panjang (ratusan baris JSON), jadi cukup ditampilkan sebagian

-catchError : digunakan untuk menangani error jika proses getData() gagal — misalnya:
Tidak ada koneksi internet, URL salah,Server API down

-setState : digunakan untuk memperbarui tampilan (UI) setiap kali nilai result berubah — baik saat sukses maupun error. Flutter akan me-render ulang Text(result) di layar dengan isi terbaru

substring(0, 450) membatasi teks dari hasil API supaya tidak terlalu panjang.
catchError menangkap dan menampilkan pesan error jika permintaan API gagal

# Result :

![result](IMG/2.gif)
