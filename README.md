# Ryuto Kazuma — Versi Sederhana

Versi ini hanya memakai HTML, JavaScript, CSS, Tailwind CSS CDN, dan asset lokal.

## Struktur

- `index.html` — halaman utama.
- `src/main.js` — mode gelap/terang, menu mobile, dan animasi scroll.
- `src/styles.css` — styling tambahan, responsive layout, dan animasi.
- `assets/ryuto-profile.webp` — foto profil.

## Menjalankan

Bisa dibuka langsung dengan double-click `index.html`. Karena Tailwind CSS dipanggil melalui CDN, koneksi internet diperlukan untuk memuat utility Tailwind dan font eksternal.

Alternatif dengan server lokal:

```bash
python3 -m http.server 8080
```

Lalu buka `http://localhost:8080`.

Versi ini tidak membutuhkan `package.json`, `package-lock.json`, Vite, atau file JSON untuk menjalankan halaman.

## Form kontak dan sosial media

Form kontak mengirim data melalui AJAX ke `ryuto.akira28@gmail.com` memakai endpoint FormSubmit. Saat tombol diklik, halaman tetap terbuka dan status pengiriman muncul di bawah tombol.

Untuk mengganti link sosial media, edit atribut `href` pada tiga link ikon di bagian contact section pada `index.html`:

- TikTok: `https://www.tiktok.com/@username`
- Instagram: `https://www.instagram.com/username`
- YouTube: `https://www.youtube.com/@username`
