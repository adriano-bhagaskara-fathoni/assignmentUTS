# Naufal Fadhlan — Portfolio

Portfolio statis yang dibuat berdasarkan CV Naufal Fadhlan. Situs ini menggunakan HTML, CSS, dan JavaScript vanilla sehingga tidak membutuhkan proses build atau dependency tambahan.

## Menjalankan secara lokal

Buka `index.html` langsung di browser, atau jalankan server statis sederhana:

```bash
python -m http.server 8000
```

Kemudian buka <http://localhost:8000>.

## Mengaktifkan GitHub Pages

1. Push repository ke GitHub.
2. Buka **Settings → Pages**.
3. Pada **Build and deployment → Source**, pilih **GitHub Actions**.
4. Push ke branch `main` (atau jalankan workflow **Deploy to GitHub Pages** secara manual dari tab **Actions**).

Workflow di `.github/workflows/deploy-pages.yml` akan mengunggah seluruh situs sebagai artifact dan menerbitkannya ke GitHub Pages setiap kali ada push ke `main`.
