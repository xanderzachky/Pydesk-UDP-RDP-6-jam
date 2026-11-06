# Pydesk

> RDP ringan berbasis Tailscale untuk coding dan game ringan — praktis, cepat, dan siap dipakai.

## 📖 Tentang Pydesk Basic

Pydesk adalah solusi RDP (Remote Desktop) simpel yang dibangun di atas **Tailscale**, dirancang untuk kebutuhan sehari-hari: coding, game ringan, dan akses remote tanpa ribet. Fokusnya satu — **koneksi yang lancar tanpa membebani mesin**.

Cocok untuk:
- 💻 Coding remote (editor, terminal, build ringan)
- 🎮 Game ringan
- 🧪 Menjalankan aplikasi yang butuh environment desktop
- 👁️‍🗨️ Anti-VM deteksi (ringan , beberapa masih terdeteksi)

## Tentang Pydesk X

Pydesk X adalah performance booster untuk `Pydesk` basic , menyediakan berbagai menu.

> ⚠️ **Catatan kompatibilitas:** Roblox Studio **Dapat berjalan** , Roblox windows **tidak dapat berjalan** di Pydesk karena terdeteksi sebagai VM oleh sistem anti-cheat Roblox. Ini adalah batasan platform, bukan bug Pydesk.

## ✨ Fitur

- **Debloat bertingkat** — pilih level pembersihan sesuai kebutuhan:
  - `normal` — debloat dasar, aman untuk semua kebutuhan
  - `light` — buang layanan non-esensial
  - `hard` — agresif, cocok untuk mesin dengan resource terbatas
  - `hardcoded` — preset tetap untuk hasil konsisten
- **Memory Release** — bebaskan memori hingga **7 GB** dengan satu perintah
- **Latency rendah** — tergantung kualitas internet Anda; semakin baik jaringan, semakin responsif
- **Berbasis Tailscale** — koneksi aman tanpa perlu buka port publik

## 🚀 Instalasi

- Silahkan pergi ke https://py-desk-flow.base44.app untuk start rdp.
  - 1.Buat `PAT` github key.
  - 2.Masukkan ke section 'ghp.-' **❗INFORMASI DATA AMAN❗**
  - 3.Masukkan Username `GitHub`
  - 4.Buat repository bernama Contoh `Pydesk runner' atau pakai template **saat ini**
  - 5.Siapkan Keys `Tailscale`
    > Ambil dari Tailscale (Wajib login di github akun yang akan dipakai) , di setting lalu buat new `keys` , Generate `Auth keys` lalu salin dan simpan dengan aman!
  - 6.Paste ke TAILSCALE_AUTH_KEY di bagian `Secrets` di Pydesk website.
  - 7.RDP siap digunakan.

- Silahkan pergi ke https://pydesk-core-flow.base44.app/workspace untuk custom agent rdp pydesk
  > ⚠️ Experience User Only/kalau masih awam dalam Pydesk maka dianjurkan untuk melihat di tiktok @8kittenoell_ untuk caranya.

## ⚡ Pydesk Basic vs Pydesk X
Pydesk hadir dalam dua lapisan: Basic sebagai fondasi, dan X sebagai agent tambahan yang mendorong performa lebih jauh. Keduanya bukan pengganti satu sama lain — X dibangun di atas Basic.

## Perbandingan Singkat
**❗Aspek	Pydesk Basic | Pydesk X❓**
- **Peran**	`Pydesk` Fondasi RDP + `Pydesk X`optimasi dasar	Agent tambahan (booster)
- **Fungsi utama**	`Pydesk` Penyedia rdp `Pydesk X` Koneksi Tailscale, debloat, memory release	Overclock performa di atas Basic
- **Wajib dipasang?**	`Pydesk` ✅ Ya — ini inti Pydesk	`Pydesk X`❌ Tidak — opsional
- **Cakupan optimasi**	`Pydesk` Debloat normal/light/hard/hardcoded + release memori hingga 7 GB `Pydesk X`	Dorongan performa tambahan (CPU/tuning)
- **Tingkat agresivitas	Terkontrol**, `Pydesk` sesuai level debloat yang dipilih	`Pydesk X` Lebih agresif, bergantung hardware
- **Jaminan hasil	Konsisten** — `Pydesk`selama internet bagus, `Pydesk X` jalan lancar	Tidak sepenuhnya bisa — hasil bervariasi antar mesin
Cocok untuk	Semua pengguna, termasuk yang baru mulai	Yang ingin mendorong performa lebih jauh dan paham risikonya
## Ringkasan 🏄🏻
> Pydesk Basic = paket lengkap untuk mulai pakai. Sudah termasuk RDP via Tailscale, debloat bertingkat, dan memory release. Tanpa X pun Pydesk sudah berfungsi penuh.

## Intinya 
> ❓Pydesk X = lapisan tambahan yang mengoptimalkan performa di atas Basic. Ia tidak sepenuhnya bisa menggantikan tuning manual — hasilnya bergantung pada hardware, kondisi sistem, dan level debloat yang dipakai.

> ❗informasi: Basic bikin jalan; X bikin lebih kencang — kalau hardware-nya mendukung.

## 📌 Catatan Performa
- Kelancaran sangat bergantung pada kualitas internet kedua sisi.

- Gunakan debloat level yang sesuai — hard bisa mematikan layanan yang Anda butuhkan.

- Memory Release bersifat sementara; memori bisa terisi kembali seiring penggunaan.
