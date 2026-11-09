# Low Poly 3D Animation Pipeline & Rules

Repositori ini berisi panduan, parameter visual, dan aset referensi karakter untuk memastikan seluruh pembuatan aset 3D dan video bernuansa **Low Poly** tetap konsisten secara gaya, geometri, dan pencahayaan.

---

## 1. Core Visual Style (Aturan Utama)
Setiap *prompt* atau generasi aset **wajib** mematuhi parameter teknis berikut:
* **Geometry:** *Strict low-poly 3D*, *faceted geometry*, *sharp polygon edges*, *visible triangular and quad faces*, *blocky/geometric proportions*.
* **Shading & Texture:** *Flat shading*, *untextured vertex colors*, *matte plastic finish*, *no smooth smoothing groups*.
* **Lighting:** *Clean studio daylight*, *global illumination*, *soft ambient occlusion*.

---

## 2. Character Registry & References
Gunakan parameter deskripsi dan file referensi berikut saat memanggil karakter:

| ID Karakter | Nama / Deskripsi Visual | File Turnaround / Asset |
| :--- | :--- | :--- |
| `char_elder` | Explorer tua berambut abu-abu kotak, topi jerawat/safari, kacamata tebal | `image_7bf590.jpg` |
| `char_01` | Rusa berekor/bertanduk biru toska, telinga merah muda | `karakter_01_biru_toska.png`[cite: 3] |
| `char_02` | Kelelawar ungu, mata merah menyala, syal cokelat | `karakter_02_kelelawar_ungu.png`[cite: 4] |
| `char_03` | Makhluk berjanggut putih runcing, tanduk belang cokelat | `karakter_03_janggut_putih.png`[cite: 5] |
| `char_04` | Makhluk oranye-tan, rambut putih asimetris, tanduk tinggi | `karakter_04_oranye_rambut_putih.png`[cite: 6] |
| `char_05` | Makhluk krem/putih, tanduk cokelat gelap, bulu bergerigi | `karakter_05_krem_tanduk_cokelat.png`[cite: 7] |
| `char_06` | Bayi naga merah, duri punggung cokelat batu, sayap bersudut | `karakter_06_naga_merah.png`[cite: 8] |

---

## 3. Environment & Props Parameters
* **Sawah / Pedesaan:** *Stepped polygonal terrain*, *geometric cubic/pyramidal rice crops*, *blocky wooden fences*, *low-poly polygonal chickens*.
* **Struktur Bangunan:** *Cubic structures*, *angular roofs*, *modular block architecture*.

---

## 4. Prompt Template Structure
Gunakan format standar ini saat memberikan instruksi baru ke model:

> **[Gaya Visual]:** Strict low-poly 3D animation, flat-shaded faceted geometry...
> **[Subjek]:** [Sebutkan ID Karakter atau deskripsinya]...
> **[Aksi & Lingkungan]:** [Deskripsikan aktivitas di dalam lingkungan low-poly]...
> **[Kamera]:** [Sebutkan pergerakan kamera atau *angle*]...
