# Lensoria Project — Invoice Studio V1.1

Website invoice jasa dokumentasi, live streaming, dan sewa alat untuk Lensoria Project.

## Fitur

- Dashboard ringkasan invoice dan pembayaran.
- Pembuatan invoice jasa, sewa alat, atau gabungan; Qty × durasi × harga.
- Katalog layanan, pelanggan, pembayaran DP/cicilan/pelunasan.
- Pratinjau invoice dan kuitansi; cetak / Save as PDF.
- Backup JSON dan impor arsip invoice lama V1.1.

## Cara menjalankan

Buka `index.html` menggunakan browser modern, atau akses GitHub Pages setelah diaktifkan pada **Settings → Pages**.

## GitHub Pages

1. Repository **Settings → Pages**.
2. **Build and deployment → Source: Deploy from a branch**.
3. Pilih branch **main**, folder **/ (root)**, lalu klik **Save**.
4. Setelah deployment berhasil, alamat: https://andrianpertopo-glitch.github.io/lensoria-invoice/

## Privasi data — penting

Website ini statis, **tanpa login atau database server**. Data invoice dan pelanggan disimpan dalam `localStorage` browser masing-masing. Data di laptop tidak otomatis muncul di HP. Backup perlu dilakukan berkala. Jangan memasukkan file backup/riwayat pelanggan pribadi ke repository publik atau ke kode sumber. Pengunjung lain tidak otomatis melihat data browser Anda, tetapi perangkat bersama tetap berisiko.

Impor data lama melalui **Pengaturan & Backup → Pulihkan backup**, menggunakan file JSON privat yang dibagikan terpisah. Arsip V1.1 digabungkan dengan data yang sudah ada.

**Jangan menggunakan GitHub Pages sebagai penyimpanan rahasia atau backend pembayaran.**

## Teknologi

HTML/CSS/JavaScript mandiri; tidak memerlukan npm atau dependency pihak ketiga. Logo sudah tertanam pada HTML, dan invoice bisa dicetak lewat browser.

© Lensoria Project.
