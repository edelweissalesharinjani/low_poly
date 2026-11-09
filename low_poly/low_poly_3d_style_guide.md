# Low Poly 3D Master Rules & Character Database

Dokumen ini adalah panduan parameter wajib (*system rules*) untuk memastikan seluruh pembuatan gambar dan video tetap konsisten dalam gaya **Strict Low Poly 3D**.

---

## 1. Core Visual Rules (Wajib Dipatuhi)
Setiap *output* visual harus mengikuti parameter teknis berikut:
* **Geometri (Mesh):** `strict low-poly 3D`, `faceted geometry`, `sharp polygon edges`, `visible triangular and quad faces`, `blocky proportions`.
* **Material & Tekstur:** `flat shading`, `untextured vertex colors`, `matte paper/plastic finish`, `zero smoothing groups`.
* **Pencahayaan:** `soft global illumination`, `clean ambient occlusion`, `minimalist 3D render`, `stylized daylight`.
* **Negative Prompt (Dilarang):** `smooth curves, realistic textures, photorealistic, high-poly, fur/hair strands, bump maps, normal maps, Subdivision Surface, blurry edges`.

---

## 2. Character Registry (Database Karakter)
*Lokasi Direktori Lokal: `D:\low_poly\karakter`*

### A. Karakter Utama (Human)
* **ID Panggilan:** `[CHAR_MAIN]`
* **Deskripsi Visual:** `blocky low-poly character, boxy torso, angular explorer hat, thick polygonal glasses, grey faceted hair, segmented tubular limbs, brown shorts and orange-brown shirt`.

### B. Karakter Pendamping (Creatures)
1. **`[CHAR_01_RUSATOSKA]`** (`karakter_01_biru_toska.png`)
   * **Parameter:** `small teal-blue low-poly quadruped creature, two angular antlers, wide rounded low-poly ears with pink insides, dark round eyes, faceted geometric body`.
2. **`[CHAR_02_KELELAWAR]`** (`karakter_02_kelelawar_ungu.png`)
   * **Parameter:** `small purple low-poly bat-like creature, large angular ears with pink inner facets, glowing red polygonal eyes, small purple bat wings, brown geometric neck bandana`.
3. **`[CHAR_03_JANGGUTPUTIH]`** (`karakter_03_janggut_putih.png`)
   * **Parameter:** `small low-poly creature with white faceted hair and pointed white geometric beard, curved brown-striped horns, peach-colored body, dark brown hooves`.
4. **`[CHAR_04_ORANYERAMBUT]`** (`karakter_04_oranye_rambut_putih.png`)
   * **Parameter:** `small tan-orange low-poly creature, asymmetrical white faceted hair covering one side, tall upward-curved light orange horns, red-tipped geometric ears, small back wings`.
5. **`[CHAR_05_KREMTANDUK]`** (`karakter_05_krem_tanduk_cokelat.png`)
   * **Parameter:** `small cream-white low-poly creature, dark brown angular horns, jagged polygonal fur around chest and cheeks, thin skeletal-like geometric wings`.
6. **`[CHAR_06_NAGAMERAH]`** (`karakter_06_naga_merah.png`)
   * **Parameter:** `small bright red low-poly baby dragon, brown rocky geometric spikes on top of head, sharp angular red wings, cream polygonal belly patch, fierce dark eyes`.

*(Tambahkan karakter baru di bawah baris ini sesuai kebutuhan)*

---

## 3. Environment & Prop Presets (Lingkungan)
* **`[ENV_SAWAH]`:** `stepped polygonal rice fields, geometric green paddy plants, blocky dirt paths, cubic low-poly chickens, faceted distant mountains`.
* **`[ENV_KAMPUNG]`:** `low-poly village under construction, blocky wooden houses, geometric trees, polygonal dirt road, flat-shaded stone wells`.

*(Tambahkan lokasi baru di bawah baris ini sesuai kebutuhan)*

---

## 4. Master Prompt Template (Cara Penggunaan)
Salin format di bawah ini saat memberikan instruksi pembuatan gambar/video:

> **[STYLE]:** Strict low-poly 3D animation, flat-shaded faceted geometry, visible sharp polygon edges, matte solid colors, zero smooth textures, soft global illumination.
> 
> **[SUBJECT]:** [Masukkan deskripsi dari ID Karakter di atas]
> 
> **[ENVIRONMENT]:** [Masukkan deskripsi dari Preset Lingkungan di atas]
> 
> **[ACTION & CAMERA]:** [Tulis adegan, pergerakan karakter, sudut kamera, dan durasi]