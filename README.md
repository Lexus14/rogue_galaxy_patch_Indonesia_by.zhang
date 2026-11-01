# Rogue Galaxy — Patch Bahasa Indonesia (Final)

Fan translation tidak resmi. Tidak berafiliasi dengan Sony maupun Level-5.
Game: Rogue Galaxy (USA) SCUS-97490, Director's Cut, NTSC-U.

Repo ini TIDAK berisi file game. Yang dibagikan hanya file patch (.xdelta)
yang berisi perubahan terjemahan. Kamu wajib memakai ISO original milikmu sendiri.

## Isi versi final ini (v1)

- Dialog cerita: ev01–ev07, ev14–ev18
- Story pembuka: penuh (46 segmen)
- NPC kota: seluruh 93 file (2422 entri unik)
- Database item: skin + seluruh key item (317 item)
- Database item: consumables (41 item, 101 string) + deskripsi senjata (128 deskripsi dari 158 senjata)
- Sengaja tidak digarap: papan hint dan teks movie

## Cara pakai — pakai UniPatcher (Android)

1. Install UniPatcher dari Play Store (gratis).
2. Siapkan dua file: ISO asli Rogue Galaxy versi USA SCUS-97490 yang bersih
   (belum pernah dipatch), dan file patch rogue-galaxy-id-v1.xdelta dari
   halaman Releases repo ini.
3. Buka UniPatcher, lalu pilih:
   - Patch: file rogue-galaxy-id-v1.xdelta
   - Game/ROM: ISO asli kamu
   - Tempat simpan hasil: buat file baru dengan nama lain, misalnya
     "Rogue Galaxy ID.iso" — jangan menimpa ISO asli.
4. Tekan tombol merah di kanan bawah dan tunggu sampai muncul tulisan
   "Patching complete". Jangan tutup aplikasi selama proses berjalan.
5. Mainkan ISO hasil patch di emulator (AetherSX2 / NetherSX2 / ARMSX2).

Catatan: siapkan ruang kosong yang lega, karena prosesnya menyalin file
sementara — ISO asli 7 GB ditambah hasil patch 7 GB. Proses file sebesar ini
memang lebih lama, itu normal, bukan hang.

Verifikasi (opsional): ISO hasil patch yang benar berukuran 6967721984 byte
dan MD5-nya 04fa3ab3a92650dce09b76a7e0d584df. Cek dengan perintah md5sum
di Termux atau terminal.

ISO hasil patch juga bisa dimainkan di emulator PS2 PC — tinggal pindahkan
file ISO hasil patch ke PC dan buka di emulator PS2 PC.

## Kalau patch gagal

- Pastikan ISO-mu versi USA SCUS-97490 (NTSC-U), bukan Europe atau Jepang.
- Pastikan ISO-mu bersih, belum pernah dipatch.
- Pastikan file patch yang dipakai adalah rogue-galaxy-id-v1.xdelta yang utuh
  (247416 byte).

## Update

v1 adalah rilis final terjemahan ini.

## Disclaimer

Patch ini hanya berisi perubahan terjemahan buatan penggemar.
Jangan membagikan ISO hasil patch ke orang lain.
