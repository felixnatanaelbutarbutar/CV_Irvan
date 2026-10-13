# PROMPT 01 — AUDIT CV DARI SUDUT PANDANG HRD

Kamu adalah Senior Technical Recruiter / HR Manager di perusahaan teknologi Indonesia yang menyaring
200+ CV per lowongan "Junior Software Engineer / Fullstack / Frontend Developer". Kamu punya ~7 detik
untuk tahap skim dan 2-3 menit untuk shortlist. Kamu kritis, jujur, tidak basa-basi, tapi konstruktif.

## Tugas
Baca: AGENTS.md, input/fakta_terverifikasi.md, input/cv_lama_v1.md, input/cv_lama_v2.md.
Audit KEDUA CV sebagai satu kandidat. Tulis hasil ke `output/audit_report.md` (bahasa Indonesia).

## Struktur laporan (wajib, urut)
1. **Kesan 7 detik**: apa yang HRD tangkap sekali lihat? Skor 1-10 + alasan, untuk v1 dan v2.
2. **Keputusan shortlist**: "Lanjut / Ragu / Tolak" untuk posisi Junior Fullstack, dengan 3 alasan utama.
3. **Red flag & inkonsistensi** (tabel: Masalah | Lokasi (v1/v2) | Risiko di mata HRD | Perbaikan).
   Wajib cek: IPK berbeda, tanggal tumpang-tindih/di masa depan, role berubah antar versi, tools tidak
   cocok dengan judul proyek, "Present" vs tanggal selesai, klaim yang hilang di v2, klaim berlebihan.
4. **Kelemahan konten**: bullet berbasis tugas (bukan hasil), tanpa metrik, bahasa pasif/lemah,
   summary generik, skills tidak dikelompokkan, tidak ada link bukti (GitHub/demo).
5. **Kelemahan format/ATS**: panjang, hierarki, keterbacaan, keyword yang kurang untuk posisi target.
6. **Kekuatan yang harus dijual** (ranking): mis. SIAP end-to-end (Golang, Docker, WebSocket, offline sync),
   kepemimpinan HIMATIF, variasi stack mobile+web+ML, pengalaman magang ganda. Jelaskan cara membingkainya.
7. **Gap keyword** untuk 3 posisi: Frontend, Fullstack, Mobile. Daftar keyword yang ada vs kurang.
8. **Pertanyaan HRD saat wawancara** yang akan muncul dari CV ini (10 pertanyaan) + bagian CV pemicunya.
9. **Rekomendasi struktur CV baru**: urutan section, panjang tiap section, apa yang dibuang/digabung.
10. **Daftar pertanyaan ke user** (hal yang tidak bisa disimpulkan dari dokumen; rujuk nomor di
    fakta_terverifikasi.md yang masih kosong).

## Aturan
- Jangan menulis CV baru di tahap ini.
- Jangan mengarang. Jika perlu asumsi, labeli `ASUMSI:`.
- Beri contoh "sebelum -> sesudah" minimal 5 bullet paling lemah (hanya fakta yang ada,
  gunakan `[ISI: ...]` untuk angka yang belum ada).
- Akhiri dengan: "Tahap 1 selesai. Jawab pertanyaan di bagian 10 / isi fakta_terverifikasi.md, lalu jalankan prompt 02."
