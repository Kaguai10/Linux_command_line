# Modul 2 — Permission & Networking Linux

Modul ini membahas pengelolaan hak akses file serta penggunaan perintah dasar networking di Linux. Materi ini penting untuk administrasi sistem, monitoring, dan keamanan sistem Linux.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

- Mengelola permission file dan direktori
- Memahami kepemilikan file pada Linux
- Menggunakan tools monitoring sistem dan jaringan
- Melakukan troubleshooting dasar melalui terminal

---

## Daftar Perintah

| Perintah         | Fungsi |
|------------------|---------|
| `chmod`          | Mengubah permission file atau direktori |
| `chown`          | Mengubah kepemilikan file atau direktori |
| `cat`            | Menampilkan isi file |
| `lspci`          | Menampilkan perangkat PCI yang terhubung |
| `uname -a`       | Menampilkan informasi kernel dan sistem |
| `lsb_release -a` | Menampilkan informasi distribusi Linux |
| `grep`           | Mencari teks atau pola tertentu |
| `nano`           | Mengedit file melalui terminal |
| `head`           | Menampilkan bagian awal file |
| `tail`           | Menampilkan bagian akhir file |
| `df`             | Menampilkan penggunaan disk |
| `du`             | Menampilkan ukuran file atau direktori |
| `free`           | Menampilkan penggunaan RAM |
| `adduser`        | Membuat user baru |
| `top`            | Monitoring proses secara real-time |
| `ps`             | Menampilkan daftar proses aktif |
| `ifconfig`       | Menampilkan konfigurasi jaringan |
| `dmesg`          | Menampilkan log kernel dan perangkat |

---

## Catatan

- Gunakan `chmod +x <file>` untuk memberikan izin eksekusi
- `grep` sering digunakan bersama pipe (`|`) untuk filtering output
- Pada distribusi Linux modern, `ifconfig` mulai digantikan oleh `ip a`
- Gunakan `top` atau `ps aux` untuk monitoring proses sistem

---

## Navigasi

[← Kembali ke README Utama](../README.md)
