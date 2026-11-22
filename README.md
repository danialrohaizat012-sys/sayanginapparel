# Sayagin Apparel — Landing Page

Landing page (`index.html`) untuk Sayagin Apparel — baju guru dari Pasir Mas, Kelantan. #barelokalboh

Identiti jenama: kuning `#FEC70A` + hitam `#111111`, fon Montserrat. Logo dalam `assets/`.

## Cara edit
Semua maklumat kedai ada dalam objek `CONFIG` di bahagian `<script>` bawah `index.html`:

- `whatsapp` — nombor WhatsApp (format `60XXXXXXXXX`). **Wajib diisi.**
- `sizes` — senarai saiz.
- `products` — nama, keterangan, harga, label, warna dan gambar setiap produk.
  Untuk gambar, letak fail dalam `assets/` dan isi `image: "assets/nama-fail.jpg"`.

Jawapan Soalan Lazim yang bertanda `[...]` juga perlu diisi.

## Ciri
- Borang tempahan yang menyusun mesej WhatsApp secara automatik
- Pilihan saiz & warna pada kad produk terus masuk ke borang
- Menu telefon, carousel produk, bar tindakan bawah di telefon
- Mod gelap, animasi lembut (dimatikan jika pengguna pilih kurang gerakan)
