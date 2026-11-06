# Bedah UU 27/2026

Situs statis yang membedah **UU Nomor 27 Tahun 2026 tentang Pelindungan Ketenagakerjaan**:
peta 23 bab, perbandingan dengan UU 13/2003 dan UU Cipta Kerja beserta kutipan bunyi pasal,
kalkulator pesangon, pencarian 313 pasal, korelasi aturan, dan tenggat transisi.

Disusun oleh **Mustakim**, Ahli K3 Umum (Kemnaker), Ahli K3 Listrik (BNSP), dan Data Scientist (BNSP).
LinkedIn: https://www.linkedin.com/in/mustakiim · Saran dan masukan: mustakimsr@gmail.com

## Isi folder
```
index.html             halaman utama (HTML, CSS, JS, dan teks 313 pasal dalam satu file)
assets/mustakim.jpg    foto penyusun
README.md              panduan ini
```

## Menerbitkan di GitHub Pages (gratis, publik)
1. Masuk ke github.com, klik **New repository**. Beri nama, misalnya `bedah-uu27`, pilih **Public**, lalu **Create repository**.
2. Di halaman repo, klik **uploading an existing file**. Seret `index.html`, `README.md`, dan folder `assets` (beserta isinya). Klik **Commit changes**.
3. Buka **Settings → Pages**. Pada *Build and deployment*, pilih *Source: Deploy from a branch*, cabang `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1–2 menit. Alamat situs muncul di bagian atas halaman Pages, misalnya
   `https://<nama-akun>.github.io/bedah-uu27/`.

Tip: kalau nama repo dibuat `<nama-akun>.github.io`, alamatnya menjadi `https://<nama-akun>.github.io/` tanpa nama folder.

## Mengganti alamat ke domain sendiri
1. Beli domain di registrar (misalnya domain `.id`, `.my.id`, `.online`, atau `.com`).
2. Di GitHub: **Settings → Pages → Custom domain**, isi nama domain (misalnya `uu27.domainanda.id`), klik **Save**.
   GitHub otomatis membuat file `CNAME` di repo.
3. Di pengelola DNS registrar:
   - Untuk subdomain (`uu27.domainanda.id`): buat record **CNAME** `uu27` → `<nama-akun>.github.io`
   - Untuk domain utama (`domainanda.id`): buat 4 record **A** ke
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`,
     dan record **CNAME** `www` → `<nama-akun>.github.io`
4. Tunggu propagasi DNS (beberapa menit sampai 24 jam). Setelah status *DNS check successful*, centang **Enforce HTTPS**.

## Memperbarui isi
Semua data ada di `index.html`:
- `<script id="pasalData">` — teks 313 pasal untuk pencarian dan kutipan,
- `BAB` — ringkasan per bab untuk peta,
- `R` dan `CR` — baris perbandingan dan kutipan pasalnya,
- `AL` — faktor pengali pesangon per alasan PHK,
- `EV` — linimasa korelasi.

Setelah mengubah file, unggah ulang `index.html` ke repo; situs diperbarui otomatis dalam 1–2 menit.

Sumber: salinan resmi UU 27/2026 (Kemensetneg, LN 2026 No. 179). Bahan edukasi, bukan nasihat hukum.
