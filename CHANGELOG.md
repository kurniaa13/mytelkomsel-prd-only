# Changelog

Semua perubahan penting pada repo ini dicatat di sini. Format mengikuti [Keep a Changelog](https://keepachangelog.com/id-ID/1.1.0/) dan versi memakai [Semantic Versioning](https://semver.org/lang/id/).

## [0.3.0] - 2026-11-25

### Added
- `index.html`: prototipe web alur Beli Paket (Beranda, Daftar Paket, Bandingkan Paket, Verifikasi Nomor, Pembayaran, Konfirmasi Hasil, Riwayat Transaksi, Detail Transaksi, Bantuan) dengan data contoh.
- Status "Pembayaran diproses", halaman Konfirmasi Hasil, dan penjelasan verifikasi ulang (UX-01, UX-02, UX-03).
- Sisa kuota di Beranda bertambah otomatis setelah transaksi berhasil (UX-07).
- Riwayat transaksi dengan filter status dan tanggal, disimpan di `localStorage` (UX-04).
- Pilihan demo "simulasikan transaksi gagal" untuk menguji layar gagal.

### Notes
- Dibuat dengan bantuan Claude, **hanya dari `README.md` (PRD)** tanpa UX Skill.
- Alur diuji otomatis (jalur berhasil dan gagal) dengan jsdom.

## [0.2.0] - 2026-11-17

### Added
- PRD: struktur informasi (sitemap), spesifikasi halaman, dan navigasi dari Worksheet 9 (Information Architecture).

## [0.1.0] - 2026-11-13

### Added
- PRD awal: ringkasan masalah, persona Naira, tujuan, dan daftar kebutuhan UX-01 sampai UX-08 beserta prioritas dari Worksheet 8 (UX Requirements).

