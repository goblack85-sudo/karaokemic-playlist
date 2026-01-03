# 🎤 KaraokeMic Playlist Server

Repository ini berisi kumpulan playlist video karaoke dalam format JSON  
yang digunakan oleh aplikasi KaraokeMic (Cordova Android App).

## 📌 Tentang Repository
- Repository ini tidak menyimpan video
- Hanya menyimpan YouTube Video ID, judul, dan thumbnail
- Digunakan sebagai playlist statis yang di-load oleh aplikasi
- Tidak menggunakan YouTube Data API

## 📂 Struktur Playlist
Setiap file JSON mewakili satu kategori karaoke:

| File | Kategori |
|-----|---------|
| dangdut.json | Dangdut Karaoke |
| pop.json | Karaoke Musik Pop |
| slowrock.json | Karaoke Slow Rock |
| lawas.json | Karaoke Lagu Lawas |
| viral.json | Karaoke Lagu Viral |

## 🔄 Cara Update Playlist
1. Edit file JSON sesuai kategori
2. Commit & push ke branch main
3. Aplikasi akan otomatis memuat playlist terbaru (tanpa rebuild APK)

## ⚠️ Catatan
- Seluruh video tetap di-host oleh YouTube
- Repository ini bukan media hosting
- Hak cipta tetap milik pemilik video masing-masing

---
🎶 KaraokeMic Project