# Catatan Pekerjaan Otomatis — Portofolio Rizqi

Jurnal berjalan (append-only). Setiap jam automation memilih SATU pekerjaan berikutnya, mencatat alasan, lalu pekerjaan itu dikerjakan di sesi berikutnya. `index.html` TIDAK diubah oleh sesi pencatatan ini.

---

## 2026-09-29 22:57 UTC

**Pekerjaan terpilih:** Paket metadata berbagi & SEO — tag Open Graph (`og:title`, `og:description`, `og:type=profile`), `twitter:card`, `theme-color`, dan JSON-LD skema `Person` (nama, `jobTitle`, `knowsAbout`, `sameAs` → GitHub riil) di `<head>` index.html.

**Alasan prioritas:** Satu-satunya peningkatan bernilai tinggi yang bisa dikerjakan mandiri tanpa data baru. Konten DEMO dan email PENDING butuh informasi riil dari pemilik (mengarang = melanggar komitmen kejujuran konten di README), sedangkan kesiapan aksesibilitas (`aria-hidden`, focus-visible, skip-link, reduced-motion) dan arsitektur animasi sudah baik. Website ini dibagikan lewat WhatsApp/sosial (form kontak pun membuka WA) — tanpa OG tag, tautan portofolio tampil polos saat dikirim ke rekruter.

**Langkah konkret:**
1. Tambahkan 6–8 tag OG/Twitter + `theme-color` `#050a07` di `<head>`, isi dari data riil yang sudah ada (nama, spesialisasi, GitHub `ghani24ep10007-spec`) — tanpa image/URL fiktif.
2. Tambahkan blok `<script type="application/ld+json">` skema `Person` di penutup `<head>`.
3. Validasi: buka di browser (tanpa error konsol) + cek struktur JSON-LD via validator schema.org.
