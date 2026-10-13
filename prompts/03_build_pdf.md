# PROMPT 03 — BUILD PDF (LaTeX / MiKTeX)

Peran: LaTeX typesetter yang membuat CV ATS-friendly.

## Input
output/cv_baru.md (final; jika masih ada `[ISI: ...]`, berhenti dan tanya user).

## Tugas
1. Buat `output/cv.tex` dari isi cv_baru.md PERSIS (jangan ubah isi/kata tanpa izin).
2. Desain:
   - Kelas `article`, A4, 10-10.5pt, margin ~1.5cm, single column.
   - Font aman ATS: `lmodern` + `[T1]{fontenc}`; jika XeLaTeX, font sistem sederhana via `fontspec`.
   - Header terpusat: nama besar, satu baris kontak dengan `\href`.
   - Heading section: bold/small caps + garis tipis, satu warna aksen gelap (navy).
   - Entri: judul tebal kiri, tanggal rata kanan (`\hfill`), peran italic di baris berikut,
     bullet rapat (`enumitem`, `nosep`, `itemsep=1pt`).
   - Tanpa foto, ikon gambar, kolom ganda, tabel, text box.
   - Teks harus bisa dipilih/disalin: `\input{glyphtounicode}` + `\pdfgentounicode=1` (pdfLaTeX).
   - Metadata PDF: judul "Irvan Agustriono Lumban Gaol - CV", author.
3. Kompilasi dari folder output/ (dua kali):
   ```
   pdflatex -interaction=nonstopmode cv.tex
   pdflatex -interaction=nonstopmode cv.tex
   ```
   (atau `xelatex` jika pakai fontspec). Izinkan MiKTeX auto-install paket.
4. Verifikasi:
   - Tepat 1 halaman (jika 2, rapatkan spasi/font dulu; jika masih, laporkan apa yang bisa dipangkas, jangan pangkas diam-diam).
   - Tidak ada overfull hbox berarti; karakter khusus (`& % _ #`) sudah di-escape.
   - `pdftotext cv.pdf -` (jika ada): urutan baca logis.
   - Render PNG (`pdftoppm`, jika ada) dan cek visual: tidak terpotong, tanggal sejajar kanan.
5. Simpan `output/cv.pdf` dan `output/cv.tex`; hapus *.aux, *.log, *.out.
6. Salin ke `Irvan_Agustriono_Lumban_Gaol_CV.pdf`.
7. Laporkan: jumlah halaman, warning, maks 5 saran perbaikan visual.

## Aturan
Tidak mengubah konten; hanya tipografi/layout.
