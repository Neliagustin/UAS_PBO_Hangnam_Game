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

Tampilan Awal:
![IMG-20230606-WA0007](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/160d07fb-01d9-40ed-b4d6-59747eacfd5c)

Tampilan Tahap Menebak benar 1 huruf:

Tampilan tahap menebak benar 2 huruf:
![IMG-20230606-WA0009](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/6954cb42-b83c-429b-9fb3-8a9904da779e)

tampilan muncul kata win jika benar:
![IMG-20230606-WA0008](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/c8b16472-fb47-4123-aa2a-8422124b7393)



![IMG-20230606-WA0006](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/38125f40-54a5-4c0c-9338-8579da88f87e)

tampilan muncul kata lose jika salah:
![IMG-20230606-WA0011](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/c1b05b4b-3058-46ff-90e1-0a16d60c5974)

