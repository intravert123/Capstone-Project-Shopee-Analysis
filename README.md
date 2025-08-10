Capstone Project: Klasifikasi dan Ringkasan Ulasan Pelanggan Shopee Menggunakan IBM Granite
Project Overview
Proyek ini bertujuan untuk menganalisis data ulasan pelanggan dari platform e-commerce Shopee untuk mendapatkan wawasan berharga mengenai kepuasan pelanggan. Latar belakang masalah adalah tingginya volume ulasan yang masuk setiap hari, sehingga sulit bagi tim produk untuk menganalisisnya secara manual. Dengan memanfaatkan model AI Generatif dari IBM Granite, proyek ini melakukan dua tugas utama: (1) Klasifikasi Sentimen untuk secara otomatis mengkategorikan setiap ulasan, dan (2) Ringkasan Otomatis untuk mengekstrak inti keluhan dari ulasan negatif.

Raw Dataset Link
Nama Dataset: Shopee Review Dataset

Sumber: Kaggle

Link: https://www.kaggle.com/datasets/damarmustikoaji/shopee-review-dataset

Insight & Findings
Dari hasil analitis, dapat ditarik beberapa wawasan dan temuan penting:

Dominasi Masalah Fundamental: Sampel awal data menunjukkan bahwa keluhan pelanggan tidak bersifat sepele, melainkan menyentuh masalah fundamental pada pengalaman pengguna, baik dari sisi pembeli maupun penjual.

Identifikasi Titik Masalah Utama: Terdapat tiga area utama yang menjadi sumber kekecewaan pengguna:

Fitur Promosi & Voucher: Pengguna baru dan lama mengalami kesulitan dalam menggunakan promosi kunci seperti "gratis ongkir" dan "voucher pengguna baru," yang seharusnya menjadi daya tarik utama platform.

Sistem Penjual (Seller System): Penjual mengalami masalah serius terkait penarikan dana yang lambat, yang secara langsung berdampak pada kepercayaan dan operasional bisnis mereka di Shopee.

Fungsionalitas & Kejelasan Aplikasi: Ada keluhan umum mengenai aplikasi yang "tidak jelas" dan "membingungkan," yang menandakan adanya masalah pada desain antarmuka (UI) atau alur pengguna (UX).

Recommendations
Berdasarkan wawasan yang didapat, berikut adalah rekomendasi konkret dan dapat ditindaklanjuti untuk tim Shopee:

Prioritaskan Perbaikan Fitur Voucher (Untuk Tim Produk & Marketing):

Aksi: Segera lakukan audit dan usability testing pada alur klaim voucher, terutama untuk pengguna baru.

Tujuan: Menyederhanakan proses dan memastikan tidak ada bug yang menghalangi pengguna menikmati promosi, sehingga dapat meningkatkan akuisisi dan retensi pelanggan.

Percepat dan Transparansikan Proses Penarikan Dana (Untuk Tim Keuangan & Seller):

Aksi: Lakukan investigasi teknis untuk mengidentifikasi penyebab keterlambatan penarikan dana dan implementasikan solusi untuk transfer yang lebih cepat (real-time).

Tujuan: Meningkatkan kepercayaan dan kepuasan penjual, yang merupakan pilar penting dalam ekosistem e-commerce Shopee.

Lakukan Audit Pengalaman Pengguna (UX Audit) (Untuk Tim UI/UX):

Aksi: Analisis lebih dalam ulasan-ulasan yang mengeluhkan aplikasi "tidak jelas" untuk mengidentifikasi fitur atau alur mana yang paling bermasalah.

Tujuan: Memperbaiki desain antarmuka dan alur pengguna agar lebih intuitif, sehingga mengurangi frustrasi dan meningkatkan efisiensi pengguna dalam bertransaksi.

AI Support Explanation
Dalam proyek ini, AI (khususnya model IBM Granite) digunakan sebagai alat utama untuk analisis data teks melalui platform Replicate. Penggunaannya relevan karena kemampuannya memahami konteks dan nuansa bahasa manusia. Berikut adalah cara AI digunakan:

Untuk Klasifikasi Teks: Saya membuat prompt engineering yang menginstruksikan model untuk membaca setiap ulasan dan mengklasifikasikannya ke dalam kategori (Positif, Negatif, Netral).

Untuk Peringkasan Teks: Untuk ulasan yang telah diklasifikasikan, saya menggunakan prompt yang berbeda untuk meminta model merangkum poin inti dari ulasan tersebut dalam satu kalimat singkat.
