Final Project ARC - TTS

i. Deskripsi Singkat
  Website  Teka Teki Silang (TTS) ini dibuat dalam rangka menyelesaikan tugas final project ARC yang diberikan pada Day-5 ARC. TTS yang kami buat terdiri dari 3 level yang mana  tema untuk pertanyaan dan jawaban yang kita pakai adalah "Networking" sesuai dengan materi yang disampaikan pada Day-4 ARC. Website TTS ini memiliki stopwatch yang akan menghitung seberapa cepat pemain menyelesaikan ketiga level yang disediakan. Pemain perlu mengisi TTS yang kosong dengan cara memencet tombol "PILIH" pada pertanyaan yang ingin dijawab. Jika jawaban benar, kolom tersebut akan terkunci dan berubah dalam keadaan disabled. Setelah pemain menyelesaikan semua pertanyaan pada level, tombol "NEXT LEVEL" akan muncul dibawah teka teki silang untuk berganti ke level selanjutnya. Saat pemain menyelesaikan ketiga level, lama pemain menyelesaikan TTS akan tercatat di leaderboard.
  
ii. Cara Instalasi
  1. Pergi ke link github.com/naufalanargya/FinalProjectTTS dan download dalam zip. Ekstrak ke folder yang anda mau di komputer anda.
  2. Buka folder di vscode
  3. Buka terminal dan jalankan ```npm install``` setelah clone dari repo untuk install semua dependencies
  4. Setting mongoDB connection pada file ```.env```, jika belum download bisa download terlebih dahulu.
  5. Jalankan ```npm start``` untuk menjalankan server

iii. Fitur yang dibuat dan teknologi yang digunakan
Create : Membuat username pada setelah menyelesaikan TTS
Read : Program akan membaca jawaban TTS untuk membuka tombol NEXT LEVEL, hingga akhirnya waktu pengerjaan TTS akan dibaca dan tercantum di leaderboard
Delete : Penghapusan rekor di leaderboard 
Update : Leaderboard akan selalu terupdate saat ada username yang mengerjakan lebih cepat, dan saat terjadi pengapusan rekor akan terupdate.

iv. Nama + Nim Anggota serta pembagian tugas
- Naufal Bhanu A (16520102) : Membuat html dan js TTS,TTS2,TTS3 dan navbar 
- Farrel Farandieka (16520295) : Memasukkan file ke database mongodb, membuat page final dan leaderboard, server.js
- M Rakha Wiratama (16520462) : Membuat html dan js stopwatch serta logika penambahan waktu stopwatch
- Febryola Kurnia P (16520050) : Mengatur tampilan page dan efek efek tambahan lain
- Jeremy Evan (16620367) : Merapihkan html tiap page, merapihkan tampilan page

v. Link
Github : github.com/naufalanargya/FinalProjectTTS
Link Web : 
