# Portfolio GitHub - Rizqi Ghani Adinata

**Junior Cybersecurity Enthusiast & Junior Data Scientist** — website portofolio bertema **hacker / terminal** dengan animasi serangan siber penuh (simulasi defensif, sandbox, data fiktif).

## Tema & Fitur Visual
- Palet terminal hacker: latar hijau-gelap `#050a07`, aksen fosfor hijau, amber (warning), merah (threat)
- Matrix digital rain (canvas) di seluruh halaman
- Efek glitch RGB pada judul hero + scanline CRT + grid overlay + binary ticker
- Boot sequence terminal mengetik otomatis di hero
- Boot/scroll scramble ("decrypt") pada judul proyek & seksi

## Animasi Serangan Siber (Simulasi — SOC Dashboard)
Kill-chain lengkap 5 fase, berjalan otomatis saat seksi terlihat atau lewat tombol ▶:
1. **Reconnaissance** — nmap sandbox, DNS beacon
2. **Scanning** — SYN stealth, port terbuka
3. **Exploitation** — payload dummy, WAF block, rate-limiter
4. **Exfiltration attempt** — beacon tertahan egress filter
5. **Detection & Mitigation** — SIEM alert, quarantine, hardening → `THREAT NEUTRALIZED ✓`
- Radar sweep + blip, 3 meter live (kill-chain, threat level, integritas defens)
- Kontrol penuh: ▶ Mulai / ❚❚ Jeda / ⟲ Reset, plus tombol global **Animasi ON/OFF**
- Semua IP/host/CVE **fiktif**; `prefers-reduced-motion` dihormati otomatis

## Layout (sesuai spesifikasi)
- Header: nama, spesialisasi, navigasi seksi bernomor `[01]…[05]` (sticky, menu hamburger di mobile)
- Hero: heading besar + bio & status terkini di kanan (terminal + panel bio)
- Grid desktop: kartu proyek 2 kolom di kiri; timeline karier, skill tags, kontak di kanan
- Kartu proyek: nama, kategori, tahun, pratinjau visual SVG animatif → klik membuka modal `<dialog>` (latar belakang, tanggung jawab, hasil) dengan tombol TUTUP + Esc + decrypt animation
- Mobile/tablet: semuanya menumpuk dalam urutan baca, scroll vertikal bebas
- Aksesibilitas: HTML semantik, focus-visible, label form, `aria-live`, skip-link

## Data & Kejujuran Konten
- Info riil (dari pemilik): nama, spesialisasi, skill, WhatsApp `0895-6226-68417`, GitHub `ghani24ep10007-spec`
- Email: **PENDING** — belum disediakan
- **6 kartu proyek = proyek riil** dari GitHub (gonet-jaya-abadi, Containerized-BI-Telemetry-System, UAS-DataScience-Toolkit, Ai-chatbot, auto-portfolio-generator, seri SIAKAD/web) dengan tautan sumber di tiap modal; timeline karier disusun dari riwayat repo nyata
- Tidak ada award/testimoni/angka performa fiktif yang diklaim sebagai nyata
- Form kontak tanpa server: menyusun pesan lalu membuka WhatsApp

## Kontak & Kolaborasi
* **Telepon/WhatsApp:** 0895622668417
* **Link Website Portofolio:** [Lihat Portofolio Live](https://ghani24ep10007-spec.github.io/portofolio/)

## Menjalankan
Buka `index.html` langsung di browser — tanpa build, tanpa CDN, tanpa dependensi eksternal.

## Automation Lokal
Automation Qoder cron berjalan tiap jam untuk memilih pekerjaan portofolio berikutnya (lihat daftar Automation di Qoder).
