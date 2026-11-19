# ⚡ EnergiBijak - Website Kampanye Hemat Energi

Website kampanye edukasi dan aksi konservasi energi di lingkungan sekolah berbasis data angket riil 636 siswa kelas XI. Proyek ini dikembangkan sebagai tugas projek PPLG yang terintegrasi dalam 3 fase utama.

---

## 📂 Struktur Proyek

```text
website_kampanye_hemat_energi/
│
├── index.html                  # Halaman Beranda (Pengantar & Alur Kampanye)
├── tentang.html                # Halaman Tentang (Tujuan & Urgensi Kampanye)
├── data.html                   # Halaman Data & Fakta (Visualisasi Chart.js Fase 2)
├── aksi.html                   # Halaman Aksi & Rekomendasi (Fase 3 & Tantangan 7 Hari)
│
├── css/
│   └── style.css               # Desain tata letak responsif dan palet ramah lingkungan
│
├── js/
│   ├── script.js               # Logika Chart.js & Tantangan Interaktif 7 Hari
│   └── data-perilaku-energi.js # Salinan data kuesioner (offline/file fallback)
│
├── data/
│   ├── data-perilaku-energi.json # Dataset utama hasil survei 636 siswa (JSON)
│   └── data.json               # Salinan dataset kuesioner energi
│
└── README.md                   # Dokumentasi proyek
```

---

## 🚀 Fitur Setiap Fase

### 1. Fase 1 — Menarik Perhatian & Edukasi Awal (`index.html` & `tentang.html`)
* Hero banner interaktif dan pengenalan prinsip hemat energi (*Perhatikan, Kurangi, Bertindak*).
* Alur kampanye terpadu 3 fase yang saling terhubung.

### 2. Fase 2 — Menyajikan Bukti Data Nyata (`data.html`)
* Data riil kuesioner dari 636 responden siswa kelas XI (partisipasi 99.4%).
* Integrasi **Chart.js via CDN** tanpa instalasi tambahan.
* 4 Visualisasi Grafik:
  1. **Grafik 1 (Horizontal Bar):** Rerata skor 10 butir indikator perilaku (P01–P10) dengan sorotan butir terendah (P04 & P09).
  2. **Grafik 2 (Doughnut):** Distribusi kategori perilaku siswa (Sangat Baik 59.4%, Baik 36.8%, Cukup 3.6%, Kurang 0.2%).
  3. **Grafik 3 (Bar Chart):** Komparasi skor per kejuruan (PMN tertinggi 3.51, PPLG & MPLB 3.24).
  4. **Grafik 4 (Bar Chart):** Rata-rata skor per rayon sekolah.
* Kalimat singkat (1–2 kalimat) penjelas temuan data di bawah setiap grafik.

### 3. Fase 3 — Rekomendasi & Ajakan Aksi (`aksi.html`)
* **5 Rekomendasi Konkret Berbasis Temuan Data:**
  - Standar penggunaan gawai & laptop (Fokus Butir P04 - skor 3.22).
  - Gerakan *Peer Reminder* & Duta Energi Bergilir (Fokus Butir P09 - skor 3.22).
  - Mobilitas hijau & *carpooling* rayon (Fokus Butir P05 - skor 3.30).
  - Prosedur 5-Jari ruangan & lab sebelum pulang (Fokus Butir P03 & P10).
  - Pemanfaatan cahaya alami & suhu pendingin optimal 25°C (Fokus Butir P07 & P08).
* **Ajakan Bertindak (Tantangan Hemat Energi 7 Hari):** Checklist interaktif harian dengan *progress bar* dinamis yang tersimpan di `localStorage` peramban.

---

## 💻 Cara Menjalankan Website
1. Buka file `index.html` langsung di peramban web (Google Chrome, Microsoft Edge, Firefox, dll).
2. Anda juga dapat menjalankannya lewat ekstensi **Live Server** di VS Code.
