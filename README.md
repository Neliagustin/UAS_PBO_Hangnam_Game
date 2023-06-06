# UAS_PBO_Hangnam_Game
Source Code dan penjelasan hangnam game
Anggota Kelompok :

Zahrah Hafizah Fakhri (G1A022046)
Neli Agustin (G1A022048)
Kevin Taqwa Abdiansyah (G1A022078)
Membuat Game Hangman.

Penjelasan Kode Secara Singkat

Kode pertama mengimpor beberapa modul yang diperlukan, termasuk modul random, time, dan pygame. Selanjutnya, beberapa variabel warna dan ukuran layar didefinisikan. Daftar kata-kata yang akan ditebak juga telah disediakan. Kemudian, layar permainan dibuat menggunakan fungsi pygame.display.set_mode(). Gambar-gambar untuk permainan hangman dimuat ke dalam daftar hangman_images. Suara tebakan benar dan salah juga dimuat menggunakan pygame.mixer.Sound().

Ada beberapa fungsi yang didefinisikan, seperti draw_text() untuk menggambar teks di layar dan draw_hangman() untuk menggambar gambar hangman. Fungsi utama hangman() mengimplementasikan logika permainan. Kata yang akan ditebak dipilih secara acak, dan pemain diberikan kesempatan untuk menebak huruf-hurufnya. Saat pemain menebak huruf dengan benar, huruf tersebut ditampilkan di tempat yang sesuai dalam kata yang harus ditebak. Jika pemain menebak huruf-huruf dengan benar dan berhasil menebak seluruh kata sebelum kesempatan habis, pemain menang. Jika pemain gagal menebak kata sebelum kesempatan habis, pemain kalah.

Setelah permainan selesai, pesan "YOU WIN!" atau "YOU LOSE!" ditampilkan selama beberapa detik sebelum program keluar. Terakhir, permainan dimulai dengan memanggil fungsi hangman(), dan ketika permainan selesai, modul Pygame ditutup dengan pygame.quit().
