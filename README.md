# Sincere: Landing Page

Landing page modern dan responsif untuk brand **"Sincere"** (fiktif). Proyek ini menampilkan desain antarmuka yang bersih dengan tipografi *Space Grotesk* dan *Work Sans*, serta elemen visual unik seperti "browser card" dengan efek skeleton loading, dibuat dengan HTML & CSS murni (tanpa framework).

## Struktur Proyek

```text
nama-repositori/
│
├── index.html              # File utama HTML (struktur halaman)
├── style.css               # File CSS (gaya dan layout)
├── Assets/                 # Folder untuk gambar (opsional)
│   └── screenshots.png     # Screenshot untuk README
└── README.md               # Dokumentasi ini
```

## Fitur / Section

| Section | Deskripsi |
|---|---|
| **Header** | Logo + navigasi sticky (nempel di atas saat scroll) |
| **Hero** | Headline utama + CTA button + mockup "browser card" (dibuat murni pakai CSS, tanpa gambar) |
| **Features** | 2 poin keunggulan layanan (Long-term Services, Affordable Price) |
| **Contact** | Form kontak (nama & email) dengan tombol submit |
| **Footer** | Logo, email kontak, copyright |

## Desain

- **Font:** Space Grotesk (heading), Work Sans (body), IBM Plex Mono (label/eyebrow)
- **Warna:** dikontrol lewat CSS variable di `:root` (`--color-primary`, `--color-accent`, dll) sehingga mudah untuk diganti tanpa perlu mencari-cari di seluruh file
- **Responsive:** breakpoint di `860px` — hero berubah dari 2 kolom jadi 1 kolom, padding mengecil, fitur-grid jadi vertikal

## Menjalankan Secara Lokal

1. Download/clone kedua file (`index.html` & `style.css`), taruh di folder yang sama.
2. Buka `index.html` langsung di browser (double-click), atau pakai **Live Server** extension di VS Code untuk auto-reload saat edit.

## Kustomisasi Cepat

Ganti warna tema di bagian paling atas `style.css`:
```css
:root {
    --color-primary: #0F3D34;   /* warna utama */
    --color-accent: #FF4D3D;    /* warna aksen/tombol */
}
```

## Teknologi

- **HTML5:** Markup semantik untuk struktur konten.
- **CSS3:** Styling kustom (file `style.css`) tanpa framework eksternal.
- **Google Fonts:** CDN untuk muat cepat tipografi web.


## Lisensi

Project latihan pribadi -- bebas dipakai/dimodifikasi.
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)]()
