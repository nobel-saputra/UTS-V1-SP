# UTS-V1-SP - Sistem Pakar dan Logika Fuzzy

Project ini berisi kumpulan implementasi sistem pakar dan logika fuzzy sebagai bagian dari Ujian Tengah Semester. Setiap notebook berisi implementasi dari metode yang berbeda dalam sistem kecerdasan buatan.

## Daftar Isi

- [Soal-1: Sistem Pakar Backward Chaining](#soal-1-sistem-pakar-backward-chaining)
- [Soal-2: Logika Fuzzy untuk Predikat Kelulusan Mahasiswa](#soal-2-logika-fuzzy-untuk-predikat-kelulusan-mahasiswa)
- [Soal-3: Sistem Diagnosis Hama dengan Certainty Factor](#soal-3-sistem-diagnosis-hama-dengan-certainty-factor)
- [Soal-4: Sistem Rekomendasi Laptop dengan Backward Chaining dan CF](#soal-4-sistem-rekomendasi-laptop-dengan-backward-chaining-dan-cf)
- [Soal-5: Fuzzy Mamdani untuk Kontrol Kecepatan Kipas Angin](#soal-5-fuzzy-mamdani-untuk-kontrol-kecepatan-kipas-angin)

## Soal-1: Sistem Pakar Backward Chaining

Soal-1 membahas tentang sistem pakar dengan metode backward chaining yang digunakan untuk mendiagnosis penyakit pada kucing berdasarkan gejala-gejala yang dialami. Program ini memungkinkan pengguna untuk memasukkan gejala yang dialami kucing, lalu sistem akan menelusuri aturan-aturan yang ada untuk menentukan apakah suatu penyakit terbukti atau tidak berdasarkan gejala tersebut.

Metode backward chaining bekerja dengan memulai dari tujuan (goal) yang ingin dibuktikan, lalu mencari aturan yang sesuai untuk membuktikan kebenaran tujuan tersebut berdasarkan fakta-fakta yang diketahui.

## Soal-2: Logika Fuzzy untuk Predikat Kelulusan Mahasiswa

Soal-2 merupakan implementasi sistem logika fuzzy untuk menentukan predikat kelulusan mahasiswa berdasarkan IPK dan jumlah publikasi. Sistem ini menggunakan fungsi keanggotaan trapesium dan segitiga untuk menghitung tingkat keanggotaan, lalu menerapkan metode inferensi Mamdani dan defuzzifikasi centroid untuk menghasilkan nilai crisp yang dapat diinterpretasikan ke dalam kategori kelulusan seperti Cum Laude, Sangat Memuaskan, atau Memuaskan.

Sistem ini berguna untuk menentukan predikat kelulusan mahasiswa berdasarkan dua parameter penting dalam dunia akademik.

## Soal-3: Sistem Diagnosis Hama dengan Certainty Factor

Soal-3 adalah sistem diagnosis hama pada tanaman menggunakan metode Certainty Factor (CF) yang membantu petani mengidentifikasi jenis hama berdasarkan gejala-gejala yang diamati. Program ini menghitung tingkat keyakinan terhadap berbagai kemungkinan hama berdasarkan input gejala dari pengguna dan memberikan rekomendasi tindakan berdasarkan nilai CF tertinggi yang dihasilkan.

Metode Certainty Factor digunakan untuk menangani ketidakpastian dalam sistem pakar, di mana setiap gejala diberi tingkat kepercayaan antara 0.0 hingga 1.0.

## Soal-4: Sistem Rekomendasi Laptop dengan Backward Chaining dan CF

Soal-4 mengimplementasikan sistem rekomendasi laptop menggunakan kombinasi backward chaining dan Certainty Factor untuk menentukan jenis laptop yang paling sesuai berdasarkan kebutuhan pengguna. Sistem ini mempertimbangkan berbagai kriteria seperti gaming, desain grafis, kebutuhan kantor, atau programming, lalu memberikan rekomendasi berdasarkan tingkat keyakinan terhadap setiap jenis laptop.

Sistem ini menggabungkan logika inferensi backward chaining dengan pendekatan Certainty Factor untuk memberikan rekomendasi yang lebih akurat dan dapat diinterpretasikan tingkat keyakinannya.

## Soal-5: Fuzzy Mamdani untuk Kontrol Kecepatan Kipas Angin

Soal-5 adalah implementasi sistem kontrol kecepatan kipas angin menggunakan logika fuzzy metode Mamdani dengan dua input (suhu dan kelembaban) dan satu output (kecepatan kipas). Sistem ini menggunakan fungsi keanggotaan trapesium dan segitiga serta beberapa aturan fuzzy untuk menentukan kecepatan kipas yang optimal berdasarkan kondisi lingkungan yang terdeteksi.

Sistem ini menunjukkan aplikasi logika fuzzy dalam sistem kontrol otomatis yang dapat menyesuaikan kecepatan kipas secara cerdas berdasarkan data sensor lingkungan.