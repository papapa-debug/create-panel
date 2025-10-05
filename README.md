# create-panel
buat panel gratisss
# VPS Panel via Termux

## 📌 Deskripsi
Panel VPS ini memungkinkan kamu untuk **mengelola VPS langsung dari Termux** di Android atau Linux.  
Dengan panel ini, kamu bisa menjalankan perintah, memonitor sistem, dan mengatur server tanpa harus login lewat SSH manual setiap saat.

---

## ⚙️ Fitur
- Jalankan perintah VPS dari Termux.
- Monitoring resource VPS (CPU, RAM, Disk, Network).
- Otomatisasi script startup.
- Mudah dikustomisasi sesuai kebutuhan.
- Mendukung multiple VPS (opsional).

---

## 🛠️ Persiapan
Sebelum menjalankan panel ini, pastikan Termux sudah terpasang dan up-to-date:

```bash
pkg update && pkg upgrade
pkg install python git curl wget nano

Opsional untuk tampilan GUI (jika ada):

pkg install dialog


---

🚀 Instalasi

1. Clone repository:



git clone https://github.com/papapa-debug/create-panel

2. masuk ke direktori :

cd create-panel


3. Jalankan panel:

python create-panel.py

> ⚠️ Pastikan kamu sudah memberi izin Termux untuk storage jika script
 membutuhkan akses file.
