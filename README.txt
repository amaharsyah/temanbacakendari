Teman Baca Kendari — Paket Website Siap Upload

Isi folder:
- index.html (katalog)
- detail.html (halaman detail buku)
- books.js (data buku + resensi singkat)
- /covers (taruh file cover di sini)

Cara pasang cover:
1) Masukkan gambar cover ke folder /covers
   Contoh nama file: covers/rich-dad-poor-dad.jpg
2) Buka books.js → cari buku yang sesuai → isi field "cover" dengan path di atas.
   Contoh: "cover": "covers/rich-dad-poor-dad.jpg"

Catatan:
- Kalau "cover" kosong, website otomatis pakai placeholder.svg.
- Semua path sudah relatif, aman untuk GitHub Pages/Netlify (asal file ada di folder yang sama).

GitHub Pages:
- Pastikan index.html ada di folder yang kamu pilih sebagai "Source" (root atau /docs).
