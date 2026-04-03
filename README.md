# 🚀 Reinstall OS via Bash Script

Repository ini menyediakan cara cepat untuk melakukan reinstall sistem operasi menggunakan script otomatis.

## 📌 Command

Gunakan perintah berikut untuk melakukan reinstall ke **Ubuntu 24.04**:

```bash
bash <(wget -qO- https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh) ubuntu 24.04
```

## ⚙️ Penjelasan

- `wget -qO-`  
  Mengunduh script secara langsung tanpa menyimpan file.

- `bash <(...)`  
  Menjalankan script langsung dari hasil download.

- `ubuntu 24.04`  
  Menentukan sistem operasi target yang akan diinstall.

## ⚠️ Peringatan

- ❗ Semua data pada server akan **terhapus permanen**
- ❗ Pastikan Anda sudah melakukan backup sebelum menjalankan command
- ❗ Jalankan sebagai **root user**

## 🧾 Persyaratan

- VPS / Dedicated Server
- Akses root
- Koneksi internet aktif

## ▶️ Cara Penggunaan

1. Login ke server sebagai root:
   ```bash
   ssh root@IP_SERVER
   ```

2. Jalankan command reinstall:
   ```bash
   bash <(wget -qO- https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh) ubuntu 24.04
   ```

3. Tunggu proses selesai (server akan reboot otomatis)

## 🔄 Catatan

- Proses bisa memakan waktu beberapa menit tergantung kecepatan jaringan
- Setelah selesai, Anda akan mendapatkan sistem baru (Ubuntu 24.04)

## 📎 Sumber

Script berasal dari:
https://github.com/bin456789/reinstall