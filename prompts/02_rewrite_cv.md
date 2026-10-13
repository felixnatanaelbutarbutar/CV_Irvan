# PROMPT 02 — TULIS ULANG CV (VERSI TERBAIK)

Peran: Career Coach + Technical Recruiter yang menulis CV agar lolos ATS dan menarik HRD.

## Input
AGENTS.md, input/fakta_terverifikasi.md (prioritas tertinggi), input/cv_lama_v1.md, input/cv_lama_v2.md,
output/audit_report.md.

## Prasyarat
Jika bagian A di fakta_terverifikasi.md masih ada yang kosong, TANYAKAN dulu. Jangan menebak.
Konflik yang belum dijawab ditulis sebagai `[ISI: ...]` di draf.

## Output: `output/cv_baru.md`
Urutan section (single column, 1 halaman):
1. Header: nama, kontak, LinkedIn, GitHub, portfolio, lokasi (tanpa alamat jalan).
2. Professional Summary: 2-3 kalimat spesifik: siapa + stack inti + bukti terkuat + target peran.
   Tanpa kata klise ("passionate", "hard-working", "fresh ideas").
3. Technical Skills: dikelompokkan (Languages | Frontend | Backend | Mobile | Database | DevOps/Cloud | ML | Tools).
   Hanya skill yang benar-benar dipakai di proyek/magang.
4. Experience (internship): Flashcom Indonesia, PDAM Tirtanadi. 2-3 bullet masing-masing, berbasis hasil.
5. Projects: pilih 4-5 terbaik, urut relevansi (bukan kronologis): SIAP, Facial Skin Disease Classification,
   PUSMASIB, LPK MORI, + 1 (KicksNStyle atau EC2, sesuai keputusan user). Tiap proyek: judul | peran | tanggal |
   stack satu baris | 2-3 bullet.
6. Leadership & Organization: HIMATIF (2 bullet), kepanitiaan kaderisasi (1 bullet, boleh digabung).
7. Education: institusi, gelar, tahun, IPK (yang terverifikasi).
8. Certifications & Achievements: TOEFL ITP 500, kursus/sertifikat relevan (Full Stack Capstone, React, dst.).
   Webinar hanya jika ruang tersisa.

## Aturan bullet
- Format: **Kata kerja aksi (past tense) + apa + tools + hasil/dampak**.
- Maks 1-2 baris per bullet, maks 3 bullet per proyek/pengalaman.
- Angka hanya dari fakta_terverifikasi.md. Tidak ada angka -> pakai kualitas konkret
  (mis. "offline mode with auto-sync", "anti-fake-GPS/root detection"), bukan klaim kosong.
- Hindari: "responsible for", "worked on", "involved in", "helped".
- Kata kerja: Built, Designed, Implemented, Integrated, Deployed, Containerized, Led, Coordinated, Automated.
- Past tense untuk yang selesai, present tense untuk yang masih berjalan.
- Satu istilah per teknologi di seluruh CV (pilih "Golang" atau "Go", konsisten).

## Keluaran
- `output/cv_baru.md` (final draft)
- `output/changelog.md`: tabel Perubahan | Alasan | Sumber fakta.
- `output/open_questions.md`: semua `[ISI: ...]` yang tersisa.
- Varian opsional jika diminta: `cv_frontend.md`, `cv_fullstack.md`, `cv_mobile.md`.

Akhiri dengan: "Tahap 2 selesai. Review cv_baru.md. Jika OK, jalankan prompt 03."
