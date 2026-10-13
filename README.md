# Cara Pakai

1. Buka folder ini di Codex (CLI/IDE). Codex otomatis membaca AGENTS.md.
2. Isi `input/fakta_terverifikasi.md` (bagian "KONFLIK" wajib dijawab; sisanya sebisanya).
3. Jalankan prompt berurutan (copy isi file ke Codex):
   - `prompts/01_audit_hrd.md`  -> hasil: output/audit_report.md
   - `prompts/02_rewrite_cv.md` -> hasil: output/cv_baru.md
   - `prompts/03_build_pdf.md`  -> hasil: output/cv.tex + output/cv.pdf
4. Install MiKTeX, pastikan `pdflatex` atau `xelatex` ada di PATH (cek: `pdflatex --version`).
5. Review PDF, lalu iterasi: "perketat bagian X", "buat varian untuk posisi Y".

Tips: simpan hasil tiap iterasi dengan nama versi (cv_v1.pdf, cv_v2.pdf). Buat varian per posisi
(Frontend / Fullstack / Mobile) dari cv_baru.md yang sama.
