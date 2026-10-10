# MEA Ecosystem — Hero Height Test (Stripped)

Versi ringan dari landing MEA Ecosystem, khusus untuk eksperimen
tinggi section hero. Semua section setelah "galaxy-section" (section
kedua) dihapus, dan elemen berat berikut dihilangkan/dijadikan statis:

- Cube 3D (`.hero-cube-col` isinya) — dihapus
- Aurora animasi (`.aurora`) — dihapus
- Marquee ikon produk (`#bloodflowStage`) — dikosongkan (butuh
  `bloodflow.js` yang tidak di-load di sini)
- Semua `<script>` eksternal (landing.js, bloodflow.js, dkk) — TIDAK
  di-load, jadi tombol Akun/ID/Jelajahi Ekosistem tidak fungsional
  (sengaja, sesuai permintaan — ini murni untuk lihat tinggi hero)
- Loading screen — dihapus biar langsung render tanpa delay

CSS yang dipakai (`landing.css`, `token-color.css`, `logo-glow.css`)
adalah COPY PERSIS dari repo asli, tidak diubah sama sekali — supaya
tinggi hero yang kamu lihat di sini representasi akurat dari aslinya.

## Cara pakai di GitHub Pages
1. Push folder ini ke repo GitHub baru (atau branch terpisah)
2. Settings → Pages → source: branch ini, folder root
3. Tunggu beberapa menit, buka link yang diberikan GitHub
4. Bandingkan dengan deploy MEA Study kamu di tab sebelah
