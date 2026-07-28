---
article_id: RFM-08-A03
title: "Slope, Roof Length, dan End Lap pada Panel Metal"
slug: "slope-roof-length-dan-end-lap"
description: "Jelaskan hubungan antara kemiringan, panjang atap, dan kebutuhan end lap untuk panel metal."
status: draft
publication_date: "2025-12-25"
publication_date_basis: editorial_backfill
date_modified: null
writing_contract_version: native-id-v2
parent_topic: RFM-08
primary_intent: "Coordinate panel geometry"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/slope-roof-length-dan-end-lap.html"
technical_review: required
sources:
  - "https://www.astm.org/membership-participation/technical-committees/committee-e06/subcommittee-e06/jurisdiction-e0657"
  - "https://store.astm.org/e1646-95r24.html"
  - "https://www.iso.org/standard/38882.html"
  - "https://pesta.bsn.go.id/produk/detail/12927-sni17272020"
---

# Slope, Roof Length, dan End Lap pada Panel Metal

Halo, Kawan Besi.co.id!

Ketika panjang atap melebihi panjang panel yang tersedia, **end lap** (tumpang ujung) diperlukan. Tapi berapa overlap yang dibutuhkan? Itu tergantung pada **kemiringan atap (slope)**—semakin landai, semakin besar overlap yang dibutuhkan karena air bergerak lebih lambat dan punya lebih banyak waktu untuk menembus celah. Salah menentukan end lap bisa berarti kebocoran di setiap sambungan.

