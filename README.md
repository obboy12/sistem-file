# sistem-file

# LAPORAN HASIL TUGAS
| Nama        | Abdullah Husin |
|--------------|------------|
| NIM        | 09030582327103 |
| Program Studi | Teknik Komputer |

1. Lihat peralatan I/O, character device, yang ada pada system komputer

![Gambar WhatsApp 2025-02-24 pukul 02 05 42_d0e789ff](https://github.com/user-attachments/assets/f54d6657-a138-4fd7-bdbf-a976ad3ad802)
Menampilkan daftar perangkat character device pada sistem Linux yang ada di direktori /dev. Perintah ini membantu melihat perangkat seperti keyboard, mouse, dan terminal (/dev/tty), yang beroperasi dengan data berbasis karakter.

2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.
![Gambar WhatsApp 2025-02-24 pukul 02 05 43_39146a85](https://github.com/user-attachments/assets/110b9355-f696-4326-b5e2-1b93c9e9e202)

Membuat tiga subdirektori dalam direktori latihan5 sekaligus, tanpa harus menjalankan perintah mkdir tiga kali. Opsi -p memastikan bahwa jika latihan5 belum ada, maka akan dibuat terlebih dahulu.

3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.
![Gambar WhatsApp 2025-02-24 pukul 02 05 43_b48c1875](https://github.com/user-attachments/assets/5b96d863-112e-4c38-a387-19aa26f8ce18)



Membuat file dataku di dalam direktori januari yang berisi informasi pribadi. Menyalin file dataku dari januari ke februari dan maret, sehingga ketiga direktori memiliki file yang sama.

4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.
![Gambar WhatsApp 2025-02-24 pukul 02 25 39_4eb09ae3](https://github.com/user-attachments/assets/73cdac7a-e70c-4ebc-a1c0-f5d3e72f8a7c)


Mengubah izin file dataku sehingga, Memungkinkan semua pengguna (group dan others) untuk mengedit isi file.

5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.
![Gambar WhatsApp 2025-02-24 pukul 02 25 56_b442a5c0](https://github.com/user-attachments/assets/4503c943-bc1c-4139-ba43-7b69b963d09b)


Kegunaan, Hanya pemilik file yang bisa mengedit, tetapi orang lain bisa membaca dan menjalankan file jika diperlukan.

6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.
![Gambar WhatsApp 2025-02-24 pukul 02 26 13_e283140a](https://github.com/user-attachments/assets/129a1f0c-a74f-4f69-84c3-96c0b54edfd1)


Semua pengguna dapat membaca, menulis, dan mengeksekusi file, tanpa batasan.

7. Hapuslah direktori maret.
![Gambar WhatsApp 2025-02-24 pukul 02 05 43_27f6d942](https://github.com/user-attachments/assets/52a6b6c5-9d17-49b2-b8c6-bdff3e8e0bdf)


Menghapus latihan5/maret dan memastikan tidak ada sisa file atau subdirektori di dalamnya.

8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.
![Gambar WhatsApp 2025-02-24 pukul 02 05 44_b5b82017](https://github.com/user-attachments/assets/3a7c09ab-d30e-4dfb-a032-b9cd3359cea6)


Mencoba membuat subdirektori lalalostyou di dalam februari, yang sebenarnya gagal karena tidak ada izin menulis.Namun, jika ingin membuat lalalostyou, izin harus diubah menggunakan chmod 750 agar pemilik bisa menulis.

9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya?
![Gambar WhatsApp 2025-02-24 pukul 02 05 44_b5b82017](https://github.com/user-attachments/assets/a60cdf37-6532-4d7d-b1da-d23331967b81)


Mengatur izin default untuk file baru agar lebih ketat dalam keamanan. Setelah membuat file baru (dataku_baru), perintah ls -l digunakan untuk mengecek apakah izin yang diberikan sesuai dengan umask.

10. Buatlah link dari file dataku ke file dataku.kemarin dengan perintah list perhatikan berapa link yang terjadi?
![Gambar WhatsApp 2025-02-24 pukul 02 05 45_14039973](https://github.com/user-attachments/assets/18ec8a08-ec60-4f82-9d41-dc146cebd988)


Hard link adalah file yang merujuk ke inode yang sama di sistem file. setelah membuat dua hard link, perintah ls -l akan menunjukkan bahwa file dataku, dataku.ini, dan dataku.juga memiliki jumlah link yang meningkat. Memastikan bahwa semua hard link merujuk ke file yang sama dan berbagi konten yang sama.

KESIMPULAN
Dalam praktikum ini, saya telah mempelajari berbagai konsep dasar dalam pengelolaan sistem file di Linux, mulai dari melihat perangkat I/O, membuat dan mengatur izin direktori, hingga memodifikasi kepemilikan dan membuat link file. Latihan-latihan ini membantu memahami bagaimana sistem operasi menangani file dan hak aksesnya, yang sangat penting untuk administrasi sistem. Dengan pemahaman ini, saya bisa lebih mudah mengelola file, menjaga keamanan data, serta mengoptimalkan penggunaan sistem Linux dalam berbagai skenario.
