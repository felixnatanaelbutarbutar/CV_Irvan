# AUDIT REPORT — CV IRVAN AGUSTRIONO LUMBAN GAOL
**Perspektif: Senior Technical Recruiter / HR Manager, Tech Company Indonesia**
**Target Posisi: Junior Software Engineer / Fullstack Developer / Frontend Developer / Software Tester**
**Tanggal Audit: 14 Oktober 2026**

---

## 1. KESAN 7 DETIK

### CV v1 — Skor: 4/10
Yang HRD tangkap dalam 7 detik:
- Terlalu padat teks, tidak ada visual hierarchy yang kuat
- IPK 3.04 langsung kelihatan (merah di benak HRD sebelum baca isinya) — SUDAH DIPERBAIKI: IPK benar 3.26
- Section "Skills" tidak ada sebagai blok tersendiri — fatal untuk ATS parsing dan skim 7 detik
- Judul proyek panjang dan tidak konsisten formatnya
- Tidak ada angka/metrik yang menarik perhatian — semua kalimat deskriptif tugas

### CV v2 — Skor: 6/10
Yang HRD tangkap dalam 7 detik:
- Format Tools/Deliverables lebih terstruktur dan lebih mudah di-scan
- Proyek SIAP langsung "wow" — Golang, Docker, WebSocket, offline sync = sinyal senior yang tidak biasa untuk D3 fresh grad
- Tapi: tidak ada Skills section = ATS bisa gagal filter keyword
- Tidak ada bagian magang (Internship) di body, hanya disebut di summary = menyia-nyiakan pengalaman nyata
- Urutan: proyek duluan sebelum pendidikan = cukup modern, tapi pendidikan harus tetap kelihatan jelas

---

## 2. KEPUTUSAN SHORTLIST

**Keputusan: RAGU (condong ke Lanjut)**

Untuk posisi **Junior Fullstack Developer / Software Developer & Tester**:

**3 Alasan Positif:**
1. **Proyek SIAP adalah killer project** — end-to-end production app dengan Golang REST API, Docker, WebSocket, offline mode + auto-sync, GPS validation, PDF generation. Ini bukan level D3 biasa. Sangat langka.
2. **Variasi stack breadth yang impressive** — mobile (Flutter), web (Laravel+React, Next.js), ML integration (PyTorch/ConvNeXt), cloud (EC2), database (MySQL, PostgreSQL, Firebase/Firestore). Menunjukkan adaptabilitas.
3. **Soft leadership yang terverifikasi** — Wakil Ketua HIMATIF + Project Manager di 2 proyek = bukan coder murni, ada kemampuan koordinasi tim.

**3 Alasan Meragukan:**
1. **Inkonsistensi data antar versi** = sinyal kandidat tidak careful dengan detail (red flag untuk QA/Tester role)
2. **Zero metrik di semua proyek** = tidak bisa membuktikan impact. "Built X" tanpa "X dipakai Y user" terasa kosong
3. **Tidak ada Skills section eksplisit** = bisa gagal ATS filter sebelum dibaca manusia

---

## 3. RED FLAG & INKONSISTENSI

