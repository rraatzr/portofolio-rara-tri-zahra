# Portofolio Rara Tri Zahra

Website portofolio pribadi (HTML, CSS, JavaScript) dengan bagian About Me, What I Can Do, Achievement, dan Contact.

## Struktur

```
portofolio-rara/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── foto-rara.jpg
```

## Menjalankan di VS Code

1. Buka folder `portofolio-rara` di VS Code (File > Open Folder).
2. Pasang ekstensi **Live Server** (Ritwick Dey).
3. Klik kanan `index.html` > **Open with Live Server**.

Bisa juga langsung klik dua kali `index.html` untuk membukanya di browser.

## Upload ke GitHub

```bash
git init
git add .
git commit -m "Portofolio pertama"
git branch -M main
git remote add origin https://github.com/rraatzr/NAMA-REPO.git
git push -u origin main
```

## Mengaktifkan GitHub Pages (agar web bisa dibuka online)

1. Buka repo di GitHub > **Settings** > **Pages**.
2. Pada **Source**, pilih **Deploy from a branch**, lalu branch `main` dan folder `/ (root)`.
3. Klik **Save**. Beberapa menit kemudian webnya aktif di `https://rraatzr.github.io/NAMA-REPO/`.

Tips: beri nama repo `rraatzr.github.io` supaya alamatnya jadi `https://rraatzr.github.io/`.

## Yang perlu dilengkapi

- Tahun juara Handball di bagian Achievement (`index.html`, cari `[isi tahun]`).
