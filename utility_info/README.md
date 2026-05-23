# Modul 5 — Utility & Informasi Sistem Linux

Modul ini membahas berbagai utility Linux yang sering digunakan untuk monitoring sistem, troubleshooting, manajemen log, serta pengelolaan resource dan informasi perangkat keras.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

- Memantau kondisi dan aktivitas sistem Linux
- Menggunakan utility tambahan untuk administrasi sistem
- Membaca log dan informasi hardware
- Mengelola resource sistem melalui terminal

---

## Daftar Perintah

| Perintah             | Fungsi |
|----------------------|---------|
| `acpi`               | Menampilkan informasi baterai |
| `swapoff` / `swapon` | Menonaktifkan atau mengaktifkan swap memory |
| `zip` / `unzip`      | Mengompresi dan mengekstrak file ZIP |
| `w`                  | Menampilkan user aktif dan aktivitasnya |
| `whois`              | Menampilkan informasi domain |
| `lsmod`              | Menampilkan modul kernel yang aktif |
| `arch`               | Menampilkan arsitektur sistem |
| `comm`               | Membandingkan isi dua file |
| `expr`               | Melakukan operasi aritmatika di terminal |
| `hwinfo`             | Menampilkan informasi hardware detail |
| `stat`               | Menampilkan metadata file |
| `ip a`               | Menampilkan konfigurasi jaringan |
| `journalctl`         | Menampilkan log sistem dan service |
| `tasksel`            | Menginstal grup paket pada Debian/Ubuntu |
| `halt`               | Mematikan sistem |

---

## Catatan

- Gunakan `journalctl -xe` untuk melihat log error terbaru
- `ip a` merupakan pengganti modern dari `ifconfig`
- `lsmod` berguna untuk melihat driver atau modul kernel yang digunakan
- `zip` dan `unzip` umum digunakan untuk distribusi dan backup file

---

## Navigasi

[← Kembali ke README Utama](../README.md)