| Masalah | Lokasi | Risiko di Mata HRD | Perbaikan |
|---|---|---|---|
| IPK berbeda: 3.04 vs 3.26 | v1 vs v2 | Kecurangan data = instant reject | **Gunakan 3.26** (terverifikasi user) |
| Proyek EC2 isinya tools Flutter/Laravel/Firebase (isi KicksNStyle) | v2 | Copy-paste error = sinyal tidak teliti (fatal untuk Tester role) | Pisahkan: EC2 = AWS infrastructure; KicksNStyle = mobile app tersendiri |
| KicksNStyle hilang di v2 | v2 | Menghilangkan proyek relevan tanpa alasan | **Masukkan kembali** (instruksi user sudah konfirmasi) |
| Tanggal magang 2026 (Flashcom Mar-Jul 2026, PDAM Jan-Mar 2026) | v1 | Masa depan saat CV dibuat = HRD bingung | **[ISI: konfirmasi tahun — apakah 2025 atau 2026?]** |
| Facial Skin Disease "Dec 2026" | v2 | Tanggal masa depan sangat jauh = HRD curiga proyek fiktif | **[ISI: konfirmasi tanggal selesai yang realistis]** |
| PUSMASIB: v1=Project Manager, v2=Programmer | v1 vs v2 | Role berbeda di 2 versi | **Gunakan: Fullstack Developer** (terverifikasi user) |
| SIAP: "React Native / Flutter" (keduanya ditulis) | v2 | Stack ambigu = tidak bisa di-probe secara teknis | **[ISI: Flutter atau React Native?]** |
| LPK MORI: "Nov 2025 - Present" vs "Nov-Dec 2025" | v1 vs v2 | Status live/selesai tidak jelas | **Sudah live** di lpkmoricentre.co.id — tulis tanggal go-live spesifik |
| HIMATIF: v2 sebut "Chairperson dan Vice Chairperson" tapi hanya Vice yang ada | v2 | Klaim ketua tanpa bukti = pelebihan | **Wakil Ketua (Vice Chairman) saja**, Periode 2024/2025 |
| Tidak ada Skills section di kedua versi | v1, v2 | ATS tidak bisa extract keyword skills | Tambah dedicated Skills section |
| Summary v1 sangat generik | v1 | Tidak ada diferensiasi = buang 3 detik HRD tanpa info baru | Rewrite jadi value proposition 3 kalimat tajam |

---

## 4. KELEMAHAN KONTEN

### A. Bullet Berbasis Tugas, Bukan Hasil
Hampir semua bullet adalah deskripsi tugas ("Implemented...", "Designed...", "Developing..."), bukan hasil yang terukur.

**Tidak ada satu pun angka di seluruh CV.**

### B. Bahasa Pasif / Lemah
- "Create and manage MySQL database" = tense tidak konsisten (mix present/past)
- "Utilized PHP..." = "Utilized" terlalu umum; lebih baik verba spesifik

### C. Summary Terlalu Generik (v1)
"I am a student... I have strong skills... I am passionate..." = bisa dipakai siapapun. HRD melewatinya tanpa membaca.

### D. Skills Tidak Dikelompokkan & Tidak Ada Section Khusus
Di v1, skills hanya muncul di akhir sebagai campuran webinar + sertifikat + proyek + skor TOEFL. Tidak ada blok Skills yang ATS-parseable.

### E. Tidak Ada Bukti Link
Tidak ada satu pun GitHub link, demo link, atau URL proyek yang bisa di-klik HRD. LPK MORI sudah live di `lpkmoricentre.co.id` — ini harus masuk CV segera.

---

## 5. KELEMAHAN FORMAT / ATS

| Aspek | Temuan | Dampak |
|---|---|---|
| Tidak ada Skills section | Skills hanya tersebar di bullet proyek | ATS keyword match rendah |
| Urutan section tidak optimal | v1: Education > Internship > Projects > Org > Skills | Proyek terkuat (SIAP) terlalu di bawah |
| Panjang v1 | Estimasi >1.5 halaman teks padat | HRD stop baca di halaman 1 |
| Judul proyek inconsistent | Beberapa dengan prefix "FIRST YEAR PROJECT -", sebagian tidak | Kesan tidak rapi |
| Bullet terlalu panjang | Beberapa bullet >3 baris | HRD skip; bullet ideal max 2 baris |
| ATS keywords hilang | "REST API", "Docker", "Testing", "QA", "Git", "GitHub" tidak muncul eksplisit | Bisa gagal filter ATS |
| Tidak ada GitHub / portfolio URL di header | Hanya ada LinkedIn dan email di v1 | Miss peluang klik langsung ke portofolio |

---

## 6. KEKUATAN YANG HARUS DIJUAL (Ranking)

### #1 — Proyek SIAP: End-to-End Production-Grade System
**Ini adalah nilai jual terbesar dan harus jadi proyek teratas di CV.**

Stack: Flutter + Next.js + Golang REST API + PostgreSQL + Docker + WebSocket + NevaCloud VPS

