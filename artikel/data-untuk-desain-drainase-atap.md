---
article_id: RFM-08-A02
title: "Data yang Dibutuhkan untuk Merancang Drainase Atap"
slug: "data-untuk-desain-drainase-atap"
description: "Kumpulkan sumber curah hujan, geometri tangkapan air, lereng, alur lembah, titik keluar, limpahan, penyumbatan, jalur buangan, pemeliharaan, dan ketidakpastian iklim."
status: draft
publication_date: "2025-12-20"
publication_date_basis: editorial_backfill
date_modified: null
writing_contract_version: native-id-v2
parent_topic: RFM-08
primary_intent: "Prepare drainage inputs"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/data-untuk-desain-drainase-atap.html"
technical_review: required
sources:
  - "https://www.astm.org/membership-participation/technical-committees/committee-e06/subcommittee-e06/jurisdiction-e0657"
  - "https://store.astm.org/e1646-95r24.html"
  - "https://www.iso.org/standard/51615.html"
---

# Data yang Dibutuhkan untuk Merancang Drainase Atap

Halo, Kawan Besi.co.id!

Sebelum Anda memilih ukuran talang atau diameter pipa buang, ada satu langkah yang sering dilewati: **mengumpulkan data yang benar**. Kesalahan dalam menentukan ukuran drainase atap bukan hanya soal talang yang meluap—ia bisa berujung pada genangan di permukaan atap, beban tambahan yang tidak direncanakan, kebocoran di sambungan, bahkan kerusakan struktural. Dan kesalahan paling umum bukan salah hitung, tapi salah input.

Data yang dibutuhkan untuk merancang drainase atap meliputi: **intensitas curah hujan lokal, geometri area tangkapan air, kemiringan dan arah alur, titik-titik keluar (outlet), rencana limpahan (overflow), potensi penyumbatan, jalur buangan ke sistem drainase kota, jadwal pemeliharaan, serta margin untuk ketidakpastian iklim**. Data ini bukan sekadar angka—ia adalah asumsi desain yang menentukan apakah sistem drainase akan bekerja selama 20 tahun ke depan atau gagal pada hujan deras pertama.

