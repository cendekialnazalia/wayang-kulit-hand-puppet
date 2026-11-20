# Wayang Kulit — AI Hand Puppet

Pertunjukan Wayang Kulit interaktif berbasis web menggunakan **MediaPipe AI Hand Tracking (21 3D Hand Landmarks)** dan **2-Bone Inverse Kinematics** pada HTML5 Canvas.

## Fitur Utama
- **Pelacakan Tangan AI Real-Time (MediaPipe Hands)**:
  - **Lingkaran Telapak Tangan**: Menggerakkan posisi badan wayang.
  - **Titik Pink (Ujung Ibu Jari & Jari Telunjuk)**: Menggerakkan kedua tangkai *cempurit* (lengan depan dan lengan belakang wayang) dengan *2-Bone Inverse Kinematics*.
  - **Gesture Peace Sign (`✌️`)**: Mengganti *background* dan adegan wayang secara otomatis (`1 → 2 → 3`).
- **3 Adegan & Tokoh Wayang Berbeda**:
  1. **Bg 1/3 — Teras Rumah Malam**: Wayang Ibu menggendong bayi (tangan kiri) & Ayah membawa mainan kuda-kudaan (tangan kanan).
  2. **Bg 2/3 — Halaman Sekolah**: Wayang Siswi bertas ransel anyaman pink.
  3. **Bg 3/3 — Auditorium Konservasi**: Wayang Pembicara ber-ID Card & membawa tas kerja.
- **Bingkai Layar Tancap Dalang & Musik Pengiring**: Dilengkapi bingkai panggung dalang tradisional, tampilan kamera *live* dengan kerangka tangan AI emas & perak, serta musik pengiring (`Tombol Speaker` / `M`).

## Cara Menjalankan secara Lokal
Jalankan server HTTP lokal di folder proyek ini:

```bash
python3 -m http.server 5173
```

Lalu buka `http://localhost:5173` di browser dan izinkan akses kamera.