Yang luar biasa untuk fresh grad D3:
- Containerized deployment (Docker) = DevOps awareness
- WebSocket = real-time architecture understanding
- Offline mode + auto-sync = complex state management
- Anti-fake GPS / root detection = mobile security awareness
- BAST PDF auto-generation = business process automation
- 3 role user yang berbeda = role-based access control (RBAC)

ASUMSI: "Built and deployed a production-grade attendance & reporting system serving [ISI: X users] across 3 divisions with Golang backend, Flutter mobile client, and Next.js admin dashboard, containerized via Docker on NevaCloud VPS."

### #2 — Variasi Stack yang Unusually Broad untuk D3
Mobile (Flutter), Web (ReactJS, Next.js), Backend (Laravel, Golang), ML Integration (PyTorch/ConvNeXt), Cloud (EC2), Database (MySQL, PostgreSQL, Firebase Firestore). T-shaped engineer yang langka.

### #3 — Kepemimpinan Terverifikasi
Wakil Ketua HIMATIF + Project Manager di 2 proyek + Deputy Chairman event cadre. Bukan coder murni.

### #4 — ML Integration ke Produksi (Langka untuk D3)
Proyek ConvNeXt Tiny: tahu cara deploy model ML ke production backend (bukan hanya Jupyter notebook). Diferensiasi serius vs fresh grad lain.

### #5 — TOEFL ITP 500 & LPK MORI Go-Live
TOEFL 500 = komunikasi teknis bahasa Inggris terpenuhi. LPK MORI live di domain sendiri = proof of deployment nyata yang bisa dikunjungi HRD sekarang.

---

## 7. GAP KEYWORD

### Frontend Developer
| Ada | Kurang |
|---|---|
| Flutter, ReactJS, Laravel Blade, JavaScript, HTML/CSS | TypeScript, Vue.js, Redux/Bloc/Provider (state mgmt), Responsive Design, Figma/UI Design |

### Fullstack Developer
| Ada | Kurang |
|---|---|
| Laravel, Golang, REST API, Firebase, PostgreSQL, MySQL, Docker | JWT/OAuth, CI/CD, GitHub Actions, Redis, Nginx, Unit Testing, Swagger/OpenAPI, Git workflow |

### Software Tester / QA
| Ada | Kurang |
|---|---|
| TOEFL 500 (komunikasi), variasi proyek (exposure ke banyak sistem) | Postman, Selenium, Jest, Cypress, JUnit, Black-Box Testing, Test Case Writing, Bug Reporting, JIRA/Trello, Regression Testing, API Testing |

> **Rekomendasi untuk posisi Tester**: Jika Anda pernah menggunakan Postman untuk testing API (hampir pasti iya di proyek SIAP/PUSMASIB), tuliskan eksplisit. Jika pernah menulis test cases atau bug reports dalam format apapun, itu nilai jual untuk QA role.

---

## 8. PERTANYAAN HRD SAAT WAWANCARA (10 Pertanyaan)

| # | Pertanyaan HRD | Bagian CV Pemicu |
|---|---|---|
| 1 | "Di proyek SIAP, Anda tulis WebSocket untuk real-time tracking. Bisa jelaskan implementasi koneksi WebSocket antara Golang backend dan Flutter client?" | SIAP — WebSocket |
| 2 | "Anti-fake GPS dan root detection logikanya bagaimana? Library apa yang dipakai di Flutter?" | SIAP — anti-fake GPS/root |
| 3 | "Kenapa pilih Golang untuk backend SIAP, bukan Laravel yang dipakai di proyek lain?" | SIAP vs PUSMASIB — stack choices |
| 4 | "Cara deploy ConvNeXt Tiny ke Golang backend bagaimana? ONNX? API terpisah? Library apa?" | Facial Skin Disease — ML integration |
| 5 | "Di PUSMASIB Anda jadi Fullstack — seberapa besar kontribusi di backend vs frontend? Ada anggota tim lain?" | PUSMASIB — scope of work |
| 6 | "LPK MORI sudah live. Berapa visitor per bulan? Fitur apa yang paling susah diimplementasi?" | LPK MORI — live project |
| 7 | "Anda pernah magang di Flashcom sebagai Frontend Developer. Stack apa yang dipakai? Apa fitur yang Anda deliver?" | Internship Flashcom |
| 8 | "IPK 3.26 dari D3 IT Del. Mata kuliah apa yang paling relevan dengan posisi ini?" | Education |
| 9 | "Sebagai Vice Chairman HIMATIF, program kerja apa yang Anda inisiasi sendiri, bukan warisan pengurus sebelumnya?" | HIMATIF — leadership |
| 10 | "Anda target posisi Tester juga. Metode testing apa yang Anda gunakan di proyek-proyek ini? Pernah nulis test cases formal?" | Target posisi Tester — tidak ada evidence di CV |

