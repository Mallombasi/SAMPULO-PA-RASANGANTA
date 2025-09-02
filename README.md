# SAMPULO PA'RASANGANTA - Web App (Static)

Versi awal aplikasi web berbasis HTML/CSS/JS yang Anda unggah.  
Struktur ini dibuat agar bisa langsung dipush ke GitHub dan dijalankan secara lokal atau di-hosting statis.

## Cara menjalankan (lokal)

1. Pastikan Node.js terpasang.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Jalankan server:
   ```bash
   npm start
   ```
   Aplikasi akan tersedia di `http://localhost:3000`.

Atau gunakan server statis sederhana (tanpa Node):
```bash
# dari folder sampulo-app
python -m http.server 8000
# lalu buka http://localhost:8000
```

## Konten
- `index.html` — file utama (dari unggahan Anda).  
- `server.js` — server Express untuk serve file statis (opsional).  
- `package.json` — metadata + script start.  
- `.gitignore` — node_modules, .env.  
- `LICENSE` — MIT.

Saya menggunakan file yang Anda unggah sebagai `index.html`. Untuk perubahan (memecah CSS/JS ke file terpisah, menambahkan build tools, atau integrasi backend), beri tahu saya dan saya akan bantu lanjutkan.
