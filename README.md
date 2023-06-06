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


![IMG-20230606-WA0007](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/284888d7-3fa1-4f43-a3b3-2cf9a1d72324)
![IMG-20230606-WA0011](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/44cf36d9-65cd-48d4-a07d-9cb3c17f27f2)
![IMG-20230606-WA0009](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/ea8131dc-e689-4609-a0a1-7380869258dc)
![IMG-20230606-WA0006](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/22c0932d-ad56-4db9-926f-7e37bdff19cd)
![IMG-20230606-WA0008](https://github.com/Neliagustin/UAS_PBO_Hangnam_Game/assets/129770165/dd18716a-38eb-48bd-a082-1012a5241ccd)