> **Catatan untuk pertanyaan #10**: Ini adalah kelemahan terbesar untuk positioning sebagai Tester. CV saat ini tidak ada satu pun evidence testing activity. Harus ditambahkan: "API testing dengan Postman", "manual black-box testing", atau "menulis test cases". Jika tidak ada sama sekali, posisi Tester akan sangat lemah.

---

## 9. REKOMENDASI STRUKTUR CV BARU

```
[HEADER]
Nama | HP | Email | LinkedIn | GitHub | irvanagustriono.my.id

[PROFESSIONAL SUMMARY — 3 kalimat tajam]
Value proposition: Developer (Fullstack/Mobile) + Tester, stack utama, differentiator

[TECHNICAL SKILLS — wajib ada, ATS-parseable]
Languages    : Dart, Golang, PHP, JavaScript/TypeScript, Python, SQL
Frameworks   : Flutter, Laravel (Inertia), ReactJS, Next.js
Backend/API  : Golang REST API, Laravel REST API, Firebase
Databases    : PostgreSQL, MySQL, Firebase Firestore
DevOps/Cloud : Docker, Amazon EC2, NevaCloud VPS
ML/AI        : PyTorch, ConvNeXt Tiny (inference integration)
Testing      : Postman (API), [ISI: tools lain jika ada]
Tools        : Git/GitHub, [ISI: tools lain]

[PROJECTS — urut dampak tertinggi ke terendah]
1. SIAP — Attendance & Reporting System (Golang + Flutter + Docker) <- KILLER PROJECT
2. Facial Skin Disease Classification (ConvNeXt Tiny + Golang + Flutter)
3. PUSMASIB — Community Health Center App (Flutter + Laravel + Firebase)
4. LPK MORI Website — Live: lpkmoricentre.co.id (Laravel Inertia + ReactJS + PostgreSQL)
5. KicksNStyle — Online Shoe Sales App (Flutter + Laravel + Firebase)
6. Roiyall Coffee Website (Laravel + JS + MySQL)
7. AWS EC2 Web Server Configuration (Amazon EC2, Linux, SSH, Security Group)

[INTERNSHIP EXPERIENCE]
- Flashcom Indonesia (Frontend Developer) — [konfirmasi tahun]
- PDAM Tirtanadi Medan (IT Support) — [konfirmasi tahun]

[EDUCATION]
Institut Teknologi Del — D3 Information Technology, GPA 3.26/4.00 (Aug 2023 – Aug 2026)

[ORGANIZATIONAL EXPERIENCE]
- Vice Chairman, HIMATIF, Institut Teknologi Del (2024/2025)
- Deputy Chairman, HIMATIF Cadre Event (Sep 2024)

[CERTIFICATIONS & ACHIEVEMENTS]
- TOEFL ITP 500/677
- Full Stack Application Development Capstone Project (2025)
- Full Stack Software Developer Assessment (2025)
- Developing Front-End Apps with React (2025)
- Software Quality Assurance and Testing Webinar (2025) <- RELEVAN untuk Tester
```

**Panjang target**: 1 halaman padat (9pt–10pt font, margin 1.5cm). Jika SIAP + Facial Skin Disease butuh detail, bisa melebar ke 1.5 halaman maksimal.

**Yang dibuang / dipangkas**:
- Summary v1 yang generik = rewrite total
- Bullet-bullet tugas tanpa aksi spesifik = rewrite ke impact-first
- Webinar listing yang panjang = pilih yang paling relevan saja

---

