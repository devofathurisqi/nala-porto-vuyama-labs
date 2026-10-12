# NALA — Demo 2

Tema: boutique. Website toko reseller dengan alur beranda → produk → detail → keranjang → checkout → WhatsApp.

## Menjalankan

Jalankan `npm start` di folder ini. Buka http://127.0.0.1:4312. Tidak perlu menginstal dependency.

## Pengaturan

- Identitas dan nomor WhatsApp: `dist/config.js`.
- Koleksi, harga, varian, gambar: `dist/products.js`.
- Server preview hanya melayani folder `dist`.
- Upload isi `dist` ke static hosting untuk publikasi.
- Harga ecer dari katalog September 2026; stok dan ongkir dikonfirmasi admin.
- Brand NALA adalah identitas contoh. Ada 20 koleksi dan 51 pilihan varian. Nama Gradasi dan Printed mengikuti folder; pilihan lainnya diberi label sesuai foto. Rincian cakupan ada di CATALOGUE-COVERAGE.md pada demo 1.
- Font dan foto self-hosted; foto WebP mempertahankan warna dan orientasi asli.
- Keranjang dan favorit tersimpan di browser, terpisah per demo. Data alamat checkout tidak disimpan ke server.
- Test logika transaksi: `npm test`.

Sumber foto dan dokumentasi validasi ada di `../porto_vuyama_labs_1/ASSET-SOURCES.md` dan `../porto_vuyama_labs_1/QA.md`.
