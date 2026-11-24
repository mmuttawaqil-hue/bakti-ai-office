# BAKTI AI OFFICE — Tahap 1

Ini adalah prototipe visual 3D interaktif berbasis browser.

## Menjalankan di komputer
1. Ekstrak ZIP.
2. Buka folder `bakti_ai_office_stage1`.
3. Jalankan server lokal (disarankan VS Code + ekstensi Live Server), lalu buka `index.html`.
   Alternatif: `python -m http.server 8000` dari folder ini, lalu buka http://localhost:8000.
4. Internet diperlukan untuk memuat Three.js dari CDN.

## Fitur prototipe
- Model kantor isometrik 3D.
- Orbit: seret untuk memutar, scroll/pinch untuk zoom.
- Klik/ketuk ruangan untuk melihat detail divisi.
- Panel informasi responsif untuk desktop dan HP.

## Batasan tahap 1
Ini masih prototipe visual. Label agen adalah rancangan, belum terhubung ke Gemini API, n8n, database, atau TikTok.
Tahap berikutnya: finalisasi layout, deploy hosting HTTPS, lalu bangun backend dan integrasi AI dengan pengamanan API key.