## CONTOH REWRITE BULLET (SEBELUM SESUDAH)

### 1. PUSMASIB
Sebelum (v1):
"Implementing the frontend using Flutter to ensure high performance and cross-platform (Android/iOS) consistency."

Sesudah:
"Engineered cross-platform mobile UI with Flutter (Dart) for Android/iOS, integrating real-time queue notifications via Firebase Firestore and seamless patient data retrieval from Laravel REST API."

---

### 2. SIAP — Backend
Sebelum (v2):
"Golang (REST API), PostgreSQL, Docker, WebSocket, NevaCloud (VPS)"

Sesudah:
"Architected a Golang REST API backend with WebSocket for real-time attendance tracking, deployed via Docker on NevaCloud VPS, serving 3 user roles (Security, CS, Utility) with role-based access control and PostgreSQL as the primary data store."

---

### 3. LPK MORI
Sebelum (v1):
"Leading the development of an LPK registration information and management system using a modern stack of Laravel Inertia and ReactJS."

Sesudah:
"Built and deployed a live LPK registration & management system (Laravel Inertia + ReactJS + PostgreSQL) at lpkmoricentre.co.id, enabling online student registration and admin data management."

---

### 4. EC2 Project
Sebelum (v2 — salah konten):
Tools: Flutter (Dart), Laravel (PHP) REST API, Firebase

Sesudah:
"Provisioned and configured a public web server on Amazon EC2 (t2.micro, Amazon Linux 2023 AMI); hardened Security Group rules for SSH (22) and HTTP (80); managed remote access via .pem key pair and deployed static web content via SSH."

---

### 5. HIMATIF
Sebelum (v1):
"Leading and managing the organization's operations together with the Chair, responsible for the strategic implementation of work programs..."

Sesudah:
"Coordinated [ISI: X] IT students across [ISI: Y] departments as Vice Chairman, driving technical skill development programs and bridging student–faculty communication."

---

## 10. DAFTAR PERTANYAAN KE USER

| # | Pertanyaan | Urgensi |
|---|---|---|
| 1 | **Magang Flashcom dan PDAM**: Tahunnya 2025 atau 2026? (Di CV ditulis 2026 — apakah sudah terjadi atau rencana?) | KRITIS |
| 2 | **Magang Flashcom**: Stack apa yang dipakai? Fitur apa yang Anda kerjakan? | KRITIS |
| 3 | **Facial Skin Disease**: Tanggal mulai dan selesai yang benar? Status proyek (TA/capstone/mandiri)? Akurasi model ConvNeXt Tiny berapa %? | KRITIS |
| 4 | **SIAP**: Flutter atau React Native? Proyek ini magang/freelance/klien? Nama klien boleh disebut? Berapa user yang pakai? | KRITIS |
| 5 | **Testing/QA evidence**: Pernah pakai Postman? Pernah tulis test case? Pernah lakukan manual testing formal? | KRITIS (untuk Tester role) |
| 6 | **Kontak**: GitHub URL? LinkedIn URL? Portfolio website (irvanagustriono.my.id — masih aktif?)? | PENTING |
| 7 | **LPK MORI**: Tanggal go-live yang tepat? (Nov 2025 atau Des 2025?) | PENTING |
| 8 | **PUSMASIB**: Berapa anggota tim? Peran spesifik Anda (backend berapa %, frontend berapa %)? | PENTING |
| 9 | **Magang PDAM Tirtanadi**: Tugas spesifik apa? Berapa perangkat/user yang ditangani? | PENTING |
| 10 | **Target perusahaan**: Startup? Software house? BUMN digital? Bersedia relokasi / prefer remote? | NICE-TO-HAVE |

---

**Tahap 1 selesai.**

Untuk melanjutkan ke Tahap 2 (penulisan CV baru), jawab minimal pertanyaan 1-5 di atas (KRITIS), terutama:
- Konfirmasi tahun magang (2025 atau 2026?)
- SIAP: Flutter atau React Native?
- Testing/QA: tools apa yang pernah dipakai?
- GitHub / kontak yang mau ditampilkan

**Setelah Anda jawab -> jalankan prompts/02_rewrite_cv.md.**
