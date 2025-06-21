<h1 align="center">🚀 CodX-lf</h1>

<p align="center">
Konfigurasi <code>lf</code> (terminal file manager) dengan navigasi bergaya <strong>Neovim</strong>. <br>
Didesain khusus untuk Termux/Linux agar cepat, efisien, dan nyaman digunakan oleh pengguna keyboard.
</p>

---

## ⚙️ Instalasi Manual

### 1. Clone Repo

```bash
git clone https://github.com/A-CodX/CodX-lf.git
```

### 2. Pindahkan konfigurasi ke lokasi lf

```bash
mkdir -p ~/.config/lf
cp CodX-lf/lfrc ~/.config/lf/lfrc
```

---

## 🧠 Fitur Navigasi

Tekan `?` di dalam `lf` untuk melihat daftar shortcut.

---

## ✅ Requirements

- **lf** file manager
- Shell: `zsh`
- Editor: `nvim` (untuk fungsi edit file)
- Command: `rm`, `mkdir`, `touch`, `less`

---

## 🧪 Shortcut Penting

```txt
Navigasi:
  h/l/j/k   : kiri, buka, bawah, atas
  gg / G    : ke atas / bawah
  H         : toggle file tersembunyi

File:
  i / n     : edit di Neovim
  y / c / p : copy, cut, paste
  x / d     : hapus file/folder (dengan konfirmasi)
  a / A     : buat file / folder
  r         : rename file
  ggVGd     : hapus semua isi file (mode nvim)

Lainnya:
  q / R     : keluar / reload
  .         : toggle hidden
  ?         : lihat shortcut (help)
  ESC :wq   : save dan keluar dari nvim
```

---

## 📂 Struktur

```bash
~/.config/lf/lfrc
```

---

## 🙌 Kredit & Lisensi

Konfigurasi ini dikembangkan dengan perhatian tinggi terhadap efisiensi dan kenyamanan oleh [A-CodX](https://github.com/A-CodX).  
Dibagikan sebagai open source agar komunitas terminal enthusiast dapat belajar, menggunakan, dan berkontribusi secara bebas.

---

<p align="center">
⭐ Berikan bintang jika kamu menyukai proyek ini!
</p>
