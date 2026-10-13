# AGENTS.md — Project Audit & Rebuild CV (Irvan Agustriono Lumban Gaol)

## Tujuan
Mengaudit CV lama (2 versi) dari sudut pandang HRD/recruiter, lalu membangun SATU CV baru terbaik
yang membuat HRD tertarik, lalu dikompilasi menjadi PDF via LaTeX (MiKTeX).

## Target
- Posisi utama: Junior Software Engineer / Fullstack Developer / Frontend Developer (fresh graduate D3 TI, lulus Aug 2026)
- Pasar: Indonesia (perusahaan teknologi, startup, software house, BUMN/korporasi digital)
- Bahasa CV: Inggris (kecuali diminta lain). Bahasa diskusi dengan user: Indonesia.

## Struktur folder
- input/cv_lama_v1.md  : CV versi 1 (lama, lebih detail)
- input/cv_lama_v2.md  : CV versi 2 (lebih baru, format ringkas Tools/Deliverables)
- input/fakta_terverifikasi.md : sumber kebenaran, diisi user. WAJIB dibaca sebelum menulis apa pun.
- prompts/01_audit_hrd.md      : prompt tahap 1 (audit)
- prompts/02_rewrite_cv.md     : prompt tahap 2 (tulis CV baru)
- prompts/03_build_pdf.md      : prompt tahap 3 (LaTeX -> PDF)
- output/                      : hasil (audit_report.md, cv_baru.md, cv.tex, cv.pdf)

## Aturan keras (jangan dilanggar)
1. DILARANG mengarang fakta, angka, metrik, tools, jabatan, atau tanggal. Jika data tidak ada, tulis
   `[ISI: pertanyaan]` dan tanyakan ke user.
2. Konflik antar-dokumen (mis. IPK, tanggal, role) tidak boleh dipilih diam-diam. Catat di audit_report.md
   dan tunggu keputusan user di fakta_terverifikasi.md.
3. Semua klaim harus bisa dipertanggungjawabkan di wawancara. Tandai klaim yang kelihatan berlebihan.
4. CV akhir: 1 halaman (maksimal 2 jika benar-benar perlu), single column, ATS-friendly,
   tanpa foto, tanpa ikon gambar, tanpa tabel bersarang, font standar.
5. Bullet memakai pola: Kata kerja aksi + apa yang dibangun + tools + dampak/hasil (angka jika ada).
6. Kerjakan bertahap sesuai nomor prompt. Berhenti dan minta konfirmasi user di akhir tiap tahap.
7. Jangan ubah file di input/ kecuali fakta_terverifikasi.md atas permintaan user.
