---

<h1 align="center">CodX-lf</h1>📁 Konfigurasi lf (terminal file manager) yang dioptimalkan untuk efisiensi, dengan navigasi layaknya Neovim (LazyVim).
Dirancang khusus untuk pengguna Termux agar nyaman, cepat, dan powerful.


---

⚙️ Instalasi Manual

1. Clone Repo

git clone https://github.com/A-CodX/CodX-lf.git

2. Pindahkan konfigurasi ke lokasi lf

mkdir -p ~/.config/lf
cp CodX-lf/lfrc ~/.config/lf/lfrc

3. Jalankan lf

lf


---

🎮 Navigasi & Shortcut

Tombol	Fungsi

h / l	Kembali folder / Masuk folder
j / k	Turun / Naik
gg / G	Ke paling atas / bawah
H	Tampilkan/sembunyikan file hidden
i	Edit file dengan Neovim
n	Buka Neovim
y / c / p	Copy / Cut / Paste
x / d	Hapus file/folder (dengan konfirmasi)
a / A	Buat file / folder
r	Rename file
q / R	Keluar / Reload ulang
?	Lihat bantuan navigasi
.	Toggle file tersembunyi
V / u	Invert seleksi / Unselect
ggVGd	(di Neovim) Hapus semua isi
:wq	(di Neovim) Simpan dan keluar



---

📎 Catatan

Shell default: zsh

Sudah mendukung icon (gunakan font Nerd Font)

Direkomendasikan terminal Termux + font monospace support icon



---

🤝 Kontribusi

Ingin menambahkan fitur, shortcut baru, atau perbaikan bug?
Silakan kirim pull request ke repository ini.


---

🧠 Kredit

Dikembangkan oleh A-CodX
Terinspirasi dari efisiensi workflow Neovim dan terminal power-user.


