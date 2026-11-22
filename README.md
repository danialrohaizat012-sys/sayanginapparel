# Sayagin Apparel — Landing Page

Landing page (`index.html`) untuk Sayagin Apparel — servis cetak baju & jersi custom dan koleksi siap pakai, dari Pasir Mas, Kelantan. #barelokalboh

Identiti jenama: kuning `#FEC70A` + hitam `#111111`, fon Montserrat. Logo dalam `assets/`.

## Cara edit
Semua maklumat kedai ada dalam objek `CONFIG` di bahagian `<script>` bawah `index.html`:

- `whatsapp` — nombor WhatsApp (sekarang `601157737765`).
- `sizes` — senarai saiz.
- `products` — nama, keterangan, harga, label, warna dan gambar setiap produk.
  Untuk gambar, letak fail dalam `assets/` dan isi `image: "assets/nama-fail.jpg"`.

Jawapan Soalan Lazim yang bertanda `[...]` juga perlu diisi.

## Ciri
- Borang tempahan yang menyusun mesej WhatsApp secara automatik
- Pilihan saiz & warna pada kad produk terus masuk ke borang
- Menu telefon, carousel produk, bar tindakan bawah di telefon
- Mod gelap, animasi lembut (dimatikan jika pengguna pilih kurang gerakan)

## Banner servis cetak
Bahagian Servis Cetak memaparkan `assets/banner-cetak.jpg` jika fail itu wujud (disembunyikan secara automatik jika tiada).
Muat naik gambar banner "Cetak ikut cara anda" dengan nama itu untuk memaparkannya.