Jawaban singkatnya: **end lap minimum tergantung pada kemiringan—semakin landai, semakin besar overlap yang dibutuhkan**. Atap curam (>15°) mungkin hanya butuh 150mm; atap landai (<10°) mungkin butuh 250mm atau lebih. Spesifikasi pabrikan adalah acuan utama. ASTM E06.57 tentang standar sistem atap mengingatkan bahwa detail sambungan adalah bagian integral dari sistem ([ASTM E06.57](https://www.astm.org/membership-participation/technical-committees/committee-e06/subcommittee-e06/jurisdiction-e0657)).

Namun, end lap juga dipengaruhi oleh: jenis profil panel (gelombang tinggi vs. rendah), kondisi angin (tekanan angin bisa mendorong air ke belakang sambungan), dan kualitas sealant (sealant di dalam sambungan berfungsi sebagai pengaman tambahan). ASTM E1646-95r24 tentang pengukuran panel atap memberikan panduan verifikasi dimensi ([ASTM E1646-95r24](https://store.astm.org/e1646-95r24.html)).

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

**Slope** (kemiringan) adalah sudut atap dari horizontal—dinyatakan dalam derajat atau persentase (misalnya 10° atau 17.6%). **Roof length** (panjang atap) adalah jarak dari eave (talang) ke ridge (puncak) sejajar kemiringan. **End lap** (tumpang ujung) adalah overlap antar panel di sambungan ujung.

Hubungan ketiganya: ketika roof length > panjang panel, end lap diperlukan. Ketebalan end lap tergantung pada slope—semakin landai, semakin besar end lap yang dibutuhkan. SNI 1727:2020 tentang pembebanan memberikan konteks tentang beban yang harus dipertimbangkan ([SNI 1727:2020](https://pesta.bsn.go.id/produk/detail/12927-sni17272020)).

Apa yang *bukan* cakupan artikel ini adalah perhitungan struktural panel—itu domain engineer. Artikel ini fokus pada **hubungan antara slope, roof length, dan end lap**. ISO 9001:2015 tentang sistem manajemen mutu mendukung pendekatan berbasis data ([ISO 9001:2015](https://www.iso.org/standard/38882.html)).

## Cara kerjanya

**Langkah 1: Tentukan slope.** Periksa gambar arsitektur—sudut atau persentase kemiringan atap. **Langkah 2: Tentukan roof length.** Ukur jarak dari eave ke ridge sejajar kemiringan (bukan horizontal).

**Langkah 3: Tentukan panjang panel.** Periksa ketersediaan panel dari pabrikan—berapa panjang maksimum yang bisa diproduksi dan diangkut? **Langkah 4: Hitung kebutuhan end lap.** Jika roof length > panjang panel, bagi menjadi beberapa segmen dan tentukan end lap berdasarkan slope.

## Faktor yang mengubah hasil

**Pertama, slope.** Semakin landai, semakin besar end lap—karena air bergerak lebih lambat. **Kedua, jenis profil.** Profil dengan gelombang tinggi mungkin butuh end lap lebih besar karena air bisa mengalir di bawah gelombang.

**Ketiga, kondisi angin.** Di lokasi dengan angin kencang, tekanan angin bisa mendorong air ke belakang sambungan—end lap perlu lebih besar. **Keempat, sealant.** Sealant di dalam sambungan berfungsi sebagai pengaman tambahan—tapi bukan pengganti end lap yang benar.

## Contoh keputusan praktis

Bayangkan dua skenario. **Skenario A:** Atap gudang dengan slope 15°, roof length 8m, panel tersedia 6m. Perlu 2 segmen: 6m + 2m + end lap. End lap 150mm cukup karena slope cukup curam. **Skenario B:** Atap pabrik dengan slope 5°, roof length 20m, panel tersedia 6m. Perlu 4 segmen dengan end lap. End lap 250mm atau lebih dibutuhkan karena slope landai.

Dalam skenario A, end lap relatif kecil. Dalam skenario B, end lap signifikan—dan setiap sambungan adalah potensi kebocoran. Kawan Besi.co.id, semakin landai atap, semakin kritis end lap.

## Kesalahan umum dan cara memeriksanya

Kesalahan paling umum adalah **menggunakan end lap yang sama untuk semua slope**. End lap yang cukup untuk slope 20° mungkin tidak cukup untuk slope 5°.

Kesalahan kedua adalah **tidak mempertimbangkan arah dominan hujan**. Jika hujan sering datang dari arah tertentu, end lap harus menghadap menjauhi arah itu.

Kesalahan ketiga adalah **mengandalkan sealant sebagai pengganti end lap**. Sealant berfungsi sebagai pengaman tambahan, bukan pengganti—end lap harus cukup tanpa sealant.

## Jalan pintas yang perlu diwaspadai

Jalan pintas yang berbahaya: **"Panel panjang saja, tidak perlu end lap."** Alasannya terdengar logis—jika panel cukup panjang, mengapa perlu sambungan? Tapi panel sangat panjang punya tantangan transport dan handling yang signifikan—lihat [artikel Panel Panjang: Batas Transport, Handling, dan Roof Layout](/artikel/panel-panjang-transport-dan-layout.html).

Alternatif yang lebih aman: rencanakan end lap berdasarkan slope dan kondisi lokal. Gunakan spesifikasi pabrikan sebagai acuan.

## Menguji keputusan end lap pada potongan memanjang

Gambar potongan memanjang memperlihatkan apakah air bertemu sambungan saat bergerak menuruni lereng. Tandai arah aliran, posisi tumpuan, ujung panel, dan ruang untuk bekerja. End lap bukan sekadar angka overlap; ia adalah detail yang harus cocok dengan profil, seal, pengikat, panjang lereng, dan kondisi angin. Nilai minimum harus datang dari detail pabrikan yang disetujui, bukan kebiasaan di proyek lain.

Jika panjang panel melebihi kemampuan transport, pecah panjangnya dengan sadar dan catat alasan setiap sambungan. Periksa apakah sambungan berada di atas tumpuan dan dapat diakses untuk inspeksi. Perubahan panjang juga memengaruhi gerakan termal dan urutan pemasangan. Tahan pemesanan ketika kemiringan aktual belum diukur atau data kompatibilitas belum diterima.

Teman Besi.co.id, cocokkan potongan dengan peta jalur air atap metal dan perhitungan kebutuhan panel. Kedua langkah itu membantu menguji geometri dan kuantitas tanpa mengarang ukuran lap atau kemiringan.

## Menyiapkan data sebelum meminta detail pabrikan

Kirimkan kemiringan terukur, panjang lereng, profil panel, posisi tumpuan, kondisi angin, dan rencana transport kepada pabrikan. Sertakan gambar peta jalur air dan takeoff panel agar detail end lap dapat dibaca dalam konteks. Jangan meminta angka lap terpisah dari sistem yang akan dipasang.

## Memastikan sambungan dapat diperiksa

Rencanakan akses untuk melihat ujung lap setelah panel terpasang dan setelah hujan pertama. Catat foto sambungan, kondisi seal, dan posisi pengikat sebagai baseline. Jika sambungan tertutup komponen lain, pastikan bukti pemasangan disimpan sebelum penutupan.

Untuk logistik, baca artikel panel panjang, transport, dan layout sebelum memutuskan sambungan. Detail geometri dan rute harus konsisten. Cocokkan pula urutan pemasangan panel dengan [catatan urutan kerja](/artikel/urutan-pemasangan-panel-atap.html).

Simpan persetujuan detail bersama gambar yang dipakai untuk pemesanan. Perubahan kecil pada kemiringan atau panjang harus memicu pemeriksaan ulang.

Catat juga siapa yang memeriksa tumpuan dan kapan pemeriksaan dilakukan. Rekaman ini membantu ketika sambungan perlu ditinjau setelah cuaca buruk.

## Kesimpulan

End lap pada panel metal tergantung pada **slope, panjang atap, dan kondisi lokal**. Semakin landai, semakin besar end lap yang dibutuhkan. Spesifikasi pabrikan adalah acuan utama.

Langkah Anda selanjutnya: hitung kebutuhan end lap untuk proyek Anda berdasarkan slope dan panjang atap. Verifikasi dengan spesifikasi pabrikan. Pastikan end lap menghadap arah yang benar dan menggunakan sealant sebagai pengaman tambahan.

Batas pengetahuan ini adalah: nilai end lap spesifik harus mengikuti spesifikasi pabrikan dan disetujui oleh engineer.