Namun, perlu dipahami bahwa data ini hanya sebagus sumbernya. Intensitas curah hujan dari BMKG mungkin berbeda dari data lokal yang terukur. Geometri atap dari gambar konsep mungkin berbeda dari kondisi terbangun. ASTM E06.57 tentang standar sistem atap logam mengingatkan bahwa kinerja sistem atap—termasuk drainase—bergantung pada konfigurasi spesifik, bukan label generik ([ASTM E06.57](https://www.astm.org/membership-participation/technical-committees/committee-e06/subcommittee-e06/jurisdiction-e0657)).

![Ilustrasi atap seng gelombang warna](/wp-content/uploads/2026/03/atap-seng-gelombang-warna.jpg)
*Foto ilustrasi: aset lokal, bukan dokumentasi proyek tertentu.*

<!-- BEGIN MANAGED IMAGE PLAN
- **Image ID:** LOCAL-001
- **Source type:** local
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi atap seng gelombang warna](/wp-content/uploads/2026/03/atap-seng-gelombang-warna.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies atap seng gelombang warna as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, leave a review marker and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Definisi dan batas objek

Artikel ini membahas **data input** yang harus dikumpulkan sebelum proses hidrolik dimulai—untuk memahami bagaimana air bergerak di permukaan atap, lihat juga [artikel Peta Jalur Air Atap Metal](/artikel/peta-jalur-air-atap-metal.html)—bukan perhitungan ukuran talang, pipa, atau kapasitas pompa. Perhitungan itu adalah domain engineer hidrolik yang memiliki metode, software, dan tanggung jawab profesional sendiri. Yang kita bahas di sini adalah: apa saja yang harus Anda siapkan sebelum duduk bersama engineer untuk mendesain sistem drainase.

Data yang kita bahas meliputi sembilan kategori: curah hujan, geometri tangkapan, kemiringan dan alur, outlet, overflow, penyumbatan, jalur buangan, pemeliharaan, dan ketidakpastian iklim. Setiap kategori punya sumber data, tingkat akurasi, dan konsekuensi jika salah. ASTM E1646-95r24 tentang pengukuran dan verifikasi panel atap mengingatkan bahwa profil panel atau label generik tidak menentukan kinerja aktual—yang menentukan adalah konfigurasi terpasang yang terverifikasi ([ASTM E1646-95r24](https://store.astm.org/e1646-95r24.html)).

Sobat Besi.co.id, batas ini penting: artikel ini tidak akan memberi Anda angka desain. Yang akan Anda dapatkan adalah daftar pertanyaan dan sumber data yang harus Anda jawab dan kumpulkan sebelum desain dimulai.

## Cara kerjanya

Proses pengumpulan data drainase dimulai dari **gambar arsitektur dan struktural**. Dari gambar ini, Anda bisa menentukan geometri atap: luas area tangkapan (catchment area), kemiringan (slope), arah alur air, dan lokasi titik-titik rendah (valley) di mana air berkumpul. Untuk atap metal dengan profil gelombang, air mengalir mengikuti lembah gelombang—jadi arah pemasangan panel menentukan arah alur.

**Langkah kedua** adalah menentukan **intensitas curah hujan desain**. Data ini biasanya diperoleh dari BMKG atau data historis lokal. Yang dibutuhkan bukan rata-rata tahunan, tapi intensitas untuk durasi tertentu (misalnya 5 menit, 15 menit, 60 menit) dengan periode ulang tertentu (misalnya 10 tahun atau 25 tahun). Semakin penting bangunan, semakin lama periode ulang yang dipilih.

**Langkah ketiga** adalah menentukan **lokasi dan ukuran outlet**. Outlet adalah titik di mana air keluar dari permukaan atap—bisa berupa talang (gutter), pipa dalam (downpipe internal), atau pipa luar (external downpipe). Jumlah, ukuran, dan lokasi outlet menentukan jarak maksimum yang harus ditempuh air di permukaan atap sebelum mencapai outlet.

**Langkah keempat** adalah merencanakan **sistem limpahan (overflow)**. Jika outlet tersumbat atau kapasitasnya terlampaui, ke mana air akan pergi? Tanpa rencana overflow, air bisa masuk ke dalam bangunan atau menyebabkan beban berlebih pada struktur atap.

Teman Besi.co.id, keempat langkah ini harus diselesaikan *sebelum* Anda memesan talang atau pipa. Mengubah ukuran atau lokasi outlet setelah material tiba di lokasi bisa sangat mahal.

## Faktor yang mengubah hasil

Beberapa faktor bisa mengubah data yang Anda kumpulkan dan cara Anda menggunakannya. **Pertama, topografi lokal.** Bangunan di lereng bukit punya pola aliran air yang berbeda dari bangunan di dataran. Air dari lereng atas bisa menambah volume yang harus ditangani drainase atap. **Kedua, vegetasi sekitar.** Pohon di dekat bangunan menghasilkan daun dan serpihan yang bisa menyumbat talang. Di kawasan dengan banyak pohon, interval pembersihan talang harus lebih pendek.

**Ketiga, iklim mikro.** Jakarta dan Surabaya punya pola hujan yang berbeda dari Bandung atau Medan. Data curah hujan harus spesifik untuk lokasi, bukan nasional. **Keempat, jenis atap.** Atap metal dengan profil tinggi punya kapasitas aliran yang berbeda dari atap metal datar ([lihat artikel Menghitung Kebutuhan Panel Atap](/artikel/menghitung-kebutuhan-panel-atap.html)). Kemiringan atap juga memengaruhi kecepatan aliran—semakin curam, semakin cepat air mencapai outlet, tapi semakin besar energi kinetik yang harus diatasi di outlet.

**Kelima, perubahan iklim.** Data historis mungkin tidak lagi representatif untuk desain umur bangunan 30–50 tahun ke depan. ISO 2063-1:2019 tentang pelapisan logam termal mengingatkan bahwa desain harus mempertimbangkan kondisi sepanjang umur bangunan, bukan hanya kondisi saat ini ([ISO 2063-1:2019](https://www.iso.org/standard/51615.html)).

## Contoh keputusan praktis

Bayangkan dua skenario. **Skenario A:** Gudang seluas 2.000 m² di Jakarta dengan atap metal kemiringan 5%. Menggunakan data BMKG untuk intensitas hujan 5 menit dengan periode ulang 10 tahun, Anda menghitung kebutuhan talang dan outlet. **Skenario B:** Gedung kantor seluas 500 m² di Bandung dengan atap metal kemiringan 15% dan beberapa valley. Selain data BMKG, Anda perlu mempertimbangkan alur air di valley, potensi genangan di area datar, dan rencana overflow jika outlet utama tersumbat.

Dalam skenario A, data yang dibutuhkan relatif sederhana—luas atap, intensitas hujan, dan lokasi outlet. Dalam skenario B, data yang dibutuhkan lebih kompleks—termasuk geometri valley, profil air di setiap segmen, dan rencana darurat. Kawan Besi.co.id, jangan menggunakan pendekatan sederhana untuk kasus kompleks hanya karena lebih cepat.

## Kesalahan umum dan cara memeriksanya

Kesalahan paling umum adalah **menggunakan rata-rata curah hujan tahunan sebagai data desain**. Rata-rata tahunan tidak memberi tahu Anda tentang intensitas hujan lebat singkat yang bisa meluapkan talang. Yang dibutuhkan adalah intensitas untuk durasi pendek (5–60 menit) dengan periode ulang yang sesuai.

Kesalahan kedua adalah **tidak mempertimbangkan penyumbatan**. Talang yang berfungsi sempurna dalam kondisi bersih bisa gagal total jika setengah tersumbat oleh daun atau serpihan. Desain yang baik mempertimbangkan "kapasitas tersumbat sebagian" sebagai kondisi operasi normal.

Kesalahan ketiga adalah **mengabaikan rencana overflow**. Ketika outlet utama tersumbat atau kapasitasnya terlampaui, air harus punya jalan alternatif. Tanpa rencana overflow, air bisa masuk ke dalam bangunan atau menyebabkan kerusakan struktural. Sobat Besi.co.id, tanyakan pada diri sendiri: "Jika talang utama tersumbat, ke mana air akan pergi?" Jika Anda tidak bisa menjawab, desain Anda belum selesai.

## Jalan pintas yang perlu diwaspadai

Jalan pintas yang sering muncul: **"Pakai ukuran talang yang sama dengan proyek sebelumnya."** Alasannya terdengar efisien—jika talang ukuran X berhasil di proyek A, seharusnya berhasil juga di proyek B. Tapi setiap proyek punya kombinasi unik dari luas atap, kemiringan, intensitas hujan lokal, dan jumlah outlet. Talang yang cukup untuk 1.000 m² atap belum tentu cukup untuk 2.000 m² atap, meskipun di lokasi yang sama.

Alternatif yang lebih aman: kumpulkan data untuk setiap proyek, meskipun terasa repetitif. Investasi waktu 1–2 hari untuk pengumpulan data bisa mencegah berminggu-minggu perbaikan setelah atap bocor.

## Kesimpulan

Data yang dibutuhkan untuk merancang drainase atap bukan sekadar angka dari tabel—ia adalah asumsi desain yang menentukan apakah sistem akan bertahan selama umur bangunan. Data meliputi curah hujan lokal, geometri atap, kemiringan dan alur, outlet, overflow, potensi penyumbatan, jalur buangan, pemeliharaan, dan ketidakpastian iklim.

Langkah Anda selanjutnya: buat checklist sembilan data di atas dan kumpulkan untuk proyek Anda. Diskusikan dengan engineer hidrolik tentang sumber data yang paling sesuai dan margin keamanan yang diperlukan. Ingat bahwa batas pengetahuan ini adalah: artikel ini tidak menggantikan perhitungan hidrolik profesional untuk ukuran talang dan pipa—ia hanya memastikan Anda punya data yang benar untuk memulai perhitungan itu.
