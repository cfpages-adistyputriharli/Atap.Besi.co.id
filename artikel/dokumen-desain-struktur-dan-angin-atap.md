---
article_id: RFM-07-A06
title: "Dokumen Desain Struktur dan Angin yang Harus Ada"
slug: "dokumen-desain-struktur-dan-angin-atap"
description: "Dokumen desain struktur dan angin yang harus ada sebelum pengadaan atap metal: dasar desain, geometri, zona beban, jalur beban, pengujian produk, dan tanda tangan persetujuan."
status: draft
publication_date: "2025-12-11"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: RFM-07
primary_intent: "Audit structural submittals"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/dokumen-desain-struktur-dan-angin-atap.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://pesta.bsn.go.id/produk/detail/12885-sni83692020"
  - "https://pesta.bsn.go.id/produk/detail/9714-sni79712013"
  - "https://store.astm.org/e1646-95r24.html"
  - "https://pesta.bsn.go.id/produk/detail/12927-sni17272020"
---

<!-- BEGIN MANAGED IMAGE PLAN
- **Image ID:** `LOCAL-001`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi atap seng gelombang warna](/wp-content/uploads/2026/03/atap-seng-gelombang-warna.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `atap seng gelombang warna` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Dokumen Desain Struktur dan Angin yang Harus Ada

Halo, Kawan Besi.co.id! Sebelum mengadakkan atau memasang atap metal, Anda perlu memastikan bahwa dokumen desain struktur dan beban angin sudah lengkap dan disetujui. Dokumen ini bukan sekadar formalitas; mereka adalah bukti bahwa atap dirancang untuk menahan beban yang akan diterimanya selama masa pakainya. Tanpa dokumen yang memadai, Anda berisiko memasang atap yang under-designed (tidak cukup kuat) atau over-designed (terlalu mahal), dan kedua situasi ini sama-sama merugikan.

Jawaban singkatnya: minimal Anda memerlukan design basis report, perhitungan struktural, gambar kerja, dan spesifikasi material yang sudah ditinjau dan disetujui oleh perancang berlisensi. PP No. 16 Tahun 2021 tentang Peraturan Pelaksanaan Undang-Undang tentang Jasa Konstruksi mengatur bahwa desain harus memenuhi standar teknis yang berlaku ([PP 16/2021](https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021)). Kekurangan dokumen bisa berarti desain tidak memenuhi regulasi, yang berisiko secara hukum dan keselamatan.

![Ilustrasi atap seng gelombang warna](/wp-content/uploads/2026/03/atap-seng-gelombang-warna.jpg)

*Ilustrasi umum dari aset lokal; bukan dokumentasi proyek tertentu.*

## Definisi dan batas objek

Artikel ini membahas dokumen desain struktur dan beban angin yang harus ada sebelum pengadaan dan pemasangan atap metal dimulai. Cakupannya meliputi dasar desain, parameter beban, zona angin, jalur beban (load path), pengujian produk, dukungan (supports), fastener, perhitungan, gambar, kondisi sementara (temporary states), revisi, dan tanda tangan persetujuan.

Artikel ini tidak membahas detail perhitungan struktural atau validasi teknis; itu domain dari insinyur sipil/struktur berlisensi. Untuk informasi tentang zona angin dan pengaruhnya terhadap desain, baca [Zona Angin Sudut Tepi Tengah Atap](/artikel/zona-angin-sudut-tepi-tengah-atap.html).

## Dasar desain yang harus terdefinisi

Design basis report adalah dokumen pertama yang harus ada. Dokumen ini mendefinisikan semua asumsi desain: lokasi proyek, ketinggian, exposure category (kategori paparan lingkungan), kecepatan angin desain, beban hujan, beban salju (jika relevan), suhu ekstrem, dan kategori bangunan. SNI 1729:2020 tentang ketentuan perencanaan struktur baja untuk bangunan gedung menetapkan metode desain yang harus diikuti ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

Selain itu, design basis harus mencantumkan standar dan kode yang digunakan sebagai referensi. Di Indonesia, ini biasanya meliputi SNI 1727:2020 untuk beban minimum ([SNI 1727:2020](https://pesta.bsn.go.id/produk/detail/12927-sni17272020)), SNI 1729:2020 untuk struktur baja, dan SNI 7971:2013 untuk struktur cold-formed ([SNI 7971:2013](https://pesta.bsn.go.id/produk/detail/9714-sni79712013)). Jika standar internasional juga digunakan (seperti ASCE 7 atau Eurocode), cantumkan juga.

## Parameter beban dan zona angin

Dokumen beban harus mendefinisikan semua beban yang akan diterima atap: beban angin (tekanan dan hisap), beban hujan, beban salju, beban akibat pekerja, dan beban akibat peralatan di atas atap. Untuk beban angin, dokumen harus membagi atap menjadi zona: sudut (corner), tepi (edge), dan tengah (interior). Setiap zona memiliki koefisien tekanan/hisap yang berbeda.

ASTM E1646-95(2024) menguji ketahanan atap terhadap air yang didorong angin, dan hasil pengujian ini harus menjadi referensi dalam desain ([ASTM E1646-95(2024)](https://store.astm.org/e1646-95r24.html)). Dokumen harus menunjukkan bahwa panel, fastener, dan segel yang dipilih sudah diuji untuk menahan beban angin di setiap zona.

## Jalur beban dan koneksi

Dokumen jalur beban (load path) harus menunjukkan bagaimana beban dari panel atap ditransfer ke struktur di bawahnya: dari panel ke purlin, dari purlin ke rangka utama (truss atau rangka portal), dari rangka ke kolom, dan dari kolom ke fondasi. Setiap koneksi dalam jalur ini harus dirancang dan didokumentasikan.

SNI 8369:2020 tentang cara uji kekakuan tekuk pelat memberikan metode pengujian yang relevan untuk panel ([SNI 8369:2020](https://pesta.bsn.go.id/produk/detail/12885-sni83692020)). Dokumen harus menunjukkan bahwa panel yang dipilih memiliki kekakuan yang memadai untuk rentang dan beban yang direncanakan.

Untuk memahami bagaimana beban angin bekerja pada panel, baca [Load Path Angin Atap Metal](/artikel/load-path-angin-atap-metal.html). Pemahaman tentang jalur beban membantu Anda memverifikasi bahwa desain benar-benar mentransfer beban dengan aman dari panel ke fondasi.

## Dokumen yang membuktikan hal berbeda

**Data produk (product data):** Lembar data teknis dari produsen yang menunjukkan spesifikasi material, dimensi profil, ketebalan, lapisan pelindung, dan kapasitas struktural.

**Sertifikat material:** Sertifikat uji dari laboratorium yang menunjukkan bahwa material memenuhi spesifikasi yang diklaim.

**Laporan tes:** Hasil pengujian beban angin, ketahanan air, atau performa lainnya yang dilakukan pada sistem atap yang dipilih.

**Gambar kerja:** Gambar detail yang menunjukkan layout panel, koneksi, flashing, penetrasi, dan detail lainnya.

**Perhitungan struktural:** Analisis dan perhitungan yang menunjukkan bahwa desain memenuhi kode dan standar yang berlaku.

## Pertanyaan wajib kepada penyedia

Ketika meminta penawaran atau submittal dari penyedia atap, ajukan pertanyaan berikut:

1. Apa dasar desain yang digunakan? Standar dan kode apa yang diikuti?
2. Zona angin mana yang dicakup oleh pengujian produk?
3. Berapa rentang maksimum yang diizinkan untuk panel yang ditawarkan?
4. Apakah perhitungan struktural sudah ditinjau oleh insinyur berlisensi?
5. Apa yang termasuk dalam scope pengujian produk?
6. Bagaimana kondisi sementara (selama pemasangan) ditangani dalam desain?

## Tanda bahaya dan biaya yang sering tersembunyi

**Tanda bahaya 1: Tidak ada design basis report.** Tanpa dokumen ini, tidak ada cara untuk memverifikasi bahwa desain sesuai dengan kondisi proyek Anda.

**Tanda bahaya 2: Perhitungan tanpa tanda tangan insinyur berlisensi.** Perhitungan yang tidak ditinjau dan disetujui oleh profesional yang berwenang tidak memiliki kekuatan hukum.

**Tanda bahaya 3: Data produk tanpa nomor laporan tes.** Klaim performa tanpa bukti pengujian tidak dapat diverifikasi.

**Biaya tersembunyi:** Biaya perubahan desain setelah submittal disetujui, biaya pengujian tambahan yang tidak termasuk dalam penawaran awal, dan biaya keterlambatan akibat submittal yang tidak lengkap.

Sobat Besi.co.id, perlu diingat bahwa kelengkapan dokumen bukan jaminan kualitas desain. Dokumen yang lengkap tetapi tidak ditinjau oleh profesional yang kompeten tetap berisiko. Pastikan setiap dokumen memiliki tanda tangan dan cap dari perancang yang berwenang.

## Penerimaan, serah terima, dan keputusan akhir

Proses penerimaan submittal harus melibatkan pengecekan kelengkapan, peninjauan teknis, dan persetujuan tertulis. Pengecekan kelengkapan memastikan semua dokumen yang dibutuhkan sudah diserahkan. Peninjauan teknis memastikan bahwa desain memenuhi kode dan standar yang berlaku. Persetujuan tertulis dari perancang berlisensi adalah langkah terakhir sebelum pengadaan dan pemasangan dimulai.

Teman Besi.co.id, jangan pernah memulai pemasangan tanpa submittal yang disetujui. Jika ada dokumen yang belum diserahkan atau belum disetujui, tunda pemasangan sampai semua dokumen lengkap.

## Objection atau jalan pintas yang perlu dijawab

Shortcut yang sering muncul: "Perhitungan dari produsen sudah cukup, tidak perlu peninjauan independen." Ini berbahaya karena perhitungan produsen mungkin tidak mempertimbangkan kondisi spesifik proyek Anda (lokasi, ketinggian, exposure). Produsen juga mungkin memiliki konflik kepentingan dalam merekomendasikan produk mereka.

Alternatif yang lebih aman: minta peninjauan independen oleh insinyur struktur yang tidak memiliki hubungan dengan produsen. Ini memastikan bahwa desain benar-benar sesuai dengan kebutuhan proyek Anda.

## Penutup

Kawan Besi.co.id, dokumen desain struktur dan beban angin adalah fondasi dari pemasangan atap metal yang aman dan tahan lama. Pastikan Anda memiliki design basis report, perhitungan struktural, gambar kerja, spesifikasi material, dan data pengujian produk yang sudah disetujui oleh perancang berlisensi sebelum memulai pengadaan dan pemasangan.

Langkah berikutnya: buat checklist submittal yang mencakup semua dokumen yang disebutkan di atas dan gunakan checklist ini untuk mengevaluasi setiap penawaran yang masuk. Batas yang jujur: kelengkapan dokumen tidak menggantikan penilaian profesional; pastikan setiap dokumen ditinjau oleh insinyur yang berwenang.
